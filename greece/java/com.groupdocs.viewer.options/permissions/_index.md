---
title: "Permissions"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Ορίζει δικαιώματα εγγράφου PDF."
type: docs
weight: 24
url: /el/java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

Ορίζει δικαιώματα εγγράφου PDF.


Η κλάση Permissions παρέχει σταθερές που αντιπροσωπεύουν διαφορετικά δικαιώματα
που μπορούν να εφαρμοστούν σε ένα PDF έγγραφο στο στοιχείο GroupDocs.Viewer.
Αυτά τα δικαιώματα ελέγχουν τις ενέργειες που μπορούν να εκτελεστούν στο PDF έγγραφο,
όπως η εκτύπωση, η αντιγραφή κειμένου, η τροποποίηση σχολίων και άλλα.


Παράδειγμα χρήσης:

````

 int permissions = Permissions.DENY_PRINTING | Permissions.DENY_MODIFICATION;
 final Security security = new Security();
 security.setPermissions(permissions);
 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Permissions()](#Permissions--) |  |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
|  | [ALLOW_ALL](#ALLOW-ALL) | Να επιτρέπεται η εκτύπωση, η τροποποίηση και η εξαγωγή δεδομένων. |
|
|  | [DENY_PRINTING](#DENY-PRINTING) | Απαγορεύεται η εκτύπωση. |
|
|  | [DENY_MODIFICATION](#DENY-MODIFICATION) | Απαγορεύεται η τροποποίηση περιεχομένου, η συμπλήρωση φορμών, η προσθήκη ή η τροποποίηση σχολίων. |
|
|  | [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | Απαγορεύεται η εξαγωγή κειμένου και γραφικών. |
|
|  | [DENY_ALL](#DENY-ALL) | Απαγορεύεται η εκτύπωση, η τροποποίηση και η εξαγωγή δεδομένων. |
|
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


Να επιτρέπεται η εκτύπωση, η τροποποίηση και η εξαγωγή δεδομένων.


### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


Απαγορεύεται η εκτύπωση.


### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


Απαγορεύεται η τροποποίηση περιεχομένου, η συμπλήρωση φορμών, η προσθήκη ή η τροποποίηση σχολίων.


### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


Απαγορεύεται η εξαγωγή κειμένου και γραφικών.


### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


Απαγορεύεται η εκτύπωση, η τροποποίηση και η εξαγωγή δεδομένων.


