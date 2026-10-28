---
title: "Argb32Color-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar 32-bitars färg i ARGB-format, med 8 bitar per varje kanal (Alfa, Röd, Grön, Blå)."
type: docs
url: /sv/python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

Representerar 32-bitars färg i ARGB-format, med 8 bitar per kanal (Alfa, Röd, Grön, Blå). Stöder transparens.

Denna typ är avsedd att vara användbar för (men inte begränsad till) CSS-operationer. Se mer: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Typen Argb32Color exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Kontrollerar om denna färg är lika med den angivna [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Bestämmer om denna färg är lika med den angivna [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | Kontrollerar om denna färg är lika med den angivna okastade färgen. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_rgb_24_color/) |  |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | Skapar en Argb32Color-instans från ett 32-bitars ARGB‑värde, kompatibelt med värden som produceras av `System.Drawing.Color.ToArgb()`. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Skapar en ny [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑instans från den angivna instansen, men med ett omdefinierat alfa‑ (opacitets)värde. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Skapar en ny Argb32Color‑instans från en angiven Rgb24Color, men med ett angivet alfa‑ (opacitets)värde. |
| [from_other_with_alpha_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_argb_32_color/) |  |
| [from_other_with_alpha_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | Skapar ett Argb32Color‑värde från angivna Röd-, Grön- och Blå‑kanaler, med Alfa‑kanalen satt till helt ogenomskinlig. |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | Skapar ett [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑värde från angivna röd-, grön-, blå- och alfa‑kanalvärden. |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | Skapar en helt ogenomskinlig (A=255) färg från ett enda byte‑värde som tillämpas på alla kanaler. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | Returnerar Hue‑Saturation‑Lightness (HSL) ljusstyrka/ljushet för detta [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑instans. |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | Returnerar en hash‑kod som definierar den aktuella färgen; inte kompatibel med `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | Returnerar Hue‑Saturation‑Lightness (HSL) nyansvärde i grader för detta [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑instans; om R == G == B är nyansen meningslös och metoden returnerar 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | Returnerar Hue‑Saturation‑Lightness (HSL) mättnad för detta [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑instans. |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | Returnerar ARGB‑värdet för detta [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑instans, kompatibelt med `System.Drawing.Color.ToArgb()`‑metoden. |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | Serialiserar detta [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑instans till den hexadecimala notationen `##RRGGBB` som en sträng utan alfakanalen. |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | Serialiserar detta [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑instans till den hexadecimala notationen `##RRGGBBAA` som en sträng med alfakanal. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | Serialiserar detta [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑instans till `rgb`‑CSS‑funktionsnotationen, utan alfakanalen. |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | Serialiserar detta [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑instans till 'rgba'‑CSS‑funktionsnotationen. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | Serialiserar Argb32Color‑instansen till den mest lämpliga CSS‑funktionsnotationen beroende på genomskinlighet. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | Alfakomponenten i färgen som ett 8‑bitars osignerat heltal i intervallet 0..255. |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | Alfakomponenten i färgen som ett flyttal i intervallet 0..1. |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | Blåkomponenten i färgen som ett 8‑bitars osignerat heltal i intervallet 0..255. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | Grönkomponenten i färgen som ett 8‑bitars osignerat heltal i intervallet 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | Egenskapen indikerar om detta [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑instans är standard (transparent), vilket betyder att alla fyra kanaler är satta till 0; den är ekvivalent med [`Argb32Color.is_empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/). |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | Egenskapen indikerar om detta [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑instans är oinitierad (alla fyra kanaler är satta till 0). Den är ekvivalent med standard‑ eller transparent färg och matchar [`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/). |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | Egenskapen indikerar om detta [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑instans är helt ogenomskinlig, utan transparens (dess alfakanal har maximalt värde). |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | Egenskapen indikerar om detta [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑instans är helt transparent—dess alfakanal har det minsta (0) värdet, så R‑, G‑ och B‑kanalerna har ingen synlig effekt. |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | Egenskapen indikerar om detta [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)‑instans är genomskinlig (varken helt transparent eller helt ogenomskinlig). |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | Rödkomponenten i färgen som ett 8‑bitars osignerat heltal (0..255). |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | Den 32‑bitars signerade heltalsrepresentationen av färgen. |

### Fält
| Fält | Beskrivning |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | Returnerar en tom färg, som saknar kanalinformation och är helt transparent. Samma som ''. Standardvärde. |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | Helt transparent tom färg. Samma som standardvärdet '' för färg. |

### Exempel

```python
from groupdocs.viewer.drawing import Argb32Color

# Skapa en helt ogenomskinlig gul färg (RGB 255, 255, 0)
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### Se även
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
