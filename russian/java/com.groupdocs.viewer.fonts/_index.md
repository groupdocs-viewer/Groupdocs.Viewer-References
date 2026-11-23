---
title: "com.groupdocs.viewer.fonts"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Пакет предоставляет классы и перечисления для управления шрифтами, используемыми в процессе рендеринга."
type: docs
weight: 16
url: /ru/java/com.groupdocs.viewer.fonts/
---

Пакет предоставляет классы и перечисления для управления шрифтами, используемыми в процессе рендеринга.

Основные классы и интерфейсы в этом пакете:

* [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) - Represents a folder that contains TrueType fonts.
* [FontSettings](../../com.groupdocs.viewer.fonts/fontsettings) - Provides methods for working with sources to look for TrueType fonts.
* [FontSource](../../com.groupdocs.viewer.fonts/fontsource) - Marker interface for the font sources.


Для получения более подробной информации о работе со шрифтами в GroupDocs.Viewer, пожалуйста, обратитесь к
[GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/).



## Классы

| Класс | Описание |
| --- | --- |
| [FolderFontSource](../com.groupdocs.viewer.fonts/folderfontsource) | Представляет папку, содержащую шрифты TrueType. |
| [FontFormat](../com.groupdocs.viewer.fonts/fontformat) | Представляет все форматы шрифтов, которые могут присутствовать в классе UsedFontInfo. |
| [FontSettings](../com.groupdocs.viewer.fonts/fontsettings) | Предоставляет методы для работы с источниками поиска шрифтов TrueType. |
| [FontStyles](../com.groupdocs.viewer.fonts/fontstyles) | Представляет 4 возможных стиля шрифта, используемых в документе: Regular, Bold, Italic или Bold Italic. |
| [PdfFontInfo](../com.groupdocs.viewer.fonts/pdffontinfo) | Инкапсулирует метаинформацию и бинарные данные одного шрифта из PDF‑документа, загруженного в экземпляр Viewer. |
| [PresentationFontInfo](../com.groupdocs.viewer.fonts/presentationfontinfo) | Инкапсулирует метаданные и бинарные данные шрифта, используемого в документе Presentation, загруженного в экземпляр Viewer. |
| [SpreadsheetFontInfo](../com.groupdocs.viewer.fonts/spreadsheetfontinfo) | Инкапсулирует метаинформацию и бинарные данные одного шрифта из документа Spreadsheet, загруженного в экземпляр Viewer. |
| [WordProcessingFontInfo](../com.groupdocs.viewer.fonts/wordprocessingfontinfo) | Инкапсулирует метаинформацию и бинарные данные одного шрифта из документа WordProcessing, загруженного в экземпляр Viewer. |
| [WordProcessingSubstitutedFontInfo](../com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo) | Инкапсулирует метаданные и бинарные данные одного заменённого шрифта, используемого в документе WordProcessing через GroupDocs.Viewer. |

## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [FontSource](../com.groupdocs.viewer.fonts/fontsource) | Маркерный интерфейс для источников шрифтов. |
| [IFontInfo](../com.groupdocs.viewer.fonts/ifontinfo) | Общий интерфейс для всех шрифтов, которые могут быть извлечены из форматов документов: PDF, WordProcessing, Spreadsheet и Presentation. |

## Перечисления

| Перечисление | Описание |
| --- | --- |
| [SearchOption](../com.groupdocs.viewer.fonts/searchoption) | Указывает, следует ли искать в текущей папке или в текущей папке и всех подпапках. |
