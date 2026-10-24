---
title: "CadOptions"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Παρέχει επιλογές για την απόδοση σχεδίων CAD."
type: docs
weight: 13
url: /el/java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

Παρέχει επιλογές για την απόδοση σχεδίων CAD.


Η κλάση CadOptions περιλαμβάνει διάφορες ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν
για τον έλεγχο της απόδοσης των σχεδίων CAD στο στοιχείο GroupDocs.Viewer.


Για περισσότερες πληροφορίες και παραδείγματα κώδικα, δείτε το [Απόδοση σχεδίων CAD και μοντέλων ως HTML, PDF και αρχεία εικόνας](../https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/) και το [Καθορισμός επιλογών απόδοσης για αρχεία CAD](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


Παράδειγμα χρήσης:

````

 CadOptions options = CadOptions.forRenderingByWidth(256);
 options.setRenderLayouts(true);
 options.setBackgroundColor(Color.YELLOW);
 options.setLayers(Arrays.asList(
         CacheableFactory.getInstance().newLayer("Layer1"),
         CacheableFactory.getInstance().newLayer("Layer2")
 ));

 try (Viewer viewer = new Viewer("document.dwg")) {
     PdfViewOptions pdfViewOptions = new PdfViewOptions();
     pdfViewOptions.setCadOptions(options);
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getPc3File()](#getPc3File--) | Ανακτά το αρχείο PC3 (Plotter Configuration) που σχετίζεται με τον εκτυπωτή. |
|
|  | [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | Ορίζει το αρχείο PC3 (Plotter Configuration) που σχετίζεται με τον εκτυπωτή. |
|
|  | [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | Αρχικοποιεί μια νέα παρουσία του |
CadOptions
κλάση για απόδοση με συντελεστή κλίμακας.
|
|  | [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | Αρχικοποιεί μια νέα παρουσία του |
CadOptions
κλάση για απόδοση με πλάτος.
|
|  | [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | Αρχικοποιεί μια νέα παρουσία του |
CadOptions
κλάση για απόδοση με ύψος.
|
|  | [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | Αρχικοποιεί μια νέα παρουσία του |
CadOptions
κλάση για απόδοση με πλάτος και ύψος.
|
|  | [getScaleFactor()](#getScaleFactor--) | Λαμβάνει το συντελεστή κλίμακας για την απόδοση. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος του τελικού αποτελέσματος σε εικονοστοιχεία. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος του αποτελέσματος εξόδου σε εικονοστοιχεία. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Λαμβάνει το χρώμα φόντου της εικόνας. |
|
|  | [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | Λαμβάνει το χρώμα φόντου της εικόνας. |
|
|  | [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | Ορίζει το χρώμα φόντου της εικόνας. |
|
|  | [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | Ορίζει το χρώμα φόντου της εικόνας. |
|
|  | [getTiles()](#getTiles--) | Λαμβάνει τις περιοχές σχεδίασης για απόδοση. |
|
|  | [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | Ορίζει τις περιοχές σχεδίασης για απόδοση. |
|
|  | [isRenderLayouts()](#isRenderLayouts--) | Δείχνει αν οι διάταξεις από το έγγραφο CAD πρέπει να αποδοθούν. |
|
|  | [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | Ορίζει αν οι διάταξεις από το έγγραφο CAD πρέπει να αποδοθούν. |
|
|  | [getLayoutName()](#getLayoutName--) | Λαμβάνει το όνομα της συγκεκριμένης διάταξης για απόδοση. |
|
|  | [setLayoutName(String value)](#setLayoutName-java.lang.String-) | Ορίζει το όνομα της συγκεκριμένης διάταξης για απόδοση. |
|
|  | [getLayers()](#getLayers--) | Λαμβάνει τα επίπεδα σχεδίασης CAD για απόδοση. |
|
|  | [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Λαμβάνει τα επίπεδα σχεδίασης CAD για απόδοση. |
|
|  | [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | Ορισμός αυτής της σημαίας σε true ενεργοποιεί μια ειδική λειτουργία μετατροπής προσανατολισμένης στην απόδοση για όλες τις μορφές της οικογένειας CAD. |
|
|  | [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | Ορισμός αυτής της σημαίας σε true ενεργοποιεί μια ειδική λειτουργία μετατροπής προσανατολισμένης στην απόδοση για όλες τις μορφές της οικογένειας CAD. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Ελέγχει αν αυτό το αντικείμενο CadOptions είναι ίσο με ένα άλλο αντικείμενο. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | {@inheritDoc} |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
### WIDTH {#WIDTH}
```
public static final String WIDTH
```


### HEIGHT {#HEIGHT}
```
public static final String HEIGHT
```


### getPc3File() {#getPc3File--}
```
public String getPc3File()
```


Ανακτά το αρχείο PC3 (Plotter Configuration) που σχετίζεται με τον εκτυπωτή.


**Returns:**
java.lang.String - η διαδρομή αρχείου PC3.

### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


Ορίζει το αρχείο PC3 (Plotter Configuration) που σχετίζεται με τον εκτυπωτή.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | pc3File | java.lang.String | Η διαδρομή αρχείου PC3. |
|

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


Αρχικοποιεί μια νέα παρουσία του
CadOptions
κλάση για απόδοση με συντελεστή κλίμακας.


Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | scaleFactor | double | Ο συντελεστής κλίμακας για την απόδοση. Τιμές μεγαλύτερες του 1 θα μεγεθύνουν το αποτέλεσμα εξόδου, ενώ τιμές μεταξύ 0 και 1 θα κάνουν το αποτέλεσμα μικρότερο. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.

### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


Αρχικοποιεί μια νέα παρουσία του
CadOptions
κλάση για απόδοση με πλάτος.


Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | width | int | Το πλάτος του αποτελέσματος εξόδου σε εικονοστοιχεία. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.

### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


Αρχικοποιεί μια νέα παρουσία του
CadOptions
κλάση για απόδοση με ύψος.


Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | ύψος | int | Το ύψος του αποτελέσματος εξόδου σε εικονοστοιχεία. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.

### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


Αρχικοποιεί μια νέα παρουσία του
CadOptions
κλάση για απόδοση με πλάτος και ύψος.


Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | width | int | Το πλάτος του αποτελέσματος εξόδου σε εικονοστοιχεία. |
|
|  | ύψος | int | Το ύψος του αποτελέσματος εξόδου σε εικονοστοιχεία. |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


Λαμβάνει το συντελεστή κλίμακας για την απόδοση.
Τιμές μεγαλύτερες του 1 θα μεγεθύνουν το αποτέλεσμα εξόδου, ενώ τιμές μεταξύ 0 και 1 θα κάνουν το αποτέλεσμα μικρότερο.


**Returns:**
double - ο συντελεστής κλίμακας για την απόδοση.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Λαμβάνει το πλάτος του τελικού αποτελέσματος σε εικονοστοιχεία.


**Returns:**
int - το πλάτος του αποτελέσματος εξόδου.

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Λαμβάνει το ύψος του αποτελέσματος εξόδου σε εικονοστοιχεία.


**Returns:**
int - το ύψος του αποτελέσματος εξόδου.

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Λαμβάνει το χρώμα φόντου της εικόνας.


**Returns:**
java.awt.Color - το χρώμα φόντου της εικόνας.

### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


Λαμβάνει το χρώμα φόντου της εικόνας.


**Returns:**
java.lang.String - το χρώμα φόντου της εικόνας σε μορφή 0xFFFFFF.

### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


Ορίζει το χρώμα φόντου της εικόνας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | backgroundColor | java.awt.Color | Το χρώμα φόντου της εικόνας. |
|

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


Ορίζει το χρώμα φόντου της εικόνας.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | colorName | java.lang.String | Το όνομα χρώματος φόντου της εικόνας. |
|

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


Λαμβάνει τις περιοχές σχεδίασης για απόδοση.
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
Το
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadorders#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadorders#setRenderLayouts-boolean-))
και
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadorders#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadorders#setLayoutName-String-)) οι επιλογές αγνοούνται
κατά την απόδοση με πλακίδια.*


**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - η λίστα των περιοχών σχεδίασης για απόδοση.

### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


Ορίζει τις περιοχές σχεδίασης για απόδοση.
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
Το
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadorders#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadorders#setRenderLayouts-boolean-))
και
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadorders#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadorders#setLayoutName-String-)) οι επιλογές αγνοούνται
κατά την απόδοση με πλακίδια.*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.util.List<com.groupdocs.viewer.options.Tile> | Η λίστα των περιοχών σχεδίασης για απόδοση. |
|

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


Δείχνει αν οι διάταξεις από το έγγραφο CAD πρέπει να αποδοθούν.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Από προεπιλογή, μόνο το Μοντέλο αποδίδεται.*


**Returns:**
boolean -  true  εάν τα layout πρέπει να αποδοθούν,  false  διαφορετικά.

### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


Ορίζει αν οι διάταξεις από το έγγραφο CAD πρέπει να αποδοθούν.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Από προεπιλογή, μόνο το Μοντέλο αποδίδεται.*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | true  για απόδοση layout,  false  διαφορετικά. |
|

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


Λαμβάνει το όνομα του συγκεκριμένου layout για απόδοση. Το όνομα του layout είναι ευαίσθητο σε πεζά/κεφαλαία.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Από προεπιλογή, μόνο το Μοντέλο αποδίδεται.*


**Returns:**
java.lang.String - το όνομα του συγκεκριμένου layout για απόδοση.

### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


Ορίζει το όνομα του συγκεκριμένου layout για απόδοση. Το όνομα του layout είναι ευαίσθητο σε πεζά/κεφαλαία.
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
Από προεπιλογή, μόνο το Μοντέλο αποδίδεται.*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Το όνομα του συγκεκριμένου layout για απόδοση. |
|

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


Λαμβάνει τα επίπεδα σχεδίασης CAD για απόδοση.


**Note:** By default, all layers are rendered. Layer names are case-sensitive.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - τα επίπεδα σχεδίασης CAD.

### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


Λαμβάνει τα επίπεδα σχεδίασης CAD για απόδοση.
***Note:** By default, all layers are rendered. Layer names are case-sensitive.*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.util.List<com.groupdocs.viewer.results.Layer> | Τα επίπεδα σχεδίασης CAD. |
|

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


Ο ορισμός αυτής της σημαίας σε true ενεργοποιεί μια ειδική λειτουργία μετατροπής προσανατολισμένης στην απόδοση για όλες τις μορφές της οικογένειας CAD. Σε αυτή τη λειτουργία, η ταχύτητα μετατροπής είναι πολύ πιο γρήγορη, αλλά η ποιότητα των παραγόμενων εγγράφων είναι σημαντικά χειρότερη. Από προεπιλογή, είναι απενεργοποιημένη (false). Η ποιότητα των παραγόμενων εγγράφων είναι η καλύτερη δυνατή εις βάρος της απόδοσης.


**Returns:**
boolean -  true  εάν η λειτουργία μετατροπής προσανατολισμένης στην απόδοση είναι ενεργοποιημένη,  false  διαφορετικά.

### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


Ο ορισμός αυτής της σημαίας σε true ενεργοποιεί μια ειδική λειτουργία μετατροπής προσανατολισμένης στην απόδοση για όλες τις μορφές της οικογένειας CAD. Σε αυτή τη λειτουργία, η ταχύτητα μετατροπής είναι πολύ πιο γρήγορη, αλλά η ποιότητα των παραγόμενων εγγράφων είναι σημαντικά χειρότερη. Από προεπιλογή, είναι απενεργοποιημένη (false). Η ποιότητα των παραγόμενων εγγράφων είναι η καλύτερη δυνατή εις βάρος της απόδοσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | enablePerformanceConversionMode | boolean | true  για ενεργοποίηση της λειτουργίας μετατροπής προσανατολισμένης στην απόδοση,  false  για απενεργοποίησή της. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Ελέγχει αν αυτό το αντικείμενο CadOptions είναι ίσο με ένα άλλο αντικείμενο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | o | java.lang.Object | Το αντικείμενο για σύγκριση. |
|

**Returns:**
boolean -  true  εάν τα αντικείμενα είναι ίσα,  false  διαφορετικά.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Υπολογίζει την τιμή του κώδικα κατακερματισμού για αυτό το αντικείμενο. Ο κώδικας κατακερματισμού βασίζεται σε
την εσωτερική κατάσταση του αντικειμένου και χρησιμοποιείται σε δομές δεδομένων βασισμένες σε κατακερματισμό
όπως οι hash maps και τα hash sets.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - η τιμή του κώδικα κατακερματισμού για αυτό το αντικείμενο.

### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναπαράσταση συμβολοσειράς αυτού του αντικειμένου.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Returns:**
java.lang.String - μια αναπαράσταση συμβολοσειράς αυτού του αντικειμένου.

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Επιστρέφει μια αναπαράσταση συμβολοσειράς αυτού του αντικειμένου.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | στυλ | org.apache.commons.lang3.builder.ToStringStyle | Το ToStringStyle που θα χρησιμοποιηθεί για τη δημιουργία της αναπαράστασης συμβολοσειράς. |
|

**Returns:**
java.lang.String - μια αναπαράσταση συμβολοσειράς αυτού του αντικειμένου χρησιμοποιώντας το καθορισμένο ToStringStyle.

