---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Περιέχει επιλογές για την απόδοση εγγράφων Visio."
type: docs
weight: 36
url: /el/java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Περιέχει επιλογές για την απόδοση εγγράφων Visio.


Η κλάση VisioRenderingOptions παρέχει επιλογές για την επεξεργασία και την απόδοση αρχείων Visio
στο στοιχείο GroupDocs.Viewer. Περιλαμβάνει ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν
για τον έλεγχο της διαδικασίας απόδοσης και της μορφής εξόδου για έγγραφα Visio.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


Παράδειγμα χρήσης:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [VisioRenderingOptions()](#VisioRenderingOptions--) | Αρχικοποιεί μια νέα παρουσία του |
VisioRenderingOptions
κλάσης.
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Απόδοση μόνο των σχημάτων Visio, εξαιρώντας το διάγραμμα. |
|
|  | [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Ορίζει τη σημαία για απόδοση μόνο των σχημάτων Visio, εξαιρώντας το διάγραμμα. |
|
|  | [getFigureWidth()](#getFigureWidth--) | Ανακτά το πλάτος του σχήματος. |
|
|  | [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Ορίζει το πλάτος του σχήματος. |
|
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


Αρχικοποιεί μια νέα παρουσία του
VisioRenderingOptions
κλάσης.


### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Απόδοση μόνο των σχημάτων Visio, εξαιρώντας το διάγραμμα.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes).


**Returns:**
boolean -  true  εάν πρέπει να αποδοθούν μόνο σχήματα Visio,  false  διαφορετικά.

### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Ορίζει τη σημαία για απόδοση μόνο των σχημάτων Visio, εξαιρώντας το διάγραμμα.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | renderFiguresOnly | boolean | true  για απόδοση μόνο σχημάτων Visio,  false  για συμπερίληψη του διαγράμματος. |
|

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
|  | figureWidth | int | Το πλάτος του σχήματος. |
|

