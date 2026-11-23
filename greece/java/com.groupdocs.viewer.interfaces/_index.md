---
title: "com.groupdocs.viewer.interfaces"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Το πακέτο παρέχει διεπαφές για τη δημιουργία και την απελευθέρωση του τελικού εγγράφου και των πόρων του."
type: docs
weight: 17
url: /el/java/com.groupdocs.viewer.interfaces/
---

Το πακέτο παρέχει διεπαφές για τη δημιουργία και την απελευθέρωση του τελικού εγγράφου και των πόρων του.


Αυτές οι διεπαφές χρησιμοποιούνται για τη διαχείριση της δημιουργίας και της απελευθέρωσης ροών και URL που σχετίζονται με το αρχείο εξόδου, τις σελίδες και τους πόρους HTML.

Οι κύριες διεπαφές σε αυτό το πακέτο είναι:

* [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
* [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
* [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.


Για περισσότερες λεπτομέρειες σχετικά με τη χρήση αυτών των διεπαφών και την προσαρμογή του εγγράφου εξόδου και της διαχείρισης πόρων στο GroupDocs.Viewer,
Παρακαλούμε ανατρέξτε στην [GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/).



## Διεπαφές

| Διεπαφή | Περιγραφή |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | Αντιπροσωπεύει μια διεπαφή που δημιουργεί μια ροή που χρησιμοποιείται για την εγγραφή δεδομένων αρχείου εξόδου. |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | Αντιπροσωπεύει μια διεπαφή που δημιουργεί μια ροή που χρησιμοποιείται για την εγγραφή δεδομένων σελίδας εξόδου. |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | Αντιπροσωπεύει μια διεπαφή που δημιουργεί μια ροή που χρησιμοποιείται για την εγγραφή δεδομένων πόρων HTML εξόδου. |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | Αντιπροσωπεύει μια διεπαφή που δημιουργεί ένα URL για έναν πόρο HTML. |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | Δηλώνει μια διεπαφή για την ανάγνωση ροής αρχείου. |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | Ορίζει μεθόδους που απαιτούνται για τη δημιουργία και την απελευθέρωση μιας ροής αρχείου εξόδου. |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | Ορίζει τις μεθόδους που απαιτούνται για τη δημιουργία και την απελευθέρωση μιας ροής σελίδας εξόδου. |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | Απελευθερώνει μια διεπαφή που δημιουργήθηκε από τη μέθοδο που σχετίζεται με τη διεπαφή CreateFileStream. |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | Απελευθερώνει μια ροή που δημιουργήθηκε από τη μέθοδο που σχετίζεται με τη διεπαφή CreatePageStream. |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | Απελευθερώνει μια ροή που δημιουργήθηκε από τη μέθοδο που σχετίζεται με τη διεπαφή CreateResourceStream. |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Ορίζει τις μεθόδους που απαιτούνται για τη δημιουργία URL πόρου, τη δημιουργία και την απελευθέρωση μιας ροής πόρου HTML εξόδου. |
