---
title: "查看器"
second_title: "GroupDocs.Viewer for .NET API 参考"
description: "初始化 Viewergroupdocs.viewer/viewer 类的新实例。"
type: docs
weight: 10
url: /zh/net/groupdocs.viewer/viewer/viewer/
---

## Viewer(Func&lt;Stream&gt;) {#constructor}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(Func<Stream> getFileStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *getFileStream* 为 null 时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 另见

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |
| getLoadOptions | Func`1 | 返回文档加载选项的方法。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *getFileStream* 为 null 时抛出。 |
| ArgumentNullException | 当 *getLoadOptions* 为 null 时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 另见

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |
| settings | ViewerSettings | Viewer 设置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *getFileStream* 为 null 时抛出。 |
| ArgumentNullException | 当 *settings* 为 null 时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 另见

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| getFileStream | Func`1 | 返回可读流的方法。 |
| getLoadOptions | Func`1 | 返回文档加载选项的方法。 |
| settings | ViewerSettings | Viewer 设置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *getFileStream* 为 null 时抛出。 |
| ArgumentNullException | 当 *getLoadOptions* 为 null 时抛出。 |
| ArgumentNullException | 当 *settings* 为 null 时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 另见

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 文件流。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *stream* 为 null 时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 另见

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 文件流。 |
| leaveOpen | Boolean | true 表示在 Viewer 对象释放后保持流打开；否则为 false。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *stream* 为 null 时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 另见

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 文件流。 |
| loadOptions | LoadOptions | 文档加载选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *stream* 为 null 时抛出。 |
| ArgumentNullException | 当 *loadOptions* 为 null 时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 另见

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 文件流。 |
| loadOptions | LoadOptions | 文档加载选项。 |
| leaveOpen | Boolean | true 表示在 Viewer 对象释放后保持流打开；否则为 false。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *stream* 为 null 时抛出。 |
| ArgumentNullException | 当 *loadOptions* 为 null 时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 另见

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 文件流。 |
| settings | ViewerSettings | Viewer 设置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *stream* 为 null 时抛出。 |
| ArgumentNullException | 当 *settings* 为 null 时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 另见

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 文件流。 |
| settings | ViewerSettings | Viewer 设置。 |
| leaveOpen | Boolean | true 表示在 Viewer 对象释放后保持流打开；否则为 false。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *stream* 为 null 时抛出。 |
| ArgumentNullException | 当 *settings* 为 null 时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 另见

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 文件流。 |
| loadOptions | LoadOptions | 文档加载选项。 |
| settings | ViewerSettings | Viewer 设置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *stream* 为 null 时抛出。 |
| ArgumentNullException | 当 *loadOptions* 为 null 时抛出。 |
| ArgumentNullException | 当 *settings* 为 null 时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 另见

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 文件流。 |
| loadOptions | LoadOptions | 文档加载选项。 |
| settings | ViewerSettings | Viewer 设置。 |
| leaveOpen | Boolean | true 表示在 Viewer 对象释放后保持流打开；否则为 false。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 当 *stream* 为 null 时抛出。 |
| ArgumentNullException | 当 *loadOptions* 为 null 时抛出。 |
| ArgumentNullException | 当 *settings* 为 null 时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 另见

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(string filePath)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 要渲染的文件路径。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 当 *filePath* 为 null 或为空时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 另见

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 要渲染的文件路径。 |
| settings | ViewerSettings | Viewer 设置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 当 *filePath* 为 null 或为空时抛出。 |
| ArgumentNullException | 当 *settings* 为 null 时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### 另见

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 要渲染的文件路径。 |
| loadOptions | LoadOptions | 用于打开文件的选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 当 *filePath* 为 null 或为空时抛出。 |
| ArgumentNullException | 当 *loadOptions* 为 null 时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 另见

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

初始化 [`Viewer`](../../viewer) 类的新实例。

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePath | String | 要渲染的文件路径。 |
| loadOptions | LoadOptions | 用于打开文件的选项。 |
| settings | ViewerSettings | Viewer 设置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 当 *filePath* 为 null 或为空时抛出。 |
| ArgumentNullException | 当 *loadOptions* 为 null 时抛出。 |
| ArgumentNullException | 当 *settings* 为 null 时抛出。 |

### 备注

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### 另见

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
