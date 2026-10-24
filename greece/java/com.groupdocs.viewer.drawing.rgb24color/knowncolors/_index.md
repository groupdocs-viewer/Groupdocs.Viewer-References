---
title: "KnownColors"
second_title: "GroupDocs.Viewer για Java API Reference"
description: 
type: docs
weight: 10
url: /el/java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | Προσπαθεί να βρει ένα χρώμα με το όνομα του σε μορφή κειμένου. |
|
|  | [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | Προσπαθεί να βρει το όνομα ενός χρώματος με την τιμή RGB του. |
|
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


Προσπαθεί να βρει ένα χρώμα με το όνομα του σε μορφή κειμένου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | λέξη-κλειδί | java.lang.String | Ένα όνομα χρώματος. |
|
|  | output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | Το δοχείο αποτελέσματος για το βρεθέν χρώμα, ή CssLevel1.Black σε περίπτωση αποτυχίας. |
|

**Returns:**
boolean - True εάν το χρώμα βρέθηκε επιτυχώς με το όνομα, false διαφορετικά.

### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


Προσπαθεί να βρει το όνομα ενός χρώματος με την τιμή RGB του.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | Μία παρουσία χρώματος. |
|
|  | όνομα | java.lang.String[] | Το δοχείο αποτελέσματος για το βρεθέν όνομα χρώματος, ή null σε περίπτωση αποτυχίας. |
|

**Returns:**
boolean - True εάν το όνομα βρέθηκε επιτυχώς για το δεδομένο χρώμα, false διαφορετικά.

