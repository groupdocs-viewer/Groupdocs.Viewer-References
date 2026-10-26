---
title: "Άδεια"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Παρέχει μεθόδους για την αδειοδότηση του στοιχείου και την ενεργοποίηση της πλήρους λειτουργικότητάς του."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

Παρέχει μεθόδους για την αδειοδότηση του στοιχείου και την ενεργοποίηση της πλήρους λειτουργικότητάς του.

Η κλάση License επιτρέπει την εφαρμογή μιας έγκυρης άδειας στο στοιχείο GroupDocs.Viewer, επιτρέποντάς σας να χρησιμοποιήσετε όλες τις λειτουργίες και να αφαιρέσετε τυχόν περιορισμούς αξιολόγησης.

Παράδειγμα χρήσης:

```

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [License()](#License--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | Παρέχει άδεια στο στοιχείο. |
| [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | Παρέχει άδεια στο στοιχείο. |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | Παρέχει άδεια στο στοιχείο. |
| [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | Παρέχει άδεια στο στοιχείο. |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


Παρέχει άδεια στο στοιχείο.

Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε μια άδεια περνώντας το InputStream του αρχείου άδειας.

Για περισσότερες πληροφορίες σχετικά με τις άδειες, παρακαλούμε ανατρέξτε στο [GroupDocs Licensing FAQ][]. Μπορείτε επίσης να βρείτε λεπτομερείς πληροφορίες σχετικά με τις άδειες του GroupDocs.Viewer στην τεκμηρίωση [Evaluation Limitations and Licensing][].

**Example:**

```

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
```


[GroupDocs Licensing FAQ]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licenseStream | java.io.InputStream | Η ροή της άδειας. |

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


Παρέχει άδεια στο στοιχείο.

Ορίζει την άδεια για το στοιχείο χρησιμοποιώντας το καθορισμένο μονοπάτι άδειας.

**Note:** This method should be called before using any functionality of the component.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licensePath | java.nio.file.Path | Το μονοπάτι της άδειας. |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


Παρέχει άδεια στο στοιχείο.

Αυτή η μέθοδος πρέπει να κληθεί πριν από τη χρήση οποιασδήποτε λειτουργικότητας.

Παράδειγμα χρήσης:

```

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licensePath | java.lang.String | Το μονοπάτι ή το URL της άδειας. |

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


Παρέχει άδεια στο στοιχείο.

Αυτή η μέθοδος πρέπει να κληθεί πριν από τη χρήση οποιασδήποτε λειτουργικότητας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| licenseUri | java.net.URL | Το URI της άδειας. |

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
