---
title: "عارض"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يُنشئ مثيلاً جديدًا لفئة Viewergroupdocs.viewer/viewer."
type: docs
weight: 10
url: /ar/net/groupdocs.viewer/viewer/viewer/
---

## Viewer(Func&lt;Stream&gt;) {#constructor}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي تُعيد تدفقًا قابلًا للقراءة. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *getFileStream* null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### انظر أيضًا

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي تُعيد تدفقًا قابلًا للقراءة. |
| getLoadOptions | Func`1 | الطرق التي تُعيد خيارات تحميل المستند. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *getFileStream* null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *getLoadOptions* null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### انظر أيضًا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي تُعيد تدفقًا قابلًا للقراءة. |
| settings | ViewerSettings | إعدادات Viewer. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *getFileStream* null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *settings* null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### انظر أيضًا

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي تُعيد تدفقًا قابلًا للقراءة. |
| getLoadOptions | Func`1 | الطرق التي تُعيد خيارات تحميل المستند. |
| settings | ViewerSettings | إعدادات Viewer. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *getFileStream* null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *getLoadOptions* null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *settings* null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### انظر أيضًا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق الملف. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *stream* null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### انظر أيضًا

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق الملف. |
| leaveOpen | Boolean | صحيح لترك التدفق مفتوحًا بعد التخلص من كائن Viewer؛ وإلا، false. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *stream* null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### انظر أيضًا

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق الملف. |
| loadOptions | LoadOptions | خيارات تحميل المستند. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *stream* null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *loadOptions* null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### انظر أيضًا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق الملف. |
| loadOptions | LoadOptions | خيارات تحميل المستند. |
| leaveOpen | Boolean | صحيح لترك التدفق مفتوحًا بعد التخلص من كائن Viewer؛ وإلا، false. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *stream* null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *loadOptions* null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### انظر أيضًا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق الملف. |
| settings | ViewerSettings | إعدادات Viewer. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *stream* null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *settings* null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### انظر أيضًا

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق الملف. |
| settings | ViewerSettings | إعدادات Viewer. |
| leaveOpen | Boolean | صحيح لترك التدفق مفتوحًا بعد التخلص من كائن Viewer؛ وإلا، false. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *stream* null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *settings* null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### انظر أيضًا

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق الملف. |
| loadOptions | LoadOptions | خيارات تحميل المستند. |
| settings | ViewerSettings | إعدادات Viewer. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *stream* null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *loadOptions* null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *settings* null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### انظر أيضًا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق الملف. |
| loadOptions | LoadOptions | خيارات تحميل المستند. |
| settings | ViewerSettings | إعدادات Viewer. |
| leaveOpen | Boolean | صحيح لترك التدفق مفتوحًا بعد التخلص من كائن Viewer؛ وإلا، false. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يتم إلقاؤه عندما تكون *stream* null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *loadOptions* null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *settings* null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### انظر أيضًا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| filePath | String | المسار إلى الملف المراد عرضه. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم إلقاؤه عندما يكون *filePath* null أو فارغ. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### انظر أيضًا

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| filePath | String | المسار إلى الملف المراد عرضه. |
| settings | ViewerSettings | إعدادات Viewer. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم إلقاؤه عندما يكون *filePath* null أو فارغ. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *settings* null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### انظر أيضًا

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| filePath | String | المسار إلى الملف المراد عرضه. |
| loadOptions | LoadOptions | الخيارات التي تُستخدم لفتح الملف. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم إلقاؤه عندما يكون *filePath* null أو فارغ. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *loadOptions* null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### انظر أيضًا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

يُنشئ مثيلاً جديدًا لفئة [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| filePath | String | المسار إلى الملف المراد عرضه. |
| loadOptions | LoadOptions | الخيارات التي تُستخدم لفتح الملف. |
| settings | ViewerSettings | إعدادات Viewer. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يتم إلقاؤه عندما يكون *filePath* null أو فارغ. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *loadOptions* null. |
| ArgumentNullException | يتم إلقاؤه عندما تكون *settings* null. |

### ملاحظات

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### انظر أيضًا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
