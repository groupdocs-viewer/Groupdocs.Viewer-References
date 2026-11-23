---
title: "Classe Rgb24Color"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta il colore RGB a 24 bit con 8 bit per canale (Rosso, Verde, Blu) e senza trasparenza."
type: docs
url: /it/python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 80
---


## Rgb24Color class

Rappresenta il colore RGB a 24 bit con 8 bit per canale (Rosso, Verde, Blu) e senza trasparenza.

Questo tipo è progettato per essere utile per (ma non limitato a) operazioni CSS. Vedi di più: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Il tipo Rgb24Color espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/) |  |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Determina se questo colore è uguale al [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) specificato. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Verifica se questo colore è uguale al colore [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) specificato. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#obj) | Verifica questo colore rispetto al colore non convertito specificato. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#red-green-blue) | Crea un valore [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) dai valori dei canali rosso, verde e blu specificati. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/) | Restituisce la luminosità Hue‑Saturation‑Lightness (HSL) per questa istanza di [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hash_code/) | Restituisce un codice hash che definisce il colore corrente. Non compatibile con `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/) | Restituisce il componente tonalità (hue) del colore nello spazio colore HSL, espresso in gradi. Se il colore è in scala di grigi (R == G == B), la tonalità è indefinita e il metodo restituisce 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/) | La saturazione Hue‑Saturation‑Lightness (HSL) per questa istanza di [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/) | Restituisce il valore ARGB di questa istanza di [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/), compatibile con `System.Drawing.Color`. |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/) | Restituisce questo colore in rappresentazione stringa esadecimale. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/) | Serializza questa istanza di [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) nella notazione della funzione CSS 'rgb'. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_string/) | Serializza questa istanza di [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) nel formato 'rgb(r, g, b)'. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b/) | Il componente blu del colore come intero senza segno a 8 bit [0..255]. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g/) | Il componente verde del colore come intero senza segno a 8 bit nell'intervallo 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default/) | La proprietà indica se questa istanza di [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) è il valore predefinito (Nero) – tutti e tre i canali sono impostati a 0. |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r/) | Il componente rosso del colore come intero senza segno a 8 bit (0..255). |

### Vedi anche
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
