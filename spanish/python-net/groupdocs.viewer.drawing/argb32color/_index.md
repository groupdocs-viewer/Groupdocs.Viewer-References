---
title: "Clase Argb32Color"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa un color de 32 bits en formato ARGB, con 8 bits por cada canal (Alfa, Rojo, Verde, Azul)."
type: docs
url: /es/python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

Representa color de 32 bits en formato ARGB, con 8 bits por cada canal (Alfa, Rojo, Verde, Azul). Soporta transparencia.

Este tipo está diseñado para ser útil en (pero no limitado a) operaciones CSS. Ver más: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

El tipo Argb32Color expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### Métodos
| Método | Descripción |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Comprueba si este color es igual al [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) especificado. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Determina si este color es igual al [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) especificado. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | Comprueba si este color es igual al color no convertido especificado. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_rgb_24_color/) |  |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | Crea una instancia de Argb32Color a partir de un valor ARGB de 32 bits, compatible con los valores producidos por `System.Drawing.Color.ToArgb()`. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Crea una nueva instancia de [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) a partir de la instancia especificada, pero con un valor alfa (opacidad) redefinido. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Crea una nueva instancia de Argb32Color a partir de un Rgb24Color especificado, pero con un valor alfa (opacidad) especificado. |
| [from_other_with_alpha_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_argb_32_color/) |  |
| [from_other_with_alpha_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | Crea un valor Argb32Color a partir de los canales Rojo, Verde y Azul especificados, con el canal Alfa configurado como completamente opaco. |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | Crea un valor de [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) a partir de los valores especificados de los canales rojo, verde, azul y alfa. |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | Crea un color completamente opaco (A=255) a partir de un único valor de byte aplicado a todos los canales. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | Devuelve la luminosidad/brillo Hue‑Saturation‑Lightness (HSL) para esta instancia de [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | Devuelve un código hash que define el color actual; no es compatible con `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | Devuelve el valor de matiz Hue‑Saturation‑Lightness (HSL), en grados, para esta instancia de [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/); si R == G == B, el matiz no tiene sentido y el método devuelve 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | Devuelve la saturación Hue‑Saturation‑Lightness (HSL) de esta instancia de [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | Devuelve el valor ARGB de esta instancia de [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/), compatible con el método `System.Drawing.Color.ToArgb()`. |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | Serializa esta instancia [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) a la notación hexadecimal `##RRGGBB` como una cadena sin el canal alfa. |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | Serializa esta instancia [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) a la notación hexadecimal `##RRGGBBAA` como una cadena con canal alfa. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | Serializa esta instancia [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) a la notación de la función CSS `rgb`, omitiendo el canal alfa. |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | Serializa esta instancia [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) a la notación de la función CSS 'rgba'. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | Serializa la instancia Argb32Color a la notación de función CSS más apropiada según la translucidez. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | El componente alfa del color como un entero sin signo de 8 bits en el rango 0..255. |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | El componente alfa del color como un número de punto flotante en el rango 0..1. |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | El componente azul del color como un entero sin signo de 8 bits en el rango 0..255. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | El componente verde del color como un entero sin signo de 8 bits en el rango 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | La propiedad indica si esta instancia [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) es predeterminada (transparente), lo que significa que los cuatro canales están establecidos en 0; es equivalente a [`Argb32Color.is_empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/). |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | La propiedad indica si esta instancia [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) está sin inicializar (los cuatro canales están establecidos en 0). Es equivalente al color predeterminado o transparente y coincide con [`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/). |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | La propiedad indica si esta instancia [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) es completamente opaca, sin transparencia (su canal Alfa tiene el valor máximo). |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | La propiedad indica si esta instancia [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) es completamente transparente—su canal Alfa tiene el valor mínimo (0), por lo que los canales R, G y B no tienen efecto visible. |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | La propiedad indica si esta instancia [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) es translúcida (no completamente transparente, pero tampoco completamente opaca). |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | El componente rojo del color como un entero sin signo de 8 bits (0..255). |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | La representación del color como entero con signo de 32 bits. |

### Campos
| Campo | Descripción |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | Devuelve un color vacío, que no tiene información de canales y es completamente transparente. Igual que ''. Valor predeterminado. |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | Color vacío totalmente transparente. Igual que el valor predeterminado '' del color. |

### Ejemplo

```python
from groupdocs.viewer.drawing import Argb32Color

# Crea un color amarillo totalmente opaco (RGB 255, 255, 0)
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### Ver también
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
