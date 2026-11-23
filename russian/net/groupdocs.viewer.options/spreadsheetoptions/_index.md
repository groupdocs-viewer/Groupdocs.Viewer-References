---
title: "SpreadsheetOptions"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Содержит параметры для рендеринга электронных таблиц. Подробности см. в дочерних элементах темы Render spreadsheet fileshttps//docs.groupdocs.com/viewer/net/renderspreadsheets/."
type: docs
weight: 530
url: /ru/net/groupdocs.viewer.options/spreadsheetoptions/
---

## SpreadsheetOptions class

Содержит параметры для рендеринга электронных таблиц. Для подробностей см. дочерние элементы темы [Рендеринг файлов электронных таблиц](https://docs.groupdocs.com/viewer/net/render-spreadsheets/).

```csharp
public class SpreadsheetOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/spreadsheetoptions/bottommargin) { get; set; } | Устанавливает нижнее поле страницы при конвертации в PDF. |
| [CountColumnsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countcolumnsperpage) { get; } | Количество столбцов, включаемых на каждую страницу при разбиении листа на страницы. |
| [CountRowsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countrowsperpage) { get; } | Количество строк, включаемых на каждую страницу при разбиении листа на страницы. |
| [DetectSeparator](../../groupdocs.viewer.options/spreadsheetoptions/detectseparator) { get; set; } | Определять разделитель (для файлов CSV/TSV). |
| [HorizontalResolution](../../groupdocs.viewer.options/spreadsheetoptions/horizontalresolution) { get; set; } | Получает или задаёт горизонтальное разрешение генерируемых изображений в точках на дюйм. Эта опция используется только при рендеринге электронных таблиц в форматы PNG или JPEG. |
| [LeftMargin](../../groupdocs.viewer.options/spreadsheetoptions/leftmargin) { get; set; } | Устанавливает левое поле страницы при конвертации в PDF. |
| [RenderGridLines](../../groupdocs.viewer.options/spreadsheetoptions/rendergridlines) { get; set; } | Включает отрисовку линий сетки. |
| [RenderHeadings](../../groupdocs.viewer.options/spreadsheetoptions/renderheadings) { get; set; } | Включает отрисовку заголовков. |
| [RenderHiddenColumns](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddencolumns) { get; set; } | Включает отрисовку скрытых столбцов. |
| [RenderHiddenRows](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddenrows) { get; set; } | Включает отрисовку скрытых строк. |
| [RightMargin](../../groupdocs.viewer.options/spreadsheetoptions/rightmargin) { get; set; } | Устанавливает правое поле страницы при конвертации в PDF. |
| [SkipEmptyColumns](../../groupdocs.viewer.options/spreadsheetoptions/skipemptycolumns) { get; set; } | Отключает отрисовку пустых столбцов. |
| [SkipEmptyRows](../../groupdocs.viewer.options/spreadsheetoptions/skipemptyrows) { get; set; } | Отключает отрисовку пустых строк. |
| [TextOverflowMode](../../groupdocs.viewer.options/spreadsheetoptions/textoverflowmode) { get; set; } | Устанавливает режим переполнения текста при отрисовке электронных таблиц в HTML. По умолчанию , что имитирует поведение MS Excel. |
| [TopMargin](../../groupdocs.viewer.options/spreadsheetoptions/topmargin) { get; set; } | Устанавливает верхнее поле страницы при конвертации в PDF. |
| [VerticalResolution](../../groupdocs.viewer.options/spreadsheetoptions/verticalresolution) { get; set; } | Получает или задает вертикальное разрешение генерируемых изображений в точках на дюйм. Эта опция используется только при отрисовке электронных таблиц в форматы PNG или JPEG. |

## Методы

| Имя | Описание |
| --- | --- |
| static [ForOnePagePerSheet](../../groupdocs.viewer.options/spreadsheetoptions/foronepagepersheet)() | Инициализирует экземпляр класса [`SpreadsheetOptions`](../spreadsheetoptions) для отрисовки всего листа на одной странице. |
| static [ForRenderingByPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingbypagebreaks)() | Инициализирует экземпляр класса [`SpreadsheetOptions`](../spreadsheetoptions) для разбиения на страницы по разрывам страниц. |
| static [ForRenderingPrintArea](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintarea)() | Инициализирует экземпляр класса [`SpreadsheetOptions`](../spreadsheetoptions) для отрисовки только областей печати. |
| static [ForRenderingPrintAreaAndPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintareaandpagebreaks)() | Инициализирует экземпляр класса [`SpreadsheetOptions`](../spreadsheetoptions) для отрисовки областей печати и разрывов страниц. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages)(int) | Инициализирует экземпляр класса [`SpreadsheetOptions`](../spreadsheetoptions) для отрисовки листа по страницам. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages_1)(int, int) | Инициализирует экземпляр класса [`SpreadsheetOptions`](../spreadsheetoptions) для отрисовки листа по страницам. |

### См. также

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
