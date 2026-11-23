---
title: "Clase Rgb24Color"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa color RGB de 24 bits con 8 bits por canal (Rojo, Verde, Azul) y sin transparencia."
type: docs
url: /es/python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 80
---


## Rgb24Color class

Representa color RGB de 24 bits con 8 bits por canal (Rojo, Verde, Azul) y sin transparencia.

Este tipo está diseñado para ser útil en (pero no limitado a) operaciones CSS. Ver más: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

El tipo Rgb24Color expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/) |  |

### Métodos
| Método | Descripción |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Determina si este color es igual al [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) especificado. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Comprueba la igualdad de este color con el color [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) especificado. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#obj) | Comprueba este color contra el color no convertido especificado. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#red-green-blue) | Crea un valor [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) a partir de los valores de los canales rojo, verde y azul especificados. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/) | Devuelve la luminosidad/brillo Hue‑Saturation‑Lightness (HSL) para esta instancia de [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hash_code/) | Devuelve un código hash que define el color actual. No es compatible con `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/) | Devuelve el componente matiz del color en el espacio de color HSL, expresado en grados. Si el color es escala de grises (R == G == B), el matiz es indefinido y el método devuelve 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/) | La saturación Hue‑Saturation‑Lightness (HSL) para esta instancia de [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/) | Devuelve el valor ARGB de esta instancia de [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/), compatible con `System.Drawing.Color`. |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/) | Devuelve este color en representación de cadena hexadecimal. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/) | Serializa esta instancia de [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) a la notación de función CSS 'rgb'. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_string/) | Serializa esta instancia de [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) al formato 'rgb(r, g, b)'. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b/) | El componente azul del color como un entero sin signo de 8 bits [0..255]. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g/) | El componente verde del color como un entero sin signo de 8 bits en el rango 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default/) | La propiedad indica si esta instancia de [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) es la predeterminada (Negro) – los tres canales están establecidos en 0. |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r/) | El componente rojo del color como un entero sin signo de 8 bits (0..255). |

### Ver también
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
