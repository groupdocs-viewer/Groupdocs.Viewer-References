---
title: "CreatePageStream"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "출력 페이지 데이터를 쓰는 데 사용되는 스트림을 인스턴스화하는 인터페이스를 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.viewer.interfaces/createpagestream/
---```
public interface CreatePageStream
```

Represents an interface that instantiates a stream used to write output page data.


The CreatePageStream interface is a functional interface that provides a method for creating a stream
to write the output page data. It can be implemented by custom classes to define the behavior of
generating and writing page data to a stream.


Example usage:

````

 CreatePageStream createPageStream = pageNumber -> new FileOutputStream("page-" + pageNumber + ".html");
 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources(createPageStream);
 
````


## Methods

| Method | Description |
| --- | --- |
| [invoke(int pageNumber)](#invoke-int-) | Returns an OutputStream that will be used to write output page data.
 |
### invoke(int pageNumber) {#invoke-int-}
```
public abstract OutputStream invoke(int pageNumber)
```


Returns an OutputStream that will be used to write output page data.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageNumber | int | Number of the page.
 |

**Returns:**
java.io.OutputStream - the stream used to write output page data.

