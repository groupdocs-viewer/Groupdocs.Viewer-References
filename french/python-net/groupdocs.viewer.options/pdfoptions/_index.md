---
title: "Classe PdfOptions"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente les options pour le rendu de documents PDF."
type: docs
url: /fr/python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

Représente les options pour le rendu de documents PDF.

Pour plus de détails, consultez la documentation.

Le type PdfOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | Initialise une nouvelle instance de la classe PdfOptions. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | La propriété désactive le regroupement des symboles pour un positionnement précis des symboles lors du rendu de la page. |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | La propriété désactive la protection contre la copie du contenu lors du rendu en HTML. |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | La propriété désactive toutes les restrictions de licence pour toutes les polices dans le document XPS/OXPS actuel. |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | La propriété active le lissage des polices. |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | La propriété active le rendu du texte et des graphiques dans l'ordre Z du document PDF original lors du rendu en HTML. |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | L'option de mise en page fixe active le rendu des documents PDF et EPUB en HTML avec une mise en page fixe. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | La qualité d'image de sortie pour les ressources image lors du rendu en HTML. La qualité par défaut est `ImageQuality.LOW`. |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | La taille de page de sortie est définie pour correspondre à la taille de page du document PDF source. |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | L'option active le rendu du texte des fichiers PDF sous forme d'image dans la sortie HTML. |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | La propriété qui active l'encapsulation de chaque image dans le document HTML de sortie dans une balise SVG pour améliorer la qualité de sortie. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # Activez le lissage des polices lors du rendu des pages PDF en images.
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### Voir aussi
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
