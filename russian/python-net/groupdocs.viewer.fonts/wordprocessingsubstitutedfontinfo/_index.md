---
title: "Класс WordProcessingSubstitutedFontInfo"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инкапсулирует метаинформацию и бинарные данные одного шрифта из документа WordProcessing, который изначально не используется в загруженном документе Viewer, но служит заменяющим шрифтом для тех, которые…"
type: docs
url: /ru/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

Инкапсулирует метаинформацию и бинарные данные одного шрифта из документа WordProcessing, который изначально не используется в загруженном документе экземпляра [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), но служит заменяющим шрифтом для тех, которые не найдены на целевой машине. Заменяющие шрифты существуют только для семейства форматов WordProcessing.

Неизменяемая структура. Ее экземпляры создаются и возвращаются публичным API [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) и обычно не должны создаваться пользователем. Для деталей см. документацию: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

Тип WordProcessingSubstitutedFontInfo раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### Методы
| Метод | Описание |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | Сериализует информацию о шрифте как правило @font-face и записывает её в указанный текстовый писатель. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | Возвращает отладочную строку, содержащую информацию о шрифте в формате "original-name -> substituted-name style, format". |

### Свойства
| Свойство | Описание |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | Содержимое заменяющего шрифта в виде массива байтов. Оно никогда не None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | Семейное имя заменяющего шрифта без стиля. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | Формат этого заменяющего (не оригинального) шрифта. |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | Семейное имя оригинального шрифта, который не найден на целевой машине, без стиля. Никогда не null и не пустая строка. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | Стиль оригинального шрифта — может быть Regular, Bold, Italic или Bold Italic. |

### См. также
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
