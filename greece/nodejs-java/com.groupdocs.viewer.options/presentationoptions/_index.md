---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Παρέχει επιλογές για την απόδοση επιλογών παρουσιάσεων."
type: docs
weight: 26
url: /el/nodejs-java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Παρέχει επιλογές για την απόδοση επιλογών παρουσιάσεων.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isRenderToPureHtml()](#isRenderToPureHtml--) | Ενεργοποιεί μια νέα λειτουργία απόδοσης HTML για έγγραφα Παρουσίασης. |
| [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Ενεργοποιεί μια νέα λειτουργία απόδοσης HTML για έγγραφα Παρουσίασης. |
| [getResolution()](#getResolution--) | Ανάλυση για εικόνες μέσα στην παρουσίαση (μόνο για απόδοση σε HTML/PDF). |
| [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Ανάλυση για εικόνες μέσα στην παρουσίαση (μόνο για απόδοση σε HTML/PDF). |
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Ενεργοποιεί μια νέα λειτουργία απόδοσης HTML για έγγραφα Παρουσίασης.

Σε αυτή τη λειτουργία, τα αρχεία Παρουσίασης αποδίδονται σε καθαρό σήμανση HTML/CSS, χωρίς εικόνες SVG. Από προεπιλογή, αυτή η δυνατότητα είναι απενεργοποιημένη (false). Ο υπάρχων HTML renderer βασισμένος σε SVG χρησιμοποιείται εάν αυτή η επιλογή δεν είναι ενεργοποιημένη.

**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Ενεργοποιεί μια νέα λειτουργία απόδοσης HTML για έγγραφα Παρουσίασης.

Σε αυτή τη λειτουργία, τα αρχεία Παρουσίασης αποδίδονται σε καθαρό σήμανση HTML/CSS, χωρίς εικόνες SVG. Από προεπιλογή, αυτή η δυνατότητα είναι απενεργοποιημένη (false). Ο υπάρχων HTML renderer βασισμένος σε SVG χρησιμοποιείται εάν αυτή η επιλογή δεν είναι ενεργοποιημένη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Ανάλυση για εικόνες μέσα στην παρουσίαση (μόνο για απόδοση σε HTML/PDF).

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Ανάλυση για εικόνες μέσα στην παρουσίαση (μόνο για απόδοση σε HTML/PDF).

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

