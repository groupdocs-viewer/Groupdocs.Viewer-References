---
title: "Classe PdfOptimizationOptions"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente les options d'optimisation PDF à appliquer au fichier PDF de sortie."
type: docs
url: /fr/python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

Représente les options d'optimisation PDF à appliquer au fichier PDF de sortie.

Pour plus de détails et des exemples de code, voir la page de documentation.

Le type PdfOptimizationOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | Initialise les valeurs par défaut de l'option MaxResolution à 300 et de l'option ImageQuality à 100. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | La propriété permet de compresser les images dans le fichier PDF de sortie. |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | La propriété permet de convertir le fichier PDF de sortie en niveaux de gris. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | La qualité d'image dans le fichier PDF de sortie, exprimée en pourcentage. |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | La propriété permet d'optimiser le fichier PDF de sortie pour la visualisation en ligne avec un navigateur web. |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | La résolution maximale dans le fichier PDF de sortie. |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | La propriété qui permet d'optimiser les feuilles de calcul dans les fichiers PDF. |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | La propriété permet de supprimer les annotations du fichier PDF de sortie. |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | La propriété permet de supprimer les champs de formulaire d'un fichier PDF. |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | La propriété supprime les objets inutilisés (orphelins) d'un fichier PDF. |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | La propriété supprime les flux inutilisés (orphelins) d'un fichier PDF qui sont référencés dans le dictionnaire des ressources de la page mais jamais utilisés dans le contenu de la page. Désactivée par défaut (`False`) ; la définir à `True` réduit la taille du PDF de sortie. |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | La propriété permet de définir la résolution maximale dans le fichier PDF de sortie. |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | La propriété crée des sous‑ensembles de polices dans le fichier PDF de sortie. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # Activer la linéarisation pour un aperçu web plus rapide
        view_options.pdf_optimization_options.lineriaze = True
        # Supprimez les annotations et les champs de formulaire pour réduire la taille
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### Voir aussi
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
