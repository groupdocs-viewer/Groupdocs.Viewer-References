---
title: "ForExternalResources"
second_title: "GroupDocs.Viewer for .NET API 参考"
description: "初始化 HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions 类的实例，以使用外部资源渲染为 HTML。"
type: docs
weight: 20
url: /zh/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

初始化 [`HtmlViewOptions`](../../htmlviewoptions) 类的实例，以使用外部资源渲染为 HTML。

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 实例化用于写入输出页面数据的流的方法。 |
| createResourceStream | CreateResourceStream | 释放由 *createPageStream* 方法创建的流的方法。 |
| createResourceUrl | CreateResourceUrl | 创建 HTML 资源 URL 的方法。 |

### 返回值

新的 [`HtmlViewOptions`](../../htmlviewoptions) 类实例，用于使用外部资源渲染为 HTML。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *createPageStream* 为 null 时抛出。 |
| ArgumentNullException | 当 *createResourceStream* 为 null 时抛出。 |
| ArgumentNullException | 当 *createResourceUrl* 为 null 时抛出。 |

### 备注

有关代码示例，请参阅[文档](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources)。

### 另见

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

初始化 [`HtmlViewOptions`](../../htmlviewoptions) 类的实例，以使用外部资源渲染为 HTML。

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 实例化用于写入输出页面数据的流的方法。 |
| createResourceStream | CreateResourceStream | 实例化用于写入输出 HTML 资源数据的流的方法。 |
| createResourceUrl | CreateResourceUrl | 创建 HTML 资源 URL 的方法。 |
| releasePageStream | ReleasePageStream | 释放由分配给委托并传递给 *createPageStream* 参数的方法创建的流的方法。 |
| releaseResourceStream | ReleaseResourceStream | 释放由分配给委托并传递给 *createResourceStream* 参数的方法创建的流的方法。 |

### 返回值

新的 [`HtmlViewOptions`](../../htmlviewoptions) 类实例，用于使用外部资源渲染为 HTML。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *createPageStream* 为 null 时抛出。 |
| ArgumentNullException | 当 *createResourceStream* 为 null 时抛出。 |
| ArgumentNullException | 当 *createResourceUrl* 为 null 时抛出。 |
| ArgumentNullException | 当 *releasePageStream* 为 null 时抛出。 |
| ArgumentNullException | 当 *releaseResourceStream* 为 null 时抛出。 |

### 备注

有关代码示例，请参阅[文档](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources)。

### 另见

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

初始化 [`HtmlViewOptions`](../../htmlviewoptions) 类的实例，以使用外部资源渲染为 HTML。

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | 实现创建和释放输出页面流方法的工厂。 |
| resourceStreamFactory | IResourceStreamFactory | 实现创建资源 URL、实例化以及释放输出 HTML 资源流所需方法的工厂。 |

### 返回值

新的 [`HtmlViewOptions`](../../htmlviewoptions) 类实例，用于使用外部资源渲染为 HTML。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *pageStreamFactory* 为 null 时抛出。 |
| ArgumentNullException | 当 *resourceStreamFactory* 为 null 时抛出。 |

### 备注

有关代码示例，请参阅[文档](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources)。

### 另见

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

初始化 [`HtmlViewOptions`](../../htmlviewoptions) 类的实例。

```csharp
public static HtmlViewOptions ForExternalResources()
```

### 备注

此构造函数初始化 [`HtmlViewOptions`](../../htmlviewoptions) 的实例

* with "p_{0}.html" as file path format for the output HTML files
* with "p_{0}_{1}" as file path format for the output HTML-resource files
* with "p_{0}_{1}" as URL format for HTML-resources

输出文件将放置在应用程序的当前工作目录中。

有关代码示例，请参阅[文档](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources)。

### 另见

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

初始化 [`HtmlViewOptions`](../../htmlviewoptions) 类的实例。

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | String | 文件路径格式，例如 'page_{0}.html'。 |
| resourceFilePathFormat | String | 资源文件路径格式，例如 'page_{0}/resource_{1}'。 |
| resourceUrlFormat | String | 资源 URL 格式，例如 'page_{0}/resource_{1}'。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 当 *filePathFormat* 为 null 或为空时抛出。 |
| ArgumentException | 当 *resourceFilePathFormat* 为 null 或为空时抛出。 |
| ArgumentException | 当 *resourceUrlFormat* 为 null 或为空时抛出此异常。 |

### 备注

有关代码示例，请参阅[文档](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources)。

### 另见

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
