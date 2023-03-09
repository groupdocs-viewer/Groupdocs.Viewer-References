---
title: Viewer
second_title: GroupDocs.Viewer for .NET API 参考
description: 初始化新实例Viewergroupdocs.viewer/viewer类.
type: docs
weight: 10
url: /zh/net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*getFileStream*一片空白。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 也可以看看

* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |
| getLoadOptions | Func`1 | 返回文档加载选项的方法。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*getFileStream*一片空白。 |
| ArgumentNullException | 抛出时*getLoadOptions*一片空白。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* 更多关于使用 GroupDocs.Viewer for .NET 加载加密文档和查看来自第三方存储的文件的信息： [如何使用 GroupDocs.Viewer 加载和查看文档](https://docs.groupdocs.com/display/viewernet/Loading)

### 也可以看看

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |
| settings | ViewerSettings | 查看器设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*getFileStream*一片空白。 |
| ArgumentNullException | 抛出时*settings*一片空白。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 也可以看看

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |
| getLoadOptions | Func`1 | 返回文档加载选项的方法。 |
| settings | ViewerSettings | 查看器设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*getFileStream*一片空白。 |
| ArgumentNullException | 抛出时*getLoadOptions*一片空白。 |
| ArgumentNullException | 抛出时*settings*一片空白。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* 更多关于使用 GroupDocs.Viewer for .NET 加载加密文档和查看来自第三方存储的文件的信息： [如何使用 GroupDocs.Viewer 加载和查看文档](https://docs.groupdocs.com/display/viewernet/Loading)

### 也可以看看

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(Stream stream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 文件流。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*stream*一片空白。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 也可以看看

* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 文件流。 |
| leaveOpen | Boolean | 真的在处理 Viewer 对象后保持流打开；否则，错误的. |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*stream*一片空白。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 也可以看看

* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 文件流。 |
| loadOptions | LoadOptions | 文档加载选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*stream*一片空白。 |
| ArgumentNullException | 抛出时*loadOptions*一片空白。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* 更多关于使用 GroupDocs.Viewer for .NET 加载加密文档和查看来自第三方存储的文件的信息： [如何使用 GroupDocs.Viewer 加载和查看文档](https://docs.groupdocs.com/display/viewernet/Loading)

### 也可以看看

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 文件流。 |
| loadOptions | LoadOptions | 文档加载选项。 |
| leaveOpen | Boolean | 真的在处理 Viewer 对象后保持流打开；否则，错误的. |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*stream*一片空白。 |
| ArgumentNullException | 抛出时*loadOptions*一片空白。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* 更多关于使用 GroupDocs.Viewer for .NET 加载加密文档和查看来自第三方存储的文件的信息： [如何使用 GroupDocs.Viewer 加载和查看文档](https://docs.groupdocs.com/display/viewernet/Loading)

### 也可以看看

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 文件流。 |
| settings | ViewerSettings | 查看器设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*stream*一片空白。 |
| ArgumentNullException | 抛出时*settings*一片空白。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 也可以看看

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 文件流。 |
| settings | ViewerSettings | 查看器设置。 |
| leaveOpen | Boolean | 真的在处理 Viewer 对象后保持流打开；否则，错误的. |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*stream*一片空白。 |
| ArgumentNullException | 抛出时*settings*一片空白。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 也可以看看

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 文件流。 |
| loadOptions | LoadOptions | 文档加载选项。 |
| settings | ViewerSettings | 查看器设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*stream*一片空白。 |
| ArgumentNullException | 抛出时*loadOptions*一片空白。 |
| ArgumentNullException | 抛出时*settings*一片空白。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* 更多关于使用 GroupDocs.Viewer for .NET 加载加密文档和查看来自第三方存储的文件的信息： [如何使用 GroupDocs.Viewer 加载和查看文档](https://docs.groupdocs.com/display/viewernet/Loading)

### 也可以看看

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 文件流。 |
| loadOptions | LoadOptions | 文档加载选项。 |
| settings | ViewerSettings | 查看器设置。 |
| leaveOpen | Boolean | 真的在处理 Viewer 对象后保持流打开；否则，错误的. |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*stream*一片空白。 |
| ArgumentNullException | 抛出时*loadOptions*一片空白。 |
| ArgumentNullException | 抛出时*settings*一片空白。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* 更多关于使用 GroupDocs.Viewer for .NET 加载加密文档和查看来自第三方存储的文件的信息： [如何使用 GroupDocs.Viewer 加载和查看文档](https://docs.groupdocs.com/display/viewernet/Loading)

### 也可以看看

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(string filePath)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 要呈现的文件的路径。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 抛出时*filePath*为 null 或空。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 也可以看看

* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 要呈现的文件的路径。 |
| settings | ViewerSettings | 查看器设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 抛出时*filePath*为 null 或空。 |
| ArgumentNullException | 抛出时*settings*一片空白。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 也可以看看

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 要呈现的文件的路径。 |
| loadOptions | LoadOptions | 用于打开文件的选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 抛出时*filePath*为 null 或空。 |
| ArgumentNullException | 抛出时*loadOptions*一片空白。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* 更多关于使用 GroupDocs.Viewer for .NET 加载加密文档和查看来自第三方存储的文件的信息： [如何使用 GroupDocs.Viewer 加载和查看文档](https://docs.groupdocs.com/display/viewernet/Loading)

### 也可以看看

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

初始化新实例[`Viewer`](../../viewer)类.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 要呈现的文件的路径。 |
| loadOptions | LoadOptions | 用于打开文件的选项。 |
| settings | ViewerSettings | 查看器设置。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 抛出时*filePath*为 null 或空。 |
| ArgumentNullException | 抛出时*loadOptions*一片空白。 |
| ArgumentNullException | 抛出时*settings*一片空白。 |

### 评论

**了解更多**

* 有关 GroupDocs.Viewer 支持的文件类型的更多信息： [GroupDocs.Viewer 支持的文档格式](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* 有关 GroupDocs.Viewer for .NET 功能的更多信息： [开发者指南](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* 更多关于使用 GroupDocs.Viewer for .NET 加载加密文档和查看来自第三方存储的文件的信息： [如何使用 GroupDocs.Viewer 加载和查看文档](https://docs.groupdocs.com/display/viewernet/Loading)

### 也可以看看

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
