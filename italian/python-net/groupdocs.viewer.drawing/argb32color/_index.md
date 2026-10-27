---
title: "Classe Argb32Color"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta un colore a 32 bit in formato ARGB, con 8 bit per ogni canale (Alpha, Rosso, Verde, Blu)."
type: docs
url: /it/python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

Rappresenta il colore a 32 bit in formato ARGB, con 8 bit per ogni canale (Alpha, Rosso, Verde, Blu). Supporta la trasparenza.

Questo tipo è progettato per essere utile per (ma non limitato a) operazioni CSS. Vedi di più: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Il tipo Argb32Color espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Verifica se questo colore è uguale al [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) specificato. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Determina se questo colore è uguale al [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) specificato. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | Verifica se questo colore è uguale al colore non convertito specificato. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_rgb_24_color/) |  |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | Crea un'istanza Argb32Color da un valore ARGB a 32 bit, compatibile con i valori prodotti da `System.Drawing.Color.ToArgb()`. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Crea una nuova istanza [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) dall'istanza specificata, ma con un valore alfa (opacità) ridefinito. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Crea una nuova istanza Argb32Color da un Rgb24Color specificato, ma con un valore alfa (opacità) specificato. |
| [from_other_with_alpha_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_argb_32_color/) |  |
| [from_other_with_alpha_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | Crea un valore Argb32Color dai canali Rosso, Verde, Blu specificati, con il canale Alpha impostato a piena opacità. |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | Crea un valore [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) dai valori dei canali rosso, verde, blu e alfa specificati. |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | Crea un colore completamente opaco (A=255) da un unico valore byte applicato a tutti i canali. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | Restituisce la luminosità (lightness) Hue‑Saturation‑Lightness (HSL) di questa [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) istanza. |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | Restituisce un codice hash che definisce il colore corrente; non compatibile con `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | Restituisce il valore di tonalità (hue) Hue‑Saturation‑Lightness (HSL), in gradi, per questa [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) istanza; se R == G == B, la tonalità è priva di significato e il metodo restituisce 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | Restituisce la saturazione Hue‑Saturation‑Lightness (HSL) di questa [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) istanza. |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | Restituisce il valore ARGB di questa [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) istanza, compatibile con il metodo `System.Drawing.Color.ToArgb()`. |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | Serializza questa istanza di [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) nella notazione esadecimale `##RRGGBB` come stringa senza il canale alfa. |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | Serializza questa istanza di [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) nella notazione esadecimale `##RRGGBBAA` come stringa con il canale alfa. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | Serializza questa istanza di [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) nella notazione della funzione CSS `rgb`, omettendo il canale alfa. |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | Serializza questa istanza di [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) nella notazione della funzione CSS 'rgba'. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | Serializza l'istanza di Argb32Color nella notazione della funzione CSS più appropriata in base alla traslucenza. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | Il componente alfa del colore come intero senza segno a 8 bit nell'intervallo 0..255. |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | Il componente alfa del colore come valore in virgola mobile nell'intervallo 0..1. |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | Il componente blu del colore come intero senza segno a 8 bit nell'intervallo 0..255. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | Il componente verde del colore come intero senza segno a 8 bit nell'intervallo 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | La proprietà indica se questa istanza di [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) è predefinita (trasparente), il che significa che tutti e quattro i canali sono impostati a 0; è equivalente a [`Argb32Color.is_empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/). |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | La proprietà indica se questa istanza di [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) non è inizializzata (tutti e quattro i canali sono impostati a 0). È equivalente al colore predefinito o trasparente e corrisponde a [`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/). |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | La proprietà indica se questa istanza di [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) è completamente opaca, senza trasparenza (il suo canale Alpha ha valore massimo). |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | La proprietà indica se questa istanza di [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) è completamente trasparente—il suo canale Alpha ha il valore minimo (0), quindi i canali R, G e B non hanno alcun effetto visibile. |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | La proprietà indica se questa istanza di [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) è translucida (non completamente trasparente, ma neanche completamente opaca). |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | Il componente rosso del colore come intero senza segno a 8 bit (0..255). |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | La rappresentazione del colore come intero con segno a 32 bit. |

### Campi
| Campo | Descrizione |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | Restituisce un colore vuoto, che non ha informazioni sui canali ed è completamente trasparente. Identico a ''. Valore predefinito. |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | Colore vuoto completamente trasparente. Identico al valore di colore predefinito ''. |

### Esempio

```python
from groupdocs.viewer.drawing import Argb32Color

# Crea un colore giallo completamente opaco (RGB 255, 255, 0)
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### Vedi anche
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
