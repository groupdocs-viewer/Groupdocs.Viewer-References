---
title: "Position"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Ορίζει τη θέση του υδατογραφήματος."
type: docs
weight: 43
url: /el/nodejs-java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

Ορίζει τη θέση του υδατογραφήματος.

Το enum Position αντιπροσωπεύει διαφορετικές θέσεις για ένα υδατογράφημα στο στοιχείο GroupDocs.Viewer. Παρέχει ένα σύνολο προκαθορισμένων θέσεων που μπορούν να χρησιμοποιηθούν για τον καθορισμό της τοποθέτησης ενός υδατογραφήματος σε ένα έγγραφο ή εικόνα κατά τη διαδικασία απόδοσης.

Παράδειγμα χρήσης:

```

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Fields

| Field | Περιγραφή |
| --- | --- |
| [DIAGONAL](#DIAGONAL) | Η διαγώνια θέση. |
| [TOP_LEFT](#TOP-LEFT) | Η θέση πάνω αριστερά. |
| [TOP_CENTER](#TOP-CENTER) | Η θέση πάνω κέντρο. |
| [TOP_RIGHT](#TOP-RIGHT) | Η θέση πάνω δεξιά. |
| [BOTTOM_LEFT](#BOTTOM-LEFT) | Η θέση κάτω αριστερά. |
| [BOTTOM_CENTER](#BOTTOM-CENTER) | Η θέση κάτω κέντρο. |
| [BOTTOM_RIGHT](#BOTTOM-RIGHT) | Η θέση κάτω δεξιά. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


Η διαγώνια θέση. Αυτή η θέση αντιπροσωπεύει μια διαγώνια στοίχιση ή τοποθέτηση.

### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


Η θέση πάνω αριστερά. Αυτή η θέση αντιπροσωπεύει την ευθυγράμμιση ή τοποθέτηση στην πάνω αριστερή γωνία.

### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


Η θέση πάνω κέντρο. Αυτή η θέση αντιπροσωπεύει την ευθυγράμμιση ή τοποθέτηση στο πάνω κέντρο.

### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


Η θέση πάνω δεξιά. Αυτή η θέση αντιπροσωπεύει την ευθυγράμμιση ή τοποθέτηση στην πάνω δεξιά γωνία.

### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


Η θέση κάτω αριστερά. Αυτή η θέση αντιπροσωπεύει την ευθυγράμμιση ή τοποθέτηση στην κάτω αριστερή γωνία.

### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


Η θέση κάτω κέντρο. Αυτή η θέση αντιπροσωπεύει την ευθυγράμμιση ή τοποθέτηση στο κάτω κέντρο.

### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


Η θέση κάτω δεξιά. Αυτή η θέση αντιπροσωπεύει την ευθυγράμμιση ή τοποθέτηση στην κάτω δεξιά γωνία.

### values() {#values--}
```
public static Position[] values()
```




**Returns:**
com.groupdocs.viewer.options.Position[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Position valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
