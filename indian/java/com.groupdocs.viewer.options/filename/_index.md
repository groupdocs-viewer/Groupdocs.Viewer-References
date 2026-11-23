---
title: "FileName"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "अभिलेख में फ़ाइल के नाम का प्रतिनिधित्व करता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

अभिलेख में फ़ाइल के नाम का प्रतिनिधित्व करता है।


FileName क्लास फ़ाइल के नाम को बिना किसी पथ या निर्देशिका जानकारी के समाहित करती है।
यह फ़ाइल नाम के बारे में जानकारी को संशोधित और प्राप्त करने के लिए मेथड्स प्रदान करती है।


उदाहरण उपयोग:

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.getArchiveOptions().setFileName(new FileName("my-file-name"));

 final LoadOptions loadOptions = new LoadOptions(FileType.ZIP);
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     viewer.view(options);
     // Use the viewer object for archive document rendering
 }
 
````


***Note:** The FileName class is used to work with file names and does not handle file operations or manipulation.*

## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [FileName(String fileName)](#FileName-java.lang.String-) | नए उदाहरण को प्रारंभ करता है |
FileName
class।
|
## Fields

| Field | विवरण |
| --- | --- |
|  | [EMPTY](#EMPTY) | एक खाली फ़ाइलनाम का प्रतिनिधित्व करता है। |
|
|  | [SOURCE](#SOURCE) | स्रोत फ़ाइल के नाम का प्रतिनिधित्व करता है। |
|
## Methods

| Method | विवरण |
| --- | --- |
| [getText()](#getText--) |  |
|  | [toString()](#toString--) | वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
|
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


नए उदाहरण को प्रारंभ करता है
FileName
class।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileName | java.lang.String | फ़ाइल का नाम। |
|

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


एक खाली फ़ाइलनाम का प्रतिनिधित्व करता है।


### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


स्रोत फ़ाइल के नाम का प्रतिनिधित्व करता है।


### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व लौटाता है।


**Returns:**
java.lang.String - वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व।

