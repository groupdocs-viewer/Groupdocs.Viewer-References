---
title: "Security"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "PDF belge güvenlik seçeneklerini sağlar."
type: docs
weight: 29
url: /tr/java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

PDF belge güvenlik seçeneklerini sağlar.


Security sınıfı, güvenlik önlemlerini uygulamak için kullanılabilecek çeşitli ayar ve seçenekleri kapsar
GroupDocs.Viewer bileşenindeki bir PDF belgesine. Bu seçenekler şifre korumasını içerir,
izinler ve daha fazlası.
Ayrıntılar için [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/) bağlantısına bakın.


Örnek kullanım:

````

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [Security()](#Security--) | Yeni bir örnek başlatır |
Security
sınıf.
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getDocumentOpenPassword()](#getDocumentOpenPassword--) | PDF belgesini açmak için gereken şifreyi alır. |
|
|  | [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | PDF belgesini açmak için gereken şifreyi ayarlar. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | İzin ayarlarını değiştirmek için gereken şifreyi alır. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | İzin ayarlarını değiştirmek için gereken şifreyi ayarlar. |
|
|  | [getPermissions()](#getPermissions--) | PDF belgesi izinlerini, örneğin yazdırma, değiştirme ve veri çıkarma gibi, alır. |
|
|  | [setPermissions(int value)](#setPermissions-int-) | PDF belgesi izinlerini, örneğin yazdırma, değiştirme ve veri çıkarma gibi, ayarlar. |
|
### Security() {#Security--}
```
public Security()
```


Yeni bir örnek başlatır
Security
sınıf.


### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


PDF belgesini açmak için gereken şifreyi alır.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/) bölümüne bakın.


**Returns:**
java.lang.String - belge açma şifresi.

### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


PDF belgesini açmak için gereken şifreyi ayarlar.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/) bölümüne bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | Belge açma şifresi. |
|

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


İzin ayarlarını değiştirmek için gereken şifreyi alır.


İzin şifresi kullanarak, yazdırma, değiştirme ve veri çıkarma işlemlerini kısıtlayabilirsiniz.
Yazdırma, değiştirme ve veri çıkarma işlemlerini kısıtlamak için bir izin şifresi kullanın. Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/) bölümüne bakın.


**Returns:**
java.lang.String - izin şifresi.

### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


İzin ayarlarını değiştirmek için gereken şifreyi ayarlar.


İzin şifresi kullanarak, yazdırma, değiştirme ve veri çıkarma işlemlerini kısıtlayabilirsiniz.
Yazdırma, değiştirme ve veri çıkarma işlemlerini kısıtlamak için bir izin şifresi kullanın. Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/) bölümüne bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | java.lang.String | İzin şifresi. |
|

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


PDF belgesi izinlerini, örneğin yazdırma, değiştirme ve veri çıkarma gibi, alır.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/) bölümüne bakın.


**Returns:**
int - PDF belge izinleri.

### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


PDF belgesi izinlerini, örneğin yazdırma, değiştirme ve veri çıkarma gibi, ayarlar.


Kod örneği için, [belgelendirme](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/) bölümüne bakın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | int | PDF belge izinleri. |
|

