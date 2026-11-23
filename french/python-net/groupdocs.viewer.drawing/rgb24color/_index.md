---
title: "Classe Rgb24Color"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente une couleur RGB 24 bits avec 8 bits par canal (Rouge, Vert, Bleu) et sans transparence."
type: docs
url: /fr/python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 80
---


## Rgb24Color class

Représente une couleur RGB 24 bits avec 8 bits par canal (Rouge, Vert, Bleu) et sans transparence.

Ce type est conçu pour être utile aux opérations CSS (mais pas uniquement). En savoir plus : https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Le type Rgb24Color expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/) |  |

### Méthodes
| Méthode | Description |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Détermine si cette couleur est égale à la [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) spécifiée. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | Vérifie cette couleur avec la couleur [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) spécifiée pour l’égalité. |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#obj) | Vérifie cette couleur par rapport à la couleur non convertie spécifiée. |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#red-green-blue) | Crée une valeur [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) à partir des valeurs de canaux rouge, vert et bleu spécifiées. |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/) | Renvoie la luminosité (lightness/brightness) de la teinte‑saturation‑luminosité (HSL) pour cette instance [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hash_code/) | Renvoie un code de hachage qui définit la couleur actuelle. Non compatible avec `System.Drawing.Color.GetHashCode`. |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/) | Renvoie le composant teinte (hue) de la couleur dans l’espace colorimétrique HSL, exprimé en degrés. Si la couleur est en niveaux de gris (R == G == B), la teinte est indéfinie et la méthode renvoie 0. |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/) | La saturation de la teinte‑saturation‑luminosité (HSL) pour cette instance [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/). |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/) | Renvoie la valeur ARGB de cette instance [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/), compatible avec `System.Drawing.Color`. |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/) | Renvoie cette couleur sous forme de chaîne hexadécimale. |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/) | Sérialise cette instance [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) au format de fonction CSS 'rgb'. |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_string/) | Sérialise cette instance [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) au format 'rgb(r, g, b)'. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b/) | Le composant bleu de la couleur en tant qu’entier non signé de 8 bits [0..255]. |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g/) | Le composant vert de la couleur sous forme d'entier non signé de 8 bits dans la plage 0..255. |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default/) | La propriété indique si cette instance [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) est la valeur par défaut (Noir) – les trois canaux sont réglés à 0. |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r/) | Le composant rouge de la couleur sous forme d'entier non signé de 8 bits (0..255). |

### Voir aussi
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
