---
title: "LoadOptions"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Содержит параметры, используемые для открытия файла. Для подробностей см. эту страницу https//docs.groupdocs.com/viewer/net/loading/ и её дочерние элементы."
type: docs
weight: 360
url: /ru/net/groupdocs.viewer.options/loadoptions/
---

## LoadOptions class

Содержит параметры, используемые для открытия файла. Для подробностей см. эту [страницу](https://docs.groupdocs.com/viewer/net/loading/) и её дочерние элементы.

```csharp
public class LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Инициализирует экземпляр класса [`LoadOptions`](../loadoptions). |
| [LoadOptions](loadoptions#constructor_1)(FileType) | Инициализирует экземпляр класса [`LoadOptions`](../loadoptions). |

## Свойства

| Имя | Описание |
| --- | --- |
| [DetectEncoding](../../groupdocs.viewer.options/loadoptions/detectencoding) { get; set; } | Включает определение кодировки для файлов [`TXT`](../../groupdocs.viewer/filetype/txt), [`CSV`](../../groupdocs.viewer/filetype/csv) и [`TSV`](../../groupdocs.viewer/filetype/tsv). |
| [Encoding](../../groupdocs.viewer.options/loadoptions/encoding) { get; set; } | Устанавливает кодировку, используемую при открытии текстовых файлов или электронных сообщений, таких как [`CSV`](../../groupdocs.viewer/filetype/csv), [`TXT`](../../groupdocs.viewer/filetype/txt) и [`MSG`](../../groupdocs.viewer/filetype/msg). Значение по умолчанию — UTF8. |
| [FileType](../../groupdocs.viewer.options/loadoptions/filetype) { get; set; } | Устанавливает тип открываемого файла. |
| [Password](../../groupdocs.viewer.options/loadoptions/password) { get; set; } | Устанавливает пароль для открытия зашифрованного файла. |
| [ResourceLoadingTimeout](../../groupdocs.viewer.options/loadoptions/resourceloadingtimeout) { get; set; } | Устанавливает тайм-аут для загрузки внешних ресурсов. |
| [SkipExternalResources](../../groupdocs.viewer.options/loadoptions/skipexternalresources) { get; set; } | Отключает загрузку всех внешних ресурсов, таких как изображения, за исключением [`WhitelistedResources`](./whitelistedresources). |
| [TryRepair](../../groupdocs.viewer.options/loadoptions/tryrepair) { get; set; } | Когда включено, GroupDocs.Viewer пытается исправить структурные повреждения PDF‑документов. Значение по умолчанию — `false`. |
| [WhitelistedResources](../../groupdocs.viewer.options/loadoptions/whitelistedresources) { get; set; } | Список фрагментов URL, соответствующих внешним ресурсам, которые должны быть загружены, когда [`SkipExternalResources`](./skipexternalresources) установлено в `true`. |

### См. также

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
