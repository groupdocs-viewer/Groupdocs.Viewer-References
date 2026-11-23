---
title: "Класс SpreadsheetFontInfo"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инкапсулирует метаданные и бинарные данные шрифта из электронного документа, загруженного в экземпляр Viewer."
type: docs
url: /ru/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

Инкапсулирует метаинформацию и бинарные данные шрифта из электронного документа, загруженного в экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). Электронные таблицы не могут содержать встроенные шрифты, поэтому шрифт, возвращаемый методом [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/), устанавливается в операционной системе, где работает просмотрщик.

Тип SpreadsheetFontInfo раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### Методы
| Метод | Описание |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | Сериализует информацию о шрифте как правило @font-face и записывает её в указанный текстовый писатель. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | Набор символов этого шрифта. |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | Цвет этого шрифта. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | Содержимое этого шрифта в виде массива байтов. Если доступны только метаданные этого шрифта и его бинарное содержимое недоступно, свойство возвращает None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | Имя семейства шрифта без стиля никогда не является null или пустой строкой. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | Формат этого шрифта. |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | У шрифта есть один перечёркнутый стиль. |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | У шрифта есть подчеркивание. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | Стиль этого шрифта — может быть Regular, Bold, Italic или Bold Italic. |

### См. также
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
