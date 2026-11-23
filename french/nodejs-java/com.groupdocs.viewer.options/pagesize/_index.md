---
title: "PageSize"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "La taille de la page."
type: docs
weight: 42
url: /fr/nodejs-java/com.groupdocs.viewer.options/pagesize/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PageSize extends Enum<PageSize>
```

La taille de la page.

L'énumération PageSize représente différentes tailles de page dans le composant GroupDocs.Viewer. Elle fournit un ensemble de tailles de page prédéfinies qui peuvent être utilisées pour spécifier les dimensions d'une page dans divers scénarios de rendu de documents.

Exemple d'utilisation :

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = htmlViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Champs

| Champ | Description |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | La taille de page par défaut, non spécifiée. |
| [LETTER](#LETTER) | La taille de la page Letter en points est de 792 x 612. |
| [LEDGER](#LEDGER) | La taille de la page A0 en points est de 3371 x 2384. |
| [A0](#A0) | La taille de la page A1 en points est de 2384 x 1685. |
| [A1](#A1) | La taille de la page A2 en points est de 1684 x 1190. |
| [A2](#A2) | La taille de la page A3 en points est de 1190 x 842. |
| [A3](#A3) | La taille de la page A3 en points est de 1190 x 842. |
| [A4](#A4) | La taille de la page A4 en points est de 842 x 595. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final PageSize UNSPECIFIED
```


La taille de page par défaut, non spécifiée. Cette taille est utilisée lorsqu'aucune taille de page spécifique n'est indiquée.

### LETTER {#LETTER}
```
public static final PageSize LETTER
```


La taille de la page Letter en points est de 792 x 612. Cette taille de page est couramment utilisée pour les lettres et les documents en Amérique du Nord.

### LEDGER {#LEDGER}
```
public static final PageSize LEDGER
```


La taille de la page A0 en points est de 3371 x 2384. Cette grande taille de page fait partie de la norme internationale ISO 216.

### A0 {#A0}
```
public static final PageSize A0
```


La taille de la page A1 en points est de 2384 x 1685. Cette taille de page fait partie de la norme internationale ISO 216.

### A1 {#A1}
```
public static final PageSize A1
```


La taille de la page A2 en points est de 1684 x 1190. Cette taille de page fait partie de la norme internationale ISO 216.

### A2 {#A2}
```
public static final PageSize A2
```


La taille de la page A3 en points est de 1190 x 842. Cette taille de page fait partie de la norme internationale ISO 216.

### A3 {#A3}
```
public static final PageSize A3
```


La taille de la page A3 en points est de 1190 x 842. Cette taille de page fait partie de la norme internationale ISO 216.

### A4 {#A4}
```
public static final PageSize A4
```


La taille de la page A4 en points est de 842 x 595. Cette taille de page fait partie de la norme internationale ISO 216.

### values() {#values--}
```
public static PageSize[] values()
```




**Returns:**
com.groupdocs.viewer.options.PageSize[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PageSize valueOf(String name)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize)
