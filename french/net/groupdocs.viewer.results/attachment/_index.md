---
title: "Attachment"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Représente le fichier de pièce jointe contenu dans le courrier électronique, le document PDF d'archive ou le fichier de données Outlook."
type: docs
weight: 80
url: /fr/net/groupdocs.viewer.results/attachment/
---

## Attachment class

Représente le fichier de pièce jointe contenu dans un message électronique, une archive, un document PDF ou un fichier de données Outlook.

```csharp
public class Attachment
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Attachment](attachment#constructor)() | Initialise une nouvelle instance de la classe [`Attachment`](../attachment). |
| [Attachment](attachment#constructor_1)(string, string) | Initialise une nouvelle instance de la classe [`Attachment`](../attachment). |
| [Attachment](attachment#constructor_3)(string, string, string, long) | Initialise une nouvelle instance de la classe [`Attachment`](../attachment). |
| [Attachment](attachment#constructor_2)(string, string, string, FileType, long) | Initialise une nouvelle instance de la classe [`Attachment`](../attachment). |

## Propriétés

| Nom | Description |
| --- | --- |
| [FileName](../../groupdocs.viewer.results/attachment/filename) { get; set; } | Nom de fichier de la pièce jointe. |
| [FilePath](../../groupdocs.viewer.results/attachment/filepath) { get; set; } | Chemin relatif de la pièce jointe, par ex. dossier/fichier.docx ou nom de fichier lorsque le fichier se trouve à la racine d'une archive, dans un message électronique ou un fichier de données. |
| [FileType](../../groupdocs.viewer.results/attachment/filetype) { get; set; } | Type de fichier de la pièce jointe. |
| [Id](../../groupdocs.viewer.results/attachment/id) { get; set; } | Identifiant unique de la pièce jointe dans le contexte d'un seul fichier contenant cette pièce jointe. |
| [Size](../../groupdocs.viewer.results/attachment/size) { get; set; } | Taille du fichier de la pièce jointe en octets. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [ToString](../../groupdocs.viewer.results/attachment/tostring)() | Renvoie une chaîne qui représente l'objet actuel. |

### Voir aussi

* namespace [GroupDocs.Viewer.Results](../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
