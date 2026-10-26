---
title: "TimeUnit"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Μονάδα χρόνου της διάρκειας του έργου."
type: docs
weight: 47
url: /el/nodejs-java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

Μονάδα χρόνου της διάρκειας του έργου.

Η απαρίθμηση TimeUnit αντιπροσωπεύει διαφορετικές μονάδες χρόνου για τον καθορισμό της διάρκειας ενός έργου στο στοιχείο GroupDocs.Viewer. Παρέχει ένα σύνολο προκαθορισμένων μονάδων χρόνου που μπορούν να χρησιμοποιηθούν για την αναπαράσταση και τον υπολογισμό της διάρκειας ενός έργου, όπως ημέρες, μήνες κ.λπ. Για λεπτομέρειες, δείτε την [documentation][].

Παράδειγμα χρήσης:

```

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit
## Fields

| Field | Περιγραφή |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | Η άγνωστη κλίμακα χρόνου. |
| [DAYS](#DAYS) | Κλίμακα χρόνου ημερών. |
| [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | Κλίμακα χρόνου τριών του μήνα. |
| [MONTHS](#MONTHS) | Κλίμακα χρόνου μηνών. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


Η άγνωστη κλίμακα χρόνου. Αυτή η μονάδα χρόνου αντιπροσωπεύει μια άγνωστη ή ακαθόριστη κλίμακα χρόνου.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


Κλίμακα χρόνου ημερών. Αυτή η μονάδα χρόνου αντιπροσωπεύει ένα διαστήμα μιας ημέρας.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


Κλίμακα χρόνου τριών του μήνα. Αυτή η μονάδα χρόνου αντιπροσωπεύει ένα τρίτο του μηνιαίου διαστήματος.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


Κλίμακα χρόνου μηνών. Αυτή η μονάδα χρόνου αντιπροσωπεύει ένα μηνιαίο διάστημα.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

### values() {#values--}
```
public static TimeUnit[] values()
```




**Returns:**
com.groupdocs.viewer.options.TimeUnit[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TimeUnit valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
