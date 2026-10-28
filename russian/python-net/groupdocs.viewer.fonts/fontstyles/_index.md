---
title: "Класс FontStyles"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет 4 возможных варианта стиля шрифта, используемых в документе: Regular, Bold, Italic или Bold Italic."
type: docs
url: /ru/python-net/groupdocs.viewer.fonts/fontstyles/
is_root: false
weight: 40
---


## FontStyles class

Представляет 4 возможных варианта стиля шрифта, используемых в документе: Regular, Bold, Italic или Bold Italic.

Неизменяемая структура с удобным API и операциями комбинирования.

Тип FontStyles раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/__init__/#is_bold-is_italic) | Инициализирует экземпляр FontStyles из указанных флагов bold и italic. |

### Методы
| Метод | Описание |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals/#other) | Указывает, равен ли данный экземпляр FontStyles указанному экземпляру. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals/#other) | Указывает, равен ли данный экземпляр [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) указанному объекту без приведения типов. |
| [equals_font_styles](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals_font_styles/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/get_hash_code/) | Возвращает хеш-код этого экземпляра. |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/to_string/) | Возвращает имя данного стиля шрифта, то же самое, что у [`FontStyles.name`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/name/). |
| [try_parse](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/#style-parsed) | Пытается разобрать указанную строку как имя стиля шрифта. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [is_bold](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/is_bold/) | Свойство указывает, включён ли флаг жирного начертания у данного экземпляра [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) (`True`) или отключён (`False`). |
| [is_italic](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/is_italic/) | Состояние флага курсив у данного экземпляра [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/); True, если включён, False, если отключён. |
| [name](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/name/) | Имя данного стиля шрифта. |

### Поля
| Поле | Описание |
| :- | :- |
| [REGULAR](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/) | Обычный стиль шрифта, значение по умолчанию (без жирного и курсивного). |
| [BOLD](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/bold/) | Жирный стиль шрифта (только жирный, без курсивного). |
| [ITALIC](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/italic/) | Курсивный стиль шрифта (только курсив, без жирного). |
| [BOLD_ITALIC](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/bold_italic/) | Жирно-курсивный стиль шрифта (жирный и курсив вместе). |

### См. также
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
