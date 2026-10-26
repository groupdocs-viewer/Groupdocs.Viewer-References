---
title: "FileType"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Αναπαριστά τον τύπο αρχείου."
type: docs
weight: 14
url: /el/nodejs-java/com.groupdocs.viewer/filetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, com.groupdocs.viewer.caching.Cacheable
```
public enum FileType extends Enum<FileType> implements System.IEquatable<FileType>, Cacheable
```

Αναπαριστά τον τύπο αρχείου. Παρέχει μεθόδους για την απόκτηση λίστας όλων των τύπων αρχείων που υποστηρίζονται από το στοιχείο GroupDocs.Viewer.

Το enum FileType παρέχει σταθερές που αντιπροσωπεύουν διαφορετικούς τύπους αρχείων που υποστηρίζονται από το στοιχείο GroupDocs.Viewer. Μπορείτε να χρησιμοποιήσετε τις μεθόδους σε αυτό το enum για να λάβετε μια λίστα όλων των υποστηριζόμενων τύπων αρχείων ή να ελέγξετε αν ένας συγκεκριμένος τύπος αρχείου υποστηρίζεται.

Παράδειγμα χρήσης:

```

 // Try to detect file type using stream
 final FileType fileTypeFromStream = FileType.fromStream(new FileInputStream("document.pdf"));
 // Detect file type by extension
 final FileType fileTypeFromExtension = FileType.fromExtension(".png");
 // Iterate all supported file types
 for (FileType supportedFileType : FileType.getSupportedFileTypes()) {
     System.out.println("File type: " + supportedFileType);
 }
 final LoadOptions loadOptions = new LoadOptions(fileTypeFromExtension);
 // Usage of loadOptions
 
```
## Fields

| Field | Περιγραφή |
| --- | --- |
| [UNKNOWN](#UNKNOWN) | Αναπαριστά έναν άγνωστο τύπο αρχείου. |
| [ZIP](#ZIP) | Αναπαριστά ένα συμπιεσμένο αρχείο (.zip) που μπορεί να περιέχει ένα ή περισσότερα αρχεία ή καταλόγους. |
| [TAR](#TAR) | Αναπαριστά ένα ενοποιημένο αρχείο αρχείου Unix (.tar) που δημιουργείται για τη συλλογή ενός ή περισσότερων αρχείων. |
| [XZ](#XZ) | Αναπαριστά ένα αρχείο XZ (.xz) συμπιεσμένο χρησιμοποιώντας έναν αλγόριθμο συμπίεσης υψηλού λόγου βάσει του αλγορίθμου LZMA. |
| [TXZ](#TXZ) | Αναπαριστά ένα ενοποιημένο αρχείο αρχείου Unix (.txz, .tar.xz) που δημιουργείται για τη συλλογή ενός ή περισσότερων αρχείων. |
| [TARXZ](#TARXZ) | Αναπαριστά ένα ενοποιημένο αρχείο αρχείου Unix (.txz, .tar.xz) που δημιουργείται για τη συλλογή ενός ή περισσότερων αρχείων. |
| [TGZ](#TGZ) | Αναπαριστά ένα ενοποιημένο αρχείο αρχείου Unix (.tgz, .tar.gz) που δημιουργείται για τη συλλογή ενός ή περισσότερων αρχείων. |
| [TARGZ](#TARGZ) | Αναπαριστά ένα ενοποιημένο αρχείο αρχείου Unix (.tgz, .tar.gz) που δημιουργείται για τη συλλογή ενός ή περισσότερων αρχείων. |
| [BZ_2](#BZ-2) | Αναπαριστά ένα αρχείο Bzip2 (.bz2) συμπιεσμένο χρησιμοποιώντας τη μέθοδο ανοιχτού κώδικα BZIP2. |
| [RAR](#RAR) | Αναπαριστά ένα αρχείο Roshal Archive (.rar) συμπιεσμένο που δημιουργήθηκε χρησιμοποιώντας τη μέθοδο συμπίεσης RAR (WINRAR έκδοση 4). |
| [GZ](#GZ) | Αναπαριστά ένα αρχείο Gnu Zipped (.gz) συμπιεσμένο που δημιουργήθηκε με την εφαρμογή συμπίεσης gzip. |
| [GZIP](#GZIP) | Αντιπροσωπεύει ένα συμπιεσμένο αρχείο Gnu Zipped (.gzip) που εισήχθη ως δωρεάν εργαλείο για την αντικατάσταση του προγράμματος Compress που χρησιμοποιείται σε συστήματα Unix. |
| [SEVEN_ZIP](#SEVEN-ZIP) | Αντιπροσωπεύει ένα αρχείο 7Zip (.7z, .7zip), το οποίο είναι ένας δωρεάν ανοιχτού κώδικα αρχειοθέτης με συμπίεση LZMA και LZMA2. |
| [CPIO](#CPIO) | Το Cpio είναι ένα γενικό εργαλείο αρχειοθέτησης αρχείων και η σχετική του μορφή αρχείου. |
| [ZSTANDARD](#ZSTANDARD) | Το αρχείο ZST είναι ένα συμπιεσμένο αρχείο που δημιουργείται με τον αλγόριθμο συμπίεσης Zstandard (zstd). |
| [TZST](#TZST) | Τα αρχεία TZST (.tar.zst, .tzst) είναι αρχεία Zstandard (ZST), τα οποία εσωτερικά περιέχουν ένα ενοποιημένο αρχείο Unix (Tar), δημιουργημένα με εργαλείο βασισμένο σε Unix για τη συλλογή ενός ή περισσότερων αρχείων. |
| [TAR_ZST](#TAR-ZST) | Τα αρχεία TZST (.tar.zst, .tzst) είναι αρχεία Zstandard (ZST), τα οποία εσωτερικά περιέχουν ένα ενοποιημένο αρχείο Unix (Tar), δημιουργημένα με εργαλείο βασισμένο σε Unix για τη συλλογή ενός ή περισσότερων αρχείων. |
| [ISO](#ISO) | Η εικόνα οπτικού δίσκου ISO είναι ένα μη συμπιεσμένο αρχείο εικόνας δίσκου που αντιπροσωπεύει το περιεχόμενο ολόκληρων δεδομένων σε έναν οπτικό δίσκο όπως CD ή DVD, βάσει του προτύπου ISO-9660. |
| [LHA](#LHA) | Το LHA ή LZH είναι ένα δωρεάν εργαλείο συμπίεσης και η σχετική μορφή αρχείου. |
| [CAB](#CAB) | Το Cabinet (ή CAB) είναι μια μορφή αρχείου αρχειοθέτησης για τα Microsoft Windows. |
| [DXF](#DXF) | Αντιπροσωπεύει ένα αρχείο Drawing Exchange Format (.dxf), το οποίο είναι μια ετικετοποιημένη αναπαράσταση δεδομένων ενός αρχείου σχεδίασης AutoCAD. |
| [DWG](#DWG) | Αντιπροσωπεύει ένα αρχείο AutoCAD Drawing Database (.dwg), το οποίο αντιπροσωπεύει ιδιόκτητα δυαδικά αρχεία που χρησιμοποιούνται για την αποθήκευση δεδομένων σχεδίασης 2D και 3D. |
| [DWT](#DWT) | Αντιπροσωπεύει ένα πρότυπο σχεδίασης AutoCAD (.dwt), το οποίο είναι ένα αρχείο προτύπου σχεδίασης AutoCAD που χρησιμοποιείται ως εκκίνηση για τη δημιουργία σχεδίων που μπορούν να αποθηκευτούν ως αρχεία DWG. |
| [STL](#STL) | Αντιπροσωπεύει ένα αρχείο Stereolithography (.stl), το οποίο είναι μια εναλλάξιμη μορφή αρχείου που αντιπροσωπεύει γεωμετρία επιφάνειας τριών διαστάσεων. |
| [IFC](#IFC) | Αντιπροσωπεύει ένα αρχείο Industry Foundation Classes (.ifc), το οποίο είναι μια μορφή αρχείου που καθιερώνει διεθνή πρότυπα για την εισαγωγή και εξαγωγή αντικειμένων κτιρίων και των ιδιοτήτων τους. |
| [DWF](#DWF) | Αντιπροσωπεύει ένα αρχείο Design Web Format (.dwf), το οποίο είναι μια συμπιεσμένη μορφή αρχείου για προβολή, ανασκόπηση ή εκτύπωση σχεδίων 2D/3D. |
| [FBX](#FBX) | Αντιπροσωπεύει ένα αρχείο Autodesk FBX Interchange (FilmBoX) (.fbx), το οποίο είναι μια μορφή 3D μοντέλου. |
| [DWFX](#DWFX) | Αντιπροσωπεύει ένα αρχείο Design Web Format XPS (.dwfx), το οποίο είναι μια συμπιεσμένη μορφή για προβολή, ανασκόπηση ή εκτύπωση σχεδίων 2D/3D ως έγγραφο XPS. |
| [DGN](#DGN) | Αντιπροσωπεύει ένα αρχείο σχεδίασης MicroStation (.dgn), το οποίο είναι σχέδια που δημιουργούνται και υποστηρίζονται από εφαρμογές CAD όπως το MicroStation και το Intergraph Interactive Graphics Design System. |
| [PLT](#PLT) | Αντιπροσωπεύει ένα αρχείο PLT (HPGL) (.plt), το οποίο είναι ένα αρχείο σχεδιαστή βασισμένο σε διανύσματα που εισήχθη από την Autodesk, Inc. |
| [CF2](#CF2) | Αντιπροσωπεύει ένα αρχείο Common File Format (.cf2). |
| [OBJ](#OBJ) | Αντιπροσωπεύει ένα αρχείο Wavefront 3D Object (.obj), το οποίο είναι ένα αρχείο 3D εικόνας που εισήχθη από την Wavefront Technologies. |
| [HPG](#HPG) | Αντιπροσωπεύει ένα αρχείο PLT (HPGL) (.hpg). |
| [IGS](#IGS) | Αντιπροσωπεύει ένα αρχείο Initial Graphics Exchange Specification (IGES) (.igs). |
| [VSD](#VSD) | Αντιπροσωπεύει ένα αρχείο Visio Drawing (.vsd), το οποίο είναι σχέδια που δημιουργούνται με την εφαρμογή Microsoft Visio για την αναπαράσταση διαφόρων γραφικών αντικειμένων και των συνδέσεών τους. |
| [VSDX](#VSDX) | Αντιπροσωπεύει ένα αρχείο Visio Drawing (.vsdx), το οποίο αντιπροσωπεύει τη μορφή αρχείου Microsoft Visio που εισήχθη από το Microsoft Office 2013 και μετά. |
| [VSS](#VSS) | Αντιπροσωπεύει ένα αρχείο Visio Stencil (.vss), το οποίο είναι αρχεία στενσίλ που δημιουργήθηκαν με το Microsoft Visio 2007 και παλαιότερα. |
| [VSSX](#VSSX) | Αντιπροσωπεύει ένα αρχείο Visio Stencil (.vssx), το οποίο είναι πρότυπα σχεδίασης που δημιουργήθηκαν με το Microsoft Visio 2013 και νεότερα. |
| [VSDM](#VSDM) | Αντιπροσωπεύει ένα σχέδιο Visio με δυνατότητα μακροεντολών (.vsdm), το οποίο είναι αρχεία σχεδίασης που δημιουργήθηκαν με την εφαρμογή Microsoft Visio και υποστηρίζουν μακροεντολές. |
| [VST](#VST) | Αντιπροσωπεύει ένα πρότυπο σχεδίου Visio (.vst), το οποίο είναι αρχεία διανυσματικών εικόνων που δημιουργήθηκαν με το Microsoft Visio. |
| [VSTX](#VSTX) | Αντιπροσωπεύει ένα πρότυπο σχεδίου Visio (.vstx), το οποίο είναι αρχεία προτύπων σχεδίου που δημιουργήθηκαν με το Microsoft Visio 2013 και νεότερα. |
| [VSTM](#VSTM) | Αντιπροσωπεύει ένα πρότυπο σχεδίου Visio με δυνατότητα μακροεντολών (.vstm), το οποίο είναι αρχεία προτύπων που δημιουργήθηκαν με το Microsoft Visio και υποστηρίζουν μακροεντολές. |
| [VSSM](#VSSM) | Αντιπροσωπεύει ένα αρχείο Stencil Visio με δυνατότητα μακροεντολών (.vssm), το οποίο είναι αρχεία Stencil του Microsoft Visio που υποστηρίζουν μακροεντολές. |
| [VSX](#VSX) | Αντιπροσωπεύει ένα αρχείο Visio Stencil XML (.vsx), το οποίο αναφέρεται σε stencils που αποτελούνται από σχέδια και σχήματα που χρησιμοποιούνται για τη δημιουργία διαγραμμάτων στο Microsoft Visio. |
| [VTX](#VTX) | Αντιπροσωπεύει ένα αρχείο Visio Template XML (.vtx), το οποίο είναι ένα πρότυπο σχεδίου Microsoft Visio που αποθηκεύεται στο δίσκο σε μορφή αρχείου XML. |
| [VDW](#VDW) | Αντιπροσωπεύει ένα σχέδιο Visio Web (.vdw), το οποίο καθορίζει τις ροές και τις αποθηκεύσεις που απαιτούνται για την απόδοση ενός web σχεδίου. |
| [VDX](#VDX) | Αντιπροσωπεύει ένα αρχείο Visio Drawing XML (.vdx), το οποίο αντιπροσωπεύει οποιοδήποτε σχέδιο ή διάγραμμα που δημιουργήθηκε στο Microsoft Visio αλλά αποθηκεύτηκε σε μορφή XML με την επέκταση .VDX. |
| [EPUB](#EPUB) | Αντιπροσωπεύει ένα αρχείο Open eBook (.epub), το οποίο είναι μια μορφή αρχείου e‑book που παρέχει ένα τυπικό ψηφιακό μορφότυπο δημοσίευσης για εκδότες και καταναλωτές. |
| [MOBI](#MOBI) | Αντιπροσωπεύει ένα eBook Mobipocket (.mobi), το οποίο είναι μία από τις πιο διαδεδομένες μορφές αρχείων ebook. |
| [AZW_3](#AZW-3) | Το ebook Amazon Kindle Format 8 (KF8) είναι η ψηφιακή μορφή αρχείου που αναπτύχθηκε για τις συσκευές Amazon Kindle. |
| [MSG](#MSG) | Αντιπροσωπεύει ένα μήνυμα αλληλογραφίας Outlook (.msg), το οποίο είναι μια μορφή αρχείου που χρησιμοποιείται από το Microsoft Outlook και το Exchange για την αποθήκευση μηνυμάτων email, επαφών, ραντεβού ή άλλων εργασιών. |
| [EML](#EML) | Αντιπροσωπεύει ένα μήνυμα ηλεκτρονικού ταχυδρομείου (.eml), το οποίο αντιπροσωπεύει μηνύματα email που αποθηκεύονται χρησιμοποιώντας το Outlook και άλλες σχετικές εφαρμογές. |
| [EMLX](#EMLX) | Αντιπροσωπεύει ένα μήνυμα Apple Mail (.emlx), το οποίο υλοποιείται και αναπτύσσεται από την Apple. |
| [PST](#PST) | Αντιπροσωπεύει ένα αρχείο Outlook Personal Information Store (.pst), το οποίο αντιπροσωπεύει τα Outlook Personal Storage Files (επίσης γνωστά ως Personal Storage Table) που αποθηκεύουν μια ποικιλία πληροφοριών χρήστη. |
| [OST](#OST) | Αντιπροσωπεύει ένα αρχείο Outlook Offline Data (.ost), το οποίο αντιπροσωπεύει τα δεδομένα του γραμματοκιβωτίου ενός χρήστη σε λειτουργία εκτός σύνδεσης σε τοπικό υπολογιστή μετά την εγγραφή σε Exchange Server χρησιμοποιώντας το Microsoft Outlook. |
| [TIF](#TIF) | Αντιπροσωπεύει ένα αρχείο Tagged Image (.tif), το οποίο αντιπροσωπεύει εικόνες raster που προορίζονται για χρήση σε διάφορες συσκευές που συμμορφώνονται με αυτό το πρότυπο μορφής αρχείου. |
| [TIFF](#TIFF) | Αντιπροσωπεύει ένα αρχείο Tagged Image File Format (.tiff), το οποίο αντιπροσωπεύει εικόνες raster που προορίζονται για χρήση σε διάφορες συσκευές που συμμορφώνονται με αυτό το πρότυπο μορφής αρχείου. |
| [JPG](#JPG) | Αντιπροσωπεύει μια εικόνα JPEG (.jpg), η οποία είναι ένας τύπος μορφής εικόνας που αποθηκεύεται χρησιμοποιώντας τη μέθοδο της απωλεστικής συμπίεσης. |
| [JPEG](#JPEG) | Αντιπροσωπεύει μια εικόνα JPEG (.jpeg), η οποία είναι ένας τύπος μορφής εικόνας που αποθηκεύεται χρησιμοποιώντας τη μέθοδο της απωλεστικής συμπίεσης. |
| [JFIF](#JFIF) | Το JPEG File Interchange Format (.jfif) είναι μια εικόνα που αναπτύχθηκε για γρήγορη ανταλλαγή μεταξύ πλατφορμών. |
| [PNG](#PNG) | Αντιπροσωπεύει ένα Portable Network Graphic (.png), το οποίο είναι ένας τύπος μορφής raster εικόνας που χρησιμοποιεί μη απωλεστική συμπίεση. |
| [GIF](#GIF) | Αντιπροσωπεύει ένα αρχείο Graphical Interchange Format (.gif), το οποίο είναι ένας τύπος υψηλής συμπίεσης εικόνας. |
| [APNG](#APNG) | Αντιπροσωπεύει ένα Animated Portable Network Graphic (.apng), το οποίο είναι μια επέκταση της μορφής PNG που υποστηρίζει κίνηση. |
| [BMP](#BMP) | Αντιπροσωπεύει ένα αρχείο Bitmap Image (.bmp), το οποίο χρησιμοποιείται για την αποθήκευση ψηφιακών bitmap εικόνων. |
| [ICO](#ICO) | Αντιπροσωπεύει ένα αρχείο Icon (.ico), το οποίο είναι τύπος αρχείου εικόνας που χρησιμοποιείται ως εικονίδιο για την αναπαράσταση μιας εφαρμογής στα Microsoft Windows. |
| [TGA](#TGA) | Αντιπροσωπεύει ένα αρχείο Truevision TGA (TARGA), το οποίο χρησιμοποιείται για την αποθήκευση ψηφιακών bitmap εικόνων που αναπτύχθηκαν από την TRUEVISION. |
| [JP_2](#JP-2) | Αντιπροσωπεύει ένα αρχείο JPEG 2000 Core Image (.jp2), το οποίο είναι σύστημα κωδικοποίησης εικόνας και σύγχρονο πρότυπο συμπίεσης εικόνας. |
| [JPF](#JPF) | Αντιπροσωπεύει ένα αρχείο JPEG 2000 Image (.jpf). |
| [JPX](#JPX) | Αντιπροσωπεύει ένα αρχείο JPEG 2000 Image (.jpx). |
| [JPM](#JPM) | Αντιπροσωπεύει ένα αρχείο JPEG 2000 Image (.jpm). |
| [J2C](#J2C) | Αντιπροσωπεύει ένα JPEG 2000 Code InputStream (.j2c). |
| [J2K](#J2K) | Αντιπροσωπεύει ένα JPEG 2000 Code Stream (.j2k), το οποίο είναι μια εικόνα συμπιεσμένη με χρήση κυματικής συμπίεσης αντί για συμπίεση DCT. |
| [JPC](#JPC) | Αντιπροσωπεύει ένα JPEG 2000 Code Stream (.jpc). |
| [JLS](#JLS) | Αντιπροσωπεύει ένα αρχείο JPEG-LS (JLS) (.jls). |
| [DIB](#DIB) | Αντιπροσωπεύει ένα αρχείο Device Independent Bitmap (.dib). |
| [WMF](#WMF) | Αντιπροσωπεύει ένα Windows Metafile (.wmf), το οποίο αντιπροσωπεύει το Microsoft Windows Metafile (WMF) για την αποθήκευση δεδομένων εικόνας σε διανυσματική καθώς και bitmap μορφή. |
| [WMZ](#WMZ) | Αντιπροσωπεύει ένα Compressed Windows Metafile (.wmz), το οποίο αντιπροσωπεύει το Microsoft Windows Metafile (WMF) συμπιεσμένο σε αρχείο GZIP για την αποθήκευση δεδομένων εικόνας σε διανυσματική καθώς και bitmap μορφή. |
| [EMF](#EMF) | Αντιπροσωπεύει ένα Enhanced Windows Metafile (.emf), το οποίο αντιπροσωπεύει γραφικές εικόνες ανεξάρτητα από τη συσκευή. |
| [EMZ](#EMZ) | Αντιπροσωπεύει ένα Windows Compressed Enhanced Metafile (.emz), το οποίο αντιπροσωπεύει γραφικές εικόνες ανεξάρτητα από τη συσκευή, συμπιεσμένες με GZIP. |
| [WEBP](#WEBP) | Αντιπροσωπεύει ένα WebP Image (.webp), το οποίο είναι μια σύγχρονη μορφή αρχείου raster εικόνας web βασισμένη σε μη απωλεστική και απωλεστική συμπίεση. |
| [DNG](#DNG) | Αντιπροσωπεύει μια Digital Negative Specification (.dng), η οποία είναι μορφή εικόνας ψηφιακής κάμερας που χρησιμοποιείται για την αποθήκευση ακατέργαστων αρχείων. |
| [CDR](#CDR) | Αντιπροσωπεύει ένα CorelDraw Vector Graphic Drawing (.cdr), το οποίο είναι αρχείο εικόνας διανυσματικού σχεδίου που δημιουργείται εγγενώς με το CorelDRAW για την αποθήκευση ψηφιακά κωδικοποιημένων και συμπιεσμένων εικόνων. |
| [CMX](#CMX) | Αντιπροσωπεύει ένα Corel Exchange (.cmx), το οποίο είναι αρχείο εικόνας σχεδίου που μπορεί να περιέχει διανυσματικά γραφικά καθώς και bitmap γραφικά. |
| [DJVU](#DJVU) | Αντιπροσωπεύει ένα DjVu Image (.djvu), το οποίο είναι μορφή αρχείου γραφικών προορισμένη για σαρωμένα έγγραφα και βιβλία, ειδικά εκείνα που περιέχουν συνδυασμό κειμένου, σχεδίων, εικόνων και φωτογραφιών. |
| [CGM](#CGM) | Αντιπροσωπεύει ένα Computer Graphics Metafile (.cgm), το οποίο είναι ελεύθερη, ανεξάρτητη από πλατφόρμα, διεθνής πρότυπη μορφή μετααρχείου για την αποθήκευση και ανταλλαγή διανυσματικών γραφικών (2D), raster γραφικών και κειμένου. |
| [PCL](#PCL) | Αντιπροσωπεύει ένα έγγραφο Printer Command Language (.pcl). |
| [PSD](#PSD) | Αντιπροσωπεύει ένα Adobe Photoshop Document (.psd), το οποίο είναι η εγγενής μορφή αρχείου του Adobe Photoshop που χρησιμοποιείται για το σχεδιασμό και την ανάπτυξη γραφικών. |
| [PSB](#PSB) | Αντιπροσωπεύει ένα Photoshop Large Document Format (.psb), το οποίο χρησιμοποιείται για σχεδίαση γραφικών και ανάπτυξη στο Adobe Photoshop. |
| [DCM](#DCM) | Αντιπροσωπεύει μια DICOM Image (.dcm), η οποία αντιπροσωπεύει μια ψηφιακή εικόνα που αποθηκεύει ιατρικές πληροφορίες ασθενών όπως MRI, αξονικές τομογραφίες (CT) και υπερηχογραφικές εικόνες. |
| [PS](#PS) | Αντιπροσωπεύει ένα PostScript File (.ps). |
| [EPS](#EPS) | Αντιπροσωπεύει ένα Encapsulated PostScript File (.eps), το οποίο περιγράφει ένα πρόγραμμα γλώσσας Encapsulated PostScript που ορίζει την εμφάνιση μιας μόνο σελίδας. |
| [ODG](#ODG) | Αντιπροσωπεύει ένα OpenDocument Graphic File (.odg), το οποίο χρησιμοποιείται από την εφαρμογή Draw του Apache OpenOffice για την αποθήκευση στοιχείων σχεδίασης ως διανυσματική εικόνα. |
| [FODG](#FODG) | Αντιπροσωπεύει ένα Flat XML ODF Template (.fodg), το οποίο χρησιμοποιείται από την εφαρμογή Draw του Apache OpenOffice για την αποθήκευση στοιχείων σχεδίασης ως διανυσματική εικόνα. |
| [SVG](#SVG) | Αντιπροσωπεύει ένα Scalable Vector Graphics File (.svg), το οποίο είναι ένα Scalar Vector Graphics αρχείο που χρησιμοποιεί μορφή κειμένου βασισμένη σε XML για την περιγραφή της εμφάνισης μιας εικόνας. |
| [SVGZ](#SVGZ) | Αντιπροσωπεύει ένα Compressed Scalable Vector Graphics File (.svgz), το οποίο είναι ένα Scalar Vector Graphics αρχείο που χρησιμοποιεί μορφή κειμένου βασισμένη σε XML, συμπιεσμένο με GZIP, για την περιγραφή της εμφάνισης μιας εικόνας. |
| [OTG](#OTG) | Αντιπροσωπεύει ένα OpenDocument Graphic Template (.otg). |
| [HTM](#HTM) | Αντιπροσωπεύει ένα Hypertext Markup Language File (.htm), το οποίο είναι η επέκταση για ιστοσελίδες που δημιουργούνται για προβολή σε προγράμματα περιήγησης. |
| [HTML](#HTML) | Αντιπροσωπεύει ένα Hypertext Markup Language File (.html), το οποίο είναι η επέκταση για ιστοσελίδες που δημιουργούνται για προβολή σε προγράμματα περιήγησης. |
| [MHT](#MHT) | Αντιπροσωπεύει ένα MHTML Web Archive (.mht). |
| [NSF](#NSF) | Αντιπροσωπεύει μια Lotus Notes Database (.nsf). |
| [MBOX](#MBOX) | Αντιπροσωπεύει ένα Email Mailbox File (.mbox). |
| [MHTML](#MHTML) | Αντιπροσωπεύει ένα MIME HTML File (.mhtml). |
| [XML](#XML) | Αντιπροσωπεύει ένα XML File (.xml). |
| [ONE](#ONE) | Αντιπροσωπεύει ένα OneNote Document (.one) που δημιουργήθηκε από την εφαρμογή Microsoft OneNote. |
| [PDF](#PDF) | Αντιπροσωπεύει ένα Portable Document Format File (.pdf), το οποίο είναι ένας τύπος εγγράφου που δημιουργήθηκε από την Adobe τη δεκαετία του 1990. |
| [XPS](#XPS) | Αντιπροσωπεύει ένα XML Paper Specification File (.xps), το οποίο αντιπροσωπεύει αρχεία διάταξης σελίδων βασισμένα στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. |
| [OXPS](#OXPS) | Αντιπροσωπεύει ένα OpenXPS File (.oxps). |
| [TEX](#TEX) | Αντιπροσωπεύει ένα LaTeX Source Document (.tex), το οποίο είναι μια γλώσσα που περιλαμβάνει προγραμματισμό καθώς και χαρακτηριστικά σήμανσης που χρησιμοποιούνται για τη στοιχειοθέτηση εγγράφων. |
| [PPT](#PPT) | Αντιπροσωπεύει ένα PowerPoint Presentation (.ppt), το οποίο αντιπροσωπεύει ένα αρχείο PowerPoint που αποτελείται από μια συλλογή διαφανειών για προβολή ως παρουσίαση. |
| [PPTX](#PPTX) | Αντιπροσωπεύει ένα PowerPoint Open XML Presentation (.pptx), τα οποία είναι αρχεία παρουσίασης που δημιουργήθηκαν με τη δημοφιλή εφαρμογή Microsoft PowerPoint. |
| [PPS](#PPS) | Αντιπροσωπεύει ένα PowerPoint Slide Show (.pps), το οποίο δημιουργείται χρησιμοποιώντας το Microsoft PowerPoint για σκοπούς παρουσίασης διαφανειών. |
| [PPSX](#PPSX) | Αντιπροσωπεύει ένα PowerPoint Open XML Slide Show (.ppsx) files, τα οποία δημιουργούνται χρησιμοποιώντας το Microsoft PowerPoint 2007 και νεότερες εκδόσεις για σκοπούς παρουσίασης διαφανειών. |
| [ODP](#ODP) | Αντιπροσωπεύει ένα OpenDocument Presentation (.odp), το οποίο αντιπροσωπεύει μια μορφή αρχείου παρουσίασης που χρησιμοποιείται από το OpenOffice.org στο πρότυπο OASISOpen. |
| [FODP](#FODP) | Αντιπροσωπεύει ένα OpenDocument Presentation (.fodp), το οποίο αντιπροσωπεύει το OpenDocument Flat XML Presentation. |
| [POT](#POT) | Αντιπροσωπεύει ένα PowerPoint Template (.pot), το οποίο αντιπροσωπεύει αρχεία προτύπων Microsoft PowerPoint που δημιουργήθηκαν από τις εκδόσεις PowerPoint 97-2003. |
| [PPTM](#PPTM) | Αντιπροσωπεύει ένα PowerPoint Open XML Macro-Enabled Presentation (.pptm), που είναι αρχεία παρουσίασης με ενεργοποιημένες μακροεντολές, δημιουργημένα με το Microsoft PowerPoint 2007 ή νεότερες εκδόσεις. |
| [POTX](#POTX) | Αντιπροσωπεύει ένα PowerPoint Open XML Presentation Template (.potx), το οποίο αντιπροσωπεύει προτύπους παρουσιάσεων Microsoft PowerPoint που δημιουργήθηκαν με το Microsoft PowerPoint 2007 και μεταγενέστερες εκδόσεις. |
| [POTM](#POTM) | Αντιπροσωπεύει ένα PowerPoint Open XML Macro-Enabled Presentation Template (.potm), που είναι αρχεία προτύπων Microsoft PowerPoint με υποστήριξη μακροεντολών. |
| [PPSM](#PPSM) | Αντιπροσωπεύει ένα PowerPoint Open XML Macro-Enabled Slide (.ppsm), το οποίο αντιπροσωπεύει μια μορφή αρχείου παρουσίασης διαφανειών με ενεργοποιημένες μακροεντολές, δημιουργημένη με το Microsoft PowerPoint 2007 ή νεότερο. |
| [OTP](#OTP) | Αντιπροσωπεύει ένα OpenDocument Presentation Template (.otp), το οποίο αντιπροσωπεύει αρχεία προτύπων παρουσίασης που δημιουργούνται από εφαρμογές σύμφωνα με το πρότυπο μορφής OASIS OpenDocument. |
| [XLS](#XLS) | Αντιπροσωπεύει ένα Excel Spreadsheet (.xls), το οποίο αντιπροσωπεύει τη μορφή αρχείου Excel Binary. |
| [EXCEL_2003_XML](#EXCEL-2003-XML) | Αντιπροσωπεύει ένα Excel 2003 XML (SpreadsheetML) (.xml), το οποίο αντιπροσωπεύει τη μορφή αρχείου Excel Binary. |
| [NUMBERS](#NUMBERS) | Αντιπροσωπεύει το Apple Numbers (.numbers), το οποίο αντιπροσωπεύει μια μορφή αρχείου δυαδικού τύπου παρόμοια με το Excel. |
| [XLSX](#XLSX) | Αντιπροσωπεύει ένα Microsoft Excel Open XML Spreadsheet (.xlsx), το οποίο είναι μια γνωστή μορφή για έγγραφα Microsoft Excel που εισήχθη από τη Microsoft με την κυκλοφορία του Microsoft Office 2007. |
| [XLSM](#XLSM) | Αντιπροσωπεύει ένα Excel Open XML Macro-Enabled Spreadsheet (.xlsm), το οποίο είναι ένας τύπος αρχείου λογιστικού φύλλου που υποστηρίζει μακροεντολές. |
| [XLSB](#XLSB) | Αντιπροσωπεύει ένα Excel Binary Spreadsheet (.xlsb), το οποίο ορίζει τη μορφή αρχείου Excel Binary. |
| [CSV](#CSV) | Αντιπροσωπεύει ένα Comma Separated Values File (.csv), το οποίο αντιπροσωπεύει αρχεία απλού κειμένου που περιέχουν εγγραφές δεδομένων με τιμές διαχωρισμένες με κόμμα. |
| [TSV](#TSV) | Αντιπροσωπεύει ένα Tab Separated Values File (.tsv), το οποίο αντιπροσωπεύει δεδομένα διαχωρισμένα με στηλοθέτες σε μορφή απλού κειμένου. |
| [ODS](#ODS) | Αντιπροσωπεύει ένα OpenDocument Spreadsheet (.ods), το οποίο σημαίνει τη μορφή εγγράφου OpenDocument Spreadsheet που μπορεί να επεξεργαστεί από τον χρήστη. |
| [FODS](#FODS) | Αντιπροσωπεύει ένα OpenDocument Flat XML Spreadsheet (.fods). |
| [OTS](#OTS) | Αντιπροσωπεύει ένα OpenDocument Spreadsheet Template (.ots). |
| [XLAM](#XLAM) | Αντιπροσωπεύει ένα Microsoft Excel Add-in (.xlam). |
| [XLTM](#XLTM) | Αντιπροσωπεύει ένα Microsoft Excel Macro-Enabled Template (.xltm), το οποίο αντιπροσωπεύει αρχεία που δημιουργούνται από το Microsoft Excel ως πρότυπα με ενεργοποιημένες μακροεντολές. |
| [XLT](#XLT) | Αντιπροσωπεύει ένα Microsoft Excel Template (.xlt), τα οποία είναι αρχεία προτύπων που δημιουργούνται με το Microsoft Excel, μια εφαρμογή λογιστικού φύλλου που αποτελεί μέρος της σουίτας Microsoft Office. |
| [XLTX](#XLTX) | Αντιπροσωπεύει ένα Excel Open XML Spreadsheet Template (.xltx), το οποίο αντιπροσωπεύει πρότυπα Microsoft Excel βασισμένα στις προδιαγραφές μορφής αρχείου Office OpenXML. |
| [SXC](#SXC) | Αντιπροσωπεύει ένα StarOffice Calc Spreadsheet (.sxc). |
| [MPP](#MPP) | Αντιπροσωπεύει ένα Microsoft Project File (.mpp), το οποίο είναι ένα αρχείο δεδομένων Microsoft Project που αποθηκεύει πληροφορίες σχετικές με τη διαχείριση έργων με ολοκληρωμένο τρόπο. |
| [MPT](#MPT) | Αντιπροσωπεύει ένα Microsoft Project Template (.mpt), το οποίο περιέχει βασικές πληροφορίες και δομή μαζί με ρυθμίσεις εγγράφου για τη δημιουργία αρχείων .MPP. |
| [MPX](#MPX) | Αντιπροσωπεύει ένα Microsoft Project Exchange file (.mpx), το οποίο είναι μορφή αρχείου ASCII για τη μεταφορά πληροφοριών έργου μεταξύ Microsoft Project (MSP) και άλλων εφαρμογών που υποστηρίζουν τη μορφή αρχείου MPX, όπως Primavera Project Planner, Sciforma και Timerline Precision Estimating. |
| [AS](#AS) | Αντιπροσωπεύει ένα ActionScript File (.as). |
| [AS_3](#AS-3) | Αντιπροσωπεύει ένα ActionScript File (.as3). |
| [ASM](#ASM) | Αντιπροσωπεύει ένα Assembly Language Source Code File (.asm). |
| [BAT](#BAT) | Αντιπροσωπεύει ένα DOS Batch File (.bat). |
| [C](#C) | Αντιπροσωπεύει ένα C/C++ Source Code File (.c). |
| [CC](#CC) | Αντιπροσωπεύει ένα C++ Source Code File (.cc). |
| [CMAKE](#CMAKE) | Αντιπροσωπεύει ένα CMake File (.cmake). |
| [CPP](#CPP) | Αντιπροσωπεύει ένα C++ Source Code File (.cpp). |
| [CS](#CS) | Αντιπροσωπεύει ένα C\\# Source Code File (.cs), το οποίο είναι αρχείο πηγαίου κώδικα για τη γλώσσα προγραμματισμού C\\#. |
| [VB](#VB) | Αντιπροσωπεύει ένα Visual Basic Project Item File (.vb), το οποίο είναι αρχείο πηγαίου κώδικα που δημιουργήθηκε στη γλώσσα Visual Basic. |
| [CSS](#CSS) | Αντιπροσωπεύει ένα Cascading Style Sheet (.css) αρχείο. |
| [CXX](#CXX) | Αντιπροσωπεύει ένα C++ Source Code File (.cxx). |
| [DIFF](#DIFF) | Αντιπροσωπεύει ένα Patch File (.diff). |
| [ERB](#ERB) | Αντιπροσωπεύει ένα Ruby ERB Script (.erb). |
| [GROOVY](#GROOVY) | Αντιπροσωπεύει ένα Groovy Source Code File (.groovy). |
| [H](#H) | Αντιπροσωπεύει ένα C/C++/Objective-C Header File (.h). |
| [HAML](#HAML) | Αντιπροσωπεύει ένα Haml Source Code File (.haml). |
| [HH](#HH) | Αντιπροσωπεύει ένα C++ Header File (.hh). |
| [JAVA](#JAVA) | Αντιπροσωπεύει ένα Java Source Code File (.java). |
| [JS](#JS) | Αντιπροσωπεύει ένα JavaScript File (.js). |
| [JSON](#JSON) | Αντιπροσωπεύει ένα JavaScript Object Notation File (.json). |
| [LESS](#LESS) | Αντιπροσωπεύει ένα LESS Style Sheet (.less) αρχείο. |
| [LOG](#LOG) | Αντιπροσωπεύει ένα Log File (.log). |
| [M](#M) | Αντιπροσωπεύει ένα αρχείο υλοποίησης Objective‑C (.m). |
| [MAKE](#MAKE) | Αντιπροσωπεύει ένα σενάριο Makefile Xcode (.make). |
| [MD](#MD) | Αντιπροσωπεύει ένα αρχείο τεκμηρίωσης Markdown (.md). |
| [ML](#ML) | Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα ML (.ml). |
| [MM](#MM) | Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα Objective‑C++ (.mm). |
| [PHP](#PHP) | Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα PHP (.php). |
| [PL](#PL) | Αντιπροσωπεύει ένα σενάριο Perl (.pl). |
| [PROPERTIES](#PROPERTIES) | Αντιπροσωπεύει ένα αρχείο ιδιοτήτων Java (.properties). |
| [PY](#PY) | Αντιπροσωπεύει ένα σενάριο Python (.py). |
| [RB](#RB) | Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα Ruby (.rb). |
| [RST](#RST) | Αντιπροσωπεύει ένα αρχείο reStructuredText (.rst). |
| [SASS](#SASS) | Αντιπροσωπεύει ένα αρχείο Syntactically Awesome StyleSheets (.sass). |
| [SCALA](#SCALA) | Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα Scala (.scala). |
| [SCM](#SCM) | Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα Scheme (.scm). |
| [SCRIPT](#SCRIPT) | Αντιπροσωπεύει ένα γενικό αρχείο σεναρίου (.script). |
| [SH](#SH) | Αντιπροσωπεύει ένα σενάριο Bash Shell (.sh). |
| [SML](#SML) | Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα Standard ML (.sml). |
| [SQL](#SQL) | Αντιπροσωπεύει ένα αρχείο δεδομένων Structured Query Language (.sql). |
| [VIM](#VIM) | Αντιπροσωπεύει ένα αρχείο ρυθμίσεων Vim (.vim). |
| [YAML](#YAML) | Αντιπροσωπεύει ένα έγγραφο YAML (.yaml). |
| [DOC](#DOC) | Αντιπροσωπεύει ένα αρχείο εγγράφου Microsoft Word (.doc). |
| [DOCX](#DOCX) | Αντιπροσωπεύει ένα αρχείο εγγράφου Microsoft Word Open XML (.docx). |
| [CHM](#CHM) | Αντιπροσωπεύει ένα αρχείο Microsoft Compiled HTML Help (.chm). |
| [DOCM](#DOCM) | Αντιπροσωπεύει ένα αρχείο εγγράφου Word Open XML Macro‑Enabled (.docm). |
| [DOT](#DOT) | Αντιπροσωπεύει ένα αρχείο προτύπου εγγράφου Word (.dot). |
| [DOTX](#DOTX) | Αντιπροσωπεύει ένα αρχείο προτύπου εγγράφου Word Open XML (.dotx). |
| [DOTM](#DOTM) | Αντιπροσωπεύει ένα αρχείο προτύπου εγγράφου Word Open XML με δυνατότητα μακροεντολών (.dotm). |
| [RTF](#RTF) | Αντιπροσωπεύει ένα αρχείο Rich Text Format (.rtf). |
| [TXT](#TXT) | Αντιπροσωπεύει ένα αρχείο απλού κειμένου (.txt). |
| [ODT](#ODT) | Αντιπροσωπεύει ένα έγγραφο κειμένου OpenDocument (.odt). |
| [OTT](#OTT) | Αντιπροσωπεύει ένα πρότυπο εγγράφου OpenDocument (.ott). |
| [VCF](#VCF) | Αντιπροσωπεύει ένα αρχείο vCard (.vcf), το οποίο είναι ψηφιακή μορφή αρχείου για αποθήκευση πληροφοριών επαφών. |
| [AI](#AI) | Αντιπροσωπεύει ένα αρχείο Adobe Illustrator (.ai), το οποίο είναι μορφή αρχείου για σχέδια Adobe Illustrator. |
| [PSM1](#PSM1) | Αντιπροσωπεύει ένα αρχείο μονάδας σεναρίου PowerShell (.psm1). |
| [PS1](#PS1) | Αντιπροσωπεύει ένα αρχείο σεναρίου PowerShell (.ps1). |
| [PSD1](#PSD1) | Αντιπροσωπεύει ένα αρχείο δηλωτικού μονάδας σεναρίου PowerShell (.psd1). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Αντιστοιχίζει μια επέκταση αρχείου σε τύπο αρχείου. |
| [fromFilePath(String filePath)](#fromFilePath-java.lang.String-) | Εξάγει την επέκταση αρχείου από όνομα αρχείου ή διαδρομή αρχείου και την αντιστοιχίζει σε τύπο αρχείου. |
| [fromMediaType(String mediaType)](#fromMediaType-java.lang.String-) | Αντιστοιχίζει έναν τύπο μέσου αρχείου σε τύπο αρχείου. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου. |
| [fromStream(InputStream stream, String password)](#fromStream-java.io.InputStream-java.lang.String-) | Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου. |
| [fromStream(InputStream stream, ILogger logger)](#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-) | Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου. |
| [fromStream(InputStream stream, String password, ILogger logger)](#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-) | Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Ανακτά τους υποστηριζόμενους τύπους αρχείων. |
| [detectCharset(String filePath)](#detectCharset-java.lang.String-) | Προσπαθεί να εντοπίσει το σύνολο χαρακτήρων των αρχείων κειμένου [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) και [CSV](../../com.groupdocs.viewer/filetype\#CSV) με βάση τη διαδρομή. |
| [detectCharset(InputStream stream)](#detectCharset-java.io.InputStream-) | Προσπαθεί να εντοπίσει το σύνολο χαρακτήρων των αρχείων κειμένου [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) και [CSV](../../com.groupdocs.viewer/filetype\#CSV) με βάση το ρεύμα. |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει το όνομα της μορφής αρχείου, π.χ., "Microsoft Word Document". |
| [getExtension()](#getExtension--) | Λαμβάνει το επίθημα επέκτασης αρχείου (συμπεριλαμβανομένου του σημείου "."), π.χ., ".doc". |
| [toString()](#toString--) | Επιστρέφει μια αναπαράσταση σε συμβολοσειρά του τρέχοντος αντικειμένου. |
### UNKNOWN {#UNKNOWN}
```
public static final FileType UNKNOWN
```


Αναπαριστά έναν άγνωστο τύπο αρχείου.

### ZIP {#ZIP}
```
public static final FileType ZIP
```


Αντιπροσωπεύει ένα συμπιεσμένο αρχείο (.zip) που μπορεί να περιέχει ένα ή περισσότερα αρχεία ή καταλόγους. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/compression/zip

### TAR {#TAR}
```
public static final FileType TAR
```


Αντιπροσωπεύει ένα ενοποιημένο αρχείο αρχείου Unix (.tar) που δημιουργήθηκε για τη συλλογή ενός ή περισσότερων αρχείων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/compression/tar

### XZ {#XZ}
```
public static final FileType XZ
```


Αντιπροσωπεύει ένα αρχείο XZ (.xz) συμπιεσμένο με αλγόριθμο υψηλής αναλογίας συμπίεσης βασισμένο στον αλγόριθμο LZMA. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://fileinfo.com/extension/xz

### TXZ {#TXZ}
```
public static final FileType TXZ
```


Αντιπροσωπεύει ένα ενοποιημένο αρχείο αρχείου Unix (.txz, .tar.xz) που δημιουργήθηκε για τη συλλογή ενός ή περισσότερων αρχείων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://fileinfo.com/extension/txz

### TARXZ {#TARXZ}
```
public static final FileType TARXZ
```


Αντιπροσωπεύει ένα ενοποιημένο αρχείο αρχείου Unix (.txz, .tar.xz) που δημιουργήθηκε για τη συλλογή ενός ή περισσότερων αρχείων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://fileinfo.com/extension/txz

### TGZ {#TGZ}
```
public static final FileType TGZ
```


Αντιπροσωπεύει ένα ενοποιημένο αρχείο αρχείου Unix (.tgz, .tar.gz) που δημιουργήθηκε για τη συλλογή ενός ή περισσότερων αρχείων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://fileinfo.com/extension/tgz

### TARGZ {#TARGZ}
```
public static final FileType TARGZ
```


Αντιπροσωπεύει ένα ενοποιημένο αρχείο αρχείου Unix (.tgz, .tar.gz) που δημιουργήθηκε για τη συλλογή ενός ή περισσότερων αρχείων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://fileinfo.com/extension/tgz

### BZ_2 {#BZ-2}
```
public static final FileType BZ_2
```


Αντιπροσωπεύει ένα συμπιεσμένο αρχείο Bzip2 (.bz2) που δημιουργήθηκε χρησιμοποιώντας τη μέθοδο συμπίεσης ανοιχτού κώδικα BZIP2. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/compression/bz2

### RAR {#RAR}
```
public static final FileType RAR
```


Αντιπροσωπεύει ένα συμπιεσμένο αρχείο Roshal Archive (.rar) που δημιουργήθηκε χρησιμοποιώντας τη μέθοδο συμπίεσης RAR (WINRAR έκδοση 4). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/compression/rar

### GZ {#GZ}
```
public static final FileType GZ
```


Αντιπροσωπεύει ένα συμπιεσμένο αρχείο Gnu Zipped File (.gz) που δημιουργήθηκε με την εφαρμογή συμπίεσης gzip. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/compression/gz

### GZIP {#GZIP}
```
public static final FileType GZIP
```


Αντιπροσωπεύει ένα συμπιεσμένο αρχείο Gnu Zipped File (.gzip) που εισήχθη ως δωρεάν εργαλείο για την αντικατάσταση του προγράμματος Compress που χρησιμοποιείται σε συστήματα Unix. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/compression/gz

### SEVEN_ZIP {#SEVEN-ZIP}
```
public static final FileType SEVEN_ZIP
```


Αντιπροσωπεύει ένα αρχείο 7Zip (.7z, .7zip), το οποίο είναι ένας δωρεάν ανοιχτού κώδικα αρχειοθέτης με συμπίεση LZMA και LZMA2. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/compression/7z/

### CPIO {#CPIO}
```
public static final FileType CPIO
```


Το Cpio είναι ένα γενικό εργαλείο αρχειοθέτησης αρχείων και η σχετική του μορφή αρχείου. Εγκαθίσταται κυρίως σε λειτουργικά συστήματα υπολογιστών τύπου Unix. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/compression/cpio

### ZSTANDARD {#ZSTANDARD}
```
public static final FileType ZSTANDARD
```


Το αρχείο ZST είναι ένα συμπιεσμένο αρχείο που δημιουργείται με τον αλγόριθμο συμπίεσης Zstandard (zstd). Είναι ένα συμπιεσμένο αρχείο που δημιουργείται με αλγοριθμική συμπίεση χωρίς απώλειες. Τα αρχεία ZST μπορούν να χρησιμοποιηθούν για τη συμπίεση διαφόρων τύπων αρχείων όπως βάσεις δεδομένων, συστήματα αρχείων, δίκτυα και παιχνίδια. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/compression/zst/

### TZST {#TZST}
```
public static final FileType TZST
```


Τα αρχεία TZST (.tar.zst, .tzst) είναι αρχεία Zstandard (ZST), τα οποία εσωτερικά περιέχουν ένα ενοποιημένο αρχείο Unix (Tar), δημιουργημένα με εργαλείο βασισμένο σε Unix για τη συλλογή ενός ή περισσότερων αρχείων.

### TAR_ZST {#TAR-ZST}
```
public static final FileType TAR_ZST
```


Τα αρχεία TZST (.tar.zst, .tzst) είναι αρχεία Zstandard (ZST), τα οποία εσωτερικά περιέχουν ένα ενοποιημένο αρχείο Unix (Tar), δημιουργημένα με εργαλείο βασισμένο σε Unix για τη συλλογή ενός ή περισσότερων αρχείων.

### ISO {#ISO}
```
public static final FileType ISO
```


Η εικόνα οπτικού δίσκου ISO είναι ένα μη συμπιεσμένο αρχείο εικόνας αρχείου δίσκου που αντιπροσωπεύει τα περιεχόμενα ολόκληρων δεδομένων σε έναν οπτικό δίσκο όπως CD ή DVD, βάσει του προτύπου ISO-9660. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/compression/iso/

### LHA {#LHA}
```
public static final FileType LHA
```


Το LHA ή LZH είναι ένα δωρεάν εργαλείο συμπίεσης και η σχετική μορφή αρχείου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/compression/lzh/

### CAB {#CAB}
```
public static final FileType CAB
```


Το Cabinet (ή CAB) είναι μια μορφή αρχείου-αρχειοθήκης για το Microsoft Windows. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://en.wikipedia.org/wiki/Cabinet_%28file_format%29

### DXF {#DXF}
```
public static final FileType DXF
```


Αντιπροσωπεύει ένα αρχείο Drawing Exchange Format (.dxf), το οποίο είναι μια ετικετοποιημένη αναπαράσταση δεδομένων αρχείου σχεδίασης AutoCAD. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/cad/dxf

### DWG {#DWG}
```
public static final FileType DWG
```


Αντιπροσωπεύει ένα αρχείο AutoCAD Drawing Database (.dwg), το οποίο αντιπροσωπεύει ιδιόκτητα δυαδικά αρχεία που χρησιμοποιούνται για την αποθήκευση δεδομένων σχεδίασης 2D και 3D. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/cad/dwg

### DWT {#DWT}
```
public static final FileType DWT
```


Αντιπροσωπεύει ένα πρότυπο σχεδίασης AutoCAD (.dwt), το οποίο είναι ένα αρχείο προτύπου σχεδίασης AutoCAD που χρησιμοποιείται ως βάση για τη δημιουργία σχεδίων που μπορούν να αποθηκευτούν ως αρχεία DWG. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/cad/dwt

### STL {#STL}
```
public static final FileType STL
```


Αντιπροσωπεύει ένα αρχείο Stereolithography (.stl), το οποίο είναι μια εναλλάξιμη μορφή αρχείου που αντιπροσωπεύει γεωμετρία επιφάνειας τριών διαστάσεων. Χρησιμοποιείται συνήθως στην ταχεία πρωτοτυποποίηση, την 3D εκτύπωση και την υποβοηθούμενη κατασκευή. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/cad/stl

### IFC {#IFC}
```
public static final FileType IFC
```


Αντιπροσωπεύει ένα αρχείο Industry Foundation Classes (.ifc), το οποίο είναι μια μορφή αρχείου που καθιερώνει διεθνή πρότυπα για την εισαγωγή και εξαγωγή αντικειμένων κτιρίων και των ιδιοτήτων τους. Επιτρέπει τη διαλειτουργικότητα μεταξύ διαφορετικών εφαρμογών λογισμικού. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/cad/ifc

### DWF {#DWF}
```
public static final FileType DWF
```


Αντιπροσωπεύει ένα αρχείο Design Web Format (.dwf), το οποίο είναι μια συμπιεσμένη μορφή αρχείου για προβολή, ανασκόπηση ή εκτύπωση σχεδίων 2D/3D. Περιέχει γραφικά και κείμενο ως μέρος των δεδομένων σχεδίασης και μειώνει το μέγεθος του αρχείου λόγω συμπίεσης. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/cad/dwf

### FBX {#FBX}
```
public static final FileType FBX
```


Αντιπροσωπεύει ένα αρχείο Autodesk FBX Interchange (FilmBoX) (.fbx), το οποίο είναι μια μορφή 3D μοντέλου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/cad/fbx

### DWFX {#DWFX}
```
public static final FileType DWFX
```


Αντιπροσωπεύει ένα αρχείο Design Web Format XPS (.dwfx), το οποίο είναι μια συμπιεσμένη μορφή για προβολή, ανασκόπηση ή εκτύπωση σχεδίων 2D/3D ως έγγραφο XPS. Περιέχει γραφικά και κείμενο ως μέρος των δεδομένων σχεδίασης και μειώνει το μέγεθος του αρχείου λόγω συμπίεσης. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/cad/dwfx

### DGN {#DGN}
```
public static final FileType DGN
```


Αντιπροσωπεύει ένα αρχείο MicroStation Design (.dgn), το οποίο είναι σχέδια που δημιουργούνται και υποστηρίζονται από εφαρμογές CAD όπως το MicroStation και το Intergraph Interactive Graphics Design System. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/cad/dgn

### PLT {#PLT}
```
public static final FileType PLT
```


Αντιπροσωπεύει ένα αρχείο PLT (HPGL) (.plt), το οποίο είναι ένα διανυσματικό αρχείο σχεδιαστή που εισήχθη από την Autodesk, Inc. Περιέχει πληροφορίες για ένα συγκεκριμένο αρχείο CAD και όλες οι εικόνες εκτυπώνονται με γραμμές αντί για κουκκίδες, εξασφαλίζοντας ακρίβεια και προσοχή στην παραγωγή. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/cad/plt

### CF2 {#CF2}
```
public static final FileType CF2
```


Αντιπροσωπεύει ένα αρχείο Common File Format (.cf2). Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://fileinfo.com/extension/cf2

### OBJ {#OBJ}
```
public static final FileType OBJ
```


Αντιπροσωπεύει ένα αρχείο Wavefront 3D Object (.obj), το οποίο είναι ένα αρχείο 3D εικόνας που εισήχθη από την Wavefront Technologies. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/3d/obj/

### HPG {#HPG}
```
public static final FileType HPG
```


Αντιπροσωπεύει ένα αρχείο PLT (HPGL) (.hpg). Είναι ένα μορφότυπο αρχείου που χρησιμοποιείται για αρχεία σχεδιαστή στη γλώσσα HP Graphics (HPGL). Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://fileinfo.com/extension/hpg

### IGS {#IGS}
```
public static final FileType IGS
```


Αντιπροσωπεύει ένα αρχείο Initial Graphics Exchange Specification (IGES) (.igs).

### VSD {#VSD}
```
public static final FileType VSD
```


Αντιπροσωπεύει ένα αρχείο Visio Drawing (.vsd), το οποίο είναι σχέδια που δημιουργήθηκαν με την εφαρμογή Microsoft Visio για την αναπαράσταση διαφόρων γραφικών αντικειμένων και των συνδέσεών τους. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/image/vsd

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Αντιπροσωπεύει ένα αρχείο Visio Drawing (.vsdx), το οποίο αντιπροσωπεύει το μορφότυπο αρχείου Microsoft Visio που εισήχθη από το Microsoft Office 2013 και μετά. Αντικατέστησε το δυαδικό μορφότυπο αρχείου (.VSD) που υποστηριζόταν από προηγούμενες εκδόσεις του Microsoft Visio. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/image/vsdx

### VSS {#VSS}
```
public static final FileType VSS
```


Αντιπροσωπεύει ένα αρχείο Visio Stencil (.vss), το οποίο είναι αρχεία στενσίλ που δημιουργήθηκαν με το Microsoft Visio 2007 και παλαιότερα. Τα αρχεία στενσίλ παρέχουν αντικείμενα σχεδίασης που μπορούν να συμπεριληφθούν σε ένα σχέδιο Visio .VSD. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/image/vss

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Αντιπροσωπεύει ένα αρχείο Visio Stencil (.vssx), το οποίο είναι στενσίλ σχεδίασης που δημιουργήθηκαν με το Microsoft Visio 2013 και νεότερα. Το μορφότυπο αρχείου VSSX μπορεί να ανοιχθεί με το Visio 2013 και νεότερα. Τα αρχεία Visio είναι γνωστά για την αναπαράσταση διαφόρων στοιχείων σχεδίασης όπως σχήματα, συνδέσμους, διαγράμματα ροής, διάταξη δικτύου, διαγράμματα UML κ.λπ. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/image/vssx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Αντιπροσωπεύει ένα αρχείο Visio Macro-Enabled Drawing (.vsdm), το οποίο είναι αρχεία σχεδίασης που δημιουργήθηκαν με την εφαρμογή Microsoft Visio και υποστηρίζουν μακροεντολές. Τα αρχεία VSDM είναι σχέδια OPC/XML που είναι παρόμοια με τα VSDX, αλλά παρέχουν επίσης τη δυνατότητα εκτέλεσης μακροεντολών όταν το αρχείο ανοίγει. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/image/vsdm

### VST {#VST}
```
public static final FileType VST
```


Αντιπροσωπεύει ένα πρότυπο σχεδίασης Visio (.vst), το οποίο είναι αρχεία διανυσματικών εικόνων που δημιουργήθηκαν με το Microsoft Visio. Λειτουργούν ως πρότυπα για τη δημιουργία περαιτέρω αρχείων και περιέχουν την προεπιλεγμένη διάταξη και τις ρυθμίσεις που χρησιμοποιούνται για τη δημιουργία νέων σχεδίων Visio. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/image/vst

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Αντιπροσωπεύει ένα πρότυπο σχεδίασης Visio (.vstx), το οποίο είναι αρχεία προτύπων σχεδίασης που δημιουργήθηκαν με το Microsoft Visio 2013 και νεότερα. Αυτά τα αρχεία VSTX παρέχουν ένα σημείο εκκίνησης για τη δημιουργία σχεδίων Visio που αποθηκεύονται ως αρχεία .VSDX, με προεπιλεγμένη διάταξη και ρυθμίσεις. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Αντιπροσωπεύει ένα πρότυπο σχεδίασης Visio Macro-Enabled (.vstm), το οποίο είναι αρχεία προτύπων που δημιουργήθηκαν με το Microsoft Visio και υποστηρίζουν μακροεντολές. Τα αρχεία που δημιουργούνται από πρότυπα VSTM μπορούν να εκτελούν μακροεντολές που αναπτύχθηκαν σε κώδικα Visual Basic for Applications (VBA). Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Αντιπροσωπεύει ένα αρχείο Visio Macro-Enabled Stencil (.vssm), το οποίο είναι αρχεία Stencil του Microsoft Visio που υποστηρίζουν μακροεντολές. Όταν ανοίγεται ένα αρχείο VSSM, μπορούν να εκτελεστούν μακροεντολές για την επίτευξη της επιθυμητής μορφοποίησης και τοποθέτησης σχημάτων σε ένα διάγραμμα. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Αντιπροσωπεύει ένα αρχείο Visio Stencil XML (.vsx), το οποίο αναφέρεται σε στενσίλ που αποτελούνται από σχέδια και σχήματα που χρησιμοποιούνται για τη δημιουργία διαγραμμάτων στο Microsoft Visio. Τα αρχεία VSX αποθηκεύονται σε μορφότυπο XML και υποστηρίζονταν μέχρι το Visio 2013. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Αντιπροσωπεύει ένα αρχείο Visio Template XML (.vtx), το οποίο είναι ένα πρότυπο σχεδίασης Microsoft Visio που αποθηκεύεται στο δίσκο σε μορφότυπο XML. Το πρότυπο παρέχει βασικές ρυθμίσεις για τη δημιουργία πολλαπλών αρχείων Visio με τις ίδιες ρυθμίσεις. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/image/vtx

### VDW {#VDW}
```
public static final FileType VDW
```


Αντιπροσωπεύει ένα Visio Web Drawing (.vdw), το οποίο καθορίζει τις ροές και τις αποθηκεύσεις που απαιτούνται για την απόδοση ενός web drawing. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/web/vdw

### VDX {#VDX}
```
public static final FileType VDX
```


Αναπαριστά ένα αρχείο Visio Drawing XML (.vdx), το οποίο αντιπροσωπεύει οποιοδήποτε σχέδιο ή διάγραμμα που δημιουργήθηκε στο Microsoft Visio αλλά αποθηκεύτηκε σε μορφή XML με την επέκταση .VDX. Ένα αρχείο Visio drawing XML δημιουργείται στο λογισμικό Visio που αναπτύχθηκε από τη Microsoft. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Αναπαριστά ένα αρχείο Open eBook (.epub), το οποίο είναι μια μορφή αρχείου e‑book που παρέχει ένα τυποποιημένο ψηφιακό μορφότυπο δημοσίευσης για εκδότες και καταναλωτές. Η μορφή υποστηρίζεται από πολλούς e‑readers και λογισμικές εφαρμογές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/ebook/epub

### MOBI {#MOBI}
```
public static final FileType MOBI
```


Αναπαριστά ένα Mobipocket eBook (.mobi), το οποίο είναι μία από τις πιο διαδεδομένες μορφές αρχείων ebook. Η μορφή αποτελεί βελτίωση της παλιάς μορφής OEB (Open Ebook Format) και χρησιμοποιήθηκε ως ιδιόκτητη μορφή για το Mobipocket Reader. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/ebook/mobi

### AZW_3 {#AZW-3}
```
public static final FileType AZW_3
```


Το Amazon Kindle Format 8 (KF8) ebook είναι η ψηφιακή μορφή αρχείου που αναπτύχθηκε για τις συσκευές Amazon Kindle. Η μορφή αποτελεί βελτίωση των παλαιότερων αρχείων AZW και χρησιμοποιείται μόνο σε συσκευές Kindle Fire με συμβατότητα προς τα πίσω με τις προγενέστερες μορφές αρχείων, δηλαδή MOBI και AZW. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/ebook/azw3

### MSG {#MSG}
```
public static final FileType MSG
```


Αναπαριστά ένα Outlook Mail Message (.msg), το οποίο είναι μια μορφή αρχείου που χρησιμοποιείται από το Microsoft Outlook και το Exchange για την αποθήκευση μηνυμάτων email, επαφών, ραντεβού ή άλλων εργασιών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/email/msg

### EML {#EML}
```
public static final FileType EML
```


Αναπαριστά ένα E‑Mail Message (.eml), το οποίο αντιπροσωπεύει μηνύματα email που αποθηκεύτηκαν χρησιμοποιώντας το Outlook και άλλες σχετικές εφαρμογές. Σχεδόν όλοι οι πελάτες email υποστηρίζουν αυτή τη μορφή αρχείου λόγω της συμμόρφωσής της με το πρότυπο RFC‑822 Internet Message Format Standard. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/email/eml

### EMLX {#EMLX}
```
public static final FileType EMLX
```


Αναπαριστά ένα Apple Mail Message (.emlx), το οποίο υλοποιείται και αναπτύσσεται από την Apple. Η εφαρμογή Apple Mail χρησιμοποιεί τη μορφή αρχείου EMLX για την εξαγωγή email. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/email/emlx

### PST {#PST}
```
public static final FileType PST
```


Αναπαριστά ένα Outlook Personal Information Store File (.pst), το οποίο αντιπροσωπεύει τα Outlook Personal Storage Files (επίσης γνωστά ως Personal Storage Table) που αποθηκεύουν ποικίλη πληροφορία χρήστη. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/email/pst

### OST {#OST}
```
public static final FileType OST
```


Αναπαριστά ένα Outlook Offline Data File (.ost), το οποίο αντιπροσωπεύει τα δεδομένα του γραμματοκιβωτίου ενός χρήστη σε λειτουργία εκτός σύνδεσης σε τοπικό υπολογιστή μετά την εγγραφή στον Exchange Server χρησιμοποιώντας το Microsoft Outlook. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/email/ost

### TIF {#TIF}
```
public static final FileType TIF
```


Αναπαριστά ένα Tagged Image File (.tif), το οποίο αντιπροσωπεύει εικόνες raster που προορίζονται για χρήση σε ποικίλες συσκευές που συμμορφώνονται με αυτό το πρότυπο μορφής αρχείου. Είναι ικανό να περιγράφει εικόνες διπλού επιπέδου, γκρι κλίμακας, χρωματιστές παλέτας και πλήρους χρώματος σε διάφορους χρωματικούς χώρους. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/image/tiff

### TIFF {#TIFF}
```
public static final FileType TIFF
```


Αναπαριστά ένα Tagged Image File Format (.tiff), το οποίο αντιπροσωπεύει εικόνες raster που προορίζονται για χρήση σε ποικίλες συσκευές που συμμορφώνονται με αυτό το πρότυπο μορφής αρχείου. Είναι ικανό να περιγράφει εικόνες διπλού επιπέδου, γκρι κλίμακας, χρωματιστές παλέτας και πλήρους χρώματος σε διάφορους χρωματικούς χώρους. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/image/tiff

### JPG {#JPG}
```
public static final FileType JPG
```


Αναπαριστά μια JPEG Image (.jpg), η οποία είναι ένας τύπος μορφής εικόνας που αποθηκεύεται με τη μέθοδο της απώλειας συμπίεσης. Η παραγόμενη εικόνα, ως αποτέλεσμα της συμπίεσης, αποτελεί μια ισορροπία μεταξύ μεγέθους αποθήκευσης και ποιότητας εικόνας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JPEG {#JPEG}
```
public static final FileType JPEG
```


Αναπαριστά μια JPEG Image (.jpeg), η οποία είναι ένας τύπος μορφής εικόνας που αποθηκεύεται με τη μέθοδο της απώλειας συμπίεσης. Η παραγόμενη εικόνα, ως αποτέλεσμα της συμπίεσης, αποτελεί μια ισορροπία μεταξύ μεγέθους αποθήκευσης και ποιότητας εικόνας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/image/jpeg

### JFIF {#JFIF}
```
public static final FileType JFIF
```


Το JPEG File Interchange Format (.jfif) είναι μια εικόνα που αναπτύχθηκε για γρήγορη ανταλλαγή μεταξύ πλατφορμών. Αυτή η μορφή χρησιμοποιεί συμπίεση JPEG. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/image/jfif

### PNG {#PNG}
```
public static final FileType PNG
```


Αναπαριστά ένα Portable Network Graphic (.png), το οποίο είναι ένας τύπος μορφής αρχείου raster εικόνας που χρησιμοποιεί συμπίεση χωρίς απώλειες. Αυτή η μορφή αρχείου δημιουργήθηκε ως αντικατάσταση του Graphics Interchange Format (GIF) και δεν έχει περιορισμούς πνευματικών δικαιωμάτων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/image/png

### GIF {#GIF}
```
public static final FileType GIF
```


Αντιπροσωπεύει ένα αρχείο Graphical Interchange Format (.gif), το οποίο είναι ένας τύπος εξαιρετικά συμπιεσμένης εικόνας. Για κάθε εικόνα, το GIF συνήθως επιτρέπει έως 8 bit ανά pixel, και επιτρέπονται έως 256 χρώματα σε ολόκληρη την εικόνα. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/gif

### APNG {#APNG}
```
public static final FileType APNG
```


Αντιπροσωπεύει ένα Animated Portable Network Graphic (.apng), το οποίο είναι μια επέκταση του μορφότυπου PNG που υποστηρίζει κίνηση. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/apng

### BMP {#BMP}
```
public static final FileType BMP
```


Αντιπροσωπεύει ένα αρχείο Bitmap Image (.bmp), το οποίο χρησιμοποιείται για την αποθήκευση ψηφιακών bitmap εικόνων. Αυτές οι εικόνες είναι ανεξάρτητες από την κάρτα γραφικών και ονομάζονται επίσης μορφότυπο device independent bitmap (DIB). Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/bmp

### ICO {#ICO}
```
public static final FileType ICO
```


Αντιπροσωπεύει ένα αρχείο Icon (.ico), το οποίο είναι τύπος αρχείου εικόνας που χρησιμοποιείται ως εικονίδιο για την αναπαράσταση μιας εφαρμογής στα Microsoft Windows. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/ico

### TGA {#TGA}
```
public static final FileType TGA
```


Αντιπροσωπεύει ένα αρχείο Truevision TGA (TARGA), το οποίο χρησιμοποιείται για την αποθήκευση ψηφιακών bitmap εικόνων που αναπτύχθηκαν από την TRUEVISION. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/tga

### JP_2 {#JP-2}
```
public static final FileType JP_2
```


Αντιπροσωπεύει ένα αρχείο JPEG 2000 Core Image (.jp2), το οποίο είναι σύστημα κωδικοποίησης εικόνας και σύγχρονο πρότυπο συμπίεσης εικόνας. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/jp2

### JPF {#JPF}
```
public static final FileType JPF
```


Αντιπροσωπεύει ένα αρχείο JPEG 2000 Image (.jpf). Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/image/jpf

### JPX {#JPX}
```
public static final FileType JPX
```


Αντιπροσωπεύει ένα αρχείο JPEG 2000 Image (.jpx). Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/jpx

### JPM {#JPM}
```
public static final FileType JPM
```


Αντιπροσωπεύει ένα αρχείο JPEG 2000 Image (.jpm). Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/jpm

### J2C {#J2C}
```
public static final FileType J2C
```


Αντιπροσωπεύει ένα JPEG 2000 Code InputStream (.j2c). Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/j2c

### J2K {#J2K}
```
public static final FileType J2K
```


Αντιπροσωπεύει ένα JPEG 2000 Code Stream (.j2k), το οποίο είναι μια εικόνα συμπιεσμένη με χρήση κυματικής συμπίεσης αντί για συμπίεση DCT. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/j2k

### JPC {#JPC}
```
public static final FileType JPC
```


Αντιπροσωπεύει ένα JPEG 2000 Code Stream (.jpc). Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/jpc

### JLS {#JLS}
```
public static final FileType JLS
```


Αντιπροσωπεύει ένα αρχείο JPEG-LS (JLS) (.jls). Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://fileinfo.com/extension/jls

### DIB {#DIB}
```
public static final FileType DIB
```


Αντιπροσωπεύει ένα αρχείο Device Independent Bitmap (.dib). Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/dib

### WMF {#WMF}
```
public static final FileType WMF
```


Αντιπροσωπεύει ένα Windows Metafile (.wmf), το οποίο αντιπροσωπεύει το Microsoft Windows Metafile (WMF) για την αποθήκευση δεδομένων εικόνας σε μορφή διανυσματικών καθώς και bitmap. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/wmf

### WMZ {#WMZ}
```
public static final FileType WMZ
```


Αντιπροσωπεύει ένα Compressed Windows Metafile (.wmz), το οποίο αντιπροσωπεύει το Microsoft Windows Metafile (WMF) συμπιεσμένο σε αρχείο GZIP για την αποθήκευση δεδομένων εικόνας σε μορφή διανυσματικών καθώς και bitmap. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://fileinfo.com/extension/wmz#compressed_windows_metafile

### EMF {#EMF}
```
public static final FileType EMF
```


Αντιπροσωπεύει ένα Enhanced Windows Metafile (.emf), το οποίο αντιπροσωπεύει γραφικές εικόνες ανεξάρτητα από τη συσκευή. Τα metafiles του EMF περιλαμβάνουν εγγραφές μεταβλητού μήκους σε χρονολογική σειρά που μπορούν να αποδώσουν την αποθηκευμένη εικόνα μετά την ανάλυση σε οποιαδήποτε συσκευή εξόδου. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/emf

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Αντιπροσωπεύει ένα Windows Compressed Enhanced Metafile (.emz), το οποίο αντιπροσωπεύει γραφικές εικόνες ανεξάρτητα από τη συσκευή, συμπιεσμένες με GZIP. Τα metafiles του EMF περιλαμβάνουν εγγραφές μεταβλητού μήκους σε χρονολογική σειρά που μπορούν να αποδώσουν την αποθηκευμένη εικόνα μετά την ανάλυση σε οποιαδήποτε συσκευή εξόδου. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/emz

### WEBP {#WEBP}
```
public static final FileType WEBP
```


Αντιπροσωπεύει μια εικόνα WebP (.webp), η οποία είναι ένας σύγχρονος raster μορφότυπος web εικόνας βασισμένος σε απώλεια-και-μη-απώλεια συμπίεση. Παρέχει την ίδια ποιότητα εικόνας ενώ μειώνει σημαντικά το μέγεθος της εικόνας. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/webp

### DNG {#DNG}
```
public static final FileType DNG
```


Αντιπροσωπεύει μια προδιαγραφή Digital Negative (.dng), η οποία είναι μορφότυπος εικόνας ψηφιακής κάμερας που χρησιμοποιείται για την αποθήκευση ακατέργαστων αρχείων. Αναπτύχθηκε από την Adobe τον Σεπτέμβριο 2004 και χρησιμοποιείται κυρίως για ψηφιακή φωτογραφία. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/dng

### CDR {#CDR}
```
public static final FileType CDR
```


Αντιπροσωπεύει ένα CorelDraw Vector Graphic Drawing (.cdr), το οποίο είναι αρχείο εικόνας διανυσματικού σχεδίου που δημιουργείται εγγενώς με το CorelDRAW για την αποθήκευση ψηφιακά κωδικοποιημένων και συμπιεσμένων εικόνων. Ένα αρχείο σχεδίου CDR περιέχει κείμενο, γραμμές, σχήματα, εικόνες, χρώματα και εφέ για διανυσματική αναπαράσταση του περιεχομένου της εικόνας. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/cdr

### CMX {#CMX}
```
public static final FileType CMX
```


Αντιπροσωπεύει ένα Corel Exchange (.cmx), το οποίο είναι αρχείο εικόνας σχεδίου που μπορεί να περιέχει διανυσματικά γραφικά καθώς και bitmap γραφικά. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://wiki.fileformat.com/image/cmx

### DJVU {#DJVU}
```
public static final FileType DJVU
```


Αντιπροσωπεύει μια εικόνα DjVu (.djvu), η οποία είναι μια μορφή αρχείου γραφικών που προορίζεται για σαρωμένα έγγραφα και βιβλία, ειδικά εκείνα που περιέχουν συνδυασμό κειμένου, σχεδίων, εικόνων και φωτογραφιών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/image/djvu

### CGM {#CGM}
```
public static final FileType CGM
```


Αντιπροσωπεύει ένα Metafile Υπολογιστικών Γραφικών (.cgm), το οποίο είναι μια δωρεάν, ανεξάρτητη από πλατφόρμα, διεθνής πρότυπη μορφή μετααρχείου για την αποθήκευση και ανταλλαγή διανυσματικών γραφικών (2Δ), ραστερ γραφικών και κειμένου. Το CGM χρησιμοποιεί αντικειμενοστραφή προσέγγιση και παρέχει πολλές λειτουργίες για την παραγωγή εικόνων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/page-description-language/cgm

### PCL {#PCL}
```
public static final FileType PCL
```


Αντιπροσωπεύει ένα έγγραφο Printer Command Language (.pcl). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/page-description-language/pcl

### PSD {#PSD}
```
public static final FileType PSD
```


Αντιπροσωπεύει ένα έγγραφο Adobe Photoshop (.psd), το οποίο είναι η εγγενής μορφή αρχείου του Adobe Photoshop που χρησιμοποιείται για σχεδίαση και ανάπτυξη γραφικών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/image/psd

### PSB {#PSB}
```
public static final FileType PSB
```


Αντιπροσωπεύει τη μορφή Photoshop Large Document (.psb), η οποία χρησιμοποιείται για σχεδίαση και ανάπτυξη γραφικών στο Adobe Photoshop. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/image/psb

### DCM {#DCM}
```
public static final FileType DCM
```


Αντιπροσωπεύει μια εικόνα DICOM (.dcm), η οποία αντιπροσωπεύει μια ψηφιακή εικόνα που αποθηκεύει ιατρικές πληροφορίες ασθενών όπως MRI, αξονικές τομογραφίες (CT) και υπερηχογραφικές εικόνες. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/image/dcm

### PS {#PS}
```
public static final FileType PS
```


Αντιπροσωπεύει ένα αρχείο PostScript (.ps). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/page-description-language/ps

### EPS {#EPS}
```
public static final FileType EPS
```


Αντιπροσωπεύει ένα αρχείο Encapsulated PostScript (.eps), το οποίο περιγράφει ένα πρόγραμμα γλώσσας Encapsulated PostScript που ορίζει την εμφάνιση μιας μόνο σελίδας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/page-description-language/eps

### ODG {#ODG}
```
public static final FileType ODG
```


Αντιπροσωπεύει ένα αρχείο OpenDocument Graphic (.odg), το οποίο χρησιμοποιείται από την εφαρμογή Draw του Apache OpenOffice για την αποθήκευση στοιχείων σχεδίασης ως διανυσματική εικόνα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/image/odg

### FODG {#FODG}
```
public static final FileType FODG
```


Αντιπροσωπεύει ένα Flat XML ODF Template (.fodg), το οποίο χρησιμοποιείται από την εφαρμογή Draw του Apache OpenOffice για την αποθήκευση στοιχείων σχεδίασης ως διανυσματική εικόνα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/image/fodg

### SVG {#SVG}
```
public static final FileType SVG
```


Αντιπροσωπεύει ένα αρχείο Scalable Vector Graphics (.svg), το οποίο είναι ένα αρχείο Scalar Vector Graphics που χρησιμοποιεί μορφή κειμένου βασισμένη σε XML για την περιγραφή της εμφάνισης μιας εικόνας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/page-description-language/svg

### SVGZ {#SVGZ}
```
public static final FileType SVGZ
```


Αντιπροσωπεύει ένα συμπιεσμένο αρχείο Scalable Vector Graphics (.svgz), το οποίο είναι ένα αρχείο Scalar Vector Graphics που χρησιμοποιεί μορφή κειμένου βασισμένη σε XML, συμπιεσμένη με GZIP, για την περιγραφή της εμφάνισης μιας εικόνας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://fileinfo.com/extension/svgz

### OTG {#OTG}
```
public static final FileType OTG
```


Αντιπροσωπεύει ένα πρότυπο OpenDocument Graphic (.otg). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/image/otg

### HTM {#HTM}
```
public static final FileType HTM
```


Αντιπροσωπεύει ένα αρχείο Hypertext Markup Language (.htm), το οποίο είναι η επέκταση για ιστοσελίδες που δημιουργούνται για προβολή σε προγράμματα περιήγησης. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/web/html

### HTML {#HTML}
```
public static final FileType HTML
```


Αντιπροσωπεύει ένα αρχείο Hypertext Markup Language (.html), το οποίο είναι η επέκταση για ιστοσελίδες που δημιουργούνται για προβολή σε προγράμματα περιήγησης. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


Αντιπροσωπεύει ένα αρχείο MHTML Web Archive (.mht). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/web/mht

### NSF {#NSF}
```
public static final FileType NSF
```


Αντιπροσωπεύει μια βάση δεδομένων Lotus Notes (.nsf). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://fileinfo.com/extension/nsf

### MBOX {#MBOX}
```
public static final FileType MBOX
```


Αντιπροσωπεύει ένα αρχείο γραμματοκιβωτίου Email (.mbox). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://fileinfo.com/extension/mbox

### MHTML {#MHTML}
```
public static final FileType MHTML
```


Αντιπροσωπεύει ένα αρχείο MIME HTML (.mhtml). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/web/mhtml

### XML {#XML}
```
public static final FileType XML
```


Αντιπροσωπεύει ένα αρχείο XML (.xml). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/web/xml

### ONE {#ONE}
```
public static final FileType ONE
```


Αντιπροσωπεύει ένα έγγραφο OneNote (.one) που δημιουργήθηκε από την εφαρμογή Microsoft OneNote. Το OneNote σας επιτρέπει να συγκεντρώνετε πληροφορίες χρησιμοποιώντας την εφαρμογή σαν να χρησιμοποιείτε το σημειωματάριό σας για λήψη σημειώσεων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Αντιπροσωπεύει ένα αρχείο Portable Document Format (.pdf), το οποίο είναι ένας τύπος εγγράφου που δημιουργήθηκε από την Adobe τη δεκαετία του 1990. Ο σκοπός αυτής της μορφής αρχείου ήταν η εισαγωγή ενός προτύπου για την αναπαράσταση εγγράφων και άλλου υλικού αναφοράς σε μορφή ανεξάρτητη από λογισμικό εφαρμογών, υλικό και λειτουργικά συστήματα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


Αντιπροσωπεύει ένα αρχείο XML Paper Specification (.xps), το οποίο αντιπροσωπεύει αρχεία διάταξης σελίδων βασισμένα στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Αυτό το φορμάτ αναπτύχθηκε από τη Microsoft ως αντικατάσταση του φορμάτ αρχείου EMF και είναι παρόμοιο με το φορμάτ αρχείου PDF, αλλά χρησιμοποιεί XML στη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/page-description-language/xps

### OXPS {#OXPS}
```
public static final FileType OXPS
```


Αντιπροσωπεύει ένα αρχείο OpenXPS (.oxps). Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/page-description-language/oxps

### TEX {#TEX}
```
public static final FileType TEX
```


Αντιπροσωπεύει ένα έγγραφο πηγής LaTeX (.tex), το οποίο είναι μια γλώσσα που περιλαμβάνει προγραμματισμό καθώς και δυνατότητες σήμανσης που χρησιμοποιούνται για τη στοιχειοθέτηση εγγράφων. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


Αντιπροσωπεύει μια παρουσίαση PowerPoint (.ppt), η οποία αντιπροσωπεύει ένα αρχείο PowerPoint που αποτελείται από μια συλλογή διαφανειών για προβολή ως παρουσίαση. Καθορίζει το Binary File Format που χρησιμοποιείται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


Αντιπροσωπεύει μια παρουσίαση PowerPoint Open XML (.pptx), η οποία είναι αρχεία παρουσίασης που δημιουργήθηκαν με τη δημοφιλή εφαρμογή Microsoft PowerPoint. Σε αντίθεση με την προηγούμενη έκδοση του φορμάτ αρχείου παρουσίασης PPT, που ήταν δυαδικό, το φορμάτ PPTX βασίζεται στο Microsoft PowerPoint Open XML φορμάτ αρχείου παρουσίασης. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


Αντιπροσωπεύει μια παρουσίαση διαφανειών PowerPoint (.pps), η οποία δημιουργείται με χρήση του Microsoft PowerPoint για σκοπούς παρουσίασης διαφανειών. Η ανάγνωση και δημιουργία αρχείων PPS υποστηρίζεται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


Αντιπροσωπεύει αρχεία PowerPoint Open XML Slide Show (.ppsx), τα οποία δημιουργούνται με χρήση του Microsoft PowerPoint 2007 και νεότερων για σκοπούς παρουσίασης διαφανειών. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


Αντιπροσωπεύει μια παρουσίαση OpenDocument (.odp), η οποία αντιπροσωπεύει ένα φορμάτ αρχείου παρουσίασης που χρησιμοποιείται από το OpenOffice.org στο πρότυπο OASISOpen. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/presentation/odp

### FODP {#FODP}
```
public static final FileType FODP
```


Αντιπροσωπεύει μια παρουσίαση OpenDocument (.fodp), η οποία αντιπροσωπεύει την OpenDocument Flat XML Presentation. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://fileinfo.com/extension/fodp

### POT {#POT}
```
public static final FileType POT
```


Αντιπροσωπεύει ένα πρότυπο PowerPoint (.pot), το οποίο αντιπροσωπεύει αρχεία προτύπων Microsoft PowerPoint που δημιουργήθηκαν από εκδόσεις PowerPoint 97-2003. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/presentation/pot

### PPTM {#PPTM}
```
public static final FileType PPTM
```


Αντιπροσωπεύει μια παρουσίαση PowerPoint Open XML Macro-Enabled (.pptm), η οποία είναι αρχεία παρουσίασης με ενεργοποιημένα μακροεντολές που δημιουργήθηκαν με το Microsoft PowerPoint 2007 ή νεότερες εκδόσεις. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/presentation/pptm

### POTX {#POTX}
```
public static final FileType POTX
```


Αντιπροσωπεύει ένα πρότυπο παρουσίασης PowerPoint Open XML (.potx), το οποίο αντιπροσωπεύει πρότυπα παρουσίασης Microsoft PowerPoint που δημιουργήθηκαν με το Microsoft PowerPoint 2007 και νεότερες εκδόσεις. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/presentation/potx

### POTM {#POTM}
```
public static final FileType POTM
```


Αντιπροσωπεύει ένα πρότυπο παρουσίασης PowerPoint Open XML Macro-Enabled (.potm), το οποίο είναι αρχεία προτύπων Microsoft PowerPoint με υποστήριξη μακροεντολών. Τα αρχεία POTM δημιουργούνται με το PowerPoint 2007 ή νεότερο και περιέχουν προεπιλεγμένες ρυθμίσεις που μπορούν να χρησιμοποιηθούν για τη δημιουργία περαιτέρω αρχείων παρουσίασης. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/presentation/potm

### PPSM {#PPSM}
```
public static final FileType PPSM
```


Αντιπροσωπεύει μια διαφάνεια PowerPoint Open XML Macro-Enabled (.ppsm), η οποία αντιπροσωπεύει ένα φορμάτ αρχείου παρουσίασης διαφανειών με ενεργοποιημένα μακροεντολές που δημιουργήθηκε με το Microsoft PowerPoint 2007 ή νεότερο. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/presentation/ppsm

### OTP {#OTP}
```
public static final FileType OTP
```


Αντιπροσωπεύει ένα πρότυπο παρουσίασης OpenDocument (.otp), το οποίο αντιπροσωπεύει αρχεία προτύπων παρουσίασης που δημιουργούνται από εφαρμογές στο πρότυπο μορφής OASIS OpenDocument. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Αντιπροσωπεύει ένα λογιστικό φύλλο Excel (.xls), το οποίο αντιπροσωπεύει το Excel Binary File Format. Τέτοια αρχεία μπορούν να δημιουργηθούν από το Microsoft Excel καθώς και από άλλα παρόμοια προγράμματα λογιστικών φύλλων όπως το OpenOffice Calc ή το Apple Numbers. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### EXCEL_2003_XML {#EXCEL-2003-XML}
```
public static final FileType EXCEL_2003_XML
```


Αντιπροσωπεύει ένα Excel 2003 XML (SpreadsheetML) (.xml), το οποίο αντιπροσωπεύει το Excel Binary File Format. Τέτοια αρχεία μπορούν να δημιουργηθούν από το Microsoft Excel καθώς και από άλλα παρόμοια προγράμματα λογιστικών φύλλων όπως το OpenOffice Calc ή το Apple Numbers. Μάθετε περισσότερα για αυτό το φορμάτ αρχείου [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xls

### NUMBERS {#NUMBERS}
```
public static final FileType NUMBERS
```


Αντιπροσωπεύει το Apple Numbers (.numbers), το οποίο αντιπροσωπεύει μια δυαδική μορφή αρχείου παρόμοια με το Excel. Τέτοια αρχεία μπορούν να δημιουργηθούν από την εφαρμογή Apple Numbers. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://fileinfo.com/extension/numbers

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Αντιπροσωπεύει ένα Microsoft Excel Open XML Spreadsheet (.xlsx), το οποίο είναι μια γνωστή μορφή για έγγραφα Microsoft Excel που εισήχθη από τη Microsoft με την κυκλοφορία του Microsoft Office 2007. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Αντιπροσωπεύει ένα Excel Open XML Macro-Enabled Spreadsheet (.xlsm), το οποίο είναι ένας τύπος αρχείου λογιστικού φύλλου που υποστηρίζει μακροεντολές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Αντιπροσωπεύει ένα Excel Binary Spreadsheet (.xlsb), το οποίο καθορίζει τη μορφή Excel Binary File Format. Είναι μια συλλογή εγγραφών και δομών που καθορίζουν το περιεχόμενο του βιβλίου εργασίας Excel. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Αντιπροσωπεύει ένα αρχείο Comma Separated Values (.csv), το οποίο αντιπροσωπεύει αρχεία απλού κειμένου που περιέχουν εγγραφές δεδομένων με τιμές χωρισμένες με κόμμα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Αντιπροσωπεύει ένα αρχείο Tab Separated Values (.tsv), το οποίο αντιπροσωπεύει δεδομένα χωρισμένα με στηλοθέτες σε μορφή απλού κειμένου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


Αντιπροσωπεύει ένα OpenDocument Spreadsheet (.ods), το οποίο σημαίνει μορφή εγγράφου OpenDocument Spreadsheet που είναι επεξεργάσιμη από τον χρήστη. Τα δεδομένα αποθηκεύονται μέσα σε αρχεία ODF σε σειρές και στήλες. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ods

### FODS {#FODS}
```
public static final FileType FODS
```


Αντιπροσωπεύει ένα OpenDocument Flat XML Spreadsheet (.fods). Είναι μια μορφή εγγράφου λογιστικού φύλλου βασισμένη σε XML που χρησιμοποιείται από το OpenOffice και το LibreOffice. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/spreadsheet/fods

### OTS {#OTS}
```
public static final FileType OTS
```


Αντιπροσωπεύει ένα OpenDocument Spreadsheet Template (.ots). Είναι μια μορφή προτύπου εγγράφου που χρησιμοποιείται από το OpenOffice και το LibreOffice για λογιστικά φύλλα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/spreadsheet/ots

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Αντιπροσωπεύει ένα Microsoft Excel Add-in (.xlam). Είναι μια μορφή αρχείου που χρησιμοποιείται από το Microsoft Excel για τη δημιουργία πρόσθετων με προσαρμοσμένη λειτουργικότητα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://fileinfo.com/extension/xlam

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Αντιπροσωπεύει ένα Microsoft Excel Macro-Enabled Template (.xltm), το οποίο αντιπροσωπεύει αρχεία που δημιουργούνται από το Microsoft Excel ως πρότυπα με μακροεντολές. Τα αρχεία XLTM είναι παρόμοια με τα XLTX στη δομή, εκτός από το ότι τα τελευταία δεν υποστηρίζουν τη δημιουργία προτύπων με μακροεντολές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltm

### XLT {#XLT}
```
public static final FileType XLT
```


Αντιπροσωπεύει ένα Microsoft Excel Template (.xlt), το οποίο είναι αρχεία προτύπου που δημιουργούνται με το Microsoft Excel, μια εφαρμογή λογιστικού φύλλου που αποτελεί μέρος της σουίτας Microsoft Office. Το Microsoft Office 97-2003 υποστήριζε τη δημιουργία νέων αρχείων XLT καθώς και το άνοιγμά τους. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xlt

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Αντιπροσωπεύει ένα Excel Open XML Spreadsheet Template (.xltx), το οποίο αντιπροσωπεύει πρότυπα Microsoft Excel βασισμένα στις προδιαγραφές μορφής αρχείου Office OpenXML. Χρησιμοποιείται για τη δημιουργία ενός τυπικού αρχείου προτύπου που μπορεί να χρησιμοποιηθεί για τη δημιουργία αρχείων XLSX με τις ίδιες ρυθμίσεις που καθορίζονται στο αρχείο XLTX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/spreadsheet/xltx

### SXC {#SXC}
```
public static final FileType SXC
```


Αντιπροσωπεύει ένα StarOffice Calc Spreadsheet (.sxc). Είναι ένα έγγραφο λογιστικού φύλλου που δημιουργήθηκε με το StarOffice Calc, ένα πρόγραμμα λογιστικού φύλλου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/spreadsheet/sxc

### MPP {#MPP}
```
public static final FileType MPP
```


Αντιπροσωπεύει ένα Microsoft Project File (.mpp), το οποίο είναι ένα αρχείο δεδομένων Microsoft Project που αποθηκεύει πληροφορίες σχετικές με τη διαχείριση έργων με ενσωματωμένο τρόπο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/project-management/mpp

### MPT {#MPT}
```
public static final FileType MPT
```


Αντιπροσωπεύει ένα Microsoft Project Template (.mpt), το οποίο περιέχει βασικές πληροφορίες και δομή μαζί με ρυθμίσεις εγγράφου για τη δημιουργία αρχείων .MPP. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/project-management/mpt

### MPX {#MPX}
```
public static final FileType MPX
```


Αντιπροσωπεύει ένα Microsoft Project Exchange file (.mpx), το οποίο είναι μια μορφή αρχείου ASCII για τη μεταφορά πληροφοριών έργου μεταξύ Microsoft Project (MSP) και άλλων εφαρμογών που υποστηρίζουν τη μορφή αρχείου MPX, όπως Primavera Project Planner, Sciforma και Timerline Precision Estimating. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/project-management/mpx

### AS {#AS}
```
public static final FileType AS
```


Αντιπροσωπεύει ένα ActionScript File (.as). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/programming/as

### AS_3 {#AS-3}
```
public static final FileType AS_3
```


Αντιπροσωπεύει ένα ActionScript File (.as3). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://datatypes.net/open-as3-files

### ASM {#ASM}
```
public static final FileType ASM
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα γλώσσας Assembly (.asm). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://docs.fileformat.com/cad/asm

### BAT {#BAT}
```
public static final FileType BAT
```


Αντιπροσωπεύει ένα αρχείο παρτίδας DOS (.bat). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://docs.fileformat.com/executable/bat

### C {#C}
```
public static final FileType C
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα C/C++ (.c). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/programming/c

### CC {#CC}
```
public static final FileType CC
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα C++ (.cc). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://docs.fileformat.com/programming/cc

### CMAKE {#CMAKE}
```
public static final FileType CMAKE
```


Αντιπροσωπεύει ένα αρχείο CMake (.cmake). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/programming/cmake

### CPP {#CPP}
```
public static final FileType CPP
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα C++ (.cpp). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/programming/cpp

### CS {#CS}
```
public static final FileType CS
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα C\# (.cs), το οποίο είναι ένα αρχείο πηγαίου κώδικα για τη γλώσσα προγραμματισμού C\#. Εισήχθη από τη Microsoft για χρήση με το .NET Framework. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/programming/cs

### VB {#VB}
```
public static final FileType VB
```


Αντιπροσωπεύει ένα αρχείο στοιχείου έργου Visual Basic (.vb), το οποίο είναι ένα αρχείο πηγαίου κώδικα που δημιουργήθηκε στη γλώσσα Visual Basic. Δημιουργήθηκε από τη Microsoft για την ανάπτυξη εφαρμογών .NET. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/programming/vb

### CSS {#CSS}
```
public static final FileType CSS
```


Αντιπροσωπεύει ένα αρχείο Cascading Style Sheet (.css). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/web/css

### CXX {#CXX}
```
public static final FileType CXX
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα C++ (.cxx). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://docs.fileformat.com/programming/cxx

### DIFF {#DIFF}
```
public static final FileType DIFF
```


Αντιπροσωπεύει ένα αρχείο διόρθωσης (.diff). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://docs.fileformat.com/programming/diff

### ERB {#ERB}
```
public static final FileType ERB
```


Αντιπροσωπεύει ένα σενάριο Ruby ERB (.erb). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://docs.fileformat.com/programming/erb

### GROOVY {#GROOVY}
```
public static final FileType GROOVY
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα Groovy (.groovy). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/programming/groovy

### H {#H}
```
public static final FileType H
```


Αντιπροσωπεύει ένα αρχείο κεφαλίδας C/C++/Objective-C (.h). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://docs.fileformat.com/programming/h

### HAML {#HAML}
```
public static final FileType HAML
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα Haml (.haml). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/programming/haml

### HH {#HH}
```
public static final FileType HH
```


Αντιπροσωπεύει ένα αρχείο κεφαλίδας C++ (.hh). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://docs.fileformat.com/programming/hh

### JAVA {#JAVA}
```
public static final FileType JAVA
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα Java (.java). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/programming/java

### JS {#JS}
```
public static final FileType JS
```


Αντιπροσωπεύει ένα αρχείο JavaScript (.js). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://docs.fileformat.com/web/js

### JSON {#JSON}
```
public static final FileType JSON
```


Αντιπροσωπεύει ένα αρχείο JavaScript Object Notation (.json). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://docs.fileformat.com/web/json

### LESS {#LESS}
```
public static final FileType LESS
```


Αντιπροσωπεύει ένα αρχείο LESS Style Sheet (.less). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/web/less

### LOG {#LOG}
```
public static final FileType LOG
```


Αντιπροσωπεύει ένα αρχείο καταγραφής (.log). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://docs.fileformat.com/database/log

### M {#M}
```
public static final FileType M
```


Αντιπροσωπεύει ένα αρχείο υλοποίησης Objective-C (.m). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://fileinfo.com/extension/m

### MAKE {#MAKE}
```
public static final FileType MAKE
```


Αντιπροσωπεύει ένα σενάριο Makefile του Xcode (.make). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://docs.fileformat.com/programming/make

### MD {#MD}
```
public static final FileType MD
```


Αντιπροσωπεύει ένα αρχείο τεκμηρίωσης Markdown (.md). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://docs.fileformat.com/word-processing/md

### ML {#ML}
```
public static final FileType ML
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα ML (.ml). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/programming/ml

### MM {#MM}
```
public static final FileType MM
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα Objective-C++ (.mm). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/programming/mm

### PHP {#PHP}
```
public static final FileType PHP
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα PHP (.php). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/programming/php

### PL {#PL}
```
public static final FileType PL
```


Αντιπροσωπεύει ένα script Perl (.pl). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/programming/pl

### PROPERTIES {#PROPERTIES}
```
public static final FileType PROPERTIES
```


Αντιπροσωπεύει ένα αρχείο ιδιοτήτων Java (.properties). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://fileinfo.com/extension/properties

### PY {#PY}
```
public static final FileType PY
```


Αντιπροσωπεύει ένα script Python (.py). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/programming/py

### RB {#RB}
```
public static final FileType RB
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα Ruby (.rb). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/programming/rb

### RST {#RST}
```
public static final FileType RST
```


Αντιπροσωπεύει ένα αρχείο reStructuredText (.rst). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/programming/rst

### SASS {#SASS}
```
public static final FileType SASS
```


Αντιπροσωπεύει ένα αρχείο Syntactically Awesome StyleSheets (.sass). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/web/sass

### SCALA {#SCALA}
```
public static final FileType SCALA
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα Scala (.scala). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/programming/scala

### SCM {#SCM}
```
public static final FileType SCM
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα Scheme (.scm). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/programming/scm

### SCRIPT {#SCRIPT}
```
public static final FileType SCRIPT
```


Αντιπροσωπεύει ένα γενικό αρχείο script (.script). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/programming/script

### SH {#SH}
```
public static final FileType SH
```


Αντιπροσωπεύει ένα script Bash Shell (.sh). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/cs/programming/sh

### SML {#SML}
```
public static final FileType SML
```


Αντιπροσωπεύει ένα αρχείο πηγαίου κώδικα Standard ML (.sml). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://fileinfo.com/extension/sml

### SQL {#SQL}
```
public static final FileType SQL
```


Αντιπροσωπεύει ένα αρχείο δεδομένων Structured Query Language (.sql). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/database/sql

### VIM {#VIM}
```
public static final FileType VIM
```


Αντιπροσωπεύει ένα αρχείο ρυθμίσεων Vim (.vim). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://fileinfo.com/extension/vim

### YAML {#YAML}
```
public static final FileType YAML
```


Αντιπροσωπεύει ένα έγγραφο YAML (.yaml). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/programming/yaml

### DOC {#DOC}
```
public static final FileType DOC
```


Αντιπροσωπεύει ένα έγγραφο Microsoft Word (.doc). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Αντιπροσωπεύει ένα έγγραφο Microsoft Word Open XML (.docx). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/word-processing/docx

### CHM {#CHM}
```
public static final FileType CHM
```


Αντιπροσωπεύει ένα αρχείο Microsoft Compiled HTML Help (.chm). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/web/chm

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Αντιπροσωπεύει ένα έγγραφο Word Open XML Macro-Enabled (.docm). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Αντιπροσωπεύει ένα πρότυπο εγγράφου Word (.dot). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Αντιπροσωπεύει ένα πρότυπο εγγράφου Word Open XML (.dotx). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Αντιπροσωπεύει ένα πρότυπο εγγράφου Word Open XML Macro-Enabled (.dotm). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Αντιπροσωπεύει ένα αρχείο Rich Text Format (.rtf). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Αντιπροσωπεύει ένα αρχείο απλού κειμένου (.txt). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://wiki.fileformat.com/word-processing/txt

### ODT {#ODT}
```
public static final FileType ODT
```


Αντιπροσωπεύει ένα έγγραφο κειμένου OpenDocument (.odt). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


Αντιπροσωπεύει ένα πρότυπο εγγράφου OpenDocument (.ott). Είναι ένα έγγραφο προτύπου που δημιουργείται σύμφωνα με το πρότυπο μορφής OpenDocument του OASIS. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/word-processing/ott

### VCF {#VCF}
```
public static final FileType VCF
```


Αντιπροσωπεύει ένα αρχείο vCard (.vcf), το οποίο είναι μια ψηφιακή μορφή αρχείου για αποθήκευση πληροφοριών επαφών. Χρησιμοποιείται ευρέως για ανταλλαγή δεδομένων μεταξύ δημοφιλών εφαρμογών ανταλλαγής πληροφοριών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://wiki.fileformat.com/email/vcf

### AI {#AI}
```
public static final FileType AI
```


Αντιπροσωπεύει ένα αρχείο Adobe Illustrator (.ai), το οποίο είναι μια μορφή αρχείου για σχέδια Adobe Illustrator. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://docs.fileformat.com/image/ai

### PSM1 {#PSM1}
```
public static final FileType PSM1
```


Αντιπροσωπεύει ένα αρχείο μονάδας σεναρίου PowerShell (.psm1). Είναι μια μορφή αρχείου για σενάρια μονάδων PowerShell. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://fileinfo.com/extension/psm1

### PS1 {#PS1}
```
public static final FileType PS1
```


Αντιπροσωπεύει ένα αρχείο σεναρίου PowerShell (.ps1). Είναι μια μορφή αρχείου για αρχεία Cmdlet του Windows PowerShell. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://fileinfo.com/extension/ps1

### PSD1 {#PSD1}
```
public static final FileType PSD1
```


Αντιπροσωπεύει ένα αρχείο μανιφέστου μονάδας σεναρίου PowerShell (.psd1). Είναι μια μορφή αρχείου για σενάρια μανιφέστου μονάδας PowerShell. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ][].


[here]: https://fileinfo.com/extension/psd1

### values() {#values--}
```
public static FileType[] values()
```




**Returns:**
com.groupdocs.viewer.FileType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static FileType valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Αντιστοιχίζει μια επέκταση αρχείου σε τύπο αρχείου.

Αυτή η μέθοδος δέχεται μια επέκταση αρχείου, με ή χωρίς την τελεία ".", και επιστρέφει τον αντίστοιχο τύπο αρχείου εάν υποστηρίζεται. Εάν ο τύπος αρχείου δεν υποστηρίζεται, επιστρέφει τον προεπιλεγμένο τύπο αρχείου [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| extension | java.lang.String | Η επέκταση αρχείου με ή χωρίς την τελεία ".". |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromFilePath(String filePath) {#fromFilePath-java.lang.String-}
```
public static FileType fromFilePath(String filePath)
```


Εξάγει την επέκταση αρχείου από όνομα αρχείου ή διαδρομή αρχείου και την αντιστοιχίζει σε τύπο αρχείου.

Εάν ο τύπος αρχείου υποστηρίζεται, η μέθοδος επιστρέφει τον αντίστοιχο  FileType , διαφορετικά επιστρέφει τον προεπιλεγμένο τύπο αρχείου [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Το όνομα αρχείου ή η διαδρομή αρχείου. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if supported, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromMediaType(String mediaType) {#fromMediaType-java.lang.String-}
```
public static FileType fromMediaType(String mediaType)
```


Αντιστοιχίζει έναν τύπο μέσου αρχείου σε έναν τύπο αρχείου. Για παράδειγμα, το 'application/pdf' θα αντιστοιχιστεί στο [PDF](../../com.groupdocs.viewer/filetype\#PDF).

Αυτή η μέθοδος δέχεται έναν τύπο μέσου αρχείου ως είσοδο και τον αντιστοιχίζει στον αντίστοιχο  FileType . Εάν ο τύπος μέσου υποστηρίζεται, η μέθοδος επιστρέφει τον αντίστοιχο τύπο αρχείου. Εάν ο τύπος μέσου δεν υποστηρίζεται, επιστρέφει τον προεπιλεγμένο τύπο αρχείου [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mediaType | java.lang.String | Ο τύπος μέσου αρχείου, π.χ., 'application/pdf'. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the corresponding file type if found, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream stream)
```


Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου.

Αυτή η μέθοδος δέχεται μια ροή εισόδου που αντιπροσωπεύει ένα αρχείο και προσπαθεί να εντοπίσει τον τύπο αρχείου του αναλύοντας την υπογραφή αρχείου. Η υπογραφή αρχείου είναι μια μοναδική ακολουθία byte στην αρχή του αρχείου που υποδεικνύει τον τύπο του. Η μέθοδος διαβάζει την υπογραφή αρχείου από τη ροή εισόδου και τη συγκρίνει με γνωστές υπογραφές αρχείων υποστηριζόμενων τύπων. Εάν βρεθεί αντιστοίχιση, η μέθοδος επιστρέφει τον αντίστοιχο τύπο αρχείου. Εάν δεν βρεθεί αντιστοίχιση, επιστρέφει τον προεπιλεγμένο τύπο αρχείου [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή εισόδου που αντιπροσωπεύει το αρχείο. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password) {#fromStream-java.io.InputStream-java.lang.String-}
```
public static FileType fromStream(InputStream stream, String password)
```


Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου.

Αυτή η μέθοδος αναλύει την υπογραφή αρχείου, η οποία είναι μια μοναδική ακολουθία byte στην αρχή του αρχείου, για να καθορίσει τον τύπο αρχείου. Διαβάζει την υπογραφή αρχείου από τη δοθείσα ροή εισόδου και τη συγκρίνει με γνωστές υπογραφές αρχείων υποστηριζόμενων τύπων. Εάν βρεθεί αντιστοίχιση, η μέθοδος επιστρέφει τον αντίστοιχο τύπο αρχείου. Εάν δεν βρεθεί αντιστοίχιση, επιστρέφει τον προεπιλεγμένο τύπο αρχείου [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

Εάν το αρχείο είναι κρυπτογραφημένο και απαιτεί κωδικό πρόσβασης για άνοιγμα, ο κωδικός πρόσβασης πρέπει να παρασχεθεί ως παράμετρος σε αυτή τη μέθοδο. Ο κωδικός πρόσβασης θα χρησιμοποιηθεί για την αποκρυπτογράφηση του αρχείου και την ανάλυση της υπογραφής του για τον καθορισμό του τύπου αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή εισόδου που αντιπροσωπεύει το αρχείο. |
| password | java.lang.String | Ο κωδικός πρόσβασης για το άνοιγμα του αρχείου. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, ILogger logger) {#fromStream-java.io.InputStream-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, ILogger logger)
```


Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου.

Αυτή η μέθοδος αναλύει την υπογραφή αρχείου, η οποία είναι μια μοναδική ακολουθία byte στην αρχή του αρχείου, για να καθορίσει τον τύπο αρχείου. Διαβάζει την υπογραφή αρχείου από τη δοθείσα ροή εισόδου και τη συγκρίνει με γνωστές υπογραφές αρχείων υποστηριζόμενων τύπων. Εάν βρεθεί αντιστοίχιση, η μέθοδος επιστρέφει τον αντίστοιχο τύπο αρχείου. Εάν δεν βρεθεί αντιστοίχιση, επιστρέφει τον προεπιλεγμένο τύπο αρχείου [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

Μπορεί να παρασχεθεί ένας καταγραφέας για την καταγραφή οποιασδήποτε σχετικής πληροφορίας ή σφαλμάτων κατά τη διαδικασία ανίχνευσης τύπου αρχείου. Ο καταγραφέας πρέπει να υλοποιεί τη διεπαφή **ILogger**. Εάν δεν παρασχεθεί καταγραφέας, η διαδικασία ανίχνευσης δεν θα παράγει καμία έξοδο καταγραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή εισόδου που αντιπροσωπεύει το αρχείο. |
| logger | com.groupdocs.foundation.logging.ILogger | Ο καταγραφέας για την καταγραφή πληροφοριών ή σφαλμάτων. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### fromStream(InputStream stream, String password, ILogger logger) {#fromStream-java.io.InputStream-java.lang.String-com.groupdocs.foundation.logging.ILogger-}
```
public static FileType fromStream(InputStream stream, String password, ILogger logger)
```


Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου.

Αυτή η μέθοδος αναλύει την υπογραφή αρχείου, η οποία είναι μια μοναδική ακολουθία byte στην αρχή του αρχείου, για να καθορίσει τον τύπο αρχείου. Διαβάζει την υπογραφή αρχείου από τη δοθείσα ροή εισόδου και τη συγκρίνει με γνωστές υπογραφές αρχείων υποστηριζόμενων τύπων. Εάν βρεθεί αντιστοίχιση, η μέθοδος επιστρέφει τον αντίστοιχο τύπο αρχείου. Εάν δεν βρεθεί αντιστοίχιση, επιστρέφει τον προεπιλεγμένο τύπο αρχείου [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN).

Μπορεί να δοθεί κωδικός πρόσβασης εάν το αρχείο είναι κρυπτογραφημένο ή προστατευμένο. Ο κωδικός πρόσβασης θα χρησιμοποιηθεί για το άνοιγμα του αρχείου πριν από την ανάλυση της υπογραφής του αρχείου. Εάν το αρχείο δεν απαιτεί κωδικό πρόσβασης, αυτή η παράμετρος μπορεί να οριστεί σε null.

Μπορεί να παρασχεθεί ένας καταγραφέας για την καταγραφή οποιασδήποτε σχετικής πληροφορίας ή σφαλμάτων κατά τη διαδικασία ανίχνευσης τύπου αρχείου. Ο καταγραφέας πρέπει να υλοποιεί τη διεπαφή **ILogger**. Εάν δεν παρασχεθεί καταγραφέας, η διαδικασία ανίχνευσης δεν θα παράγει καμία έξοδο καταγραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή εισόδου που αντιπροσωπεύει το αρχείο. |
| password | java.lang.String | Ο κωδικός πρόσβασης για το άνοιγμα του αρχείου. |
| logger | com.groupdocs.foundation.logging.ILogger | Ο καταγραφέας για την καταγραφή πληροφοριών ή σφαλμάτων. |

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the detected file type if successful, otherwise the default [UNKNOWN](../../com.groupdocs.viewer/filetype\#UNKNOWN) file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Ανακτά τους υποστηριζόμενους τύπους αρχείων.

Αυτή η μέθοδος επιστρέφει μια ακολουθία όλων των τύπων αρχείων που υποστηρίζονται από το σύστημα. Οι τύποι αρχείων αντιπροσωπεύουν διάφορες μορφές εγγράφων που μπορούν να υποβληθούν σε επεξεργασία ή αναγνώριση από το σύστημα.

 **Learn more**

 *  Learn more about the supported document formats: [Full list of supported file formats][]


[Full list of supported file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/

**Returns:**
java.util.List<com.groupdocs.viewer.FileType> - μια ακολουθία των υποστηριζόμενων τύπων αρχείων.
### detectCharset(String filePath) {#detectCharset-java.lang.String-}
```
public static Charset detectCharset(String filePath)
```


Προσπαθεί να εντοπίσει το σύνολο χαρακτήρων των αρχείων κειμένου [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) και [CSV](../../com.groupdocs.viewer/filetype\#CSV) με βάση τη διαδρομή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| filePath | java.lang.String | Το όνομα αρχείου ή η διαδρομή αρχείου. |

**Returns:**
java.nio.charset.Charset - Charset ή null όταν αποτυγχάνει η ανίχνευση του charset του αρχείου.

**Example:**

```
Charset charset = FileType.detectCharset("message.txt");
```
### detectCharset(InputStream stream) {#detectCharset-java.io.InputStream-}
```
public static Charset detectCharset(InputStream stream)
```


Προσπαθεί να εντοπίσει το σύνολο χαρακτήρων των αρχείων κειμένου [TXT](../../com.groupdocs.viewer/filetype\#TXT), [TSV](../../com.groupdocs.viewer/filetype\#TSV) και [CSV](../../com.groupdocs.viewer/filetype\#CSV) με βάση το ρεύμα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | java.io.InputStream | Η ροή αρχείου. |

**Returns:**
java.nio.charset.Charset - Charset ή null όταν αποτυγχάνει η ανίχνευση του charset του αρχείου.

**Example:**

```
InputStream stream = new FileInputStream("message.txt");
 Charset charset = FileType.detectCharset(stream);
```
### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Λαμβάνει το όνομα της μορφής αρχείου, π.χ., "Microsoft Word Document".

**Returns:**
java.lang.String - το όνομα της μορφής αρχείου.
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Λαμβάνει το επίθημα επέκτασης αρχείου (συμπεριλαμβανομένου του σημείου "."), π.χ., ".doc".

**Returns:**
java.lang.String - το επίθημα της επέκτασης αρχείου.
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια αναπαράσταση σε συμβολοσειρά του τρέχοντος αντικειμένου.

**Returns:**
java.lang.String - μια αναπαράσταση σε συμβολοσειρά του τρέχοντος αντικειμένου.
