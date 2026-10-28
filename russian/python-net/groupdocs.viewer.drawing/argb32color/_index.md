---
title: "Класс Argb32Color"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет 32‑битный цвет в формате ARGB, по 8 бит на каждый канал (Alpha, Red, Green, Blue)."
type: docs
url: /ru/python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

Представляет 32‑битный цвет в формате ARGB, по 8 бит на каждый канал (Alpha, Red, Green, Blue). Поддерживает прозрачность.

Этот тип разработан для использования в операциях CSS (но не только). Подробнее: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Тип Argb32Color раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### Методы
| Метод | Описание |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Проверяет, равен ли этот цвет указанному [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Определяет, равен ли этот цвет указанному [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | Проверяет, совпадает ли этот цвет с указанным неконвертированным цветом. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_rgb_24_color/) |  |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | Создаёт экземпляр Argb32Color из 32‑битного значения ARGB, совместимого со значениями, полученными с помощью `System.Drawing.Color.ToArgb()`. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Создаёт новый экземпляр [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) из указанного экземпляра, но с переопределённым значением альфа (непрозрачности). |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Создаёт новый экземпляр Argb32Color из указанного Rgb24Color, но с заданным значением альфа (непрозрачности). |
| [from_other_with_alpha_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_argb_32_color/) |  |
| [from_other_with_alpha_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | Создаёт значение Argb32Color из указанных каналов Red, Green, Blue, при этом канал Alpha устанавливается полностью непрозрачным. |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | Создаёт значение [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) из указанных значений каналов red, green, blue и alpha. |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | Создаёт полностью непрозрачный (A=255) цвет из одного байтового значения, применённого ко всем каналам. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | Возвращает светлоту (lightness) модели Hue‑Saturation‑Lightness (HSL) для данного экземпляра [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | Возвращает хеш‑код, определяющий текущий цвет; не совместим с `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | Возвращает значение оттенка (hue) модели Hue‑Saturation‑Lightness (HSL) в градусах для данного экземпляра [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/); если R == G == B, оттенок не имеет смысла, и метод возвращает 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | Возвращает насыщенность (saturation) модели Hue‑Saturation‑Lightness (HSL) для данного экземпляра [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | Возвращает значение ARGB данного экземпляра [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/), совместимое с методом `System.Drawing.Color.ToArgb()`. |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | Сериализует этот [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) экземпляр в шестнадцатеричную нотацию `##RRGGBB` в виде строки без альфа‑канала. |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | Сериализует этот [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) экземпляр в шестнадцатеричную нотацию `##RRGGBBAA` в виде строки с альфа‑каналом. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | Сериализует этот [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) экземпляр в нотацию CSS функции `rgb`, опуская альфа‑канал. |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | Сериализует этот [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) экземпляр в нотацию CSS функции 'rgba'. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | Сериализует экземпляр Argb32Color в наиболее подходящую нотацию CSS функции в зависимости от полупрозрачности. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | Компонент альфа цвета в виде 8‑битного беззнакового целого в диапазоне 0..255. |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | Компонент альфа цвета в виде числа с плавающей точкой в диапазоне 0..1. |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | Компонент синего цвета в виде 8‑битного беззнакового целого в диапазоне 0..255. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | Компонент зелёного цвета в виде 8‑битного беззнакового целого в диапазоне 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | Свойство указывает, является ли данный [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) экземпляр значением по умолчанию (прозрачным), что означает, что все четыре канала установлены в 0; это эквивалентно [`Argb32Color.is_empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/). |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | Свойство указывает, является ли данный [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) экземпляр неинициализированным (все четыре канала установлены в 0). Это эквивалентно цвету по умолчанию или прозрачному цвету и соответствует [`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/). |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | Свойство указывает, является ли данный [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) экземпляр полностью непрозрачным, без прозрачности (его альфа‑канал имеет максимальное значение). |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | Свойство указывает, является ли данный [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) экземпляр полностью прозрачным — его альфа‑канал имеет минимальное (0) значение, поэтому каналы R, G и B не оказывают видимого эффекта. |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | Свойство указывает, является ли данный [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) экземпляр полупрозрачным (не полностью прозрачным, но и не полностью непрозрачным). |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | Компонент красного цвета в виде 8‑битного беззнакового целого (0..255). |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | 32‑битное знаковое целочисленное представление цвета. |

### Поля
| Поле | Описание |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | Возвращает пустой цвет, у которого нет информации о каналах и который полностью прозрачен. То же, что '' . Значение по умолчанию. |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | Полностью прозрачный пустой цвет. То же, что значение цвета по умолчанию '' . |

### Пример

```python
from groupdocs.viewer.drawing import Argb32Color

# Создайте полностью непрозрачный желтый цвет (RGB 255, 255, 0)
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### См. также
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
