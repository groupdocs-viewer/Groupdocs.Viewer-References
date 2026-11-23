---
title: "ArchiveSecurityOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "क्लास जो आर्काइव निकासी प्रक्रिया को सीमित करने के लिए उपयोग की जा सकती है।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

क्लास जो आर्काइव निकासी प्रक्रिया को सीमित करने के लिए उपयोग की जा सकती है।

ArchiveSecurityOptions क्लास आर्काइव्स के निष्कर्षण को सीमित करने और कुछ प्रतिबंध लागू करने का तरीका प्रदान करती है।

उदाहरण उपयोग:

```

 ArchiveSecurityOptions securityOptions = new ArchiveSecurityOptions();
 securityOptions.setMaxAllowedEntryNameLength(255);
 securityOptions.setMaxAllowedEntrySize(10737418240L);
 securityOptions.setMaxAllowedEntriesCount(1000);
 securityOptions.setMaxAllowedEntryCompressionRatio(100);

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setArchiveSecurityOptions(securityOptions);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     // Use the viewer object for archive document rendering
 }
 
```

***Note:** Not each archive type supports all options.*
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | यह विकल्प आर्काइव प्रविष्टि नाम की अधिकतम लंबाई निर्दिष्ट करता है। |
| [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | आर्काइव प्रविष्टि नामों के लिए अधिकतम अनुमत लंबाई सेट करता है। |
| [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | आर्काइव प्रविष्टियों के लिए अधिकतम अनुमत आकार प्राप्त करता है। |
| [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | आर्काइव प्रविष्टियों के लिए अधिकतम अनुमत आकार सेट करता है। |
| [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | आर्काइव में प्रविष्टियों की अधिकतम अनुमत गिनती प्राप्त करता है। |
| [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | आर्काइव में प्रविष्टियों की अधिकतम अनुमत गिनती सेट करता है। |
| [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | आर्काइव प्रविष्टियों को निकालने के लिए अधिकतम संपीड़न अनुपात निर्दिष्ट करता है। |
| [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | आर्काइव प्रविष्टियों को निकालने के लिए अधिकतम संपीड़न अनुपात निर्दिष्ट करता है। |
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


यह विकल्प आर्काइव प्रविष्टि नाम की अधिकतम लंबाई निर्दिष्ट करता है। यदि कोई प्रविष्टि नाम इस सीमा से अधिक हो जाता है, तो यह त्रुटि उत्पन्न करेगा।

***Note:** The default value for this option is 255.*

**Returns:**
int - आर्काइव प्रविष्टि नामों की अधिकतम अनुमत लंबाई।
### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


आर्काइव एंट्री नामों की अधिकतम अनुमत लंबाई सेट करता है। अधिकतम अनुमत लंबाई आर्काइव एंट्री नाम की लंबाई की सीमा निर्धारित करती है। यदि एंट्री नाम की लंबाई इस सीमा से अधिक हो जाती है, तो यह त्रुटि उत्पन्न करेगा।

***Note:** The default value for the maximum allowed entry name length is 255.*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxAllowedEntryNameLength | int | सेट की जाने वाली अधिकतम आर्काइव एंट्री नाम लंबाई। |

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


आर्काइव एंट्रीज़ के लिए अधिकतम अनुमत आकार प्राप्त करता है। अधिकतम अनुमत एंट्री आकार आर्काइव एंट्री के आकार की सीमा निर्धारित करता है। यदि एंट्री का आकार इस सीमा से अधिक हो जाता है, तो यह त्रुटि का परिणाम देगा।

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Returns:**
long - अधिकतम आर्काइव एंट्री आकार।
### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


आर्काइव एंट्रीज़ के लिए अधिकतम अनुमत आकार सेट करता है। अधिकतम अनुमत एंट्री आकार आर्काइव एंट्री के आकार की सीमा निर्धारित करता है। यदि एंट्री का आकार इस सीमा से अधिक हो जाता है, तो यह त्रुटि का परिणाम देगा।

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxAllowedEntrySize | long | अधिकतम आर्काइव एंट्री आकार। |

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


आर्काइव में एंट्रीज़ की अधिकतम अनुमत संख्या प्राप्त करता है। अधिकतम अनुमत एंट्री संख्या आर्काइव में मौजूद एंट्रीज़ की संख्या की सीमा निर्धारित करती है। यदि आर्काइव इस सीमा से अधिक एंट्रीज़ रखता है, तो उसे निकाला नहीं जा सकता।

***Note:** The default value for the maximum allowed entries count is 1000.*

**Returns:**
long - आर्काइव में एंट्रीज़ की अधिकतम संख्या।
### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


आर्काइव में एंट्रीज़ की अधिकतम अनुमत संख्या सेट करता है। अधिकतम अनुमत एंट्री संख्या आर्काइव में मौजूद एंट्रीज़ की संख्या की सीमा निर्धारित करती है। यदि आर्काइव इस सीमा से अधिक एंट्रीज़ रखता है, तो उसे निकाला नहीं जा सकता।

***Note:** The default value for the maximum allowed entries count is 1000.*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxAllowedEntriesCount | long | आर्काइव में एंट्रीज़ की अधिकतम संख्या। |

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


आर्काइव प्रविष्टियों को निकालने के लिए अधिकतम संपीड़न अनुपात निर्दिष्ट करता है।

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Returns:**
double - आर्काइव एंट्रीज़ के लिए अधिकतम अनुमत संपीड़न अनुपात।
### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


आर्काइव प्रविष्टियों को निकालने के लिए अधिकतम संपीड़न अनुपात निर्दिष्ट करता है।

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxAllowedEntryCompressionRatio | double | आर्काइव एंट्रीज़ के लिए अधिकतम अनुमत संपीड़न अनुपात। |

