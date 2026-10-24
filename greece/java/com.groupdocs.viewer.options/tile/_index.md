---
title: "Τίλ"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αναπαριστά την περιοχή σχεδίασης."
type: docs
weight: 33
url: /el/java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Αναπαριστά την περιοχή σχεδίασης.


Η κλάση Tile αντιπροσωπεύει μια περιοχή σχεδίασης στο στοιχείο GroupDocs.Viewer.
Χρησιμοποιείται για να ορίσει μια συγκεκριμένη περιοχή ή τμήμα μέσα σε ένα έγγραφο που χρειάζεται να αποδοθεί ή να επεξεργαστεί ξεχωριστά.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


Παράδειγμα χρήσης:

````

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Αρχικοποιεί μια νέα παρουσία του |
Τίλ
κλάσης.
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getStartPointX()](#getStartPointX--) | Ανακτά το συντεταγμένο X του χαμηλότερου αριστερού σημείου στο σχέδιο όπου ξεκινά το tile. |
|
|  | [getStartPointY()](#getStartPointY--) | Λαμβάνει τη συντεταγμένη Y του χαμηλότερου αριστερού σημείου στο σχέδιο όπου αρχίζει το πλακίδιο. |
|
|  | [getWidth()](#getWidth--) | Λαμβάνει το πλάτος του πλακιδίου σε εικονοστοιχεία. |
|
|  | [getHeight()](#getHeight--) | Λαμβάνει το ύψος του πλακιδίου σε εικονοστοιχεία. |
|
|  | [getEndPointX()](#getEndPointX--) | Επιστρέφει τη συντεταγμένη X του υψηλότερου δεξιού σημείου στο σχέδιο όπου τελειώνει το πλακίδιο. |
|
|  | [getEndPointY()](#getEndPointY--) | Επιστρέφει τη συντεταγμένη Y του υψηλότερου δεξιού σημείου στο σχέδιο όπου τελειώνει το πλακίδιο. |
|
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Αρχικοποιεί μια νέα παρουσία του
Τίλ
κλάσης.


Αυτός ο κατασκευαστής δημιουργεί ένα νέο αντικείμενο πλακιδίου με το καθορισμένο σημείο εκκίνησης, πλάτος και ύψος.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | startPointX | int | Η συντεταγμένη X του χαμηλότερου αριστερού σημείου στο σχέδιο όπου αρχίζει το πλακίδιο. |
|
|  | startPointY | int | Η συντεταγμένη Y του χαμηλότερου αριστερού σημείου στο σχέδιο όπου αρχίζει το πλακίδιο. |
|
|  | width | int | Το πλάτος του πλακιδίου σε εικονοστοιχεία. |
|
|  | ύψος | int | Το ύψος του πλακιδίου σε εικονοστοιχεία. |
|

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Ανακτά το συντεταγμένο X του χαμηλότερου αριστερού σημείου στο σχέδιο όπου ξεκινά το tile.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - η συντεταγμένη X του χαμηλότερου αριστερού σημείου.

### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Λαμβάνει τη συντεταγμένη Y του χαμηλότερου αριστερού σημείου στο σχέδιο όπου αρχίζει το πλακίδιο.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - η συντεταγμένη Y του χαμηλότερου αριστερού σημείου.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Λαμβάνει το πλάτος του πλακιδίου σε εικονοστοιχεία.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - το πλάτος του πλακιδίου.

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Λαμβάνει το ύψος του πλακιδίου σε εικονοστοιχεία.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - το ύψος του πλακιδίου.

### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Επιστρέφει τη συντεταγμένη X του υψηλότερου δεξιού σημείου στο σχέδιο όπου τελειώνει το πλακίδιο.


**Returns:**
int - η συντεταγμένη X του υψηλότερου δεξιού σημείου.

### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Επιστρέφει τη συντεταγμένη Y του υψηλότερου δεξιού σημείου στο σχέδιο όπου τελειώνει το πλακίδιο.


**Returns:**
int - η συντεταγμένη Y του υψηλότερου δεξιού σημείου.

