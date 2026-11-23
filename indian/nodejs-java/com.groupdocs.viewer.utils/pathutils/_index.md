---
title: "PathUtils"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "PathUtils क्लास फ़ाइल पाथ के साथ काम करने के लिए यूटिलिटी मेथड प्रदान करती है।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

PathUtils क्लास फ़ाइल पाथ के साथ काम करने के लिए यूटिलिटी मेथड प्रदान करती है।

PathUtils क्लास में स्थैतिक मेथड्स होते हैं जो आपको GroupDocs.Viewer घटक में फ़ाइल पाथ पर विभिन्न ऑपरेशन्स करने की अनुमति देते हैं।

उदाहरण उपयोग:

```

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [combine(String[] params)](#combine-java.lang.String...-) | सेपरेटर का उपयोग करके पाथ भागों को संयोजित करें। |
| [getFileName(String path)](#getFileName-java.lang.String-) | फ़ाइल नाम प्राप्त करता है। |
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


सेपरेटर का उपयोग करके पाथ भागों को संयोजित करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| params | java.lang.String[] | पाथ के भाग |

**Returns:**
java.lang.String - परिणाम पाथ
### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


फ़ाइल नाम प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पाथ | java.lang.String | पाथ |

**Returns:**
java.lang.String - फ़ाइल नाम
