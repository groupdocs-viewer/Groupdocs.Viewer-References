---
title: "Argb32Color klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt een 32-bits kleur voor in ARGB-indeling, met 8 bits per kanaal (Alpha, Rood, Groen, Blauw)."
type: docs
url: /nl/python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

Stelt 32-bit kleur in ARGB-formaat voor, met 8 bits per elk kanaal (Alpha, Red, Green, Blue). Ondersteunt transparantie.

Dit type is ontworpen om nuttig te zijn voor (maar niet beperkt tot) CSS-bewerkingen. Zie meer: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Het Argb32Color-type toont de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Controleert of deze kleur gelijk is aan de opgegeven [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Bepaalt of deze kleur gelijk is aan de opgegeven [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | Controleert of deze kleur gelijk is aan de opgegeven niet-gecastte kleur. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_rgb_24_color/) |  |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | Maakt een Argb32Color‑instantie aan vanuit een 32-bits ARGB‑waarde, compatibel met waarden die worden geproduceerd door `System.Drawing.Color.ToArgb()`. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Maakt een nieuwe [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instantie aan op basis van de opgegeven instantie, maar met een opnieuw gedefinieerde alfa‑(opaciteit)waarde. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Maakt een nieuwe Argb32Color‑instantie aan vanuit een opgegeven Rgb24Color, maar met een opgegeven alfa‑(opaciteit)waarde. |
| [from_other_with_alpha_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_argb_32_color/) |  |
| [from_other_with_alpha_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | Maakt een Argb32Color‑waarde aan vanuit opgegeven rood-, groen- en blauwkanalen, waarbij het Alpha‑kanaal volledig ondoorzichtig wordt ingesteld. |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | Maakt een [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) waarde aan vanuit opgegeven rood-, groen-, blauw- en Alpha‑kanaalwaarden. |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | Maakt een volledig ondoorzichtige (A=255) kleur aan vanuit één byte‑waarde die op alle kanalen wordt toegepast. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | Retourneert de Hue‑Saturation‑Lightness (HSL) helderheid/lichtheid voor deze [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instantie. |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | Retourneert een hash‑code die de huidige kleur definieert; niet compatibel met `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | Retourneert de Hue‑Saturation‑Lightness (HSL) tintwaarde, in graden, voor deze [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instantie; als R == G == B, is de tint betekenisloos en geeft de methode 0 terug. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | Retourneert de Hue‑Saturation‑Lightness (HSL) verzadiging van deze [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instantie. |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | Retourneert de ARGB‑waarde van deze [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instantie, compatibel met de `System.Drawing.Color.ToArgb()`‑methode. |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | Serialiseert deze [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instantie naar de hexadecimale notatie `##RRGGBB` als een string zonder het alfakanaal. |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | Serialiseert deze [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instantie naar de hexadecimale notatie `##RRGGBBAA` als een string met alfakanaal. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | Serialiseert deze [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instantie naar de `rgb` CSS-functienotatie, waarbij het alfakanaal wordt weggelaten. |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | Serialiseert deze [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instantie naar de 'rgba' CSS-functienotatie. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | Serialiseert de Argb32Color‑instantie naar de meest geschikte CSS-functienotatie, afhankelijk van de doorzichtigheid. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | Het alfacomponent van de kleur als een 8‑bit ongetekend geheel getal in het bereik 0..255. |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | Het alfacomponent van de kleur als een float in het bereik 0..1. |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | Het blauwe component van de kleur als een 8‑bit ongetekend geheel getal in het bereik 0..255. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | Het groene component van de kleur als een 8‑bit ongetekend geheel getal in het bereik 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | De eigenschap geeft aan of deze [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instantie de standaard (transparant) is, wat betekent dat alle vier kanalen op 0 zijn ingesteld; dit is equivalent aan [`Argb32Color.is_empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/). |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | De eigenschap geeft aan of deze [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instantie niet geïnitialiseerd is (alle vier kanalen zijn op 0 ingesteld). Dit is equivalent aan de standaard‑ of transparante kleur en komt overeen met [`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/). |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | De eigenschap geeft aan of deze [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instantie volledig ondoorzichtig is, zonder transparantie (het alfakanaal heeft de maximale waarde). |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | De eigenschap geeft aan of deze [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instantie volledig transparant is — het alfakanaal heeft de minimale (0) waarde, waardoor de R-, G- en B-kanalen geen zichtbaar effect hebben. |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | De eigenschap geeft aan of deze [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) instantie doorschijnend is (niet volledig transparant, maar ook niet volledig ondoorzichtig). |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | Het rode component van de kleur als een 8‑bit ongetekend geheel getal (0..255). |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | De 32‑bit ondertekende gehele getalrepresentatie van de kleur. |

### Velden
| Veld | Beschrijving |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | Geeft een lege kleur terug, die geen kanaalinformatie heeft en volledig transparant is. Hetzelfde als ''. Standaardwaarde. |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | Volledig transparante lege kleur. Hetzelfde als de standaard '' kleurwaarde. |

### Voorbeeld

```python
from groupdocs.viewer.drawing import Argb32Color

# Maak een volledig ondoorzichtige gele kleur (RGB 255, 255, 0)
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### Zie ook
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
