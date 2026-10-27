---
title: "ιδιότητα disable_font_license_verifications"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Η ιδιότητα απενεργοποιεί τυχόν περιορισμούς άδειας για όλες τις γραμματοσειρές στο τρέχον έγγραφο XPS/OXPS."
type: docs
url: /el/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

Η ιδιότητα απενεργοποιεί τυχόν περιορισμούς άδειας για όλες τις γραμματοσειρές στο τρέχον έγγραφο XPS/OXPS.

Πολλές λειτουργίες με γραμματοσειρές δεν μπορούν να εκτελεστούν εάν απαγορεύονται από την άδεια της γραμματοσειράς. Για παράδειγμα, ορισμένες γραμματοσειρές δεν μπορούν να ενσωματωθούν σε ένα έγγραφο PDF εάν οι κανόνες άδειας απαγορεύουν την ενσωμάτωση για αυτή τη γραμματοσειρά. Αυτή η επιλογή σας επιτρέπει να παραλείψετε την επαλήθευση αυτών των κανόνων.

Να είστε προσεκτικοί όταν χρησιμοποιείτε αυτή τη σημαία. Όταν οριστεί, σημαίνει ότι το άτομο που τη θέτει αναλαμβάνει πλήρη ευθύνη για πιθανές παραβιάσεις άδειας ή νόμου. Συνιστάται έντονα να χρησιμοποιείτε αυτή τη σημαία μόνο όταν είστε πλήρως βέβαιοι ότι δεν παραβιάζετε το νόμο περί πνευματικών δικαιωμάτων. Η προεπιλεγμένη τιμή είναι `False`.

Για παράδειγμα κώδικα, δείτε την τεκμηρίωση στη διεύθυνση https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### Δείτε επίσης
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
