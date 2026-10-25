---
title: "DisableFontLicenseVerifications"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Désactive toutes les restrictions de licence pour toutes les polices dans le document XPS/OXPS actuel."
type: docs
weight: 40
url: /fr/net/groupdocs.viewer.options/pdfoptions/disablefontlicenseverifications/
---

## PdfOptions.DisableFontLicenseVerifications property

Désactive toutes les restrictions de licence pour toutes les polices dans le document XPS/OXPS actuel.

```csharp
public bool DisableFontLicenseVerifications { get; set; }
```

### Remarques

De nombreuses opérations avec les polices ne peuvent pas être exécutées si elles sont interdites par la licence de cette police. Par exemple, certaines polices ne peuvent pas être incorporées dans un document PDF si les règles de licence désactivent l’incorporation pour cette police. Cette option vous permet d’ignorer la vérification de ces règles.

Soyez prudent lors de l’utilisation de ce drapeau. Lorsqu’il est activé, cela signifie que la personne qui le définit assume toute la responsabilité des éventuelles violations de licence ou de loi. Il le fait à ses propres risques. Il est fortement recommandé de n’utiliser ce drapeau que lorsque vous êtes pleinement convaincu de ne pas enfreindre la loi sur le droit d’auteur. La valeur par défaut est `false`.

Pour un exemple de code, voir la [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).

### Voir aussi

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
