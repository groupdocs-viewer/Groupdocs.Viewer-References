---
title: "FontSettings"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Fournit des méthodes pour travailler avec les sources afin de rechercher des polices TrueType."
type: docs
weight: 12
url: /fr/nodejs-java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

Fournit des méthodes pour travailler avec les sources afin de rechercher des polices TrueType.

La classe FontSettings est utilisée pour spécifier et gérer les sources permettant de localiser les polices TrueType. Elle fournit des méthodes pour ajouter et réinitialiser les sources de polices pour l'API GroupDocs.Viewer.

Exemple d'utilisation :

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | Définit les sources à rechercher pour les polices TrueType lors du rendu des documents. |
| [resetFontSources()](#resetFontSources--) | Réinitialise les sources de polices qui ont été définies auparavant. |
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


Définit les sources à rechercher pour les polices TrueType lors du rendu des documents.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | Les sources de polices à définir. |

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


Réinitialise les sources de polices qui ont été définies auparavant.

