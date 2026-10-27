---
title: "Metered classe"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Gère la licence à la consommation (pay-per-use)."
type: docs
url: /fr/python-net/groupdocs.viewer/metered/
is_root: false
weight: 80
---


## Metered class

Gère la licence à la consommation (pay-per-use).

Les licences Metered facturent la consommation réelle (généralement les pages ou
documents traités). Définissez la paire de clés publique/privée une fois au
démarrage de l'application ; le wrapper rapporte l'utilisation au GroupDocs
serveur de licence en arrière-plan.

Le type Metered expose les membres suivants :

### Méthodes
| Méthode | Description |
| :- | :- |
| [get_consumption_credit](/viewer/python-net/groupdocs.viewer/metered/get_consumption_credit/) | Renvoie le crédit Metered restant pour la clé actuelle. |
| [get_consumption_quantity](/viewer/python-net/groupdocs.viewer/metered/get_consumption_quantity/) | Renvoie la quantité totale Metered consommée jusqu'à présent. |
| [set_metered_key](/viewer/python-net/groupdocs.viewer/metered/set_metered_key/#public_key-private_key) | Activez la facturation Metered avec la paire de clés publique/privée fournie. |

### Voir aussi
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
