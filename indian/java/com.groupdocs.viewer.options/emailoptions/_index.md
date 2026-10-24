---
title: "EmailOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "ईमेल संदेशों को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

ईमेल संदेशों को रेंडर करने के विकल्प प्रदान करता है।


EmailOptions क्लास विभिन्न सेटिंग्स और पैरामीटरों को समाहित करती है जिन्हें उपयोग किया जा सकता है
GroupDocs.Viewer घटक में ईमेल संदेशों के रेंडरिंग को नियंत्रित करने के लिए।


विवरण के लिए, देखें [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


उदाहरण उपयोग:

````

 EmailOptions options = new EmailOptions();
 options.setDateTimeFormat("MM d yyyy HH:mm tt");
 options.setPageSize(PageSize.A4);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setEmailOptions(options);

 try (Viewer viewer = new Viewer("email.msg")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [EmailOptions()](#EmailOptions--) | नए उदाहरण को प्रारंभ करता है |
EmailOptions
class।
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [getDateTimeFormat()](#getDateTimeFormat--) | तारीख और समय मानों के लिए समय प्रारूप प्राप्त करता है। |
|
|  | [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | तारीख और समय मानों के लिए समय प्रारूप प्राप्त करता है। |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | संदेश के लिए टाइम ज़ोन ऑफ़सेट प्राप्त करता है। |
|
|  | [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | संदेश के लिए टाइम ज़ोन मिनटों का ऑफ़सेट प्राप्त करता है। |
|
|  | [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | संदेश के लिए टाइम ज़ोन ऑफ़सेट प्राप्त करता है। |
|
|  | [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | संदेश के लिए समय क्षेत्र ऑफ़सेट मिनट प्राप्त करता है। |
|
|  | [getPageSize()](#getPageSize--) | आउटपुट पृष्ठ का आकार प्राप्त करता है। |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | आउटपुट पृष्ठ का आकार प्राप्त करता है। |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | ईमेल संदेश फ़ील्ड और उनके टेक्स्ट प्रतिनिधित्व के बीच मैपिंग पुनः प्राप्त करता है। |
|
|  | [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | ईमेल संदेश फ़ील्ड और उनके टेक्स्ट प्रतिनिधित्व के बीच मैपिंग सेट करता है। |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Object क्लास की equals() मेथड को ओवरराइड करता है। |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | Object क्लास की toString() मेथड को ओवरराइड करता है। |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


नए उदाहरण को प्रारंभ करता है
EmailOptions
class।
यह कंस्ट्रक्टर नई इंस्टेंस बनाने के लिए उपयोग किया जाता है।
EmailOptions
डिफ़ॉल्ट सेटिंग्स के साथ क्लास।


### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


तारीख और समय मानों के लिए समय प्रारूप प्राप्त करता है।
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
यदि समय प्रारूप सेट नहीं है, तो वर्तमान सिस्टम प्रारूप उपयोग किया जाएगा।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.lang.String - तारीख और समय मानों के लिए समय प्रारूप।

### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


तारीख और समय मानों के लिए समय प्रारूप प्राप्त करता है।
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
यदि समय प्रारूप सेट नहीं है, तो वर्तमान सिस्टम प्रारूप उपयोग किया जाएगा।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | dateTimeFormat | java.lang.String | तारीख और समय मानों के लिए समय प्रारूप। |
|

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


संदेश के लिए टाइम ज़ोन ऑफ़सेट प्राप्त करता है।
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.util.TimeZone - समय क्षेत्र ऑफ़सेट।

### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


संदेश के लिए टाइम ज़ोन मिनटों का ऑफ़सेट प्राप्त करता है।
***Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC).
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
int - समय क्षेत्र ऑफ़सेट।

### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


संदेश के लिए टाइम ज़ोन ऑफ़सेट प्राप्त करता है।
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | timeZoneOffset | java.util.TimeZone | समय क्षेत्र ऑफ़सेट। |
|

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


संदेश के लिए समय क्षेत्र ऑफ़सेट मिनट प्राप्त करता है।
***Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | offsetMinutes | int | समय क्षेत्र ऑफ़सेट। |
|

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


आउटपुट पृष्ठ का आकार प्राप्त करता है।


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


आउटपुट पृष्ठ का आकार प्राप्त करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | पृष्ठ का आकार। |
|

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


ईमेल संदेश फ़ील्ड और उनके टेक्स्ट प्रतिनिधित्व के बीच मैपिंग पुनः प्राप्त करता है।


**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - ईमेल संदेश फ़ील्ड और उनके टेक्स्ट प्रतिनिधित्व के बीच मैपिंग।

### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


ईमेल संदेश फ़ील्ड और उनके टेक्स्ट प्रतिनिधित्व के बीच मैपिंग सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | ईमेल संदेश फ़ील्ड और उनके टेक्स्ट प्रतिनिधित्व के बीच मैपिंग। |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Object क्लास की equals() मेथड को ओवरराइड करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | o | java.lang.Object | तुलना करने के लिए वस्तु। |
|

**Returns:**
boolean - true यदि वस्तुएँ समान हैं, false अन्यथा।

### hashCode() {#hashCode--}
```
public int hashCode()
```


इस वस्तु के लिए हैश कोड मान की गणना करता है। हैश कोड आधारित है
वस्तु की आंतरिक स्थिति पर और हैश-आधारित डेटा संरचनाओं में उपयोग किया जाता है
जैसे हैश मैप और हैश सेट।
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


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
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | स्टाइल | org.apache.commons.lang3.builder.ToStringStyle | स्ट्रिंग प्रतिनिधित्व उत्पन्न करने के लिए उपयोग करने वाला ToStringStyle। |
|

**Returns:**
java.lang.String - निर्दिष्ट ToStringStyle का उपयोग करके इस वस्तु का स्ट्रिंग प्रतिनिधित्व।

