---
title: "FileReader"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "फ़ाइल स्ट्रीम पढ़ने के लिए एक इंटरफ़ेस घोषित करता है।"
type: docs
weight: 14
url: /hi/nodejs-java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

फ़ाइल स्ट्रीम पढ़ने के लिए एक इंटरफ़ेस घोषित करता है।

FileReader इंटरफ़ेस फ़ाइल स्ट्रीम को पढ़ने के लिए एक मेथड प्रदान करता है। यह फ़ाइल की सामग्री को क्रमिक रूप से एक्सेस करने और पढ़ने के लिए उपयोग किया जाता है। इस इंटरफ़ेस के कार्यान्वयन को फ़ाइल से डेटा पढ़ने के लिए आवश्यक संचालन को संभालना चाहिए।

उदाहरण उपयोग:

```

 FileReader fileReader = new FileReader() {
     @Override
     public InputStream read() {
         // Create document stream
     }

     @Override
     public void close() {
         // Close the stream
     }
 };
 try (Viewer viewer = new Viewer(fileReader, new ViewerSettings())){
     // Process document
 }
 
```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [read()](#read--) | फ़ाइल के लिए एक पठनीय स्ट्रीम का प्रतिनिधित्व करने वाला InputStream लौटाता है। |
| [close()](#close--) | ऑब्जेक्ट को डिस्पोज़ करता है और उससे जुड़े सभी सिस्टम संसाधनों को रिलीज़ करता है। |
### read() {#read--}
```
public abstract InputStream read()
```


फ़ाइल के लिए एक पठनीय स्ट्रीम का प्रतिनिधित्व करने वाला InputStream लौटाता है।

**Returns:**
java.io.InputStream - InputStream पठनीय स्ट्रीम।
### close() {#close--}
```
public abstract void close()
```


ऑब्जेक्ट को डिस्पोज़ करता है और उससे जुड़े सभी सिस्टम संसाधनों को रिलीज़ करता है।

