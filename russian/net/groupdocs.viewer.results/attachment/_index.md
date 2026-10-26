---
title: "Attachment"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Представляет файл вложения, содержащийся в архиве электронных сообщений, PDF‑документе или файле данных Outlook."
type: docs
weight: 80
url: /ru/net/groupdocs.viewer.results/attachment/
---

## Attachment class

Представляет файл вложения, содержащийся в электронном письме, архиве, PDF‑документе или файле данных Outlook.

```csharp
public class Attachment
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Attachment](attachment#constructor)() | Инициализирует новый экземпляр класса [`Attachment`](../attachment). |
| [Attachment](attachment#constructor_1)(string, string) | Инициализирует новый экземпляр класса [`Attachment`](../attachment). |
| [Attachment](attachment#constructor_3)(string, string, string, long) | Инициализирует новый экземпляр класса [`Attachment`](../attachment). |
| [Attachment](attachment#constructor_2)(string, string, string, FileType, long) | Инициализирует новый экземпляр класса [`Attachment`](../attachment). |

## Свойства

| Имя | Описание |
| --- | --- |
| [FileName](../../groupdocs.viewer.results/attachment/filename) { get; set; } | Имя файла вложения. |
| [FilePath](../../groupdocs.viewer.results/attachment/filepath) { get; set; } | Относительный путь к вложению, например folder/file.docx или имя файла, когда файл находится в корне архива, в электронном письме или в файле данных. |
| [FileType](../../groupdocs.viewer.results/attachment/filetype) { get; set; } | Тип файла вложения. |
| [Id](../../groupdocs.viewer.results/attachment/id) { get; set; } | Уникальный идентификатор вложения в контексте единственного файла, содержащего это вложение. |
| [Size](../../groupdocs.viewer.results/attachment/size) { get; set; } | Размер файла вложения в байтах. |

## Методы

| Имя | Описание |
| --- | --- |
| override [ToString](../../groupdocs.viewer.results/attachment/tostring)() | Возвращает строку, представляющую текущий объект. |

### См. также

* namespace [GroupDocs.Viewer.Results](../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
