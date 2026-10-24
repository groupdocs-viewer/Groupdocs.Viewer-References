---
title: "com.groupdocs.viewer.interfaces"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "该包提供用于实例化和释放输出文档及其资源的接口。"
type: docs
weight: 17
url: /zh/java/com.groupdocs.viewer.interfaces/
---

该包提供用于实例化和释放输出文档及其资源的接口。


这些接口用于管理与输出文件、页面和 HTML 资源相关的流和 URL 的创建和释放。

此包中的主要接口有：

* [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
* [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
* [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.


有关使用这些接口以及自定义 GroupDocs.Viewer 中输出文档和资源处理的更多详细信息，
请参阅 [GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/)。



## 接口

| 接口 | 描述 |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | 表示用于实例化写入输出文件数据的流的接口。 |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | 表示用于实例化写入输出页面数据的流的接口。 |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | 表示用于实例化写入输出 HTML 资源数据的流的接口。 |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | 表示用于为 HTML 资源创建 URL 的接口。 |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | 声明用于读取文件流的接口。 |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | 定义实例化和释放输出文件流所需的方法。 |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | 定义实例化和释放输出页面流所需的方法。 |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | 释放由 CreateFileStream 接口关联的方法实例化的接口。 |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | 释放由 CreatePageStream 接口关联的方法实例化的流。 |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | 释放由 CreateResourceStream 接口关联的方法实例化的流。 |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | 定义创建资源 URL、实例化和释放输出 HTML 资源流所需的方法。 |
