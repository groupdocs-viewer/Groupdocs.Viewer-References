---
title: "Watermark"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αναπαριστά ένα υδατογράφημα κειμένου."
type: docs
weight: 37
url: /el/java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

Αναπαριστά ένα υδατογράφημα κειμένου. Για λεπτομέρειες, δείτε την [documentation](../https://docs.groupdocs.com/viewer/net/add-text-watermark/).


Η κλάση Watermark αντιπροσωπεύει ένα υδατογράφημα κειμένου στο στοιχείο GroupDocs.Viewer.
Χρησιμοποιείται για τον ορισμό και την εφαρμογή ενός υδατογραφήματος στην παραγόμενη έξοδο των εγγράφων.


Παράδειγμα χρήσης:

````

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
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Watermark(String text)](#Watermark-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία του |
Watermark
κλάσης.
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getText()](#getText--) | Επιστρέφει το κείμενο του υδατογραφήματος. |
|
|  | [getColor()](#getColor--) | Επιστρέφει το χρώμα του υδατογραφήματος. |
|
|  | [getColorAsHex()](#getColorAsHex--) | Επιστρέφει το χρώμα του υδατογραφήματος σε μορφή hex. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Ορίζει το χρώμα του υδατογραφήματος. |
|
|  | [setColor(String colorName)](#setColor-java.lang.String-) | Ορίζει το χρώμα του υδατογραφήματος. |
|
|  | [getPosition()](#getPosition--) | Επιστρέφει τη θέση του υδατογραφήματος. |
|
|  | [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | Ορίζει τη θέση του υδατογραφήματος. |
|
|  | [getSize()](#getSize--) | Επιστρέφει το μέγεθος του υδατογραφήματος. |
|
|  | [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | Ορίζει το μέγεθος του υδατογραφήματος. |
|
|  | [getFontName()](#getFontName--) | Επιστρέφει το όνομα της γραμματοσειράς που χρησιμοποιείται για το υδατογράφημα. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | Ορίζει το όνομα της γραμματοσειράς που χρησιμοποιείται για το υδατογράφημα. |
|
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Αρχικοποιεί μια νέα παρουσία του
Watermark
κλάσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | κείμενο | java.lang.String | Το κείμενο του υδατογραφήματος. |
|

### getText() {#getText--}
```
public final String getText()
```


Επιστρέφει το κείμενο του υδατογραφήματος.
Αυτή η μέθοδος ανακτά το κείμενο του υδατογραφήματος που εφαρμόζεται στο έγγραφο.


**Returns:**
java.lang.String - το κείμενο του υδατογραφήματος.

### getColor() {#getColor--}
```
public final Color getColor()
```


Επιστρέφει το χρώμα του υδατογραφήματος.
Αυτή η μέθοδος ανακτά το χρώμα του υδατογραφήματος που εφαρμόζεται στο έγγραφο.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.awt.Color - το χρώμα του υδατογραφήματος.

### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


Επιστρέφει το χρώμα του υδατογραφήματος σε μορφή hex.
Αυτή η μέθοδος ανακτά το χρώμα του υδατογραφήματος που εφαρμόζεται στο έγγραφο.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.lang.String - το χρώμα του υδατογραφήματος σε δεκαεξαδική μορφή.

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Ορίζει το χρώμα του υδατογραφήματος.
Αυτή η μέθοδος ορίζει το χρώμα του υδατογραφήματος που εφαρμόζεται στο έγγραφο.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.awt.Color | Το χρώμα του υδατογραφήματος προς ορισμό. |
|

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Ορίζει το χρώμα του υδατογραφήματος.
Αυτή η μέθοδος ορίζει το χρώμα του υδατογραφήματος που εφαρμόζεται στο έγγραφο.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | colorName | java.lang.String | Το χρώμα του υδατογραφήματος προς ορισμό. |
|

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


Επιστρέφει τη θέση του υδατογραφήματος.
Αυτή η μέθοδος επιστρέφει τη θέση του υδατογραφήματος που εφαρμόζεται στο έγγραφο.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.

### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


Ορίζει τη θέση του υδατογραφήματος.
Αυτή η μέθοδος ορίζει τη θέση του υδατογραφήματος που εφαρμόζεται στο έγγραφο.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Position](../../com.groupdocs.viewer.options/position) | Η θέση του υδατογραφήματος. |
|

### getSize() {#getSize--}
```
public final Size getSize()
```


Επιστρέφει το μέγεθος του υδατογραφήματος.
Αυτή η μέθοδος ανακτά το μέγεθος του υδατογραφήματος που εφαρμόζεται στο έγγραφο.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.

### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


Ορίζει το μέγεθος του υδατογραφήματος.
Αυτή η μέθοδος ορίζει το μέγεθος του υδατογραφήματος που θα εφαρμοστεί στο έγγραφο.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.viewer.options/size) | Το μέγεθος του υδατογραφήματος. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Επιστρέφει το όνομα της γραμματοσειράς που χρησιμοποιείται για το υδατογράφημα.


**Returns:**
java.lang.String - το όνομα της γραμματοσειράς που χρησιμοποιείται για το υδατογράφημα.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Ορίζει το όνομα της γραμματοσειράς που χρησιμοποιείται για το υδατογράφημα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Το όνομα της γραμματοσειράς που χρησιμοποιείται για το υδατογράφημα. |
|

