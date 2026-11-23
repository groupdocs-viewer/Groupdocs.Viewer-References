---
title: "MailStorageOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "Mail storage Lotus Notes MBox डेटा फ़ाइलों को रेंडर करने के लिए विकल्प प्रदान करता है।"
type: docs
weight: 19
url: /hi/java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

मेल स्टोरेज (Lotus Notes, MBox) डेटा फ़ाइलों को रेंडर करने के विकल्प प्रदान करता है।


MailStorageOptions क्लास विभिन्न सेटिंग्स और पैरामीटरों को समाहित करती है जिन्हें उपयोग किया जा सकता है।
GroupDocs.Viewer घटक में मेल स्टोरेज डेटा फ़ाइलों (जैसे Lotus Notes या MBox) के रेंडरिंग को नियंत्रित करने के लिए।


विवरण के लिए, देखें [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options)।


उदाहरण उपयोग:

````

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## Methods

| Method | विवरण |
| --- | --- |
|  | [getTextFilter()](#getTextFilter--) | संदेशों को फ़िल्टर करने के लिए उपयोग किए जाने वाले कीवर्ड प्राप्त करता है। |
|
|  | [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | संदेशों को फ़िल्टर करने के लिए उपयोग किए जाने वाले कीवर्ड सेट करता है। |
|
|  | [getAddressFilter()](#getAddressFilter--) | प्रेषक या प्राप्तकर्ता द्वारा संदेशों को फ़िल्टर करने के लिए उपयोग किया गया ईमेल पता प्राप्त करता है। |
|
|  | [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | प्रेषक या प्राप्तकर्ता द्वारा संदेशों को फ़िल्टर करने के लिए उपयोग किया गया ईमेल पता सेट करता है। |
|
|  | [getMaxItems()](#getMaxItems--) | रेंडर करने के लिए संदेशों या आइटमों की अधिकतम संख्या प्राप्त करता है। |
|
|  | [setMaxItems(int maxItems)](#setMaxItems-int-) | रेंडर करने के लिए संदेशों या आइटमों की अधिकतम संख्या सेट करता है। |
|
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


संदेशों को फ़िल्टर करने के लिए उपयोग किए जाने वाले कीवर्ड प्राप्त करता है।


विषय या बॉडी में विशिष्ट टेक्स्ट वाले सभी संदेशों को रेंडर करने के लिए इस प्रॉपर्टी का उपयोग करें। कोड उदाहरण के लिए, देखें [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages)।


**Returns:**
java.lang.String - संदेशों को फ़िल्टर करने के लिए उपयोग किए जाने वाले कीवर्ड।

### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


संदेशों को फ़िल्टर करने के लिए उपयोग किए जाने वाले कीवर्ड सेट करता है।


विषय या बॉडी में विशिष्ट टेक्स्ट वाले सभी संदेशों को रेंडर करने के लिए इस प्रॉपर्टी का उपयोग करें। कोड उदाहरण के लिए, देखें [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | textFilter | java.lang.String | संदेशों को फ़िल्टर करने के लिए उपयोग किए गए कीवर्ड। |
|

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


प्रेषक या प्राप्तकर्ता द्वारा संदेशों को फ़िल्टर करने के लिए उपयोग किया गया ईमेल पता प्राप्त करता है।


प्रेषक या प्राप्तकर्ता के पते में विशिष्ट टेक्स्ट वाले सभी संदेशों को रेंडर करने के लिए इस प्रॉपर्टी का उपयोग करें। कोड उदाहरण के लिए, देखें [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages)।


**Returns:**
java.lang.String - संदेशों को फ़िल्टर करने के लिए उपयोग किया गया ईमेल पता।

### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


प्रेषक या प्राप्तकर्ता द्वारा संदेशों को फ़िल्टर करने के लिए उपयोग किया गया ईमेल पता सेट करता है।


प्रेषक या प्राप्तकर्ता के पते में विशिष्ट टेक्स्ट वाले सभी संदेशों को रेंडर करने के लिए इस प्रॉपर्टी का उपयोग करें। कोड उदाहरण के लिए, देखें [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | addressFilter | java.lang.String | संदेशों को फ़िल्टर करने के लिए उपयोग किया गया ईमेल पता। |
|

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


रेंडर करने के लिए संदेशों या आइटमों की अधिकतम संख्या प्राप्त करता है।


Lotus Notes डेटा फ़ाइलें बड़ी हो सकती हैं, और सभी संदेशों को पुनः प्राप्त करने में काफी समय लग सकता है।
यह सेटिंग रेंडर किए जाने वाले संदेशों या आइटमों की अधिकतम संख्या को सीमित करती है।


***Note:** The default value is 0, which means all messages will be rendered.*
कोड उदाहरण के लिए, देखें [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render)।


**Returns:**
int - रेंडर करने के लिए संदेशों या आइटमों की अधिकतम संख्या।

### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


रेंडर करने के लिए संदेशों या आइटमों की अधिकतम संख्या सेट करता है।


Lotus Notes डेटा फ़ाइलें बड़ी हो सकती हैं, और सभी संदेशों को पुनः प्राप्त करने में काफी समय लग सकता है।
यह सेटिंग रेंडर किए जाने वाले संदेशों या आइटमों की अधिकतम संख्या को सीमित करती है।


***Note:** The default value is 0, which means all messages will be rendered.*
कोड उदाहरण के लिए, देखें [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | maxItems | int | रेंडर करने के लिए संदेशों या आइटमों की अधिकतम संख्या। |
|

