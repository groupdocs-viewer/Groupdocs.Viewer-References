---
title: "classe Argb32Color"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente une couleur 32 bits au format ARGB, avec 8 bits pour chaque canal (Alpha, Rouge, Vert, Bleu)."
type: docs
url: /fr/python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

Représente une couleur 32 bits au format ARGB, avec 8 bits par canal (Alpha, Rouge, Vert, Bleu). Prend en charge la transparence.

Ce type est conçu pour être utile aux opérations CSS (mais pas uniquement). En savoir plus : https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Le type Argb32Color expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### Méthodes
| Méthode | Description |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Vérifie si cette couleur est égale à la [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) spécifiée. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | Détermine si cette couleur est égale à la [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) spécifiée. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | Vérifie si cette couleur est égale à la couleur non convertie spécifiée. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_rgb_24_color/) |  |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | Crée une instance Argb32Color à partir d'une valeur ARGB 32 bits, compatible avec les valeurs produites par `System.Drawing.Color.ToArgb()`. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Crée une nouvelle instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) à partir de l'instance spécifiée, mais avec une valeur alpha (opacité) redéfinie. |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | Crée une nouvelle instance Argb32Color à partir d'un Rgb24Color spécifié, mais avec une valeur alpha (opacité) spécifiée. |
| [from_other_with_alpha_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_argb_32_color/) |  |
| [from_other_with_alpha_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | Crée une valeur Argb32Color à partir des canaux Rouge, Vert, Bleu spécifiés, le canal Alpha étant réglé sur totalement opaque. |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | Crée une valeur [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) à partir des valeurs spécifiées des canaux rouge, vert, bleu et alpha. |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | Crée une couleur totalement opaque (A=255) à partir d'une valeur d'octet unique appliquée à tous les canaux. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | Renvoie la luminosité (lightness/brightness) Hue‑Saturation‑Lightness (HSL) de cette instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | Renvoie un code de hachage qui définit la couleur actuelle ; non compatible avec `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | Renvoie la valeur de teinte Hue‑Saturation‑Lightness (HSL), en degrés, de cette instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) ; si R == G == B, la teinte n'a aucun sens et la méthode renvoie 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | Renvoie la saturation Hue‑Saturation‑Lightness (HSL) de cette instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/). |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | Renvoie la valeur ARGB de cette instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/), compatible avec la méthode `System.Drawing.Color.ToArgb()`. |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | Sérialise cette instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) en notation hexadécimale `##RRGGBB` sous forme de chaîne sans le canal alpha. |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | Sérialise cette instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) en notation hexadécimale `##RRGGBBAA` sous forme de chaîne avec le canal alpha. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | Sérialise cette instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) en notation de fonction CSS `rgb`, en omettant le canal alpha. |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | Sérialise cette instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) en notation de fonction CSS 'rgba'. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | Sérialise l'instance Argb32Color en la notation de fonction CSS la plus appropriée selon la translucidité. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | Le composant alpha de la couleur sous forme d'entier non signé de 8 bits dans la plage 0..255. |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | Le composant alpha de la couleur sous forme de nombre flottant dans la plage 0..1. |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | Le composant bleu de la couleur sous forme d'entier non signé de 8 bits dans la plage 0..255. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | Le composant vert de la couleur sous forme d'entier non signé de 8 bits dans la plage 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | La propriété indique si cette instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) est par défaut (transparente), ce qui signifie que les quatre canaux sont réglés à 0 ; elle est équivalente à [`Argb32Color.is_empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/). |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | La propriété indique si cette instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) est non initialisée (les quatre canaux sont réglés à 0). Elle est équivalente à la couleur par défaut ou transparente et correspond à [`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/). |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | La propriété indique si cette instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) est totalement opaque, sans transparence (son canal Alpha a la valeur maximale). |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | La propriété indique si cette instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) est totalement transparente — son canal Alpha a la valeur minimale (0), de sorte que les canaux R, G et B n'ont aucun effet visible. |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | La propriété indique si cette instance [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) est translucide (ni totalement transparente, ni totalement opaque). |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | Le composant rouge de la couleur sous forme d'entier non signé de 8 bits (0..255). |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | La représentation de la couleur sous forme d'entier signé de 32 bits. |

### Champs
| Champ | Description |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | Renvoie une couleur vide, qui n'a aucune information de canal et est totalement transparente. Identique à ''. Valeur par défaut. |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | Couleur vide totalement transparente. Identique à la valeur de couleur par défaut ''. |

### Exemple

```python
from groupdocs.viewer.drawing import Argb32Color

# Créez une couleur jaune totalement opaque (RGB 255, 255, 0)
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### Voir aussi
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
