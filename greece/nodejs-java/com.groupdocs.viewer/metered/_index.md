---
title: "Metered"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Παρέχει μεθόδους για την εφαρμογή μετρημένης άδειας στο στοιχείο GroupDocs.Viewer."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Παρέχει μεθόδους για την εφαρμογή μετρημένης άδειας στο στοιχείο GroupDocs.Viewer.

Η αδειοδότηση Metered σας επιτρέπει να παρακολουθείτε και να ελέγχετε δυναμικά τη χρήση του GroupDocs.Viewer με βάση τον αριθμό των σελίδων εγγράφου που επεξεργάζονται, αντί για μια παραδοσιακή άδεια ανά διακομιστή ή ανά προγραμματιστή. Αυτό το ευέλικτο μοντέλο αδειοδότησης είναι κατάλληλο για σενάρια όπου οι απαιτήσεις επεξεργασίας εγγράφων διαφέρουν με την πάροδο του χρόνου ή όταν θέλετε να πληρώνετε μόνο για ό,τι χρησιμοποιείτε.

Παράδειγμα χρήσης:

```

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Metered()](#Metered--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Ανακτά το ποσό των megabytes (MB) που επεξεργάστηκαν. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Ανακτά τον αριθμό των καταναλωμένων credits. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ενεργοποιεί το προϊόν με Metered keys. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Ανακτά το ποσό των megabytes (MB) που επεξεργάστηκαν.

Αυτή η μέθοδος επιστρέφει το συνολικό ποσό των MB που επεξεργάστηκε το στοιχείο.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
```

**Returns:**
double - το ποσό των MB που επεξεργάστηκε.
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Ανακτά τον αριθμό των καταναλωμένων credits.

Αυτή η μέθοδος επιστρέφει τον συνολικό αριθμό των καταναλωμένων credits από το στοιχείο.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
```

**Returns:**
double - ο αριθμός των καταναλωμένων credits.
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Ενεργοποιεί το προϊόν με Metered keys.

Το παρακάτω παράδειγμα δείχνει πώς να ενεργοποιήσετε το προϊόν με Metered keys.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| publicKey | java.lang.String | Το δημόσιο κλειδί. |
| privateKey | java.lang.String | Το ιδιωτικό κλειδί. |

