---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Παρέχει επιλογές για την απόδοση παρουσιάσεων."
type: docs
weight: 26
url: /el/java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Παρέχει επιλογές για την απόδοση παρουσιάσεων.


Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-presentations/).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [isRenderToPureHtml()](#isRenderToPureHtml--) | Ενεργοποιεί μια νέα λειτουργία απόδοσης HTML για έγγραφα Presentation. |
|
|  | [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Ενεργοποιεί μια νέα λειτουργία απόδοσης HTML για έγγραφα Presentation. |
|
|  | [isRenderHeaderFooterPlaceholders()](#isRenderHeaderFooterPlaceholders--) | Ενεργοποιεί την απόδοση placeholders στην κεφαλίδα και το υποσέλιδο μιας διαφάνειας. |
|
|  | [setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)](#setRenderHeaderFooterPlaceholders-boolean-) | Ενεργοποιεί την απόδοση placeholders στην κεφαλίδα και το υποσέλιδο μιας διαφάνειας. |
|
|  | [getResolution()](#getResolution--) | Ανάλυση για εικόνες μέσα στην παρουσίαση (μόνο για απόδοση σε HTML/PDF). |
|
|  | [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Ανάλυση για εικόνες μέσα στην παρουσίαση (μόνο για απόδοση σε HTML/PDF). |
|
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Ενεργοποιεί μια νέα λειτουργία απόδοσης HTML για έγγραφα Presentation.


Σε αυτή τη λειτουργία, τα αρχεία Presentation αποδίδονται σε καθαρό markup HTML/CSS, χωρίς εικόνες SVG.
Από προεπιλογή, αυτή η λειτουργία είναι απενεργοποιημένη (false). Ο υπάρχων renderer HTML βασισμένος σε SVG χρησιμοποιείται εάν αυτή η επιλογή δεν είναι ενεργοποιημένη.


**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Ενεργοποιεί μια νέα λειτουργία απόδοσης HTML για έγγραφα Presentation.


Σε αυτή τη λειτουργία, τα αρχεία Presentation αποδίδονται σε καθαρό markup HTML/CSS, χωρίς εικόνες SVG.
Από προεπιλογή, αυτή η λειτουργία είναι απενεργοποιημένη (false). Ο υπάρχων renderer HTML βασισμένος σε SVG χρησιμοποιείται εάν αυτή η επιλογή δεν είναι ενεργοποιημένη.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### isRenderHeaderFooterPlaceholders() {#isRenderHeaderFooterPlaceholders--}
```
public boolean isRenderHeaderFooterPlaceholders()
```


Ενεργοποιεί την απόδοση των δεσμευτικών θέσεων στην κεφαλίδα και το υποσέλιδο μιας διαφάνειας. Απενεργοποιημένο εξ ορισμού (false). Αυτή η επιλογή ισχύει για όλες τις 4 λειτουργίες απόδοσης παρουσιάσεων: HTML, PDF, PNG και JPEG. Δεν ισχύει όταν η παρουσίαση αποδίδεται σε καθαρό HTML/CSS markup χρησιμοποιώντας .


**Returns:**
boolean
### setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders) {#setRenderHeaderFooterPlaceholders-boolean-}
```
public void setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)
```


Ενεργοποιεί την απόδοση των δεσμευτικών θέσεων στην κεφαλίδα και το υποσέλιδο μιας διαφάνειας. Απενεργοποιημένο εξ ορισμού (false). Αυτή η επιλογή ισχύει για όλες τις 4 λειτουργίες απόδοσης παρουσιάσεων: HTML, PDF, PNG και JPEG. Δεν ισχύει όταν η παρουσίαση αποδίδεται σε καθαρό HTML/CSS markup χρησιμοποιώντας .


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderHeaderFooterPlaceholders | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Ανάλυση για εικόνες μέσα στην παρουσίαση (μόνο για απόδοση σε HTML/PDF).


Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Ανάλυση για εικόνες μέσα στην παρουσίαση (μόνο για απόδοση σε HTML/PDF).


Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

