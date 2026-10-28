---
title: "WordProcessingFontInfo класс"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инкапсулирует метаинформацию и бинарные данные шрифта из документа WordProcessing, загруженного в экземпляр Viewer."
type: docs
url: /ru/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

Инкапсулирует метаинформацию и бинарные данные шрифта из документа WordProcessing, загруженного в экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Неизменяемая структура.

Её экземпляры создаются и возвращаются публичным API [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), и обычно их не следует создавать пользователю.

Подробности см. в документации: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

Тип WordProcessingFontInfo раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### Методы
| Метод | Описание |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | Сериализует информацию о шрифте как правило @font-face и записывает её в указанный текстовый писатель. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | Возвращает отладочную информацию об этих данных шрифта в виде шаблона: "name style, embedded/system, format". |

### Свойства
| Свойство | Описание |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | Альтернативное семейное имя шрифта. Если отсутствует, возвращается пустая строка. |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | Набор символов этого шрифта. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | Содержимое этого шрифта в виде массива байтов. Если доступна только метаинформация о шрифте и бинарное содержимое недоступно, свойство возвращает None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | Семейное имя шрифта без стиля; никогда не None и не пустая строка. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | Формат этого шрифта. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | Свойство указывает, встроен ли этот шрифт в документ, загружен в экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`), или это системный шрифт (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | Стиль шрифта — может быть Regular, Bold, Italic или Bold Italic. |

### См. также
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
