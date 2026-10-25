---
title: "LoadOptions"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Contient les options utilisées pour ouvrir le fichier. Pour plus de détails, voir cette page https//docs.groupdocs.com/viewer/net/loading/ et ses enfants."
type: docs
weight: 360
url: /fr/net/groupdocs.viewer.options/loadoptions/
---

## LoadOptions class

Contient des options utilisées pour ouvrir le fichier. Pour plus de détails, consultez cette [page](https://docs.groupdocs.com/viewer/net/loading/) et ses sous‑sections.

```csharp
public class LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Initialise une instance de la classe [`LoadOptions`](../loadoptions). |
| [LoadOptions](loadoptions#constructor_1)(FileType) | Initialise une instance de la classe [`LoadOptions`](../loadoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [DetectEncoding](../../groupdocs.viewer.options/loadoptions/detectencoding) { get; set; } | Active la détection d'encodage pour les fichiers [`TXT`](../../groupdocs.viewer/filetype/txt), [`CSV`](../../groupdocs.viewer/filetype/csv) et [`TSV`](../../groupdocs.viewer/filetype/tsv). |
| [Encoding](../../groupdocs.viewer.options/loadoptions/encoding) { get; set; } | Définit l'encodage utilisé lors de l'ouverture de fichiers texte ou de messages électroniques tels que [`CSV`](../../groupdocs.viewer/filetype/csv), [`TXT`](../../groupdocs.viewer/filetype/txt) et [`MSG`](../../groupdocs.viewer/filetype/msg). La valeur par défaut est UTF8. |
| [FileType](../../groupdocs.viewer.options/loadoptions/filetype) { get; set; } | Définit le type du fichier à ouvrir. |
| [Password](../../groupdocs.viewer.options/loadoptions/password) { get; set; } | Définit le mot de passe pour ouvrir le fichier chiffré. |
| [ResourceLoadingTimeout](../../groupdocs.viewer.options/loadoptions/resourceloadingtimeout) { get; set; } | Définit le délai d'attente pour charger les ressources externes. |
| [SkipExternalResources](../../groupdocs.viewer.options/loadoptions/skipexternalresources) { get; set; } | Désactive le chargement de toutes les ressources externes telles que les images, sauf [`WhitelistedResources`](./whitelistedresources). |
| [TryRepair](../../groupdocs.viewer.options/loadoptions/tryrepair) { get; set; } | Lorsqu'il est activé, GroupDocs.Viewer tente de réparer les corruptions structurelles dans les documents PDF. La valeur par défaut est `false`. |
| [WhitelistedResources](../../groupdocs.viewer.options/loadoptions/whitelistedresources) { get; set; } | La liste des fragments d'URL correspondant aux ressources externes qui doivent être chargées lorsque [`SkipExternalResources`](./skipexternalresources) est définie sur `true`. |

### Voir aussi

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
