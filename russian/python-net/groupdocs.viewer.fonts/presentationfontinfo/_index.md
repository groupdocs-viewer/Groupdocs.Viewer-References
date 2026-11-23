---
title: "PresentationFontInfo класс"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет метаданные и бинарные данные шрифта из документа Presentation, загруженного в экземпляр Viewer."
type: docs
url: /ru/python-net/groupdocs.viewer.fonts/presentationfontinfo/
is_root: false
weight: 80
---


## PresentationFontInfo class

Представляет метаинформацию и бинарные данные шрифта из документа Presentation, загруженного в экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). Шрифт используется в содержимом документа и может быть встроен в документ или установлен в операционной системе, где работает просмотрщик.

Тип PresentationFontInfo раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/__init__/) |  |

### Методы
| Метод | Описание |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css/#output) | Сериализует эту информацию о шрифте как правило @font-face и записывает её в указанный текстовый писатель. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css_text_writer/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/content/) | Содержимое этого шрифта в виде массива байтов. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/family_name/) | Семейное имя шрифта без стиля; никогда не None и не пустая строка. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/format/) | Формат этого шрифта. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/) | Свойство указывает, встроен ли шрифт в документ и загружен в экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`), или это системный шрифт (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/style/) | Стиль шрифта — может быть Regular, Bold, Italic или Bold Italic. |

### См. также
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
