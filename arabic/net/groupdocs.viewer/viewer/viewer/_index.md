---
title: Viewer
second_title: GroupDocs.Viewer لمرجع .NET API
description: تهيئة مثيل جديد لـViewergroupdocs.viewer/viewer فئة .
type: docs
weight: 10
url: /ar/net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(Func<Stream> getFileStream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي ترجع الدفق المقروء. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*getFileStream* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### أنظر أيضا

* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي ترجع الدفق المقروء. |
| getLoadOptions | Func`1 | الطرق التي ترجع خيارات تحميل المستند. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*getFileStream* باطل. |
| ArgumentNullException | عندما ألقيت*getLoadOptions* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* المزيد حول تحميل المستندات المشفرة وعرض الملفات من مخازن الطرف الثالث باستخدام GroupDocs.Viewer for .NET: [كيفية تحميل وعرض المستند باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي ترجع الدفق المقروء. |
| settings | ViewerSettings | إعدادات العارض. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*getFileStream* باطل. |
| ArgumentNullException | عندما ألقيت*settings* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### أنظر أيضا

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| getFileStream | Func`1 | الطريقة التي ترجع الدفق المقروء. |
| getLoadOptions | Func`1 | الطرق التي ترجع خيارات تحميل المستند. |
| settings | ViewerSettings | إعدادات العارض. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*getFileStream* باطل. |
| ArgumentNullException | عندما ألقيت*getLoadOptions* باطل. |
| ArgumentNullException | عندما ألقيت*settings* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* المزيد حول تحميل المستندات المشفرة وعرض الملفات من مخازن الطرف الثالث باستخدام GroupDocs.Viewer for .NET: [كيفية تحميل وعرض المستند باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(Stream stream)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | دفق الملف. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*stream* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### أنظر أيضا

* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | دفق الملف. |
| leaveOpen | Boolean | حقيقي لترك الدفق مفتوحًا بعد التخلص من كائن العارض ؛ خلاف ذلك،خطأ شنيع. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*stream* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### أنظر أيضا

* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | دفق الملف. |
| loadOptions | LoadOptions | خيارات تحميل المستند. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*stream* باطل. |
| ArgumentNullException | عندما ألقيت*loadOptions* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* المزيد حول تحميل المستندات المشفرة وعرض الملفات من مخازن الطرف الثالث باستخدام GroupDocs.Viewer for .NET: [كيفية تحميل وعرض المستند باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | دفق الملف. |
| loadOptions | LoadOptions | خيارات تحميل المستند. |
| leaveOpen | Boolean | حقيقي لترك الدفق مفتوحًا بعد التخلص من كائن العارض ؛ خلاف ذلك،خطأ شنيع. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*stream* باطل. |
| ArgumentNullException | عندما ألقيت*loadOptions* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* المزيد حول تحميل المستندات المشفرة وعرض الملفات من مخازن الطرف الثالث باستخدام GroupDocs.Viewer for .NET: [كيفية تحميل وعرض المستند باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | دفق الملف. |
| settings | ViewerSettings | إعدادات العارض. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*stream* باطل. |
| ArgumentNullException | عندما ألقيت*settings* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### أنظر أيضا

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | دفق الملف. |
| settings | ViewerSettings | إعدادات العارض. |
| leaveOpen | Boolean | حقيقي لترك الدفق مفتوحًا بعد التخلص من كائن العارض ؛ خلاف ذلك،خطأ شنيع. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*stream* باطل. |
| ArgumentNullException | عندما ألقيت*settings* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### أنظر أيضا

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | دفق الملف. |
| loadOptions | LoadOptions | خيارات تحميل المستند. |
| settings | ViewerSettings | إعدادات العارض. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*stream* باطل. |
| ArgumentNullException | عندما ألقيت*loadOptions* باطل. |
| ArgumentNullException | عندما ألقيت*settings* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* المزيد حول تحميل المستندات المشفرة وعرض الملفات من مخازن الطرف الثالث باستخدام GroupDocs.Viewer for .NET: [كيفية تحميل وعرض المستند باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| stream | Stream | دفق الملف. |
| loadOptions | LoadOptions | خيارات تحميل المستند. |
| settings | ViewerSettings | إعدادات العارض. |
| leaveOpen | Boolean | حقيقي لترك الدفق مفتوحًا بعد التخلص من كائن العارض ؛ خلاف ذلك،خطأ شنيع. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentNullException | عندما ألقيت*stream* باطل. |
| ArgumentNullException | عندما ألقيت*loadOptions* باطل. |
| ArgumentNullException | عندما ألقيت*settings* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* المزيد حول تحميل المستندات المشفرة وعرض الملفات من مخازن الطرف الثالث باستخدام GroupDocs.Viewer for .NET: [كيفية تحميل وعرض المستند باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(string filePath)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | المسار إلى الملف المطلوب تقديمه. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | عندما ألقيت*filePath* فارغ أو فارغ. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### أنظر أيضا

* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | المسار إلى الملف المطلوب تقديمه. |
| settings | ViewerSettings | إعدادات العارض. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | عندما ألقيت*filePath* فارغ أو فارغ. |
| ArgumentNullException | عندما ألقيت*settings* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### أنظر أيضا

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | المسار إلى الملف المطلوب تقديمه. |
| loadOptions | LoadOptions | الخيارات المستخدمة لفتح الملف. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | عندما ألقيت*filePath* فارغ أو فارغ. |
| ArgumentNullException | عندما ألقيت*loadOptions* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* المزيد حول تحميل المستندات المشفرة وعرض الملفات من مخازن الطرف الثالث باستخدام GroupDocs.Viewer for .NET: [كيفية تحميل وعرض المستند باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

تهيئة مثيل جديد لـ[`Viewer`](../../viewer) فئة .

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| filePath | String | المسار إلى الملف المطلوب تقديمه. |
| loadOptions | LoadOptions | الخيارات المستخدمة لفتح الملف. |
| settings | ViewerSettings | إعدادات العارض. |

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | عندما ألقيت*filePath* فارغ أو فارغ. |
| ArgumentNullException | عندما ألقيت*loadOptions* باطل. |
| ArgumentNullException | عندما ألقيت*settings* باطل. |

### ملاحظات

**يتعلم أكثر**

* المزيد حول أنواع الملفات التي يدعمها GroupDocs.Viewer: [تنسيقات المستندات التي يدعمها GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* المزيد حول GroupDocs.Viewer لميزات .NET: [دليل المطور](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* المزيد حول تحميل المستندات المشفرة وعرض الملفات من مخازن الطرف الثالث باستخدام GroupDocs.Viewer for .NET: [كيفية تحميل وعرض المستند باستخدام GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### أنظر أيضا

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* مساحة الاسم [GroupDocs.Viewer](../../viewer)
* المجسم [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
