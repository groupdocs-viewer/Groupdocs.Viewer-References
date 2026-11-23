---
title: "FolderFontSource"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une nouvelle instance de la classe FolderFontSourcegroupdocs.viewer.fonts/folderfontsource."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.fonts/folderfontsource/folderfontsource/
---

## FolderFontSource constructor

Initialise une nouvelle instance de la classe [`FolderFontSource`](../../folderfontsource).

```csharp
public FolderFontSource(string folderPath, SearchOption searchOption)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| folderPath | String | Chemin vers le dossier qui contient les polices TrueType. |
| searchOption | SearchOption | Spécifie s'il faut rechercher le dossier actuel, ou le dossier actuel et tous les sous-dossiers. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *folderPath* est nul. |
| DirectoryNotFoundException | Lancée lorsque le chemin spécifié dans *folderPath* ne peut pas être trouvé. |

### Voir aussi

* enum [SearchOption](../../searchoption)
* class [FolderFontSource](../../folderfontsource)
* namespace [GroupDocs.Viewer.Fonts](../../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
