---
title: "WordProcessingFontInfo"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Encapsule les métadonnées et les données binaires d'une police provenant du document WordProcessing chargé dans l'instance Viewer../groupdocs.viewer/viewer. Cette police est utilisée dans le contenu du document et est intégrée dans le document lui‑même ou installée dans le système d'exploitation où le GroupDocs.Viewer s'exécute."
type: docs
weight: 880
url: /fr/net/groupdocs.viewer.fonts/wordprocessingfontinfo/
---

## WordProcessingFontInfo structure

Encapsule les métadonnées et les données binaires d’une police du document WordProcessing, chargée dans l’instance [`Viewer`](../../groupdocs.viewer/viewer). Cette police est utilisée dans le contenu du document et est intégrée dans le document lui‑même ou installée dans le système d’exploitation où s’exécute GroupDocs.Viewer.

```csharp
public struct WordProcessingFontInfo : IFontInfo
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AltFamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/altfamilyname) { get; } | Nom de famille alternatif de la police. Si absent, alors chaîne vide. |
| [Charset](../../groupdocs.viewer.fonts/wordprocessingfontinfo/charset) { get; } | Jeu de caractères de cette police |
| [Content](../../groupdocs.viewer.fonts/wordprocessingfontinfo/content) { get; } | Contenu de cette police sous forme de tableau d'octets. S'il n'existe que des métadonnées sur cette police, mais que son contenu binaire n'est pas disponible, cette propriété renvoie `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/familyname) { get; } | Nom de famille de la police, sans style, n'est jamais nul ni une chaîne vide |
| [Format](../../groupdocs.viewer.fonts/wordprocessingfontinfo/format) { get; } | Format de cette police. Les documents peuvent utiliser des polices dans les formats suivants : TrueType, TrueType Collection, OpenType, Embedded OpenType. S'il n'existe que des métadonnées sur cette police, mais que son contenu binaire n'est pas disponible, cette propriété renvoie une valeur Unknown. |
| [IsEmbedded](../../groupdocs.viewer.fonts/wordprocessingfontinfo/isembedded) { get; } | Indique si cette police est intégrée dans le document, chargée dans l’instance [`Viewer`](../../groupdocs.viewer/viewer) (`true`), ou s’il s’agit d’une police système (`false`). |
| [Style](../../groupdocs.viewer.fonts/wordprocessingfontinfo/style) { get; } | Style de la police — peut être Regular, Bold, Italic ou Bold Italic. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingfontinfo/serializetocss)(TextWriter) | Sérialise ces informations de police en règle @font-face et les écrit dans le rédacteur de texte spécifié |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingfontinfo/tostring)() | Renvoie des informations de débogage sur les données de cette police selon le modèle suivant : "nom style, intégré/système, format" |

### Remarques

Structure immuable. Ses instances sont produites et renvoyées par l'API publique de GroupDocs.Viewer et ne devraient normalement pas être créées par l'utilisateur. Pour plus de détails, consultez la [documentation](https://docs.groupdocs.com/viewer/net/getting-used-fonts/).

### Voir aussi

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
