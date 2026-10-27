---
title: "Security"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "PDF belge güvenlik seçenekleri sağlar."
type: docs
weight: 29
url: /tr/nodejs-java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

PDF belge güvenlik seçenekleri sağlar.

Security sınıfı, GroupDocs.Viewer bileşenindeki bir PDF belgesine güvenlik önlemleri uygulamak için kullanılabilecek çeşitli ayar ve seçenekleri kapsar. Bu seçenekler arasında şifre koruması, izinler ve daha fazlası bulunur. Ayrıntılar için [documentation][].

Örnek kullanım:

```

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Security()](#Security--) | Security sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDocumentOpenPassword()](#getDocumentOpenPassword--) | PDF belgesini açmak için gereken şifreyi alır. |
| [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | PDF belgesini açmak için gereken şifreyi ayarlar. |
| [getPermissionsPassword()](#getPermissionsPassword--) | İzin ayarlarını değiştirmek için gereken şifreyi alır. |
| [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | İzin ayarlarını değiştirmek için gereken şifreyi ayarlar. |
| [getPermissions()](#getPermissions--) | PDF belge izinlerini, örneğin yazdırma, değiştirme ve veri çıkarma gibi, alır. |
| [setPermissions(int value)](#setPermissions-int-) | PDF belge izinlerini, örneğin yazdırma, değiştirme ve veri çıkarma gibi, ayarlar. |
### Security() {#Security--}
```
public Security()
```


Security sınıfının yeni bir örneğini başlatır.

### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


PDF belgesini açmak için gereken şifreyi alır.

Kod örneği için, [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - belge açma parolası.
### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


PDF belgesini açmak için gereken şifreyi ayarlar.

Kod örneği için, [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String | Belge açma parolası. |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


İzin ayarlarını değiştirmek için gereken şifreyi alır.

İzin parolası kullanarak, yazdırma, değiştirme ve veri çıkarma işlemlerini kısıtlayabilirsiniz. Yazdırma, değiştirme ve veri çıkarma işlemlerini kısıtlamak için bir izin parolası kullanın. Kod örneği için, [documentation][] bakın.


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - izin parolası.
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


İzin ayarlarını değiştirmek için gereken şifreyi ayarlar.

İzin parolası kullanarak, yazdırma, değiştirme ve veri çıkarma işlemlerini kısıtlayabilirsiniz. Yazdırma, değiştirme ve veri çıkarma işlemlerini kısıtlamak için bir izin parolası kullanın. Kod örneği için, [documentation][] bakın.


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String | İzin parolası. |

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


PDF belge izinlerini, örneğin yazdırma, değiştirme ve veri çıkarma gibi, alır.

Kod örneği için, [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
int - PDF belge izinleri.
### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


PDF belge izinlerini, örneğin yazdırma, değiştirme ve veri çıkarma gibi, ayarlar.

Kod örneği için, [documentation][] sayfasına bakın.


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int | PDF belge izinleri. |

