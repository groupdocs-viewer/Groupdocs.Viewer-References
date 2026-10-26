---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Περιέχει επιλογές για την απόδοση εγγράφων Visio."
type: docs
weight: 36
url: /el/nodejs-java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Περιέχει επιλογές για την απόδοση εγγράφων Visio.

Η κλάση VisioRenderingOptions παρέχει επιλογές για την επεξεργασία και τη μετατροπή αρχείων Visio στο στοιχείο GroupDocs.Viewer. Συμπεριλαμβάνει ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν για τον έλεγχο της διαδικασίας μετατροπής και της μορφής εξόδου για έγγραφα Visio. Για λεπτομέρειες, δείτε την [documentation][].

Παράδειγμα χρήσης:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [VisioRenderingOptions()](#VisioRenderingOptions--) | Αρχικοποιεί μια νέα παρουσία της  VisioRenderingOptions  κλάσης. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Μετατρέπει μόνο τα σχήματα Visio, εξαιρώντας το διάγραμμα. |
| [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Ορίζει τη σημαία για μετατροπή μόνο των σχημάτων Visio, εξαιρώντας το διάγραμμα. |
| [getFigureWidth()](#getFigureWidth--) | Ανακτά το πλάτος του σχήματος. |
| [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Ορίζει το πλάτος του σχήματος. |
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


Αρχικοποιεί μια νέα παρουσία της  VisioRenderingOptions  κλάσης.

### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Μετατρέπει μόνο τα σχήματα Visio, εξαιρώντας το διάγραμμα.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Returns:**
boolean -  true  εάν πρέπει να αποδοθούν μόνο τα σχήματα Visio,  false  διαφορετικά.
### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Ορίζει τη σημαία για μετατροπή μόνο των σχημάτων Visio, εξαιρώντας το διάγραμμα.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderFiguresOnly | boolean | true  για απόδοση μόνο των σχημάτων Visio,  false  για συμπερίληψη του διαγράμματος. |

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


Ανακτά το πλάτος του σχήματος. Το ύψος θα υπολογιστεί αυτόματα.

**Returns:**
int - το πλάτος του σχήματος.
### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


Ορίζει το πλάτος του σχήματος. Το ύψος θα υπολογιστεί αυτόματα.

***Note:** Default value is 100.*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| figureWidth | int | Το πλάτος του σχήματος. |

