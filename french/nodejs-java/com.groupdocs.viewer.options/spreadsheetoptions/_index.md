---
title: "SpreadsheetOptions"
second_title: "Référence API de GroupDocs.Viewer pour Node.js via Java"
description: "Fournit des options pour le rendu des feuilles de calcul."
type: docs
weight: 31
url: /fr/nodejs-java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Fournit des options pour le rendu des feuilles de calcul.

La classe SpreadsheetOptions encapsule divers paramètres et réglages qui peuvent être utilisés pour contrôler le rendu des fichiers de feuille de calcul (tels que les fichiers Excel ou CSV) dans le composant GroupDocs.Viewer. Pour plus de détails, voir les sous‑sections du sujet [Render spreadsheet files][].

Exemple d'utilisation :

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 SpreadsheetOptions spreadsheetOptions = pngViewOptions.getSpreadsheetOptions();
 spreadsheetOptions.setRenderHeadings(true);
 spreadsheetOptions.setCountColumnsPerPage(24);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[Render spreadsheet files]: https://docs.groupdocs.com/viewer/java/render-spreadsheets/
## Méthodes

| Méthode | Description |
| --- | --- |
| [isRenderByPageBreaks()](#isRenderByPageBreaks--) | Détermine si la feuille de calcul doit être rendue par sauts de page. |
| [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | Définit si la feuille de calcul doit être rendue par sauts de page. |
| [isDetectSeparator()](#isDetectSeparator--) | Détecte le séparateur pour les fichiers CSV/TSV. |
| [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | Définit s'il faut détecter le séparateur pour les fichiers CSV/TSV. |
| [forOnePagePerSheet()](#forOnePagePerSheet--) | Crée une nouvelle instance de la classe  SpreadsheetOptions  pour rendre une feuille en une page. |
| [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Crée une nouvelle instance de la classe  SpreadsheetOptions  pour rendre une feuille en plusieurs pages. |
| [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Initialise une nouvelle instance de la classe  SpreadsheetOptions  pour rendre une feuille en pages. |
| [forRenderingPrintArea()](#forRenderingPrintArea--) | Initialise une nouvelle instance de la classe  SpreadsheetOptions  pour ne rendre que les zones d'impression. |
| [isOnePagePerSheet()](#isOnePagePerSheet--) | Indique si une feuille est rendue en une page. |
| [getCountRowsPerPage()](#getCountRowsPerPage--) | Obtient le nombre de lignes à inclure dans chaque page lors du fractionnement de la feuille de calcul en pages. |
| [getCountColumnsPerPage()](#getCountColumnsPerPage--) | Obtient le nombre de colonnes à inclure dans chaque page lors du fractionnement de la feuille de calcul en pages. |
| [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | Définit le nombre de colonnes à inclure dans chaque page lors du fractionnement de la feuille de calcul en pages. |
| [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Indique si seules les zones d'impression sont rendues. |
| [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | Lorsque cette option est activée, une feuille de calcul sera rendue par les sauts de page qui se trouvent dans la zone d'impression. |
| [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | Définit s'il faut rendre une feuille de calcul par les sauts de page qui se trouvent dans la zone d'impression. |
| [isRenderGridLines()](#isRenderGridLines--) | Active le rendu des lignes de grille. |
| [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Active ou désactive le rendu des lignes de grille. |
| [isSkipEmptyRows()](#isSkipEmptyRows--) | Indique si les lignes vides doivent être ignorées lors du rendu. |
| [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Définit si les lignes vides doivent être ignorées lors du rendu. |
| [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Indique si les colonnes vides doivent être ignorées lors du rendu. |
| [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Définit si les colonnes vides doivent être ignorées lors du rendu. |
| [isRenderHiddenRows()](#isRenderHiddenRows--) | Détermine si les lignes masquées doivent être rendues. |
| [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Définit si les lignes masquées doivent être rendues. |
| [isRenderHeadings()](#isRenderHeadings--) | Vérifie si le rendu des en-têtes est activé. |
| [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | Active le rendu des en-têtes. |
| [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Active le rendu des colonnes masquées. |
| [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Active le rendu des colonnes masquées. |
| [getTextOverflowMode()](#getTextOverflowMode--) | Renvoie le mode de dépassement de texte pour le rendu des documents de feuille de calcul en HTML. |
| [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | Définit le mode de dépassement de texte pour le rendu des documents de feuille de calcul en HTML. |
| [getLeftMargin()](#getLeftMargin--) | Pour définir la marge gauche de la feuille de calcul lors de la conversion en PDF, si elle est inférieure à 0, la valeur de conversion par défaut est utilisée |
| [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | Pour définir la marge gauche de la feuille de calcul lors de la conversion en PDF, si elle est inférieure à 0, la valeur de conversion par défaut est utilisée |
| [getRightMargin()](#getRightMargin--) | Pour définir la marge droite de la feuille de calcul lors de la conversion en PDF, si elle est inférieure à 0, la valeur de conversion par défaut est utilisée. Si le paramètre est inférieur à 0, la valeur par défaut est utilisée. |
| [setRightMargin(double rightMargin)](#setRightMargin-double-) | Pour définir la marge droite de la feuille de calcul lors de la conversion en PDF, si elle est inférieure à 0, la valeur de conversion par défaut est utilisée. Si le paramètre est inférieur à 0, la valeur par défaut est utilisée. |
| [getTopMargin()](#getTopMargin--) | Pour définir la marge supérieure de la feuille de calcul lors de la conversion en PDF, si elle est inférieure à 0, la valeur de conversion par défaut est utilisée. Si le paramètre est inférieur à 0, la valeur par défaut est utilisée. |
| [setTopMargin(double topMargin)](#setTopMargin-double-) | Pour définir la marge supérieure de la feuille de calcul lors de la conversion en PDF, si elle est inférieure à 0, la valeur de conversion par défaut est utilisée. Si le paramètre est inférieur à 0, la valeur par défaut est utilisée. |
| [getBottomMargin()](#getBottomMargin--) | Pour définir la marge inférieure de la feuille de calcul lors de la conversion en PDF, si elle est inférieure à 0, la valeur de conversion par défaut est utilisée. Si le paramètre est inférieur à 0, la valeur par défaut est utilisée. |
| [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | Pour définir la marge inférieure de la feuille de calcul lors de la conversion en PDF, si elle est inférieure à 0, la valeur de conversion par défaut est utilisée. Si le paramètre est inférieur à 0, la valeur par défaut est utilisée. |
| [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | Initialise une nouvelle instance de  SpreadsheetOptions  pour le rendu des zones d’impression et des sauts de page. |
| [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Initialise une nouvelle instance de la classe  SpreadsheetOptions  pour ne rendre que les zones d'impression. |
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


Détermine si la feuille de calcul doit être rendue par sauts de page.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Returns:**
boolean -  true  si la feuille de calcul doit être rendue par sauts de page,  false  sinon.
### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


Définit si la feuille de calcul doit être rendue par sauts de page.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderByPageBreaks | boolean | true  si la feuille de calcul doit être rendue par sauts de page,  false  sinon. |

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


Détecte le séparateur pour les fichiers CSV/TSV.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Returns:**
boolean -  true  si le séparateur doit être détecté automatiquement,  false  sinon.
### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


Définit s'il faut détecter le séparateur pour les fichiers CSV/TSV.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| detectSeparator | boolean | true  pour détecter automatiquement le séparateur,  false  sinon. |

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Crée une nouvelle instance de la classe  SpreadsheetOptions  pour rendre une feuille en une page.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.
### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Crée une nouvelle instance de la classe  SpreadsheetOptions  pour rendre une feuille en plusieurs pages.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| countRowsPerPage | int | Le nombre de lignes à inclure dans chaque page. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.
### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Initialise une nouvelle instance de la classe  SpreadsheetOptions  pour rendre une feuille en pages.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| countRowsPerPage | int | Le nombre de lignes à inclure sur chaque page. |
| countColumnsPerPage | int | Le nombre de colonnes à inclure sur chaque page. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.
### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Initialise une nouvelle instance de la classe  SpreadsheetOptions  pour ne rendre que les zones d'impression.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.
### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


Indique si une feuille est rendue en une page.

**Returns:**
boolean -  true  si une feuille est rendue sur une page ;  false  sinon.
### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


Obtient le nombre de lignes à inclure dans chaque page lors du fractionnement de la feuille de calcul en pages.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Returns:**
int - le nombre de lignes à inclure dans chaque page.
### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


Obtient le nombre de colonnes à inclure dans chaque page lors du fractionnement de la feuille de calcul en pages.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Returns:**
int - le nombre de colonnes à inclure dans chaque page.
### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


Définit le nombre de colonnes à inclure dans chaque page lors du fractionnement de la feuille de calcul en pages.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| countColumnsPerPage | int | Le nombre de colonnes à inclure dans chaque page. |

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Indique si seules les zones d'impression sont rendues.

**Returns:**
boolean -  true  si seules les zones d’impression sont rendues,  false  sinon.
### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


Lorsque cette option est activée, une feuille de calcul sera rendue par les sauts de page qui se trouvent dans la zone d'impression.

**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


Définit s'il faut rendre une feuille de calcul par les sauts de page qui se trouvent dans la zone d'impression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderingPrintAreaAndPageBreaks | boolean | Définir sur true pour activer, false pour désactiver. |

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Active le rendu des lignes de grille.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Returns:**
booléen -  true  si les lignes de grille sont activées,  false  sinon.
### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Active ou désactive le rendu des lignes de grille.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | true  pour activer le rendu des lignes de grille,  false  pour le désactiver. |

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Indique si les lignes vides doivent être ignorées lors du rendu.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
booléen -  true  si les lignes vides doivent être ignorées,  false  sinon.
### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Définit si les lignes vides doivent être ignorées lors du rendu.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | true  pour ignorer les lignes vides,  false  sinon. |

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Indique si les colonnes vides doivent être ignorées lors du rendu.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
booléen -  true  si les colonnes vides sont ignorées,  false  sinon.
### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Définit si les colonnes vides doivent être ignorées lors du rendu.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | true  pour ignorer les colonnes vides,  false  sinon. |

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Détermine si les lignes masquées doivent être rendues.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
booléen -  true  si les lignes masquées doivent être rendues,  false  sinon.
### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Définit si les lignes masquées doivent être rendues.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | true  pour activer le rendu des lignes masquées,  false  pour le désactiver. |

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Vérifie si le rendu des en-têtes est activé.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Returns:**
booléen -  true  si le rendu des en-têtes est activé,  false  sinon.
### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


Active le rendu des en-têtes.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| renderHeadings | boolean | true  pour activer le rendu des en-têtes,  false  pour le désactiver. |

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Active le rendu des colonnes masquées.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
booléen -  true  si le rendu des colonnes masquées est activé,  false  sinon.
### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Active le rendu des colonnes masquées.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean | true  pour activer le rendu des colonnes masquées,  false  pour le désactiver. |

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


Renvoie le mode de dépassement de texte pour le rendu des documents de feuille de calcul en HTML.

Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.
### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


Définit le mode de débordement du texte pour le rendu des documents de feuille de calcul en HTML. Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | Le mode de débordement du texte à définir. |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Pour définir la marge gauche de la feuille de calcul lors de la conversion en PDF, si elle est inférieure à 0, la valeur de conversion par défaut est utilisée

Si le paramètre est inférieur à 0, la valeur par défaut est utilisée. Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


Pour définir la marge gauche de la feuille de calcul lors de la conversion en PDF, si elle est inférieure à 0, la valeur de conversion par défaut est utilisée

Si le paramètre est inférieur à 0, la valeur par défaut est utilisée. Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Pour définir la marge droite de la feuille de calcul lors de la conversion en pdf, si elle est inférieure à 0 alors la valeur de conversion par défaut est utilisée. Si le paramètre est inférieur à 0, la valeur par défaut est utilisée. Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


Pour définir la marge droite de la feuille de calcul lors de la conversion en pdf, si elle est inférieure à 0 alors la valeur de conversion par défaut est utilisée. Si le paramètre est inférieur à 0, la valeur par défaut est utilisée. Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Pour définir la marge supérieure de la feuille de calcul lors de la conversion en pdf, si elle est inférieure à 0 alors la valeur de conversion par défaut est utilisée. Si le paramètre est inférieur à 0, la valeur par défaut est utilisée. Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


Pour définir la marge supérieure de la feuille de calcul lors de la conversion en pdf, si elle est inférieure à 0 alors la valeur de conversion par défaut est utilisée. Si le paramètre est inférieur à 0, la valeur par défaut est utilisée. Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Pour définir la marge inférieure de la feuille de calcul lors de la conversion en pdf, si elle est inférieure à 0 alors la valeur de conversion par défaut est utilisée. Si le paramètre est inférieur à 0, la valeur par défaut est utilisée. Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


Pour définir la marge inférieure de la feuille de calcul lors de la conversion en pdf, si elle est inférieure à 0 alors la valeur de conversion par défaut est utilisée. Si le paramètre est inférieur à 0, la valeur par défaut est utilisée. Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bottomMargin | double |  |

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


Initialise une nouvelle instance de  SpreadsheetOptions  pour le rendu des zones d'impression et des sauts de page. Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.
### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Initialise une nouvelle instance de la classe  SpreadsheetOptions  pour le rendu des zones d'impression uniquement. Pour plus de détails, voir la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.
