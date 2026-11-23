---
title: "WordProcessingOptions"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Fournit des options pour le rendu des documents de traitement de texte."
type: docs
weight: 38
url: /fr/nodejs-java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Fournit des options pour le rendu des documents de traitement de texte.

La classe WordProcessingOptions fournit des options pour le rendu des documents de traitement de texte dans le composant GroupDocs.Viewer. Elle encapsule les paramètres et les réglages qui peuvent être utilisés pour contrôler le processus de rendu et le format de sortie des fichiers de traitement de texte. Pour plus de détails, consultez la [documentation][].

Exemple d'utilisation :

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WordProcessingOptions()](#WordProcessingOptions--) | Initialise une nouvelle instance de la classe  WordProcessingOptions  . |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPageSize()](#getPageSize--) | Récupère la taille de page pour le rendu des fichiers HTM et HTML. |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Définit la taille de page pour le rendu des fichiers HTM et HTML. |
| [isRenderTrackedChanges()](#isRenderTrackedChanges--) | Indique si le rendu des modifications suivies (révisions) est activé. |
| [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | Définit si le rendu des modifications suivies (révisions) est activé. |
| [getLeftMargin()](#getLeftMargin--) | Récupère la marge gauche de la page pour le rendu HTML. |
| [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | Définit la marge gauche de la page pour le rendu HTML. |
| [getRightMargin()](#getRightMargin--) | Récupère la marge droite de la page pour le rendu HTML. |
| [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | Définit la marge droite de la page pour le rendu HTML. |
| [getTopMargin()](#getTopMargin--) | Récupère la marge supérieure de la page pour le rendu HTML. |
| [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | Définit la marge supérieure de la page pour le rendu HTML. |
| [getBottomMargin()](#getBottomMargin--) | Marge inférieure de la page (pour le rendu HTML uniquement) |
| [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | Définit la marge inférieure de la page pour le rendu HTML. |
| [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | Cette option active le crénage et d'autres fonctionnalités OpenType lors du rendu des scripts arabes, hébreux, indiens, basés sur le latin ou le cyrillique. |
| [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | Cette option active le crénage et d'autres fonctionnalités OpenType lors du rendu des scripts arabes, hébreux, indiens, basés sur le latin ou le cyrillique. |
| [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | Indique si la navigation du table des matières doit être désactivée lors du rendu en HTML ou PDF. |
| [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | Définit si la navigation du table des matières doit être désactivée lors du rendu en HTML ou PDF. |
| [isUpdateFields()](#isUpdateFields--) | Obtient une valeur déterminant si les champs de certains types doivent être mis à jour avant d'enregistrer le document WordProcessing d'entrée aux formats de sortie HTML, PDF, PNG ou JPEG. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Définit une valeur déterminant si les champs de certains types doivent être mis à jour avant d'enregistrer le document WordProcessing d'entrée aux formats de sortie HTML, PDF, PNG ou JPEG. |
| [equals(Object o)](#equals-java.lang.Object-) | Vérifiez si les options ont été modifiées. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Initialise une nouvelle instance de la classe WordProcessingOptions. Contient les options pour le rendu des documents de traitement de texte. Pour plus de détails, consultez la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Récupère la taille de page pour le rendu des fichiers HTM et HTML.

Lors de l'utilisation de la taille de page par défaut, certains contenus peuvent ne pas tenir dans le cadre de la page. Pour ajuster le contenu, vous pouvez définir une taille de page plus grande, comme A3, en utilisant [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3).

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Définit la taille de page pour le rendu des fichiers HTM et HTML.

Lors de l'utilisation de la taille de page par défaut, certains contenus peuvent ne pas tenir dans le cadre de la page. Pour ajuster le contenu, vous pouvez définir une taille de page plus grande, comme A3, en utilisant [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3).

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | La taille de la page de sortie. |

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


Indique si le rendu des modifications suivies (révisions) est activé.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Returns:**
boolean -  true  si le rendu des modifications suivies est activé,  false  sinon.
### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


Définit si le rendu des modifications suivies (révisions) est activé.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | true  pour activer le rendu des modifications suivies,  false  pour le désactiver. |

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


Récupère la marge gauche de la page pour le rendu HTML.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - la valeur de la marge gauche de la page.
### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


Définit la marge gauche de la page pour le rendu HTML.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| leftMargin | java.lang.Double | Valeur de la marge gauche de la page à définir. |

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


Récupère la marge droite de la page pour le rendu HTML.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - la valeur de la marge droite de la page.
### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


Définit la marge droite de la page pour le rendu HTML.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rightMargin | java.lang.Double | Valeur de la marge droite de la page à définir. |

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


Récupère la marge supérieure de la page pour le rendu HTML.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - la marge supérieure de la page.
### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


Définit la marge supérieure de la page pour le rendu HTML.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| topMargin | java.lang.Double | Marge supérieure de la page à définir. |

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Marge inférieure de la page (pour le rendu HTML uniquement)

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - la marge inférieure de la page.
### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


Définit la marge inférieure de la page pour le rendu HTML.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bottomMargin | java.lang.Double | Marge inférieure de la page à définir. |

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


Cette option active le crénage et d'autres fonctionnalités OpenType lors du rendu des scripts arabes, hébreux, indiens, basés sur le latin ou le cyrillique.

**Returns:**
boolean - True si les fonctionnalités OpenType sont activées, false sinon.
### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


Cette option active le crénage et d'autres fonctionnalités OpenType lors du rendu des scripts arabes, hébreux, indiens, basés sur le latin ou le cyrillique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| enableOpenTypeFeatures | boolean | Vrai pour activer les fonctionnalités OpenType, faux sinon. |

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


Indique si la navigation du sommaire doit être désactivée lors du rendu en HTML ou PDF. Lorsque cette option est définie sur vrai, pour le rendu HTML, les liens relatifs du sommaire seront remplacés par des balises span, supprimant la fonctionnalité tout en conservant l'apparence visuelle. Pour le rendu PDF, le sommaire sera rendu en texte brut sans liens.

**Returns:**
booléen - Vrai si la navigation du sommaire est désactivée ; sinon, faux.
### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


Définit si la navigation du sommaire doit être désactivée lors du rendu en HTML ou PDF. Lorsque cette option est définie sur vrai, pour le rendu HTML, les liens relatifs du sommaire seront remplacés par des balises span, supprimant la fonctionnalité tout en conservant l'apparence visuelle. Pour le rendu PDF, le sommaire sera rendu en texte brut sans liens.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| unlinkTableOfContents | boolean | Indique si la navigation du sommaire doit être désactivée. |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Obtient une valeur déterminant si les champs de certains types doivent être mis à jour avant d'enregistrer le document WordProcessing d'entrée aux formats de sortie HTML, PDF, PNG ou JPEG. La valeur par défaut de cette propriété est vraie \u2014 les champs seront mis à jour avant l'enregistrement.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Définit une valeur déterminant si les champs de certains types doivent être mis à jour avant d'enregistrer le document WordProcessing d'entrée aux formats de sortie HTML, PDF, PNG ou JPEG. La valeur par défaut de cette propriété est vraie \u2014 les champs seront mis à jour avant l'enregistrement.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| updateFields | boolean |  |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Vérifiez si les options ont été modifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | L'objet à comparer pour l'égalité. |

**Returns:**
booléen -  vrai  si les options sont égales à l'objet spécifié,  faux  sinon.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Calcule la valeur du code de hachage pour cet objet. Le code de hachage est basé sur l'état interne de l'objet et est utilisé dans les structures de données basées sur le hachage telles que les tables de hachage et les ensembles de hachage.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - la valeur du code de hachage pour cet objet.
