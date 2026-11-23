---
title: "Класс IFontInfo"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет общий интерфейс для всех шрифтов, которые могут быть извлечены из всех поддерживаемых семейств форматов документов: PDF, WordProcessing, Spreadsheet и Presentation."
type: docs
url: /ru/python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

Представляет общий интерфейс для всех шрифтов, которые могут быть извлечены из всех поддерживаемых семейств форматов документов: PDF, WordProcessing, Spreadsheet и Presentation.

Тип IFontInfo раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | Сериализует эту информацию о шрифте как правило @font-face и записывает её в указанный текстовый писатель. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | Бинарное содержимое шрифта в виде массива байтов, если доступно, или None, если нет. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | Семейное имя шрифта в виде строки. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | Формат этого шрифта как перечисление — TrueType, TrueType Collection, OpenType, Embedded OpenType или `FontFormat.unknown`. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | Стиль шрифта как перечисление (Regular, Bold, Italic или Bold Italic); некоторые форматы документов могут поддерживать только [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/). |

### См. также
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
