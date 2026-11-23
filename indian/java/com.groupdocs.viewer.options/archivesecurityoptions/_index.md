---
title: "ArchiveSecurityOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "क्लास जिसका उपयोग अभिलेखों के निष्कर्षण प्रक्रिया को सीमित करने के लिए किया जा सकता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

क्लास जिसका उपयोग अभिलेखों के निष्कर्षण प्रक्रिया को सीमित करने के लिए किया जा सकता है।

ArchiveSecurityOptions क्लास आर्काइव के निष्कर्षण को सीमित करने और कुछ प्रतिबंध लागू करने का तरीका प्रदान करती है।

उदाहरण उपयोग:

````

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
 
````


***Note:** Not each archive type supports all options.*

## Constructors

| Constructor | विवरण |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Methods

| Method | विवरण |
| --- | --- |
|  | [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | यह विकल्प एक आर्काइव प्रविष्टि नाम की अधिकतम लंबाई निर्दिष्ट करता है। |
|
|  | [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | आर्काइव प्रविष्टि नामों के लिए अधिकतम अनुमत लंबाई सेट करता है। |
|
|  | [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | आर्काइव प्रविष्टियों के लिए अधिकतम अनुमत आकार प्राप्त करता है। |
|
|  | [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | आर्काइव प्रविष्टियों के लिए अधिकतम अनुमत आकार सेट करता है। |
|
|  | [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | आर्काइव में प्रविष्टियों की अधिकतम अनुमत संख्या प्राप्त करता है। |
|
|  | [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | आर्काइव में प्रविष्टियों की अधिकतम अनुमत संख्या सेट करता है। |
|
|  | [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | आर्काइव प्रविष्टियों को निकालने के लिए अनुमत अधिकतम संपीड़न अनुपात निर्दिष्ट करता है। |
|
|  | [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | आर्काइव प्रविष्टियों को निकालने के लिए अनुमत अधिकतम संपीड़न अनुपात निर्दिष्ट करता है। |
|
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


यह विकल्प एक आर्काइव प्रविष्टि नाम की अधिकतम लंबाई निर्दिष्ट करता है।
यदि कोई प्रविष्टि नाम इस सीमा से अधिक हो जाता है, तो यह त्रुटि उत्पन्न करेगा।


***Note:** The default value for this option is 255.*


**Returns:**
int - आर्काइव प्रविष्टि नामों के लिए अधिकतम अनुमत लंबाई।

### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


आर्काइव प्रविष्टि नामों के लिए अधिकतम अनुमत लंबाई सेट करता है।
अधिकतम अनुमत लंबाई एक आर्काइव प्रविष्टि नाम की लंबाई की सीमा निर्दिष्ट करती है।
यदि प्रविष्टि नाम की लंबाई इस सीमा से अधिक हो जाती है, तो यह त्रुटि उत्पन्न करेगा।


***Note:** The default value for the maximum allowed entry name length is 255.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | maxAllowedEntryNameLength | int | सेट करने के लिए अधिकतम आर्काइव प्रविष्टि नाम लंबाई। |
|

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


आर्काइव प्रविष्टियों के लिए अधिकतम अनुमत आकार प्राप्त करता है।
अधिकतम अनुमत प्रविष्टि आकार एक आर्काइव प्रविष्टि के आकार की सीमा निर्दिष्ट करता है।
यदि किसी प्रविष्टि का आकार इस सीमा से अधिक हो जाता है, तो यह त्रुटि का परिणाम देगा।


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Returns:**
long - अधिकतम अभिलेख प्रविष्टि आकार।

### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


आर्काइव प्रविष्टियों के लिए अधिकतम अनुमत आकार सेट करता है।
अधिकतम अनुमत प्रविष्टि आकार एक आर्काइव प्रविष्टि के आकार की सीमा निर्दिष्ट करता है।
यदि किसी प्रविष्टि का आकार इस सीमा से अधिक हो जाता है, तो यह त्रुटि का परिणाम देगा।


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | maxAllowedEntrySize | long | अधिकतम अभिलेख प्रविष्टि आकार। |
|

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


आर्काइव में प्रविष्टियों की अधिकतम अनुमत संख्या प्राप्त करता है।
अधिकतम अनुमत प्रविष्टियों की गिनती यह निर्धारित करती है कि एक अभिलेख में कितनी प्रविष्टियाँ हो सकती हैं।
यदि किसी अभिलेख में इस सीमा से अधिक प्रविष्टियाँ हों, तो उसे निकाला नहीं जा सकता।


***Note:** The default value for the maximum allowed entries count is 1000.*


**Returns:**
long - अभिलेख में प्रविष्टियों की अधिकतम गिनती।

### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


आर्काइव में प्रविष्टियों की अधिकतम अनुमत संख्या सेट करता है।
अधिकतम अनुमत प्रविष्टियों की गिनती यह निर्धारित करती है कि एक अभिलेख में कितनी प्रविष्टियाँ हो सकती हैं।
यदि किसी अभिलेख में इस सीमा से अधिक प्रविष्टियाँ हों, तो उसे निकाला नहीं जा सकता।


***Note:** The default value for the maximum allowed entries count is 1000.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | maxAllowedEntriesCount | long | अभिलेख में प्रविष्टियों की अधिकतम गिनती। |
|

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


आर्काइव प्रविष्टियों को निकालने के लिए अनुमत अधिकतम संपीड़न अनुपात निर्दिष्ट करता है।


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Returns:**
double - अभिलेख प्रविष्टियों के लिए अधिकतम अनुमत संपीड़न अनुपात।

### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


आर्काइव प्रविष्टियों को निकालने के लिए अनुमत अधिकतम संपीड़न अनुपात निर्दिष्ट करता है।


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | maxAllowedEntryCompressionRatio | double | अभिलेख प्रविष्टियों के लिए अधिकतम अनुमत संपीड़न अनुपात। |
|

