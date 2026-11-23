---
title: "WordProcessingSubstitutedFontInfo"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Encapsule les métadonnées et les données binaires d'une police provenant d'un document WordProcessing qui, à l'origine, n'est pas utilisée dans le document chargé dans l'instance Viewer../groupdocs.viewer/viewer mais sert de police de substitution pour celles qui ne peuvent pas être trouvées sur la machine cible. Les polices de substitution existent uniquement pour la famille de formats WordProcessing."
type: docs
weight: 890
url: /fr/net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---

## WordProcessingSubstitutedFontInfo structure

Encapsule les métadonnées et les données binaires d'une police provenant d'un document WordProcessing, qui à l'origine n'est pas utilisée dans le document chargé dans l'instance [`Viewer`](../../groupdocs.viewer/viewer), mais sert de police de substitution pour celles qui ne peuvent pas être trouvées sur la machine cible. Les polices de substitution existent uniquement pour la famille de formats WordProcessing.

```csharp
public struct WordProcessingSubstitutedFontInfo : IFontInfo
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content) { get; } | Contenu de cette police substituée sous forme de tableau d'octets. N'est jamais `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/familyname) { get; } | Nom de famille de la police **substituted**, sans style, n'est jamais nul ou une chaîne vide |
| [Format](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format) { get; } | Format de cette police substituée (non originale). Peut être TrueType, TrueType Collection, OpenType, Embedded OpenType. Pour la police substituée, comme son contenu binaire est disponible par définition, cette propriété ne renvoie jamais une valeur Unknown. |
| [OriginalFamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/originalfamilyname) { get; } | Nom de famille de la police originale, qui ne peut pas être trouvée sur une machine cible, sans style, n'est jamais nul ou une chaîne vide |
| [Style](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style) { get; } | Style de la police originale — peut être Regular, Bold, Italic ou Bold Italic. La police substituée est généralement (mais pas toujours) du même style. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serializetocss)(TextWriter) | Sérialise ces informations de police en règle @font-face et les écrit dans le rédacteur de texte spécifié |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/tostring)() | Renvoie une information de débogage sur ces données de police selon le modèle suivant : "original-name -> substituted-name style, format" |

### Remarques

Structure immuable. Ses instances sont produites et renvoyées par l'API publique de GroupDocs.Viewer et ne devraient normalement pas être créées par l'utilisateur. Pour plus de détails, consultez la [documentation](https://docs.groupdocs.com/viewer/net/getting-used-fonts/).

### Voir aussi

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
