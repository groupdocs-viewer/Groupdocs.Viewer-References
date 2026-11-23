---
title: "TextOverflowMode"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Définit le mode de débordement du texte pour le rendu des documents de feuilles de calcul en HTML."
type: docs
weight: 46
url: /fr/nodejs-java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

Définit le mode de débordement du texte pour le rendu des documents de feuilles de calcul en HTML.

L'énumération TextOverflowMode représente différents modes de gestion du débordement de texte dans le composant GroupDocs.Viewer. Elle fournit un ensemble d'options prédéfinies pouvant être utilisées pour contrôler la façon dont le texte est affiché lorsqu'il dépasse l'espace disponible dans les cellules lors du rendu de documents tableur en HTML. Pour plus de détails, consultez la [documentation][].

Exemple d'utilisation :

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow
## Champs

| Champ | Description |
| --- | --- |
| [OVERLAY](#OVERLAY) | Superposer les cellules suivantes même si elles ne sont pas vides. |
| [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | Superposer les cellules suivantes uniquement si elles sont vides. |
| [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | Agrandir les colonnes pour adapter le texte. |
| [HIDE_TEXT](#HIDE-TEXT) | Masquer le texte débordant. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


Superposer les cellules suivantes même si elles ne sont pas vides. Ce mode permet au texte de déborder dans les cellules adjacentes, quel que soit leur contenu.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


Superposer les cellules suivantes uniquement si elles sont vides. Ce mode permet au texte de déborder dans les cellules adjacentes uniquement si ces cellules sont vides.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


Agrandir les colonnes pour adapter le texte. Ce mode ajuste automatiquement la largeur des colonnes afin de contenir le texte débordant.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


Masquer le texte débordant. Ce mode masque le texte débordant, empêchant son affichage.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### values() {#values--}
```
public static TextOverflowMode[] values()
```




**Returns:**
com.groupdocs.viewer.options.TextOverflowMode[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TextOverflowMode valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
