---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Αντιπροσωπεύει πληροφορίες προβολής για ένα σχέδιο CAD."
type: docs
weight: 13
url: /el/nodejs-java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

Αντιπροσωπεύει πληροφορίες προβολής για ένα σχέδιο CAD.

Η διεπαφή CadViewInfo ορίζει τη σύμβαση για την ανάκτηση πληροφοριών προβολής ειδικά για ένα σχέδιο CAD στο στοιχείο GroupDocs.Viewer. Παρέχει μεθόδους για πρόσβαση σε στρώματα σχεδίων CAD.

Παράδειγμα χρήσης:

```

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is CadViewInfoImpl.*
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getLayers()](#getLayers--) | Ανακτά τη λίστα των στρωμάτων στο σχέδιο CAD. |
| [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Ορίζει τη λίστα των στρωμάτων στο σχέδιο CAD. |
| [getLayouts()](#getLayouts--) | Ανακτά τη λίστα των διατάξεων που περιέχονται στο σχέδιο CAD. |
| [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | Ορίζει τη λίστα των διατάξεων που περιέχονται στο σχέδιο CAD. |
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


Ανακτά τη λίστα των στρωμάτων στο σχέδιο CAD.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - τα στρώματα στο σχέδιο CAD.
### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


Ορίζει τη λίστα των στρωμάτων στο σχέδιο CAD.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| στρώματα | java.util.List<com.groupdocs.viewer.results.Layer> | τα στρώματα που θα οριστούν για το σχέδιο CAD. |

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


Ανακτά τη λίστα των διατάξεων που περιέχονται στο σχέδιο CAD.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - οι διατάξεις στο σχέδιο CAD.
### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


Ορίζει τη λίστα των διατάξεων που περιέχονται στο σχέδιο CAD.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διατάξεις | java.util.List<com.groupdocs.viewer.results.Layout> | οι διατάξεις που θα οριστούν για το σχέδιο CAD. |

