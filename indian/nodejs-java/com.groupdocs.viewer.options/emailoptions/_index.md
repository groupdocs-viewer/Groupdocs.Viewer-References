---
title: "EmailOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "ईमेल संदेशों को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 14
url: /hi/nodejs-java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

ईमेल संदेशों को रेंडर करने के विकल्प प्रदान करता है।

EmailOptions क्लास विभिन्न सेटिंग्स और पैरामीटर को संलग्न करता है जिन्हें GroupDocs.Viewer घटक में ईमेल संदेशों के रेंडरिंग को नियंत्रित करने के लिए उपयोग किया जा सकता है।

विवरण के लिए, देखें [documentation][].

उदाहरण उपयोग:

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
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [EmailOptions()](#EmailOptions--) | EmailOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getDateTimeFormat()](#getDateTimeFormat--) | तारीख और समय मानों के लिए समय प्रारूप प्राप्त करता है। |
| [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | तारीख और समय मानों के लिए समय प्रारूप प्राप्त करता है। |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | संदेश के लिए टाइम ज़ोन ऑफ़सेट प्राप्त करता है। |
| [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | संदेश के लिए टाइम ज़ोन मिनट ऑफ़सेट प्राप्त करता है। |
| [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | संदेश के लिए टाइम ज़ोन ऑफ़सेट प्राप्त करता है। |
| [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | संदेश के लिए टाइम ज़ोन ऑफ़सेट मिनट प्राप्त करता है। |
| [getPageSize()](#getPageSize--) | आउटपुट पेज का आकार प्राप्त करता है। |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | आउटपुट पेज का आकार प्राप्त करता है। |
| [getFieldTextMap()](#getFieldTextMap--) | ईमेल संदेश फ़ील्ड्स और उनके टेक्स्ट प्रतिनिधित्व के बीच मैपिंग प्राप्त करता है। |
| [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | ईमेल संदेश फ़ील्ड्स और उनके टेक्स्ट प्रतिनिधित्व के बीच मैपिंग सेट करता है। |
| [equals(Object o)](#equals-java.lang.Object-) | Object क्लास की equals() मेथड को ओवरराइड करता है। |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Object क्लास की toString() मेथड को ओवरराइड करता है। |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


EmailOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है। यह कंस्ट्रक्टर डिफ़ॉल्ट सेटिंग्स के साथ EmailOptions क्लास का नया इंस्टेंस बनाने के लिए उपयोग किया जाता है।

### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


तारीख और समय मानों के लिए समय प्रारूप प्राप्त करता है।

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.lang.String - तारीख और समय मानों के लिए समय प्रारूप।
### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


तारीख और समय मानों के लिए समय प्रारूप प्राप्त करता है।

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| dateTimeFormat | java.lang.String | तारीख और समय मानों के लिए समय प्रारूप। |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


संदेश के लिए टाइम ज़ोन ऑफ़सेट प्राप्त करता है।

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.util.TimeZone - टाइम ज़ोन ऑफ़सेट।
### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


संदेश के लिए टाइम ज़ोन मिनट ऑफ़सेट प्राप्त करता है।

**Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
int - टाइम ज़ोन ऑफ़सेट।
### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


संदेश के लिए टाइम ज़ोन ऑफ़सेट प्राप्त करता है।

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| timeZoneOffset | java.util.TimeZone | टाइम ज़ोन ऑफ़सेट। |

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


संदेश के लिए टाइम ज़ोन ऑफ़सेट मिनट प्राप्त करता है।

**Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| offsetMinutes | int | टाइम ज़ोन ऑफ़सेट। |

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


आउटपुट पेज का आकार प्राप्त करता है।

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


आउटपुट पेज का आकार प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | पेज का आकार। |

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


ईमेल संदेश फ़ील्ड्स और उनके टेक्स्ट प्रतिनिधित्व के बीच मैपिंग प्राप्त करता है।

**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - ईमेल संदेश फ़ील्ड्स और उनके टेक्स्ट प्रतिनिधित्व के बीच मैपिंग।
### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


ईमेल संदेश फ़ील्ड्स और उनके टेक्स्ट प्रतिनिधित्व के बीच मैपिंग सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | ईमेल संदेश फ़ील्ड्स और उनके टेक्स्ट प्रतिनिधित्व के बीच मैपिंग। |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Object क्लास की equals() मेथड को ओवरराइड करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| o | java.lang.Object | तुलना करने के लिए वस्तु। |

**Returns:**
boolean - यदि ऑब्जेक्ट समान हैं तो true, अन्यथा false।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस वस्तु के लिए हैश कोड मान की गणना करता है। हैश कोड वस्तु की आंतरिक स्थिति पर आधारित होता है और हैश-आधारित डेटा संरचनाओं जैसे हैश मैप और हैश सेट में उपयोग किया जाता है।

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - इस वस्तु के लिए हैश कोड मान।
### toString() {#toString--}
```
public String toString()
```


Object क्लास की toString() मेथड को ओवरराइड करता है।

**Returns:**
java.lang.String - ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व।
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


इस वस्तु का स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| शैली | org.apache.commons.lang3.builder.ToStringStyle | स्ट्रिंग प्रतिनिधित्व उत्पन्न करने के लिए उपयोग किया जाने वाला ToStringStyle। |

**Returns:**
java.lang.String - निर्दिष्ट ToStringStyle का उपयोग करके इस वस्तु का स्ट्रिंग प्रतिनिधित्व।
