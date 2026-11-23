---
title: "GroupDocs.Viewer.Fonts"
second_title: "Справочник API GroupDocs.Viewer для .NET"
description: "Это пространство имён предоставляет классы и перечисления для управления шрифтами, используемыми в процессе рендеринга."
type: docs
weight: 50
url: /ru/net/groupdocs.viewer.fonts/
---

Это пространство имён предоставляет классы и перечисления для управления шрифтами, используемыми в процессе рендеринга.

## Классы

| Класс | Описание |
| --- | --- |
| [FolderFontSource](./folderfontsource) | Представляет папку, содержащую шрифты TrueType. |
| [FontSettings](./fontsettings) | Предоставляет методы для работы с источниками при поиске шрифтов TrueType. |
## Structures

| Структура | Описание |
| --- | --- |
| [FontStyles](./fontstyles) | Представляет 4 возможных стиля шрифта, используемых в документе: Regular, Bold, Italic или Bold Italic. |
| [PdfFontInfo](./pdffontinfo) | Инкапсулирует метаданные и бинарные данные одного шрифта из PDF‑документа, загруженного в экземпляр [`Viewer`](../groupdocs.viewer/viewer). Этот шрифт используется в содержимом документа и встроен в сам документ либо установлен в операционной системе, где работает GroupDocs.Viewer. |
| [PresentationFontInfo](./presentationfontinfo) | Инкапсулирует метаданные и бинарные данные одного шрифта из презентационного документа, загруженного в экземпляр [`Viewer`](../groupdocs.viewer/viewer). Этот шрифт используется в содержимом документа и встроен в сам документ либо установлен в операционной системе, где работает GroupDocs.Viewer. |
| [SpreadsheetFontInfo](./spreadsheetfontinfo) | Инкапсулирует метаданные и бинарные данные одного шрифта из документа таблицы, загруженного в экземпляр [`Viewer`](../groupdocs.viewer/viewer). Таблицы не могут содержать встроенные шрифты, поэтому данный шрифт, если он был возвращён методом [`GetAllFonts`](../groupdocs.viewer/viewer/getallfonts), установлен в операционной системе, где работает GroupDocs.Viewer. |
| [WordProcessingFontInfo](./wordprocessingfontinfo) | Инкапсулирует метаданные и бинарные данные одного шрифта из документа WordProcessing, загруженного в экземпляр [`Viewer`](../groupdocs.viewer/viewer). Этот шрифт используется в содержимом документа и встроен в сам документ либо установлен в операционной системе, где работает GroupDocs.Viewer. |
| [WordProcessingSubstitutedFontInfo](./wordprocessingsubstitutedfontinfo) | Инкапсулирует метаданные и бинарные данные одного шрифта из документа WordProcessing, который изначально не используется в документе, загруженном в экземпляр [`Viewer`](../groupdocs.viewer/viewer), но служит заменяющим шрифтом для тех, которые не найдены на целевой машине. Заменяющие шрифты существуют только для семейства форматов WordProcessing. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IFontInfo](./ifontinfo) | Общий интерфейс для всех шрифтов, которые могут быть извлечены из всех поддерживаемых семейств форматов документов: PDF, WordProcessing, Spreadsheet и Presentation. |
| [IFontSource](./ifontsource) | Маркерный интерфейс для источников шрифтов. |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [FontFormat](./fontformat) | Представляет все форматы шрифтов, которые могут присутствовать у наследников [`IFontInfo`](../groupdocs.viewer.fonts/ifontinfo). |
| [SearchOption](./searchoption) | Указывает, следует ли искать в текущей папке или в текущей папке и всех её подпапках. |

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Viewer.dll -->
