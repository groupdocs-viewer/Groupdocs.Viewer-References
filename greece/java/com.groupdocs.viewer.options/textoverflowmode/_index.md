---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Ορίζει τη λειτουργία υπερχείλισης κειμένου για την απόδοση εγγράφων λογιστικού φύλλου σε HTML."
type: docs
weight: 46
url: /el/java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

Ορίζει τη λειτουργία υπερχείλισης κειμένου για την απόδοση εγγράφων λογιστικού φύλλου σε HTML.


Το enum TextOverflowMode αντιπροσωπεύει διαφορετικές λειτουργίες για τη διαχείριση υπερχείλισης κειμένου στο στοιχείο GroupDocs.Viewer.
Παρέχει ένα σύνολο προεπιλεγμένων επιλογών που μπορούν να χρησιμοποιηθούν για τον έλεγχο του τρόπου εμφάνισης του κειμένου όταν υπερβαίνει το διαθέσιμο
χώρο στα κελιά κατά τη μετατροπή εγγράφων υπολογιστικών φύλλων σε HTML.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


Παράδειγμα χρήσης:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [OVERLAY](#OVERLAY) | Επικάλυψη των επόμενων κελιών ακόμη και αν δεν είναι κενά. |
|
|  | [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | Επικάλυψη των επόμενων κελιών μόνο εάν είναι κενά. |
|
|  | [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | Επέκταση των στηλών ώστε να ταιριάζουν με το κείμενο. |
|
|  | [HIDE_TEXT](#HIDE-TEXT) | Απόκρυψη του υπερχείλιου κειμένου. |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


Επικάλυψη των επόμενων κελιών ακόμη και αν δεν είναι κενά.
Αυτή η λειτουργία επιτρέπει στο κείμενο να υπερχείρει στα γειτονικά κελιά, ανεξάρτητα από το περιεχόμενό τους.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


Επικάλυψη των επόμενων κελιών μόνο εάν είναι κενά.
Αυτή η λειτουργία επιτρέπει στο κείμενο να υπερχείρει στα γειτονικά κελιά μόνο εάν αυτά τα κελιά είναι κενά.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


Επέκταση των στηλών ώστε να ταιριάζουν με το κείμενο.
Αυτή η λειτουργία προσαρμόζει αυτόματα το πλάτος των στηλών ώστε να φιλοξενήσει το υπερχείροντας κείμενο.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


Απόκρυψη του υπερχείλιου κειμένου.
Αυτή η λειτουργία κρύβει το υπερχείροντας κείμενο, αποτρέποντας την εμφάνισή του.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### values() {#values--}
```
public static TextOverflowMode[] values()
```




**Returns:**
com.groupdocs.viewer.options.TextOverflowMode[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TextOverflowMode valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
