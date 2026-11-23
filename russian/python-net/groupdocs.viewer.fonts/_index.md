---
title: "groupdocs.viewer.fonts"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Конфигурация загрузки шрифтов и их замены."
type: docs
url: /ru/python-net/groupdocs.viewer.fonts/
is_root: false
weight: 40
---


Конфигурация загрузки шрифтов и их замены.

### Классы
| Класс | Описание |
| :- | :- |
| [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) | Представляет папку, содержащую TrueType‑шрифты. |
| [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/) | Предоставляет методы для работы с источниками при поиске TrueType‑шрифтов. |
| [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) | Представляет 4 возможных варианта стиля шрифта, используемых в документе: Regular, Bold, Italic или Bold Italic. |
| [`IFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/) | Представляет общий интерфейс для всех шрифтов, которые могут быть извлечены из всех поддерживаемых семейств форматов документов: PDF, WordProcessing, Spreadsheet и Presentation. |
| [`PdfFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/) | Инкапсулирует метаданные и бинарные данные PDF‑шрифта, загруженного в экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), который может быть встроен в документ или установлен в операционной системе, где работает GroupDocs.Viewer. |
| [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/) | Представляет метаинформацию и бинарные данные шрифта из документа Presentation, загруженного в экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). Шрифт используется в содержимом документа и может быть встроен в документ или установлен в операционной системе, где работает просмотрщик. |
| [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/) | Инкапсулирует метаинформацию и бинарные данные шрифта из электронного документа, загруженного в экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). Электронные таблицы не могут содержать встроенные шрифты, поэтому шрифт, возвращаемый методом [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/), устанавливается в операционной системе, где работает просмотрщик. |
| [`WordProcessingFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/) | Инкапсулирует метаинформацию и бинарные данные шрифта из документа WordProcessing, загруженного в экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/) | Инкапсулирует метаинформацию и бинарные данные одного шрифта из документа WordProcessing, который изначально не используется в загруженном документе экземпляра [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), но служит заменяющим шрифтом для тех, которые не найдены на целевой машине. Заменяющие шрифты существуют только для семейства форматов WordProcessing. |

### Перечисления
| Перечисление | Описание |
| :- | :- |
| [`FontFormat`](/viewer/python-net/groupdocs.viewer.fonts/fontformat/) |  |
| [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) | Представляет маркерный интерфейс для источников шрифтов. |
| [`SearchOption`](/viewer/python-net/groupdocs.viewer.fonts/searchoption/) |  |
