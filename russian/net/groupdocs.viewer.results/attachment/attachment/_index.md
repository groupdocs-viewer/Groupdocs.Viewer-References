---
title: "Attachment"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Инициализирует новый экземпляр класса Attachmentgroupdocs.viewer.results/attachment."
type: docs
weight: 10
url: /ru/net/groupdocs.viewer.results/attachment/attachment/
---

## Attachment() {#constructor}

Инициализирует новый экземпляр класса [`Attachment`](../../attachment).

```csharp
public Attachment()
```

### См. также

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string) {#constructor_1}

Инициализирует новый экземпляр класса [`Attachment`](../../attachment).

```csharp
public Attachment(string fileName, string filePath)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| fileName | String | Имя файла вложения. |
| filePath | String | Относительный путь к вложению, например folder/file.docx или имя файла, когда файл находится в корне архива, в электронном письме или в файле данных. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *fileName* равно null или пусто. |
| ArgumentException | Выбрасывается, когда *filePath* равно null или пусто. |

### См. также

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, long) {#constructor_3}

Инициализирует новый экземпляр класса [`Attachment`](../../attachment).

```csharp
public Attachment(string id, string fileName, string filePath, long size)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| ид | String | Уникальный (в контексте одного файла) идентификатор вложения. |
| fileName | String | Имя файла вложения. |
| filePath | String | Относительный путь к вложению, например folder/file.docx или имя файла, когда файл находится в корне архива, в электронном письме или в файле данных. |
| размер | Int64 | Размер файла вложения в байтах. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *id* равен null или пустой. |
| ArgumentException | Выбрасывается, когда *fileName* равно null или пусто. |
| ArgumentException | Выбрасывается, когда *filePath* равно null или пусто. |

### См. также

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, FileType, long) {#constructor_2}

Инициализирует новый экземпляр класса [`Attachment`](../../attachment).

```csharp
public Attachment(string id, string fileName, string filePath, FileType fileType, long size)
```

| Параметр | Type | Описание |
| --- | --- | --- |
| ид | String | Уникальный (в контексте одного файла) идентификатор вложения. |
| fileName | String | Имя файла вложения. |
| filePath | String | Относительный путь к вложению, например folder/file.docx или имя файла, когда файл находится в корне архива, в электронном письме или в файле данных. |
| fileType | FileType | Тип файла вложения. |
| размер | Int64 | Размер файла вложения в байтах. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Выбрасывается, когда *id* равен null или пустой. |
| ArgumentException | Выбрасывается, когда *fileName* равно null или пусто. |
| ArgumentException | Выбрасывается, когда *filePath* равно null или пусто. |
| ArgumentNullException | Выбрасывается, когда *fileType* равно null. |

### См. также

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
