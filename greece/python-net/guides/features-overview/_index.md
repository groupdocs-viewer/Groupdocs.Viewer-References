---
title: "Επισκόπηση Χαρακτηριστικών"
linkTitle: "Features overview"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αποδώστε έγγραφα σε HTML, PDF, PNG ή JPEG· εξάγετε κείμενο· καταγράψτε συνημμένα· και εφαρμόστε περιστροφές, επαναδιατάξεις και υδατογραφήματα με το GroupDocs.Viewer for Python μέσω .NET."
type: docs
url: /el/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Rendering Documents

Ο όρος *rendering* στο GroupDocs.Viewer περιγράφει τη διαδικασία μετατροπής ενός εγγράφου σε μορφή αρχείου που διατηρεί τα όρια των σελίδων. Για παράδειγμα, όταν ένα τρισελίδες αρχείο DOCX αποδίδεται σε HTML, το αποτέλεσμα είναι τρία αρχεία HTML — ένα ανά σελίδα. Δείτε τον [Developer Guide]() για παραδείγματα εκτέλεσης.

![Rendering diagram](https://docs.groupdocs.com/viewer/python-net/images/getting-started/features-overview/rendering.png)

### Rendering to HTML

Η απόδοση σε HTML είναι η καλύτερη επιλογή όταν χρειάζεται να:

- Build a web-based application and display document content inside a browser.
- Allow users to interact with the rendered text — select, copy, or search it.
- View document pages separately.
- Zoom in on a document without quality loss.
- Rotate, reorder, or watermark pages.

Το GroupDocs.Viewer for Python προσφέρει δύο τρόπους διαχείρισης πόρων HTML:

- **HTML with external resources** — stores page resources (CSS, fonts, images) next to the HTML file so common resources are reused across pages. Reduces overall page size and speeds up loading.
- **HTML with embedded resources** — inlines every resource into the HTML file so each page is self-contained. Larger individual files but easier to distribute.

### Rendering to PNG or JPEG

Η απόδοση σε PNG ή JPEG είναι η καλύτερη επιλογή όταν χρειάζεται να:

- Support any type of application (desktop, web, mobile, CLI).
- Restrict interaction with rendered text — for example, to prevent copying. You can still extract a text layer separately if you want to overlay selectable text on the image.
- View document pages separately.
- Rotate, reorder, or watermark pages.

Μια γρήγορη σύγκριση των δύο μορφών εικόνας:

- **PNG** is a lossless raster format that supports full-colour images and transparency. PNG does not expose a quality setting. It is a good choice for line drawings, text, and iconic graphics at small file sizes.
- **JPEG** is a lossy compressed format whose quality can be tuned — lowering the quality removes detail and adds noise, but the file becomes smaller. JPEG is optimal for photographs and any image with a large colour range, and is a common web choice thanks to its compression ratio.

### Rendering to PDF

Το GroupDocs.Viewer αποδίδει ένα έγγραφο σε ένα ενιαίο αρχείο PDF. Η απόδοση σε PDF είναι η καλύτερη επιλογή όταν χρειάζεται να:

- Print documents.
- Send documents via email.
- Distribute all pages as a single file rather than a collection of per-page files.

## Retrieving Document Information

Το GroupDocs.Viewer for Python εκθέτει βασικές πληροφορίες σχετικά με ένα πηγαίο έγγραφο — τύπο αρχείου, αριθμό σελίδων, κείμενο με συντεταγμένες και άλλα — χωρίς απόδοση. Δείτε το [Get Document Info]().

Πληροφορίες ειδικές για τη μορφή είναι επίσης διαθέσιμες:

- **Archive** — list of folders contained in the archive.
- **CAD** — list of layers and layouts in a CAD document.
- **Email** — list of folders contained in an Outlook data file.
- **PDF** — a flag that indicates whether document printing is allowed.
- **Project Management** — project start and end dates.

### Text extraction

Μπορείτε να επιλέξετε την εξαγωγή κειμένου εγγράφου όταν αποδίδετε σε PNG ή JPEG. Το κείμενο επιστρέφεται μαζί με συντεταγμένες ανά λέξη, κάτι που είναι χρήσιμο όταν τοποθετείτε ένα επιλέξιμο στρώμα κειμένου πάνω σε εικόνα σελίδας.

## Processing Attachments

Στο GroupDocs.Viewer, *attachments* περιλαμβάνει συνημμένα email, αρχεία ενσωματωμένα σε PDF και μεμονωμένα στοιχεία μέσα σε συμπιεσμένα αρχεία.

Με το GroupDocs.Viewer μπορείτε να καταγράψετε και να αποθηκεύσετε:

- Email attachments.
- Files embedded in PDF documents.
- Email messages contained in Outlook and Lotus Notes data files.
- Individual files inside archive containers.

Δείτε το [Processing Attachments]() για ένα εκτελέσιμο παράδειγμα.

## Output Transformation

Το GroupDocs.Viewer for Python παρέχει ένα σύνολο επιλογών για τη μετατροπή κάθε αποδοθέντος σελίδας:

- **Rotate pages** — change page orientation when rendering to HTML, JPG, PNG, or PDF.
- **Add a text watermark** — stamp a text watermark on every rendered page.
- **Reorder pages** — render pages in any order you prefer, including when rendering to PDF.

## Caching Results

Το GroupDocs.Viewer for Python υποστηρίζει caching για την επιτάχυνση επαναλαμβανόμενων αποδόσεων και τη μείωση του συνολικού φορτίου στην εφαρμογή.

Από προεπιλογή, η κρυφή μνήμη αποθηκεύεται στον τοπικό δίσκο. Το API του viewer εκθέτει επίσης διεπαφές κρυφής μνήμης που μπορούν να υλοποιηθούν για αποθήκευση τρίτων — FTP, Amazon S3, Dropbox, Google Drive, Microsoft Azure, Redis ή οποιοδήποτε άλλο backend.
