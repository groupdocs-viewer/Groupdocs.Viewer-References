---
title: "FileName"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "आर्काइव में फ़ाइल के नाम को दर्शाता है।"
type: docs
weight: 15
url: /hi/nodejs-java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

आर्काइव में फ़ाइल के नाम को दर्शाता है।

FileName क्लास फ़ाइल के नाम को बिना किसी पथ या डायरेक्टरी जानकारी के समाहित करता है। यह फ़ाइल नाम के बारे में जानकारी को संशोधित और प्राप्त करने के लिए मेथड्स प्रदान करता है।

उदाहरण उपयोग:

```

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.getArchiveOptions().setFileName(new FileName("my-file-name"));

 final LoadOptions loadOptions = new LoadOptions(FileType.ZIP);
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     viewer.view(options);
     // Use the viewer object for archive document rendering
 }
 
```

***Note:** The FileName class is used to work with file names and does not handle file operations or manipulation.*
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FileName(String fileName)](#FileName-java.lang.String-) | FileName क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [EMPTY](#EMPTY) | एक खाली फ़ाइलनाम का प्रतिनिधित्व करता है। |
| [SOURCE](#SOURCE) | स्रोत फ़ाइल का नाम दर्शाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getText()](#getText--) |  |
| [toString()](#toString--) | वर्तमान ऑब्जेक्ट का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


FileName क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल का नाम। |

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


एक खाली फ़ाइलनाम का प्रतिनिधित्व करता है।

### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


स्रोत फ़ाइल का नाम दर्शाता है।

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
