---
title: "Класс Rgb24Color"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет 24‑битный RGB‑цвет с 8 битами на канал (Red, Green, Blue) без прозрачности."
type: docs
url: /ru/python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 80
---


## Rgb24Color class

Представляет 24‑битный RGB‑цвет с 8 битами на канал (Red, Green, Blue) без прозрачности.

Этот тип разработан для использования в операциях CSS (но не только). Подробнее: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Тип Rgb24Color раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/) |  |

### Методы
| Метод | Описание |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Определяет, равен ли этот цвет указанному [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Проверяет равенство этого цвета указанному цвету [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#obj) | Проверяет этот цвет относительно указанного неприведённого цвета. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#red-green-blue) | Создаёт значение [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) из указанных значений каналов красного, зелёного и синего. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/) | Возвращает светлоту/яркость в модели Hue‑Saturation‑Lightness (HSL) для данного экземпляра [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hash_code/) | Возвращает хеш‑код, определяющий текущий цвет. Не совместим с `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/) | Возвращает компонент оттенка (hue) цвета в цветовом пространстве HSL, выраженный в градусах. Если цвет является оттенком серого (R == G == B), оттенок не определён, и метод возвращает 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/) | Насыщенность Hue‑Saturation‑Lightness (HSL) для данного экземпляра [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/) | Возвращает значение ARGB данного экземпляра [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/), совместимое с `System.Drawing.Color`. |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/) | Возвращает этот цвет в шестнадцатеричном строковом представлении. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/) | Сериализует данный экземпляр [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) в нотацию CSS функции 'rgb'. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_string/) | Сериализует данный экземпляр [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) в формат 'rgb(r, g, b)'. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b/) | Синий компонент цвета как 8‑битное беззнаковое целое [0..255]. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g/) | Компонент зелёного цвета в виде 8‑битного беззнакового целого в диапазоне 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default/) | Свойство указывает, является ли данный экземпляр [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) значением по умолчанию (чёрным) — все три канала установлены в 0. |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r/) | Компонент красного цвета в виде 8‑битного беззнакового целого (0..255). |

### См. также
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
