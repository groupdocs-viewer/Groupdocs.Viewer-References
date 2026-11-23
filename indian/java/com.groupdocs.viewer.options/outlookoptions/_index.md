---
title: "OutlookOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "Outlook डेटा फ़ाइलों को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 20
url: /hi/java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Outlook डेटा फ़ाइलों को रेंडर करने के विकल्प प्रदान करता है।


OutlookOptions क्लास विभिन्न सेटिंग्स और पैरामीटरों को समाहित करती है जिन्हें उपयोग किया जा सकता है
GroupDocs.Viewer घटक में Outlook डेटा फ़ाइलों (जैसे PST या OST फ़ाइलें) के रेंडरिंग को नियंत्रित करने के लिए।


विवरण के लिए, देखें [दस्तावेज़](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options)।


उदाहरण उपयोग:

````

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## Methods

| Method | विवरण |
| --- | --- |
|  | [getFolder()](#getFolder--) | फ़ोल्डर को रेंडर करने के लिए नाम प्राप्त करता है। |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | फ़ोल्डर को रेंडर करने के लिए नाम सेट करता है। |
|
|  | [getTextFilter()](#getTextFilter--) | संदेशों को फ़िल्टर करने के लिए उपयोग किए जाने वाले कीवर्ड प्राप्त करता है। |
|
|  | [setTextFilter(String value)](#setTextFilter-java.lang.String-) | संदेशों को फ़िल्टर करने के लिए उपयोग किए जाने वाले कीवर्ड प्राप्त करता है। |
|
|  | [getAddressFilter()](#getAddressFilter--) | प्रेषक या प्राप्तकर्ता द्वारा संदेशों को फ़िल्टर करने के लिए उपयोग किया गया ईमेल पता प्राप्त करता है। |
|
|  | [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | प्रेषक या प्राप्तकर्ता द्वारा संदेशों को फ़िल्टर करने के लिए उपयोग किया गया ईमेल पता सेट करता है। |
|
|  | [getMaxItemsInFolder()](#getMaxItemsInFolder--) | एक फ़ोल्डर से रेंडर किए जा सकने वाले संदेशों या आइटमों की अधिकतम संख्या प्राप्त करता है। |
|
|  | [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | एक फ़ोल्डर से रेंडर किए जा सकने वाले संदेशों या आइटमों की अधिकतम संख्या सेट करता है। |
|
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


फ़ोल्डर को रेंडर करने के लिए नाम प्राप्त करता है।
रेंडर करने के लिए फ़ोल्डर (जैसे, Inbox, Sent Item, या Deleted Items) का नाम।


जब Outlook डेटा फ़ाइल को रेंडर किया जाता है, तो GroupDocs.Viewer फ़ाइल में मौजूद सभी फ़ोल्डरों (नेस्टेड फ़ोल्डरों सहित) से संदेश रेंडर करता है। किसी विशिष्ट फ़ोल्डर से आइटम रेंडर करने के लिए इस प्रॉपर्टी का उपयोग करें।
कोड उदाहरण के लिए, इस [डॉक्यूमेंटेशन](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder) को देखें।


**Returns:**
java.lang.String - रेंडर करने के लिए फ़ोल्डर का नाम।

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


फ़ोल्डर को रेंडर करने के लिए नाम सेट करता है।
रेंडर करने के लिए फ़ोल्डर (जैसे, Inbox, Sent Item, या Deleted Items) का नाम।


जब Outlook डेटा फ़ाइल को रेंडर किया जाता है, तो GroupDocs.Viewer फ़ाइल में मौजूद सभी फ़ोल्डरों (नेस्टेड फ़ोल्डरों सहित) से संदेश रेंडर करता है। किसी विशिष्ट फ़ोल्डर से आइटम रेंडर करने के लिए इस प्रॉपर्टी का उपयोग करें।
कोड उदाहरण के लिए, इस [डॉक्यूमेंटेशन](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder) को देखें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | रेंडर करने के लिए फ़ोल्डर का नाम। |
|

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


संदेशों को फ़िल्टर करने के लिए उपयोग किए जाने वाले कीवर्ड प्राप्त करता है।


विषय या बॉडी में विशिष्ट टेक्स्ट वाले सभी संदेशों को रेंडर करने के लिए इस प्रॉपर्टी का उपयोग करें। कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages) देखें।


**Returns:**
java.lang.String - कीवर्ड्स।

### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


संदेशों को फ़िल्टर करने के लिए उपयोग किए जाने वाले कीवर्ड प्राप्त करता है।


विषय या बॉडी में विशिष्ट टेक्स्ट वाले सभी संदेशों को रेंडर करने के लिए इस प्रॉपर्टी का उपयोग करें। कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages) देखें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | कीवर्ड्स। |
|

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


प्रेषक या प्राप्तकर्ता द्वारा संदेशों को फ़िल्टर करने के लिए उपयोग किया गया ईमेल पता प्राप्त करता है।


प्रेषक\\ufffds या प्राप्तकर्ता\\ufffds पते में विशिष्ट टेक्स्ट वाले सभी संदेशों को रेंडर करने के लिए इस प्रॉपर्टी का उपयोग करें। कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages) देखें।


**Returns:**
java.lang.String - संदेशों को फ़िल्टर करने के लिए उपयोग किया गया ईमेल पता।

### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


प्रेषक या प्राप्तकर्ता द्वारा संदेशों को फ़िल्टर करने के लिए उपयोग किया गया ईमेल पता सेट करता है।


प्रेषक\\ufffds या प्राप्तकर्ता\\ufffds पते में विशिष्ट टेक्स्ट वाले सभी संदेशों को रेंडर करने के लिए इस प्रॉपर्टी का उपयोग करें। कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages) देखें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | संदेशों को फ़िल्टर करने के लिए उपयोग किया गया ईमेल पता। |
|

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


एक फ़ोल्डर से रेंडर किए जा सकने वाले संदेशों या आइटमों की अधिकतम संख्या प्राप्त करता है।


Outlook डेटा फ़ाइलें बड़ी हो सकती हैं और सभी संदेशों को प्राप्त करने में काफी समय लग सकता है।
यह सेटिंग रेंडर किए जाने वाले संदेशों या आइटमों (जैसे संपर्क और कार्य) की अधिकतम संख्या को सीमित करती है।
डिफ़ॉल्ट मान 50 है। सभी संदेशों को रेंडर करने के लिए मान को 0 सेट करें।
कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render) देखें।


**Returns:**
int - एक फ़ोल्डर से रेंडर किए जा सकने वाले संदेशों या आइटमों की अधिकतम संख्या।

### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


एक फ़ोल्डर से रेंडर किए जा सकने वाले संदेशों या आइटमों की अधिकतम संख्या सेट करता है।


Outlook डेटा फ़ाइलें बड़ी हो सकती हैं और सभी संदेशों को प्राप्त करने में काफी समय लग सकता है।
यह सेटिंग रेंडर किए जाने वाले संदेशों या आइटमों (जैसे संपर्क और कार्य) की अधिकतम संख्या को सीमित करती है।
डिफ़ॉल्ट मान 50 है। सभी संदेशों को रेंडर करने के लिए मान को 0 सेट करें।
कोड उदाहरण के लिए, [डॉक्यूमेंटेशन](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render) देखें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | int | एक फ़ोल्डर से रेंडर किए जा सकने वाले संदेशों या आइटमों की अधिकतम संख्या। |
|

