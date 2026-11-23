---
title: "Rgb24Color-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar 24-bitars RGB-färg med 8 bitar per kanal (Röd, Grön, Blå) och utan transparens."
type: docs
url: /sv/python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 80
---


## Rgb24Color class

Representerar 24-bitars RGB-färg med 8 bitar per kanal (Röd, Grön, Blå) och utan transparens.

Denna typ är avsedd att vara användbar för (men inte begränsad till) CSS-operationer. Se mer: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Typen Rgb24Color exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/) |  |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Bestämmer om den här färgen är lika med den angivna [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Kontrollerar om den här färgen är lika med den angivna [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) färgen. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#obj) | Kontrollerar den här färgen mot den angivna okastade färgen. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#red-green-blue) | Skapar ett [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) värde från de angivna röd-, grön- och blåkanalvärdena. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/) | Returnerar Hue‑Saturation‑Lightness (HSL) ljusstyrka för detta [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)‑instans. |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hash_code/) | Returnerar en hashkod som definierar den aktuella färgen. Inte kompatibel med `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/) | Returnerar nyanskomponenten för färgen i HSL-färgrymden, uttryckt i grader. Om färgen är gråskala (R == G == B) är nyansen odefinierad och metoden returnerar 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/) | Hue‑Saturation‑Lightness (HSL) mättnad för detta [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)‑instans. |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/) | Returnerar ARGB‑värdet för detta [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)‑instans, kompatibelt med `System.Drawing.Color`. |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/) | Returnerar den här färgen i hexadecimal strängrepresentation. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/) | Serialiserar detta [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)‑instans till 'rgb'-CSS-funktionsnotation. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_string/) | Serialiserar detta [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)‑instans till formatet 'rgb(r, g, b)'. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b/) | Den blå komponenten i färgen som ett 8-bitars osignerat heltal [0..255]. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g/) | Grönkomponenten i färgen som ett 8‑bitars osignerat heltal i intervallet 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default/) | Egenskapen indikerar om detta [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/)‑instans är standard (Svart) – alla tre kanaler är satta till 0. |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r/) | Rödkomponenten i färgen som ett 8‑bitars osignerat heltal (0..255). |

### Se även
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
