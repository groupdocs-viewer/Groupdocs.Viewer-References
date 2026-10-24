---
title: "Viewer"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία απόδοσης του εγγράφου."
type: docs
weight: 12
url: /el/java/com.groupdocs.viewer/viewer/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Viewer implements Closeable
```

Αντιπροσωπεύει την κύρια κλάση που ελέγχει τη διαδικασία απόδοσης του εγγράφου.


Η κλάση Viewer είναι το σημείο εισόδου για την απόδοση εγγράφων χρησιμοποιώντας το στοιχείο GroupDocs.Viewer.
Παρέχει μεθόδους και επιλογές για τη φόρτωση εγγράφων από διάφορες πηγές, την προσαρμογή της διαδικασίας απόδοσης και την ανάκτηση του παραγόμενου αποτελέσματος σε διαφορετικές μορφές.


Παράδειγμα χρήσης:

````

 try (Viewer viewer = new Viewer("source.pdf")) {
     viewer.view(new PngViewOptions("result-page{0}.png"));
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Viewer(InputStream fileStream)](#Viewer-java.io.InputStream-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(InputStream fileStream, boolean leaveOpen)](#Viewer-java.io.InputStream-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)](#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-) | Αρχικοποιεί νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(URL url)](#Viewer-java.net.URL-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(URL url, LoadOptions loadOptions)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(URL url, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(FileReader fileReader, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(String filePath)](#Viewer-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(Path filePath)](#Viewer-java.nio.file.Path-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(String filePath, LoadOptions loadOptions)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(String filePath, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(Path filePath, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
|  | [Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)](#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer. |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [LOAD_OPTIONS](#LOAD-OPTIONS) |  |
| [SETTINGS](#SETTINGS) |  |
| [FILE_READER](#FILE-READER) |  |
| [OPTIONS](#OPTIONS) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getViewInfo(ViewInfoOptions options)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-) | Επιστρέφει πληροφορίες σχετικά με την προβολή και συγκεκριμένες πληροφορίες του εγγράφου. |
|
|  | [getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)](#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-) | Επιστρέφει πληροφορίες σχετικά με την προβολή και συγκεκριμένες πληροφορίες του εγγράφου. |
|
|  | [getAttachments()](#getAttachments--) | Επιστρέφει τα συνημμένα που περιέχονται στο έγγραφο. |
|
|  | [getAttachments(CancellationToken cancellationToken)](#getAttachments-com.groupdocs.viewer.utils.CancellationToken-) | Επιστρέφει τα συνημμένα που περιέχονται στο έγγραφο. |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-) | Αποθηκεύει ένα αρχείο συνημμένου στη ροή προορισμού. |
|
|  | [saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)](#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-) | Αποθηκεύει ένα αρχείο συνημμένου στη ροή προορισμού. |
|
|  | [view(ViewOptions options)](#view-com.groupdocs.viewer.options.ViewOptions-) | Δημιουργεί μια προβολή όλων των σελίδων του εγγράφου. |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-) | Δημιουργεί μια προβολή όλων των σελίδων του εγγράφου. |
|
|  | [view(ViewOptions options, int pageNumber)](#view-com.groupdocs.viewer.options.ViewOptions-int-) | Δημιουργεί μια προβολή συγκεκριμένης σελίδας του εγγράφου. |
|
|  | [view(ViewOptions options, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-int...-) | Δημιουργεί μια προβολή συγκεκριμένων σελίδων του εγγράφου. |
|
|  | [view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)](#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-) | Δημιουργεί μια προβολή συγκεκριμένων σελίδων του εγγράφου. |
|
|  | [getAllFonts()](#getAllFonts--) | Επιστρέφει όλες τις γραμματοσειρές που χρησιμοποιούνται στα φορτωμένα έγγραφα, συμπεριλαμβανομένων των ενσωματωμένων στο ίδιο το έγγραφο και των γραμματοσειρών συστήματος που είναι εγκατεστημένες στο λειτουργικό σύστημα και χρησιμοποιούνται στο έγγραφο. |
|
|  | [search(SearchHighlightOptions options)](#search-com.groupdocs.viewer.options.SearchHighlightOptions-) | Πραγματοποιεί αναζήτηση κειμένου και επισημαίνει τις αντιστοιχίες (αν βρεθούν) στο φορτωμένο έγγραφο σύμφωνα με τις παρεχόμενες επιλογές. |
|
|  | [getFileInfo()](#getFileInfo--) | Επιστρέφει πληροφορίες σχετικά με το αρχείο, όπως τον τύπο του αρχείου και μια σημαία που υποδεικνύει αν το αρχείο είναι κρυπτογραφημένο. |
|
|  | [close()](#close--) | Απελευθερώνει τη ροή αρχείου και τους διαχειριζόμενους εσωτερικούς πόρους. |
|
### Viewer(InputStream fileStream) {#Viewer-java.io.InputStream-}
```
public Viewer(InputStream fileStream)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.


Περισσότερα για τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer:
[Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Η μέθοδος που επιστρέφει μια αναγνώσιμη ροή. |
|

### Viewer(InputStream fileStream, boolean leaveOpen) {#Viewer-java.io.InputStream-boolean-}
```
public Viewer(InputStream fileStream, boolean leaveOpen)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Η ροή αρχείου. |
|
|  | leaveOpen | boolean | true για να αφήσετε τη ροή ανοιχτή μετά την απελευθέρωση του αντικειμένου Viewer· διαφορετικά, false. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Η αναγνώσιμη ροή. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, boolean leaveOpen)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Η ροή αρχείου. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |
|
|  | leaveOpen | boolean | true για να αφήσετε τη ροή ανοιχτή μετά την απελευθέρωση του αντικειμένου Viewer· διαφορετικά, false. |
|

### Viewer(InputStream fileStream, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, ViewerSettings settings)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Η ροή αρχείου. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Οι ρυθμίσεις του Viewer. |
|

### Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, ViewerSettings settings, boolean leaveOpen)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Η ροή αρχείου. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Οι ρυθμίσεις του Viewer. |
|
|  | leaveOpen | boolean | true για να αφήσετε τη ροή ανοιχτή μετά την απελευθέρωση του αντικειμένου Viewer· διαφορετικά, false. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Η ροή αρχείου. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Οι ρυθμίσεις του Viewer. |
|

### Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen) {#Viewer-java.io.InputStream-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-boolean-}
```
public Viewer(InputStream fileStream, LoadOptions loadOptions, ViewerSettings settings, boolean leaveOpen)
```


Αρχικοποιεί νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileStream | java.io.InputStream | Η ροή αρχείου. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Οι ρυθμίσεις του Viewer. |
|
|  | leaveOpen | boolean | true για να αφήσετε τη ροή ανοιχτή μετά την απελευθέρωση του αντικειμένου Viewer· διαφορετικά, false. |
|

### Viewer(URL url) {#Viewer-java.net.URL-}
```
public Viewer(URL url)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.


Περισσότερα για τους τύπους αρχείων που υποστηρίζονται από το GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | url | java.net.URL | Ένα URL προς ένα αρχείο που πρέπει να φορτωθεί στον Viewer. |
|

### Viewer(URL url, LoadOptions loadOptions) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(URL url, LoadOptions loadOptions)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | url | java.net.URL | Ένα URL προς ένα αρχείο που πρέπει να φορτωθεί στον Viewer. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |
|

### Viewer(URL url, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, ViewerSettings settings)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | url | java.net.URL | Ένα URL προς ένα αρχείο που πρέπει να φορτωθεί στον Viewer. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Οι ρυθμίσεις του Viewer. |
|

### Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.net.URL-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(URL url, LoadOptions loadOptions, ViewerSettings settings)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | url | java.net.URL | Ένα URL προς ένα αρχείο που πρέπει να φορτωθεί στον Viewer. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Οι ρυθμίσεις του Viewer. |
|

### Viewer(FileReader fileReader, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, ViewerSettings settings)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.


Αυτός ο κατασκευαστής σας επιτρέπει να δημιουργήσετε ένα αντικείμενο Viewer για να προβάλετε ένα έγγραφο από ένα [FileReader](../../com.groupdocs.viewer.interfaces/filereader) με τις καθορισμένες [ViewerSettings](../../com.groupdocs.viewer/viewersettings).
***Learn more**
* To learn about the file types supported by GroupDocs.Viewer, visit: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* To explore the features of GroupDocs.Viewer for Java, refer to: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Ο [FileReader](../../com.groupdocs.viewer.interfaces/filereader) που περιέχει το έγγραφο που θα φορτωθεί στον Viewer. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Οι [ViewerSettings](../../com.groupdocs.viewer/viewersettings) που θα εφαρμοστούν στον Viewer. |
|

### Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-com.groupdocs.viewer.interfaces.FileReader-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(FileReader fileReader, LoadOptions loadOptions, ViewerSettings settings)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.


Παρέχει λειτουργικότητα για τη φόρτωση και προβολή εγγράφων χρησιμοποιώντας το GroupDocs.Viewer.


**Note:** Ensure that the file reader, load options, and settings are properly configured for accurate document processing.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileReader | [FileReader](../../com.groupdocs.viewer.interfaces/filereader) | Ο αναγνώστης αρχείου. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Οι επιλογές φόρτωσης. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Οι ρυθμίσεις του Viewer. |
|

### Viewer(String filePath) {#Viewer-java.lang.String-}
```
public Viewer(String filePath)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more:**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή προς το αρχείο που θα αποδοθεί. |
|

### Viewer(Path filePath) {#Viewer-java.nio.file.Path-}
```
public Viewer(Path filePath)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Η διαδρομή προς το αρχείο που θα αποδοθεί. |
|

### Viewer(String filePath, LoadOptions loadOptions) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(String filePath, LoadOptions loadOptions)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή προς το αρχείο που θα αποδοθεί. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |
|

### Viewer(Path filePath, LoadOptions loadOptions) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-}
```
public Viewer(Path filePath, LoadOptions loadOptions)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view a document with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Η διαδρομή προς το αρχείο που θα αποδοθεί. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |
|

### Viewer(String filePath, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, ViewerSettings settings)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή προς το αρχείο που θα αποδοθεί. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Οι ρυθμίσεις του Viewer. |
|

### Viewer(Path filePath, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, ViewerSettings settings)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Η διαδρομή προς το αρχείο που θα αποδοθεί. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Οι ρυθμίσεις του Viewer. |
|

### Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.lang.String-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(String filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.lang.String | Η διαδρομή προς το αρχείο που θα αποδοθεί. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Οι ρυθμίσεις του Viewer. |
|

### Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings) {#Viewer-java.nio.file.Path-com.groupdocs.viewer.options.LoadOptions-com.groupdocs.viewer.ViewerSettings-}
```
public Viewer(Path filePath, LoadOptions loadOptions, ViewerSettings settings)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης Viewer.
***Learn more**
* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Supported+Document+Formats)
* More about GroupDocs.Viewer for Java features: [Developer Guide](../https://docs.groupdocs.com/display/viewerjava/Developer+Guide)
* More about loading password-protected documents and viewing files from third-party storages with GroupDocs.Viewer for Java: [How to load and view documents with GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Loading)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | filePath | java.nio.file.Path | Η διαδρομή προς το αρχείο που θα αποδοθεί. |
|
|  | loadOptions | [LoadOptions](../../com.groupdocs.viewer.options/loadoptions) | Οι επιλογές φόρτωσης του εγγράφου. |
|
|  | settings | [ViewerSettings](../../com.groupdocs.viewer/viewersettings) | Οι ρυθμίσεις του Viewer. |
|

### LOAD_OPTIONS {#LOAD-OPTIONS}
```
public static final String LOAD_OPTIONS
```


### SETTINGS {#SETTINGS}
```
public static final String SETTINGS
```


### FILE_READER {#FILE-READER}
```
public static final String FILE_READER
```


### OPTIONS {#OPTIONS}
```
public static final String OPTIONS
```


### getViewInfo(ViewInfoOptions options) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options)
```


Επιστρέφει πληροφορίες σχετικά με την προβολή και συγκεκριμένες πληροφορίες του εγγράφου.
***Learn more:**
* Learn more about the document - file type, page count, and other format specific properties: [How to get file information using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+file+information)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | Οι επιλογές πληροφοριών προβολής. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken) {#getViewInfo-com.groupdocs.viewer.options.ViewInfoOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final ViewInfo getViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```


Επιστρέφει πληροφορίες σχετικά με την προβολή και συγκεκριμένες πληροφορίες του εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | options | [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) | Οι επιλογές πληροφοριών προβολής. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Διακριτικό ακύρωσης για την ακύρωση της λειτουργίας. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - Information about the view and document specific information.

### getAttachments() {#getAttachments--}
```
public final List<Attachment> getAttachments()
```


Επιστρέφει τα συνημμένα που περιέχονται στο έγγραφο.
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - συνημμένα που περιέχονται στο έγγραφο.

### getAttachments(CancellationToken cancellationToken) {#getAttachments-com.groupdocs.viewer.utils.CancellationToken-}
```
public final List<Attachment> getAttachments(CancellationToken cancellationToken)
```


Επιστρέφει τα συνημμένα που περιέχονται στο έγγραφο.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Διακριτικό ακύρωσης για την ακύρωση της λειτουργίας. |
|

**Returns:**
java.util.List<com.groupdocs.viewer.results.Attachment> - συνημμένα που περιέχονται στο έγγραφο.

### saveAttachment(Attachment attachment, OutputStream destination) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-}
```
public void saveAttachment(Attachment attachment, OutputStream destination)
```


Αποθηκεύει ένα αρχείο συνημμένου στη ροή προορισμού.
***Learn more:**
* Learn more about getting document attachments in Java: [How to get a list of document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Get+attachments)
* Learn more about saving document attachments in Java: [How to save document attachments using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Save+attachments)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | Το συνημμένο. |
|
|  | προορισμός | java.io.OutputStream | Η εγγράψιμη ροή. |
|

### saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken) {#saveAttachment-com.groupdocs.viewer.results.Attachment-java.io.OutputStream-com.groupdocs.viewer.utils.CancellationToken-}
```
public void saveAttachment(Attachment attachment, OutputStream destination, CancellationToken cancellationToken)
```


Αποθηκεύει ένα αρχείο συνημμένου στη ροή προορισμού.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | attachment | [Attachment](../../com.groupdocs.viewer.results/attachment) | Το συνημμένο. |
|
|  | προορισμός | java.io.OutputStream | Η εγγράψιμη ροή. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Διακριτικό ακύρωσης για την ακύρωση της λειτουργίας. |
|

### view(ViewOptions options) {#view-com.groupdocs.viewer.options.ViewOptions-}
```
public final void view(ViewOptions options)
```


Δημιουργεί μια προβολή όλων των σελίδων του εγγράφου.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Οι επιλογές προβολής. |
|

### view(ViewOptions options, CancellationToken cancellationToken) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken)
```


Δημιουργεί μια προβολή όλων των σελίδων του εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Οι επιλογές προβολής. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Διακριτικό ακύρωσης για την ακύρωση της διαδικασίας απόδοσης. |
|

### view(ViewOptions options, int pageNumber) {#view-com.groupdocs.viewer.options.ViewOptions-int-}
```
public final void view(ViewOptions options, int pageNumber)
```


Δημιουργεί μια προβολή συγκεκριμένης σελίδας του εγγράφου.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Οι επιλογές προβολής. |
|
|  | pageNumber | int | Ο αριθμός σελίδας για προβολή. |
|

### view(ViewOptions options, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-int...-}
```
public final void view(ViewOptions options, int[] pageNumbers)
```


Δημιουργεί μια προβολή συγκεκριμένων σελίδων του εγγράφου.
***Learn more**
* Learn more about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](../https://docs.groupdocs.com/display/viewerjava/Viewing)*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Οι επιλογές προβολής. |
|
|  | pageNumbers | int[] | Οι αριθμοί σελίδων για προβολή. |
|

### view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers) {#view-com.groupdocs.viewer.options.ViewOptions-com.groupdocs.viewer.utils.CancellationToken-int...-}
```
public final void view(ViewOptions options, CancellationToken cancellationToken, int[] pageNumbers)
```


Δημιουργεί μια προβολή συγκεκριμένων σελίδων του εγγράφου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | options | [ViewOptions](../../com.groupdocs.viewer.options/viewoptions) | Οι επιλογές προβολής. |
|
|  | cancellationToken | [CancellationToken](../../com.groupdocs.viewer.utils/cancellationtoken) | Διακριτικό ακύρωσης για την ακύρωση της διαδικασίας απόδοσης. |
|
|  | pageNumbers | int[] | Οι αριθμοί σελίδων για προβολή. |
|

### getAllFonts() {#getAllFonts--}
```
public IFontInfo[] getAllFonts()
```


Επιστρέφει όλες τις γραμματοσειρές που χρησιμοποιούνται στα φορτωμένα έγγραφα, συμπεριλαμβανομένων των ενσωματωμένων στο ίδιο το έγγραφο και των γραμματοσειρών συστήματος που είναι εγκατεστημένες στο λειτουργικό σύστημα και χρησιμοποιούνται στο έγγραφο.

Για λεπτομέρειες, δείτε το
[documentation](../https://docs.groupdocs.com/viewer/net/getting-used-fonts/).


**Returns:**
com.groupdocs.viewer.fonts.IFontInfo[] - Μη-μηδενική λίστα όλων των γραμματοσειρών που χρησιμοποιούνται στο έγγραφο που φορτώθηκε σε αυτήν την παρουσία του [Viewer](../../com.groupdocs.viewer/viewer).

### search(SearchHighlightOptions options) {#search-com.groupdocs.viewer.options.SearchHighlightOptions-}
```
public void search(SearchHighlightOptions options)
```


Πραγματοποιεί αναζήτηση κειμένου και επισημαίνει τις αντιστοιχίες (αν βρεθούν) στο φορτωμένο έγγραφο σύμφωνα με τις παρεχόμενες επιλογές.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | επιλογές | com.groupdocs.viewer.options.SearchHighlightOptions | Επιλογές αναζήτησης και επισήμανσης, συμπεριλαμβανομένης μιας φράσης κειμένου για αναζήτηση. Δεν μπορεί να είναι null. |
|

### getFileInfo() {#getFileInfo--}
```
public FileInfo getFileInfo()
```


Επιστρέφει πληροφορίες σχετικά με το αρχείο, όπως τον τύπο του αρχείου και μια σημαία που υποδεικνύει αν το αρχείο είναι κρυπτογραφημένο.
***Learn more:**
* Learn more about how to check if a file is encrypted: [How to check if a file is encrypted](../https://docs.groupdocs.com/viewer/net/how-to-check-if-file-is-encrypted/)*


**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - the file information.

### close() {#close--}
```
public final void close()
```


Απελευθερώνει τη ροή αρχείου και τους διαχειριζόμενους εσωτερικούς πόρους.


