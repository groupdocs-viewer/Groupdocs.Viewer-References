---
title: "FileReader"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "फ़ाइल स्ट्रीम पढ़ने के लिए एक इंटरफ़ेस घोषित करता है।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

फ़ाइल स्ट्रीम पढ़ने के लिए एक इंटरफ़ेस घोषित करता है।


फ़ाइलरीडर इंटरफ़ेस एक फ़ाइल स्ट्रीम पढ़ने के लिए एक मेथड प्रदान करता है। यह सामग्री तक पहुँचने और पढ़ने के लिए उपयोग किया जाता है।
फ़ाइल को क्रमिक रूप से पढ़ने के लिए। इस इंटरफ़ेस के कार्यान्वयन को फ़ाइल से डेटा पढ़ने के लिए आवश्यक संचालन को संभालना चाहिए।


उदाहरण उपयोग:

````

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
 
````


## Methods

| Method | विवरण |
| --- | --- |
|  | [read()](#read--) | फ़ाइल के लिए एक पठनीय स्ट्रीम का प्रतिनिधित्व करने वाला InputStream लौटाता है। |
|
|  | [close()](#close--) | ऑब्जेक्ट को नष्ट करता है और उससे जुड़े किसी भी सिस्टम संसाधन को मुक्त करता है। |
|
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


ऑब्जेक्ट को नष्ट करता है और उससे जुड़े किसी भी सिस्टम संसाधन को मुक्त करता है।


