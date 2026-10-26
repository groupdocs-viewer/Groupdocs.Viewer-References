---
title: "Просмотрщик"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Представляет основной класс, управляющий процессом рендеринга документа."
type: docs
weight: 50
url: /ru/net/groupdocs.viewer/viewer/
---

## Viewer class

Представляет основной класс, управляющий процессом рендеринга документа.

```csharp
public class Viewer : IDisposable
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Viewer](viewer#constructor)(Func&lt;Stream&gt;) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_4)(Stream) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_12)(string) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_2)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_1)(Func&lt;Stream&gt;, ViewerSettings) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_5)(Stream, bool) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_6)(Stream, LoadOptions) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_10)(Stream, ViewerSettings) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_13)(string, LoadOptions) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_15)(string, ViewerSettings) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_7)(Stream, LoadOptions, bool) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_8)(Stream, LoadOptions, ViewerSettings) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_11)(Stream, ViewerSettings, bool) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_14)(string, LoadOptions, ViewerSettings) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_9)(Stream, LoadOptions, ViewerSettings, bool) | Инициализирует новый экземпляр класса [`Viewer`](../viewer). |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../groupdocs.viewer/viewer/dispose)() | Освобождает поток файла и управляемые внутренние ресурсы. |
| [GetAllFonts](../../groupdocs.viewer/viewer/getallfonts)() | Возвращает все шрифты, используемые в загруженных документах, включая встроенные в сам документ шрифты и системные шрифты, установленные в ОС и используемые в документе. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments)() | Возвращает вложения, содержащиеся в документе. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments_1)(CancellationToken) | Возвращает вложения, содержащиеся в документе. |
| [GetFileInfo](../../groupdocs.viewer/viewer/getfileinfo)() | Возвращает информацию о файле, такую как тип файла и флаг, указывающий, зашифрован ли файл. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo)(ViewInfoOptions) | Возвращает информацию о представлении и специфическую информацию о документе. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo_1)(ViewInfoOptions, CancellationToken) | Возвращает информацию о представлении и специфическую информацию о документе. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment)(Attachment, Stream) | Сохраняет файл вложения в поток *destination*. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment_1)(Attachment, Stream, CancellationToken) | Сохраняет файл вложения в поток *destination*. |
| [Search](../../groupdocs.viewer/viewer/search)(SearchHighlightOptions) | Выполняет поиск текста и его подсветку (если найден) в загруженном документе в соответствии с загруженными параметрами. |
| [View](../../groupdocs.viewer/viewer/view#view)(ViewOptions) | Создаёт представление всех страниц документа. |
| [View](../../groupdocs.viewer/viewer/view#view_2)(ViewOptions, CancellationToken) | Создаёт представление всех страниц документа. |
| [View](../../groupdocs.viewer/viewer/view#view_1)(ViewOptions, params int[]) | Создаёт представление определённых страниц документа. |
| [View](../../groupdocs.viewer/viewer/view#view_3)(ViewOptions, CancellationToken, params int[]) | Создаёт представление определённых страниц документа. |

### См. также

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
