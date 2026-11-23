---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Παρέχει επιλογές για την απόδοση λογιστικών φύλλων."
type: docs
weight: 31
url: /el/nodejs-java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

Παρέχει επιλογές για την απόδοση λογιστικών φύλλων.

Η κλάση SpreadsheetOptions περιλαμβάνει διάφορες ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν για τον έλεγχο της απόδοσης αρχείων λογιστικών φύλλων (όπως αρχεία Excel ή CSV) στο στοιχείο GroupDocs.Viewer. Για λεπτομέρειες, δείτε τα υπο-θέματα του θέματος [Render spreadsheet files][].

Παράδειγμα χρήσης:

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
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isRenderByPageBreaks()](#isRenderByPageBreaks--) | Καθορίζει εάν το φύλλο εργασίας πρέπει να αποδοθεί με διακοπές σελίδας. |
| [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | Ορίζει εάν το φύλλο εργασίας πρέπει να αποδοθεί με διακοπές σελίδας. |
| [isDetectSeparator()](#isDetectSeparator--) | Ανιχνεύει το διαχωριστικό για αρχεία CSV/TSV. |
| [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | Ορίζει εάν θα ανιχνευθεί το διαχωριστικό για αρχεία CSV/TSV. |
| [forOnePagePerSheet()](#forOnePagePerSheet--) | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης SpreadsheetOptions για απόδοση ενός φύλλου σε μία σελίδα. |
| [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | Δημιουργεί ένα νέο στιγμιότυπο της κλάσης SpreadsheetOptions για απόδοση ενός φύλλου σε πολλαπλές σελίδες. |
| [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης SpreadsheetOptions για απόδοση ενός φύλλου σε σελίδες. |
| [forRenderingPrintArea()](#forRenderingPrintArea--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης SpreadsheetOptions για απόδοση μόνο των περιοχών εκτύπωσης. |
| [isOnePagePerSheet()](#isOnePagePerSheet--) | Δείχνει εάν ένα φύλλο αποδίδεται σε μία σελίδα. |
| [getCountRowsPerPage()](#getCountRowsPerPage--) | Λαμβάνει τον αριθμό των γραμμών που θα συμπεριληφθούν σε κάθε σελίδα κατά τη διαίρεση του φύλλου εργασίας σε σελίδες. |
| [getCountColumnsPerPage()](#getCountColumnsPerPage--) | Λαμβάνει τον αριθμό των στηλών που θα συμπεριληφθούν σε κάθε σελίδα κατά τη διαίρεση του φύλλου εργασίας σε σελίδες. |
| [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | Ορίζει τον αριθμό των στηλών που θα συμπεριληφθούν σε κάθε σελίδα κατά τη διαίρεση του φύλλου εργασίας σε σελίδες. |
| [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | Δείχνει εάν αποδίδονται μόνο οι περιοχές εκτύπωσης. |
| [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | Όταν αυτή η επιλογή είναι ενεργοποιημένη, ένα φύλλο εργασίας θα αποδοθεί με διακοπές σελίδας που εμπίπτουν στην περιοχή εκτύπωσης. |
| [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | Ορίζει εάν θα αποδοθεί ένα φύλλο εργασίας με διακοπές σελίδας που εμπίπτουν στην περιοχή εκτύπωσης. |
| [isRenderGridLines()](#isRenderGridLines--) | Ενεργοποιεί την απόδοση των γραμμών πλέγματος. |
| [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | Ενεργοποιεί ή απενεργοποιεί την απόδοση των γραμμών πλέγματος. |
| [isSkipEmptyRows()](#isSkipEmptyRows--) | Δείχνει εάν οι κενές γραμμές πρέπει να παραλειφθούν κατά την απόδοση. |
| [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | Ορίζει εάν οι κενές γραμμές πρέπει να παραλειφθούν κατά την απόδοση. |
| [isSkipEmptyColumns()](#isSkipEmptyColumns--) | Δείχνει εάν οι κενές στήλες πρέπει να παραλειφθούν κατά την απόδοση. |
| [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | Ορίζει εάν οι κενές στήλες πρέπει να παραλειφθούν κατά την απόδοση. |
| [isRenderHiddenRows()](#isRenderHiddenRows--) | Καθορίζει εάν οι κρυφές γραμμές πρέπει να αποδοθούν. |
| [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | Ορίζει εάν οι κρυφές γραμμές πρέπει να αποδοθούν. |
| [isRenderHeadings()](#isRenderHeadings--) | Ελέγχει εάν η απόδοση των επικεφαλίδων είναι ενεργοποιημένη. |
| [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | Ενεργοποιεί την απόδοση των επικεφαλίδων. |
| [isRenderHiddenColumns()](#isRenderHiddenColumns--) | Ενεργοποιεί την απόδοση των κρυφών στηλών. |
| [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | Ενεργοποιεί την απόδοση των κρυφών στηλών. |
| [getTextOverflowMode()](#getTextOverflowMode--) | Επιστρέφει τη λειτουργία υπερχείλισης κειμένου για την απόδοση εγγράφων λογιστικού φύλλου σε HTML. |
| [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | Ορίζει τη λειτουργία υπερχείλισης κειμένου για την απόδοση εγγράφων λογιστικού φύλλου σε HTML. |
| [getLeftMargin()](#getLeftMargin--) | Για να ορίσετε το αριστερό περιθώριο του φύλλου εργασίας κατά τη μετατροπή σε PDF, εάν είναι μικρότερο του 0, χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής. |
| [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | Για να ορίσετε το αριστερό περιθώριο του φύλλου εργασίας κατά τη μετατροπή σε PDF, εάν είναι μικρότερο του 0, χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής. |
| [getRightMargin()](#getRightMargin--) | Για να ορίσετε το δεξί περιθώριο του φύλλου εργασίας κατά τη μετατροπή σε PDF, εάν είναι μικρότερο του 0, χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής. Εάν η παράμετρος είναι μικρότερη του 0, τότε χρησιμοποιείται η προεπιλεγμένη τιμή. |
| [setRightMargin(double rightMargin)](#setRightMargin-double-) | Για να ορίσετε το δεξί περιθώριο του φύλλου εργασίας κατά τη μετατροπή σε PDF, εάν είναι μικρότερο του 0, χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής. Εάν η παράμετρος είναι μικρότερη του 0, τότε χρησιμοποιείται η προεπιλεγμένη τιμή. |
| [getTopMargin()](#getTopMargin--) | Για να ορίσετε το επάνω περιθώριο του φύλλου εργασίας κατά τη μετατροπή σε PDF, εάν είναι μικρότερο του 0, χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής. Εάν η παράμετρος είναι μικρότερη του 0, τότε χρησιμοποιείται η προεπιλεγμένη τιμή. |
| [setTopMargin(double topMargin)](#setTopMargin-double-) | Για να ορίσετε το επάνω περιθώριο του φύλλου εργασίας κατά τη μετατροπή σε PDF, εάν είναι μικρότερο του 0, χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής. Εάν η παράμετρος είναι μικρότερη του 0, τότε χρησιμοποιείται η προεπιλεγμένη τιμή. |
| [getBottomMargin()](#getBottomMargin--) | Για να ορίσετε το κάτω περιθώριο του φύλλου εργασίας κατά τη μετατροπή σε PDF, εάν είναι μικρότερο του 0, χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής. Εάν η παράμετρος είναι μικρότερη του 0, τότε χρησιμοποιείται η προεπιλεγμένη τιμή. |
| [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | Για να ορίσετε το κάτω περιθώριο του φύλλου εργασίας κατά τη μετατροπή σε PDF, εάν είναι μικρότερο του 0, χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής. Εάν η παράμετρος είναι μικρότερη του 0, τότε χρησιμοποιείται η προεπιλεγμένη τιμή. |
| [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | Αρχικοποιεί ένα νέο στιγμιότυπο του  SpreadsheetOptions  για την απόδοση περιοχών εκτύπωσης και αλλαγών σελίδας. |
| [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης SpreadsheetOptions για απόδοση μόνο των περιοχών εκτύπωσης. |
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


Καθορίζει εάν το φύλλο εργασίας πρέπει να αποδοθεί με διακοπές σελίδας.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Returns:**
boolean -  true  εάν το φύλλο εργασίας πρέπει να αποδοθεί με αλλαγές σελίδας,  false  διαφορετικά.
### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


Ορίζει εάν το φύλλο εργασίας πρέπει να αποδοθεί με διακοπές σελίδας.

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderByPageBreaks | boolean | true  εάν το φύλλο εργασίας πρέπει να αποδοθεί με αλλαγές σελίδας,  false  διαφορετικά. |

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


Ανιχνεύει το διαχωριστικό για αρχεία CSV/TSV.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Returns:**
boolean -  true  εάν ο διαχωριστής πρέπει να εντοπιστεί αυτόματα,  false  διαφορετικά.
### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


Ορίζει εάν θα ανιχνευθεί το διαχωριστικό για αρχεία CSV/TSV.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| detectSeparator | boolean | true  για αυτόματη ανίχνευση του διαχωριστή,  false  διαφορετικά. |

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης SpreadsheetOptions για απόδοση ενός φύλλου σε μία σελίδα.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.
### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


Δημιουργεί ένα νέο στιγμιότυπο της κλάσης SpreadsheetOptions για απόδοση ενός φύλλου σε πολλαπλές σελίδες.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| countRowsPerPage | int | Ο αριθμός των γραμμών που θα συμπεριληφθούν σε κάθε σελίδα. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.
### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης SpreadsheetOptions για απόδοση ενός φύλλου σε σελίδες.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| countRowsPerPage | int | Ο αριθμός των γραμμών που θα συμπεριληφθούν σε κάθε σελίδα. |
| countColumnsPerPage | int | Ο αριθμός των στηλών που θα συμπεριληφθούν σε κάθε σελίδα. |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.
### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης SpreadsheetOptions για απόδοση μόνο των περιοχών εκτύπωσης.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.
### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


Δείχνει εάν ένα φύλλο αποδίδεται σε μία σελίδα.

**Returns:**
boolean -  true  εάν ένα φύλλο αποδίδεται σε μία σελίδα·  false  διαφορετικά.
### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


Λαμβάνει τον αριθμό των γραμμών που θα συμπεριληφθούν σε κάθε σελίδα κατά τη διαίρεση του φύλλου εργασίας σε σελίδες.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Returns:**
int - ο αριθμός των γραμμών που θα συμπεριληφθούν σε κάθε σελίδα.
### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


Λαμβάνει τον αριθμό των στηλών που θα συμπεριληφθούν σε κάθε σελίδα κατά τη διαίρεση του φύλλου εργασίας σε σελίδες.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Returns:**
int - ο αριθμός των στηλών που θα συμπεριληφθούν σε κάθε σελίδα.
### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


Ορίζει τον αριθμό των στηλών που θα συμπεριληφθούν σε κάθε σελίδα κατά τη διαίρεση του φύλλου εργασίας σε σελίδες.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| countColumnsPerPage | int | Ο αριθμός των στηλών που θα συμπεριληφθούν σε κάθε σελίδα. |

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


Δείχνει εάν αποδίδονται μόνο οι περιοχές εκτύπωσης.

**Returns:**
boolean -  true  εάν αποδίδονται μόνο οι περιοχές εκτύπωσης,  false  διαφορετικά.
### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


Όταν αυτή η επιλογή είναι ενεργοποιημένη, ένα φύλλο εργασίας θα αποδοθεί με διακοπές σελίδας που εμπίπτουν στην περιοχή εκτύπωσης.

**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


Ορίζει εάν θα αποδοθεί ένα φύλλο εργασίας με διακοπές σελίδας που εμπίπτουν στην περιοχή εκτύπωσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderingPrintAreaAndPageBreaks | boolean | Ορίστε σε true για ενεργοποίηση, false για απενεργοποίηση. |

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


Ενεργοποιεί την απόδοση των γραμμών πλέγματος.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Returns:**
boolean -  true  εάν οι γραμμές πλέγματος είναι ενεργοποιημένες,  false  διαφορετικά.
### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


Ενεργοποιεί ή απενεργοποιεί την απόδοση των γραμμών πλέγματος.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | true  για ενεργοποίηση απόδοσης γραμμών πλέγματος,  false  για απενεργοποίηση. |

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


Δείχνει εάν οι κενές γραμμές πρέπει να παραλειφθούν κατά την απόδοση.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  εάν πρέπει να παραλείπονται κενές γραμμές,  false  διαφορετικά.
### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


Ορίζει εάν οι κενές γραμμές πρέπει να παραλειφθούν κατά την απόδοση.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | true  για παράλειψη κενών γραμμών,  false  διαφορετικά. |

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


Δείχνει εάν οι κενές στήλες πρέπει να παραλειφθούν κατά την απόδοση.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  εάν παραλείπονται κενές στήλες,  false  διαφορετικά.
### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


Ορίζει εάν οι κενές στήλες πρέπει να παραλειφθούν κατά την απόδοση.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | true  για παράλειψη κενών στηλών,  false  διαφορετικά. |

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


Καθορίζει εάν οι κρυφές γραμμές πρέπει να αποδοθούν.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  εάν πρέπει να αποδοθούν κρυφές γραμμές,  false  διαφορετικά.
### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


Ορίζει εάν οι κρυφές γραμμές πρέπει να αποδοθούν.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | true  για ενεργοποίηση απόδοσης κρυφών γραμμών,  false  για απενεργοποίηση. |

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


Ελέγχει εάν η απόδοση των επικεφαλίδων είναι ενεργοποιημένη.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Returns:**
boolean -  true  εάν η απόδοση επικεφαλίδων είναι ενεργοποιημένη,  false  διαφορετικά.
### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


Ενεργοποιεί την απόδοση των επικεφαλίδων.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderHeadings | boolean | true  για ενεργοποίηση απόδοσης επικεφαλίδων,  false  για απενεργοποίηση. |

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


Ενεργοποιεί την απόδοση των κρυφών στηλών.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  εάν η απόδοση κρυφών στηλών είναι ενεργοποιημένη,  false  διαφορετικά.
### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


Ενεργοποιεί την απόδοση των κρυφών στηλών.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | boolean | true  για ενεργοποίηση απόδοσης κρυφών στηλών,  false  για απενεργοποίηση. |

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


Επιστρέφει τη λειτουργία υπερχείλισης κειμένου για την απόδοση εγγράφων λογιστικού φύλλου σε HTML.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.
### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


Ορίζει τη λειτουργία υπερχείλισης κειμένου για την απόδοση εγγράφων λογιστικού φύλλου σε HTML. Για λεπτομέρειες, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | Η λειτουργία υπερχείλισης κειμένου που θα οριστεί. |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


Για να ορίσετε το αριστερό περιθώριο του φύλλου εργασίας κατά τη μετατροπή σε PDF, εάν είναι μικρότερο του 0, χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής.

Εάν η παράμετρος είναι μικρότερη του 0, τότε χρησιμοποιείται η προεπιλεγμένη τιμή. Για λεπτομέρειες, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


Για να ορίσετε το αριστερό περιθώριο του φύλλου εργασίας κατά τη μετατροπή σε PDF, εάν είναι μικρότερο του 0, χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής.

Εάν η παράμετρος είναι μικρότερη του 0, τότε χρησιμοποιείται η προεπιλεγμένη τιμή. Για λεπτομέρειες, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


Για ορισμό του δεξιού περιθωρίου του φύλλου εργασίας κατά τη μετατροπή σε pdf, εάν είναι μικρότερο του 0 τότε χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής. Εάν η παράμετρος είναι μικρότερη του 0, τότε χρησιμοποιείται η προεπιλεγμένη τιμή. Για λεπτομέρειες, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


Για ορισμό του δεξιού περιθωρίου του φύλλου εργασίας κατά τη μετατροπή σε pdf, εάν είναι μικρότερο του 0 τότε χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής. Εάν η παράμετρος είναι μικρότερη του 0, τότε χρησιμοποιείται η προεπιλεγμένη τιμή. Για λεπτομέρειες, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


Για ορισμό του άνω περιθωρίου του φύλλου εργασίας κατά τη μετατροπή σε pdf, εάν είναι μικρότερο του 0 τότε χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής. Εάν η παράμετρος είναι μικρότερη του 0, τότε χρησιμοποιείται η προεπιλεγμένη τιμή. Για λεπτομέρειες, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


Για ορισμό του άνω περιθωρίου του φύλλου εργασίας κατά τη μετατροπή σε pdf, εάν είναι μικρότερο του 0 τότε χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής. Εάν η παράμετρος είναι μικρότερη του 0, τότε χρησιμοποιείται η προεπιλεγμένη τιμή. Για λεπτομέρειες, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


Για ορισμό του κάτω περιθωρίου του φύλλου εργασίας κατά τη μετατροπή σε pdf, εάν είναι μικρότερο του 0 τότε χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής. Εάν η παράμετρος είναι μικρότερη του 0, τότε χρησιμοποιείται η προεπιλεγμένη τιμή. Για λεπτομέρειες, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


Για ορισμό του κάτω περιθωρίου του φύλλου εργασίας κατά τη μετατροπή σε pdf, εάν είναι μικρότερο του 0 τότε χρησιμοποιείται η προεπιλεγμένη τιμή μετατροπής. Εάν η παράμετρος είναι μικρότερη του 0, τότε χρησιμοποιείται η προεπιλεγμένη τιμή. Για λεπτομέρειες, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bottomMargin | double |  |

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


Αρχικοποιεί ένα νέο στιγμιότυπο του  SpreadsheetOptions  για την απόδοση περιοχών εκτύπωσης και αλλαγών σελίδας. Για λεπτομέρειες, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.
### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  SpreadsheetOptions  μόνο για την απόδοση περιοχών εκτύπωσης. Για λεπτομέρειες, δείτε την [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.
