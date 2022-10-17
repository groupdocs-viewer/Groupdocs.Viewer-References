---
title: ForExternalResources
second_title: GroupDocs.Viewer for .NET API 参考
description: 初始化的新实例HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions使用外部资源渲染成 HTML 的类
type: docs
weight: 20
url: /zh/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

初始化的新实例[`HtmlViewOptions`](../../htmlviewoptions)使用外部资源渲染成 HTML 的类。

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 实例化用于写入输出页面数据的流的方法。 |
| createResourceStream | CreateResourceStream | 释放由创建的流的方法*createPageStream*方法。 |
| createResourceUrl | CreateResourceUrl | 为 HTML 资源创建 URL 的方法。 |

### 返回值

的新实例[`HtmlViewOptions`](../../htmlviewoptions)用于使用外部资源呈现为 HTML 的类。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*createPageStream*一片空白。 |
| ArgumentNullException | 何时抛出*createResourceStream*一片空白。 |
| ArgumentNullException | 何时抛出*createResourceUrl*一片空白。 |

### 也可以看看

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* 命名空间 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 部件 [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

初始化的新实例[`HtmlViewOptions`](../../htmlviewoptions)使用外部资源渲染成 HTML 的类。

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 实例化用于写入输出页面数据的流的方法。 |
| createResourceStream | CreateResourceStream | 实例化用于写入输出 HTML 资源数据的流的方法。 |
| createResourceUrl | CreateResourceUrl | 为 HTML 资源创建 URL 的方法。 |
| releasePageStream | ReleasePageStream | 释放由分配给委托的方法创建的流的方法，该委托传递给*createPageStream*范围。 |
| releaseResourceStream | ReleaseResourceStream | 释放由分配给委托的方法创建的流的方法，该委托传递给*createResourceStream*范围。 |

### 返回值

的新实例[`HtmlViewOptions`](../../htmlviewoptions)用于使用外部资源呈现为 HTML 的类。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*createPageStream*一片空白。 |
| ArgumentNullException | 何时抛出*createResourceStream*一片空白。 |
| ArgumentNullException | 何时抛出*createResourceUrl*一片空白。 |
| ArgumentNullException | 何时抛出*releasePageStream*一片空白。 |
| ArgumentNullException | 何时抛出*releaseResourceStream*一片空白。 |

### 也可以看看

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* 命名空间 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 部件 [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

初始化的新实例[`HtmlViewOptions`](../../htmlviewoptions)使用外部资源渲染成 HTML 的类。

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | 实现创建和释放输出页面流的方法的工厂。 |
| resourceStreamFactory | IResourceStreamFactory | 实现创建资源 URL、实例化和释放输出 HTML 资源流所需的方法的工厂。 |

### 返回值

的新实例[`HtmlViewOptions`](../../htmlviewoptions)用于使用外部资源呈现为 HTML 的类。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*pageStreamFactory*一片空白。 |
| ArgumentNullException | 何时抛出*resourceStreamFactory*一片空白。 |

### 也可以看看

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* 命名空间 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 部件 [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

初始化的新实例[`HtmlViewOptions`](../../htmlviewoptions)类.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### 评论

此构造函数初始化[`HtmlViewOptions`](../../htmlviewoptions) - 使用“p_{0}.html”作为输出 HTML 文件的文件路径格式； - 使用“p_{0}_{1}”作为输出 HTML 资源文件的文件路径格式； - 使用“ p_{0}_{1}" 作为 HTML 资源的 URL 格式； 输出文件将被放置到应用程序的当前工作目录中。

### 也可以看看

* class [HtmlViewOptions](../../htmlviewoptions)
* 命名空间 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 部件 [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

初始化的新实例[`HtmlViewOptions`](../../htmlviewoptions)类.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | String | 文件路径格式，例如“page_{0}.html”。 |
| resourceFilePathFormat | String | 资源文件路径格式，例如“page_{0}/resource_{1}”。 |
| resourceUrlFormat | String | 资源 URL 格式，例如“page_{0}/resource_{1}”。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 何时抛出*filePathFormat*为空或为空。 |
| ArgumentException | 何时抛出*resourceFilePathFormat*为空或为空。 |
| ArgumentException | 何时抛出*resourceUrlFormat*为空或为空。 |

### 也可以看看

* class [HtmlViewOptions](../../htmlviewoptions)
* 命名空间 [GroupDocs.Viewer.Options](../../htmlviewoptions)
* 部件 [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
