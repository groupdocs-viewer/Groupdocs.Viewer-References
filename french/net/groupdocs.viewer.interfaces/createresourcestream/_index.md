---
title: "CreateResourceStream"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Représente la méthode qui instancie le flux utilisé pour écrire les données de la ressource HTML de sortie."
type: docs
weight: 720
url: /fr/net/groupdocs.viewer.interfaces/createresourcestream/
---

## CreateResourceStream delegate

Représente la méthode qui instancie le flux utilisé pour écrire les données de la ressource HTML de sortie.

```csharp
public delegate Stream CreateResourceStream(int pageNumber, Resource resource);
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Numéro de la page. |
| resource | Ressource | Ressource HTML telle que police, style, image ou graphique. |

### Valeur de retour

Le flux utilisé pour écrire les données de ressource HTML de sortie.

### Voir aussi

* class [Resource](../../groupdocs.viewer.results/resource)
* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
