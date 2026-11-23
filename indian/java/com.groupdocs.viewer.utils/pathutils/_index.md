---
title: "PathUtils"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "PathUtils क्लास फ़ाइल पाथ के साथ काम करने के लिए उपयोगी मेथड्स प्रदान करती है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

PathUtils क्लास फ़ाइल पाथ के साथ काम करने के लिए उपयोगी मेथड्स प्रदान करती है।


PathUtils क्लास में स्थैतिक मेथड्स होते हैं जो आपको विभिन्न ऑपरेशन्स करने की अनुमति देते हैं
GroupDocs.Viewer घटक में फ़ाइल पाथ्स पर।


उदाहरण उपयोग:

````

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
````


## Methods

| Method | विवरण |
| --- | --- |
|  | [combine(String[] params)](#combine-java.lang.String...-) | सेपरेटर का उपयोग करके पाथ भागों को संयोजित करें। |
|
|  | [getFileName(String path)](#getFileName-java.lang.String-) | फ़ाइल नाम प्राप्त करता है। |
|
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


सेपरेटर का उपयोग करके पाथ भागों को संयोजित करें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | params | java.lang.String[] | पाथ भाग |
|

**Returns:**
java.lang.String - परिणाम पाथ

### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


फ़ाइल नाम प्राप्त करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | पाथ | java.lang.String | पाथ |
|

**Returns:**
java.lang.String - फ़ाइल नाम

