---
title: "groupdocs.viewer.fonts"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Configuration du chargement et du remplacement des polices."
type: docs
url: /fr/python-net/groupdocs.viewer.fonts/
is_root: false
weight: 40
---


Configuration du chargement et du remplacement des polices.

### Classes
| Classe | Description |
| :- | :- |
| [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) | Représente le dossier contenant les polices TrueType. |
| [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/) | Fournit des méthodes pour travailler avec les sources afin de rechercher les polices TrueType. |
| [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) | Représente les 4 styles possibles de la police, utilisés dans le document : Regular, Bold, Italic ou Bold Italic. |
| [`IFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/) | Représente une interface commune pour toutes les polices qui peuvent être extraites de toutes les familles de formats de documents prises en charge : PDF, WordProcessing, Spreadsheet et Presentation. |
| [`PdfFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/) | Encapsule les métadonnées et les données binaires d’une police PDF chargée dans une instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), qui peut être intégrée au document ou installée sur le système d’exploitation où s’exécute GroupDocs.Viewer. |
| [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/) | Représente les métadonnées et les données binaires d’une police provenant d’un document Presentation chargé dans une instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). La police est utilisée dans le contenu du document et peut être intégrée au document ou installée sur le système d’exploitation où le visualiseur s’exécute. |
| [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/) | Encapsule les métadonnées et les données binaires d’une police provenant d’un document de feuille de calcul chargé dans une instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). Les documents de feuille de calcul ne peuvent pas contenir de polices intégrées, ainsi une police renvoyée par [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) est installée sur le système d’exploitation où le visualiseur s’exécute. |
| [`WordProcessingFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/) | Encapsule les métadonnées et les données binaires d’une police provenant d’un document WordProcessing chargé dans une instance de [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/) | Encapsule les métadonnées et les données binaires d’une police provenant d’un document WordProcessing, qui n’est initialement pas utilisée dans le document chargé par l’instance [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), mais sert de police de substitution pour celles qui ne peuvent pas être trouvées sur la machine cible. Les polices de substitution existent uniquement pour la famille de formats WordProcessing. |

### Énumérations
| Énum | Description |
| :- | :- |
| [`FontFormat`](/viewer/python-net/groupdocs.viewer.fonts/fontformat/) |  |
| [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) | Représente une interface marqueur pour les sources de polices. |
| [`SearchOption`](/viewer/python-net/groupdocs.viewer.fonts/searchoption/) |  |
