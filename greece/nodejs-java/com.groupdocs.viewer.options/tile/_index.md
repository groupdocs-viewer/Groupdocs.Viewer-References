---
title: "Tile"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Αναπαριστά την περιοχή σχεδίασης."
type: docs
weight: 33
url: /el/nodejs-java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

Αναπαριστά την περιοχή σχεδίασης.

Η κλάση Tile αντιπροσωπεύει μια περιοχή σχεδίασης στο στοιχείο GroupDocs.Viewer. Χρησιμοποιείται για τον ορισμό μιας συγκεκριμένης περιοχής ή περιοχής μέσα σε ένα έγγραφο που πρέπει να αποδοθεί ή να επεξεργαστεί ξεχωριστά. Για λεπτομέρειες, δείτε την [documentation][].

Παράδειγμα χρήσης:

```

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Αρχικοποιεί μια νέα παρουσία της κλάσης Tile. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getStartPointX()](#getStartPointX--) | Λαμβάνει τη συντεταγμένη X του χαμηλότερου αριστερού σημείου στο σχέδιο όπου αρχίζει το tile. |
| [getStartPointY()](#getStartPointY--) | Λαμβάνει τη συντεταγμένη Y του χαμηλότερου αριστερού σημείου στο σχέδιο όπου αρχίζει το tile. |
| [getWidth()](#getWidth--) | Λαμβάνει το πλάτος του tile σε εικονοστοιχεία. |
| [getHeight()](#getHeight--) | Λαμβάνει το ύψος του tile σε εικονοστοιχεία. |
| [getEndPointX()](#getEndPointX--) | Επιστρέφει τη συντεταγμένη X του υψηλότερου δεξιού σημείου στο σχέδιο όπου το tile τελειώνει. |
| [getEndPointY()](#getEndPointY--) | Επιστρέφει τη συντεταγμένη Y του υψηλότερου δεξιού σημείου στο σχέδιο όπου το tile τελειώνει. |
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης Tile.

Αυτός ο κατασκευαστής δημιουργεί ένα νέο αντικείμενο tile με το καθορισμένο σημείο εκκίνησης, πλάτος και ύψος. Για λεπτομέρειες, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startPointX | int | Η συντεταγμένη X του χαμηλότερου αριστερού σημείου στο σχέδιο όπου αρχίζει το tile. |
| startPointY | int | Η συντεταγμένη Y του χαμηλότερου αριστερού σημείου στο σχέδιο όπου αρχίζει το tile. |
| width | int | Το πλάτος του tile σε εικονοστοιχεία. |
| height | int | Το ύψος του tile σε εικονοστοιχεία. |

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


Λαμβάνει τη συντεταγμένη X του χαμηλότερου αριστερού σημείου στο σχέδιο όπου αρχίζει το tile.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - η συντεταγμένη X του χαμηλότερου αριστερού σημείου.
### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


Λαμβάνει τη συντεταγμένη Y του χαμηλότερου αριστερού σημείου στο σχέδιο όπου αρχίζει το tile.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - η συντεταγμένη Y του χαμηλότερου αριστερού σημείου.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


Λαμβάνει το πλάτος του tile σε εικονοστοιχεία.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - το πλάτος του tile.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


Λαμβάνει το ύψος του tile σε εικονοστοιχεία.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - το ύψος του tile.
### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


Επιστρέφει τη συντεταγμένη X του υψηλότερου δεξιού σημείου στο σχέδιο όπου το tile τελειώνει.

**Returns:**
int - η συντεταγμένη X του υψηλότερου δεξιού σημείου.
### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


Επιστρέφει τη συντεταγμένη Y του υψηλότερου δεξιού σημείου στο σχέδιο όπου το tile τελειώνει.

**Returns:**
int - η συντεταγμένη Y του υψηλότερου δεξιού σημείου.
