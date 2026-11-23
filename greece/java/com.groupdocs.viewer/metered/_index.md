---
title: "Μετρημένο"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Παρέχει μεθόδους για την εφαρμογή μετρημένης άδειας στο στοιχείο GroupDocs.Viewer."
type: docs
weight: 11
url: /el/java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Παρέχει μεθόδους για την εφαρμογή μετρημένης άδειας στο στοιχείο GroupDocs.Viewer.


Η άδεια Metered σάς επιτρέπει να παρακολουθείτε και να ελέγχετε δυναμικά τη χρήση του GroupDocs.Viewer με βάση τον αριθμό των επεξεργασμένων σελίδων εγγράφου, αντί για μια παραδοσιακή άδεια ανά διακομιστή ή ανά προγραμματιστή.
Αυτό το ευέλικτο μοντέλο αδειοδότησης είναι κατάλληλο για σενάρια όπου οι απαιτήσεις επεξεργασίας εγγράφων μεταβάλλονται με την πάροδο του χρόνου ή όταν θέλετε να πληρώνετε μόνο για ό,τι χρησιμοποιείτε.


Παράδειγμα χρήσης:

````

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Metered()](#Metered--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Ανακτά την ποσότητα των επεξεργασμένων μεγαμπάιτ (MB). |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Ανακτά τον αριθμό των καταναλωμένων μονάδων (credits). |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ενεργοποιεί το προϊόν με κλειδιά Metered. |
|
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Ανακτά την ποσότητα των επεξεργασμένων μεγαμπάιτ (MB).


Αυτή η μέθοδος επιστρέφει τη συνολική ποσότητα των MB που επεξεργάστηκε το στοιχείο.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
````



**Returns:**
double - η ποσότητα των επεξεργασμένων MB.

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Ανακτά τον αριθμό των καταναλωμένων μονάδων (credits).


Αυτή η μέθοδος επιστρέφει τον συνολικό αριθμό των καταναλωμένων μονάδων (credits) από το στοιχείο.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
````



**Returns:**
double - ο αριθμός των καταναλωμένων μονάδων.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Ενεργοποιεί το προϊόν με κλειδιά Metered.


Το παρακάτω παράδειγμα δείχνει πώς να ενεργοποιήσετε το προϊόν με κλειδιά Metered.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | publicKey | java.lang.String | Το δημόσιο κλειδί. |
|
|  | privateKey | java.lang.String | Το ιδιωτικό κλειδί. |
|

