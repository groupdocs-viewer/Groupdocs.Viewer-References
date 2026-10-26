---
title: "Security"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Παρέχει επιλογές ασφαλείας για έγγραφα PDF."
type: docs
weight: 29
url: /el/nodejs-java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

Παρέχει επιλογές ασφαλείας για έγγραφα PDF.

Η κλάση Security περιλαμβάνει διάφορες ρυθμίσεις και επιλογές που μπορούν να χρησιμοποιηθούν για την εφαρμογή μέτρων ασφαλείας σε ένα έγγραφο PDF στο στοιχείο GroupDocs.Viewer. Αυτές οι επιλογές περιλαμβάνουν προστασία με κωδικό, δικαιώματα και άλλα. Για λεπτομέρειες, δείτε το [τεκμηρίωση][].

Παράδειγμα χρήσης:

```

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [Security()](#Security--) | Αρχικοποιεί μια νέα παρουσία της κλάσης  Security  . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDocumentOpenPassword()](#getDocumentOpenPassword--) | Λαμβάνει τον κωδικό πρόσβασης που απαιτείται για το άνοιγμα του εγγράφου PDF. |
| [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | Ορίζει τον κωδικό πρόσβασης που απαιτείται για το άνοιγμα του εγγράφου PDF. |
| [getPermissionsPassword()](#getPermissionsPassword--) | Λαμβάνει τον κωδικό πρόσβασης που απαιτείται για την αλλαγή των ρυθμίσεων δικαιωμάτων. |
| [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | Ορίζει τον κωδικό πρόσβασης που απαιτείται για την αλλαγή των ρυθμίσεων δικαιωμάτων. |
| [getPermissions()](#getPermissions--) | Λαμβάνει τα δικαιώματα του εγγράφου PDF, όπως εκτύπωση, τροποποίηση και εξαγωγή δεδομένων. |
| [setPermissions(int value)](#setPermissions-int-) | Ορίζει τα δικαιώματα του εγγράφου PDF, όπως εκτύπωση, τροποποίηση και εξαγωγή δεδομένων. |
### Security() {#Security--}
```
public Security()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης  Security  .

### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


Λαμβάνει τον κωδικό πρόσβασης που απαιτείται για το άνοιγμα του εγγράφου PDF.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - ο κωδικός πρόσβασης ανοίγματος του εγγράφου.
### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


Ορίζει τον κωδικό πρόσβασης που απαιτείται για το άνοιγμα του εγγράφου PDF.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String | Ο κωδικός πρόσβασης ανοίγματος του εγγράφου. |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


Λαμβάνει τον κωδικό πρόσβασης που απαιτείται για την αλλαγή των ρυθμίσεων δικαιωμάτων.

Χρησιμοποιώντας έναν κωδικό δικαιωμάτων, μπορείτε να περιορίσετε την εκτύπωση, την τροποποίηση και την εξαγωγή δεδομένων. Χρησιμοποιήστε έναν κωδικό δικαιωμάτων για να περιορίσετε την εκτύπωση, την τροποποίηση και την εξαγωγή δεδομένων. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - ο κωδικός δικαιωμάτων.
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


Ορίζει τον κωδικό πρόσβασης που απαιτείται για την αλλαγή των ρυθμίσεων δικαιωμάτων.

Χρησιμοποιώντας έναν κωδικό δικαιωμάτων, μπορείτε να περιορίσετε την εκτύπωση, την τροποποίηση και την εξαγωγή δεδομένων. Χρησιμοποιήστε έναν κωδικό δικαιωμάτων για να περιορίσετε την εκτύπωση, την τροποποίηση και την εξαγωγή δεδομένων. Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.lang.String | Ο κωδικός δικαιωμάτων. |

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


Λαμβάνει τα δικαιώματα του εγγράφου PDF, όπως εκτύπωση, τροποποίηση και εξαγωγή δεδομένων.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
int - τα δικαιώματα του εγγράφου PDF.
### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


Ορίζει τα δικαιώματα του εγγράφου PDF, όπως εκτύπωση, τροποποίηση και εξαγωγή δεδομένων.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | int | Τα δικαιώματα του εγγράφου PDF. |

