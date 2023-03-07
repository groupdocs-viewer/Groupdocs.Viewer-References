---
title: Viewer
second_title: Справочник по API GroupDocs.Viewer для .NET
description: Инициализирует новый экземплярViewergroupdocs.viewer/viewer класс.
type: docs
weight: 10
url: /ru/net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| getFileStream | Func`1 | Метод, который возвращает читаемый поток. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*getFileStream* нулевой. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Смотрите также

* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| getFileStream | Func`1 | Метод, который возвращает читаемый поток. |
| getLoadOptions | Func`1 | Методы, возвращающие параметры загрузки документа. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*getFileStream* нулевой. |
| ArgumentNullException | Брошен, когда*getLoadOptions* нулевой. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Подробнее о загрузке зашифрованных документов и просмотре файлов из сторонних хранилищ с помощью GroupDocs.Viewer для .NET: [Как загрузить и просмотреть документ с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Смотрите также

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| getFileStream | Func`1 | Метод, который возвращает читаемый поток. |
| settings | ViewerSettings | Настройки просмотра. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*getFileStream* нулевой. |
| ArgumentNullException | Брошен, когда*settings* нулевой. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Смотрите также

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| getFileStream | Func`1 | Метод, который возвращает читаемый поток. |
| getLoadOptions | Func`1 | Методы, возвращающие параметры загрузки документа. |
| settings | ViewerSettings | Настройки просмотра. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*getFileStream* нулевой. |
| ArgumentNullException | Брошен, когда*getLoadOptions* нулевой. |
| ArgumentNullException | Брошен, когда*settings* нулевой. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Подробнее о загрузке зашифрованных документов и просмотре файлов из сторонних хранилищ с помощью GroupDocs.Viewer для .NET: [Как загрузить и просмотреть документ с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Смотрите также

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Файловый поток. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*stream* нулевой. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Смотрите также

* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Файловый поток. |
| leaveOpen | Boolean | истинный оставить поток открытым после удаления объекта Viewer; в противном случае,ЛОЖЬ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*stream* нулевой. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Смотрите также

* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Файловый поток. |
| loadOptions | LoadOptions | Параметры загрузки документа. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*stream* нулевой. |
| ArgumentNullException | Брошен, когда*loadOptions* нулевой. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Подробнее о загрузке зашифрованных документов и просмотре файлов из сторонних хранилищ с помощью GroupDocs.Viewer для .NET: [Как загрузить и просмотреть документ с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Смотрите также

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Файловый поток. |
| loadOptions | LoadOptions | Параметры загрузки документа. |
| leaveOpen | Boolean | истинный оставить поток открытым после удаления объекта Viewer; в противном случае,ЛОЖЬ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*stream* нулевой. |
| ArgumentNullException | Брошен, когда*loadOptions* нулевой. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Подробнее о загрузке зашифрованных документов и просмотре файлов из сторонних хранилищ с помощью GroupDocs.Viewer для .NET: [Как загрузить и просмотреть документ с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Смотрите также

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Файловый поток. |
| settings | ViewerSettings | Настройки просмотра. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*stream* нулевой. |
| ArgumentNullException | Брошен, когда*settings* нулевой. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Смотрите также

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Файловый поток. |
| settings | ViewerSettings | Настройки просмотра. |
| leaveOpen | Boolean | истинный оставить поток открытым после удаления объекта Viewer; в противном случае,ЛОЖЬ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*stream* нулевой. |
| ArgumentNullException | Брошен, когда*settings* нулевой. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Смотрите также

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Файловый поток. |
| loadOptions | LoadOptions | Параметры загрузки документа. |
| settings | ViewerSettings | Настройки просмотра. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*stream* нулевой. |
| ArgumentNullException | Брошен, когда*loadOptions* нулевой. |
| ArgumentNullException | Брошен, когда*settings* нулевой. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Подробнее о загрузке зашифрованных документов и просмотре файлов из сторонних хранилищ с помощью GroupDocs.Viewer для .NET: [Как загрузить и просмотреть документ с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Смотрите также

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Файловый поток. |
| loadOptions | LoadOptions | Параметры загрузки документа. |
| settings | ViewerSettings | Настройки просмотра. |
| leaveOpen | Boolean | истинный оставить поток открытым после удаления объекта Viewer; в противном случае,ЛОЖЬ. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Брошен, когда*stream* нулевой. |
| ArgumentNullException | Брошен, когда*loadOptions* нулевой. |
| ArgumentNullException | Брошен, когда*settings* нулевой. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Подробнее о загрузке зашифрованных документов и просмотре файлов из сторонних хранилищ с помощью GroupDocs.Viewer для .NET: [Как загрузить и просмотреть документ с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Смотрите также

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу для рендеринга. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Брошен, когда*filePath* является нулевым или пустым. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Смотрите также

* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу для рендеринга. |
| settings | ViewerSettings | Настройки просмотра. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Брошен, когда*filePath* является нулевым или пустым. |
| ArgumentNullException | Брошен, когда*settings* нулевой. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Смотрите также

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу для рендеринга. |
| loadOptions | LoadOptions | Параметры, которые использовались для открытия файла. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Брошен, когда*filePath* является нулевым или пустым. |
| ArgumentNullException | Брошен, когда*loadOptions* нулевой. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Подробнее о загрузке зашифрованных документов и просмотре файлов из сторонних хранилищ с помощью GroupDocs.Viewer для .NET: [Как загрузить и просмотреть документ с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Смотрите также

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Инициализирует новый экземпляр[`Viewer`](../../viewer) класс.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу для рендеринга. |
| loadOptions | LoadOptions | Параметры, которые использовались для открытия файла. |
| settings | ViewerSettings | Настройки просмотра. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Брошен, когда*filePath* является нулевым или пустым. |
| ArgumentNullException | Брошен, когда*loadOptions* нулевой. |
| ArgumentNullException | Брошен, когда*settings* нулевой. |

### Примечания

**Узнать больше**

* Подробнее о типах файлов, поддерживаемых GroupDocs.Viewer: [Форматы документов, поддерживаемые GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Подробнее о возможностях GroupDocs.Viewer для .NET: [Руководство для разработчиков](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Подробнее о загрузке зашифрованных документов и просмотре файлов из сторонних хранилищ с помощью GroupDocs.Viewer для .NET: [Как загрузить и просмотреть документ с помощью GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Смотрите также

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* пространство имен [GroupDocs.Viewer](../../viewer)
* сборка [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
