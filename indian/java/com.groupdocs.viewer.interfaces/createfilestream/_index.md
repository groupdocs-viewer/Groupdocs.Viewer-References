---
title: "CreateFileStream"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "एक इंटरफ़ेस का प्रतिनिधित्व करता है जो आउटपुट फ़ाइल डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंशिएट करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.viewer.interfaces/createfilestream/
---```
public interface CreateFileStream
```

Represents an interface that instantiates a stream used to write output file data.


The CreateFileStream interface is a functional interface that provides a method for instantiating a stream used to write data to an output file.
Implementing classes or lambdas can use this interface to customize the creation of the output file stream based on specific requirements.


Example usage:

````

 CreateFileStream createFileStream = (filePath) -> new FileOutputStream(filePath);
 PdfViewOptions pdfViewOptions = new PdfViewOptions(createFileStream);
 
````


***Note:** The CreateFileStream interface can be used to define different strategies for creating output file streams,
such as using a FileOutputStream or any other custom stream implementation.*

## Methods

| Method | Description |
| --- | --- |
| [invoke()](#invoke--) | Returns an OutputStream that will be used to write output file data.
 |
### invoke() {#invoke--}
```
public abstract OutputStream invoke()
```


Returns an OutputStream that will be used to write output file data.


**Returns:**
java.io.OutputStream - the stream used to write output file data.

