---
title: "EmailOptions"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "E-posta mesajlarını renderleme seçeneklerini sağlar."
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

E-posta mesajlarını renderleme seçeneklerini sağlar.

EmailOptions sınıfı, GroupDocs.Viewer bileşeninde e-posta mesajlarının işlenmesini kontrol etmek için kullanılabilecek çeşitli ayarları ve parametreleri kapsar.

Ayrıntılar için, [documentation][].

Örnek kullanım:

```

 EmailOptions options = new EmailOptions();
 options.setDateTimeFormat("MM d yyyy HH:mm tt");
 options.setPageSize(PageSize.A4);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setEmailOptions(options);

 try (Viewer viewer = new Viewer("email.msg")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmailOptions()](#EmailOptions--) | EmailOptions sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDateTimeFormat()](#getDateTimeFormat--) | Tarih ve saat değerleri için zaman biçimini alır. |
| [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | Tarih ve saat değerleri için zaman biçimini alır. |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | Mesaj için saat dilimi ofsetini alır. |
| [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | Mesaj için saat dilimi dakikası ofsetini alır. |
| [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | Mesaj için saat dilimi ofsetini alır. |
| [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | Mesaj için saat dilimi dakikası ofsetini alır. |
| [getPageSize()](#getPageSize--) | Çıktı sayfasının boyutunu alır. |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Çıktı sayfasının boyutunu alır. |
| [getFieldTextMap()](#getFieldTextMap--) | E-posta mesajı alanları ile bunların metin temsilleri arasındaki eşlemeyi alır. |
| [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | E-posta mesajı alanları ile bunların metin temsilleri arasındaki eşlemeyi ayarlar. |
| [equals(Object o)](#equals-java.lang.Object-) | Object sınıfının equals() metodunu geçersiz kılar. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Object sınıfının toString() metodunu geçersiz kılar. |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


EmailOptions sınıfının yeni bir örneğini başlatır. Bu yapıcı, varsayılan ayarlarla EmailOptions sınıfının yeni bir örneğini oluşturmak için kullanılır.

### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


Tarih ve saat değerleri için zaman biçimini alır.

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.lang.String - tarih ve saat değerleri için zaman biçimi.
### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


Tarih ve saat değerleri için zaman biçimini alır.

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dateTimeFormat | java.lang.String | Tarih ve saat değerleri için zaman biçimi. |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


Mesaj için saat dilimi ofsetini alır.

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.util.TimeZone - saat dilimi ofseti.
### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


Mesaj için saat dilimi dakikası ofsetini alır.

**Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
int - saat dilimi ofseti.
### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


Mesaj için saat dilimi ofsetini alır.

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| timeZoneOffset | java.util.TimeZone | Saat dilimi ofseti. |

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


Mesaj için saat dilimi dakikası ofsetini alır.

**Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| offsetMinutes | int | Saat dilimi ofseti. |

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Çıktı sayfasının boyutunu alır.

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Çıktı sayfasının boyutunu alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Sayfa boyutu. |

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


E-posta mesajı alanları ile bunların metin temsilleri arasındaki eşlemeyi alır.

**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - e-posta mesajı alanları ile bunların metin temsilleri arasındaki eşleme.
### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


E-posta mesajı alanları ile bunların metin temsilleri arasındaki eşlemeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | E-posta mesajı alanları ile metin temsilleri arasındaki eşleme. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Object sınıfının equals() metodunu geçersiz kılar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| o | java.lang.Object | Karşılaştırılacak nesne. |

**Returns:**
boolean - nesneler eşitse true, aksi takdirde false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu nesne için hash kod değerini hesaplar. Hash kod, nesnenin iç durumuna dayanır ve hash haritaları ve hash kümeleri gibi hash tabanlı veri yapılarında kullanılır.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - bu nesne için hash kod değeri.
### toString() {#toString--}
```
public String toString()
```


Object sınıfının toString() metodunu geçersiz kılar.

**Returns:**
java.lang.String - nesnenin string temsili.
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Bu nesnenin bir dize temsilini döndürür.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stil | org.apache.commons.lang3.builder.ToStringStyle | Dize temsilini oluşturmak için kullanılacak ToStringStyle. |

**Returns:**
java.lang.String - belirtilen ToStringStyle kullanılarak bu nesnenin bir dize temsili.
