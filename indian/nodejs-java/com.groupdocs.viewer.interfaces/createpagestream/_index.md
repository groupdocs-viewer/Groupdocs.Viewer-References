---
title: "CreatePageStream"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "एक इंटरफ़ेस को दर्शाता है जो आउटपुट पृष्ठ डेटा लिखने के लिए उपयोग किए जाने वाले स्ट्रीम को इंस्टैंसिएट करता है।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.viewer.interfaces/createpagestream/
---```
public interface CreatePageStream
```

Represents an interface that instantiates a stream used to write output page data.

The CreatePageStream interface is a functional interface that provides a method for creating a stream to write the output page data. It can be implemented by custom classes to define the behavior of generating and writing page data to a stream.

Example usage:

```

 CreatePageStream createPageStream = pageNumber -> new FileOutputStream("page-" + pageNumber + ".html");
 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources(createPageStream);
 
```
## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber)](#invoke-int-) | Returns an OutputStream that will be used to write output page data. |
### invoke(int pageNumber) {#invoke-int-}
```
public abstract OutputStream invoke(int pageNumber)
```


Returns an OutputStream that will be used to write output page data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Number of the page. |

**Returns:**
java.io.OutputStream - the stream used to write output page data.
