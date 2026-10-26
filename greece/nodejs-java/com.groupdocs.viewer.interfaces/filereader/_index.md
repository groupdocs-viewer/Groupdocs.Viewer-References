---
title: "FileReader"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Δηλώνει μια διεπαφή για την ανάγνωση μιας ροής αρχείου."
type: docs
weight: 14
url: /el/nodejs-java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

Δηλώνει μια διεπαφή για την ανάγνωση μιας ροής αρχείου.

Η διεπαφή FileReader παρέχει μια μέθοδο για την ανάγνωση ενός ρεύματος αρχείου. Χρησιμοποιείται για την πρόσβαση και την ανάγνωση του περιεχομένου ενός αρχείου με διαδοχικό τρόπο. Οι υλοποιήσεις αυτής της διεπαφής πρέπει να διαχειρίζονται τις απαραίτητες λειτουργίες για την ανάγνωση δεδομένων από ένα αρχείο.

Παράδειγμα χρήσης:

```

 FileReader fileReader = new FileReader() {
     @Override
     public InputStream read() {
         // Create document stream
     }

     @Override
     public void close() {
         // Close the stream
     }
 };
 try (Viewer viewer = new Viewer(fileReader, new ViewerSettings())){
     // Process document
 }
 
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [read()](#read--) | Επιστρέφει ένα InputStream που αντιπροσωπεύει ένα αναγνώσιμο ρεύμα για το αρχείο. |
| [close()](#close--) | Καταστρέφει το αντικείμενο και απελευθερώνει τυχόν πόρους συστήματος που σχετίζονται με αυτό. |
### read() {#read--}
```
public abstract InputStream read()
```


Επιστρέφει ένα InputStream που αντιπροσωπεύει ένα αναγνώσιμο ρεύμα για το αρχείο.

**Returns:**
java.io.InputStream - το αναγνώσιμο ρεύμα InputStream.
### close() {#close--}
```
public abstract void close()
```


Καταστρέφει το αντικείμενο και απελευθερώνει τυχόν πόρους συστήματος που σχετίζονται με αυτό.

