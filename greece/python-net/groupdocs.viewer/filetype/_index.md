---
title: "Κλάση FileType"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει έναν τύπο αρχείου και παρέχει μεθόδους για την απόκτηση της λίστας όλων των τύπων αρχείων που υποστηρίζονται από το GroupDocs.Viewer."
type: docs
url: /el/python-net/groupdocs.viewer/filetype/
is_root: false
weight: 10
---


## FileType class

Αντιπροσωπεύει έναν τύπο αρχείου και παρέχει μεθόδους για την απόκτηση της λίστας όλων των τύπων αρχείων που υποστηρίζονται από το GroupDocs.Viewer.

Ο τύπος FileType εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/) | Αρχικοποιεί μια νέα παρουσία του [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [__init__](/viewer/python-net/groupdocs.viewer/filetype/__init__/#file_format-extension) | Αρχικοποιεί μια νέα παρουσία FileType. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#file_path) | Ανιχνεύει την κωδικοποίηση των αρχείων κειμένου TXT, TSV και CSV με βάση τη διαδρομή. |
| [detect_encoding](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding/#stream) | Προσπαθεί να ανιχνεύσει την κωδικοποίηση των αρχείων κειμένου (TXT, TSV, CSV) από μια ροή. |
| [detect_encoding_file](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_file/) |  |
| [detect_encoding_stream](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_stream/) |  |
| [detect_encoding_streams](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_streams/) |  |
| [detect_encoding_string](/viewer/python-net/groupdocs.viewer/filetype/detect_encoding_string/) |  |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#other) | Καθορίζει εάν το τρέχον [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) είναι το ίδιο με το καθορισμένο [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [equals](/viewer/python-net/groupdocs.viewer/filetype/equals/#obj) | Καθορίζει εάν το τρέχον [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) είναι το ίδιο με το καθορισμένο αντικείμενο. |
| [equals_file_type](/viewer/python-net/groupdocs.viewer/filetype/equals_file_type/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer/filetype/equals_object/) |  |
| [from_extension](/viewer/python-net/groupdocs.viewer/filetype/from_extension/#extension) | Αντιστοιχίζει την επέκταση αρχείου με τον τύπο αρχείου. |
| [from_file_path](/viewer/python-net/groupdocs.viewer/filetype/from_file_path/#file_path) | Εξάγει την επέκταση αρχείου και την αντιστοιχίζει σε έναν τύπο αρχείου. |
| [from_media_type](/viewer/python-net/groupdocs.viewer/filetype/from_media_type/#media_type) | Αντιστοιχίζει έναν τύπο μέσου αρχείου σε ένα [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/) (π.χ., 'application/pdf' αντιστοιχεί στο [`FileType.pdf`](/viewer/python-net/groupdocs.viewer/filetype/pdf/)). |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream) | Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password) | Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-logger) | Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου. |
| [from_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream/#stream-password-logger) | Ανιχνεύει τον τύπο αρχείου διαβάζοντας την υπογραφή του αρχείου. |
| [from_stream_file](/viewer/python-net/groupdocs.viewer/filetype/from_stream_file/) |  |
| [from_stream_stream](/viewer/python-net/groupdocs.viewer/filetype/from_stream_stream/) |  |
| [from_stream_streams](/viewer/python-net/groupdocs.viewer/filetype/from_stream_streams/) |  |
| [from_stream_string](/viewer/python-net/groupdocs.viewer/filetype/from_stream_string/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer/filetype/get_hash_code/) | Επιστρέφει τον κωδικό κατακερματισμού για το τρέχον αντικείμενο [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/). |
| [get_supported_file_types](/viewer/python-net/groupdocs.viewer/filetype/get_supported_file_types/) | Ανακτά τους υποστηριζόμενους τύπους αρχείων. |
| [to_string](/viewer/python-net/groupdocs.viewer/filetype/to_string/) | Επιστρέφει ένα str που αντιπροσωπεύει το τρέχον αντικείμενο. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [extension](/viewer/python-net/groupdocs.viewer/filetype/extension/) | Το επίθημα του ονόματος αρχείου (συμπεριλαμβανομένου του σημείου ".") π.χ. ".doc". |
| [file_format](/viewer/python-net/groupdocs.viewer/filetype/file_format/) | Το όνομα του τύπου αρχείου π.χ. "Microsoft Word Document". |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [UNKNOWN](/viewer/python-net/groupdocs.viewer/filetype/unknown/) | Αντιπροσωπεύει άγνωστο τύπο αρχείου. |
| [ZIP](/viewer/python-net/groupdocs.viewer/filetype/zip/) | Το συμπιεσμένο αρχείο (.zip) αντιπροσωπεύει αρχεία που μπορούν να περιέχουν ένα ή περισσότερα αρχεία ή καταλόγους. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [TAR](/viewer/python-net/groupdocs.viewer/filetype/tar/) | Το ενοποιημένο αρχείο Unix (.tar) είναι αρχεία που δημιουργούνται με βοηθητικό πρόγραμμα βασισμένο σε Unix για τη συλλογή ενός ή περισσότερων αρχείων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [XZ](/viewer/python-net/groupdocs.viewer/filetype/xz/) | Το αρχείο XZ (.xz) είναι αρχείο συμπιεσμένο με αλγόριθμο υψηλής αναλογίας συμπίεσης βασισμένο στον αλγόριθμο LZMA. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [TXZ](/viewer/python-net/groupdocs.viewer/filetype/txz/) | Το ενοποιημένο αρχείο Unix (.txz, .tar.xz) είναι αρχεία που δημιουργούνται με βοηθητικό πρόγραμμα βασισμένο σε Unix για τη συλλογή ενός ή περισσότερων αρχείων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [TARXZ](/viewer/python-net/groupdocs.viewer/filetype/tarxz/) | Το ενοποιημένο αρχείο Unix (.txz, .tar.xz) είναι αρχεία που δημιουργούνται με βοηθητικό πρόγραμμα βασισμένο σε Unix για τη συλλογή ενός ή περισσότερων αρχείων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [TGZ](/viewer/python-net/groupdocs.viewer/filetype/tgz/) | Το ενοποιημένο αρχείο Unix (.tgz, .tar.gz) είναι αρχεία που δημιουργούνται με βοηθητικό πρόγραμμα βασισμένο σε Unix για τη συλλογή ενός ή περισσότερων αρχείων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [TARGZ](/viewer/python-net/groupdocs.viewer/filetype/targz/) | Το ενοποιημένο αρχείο Unix (.tgz, .tar.gz) είναι αρχεία που δημιουργούνται με βοηθητικό πρόγραμμα βασισμένο σε Unix για τη συλλογή ενός ή περισσότερων αρχείων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [BZ2](/viewer/python-net/groupdocs.viewer/filetype/bz2/) | Το συμπιεσμένο αρχείο Bzip2 (.bz2) είναι συμπιεσμένα αρχεία που δημιουργούνται χρησιμοποιώντας τη μέθοδο ανοιχτού κώδικα BZIP2, κυρίως σε συστήματα UNIX ή Linux. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [RAR](/viewer/python-net/groupdocs.viewer/filetype/rar/) | Το Roshal ARchive (.rar) είναι συμπιεσμένα αρχεία που δημιουργούνται χρησιμοποιώντας τη μέθοδο συμπίεσης RAR (WINRAR). Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [GZ](/viewer/python-net/groupdocs.viewer/filetype/gz/) | Το Gnu Zipped File (.gz) είναι συμπιεσμένα αρχεία που δημιουργούνται με την εφαρμογή συμπίεσης gzip. Μπορεί να περιέχει πολλαπλά συμπιεσμένα αρχεία και χρησιμοποιείται συνήθως σε συστήματα UNIX και Linux. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [GZIP](/viewer/python-net/groupdocs.viewer/filetype/gzip/) | Το Gnu Zipped File (.gzip) εισήχθη ως δωρεάν βοηθητικό πρόγραμμα για την αντικατάσταση του προγράμματος Compress που χρησιμοποιείται σε συστήματα Unix. Τέτοια αρχεία μπορούν να ανοιχτούν και να εξαχθούν με διάφορες εφαρμογές όπως το WinZip, το οποίο είναι διαθέσιμο τόσο για Windows όσο και για MacOS. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [SEVEN_ZIP](/viewer/python-net/groupdocs.viewer/filetype/seven_zip/) | Το 7Zip (.7z, .7zip) είναι δωρεάν ανοιχτού κώδικα πρόγραμμα αρχειοθέτησης με συμπίεση LZMA και LZMA2. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [CPIO](/viewer/python-net/groupdocs.viewer/filetype/cpio/) | Το Cpio είναι ένα γενικό βοηθητικό πρόγραμμα αρχειοθέτησης αρχείων και η σχετική μορφή αρχείου του. Εγκαθίσταται κυρίως σε λειτουργικά συστήματα υπολογιστών τύπου Unix. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [ZSTANDARD](/viewer/python-net/groupdocs.viewer/filetype/zstandard/) | Το αρχείο ZST είναι ένα συμπιεσμένο αρχείο που δημιουργείται με τον αλγόριθμο συμπίεσης Zstandard (zstd). Είναι ένα συμπιεσμένο αρχείο που παράγεται με ασύμπτωτη (lossless) συμπίεση από τον αλγόριθμο. Τα αρχεία ZST μπορούν να χρησιμοποιηθούν για τη συμπίεση διαφόρων τύπων αρχείων όπως βάσεις δεδομένων, συστήματα αρχείων, δίκτυα και παιχνίδια. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [TZST](/viewer/python-net/groupdocs.viewer/filetype/tzst/) | Τα αρχεία TZST (.tar.zst, .tzst) είναι αρχεία Zstandard (ZST), τα οποία εσωτερικά περιέχουν ένα ενοποιημένο αρχείο Unix (Tar), δημιουργημένο με βοηθητικό πρόγραμμα βασισμένο σε Unix για τη συλλογή ενός ή περισσότερων αρχείων. |
| [TAR_ZST](/viewer/python-net/groupdocs.viewer/filetype/tar_zst/) | Τα αρχεία TZST (.tar.zst, .tzst) είναι αρχεία Zstandard (ZST), τα οποία εσωτερικά περιέχουν ένα ενοποιημένο αρχείο Unix (Tar), δημιουργημένο με βοηθητικό πρόγραμμα βασισμένο σε Unix για τη συλλογή ενός ή περισσότερων αρχείων. |
| [ISO](/viewer/python-net/groupdocs.viewer/filetype/iso/) | Η εικόνα οπτικού δίσκου ISO είναι ένα μη συμπιεσμένο αρχείο εικόνας δίσκου που αντιπροσωπεύει το περιεχόμενο ολόκληρων δεδομένων σε έναν οπτικό δίσκο όπως CD ή DVD, βάσει του προτύπου ISO-9660. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [LHA](/viewer/python-net/groupdocs.viewer/filetype/lha/) | Το LHA ή LZH είναι ένα δωρεάν βοηθητικό πρόγραμμα συμπίεσης και η σχετική μορφή αρχείου του. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [CAB](/viewer/python-net/groupdocs.viewer/filetype/cab/) | Το Cabinet (ή CAB) είναι μια μορφή αρχείου αρχειοθέτησης για το Microsoft Windows. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [DXF](/viewer/python-net/groupdocs.viewer/filetype/dxf/) | Το Drawing Exchange Format File (.dxf) είναι μια ετικετοποιημένη αναπαράσταση δεδομένων αρχείου σχεδίου AutoCAD. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [DWG](/viewer/python-net/groupdocs.viewer/filetype/dwg/) | Το AutoCAD Drawing Database File (.dwg) αντιπροσωπεύει ιδιόκτητα δυαδικά αρχεία που χρησιμοποιούνται για την αποθήκευση δεδομένων σχεδίασης 2D και 3D. Όπως το DXF, που είναι αρχεία ASCII, το DWG αντιπροσωπεύει τη δυαδική μορφή αρχείου για σχέδια CAD (Computer Aided Design). Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [DWT](/viewer/python-net/groupdocs.viewer/filetype/dwt/) | Το AutoCAD Drawing Template (.dwt) είναι ένα πρότυπο αρχείου σχεδίου AutoCAD που χρησιμοποιείται ως εκκίνηση για τη δημιουργία σχεδίων που μπορούν να αποθηκευτούν ως αρχεία DWG. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [STL](/viewer/python-net/groupdocs.viewer/filetype/stl/) | Το Stereolithography File (.stl) είναι μια εναλλάξιμη μορφή αρχείου που αντιπροσωπεύει γεωμετρία επιφάνειας τριών διαστάσεων. Η μορφή αρχείου αυτή χρησιμοποιείται σε διάφορους τομείς όπως η γρήγορη πρωτοτυποποίηση, η 3D εκτύπωση και η υπολογιστική κατασκευή. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [IFC](/viewer/python-net/groupdocs.viewer/filetype/ifc/) | Το Industry Foundation Classes File (.ifc) είναι μια μορφή αρχείου που καθιερώνει διεθνή πρότυπα για την εισαγωγή και εξαγωγή αντικειμένων κτιρίων και των ιδιοτήτων τους. Αυτή η μορφή αρχείου παρέχει διαλειτουργικότητα μεταξύ διαφορετικών εφαρμογών λογισμικού. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [DWF](/viewer/python-net/groupdocs.viewer/filetype/dwf/) | Το Design Web Format File (.dwf) αντιπροσωπεύει σχέδιο 2D/3D σε συμπιεσμένη μορφή για προβολή, ανασκόπηση ή εκτύπωση αρχείων σχεδίου. Περιέχει γραφικά και κείμενο ως μέρος των δεδομένων σχεδίου και μειώνει το μέγεθος του αρχείου λόγω της συμπιεσμένης μορφής του. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [FBX](/viewer/python-net/groupdocs.viewer/filetype/fbx/) | Το Autodesk FBX Interchange File (FilmBoX) (.fbx) αντιπροσωπεύει μορφή 3D μοντέλου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [DWFX](/viewer/python-net/groupdocs.viewer/filetype/dwfx/) | Το Design Web Format File XPS (.dwfx) αντιπροσωπεύει σχέδιο 2D/3D ως έγγραφο XPS σε συμπιεσμένη μορφή για προβολή, ανασκόπηση ή εκτύπωση αρχείων σχεδίου. Περιέχει γραφικά και κείμενο ως μέρος των δεδομένων σχεδίου και μειώνει το μέγεθος του αρχείου λόγω της συμπιεσμένης μορφής του. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [DGN](/viewer/python-net/groupdocs.viewer/filetype/dgn/) | Το MicroStation Design File (.dgn) είναι σχέδια που δημιουργούνται και υποστηρίζονται από εφαρμογές CAD όπως το MicroStation και το Intergraph Interactive Graphics Design System. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [PLT](/viewer/python-net/groupdocs.viewer/filetype/plt/) | Το PLT (HPGL) (.plt) είναι ένα αρχείο σχεδιαστή βασισμένο σε διανύσματα που εισήχθη από την Autodesk, Inc. και περιέχει πληροφορίες για ένα συγκεκριμένο αρχείο CAD. Οι λεπτομέρειες σχεδίασης απαιτούν ακρίβεια και προσοχή στην παραγωγή, και η χρήση του αρχείου PLT εγγυάται αυτό καθώς όλες οι εικόνες εκτυπώνονται με γραμμές αντί για κουκκίδες. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [CF2](/viewer/python-net/groupdocs.viewer/filetype/cf2/) | Αρχείο Κοινής Μορφής Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [OBJ](/viewer/python-net/groupdocs.viewer/filetype/obj/) | Το Wavefront 3D Object File (.obj) είναι αρχείο 3D εικόνας που εισήχθη από την Wavefront Technologies. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [HPG](/viewer/python-net/groupdocs.viewer/filetype/hpg/) | PLT (HPGL) (.hpg) |
| [IGS](/viewer/python-net/groupdocs.viewer/filetype/igs/) | Initial Graphics Exchange Specification (IGES) (.igs) |
| [VSD](/viewer/python-net/groupdocs.viewer/filetype/vsd/) | Το Visio Drawing File (.vsd) είναι σχέδια που δημιουργούνται με την εφαρμογή Microsoft Visio για να αντιπροσωπεύουν ποικιλία γραφικών αντικειμένων και τη διασύνδεσή τους. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [VSDX](/viewer/python-net/groupdocs.viewer/filetype/vsdx/) | Το Visio Drawing (.vsdx) αντιπροσωπεύει το μορφότυπο αρχείου Microsoft Visio που εισήχθη από το Microsoft Office 2013 και μετά. Αναπτύχθηκε για να αντικαταστήσει το δυαδικό μορφότυπο αρχείου, .VSD, το οποίο υποστηρίζεται από προηγούμενες εκδόσεις του Microsoft Visio. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [VSS](/viewer/python-net/groupdocs.viewer/filetype/vss/) | Το Visio Stencil File (.vss) είναι αρχεία προτύπων που δημιουργήθηκαν με το Microsoft Visio 2007 και παλαιότερα. Τα αρχεία προτύπων παρέχουν αντικείμενα σχεδίασης που μπορούν να συμπεριληφθούν σε ένα σχέδιο Visio .VSD. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [VSSX](/viewer/python-net/groupdocs.viewer/filetype/vssx/) | Το Visio Stencil File (.vssx) είναι πρότυπα σχεδίασης που δημιουργήθηκαν με το Microsoft Visio 2013 και μεταγενέστερα. Το μορφότυπο αρχείου VSSX μπορεί να ανοιχτεί με το Visio 2013 και μεταγενέστερα. Τα αρχεία Visio είναι γνωστά για την αναπαράσταση μιας ποικιλίας στοιχείων σχεδίασης όπως συλλογή σχημάτων, συνδέσμων, διαγραμμάτων ροής, διάταξης δικτύου, διαγραμμάτων UML. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [VSDM](/viewer/python-net/groupdocs.viewer/filetype/vsdm/) | Το Visio Macro-Enabled Drawing (.vsdm) είναι αρχεία σχεδίασης που δημιουργήθηκαν με την εφαρμογή Microsoft Visio και υποστηρίζουν μακροεντολές. Τα αρχεία VSDM είναι σχεδιάσματα OPC/XML που είναι παρόμοια με τα VSDX, αλλά παρέχουν επίσης τη δυνατότητα εκτέλεσης μακροεντολών όταν το αρχείο ανοίγει. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [VST](/viewer/python-net/groupdocs.viewer/filetype/vst/) | Το Visio Drawing Template (.vst) είναι αρχεία διανυσματικών εικόνων που δημιουργήθηκαν με το Microsoft Visio και λειτουργούν ως πρότυπο για τη δημιουργία περαιτέρω αρχείων. Αυτά τα αρχεία προτύπων είναι σε δυαδικό μορφότυπο και περιέχουν την προεπιλεγμένη διάταξη και ρυθμίσεις που χρησιμοποιούνται για τη δημιουργία νέων σχεδίων Visio. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [VSTX](/viewer/python-net/groupdocs.viewer/filetype/vstx/) | Το Visio Drawing Template (.vstx) είναι αρχεία προτύπων σχεδίασης που δημιουργήθηκαν με το Microsoft Visio 2013 και μεταγενέστερα. Αυτά τα αρχεία VSTX παρέχουν σημείο εκκίνησης για τη δημιουργία σχεδίων Visio, αποθηκευμένων ως αρχεία .VSDX, με προεπιλεγμένη διάταξη και ρυθμίσεις. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [VSTM](/viewer/python-net/groupdocs.viewer/filetype/vstm/) | Το Visio Macro-Enabled Drawing Template (.vstm) είναι αρχεία προτύπων που δημιουργήθηκαν με το Microsoft Visio και υποστηρίζουν μακροεντολές. Σε αντίθεση με τα αρχεία VSDX, τα αρχεία που δημιουργούνται από πρότυπα VSTM μπορούν να εκτελούν μακροεντολές που έχουν αναπτυχθεί σε κώδικα Visual Basic for Applications (VBA). Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [VSSM](/viewer/python-net/groupdocs.viewer/filetype/vssm/) | Το Visio Macro-Enabled Stencil File (.vssm) είναι αρχεία προτύπων Microsoft Visio που παρέχουν υποστήριξη για μακροεντολές. Ένα αρχείο VSSM όταν ανοίγει επιτρέπει την εκτέλεση των μακροεντολών για την επίτευξη της επιθυμητής μορφοποίησης και τοποθέτησης των σχημάτων σε ένα διάγραμμα. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [VSX](/viewer/python-net/groupdocs.viewer/filetype/vsx/) | Το Visio Stencil XML File (.vsx) αναφέρεται σε πρότυπα που αποτελούνται από σχέδια και σχήματα που χρησιμοποιούνται για τη δημιουργία διαγραμμάτων στο Microsoft Visio. Τα αρχεία VSX αποθηκεύονται σε μορφότυπο XML και υποστηρίζονταν μέχρι το Visio 2013. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [VTX](/viewer/python-net/groupdocs.viewer/filetype/vtx/) | Το Visio Template XML File (.vtx) είναι ένα πρότυπο σχεδίου Microsoft Visio που αποθηκεύεται σε δίσκο σε μορφότυπο XML. Το πρότυπο αποσκοπεί στην παροχή ενός αρχείου με βασικές ρυθμίσεις που μπορούν να χρησιμοποιηθούν για τη δημιουργία πολλαπλών αρχείων Visio με τις ίδιες ρυθμίσεις. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [VDW](/viewer/python-net/groupdocs.viewer/filetype/vdw/) | Το Visio Web Drawing (.vdw) αντιπροσωπεύει μορφότυπο αρχείου που καθορίζει τις ροές και τις αποθηκεύσεις που απαιτούνται για την απόδοση ενός σχεδίου Web. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [VDX](/viewer/python-net/groupdocs.viewer/filetype/vdx/) | Το Visio Drawing XML File (.vdx) αντιπροσωπεύει οποιοδήποτε σχέδιο ή διάγραμμα που δημιουργείται στο Microsoft Visio, αλλά αποθηκεύεται σε μορφότυπο XML με επέκταση .VDX. Ένα αρχείο Visio drawing XML δημιουργείται στο λογισμικό Visio, το οποίο αναπτύχθηκε από τη Microsoft. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [EPUB](/viewer/python-net/groupdocs.viewer/filetype/epub/) | Το Open eBook File (.epub) είναι μια μορφή αρχείου e‑book που παρέχει ένα τυποποιημένο ψηφιακό φορμά δημοσίευσης για εκδότες και καταναλωτές. Η μορφή αυτή είναι πλέον τόσο κοινή που υποστηρίζεται από πολλούς αναγνώστες e‑book και λογισμικά εφαρμογές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [MOBI](/viewer/python-net/groupdocs.viewer/filetype/mobi/) | Το Mobipocket eBook (.mobi) είναι μία από τις πιο διαδεδομένες μορφές αρχείων ebook. Η μορφή αυτή είναι μια βελτίωση της παλιάς μορφής OEB (Open Ebook Format) και χρησιμοποιήθηκε ως ιδιόκτητη μορφή για το Mobipocket Reader. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [AZW3](/viewer/python-net/groupdocs.viewer/filetype/azw3/) | Το Amazon Kindle Format 8 (KF8) ebook είναι η ψηφιακή μορφή αρχείου που αναπτύχθηκε για συσκευές Amazon Kindle. Η μορφή αυτή είναι μια βελτίωση των παλαιότερων αρχείων AZW και χρησιμοποιείται μόνο σε συσκευές Kindle Fire με συμβατότητα προς τα πίσω με τις προγενέστερες μορφές αρχείων, δηλαδή MOBI και AZW. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [MSG](/viewer/python-net/groupdocs.viewer/filetype/msg/) | Το Outlook Mail Message (.msg) είναι μια μορφή αρχείου που χρησιμοποιείται από το Microsoft Outlook και το Exchange για την αποθήκευση μηνυμάτων email, επαφών, ραντεβού ή άλλων εργασιών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [EML](/viewer/python-net/groupdocs.viewer/filetype/eml/) | Το E‑Mail Message (.eml) αντιπροσωπεύει μηνύματα email που αποθηκεύονται με χρήση του Outlook και άλλων σχετικών εφαρμογών. Σχεδόν όλοι οι πελάτες ηλεκτρονικού ταχυδρομείου υποστηρίζουν αυτή τη μορφή αρχείου λόγω της συμμόρφωσής της με το πρότυπο RFC‑822 Internet Message Format Standard. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [NSF](/viewer/python-net/groupdocs.viewer/filetype/nsf/) | Lotus Notes Database (.nsf) Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [MBOX](/viewer/python-net/groupdocs.viewer/filetype/mbox/) | Email Mailbox File (.mbox) Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [EMLX](/viewer/python-net/groupdocs.viewer/filetype/emlx/) | Το Apple Mail Message (.emlx) υλοποιείται και αναπτύσσεται από την Apple. Η εφαρμογή Apple Mail χρησιμοποιεί τη μορφή αρχείου EMLX για την εξαγωγή των email. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [PST](/viewer/python-net/groupdocs.viewer/filetype/pst/) | Το Outlook Personal Information Store File (.pst) αντιπροσωπεύει τα Outlook Personal Storage Files (επίσης γνωστά ως Personal Storage Table) που αποθηκεύουν διάφορες πληροφορίες χρήστη. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [OST](/viewer/python-net/groupdocs.viewer/filetype/ost/) | Το Outlook Offline Data File (.ost) αντιπροσωπεύει τα δεδομένα του γραμματοκιβωτίου του χρήστη σε λειτουργία εκτός σύνδεσης στον τοπικό υπολογιστή μετά την εγγραφή στον Exchange Server χρησιμοποιώντας το Microsoft Outlook. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [TIF](/viewer/python-net/groupdocs.viewer/filetype/tif/) | Το Tagged Image File (.tif) αντιπροσωπεύει ραστερικές εικόνες που προορίζονται για χρήση σε ποικίλες συσκευές που συμμορφώνονται με αυτό το πρότυπο μορφής αρχείου. Είναι ικανό να περιγράφει δεδομένα εικόνας διπλού επιπέδου, γκρι κλίμακας, χρωματικής παλέτας και πλήρους χρώματος σε διάφορους χρωματικούς χώρους. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [TIFF](/viewer/python-net/groupdocs.viewer/filetype/tiff/) | Το Tagged Image File Format (.tiff) αντιπροσωπεύει ραστερικές εικόνες που προορίζονται για χρήση σε ποικίλες συσκευές που συμμορφώνονται με αυτό το πρότυπο μορφής αρχείου. Είναι ικανό να περιγράφει δεδομένα εικόνας διπλού επιπέδου, γκρι κλίμακας, χρωματικής παλέτας και πλήρους χρώματος σε διάφορους χρωματικούς χώρους. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [JPG](/viewer/python-net/groupdocs.viewer/filetype/jpg/) | Η JPEG Image (.jpg) είναι ένας τύπος μορφής εικόνας που αποθηκεύεται με τη μέθοδο της απωλεστικής συμπίεσης. Η παραγόμενη εικόνα, ως αποτέλεσμα της συμπίεσης, αποτελεί μια ισορροπία μεταξύ μεγέθους αποθήκευσης και ποιότητας εικόνας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [JPEG](/viewer/python-net/groupdocs.viewer/filetype/jpeg/) | Η JPEG Image (.jpeg) είναι ένας τύπος μορφής εικόνας που αποθηκεύεται με τη μέθοδο της απωλεστικής συμπίεσης. Η παραγόμενη εικόνα, ως αποτέλεσμα της συμπίεσης, αποτελεί μια ισορροπία μεταξύ μεγέθους αποθήκευσης και ποιότητας εικόνας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [JFIF](/viewer/python-net/groupdocs.viewer/filetype/jfif/) | Το JPEG File Interchange Format (.jfif) είναι μια εικόνα που αναπτύχθηκε για γρήγορη ανταλλαγή μεταξύ πλατφορμών. Αυτή η μορφή χρησιμοποιεί συμπίεση JPEG. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [PNG](/viewer/python-net/groupdocs.viewer/filetype/png/) | Το Portable Network Graphic (.png) είναι ένας τύπος μορφής αρχείου ραστερικής εικόνας που χρησιμοποιεί χωρίς απώλειες συμπίεση. Αυτή η μορφή αρχείου δημιουργήθηκε ως αντικατάσταση του Graphics Interchange Format (GIF) και δεν έχει περιορισμούς πνευματικών δικαιωμάτων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [GIF](/viewer/python-net/groupdocs.viewer/filetype/gif/) | Το Graphical Interchange Format File (.gif) είναι ένας τύπος εξαιρετικά συμπιεσμένης εικόνας. Για κάθε εικόνα, το GIF επιτρέπει συνήθως έως 8 bits ανά pixel και έως 256 χρώματα σε όλη την εικόνα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [APNG](/viewer/python-net/groupdocs.viewer/filetype/apng/) | Το Animated Portable Network Graphic (.apng) είναι μια επέκταση της μορφής PNG που υποστηρίζει κίνηση. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [BMP](/viewer/python-net/groupdocs.viewer/filetype/bmp/) | Το αρχείο εικόνας Bitmap (.bmp) χρησιμοποιείται για την αποθήκευση ψηφιακών bitmap εικόνων. Αυτές οι εικόνες είναι ανεξάρτητες από την κάρτα γραφικών και ονομάζονται επίσης μορφή αρχείου device independent bitmap (DIB). Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [TGA](/viewer/python-net/groupdocs.viewer/filetype/tga/) | Το Truevision TGA (Truevision Advanced Raster Adapter - TARGA) χρησιμοποιείται για την αποθήκευση ψηφιακών bitmap εικόνων που αναπτύχθηκαν από την TRUEVISION. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [ICO](/viewer/python-net/groupdocs.viewer/filetype/ico/) | Το αρχείο εικονιδίου (.ico) είναι τύποι αρχείων εικόνας που χρησιμοποιούνται ως εικονίδιο για την αναπαράσταση μιας εφαρμογής στα Microsoft Windows. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [JP2](/viewer/python-net/groupdocs.viewer/filetype/jp2/) | Το JPEG 2000 Core Image File (.jp2) είναι ένα σύστημα κωδικοποίησης εικόνας και ένα σύγχρονο πρότυπο συμπίεσης εικόνας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [JPF](/viewer/python-net/groupdocs.viewer/filetype/jpf/) | Αρχείο εικόνας JPEG 2000 (.jpf) |
| [JPX](/viewer/python-net/groupdocs.viewer/filetype/jpx/) | Αρχείο εικόνας JPEG 2000 (.jpx) |
| [JPM](/viewer/python-net/groupdocs.viewer/filetype/jpm/) | Αρχείο εικόνας JPEG 2000 (.jpm) |
| [J2C](/viewer/python-net/groupdocs.viewer/filetype/j2c/) | Ροή κώδικα JPEG 2000 (.j2c) |
| [J2K](/viewer/python-net/groupdocs.viewer/filetype/j2k/) | Η ροή κώδικα JPEG 2000 (.j2k) είναι μια εικόνα που συμπιέζεται χρησιμοποιώντας τη συμπίεση κυματικού (wavelet) αντί για τη συμπίεση DCT. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [JPC](/viewer/python-net/groupdocs.viewer/filetype/jpc/) | Ροή κώδικα JPEG 2000 (.jpc) |
| [JLS](/viewer/python-net/groupdocs.viewer/filetype/jls/) | JPEG-LS (JLS) (.jls) |
| [DIB](/viewer/python-net/groupdocs.viewer/filetype/dib/) | Αρχείο Device Independent Bitmap (.dib) |
| [WMF](/viewer/python-net/groupdocs.viewer/filetype/wmf/) | Το Windows Metafile (.wmf) αντιπροσωπεύει το Microsoft Windows Metafile (WMF) για την αποθήκευση δεδομένων εικόνων σε μορφή διανυσματικών καθώς και bitmap. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [WMZ](/viewer/python-net/groupdocs.viewer/filetype/wmz/) | Το Compressed Windows Metafile (.wmz) αντιπροσωπεύει το Microsoft Windows Metafile (WMF) συμπιεσμένο σε αρχείο GZIP - για την αποθήκευση δεδομένων εικόνων σε μορφή διανυσματικών καθώς και bitmap. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [EMF](/viewer/python-net/groupdocs.viewer/filetype/emf/) | Το Enhanced Windows Metafile (.emf) αντιπροσωπεύει γραφικές εικόνες ανεξάρτητα από τη συσκευή. Τα μετααρχεία EMF περιλαμβάνουν εγγραφές μεταβλητού μήκους σε χρονολογική σειρά που μπορούν να αποδώσουν την αποθηκευμένη εικόνα μετά την ανάλυση σε οποιαδήποτε συσκευή εξόδου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [EMZ](/viewer/python-net/groupdocs.viewer/filetype/emz/) | Το Enhanced Windows Metafile compressed (.emz) αντιπροσωπεύει γραφικές εικόνες ανεξάρτητα από τη συσκευή, συμπιεσμένες με GZIP. Τα μετααρχεία EMF περιλαμβάνουν εγγραφές μεταβλητού μήκους σε χρονολογική σειρά που μπορούν να αποδώσουν την αποθηκευμένη εικόνα μετά την ανάλυση σε οποιαδήποτε συσκευή εξόδου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [WEBP](/viewer/python-net/groupdocs.viewer/filetype/webp/) | Η εικόνα WebP (.webp) είναι μια σύγχρονη μορφή αρχείου raster εικόνας για το web που βασίζεται σε συμπίεση χωρίς απώλειες και με απώλειες. Παρέχει την ίδια ποιότητα εικόνας ενώ μειώνει σημαντικά το μέγεθος της εικόνας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [DNG](/viewer/python-net/groupdocs.viewer/filetype/dng/) | Η προδιαγραφή Digital Negative (.dng) είναι μια μορφή εικόνας ψηφιακής κάμερας που χρησιμοποιείται για την αποθήκευση ακατέργαστων αρχείων. Αναπτύχθηκε από την Adobe τον Σεπτέμβριο του 2004. Αναπτύχθηκε κυρίως για τη ψηφιακή φωτογραφία. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [CDR](/viewer/python-net/groupdocs.viewer/filetype/cdr/) | Το CorelDraw Vector Graphic Drawing (.cdr) είναι ένα αρχείο εικόνας διανυσματικού σχεδίου που δημιουργείται εγγενώς με το CorelDRAW για την αποθήκευση κωδικοποιημένων και συμπιεσμένων ψηφιακών εικόνων. Ένα τέτοιο αρχείο σχεδίου περιέχει κείμενο, γραμμές, σχήματα, εικόνες, χρώματα και εφέ για διανυσματική αναπαράσταση του περιεχομένου της εικόνας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [CMX](/viewer/python-net/groupdocs.viewer/filetype/cmx/) | Το Corel Exchange (.cmx) είναι ένα αρχείο εικόνας σχεδίου που μπορεί να περιέχει διανυσματικά γραφικά καθώς και bitmap γραφικά. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [DJVU](/viewer/python-net/groupdocs.viewer/filetype/djvu/) | Η εικόνα DjVu (.djvu) είναι μια μορφή αρχείου γραφικών που προορίζεται για σαρωμένα έγγραφα και βιβλία, ειδικά εκείνα που περιέχουν συνδυασμό κειμένου, σχεδίων, εικόνων και φωτογραφιών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [CGM](/viewer/python-net/groupdocs.viewer/filetype/cgm/) | Το Computer Graphics Metafile (.cgm) είναι μια δωρεάν, ανεξάρτητη από πλατφόρμα, διεθνές πρότυπο μορφή μετααρχείου για την αποθήκευση και ανταλλαγή διανυσματικών γραφικών (2D), raster γραφικών και κειμένου. Το CGM χρησιμοποιεί αντικειμενοστραφή προσέγγιση και πολλές λειτουργικές δυνατότητες για την παραγωγή εικόνας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [PCL](/viewer/python-net/groupdocs.viewer/filetype/pcl/) | Έγγραφο Printer Command Language (.pcl) |
| [PSD](/viewer/python-net/groupdocs.viewer/filetype/psd/) | Το Adobe Photoshop Document (.psd) αντιπροσωπεύει τη φυσική μορφή αρχείου του Adobe Photoshop που χρησιμοποιείται για σχεδίαση και ανάπτυξη γραφικών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [PSB](/viewer/python-net/groupdocs.viewer/filetype/psb/) | Το Photoshop Large Document Format (.psb) αντιπροσωπεύει τη μορφή μεγάλου εγγράφου του Photoshop που χρησιμοποιείται για σχεδίαση και ανάπτυξη γραφικών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [DCM](/viewer/python-net/groupdocs.viewer/filetype/dcm/) | Η εικόνα DICOM (.dcm) αντιπροσωπεύει ψηφιακή εικόνα που αποθηκεύει ιατρικές πληροφορίες των ασθενών, όπως MRI, CT σκαναρίσματα και υπερηχογραφικές εικόνες. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [PS](/viewer/python-net/groupdocs.viewer/filetype/ps/) | Αρχείο PostScript (.ps) |
| [EPS](/viewer/python-net/groupdocs.viewer/filetype/eps/) | Το αρχείο Encapsulated PostScript (.eps) περιγράφει ένα πρόγραμμα γλώσσας Encapsulated PostScript που περιγράφει την εμφάνιση μιας μόνο σελίδας. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [ODG](/viewer/python-net/groupdocs.viewer/filetype/odg/) | Το αρχείο OpenDocument Graphic (.odg) χρησιμοποιείται από την εφαρμογή Draw του Apache OpenOffice για την αποθήκευση στοιχείων σχεδίασης ως διανυσματική εικόνα. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [FODG](/viewer/python-net/groupdocs.viewer/filetype/fodg/) | Το πρότυπο Flat XML ODF (.fodg) χρησιμοποιείται από την εφαρμογή Draw του Apache OpenOffice για την αποθήκευση στοιχείων σχεδίασης ως διανυσματική εικόνα. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [SVG](/viewer/python-net/groupdocs.viewer/filetype/svg/) | Το αρχείο Scalable Vector Graphics (.svg) είναι ένα αρχείο Scalable Vector Graphics που χρησιμοποιεί μορφή κειμένου βασισμένη σε XML για την περιγραφή της εμφάνισης μιας εικόνας. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [SVGZ](/viewer/python-net/groupdocs.viewer/filetype/svgz/) | Το αρχείο Scalable Vector Graphics (.svgz) είναι ένα αρχείο Scalar Vector Graphics που χρησιμοποιεί μορφή κειμένου βασισμένη σε XML, συμπιεσμένη με GZIP, για την περιγραφή της εμφάνισης μιας εικόνας. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [OTG](/viewer/python-net/groupdocs.viewer/filetype/otg/) | Πρότυπο OpenDocument Graphic (.otg) |
| [HTM](/viewer/python-net/groupdocs.viewer/filetype/htm/) | Το αρχείο Hypertext Markup Language (.htm) είναι η επέκταση για ιστοσελίδες που δημιουργούνται για προβολή σε προγράμματα περιήγησης. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [HTML](/viewer/python-net/groupdocs.viewer/filetype/html/) | Το αρχείο Hypertext Markup Language (.html) είναι η επέκταση για ιστοσελίδες που δημιουργούνται για προβολή σε προγράμματα περιήγησης. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [MHT](/viewer/python-net/groupdocs.viewer/filetype/mht/) | Αρχείο MHTML Web Archive (.mht) |
| [MHTML](/viewer/python-net/groupdocs.viewer/filetype/mhtml/) | Αρχείο MIME HTML (.mhtml) |
| [XML](/viewer/python-net/groupdocs.viewer/filetype/xml/) | Αρχείο XML (.xml). Το GroupDocs.Viewer διαθέτει έναν ειδικό επεξεργαστή για τη διαχείριση των αρχείων XML, δείτε την τεκμηρίωση. |
| [ONE](/viewer/python-net/groupdocs.viewer/filetype/one/) | Το έγγραφο OneNote (.one) δημιουργείται από την εφαρμογή Microsoft OneNote. Το OneNote σας επιτρέπει να συγκεντρώνετε πληροφορίες χρησιμοποιώντας την εφαρμογή, σαν να χρησιμοποιείτε το σημειωματάριό σας για λήψη σημειώσεων. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [PDF](/viewer/python-net/groupdocs.viewer/filetype/pdf/) | Το αρχείο Portable Document Format (.pdf) είναι ένας τύπος εγγράφου που δημιουργήθηκε από την Adobe τη δεκαετία του 1990. Ο σκοπός αυτού του μορφότυπου αρχείου ήταν η εισαγωγή ενός προτύπου για την αναπαράσταση εγγράφων και άλλου υλικού αναφοράς σε μορφή ανεξάρτητη από λογισμικό εφαρμογών, υλικό καθώς και λειτουργικό σύστημα. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [XPS](/viewer/python-net/groupdocs.viewer/filetype/xps/) | Το αρχείο XML Paper Specification (.xps) αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις προδιαγραφές XML Paper Specification που δημιουργήθηκαν από τη Microsoft. Αυτό το μορφότυπο αναπτύχθηκε από τη Microsoft ως αντικατάσταση του μορφότυπου αρχείου EMF και είναι παρόμοιο με το μορφότυπο PDF, αλλά χρησιμοποιεί XML για τη διάταξη, την εμφάνιση και τις πληροφορίες εκτύπωσης ενός εγγράφου. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [OXPS](/viewer/python-net/groupdocs.viewer/filetype/oxps/) | Αρχείο OpenXPS (.oxps) |
| [TEX](/viewer/python-net/groupdocs.viewer/filetype/tex/) | Το έγγραφο πηγής LaTeX (.tex) είναι μια γλώσσα που περιλαμβάνει προγραμματιστικές καθώς και χαρακτηριστικά σήμανσης, χρησιμοποιείται για τη σύνθεση εγγράφων. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [OFD](/viewer/python-net/groupdocs.viewer/filetype/ofd/) | Η μορφή Open Fixed-layout Document (OFD) που ορίζεται από το GB/T 33190-2016 στοχεύει να αντικαταστήσει το PDF σε κινεζικούς δημόσιους οργανισμούς. |
| [PPT](/viewer/python-net/groupdocs.viewer/filetype/ppt/) | Η παρουσίαση PowerPoint (.ppt) αντιπροσωπεύει αρχείο PowerPoint που αποτελείται από μια συλλογή διαφανειών για προβολή ως SlideShow. Καθορίζει τη Δυαδική Μορφή Αρχείου που χρησιμοποιείται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [PPTX](/viewer/python-net/groupdocs.viewer/filetype/pptx/) | Οι παρουσιάσεις PowerPoint Open XML (.pptx) είναι αρχεία παρουσίασης που δημιουργούνται με τη δημοφιλή εφαρμογή Microsoft PowerPoint. Σε αντίθεση με την προηγούμενη έκδοση του μορφότυπου αρχείου παρουσίασης PPT που ήταν δυαδική, η μορφή PPTX βασίζεται στη μορφή αρχείου παρουσίασης Microsoft PowerPoint open XML. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [PPS](/viewer/python-net/groupdocs.viewer/filetype/pps/) | Η παρουσίαση Slide Show PowerPoint (.pps) δημιουργείται χρησιμοποιώντας το Microsoft PowerPoint για σκοπό Slide Show. Η ανάγνωση και δημιουργία αρχείων PPS υποστηρίζεται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [PPSX](/viewer/python-net/groupdocs.viewer/filetype/ppsx/) | Τα αρχεία PowerPoint Open XML Slide Show (.ppsx) δημιουργούνται χρησιμοποιώντας το Microsoft PowerPoint 2007 και νεότερες εκδόσεις για σκοπό Slide Show. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [ODP](/viewer/python-net/groupdocs.viewer/filetype/odp/) | Η παρουσίαση OpenDocument (.odp) αντιπροσωπεύει το μορφότυπο αρχείου παρουσίασης που χρησιμοποιείται από το OpenOffice.org στο πρότυπο OASISOpen. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [FODP](/viewer/python-net/groupdocs.viewer/filetype/fodp/) | Η παρουσίαση OpenDocument (.fodp) αντιπροσωπεύει το OpenDocument Flat XML Presentation. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [POT](/viewer/python-net/groupdocs.viewer/filetype/pot/) | Το PowerPoint Template (.pot) αντιπροσωπεύει αρχεία προτύπων Microsoft PowerPoint που δημιουργήθηκαν από εκδόσεις PowerPoint 97-2003. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [PPTM](/viewer/python-net/groupdocs.viewer/filetype/pptm/) | Το PowerPoint Open XML Macro-Enabled Presentation είναι αρχεία Παρουσίασης με ενεργοποιημένα μακροεντολές που δημιουργούνται με το Microsoft PowerPoint 2007 ή νεότερες εκδόσεις. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [POTX](/viewer/python-net/groupdocs.viewer/filetype/potx/) | Το PowerPoint Open XML Presentation Template (.potx) αντιπροσωπεύει πρότυπα παρουσιάσεων Microsoft PowerPoint που δημιουργούνται με το Microsoft PowerPoint 2007 και μεταγενέστερες εκδόσεις. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [POTM](/viewer/python-net/groupdocs.viewer/filetype/potm/) | Το PowerPoint Open XML Macro-Enabled Presentation Template (.potm) είναι αρχεία προτύπων Microsoft PowerPoint με υποστήριξη μακροεντολών. Τα αρχεία POTM δημιουργούνται με το PowerPoint 2007 ή νεότερο και περιέχουν προεπιλεγμένες ρυθμίσεις που μπορούν να χρησιμοποιηθούν για τη δημιουργία περαιτέρω αρχείων παρουσίασης. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [PPSM](/viewer/python-net/groupdocs.viewer/filetype/ppsm/) | Το PowerPoint Open XML Macro-Enabled Slide (.ppsm) αντιπροσωπεύει μορφότυπο αρχείου Παρουσίασης διαφανειών με ενεργοποιημένα μακροεντολές που δημιουργείται με το Microsoft PowerPoint 2007 ή νεότερο. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [OTP](/viewer/python-net/groupdocs.viewer/filetype/otp/) | Το OpenDocument Presentation Template (.otp) αντιπροσωπεύει αρχεία προτύπων παρουσίασης που δημιουργούνται από εφαρμογές σε τυποποιημένη μορφή OASIS OpenDocument. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [XLS](/viewer/python-net/groupdocs.viewer/filetype/xls/) | Το Excel Spreadsheet (.xls) αντιπροσωπεύει τη Μορφή Δυαδικού Αρχείου Excel. Τέτοια αρχεία μπορούν να δημιουργηθούν από το Microsoft Excel καθώς και από άλλα παρόμοια προγράμματα λογιστικών φύλλων όπως το OpenOffice Calc ή το Apple Numbers. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [EXCEL_2003XML](/viewer/python-net/groupdocs.viewer/filetype/excel_2003xml/) | Το Excel 2003 XML (SpreadsheetML) αντιπροσωπεύει τη Μορφή Δυαδικού Αρχείου Excel. Τέτοια αρχεία μπορούν να δημιουργηθούν από το Microsoft Excel καθώς και από άλλα παρόμοια προγράμματα λογιστικών φύλλων όπως το OpenOffice Calc ή το Apple Numbers. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [NUMBERS](/viewer/python-net/groupdocs.viewer/filetype/numbers/) | Το Apple Numbers αντιπροσωπεύει μορφή δυαδικού αρχείου παρόμοια με το Excel. Τέτοια αρχεία μπορούν να δημιουργηθούν από την εφαρμογή Apple Numbers. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [XLSX](/viewer/python-net/groupdocs.viewer/filetype/xlsx/) | Το Microsoft Excel Open XML Spreadsheet (.xlsx) είναι μια γνωστή μορφή για έγγραφα Microsoft Excel που εισήχθη από τη Microsoft με την κυκλοφορία του Microsoft Office 2007. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [XLSM](/viewer/python-net/groupdocs.viewer/filetype/xlsm/) | Το Excel Open XML Macro-Enabled Spreadsheet (.xlsm) είναι ένας τύπος αρχείων λογιστικού φύλλου που υποστηρίζουν μακροεντολές. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [XLSB](/viewer/python-net/groupdocs.viewer/filetype/xlsb/) | Το Excel Binary Spreadsheet (.xlsb) καθορίζει τη Μορφή Δυαδικού Αρχείου Excel, η οποία αποτελεί μια συλλογή εγγραφών και δομών που ορίζουν το περιεχόμενο του βιβλίου εργασίας Excel. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [CSV](/viewer/python-net/groupdocs.viewer/filetype/csv/) | Το Comma Separated Values File (.csv) αντιπροσωπεύει αρχεία απλού κειμένου που περιέχουν εγγραφές δεδομένων με τιμές χωρισμένες με κόμμα. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [TSV](/viewer/python-net/groupdocs.viewer/filetype/tsv/) | Το Tab Separated Values File (.tsv) αντιπροσωπεύει δεδομένα χωρισμένα με καρτέλες σε μορφή απλού κειμένου. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [ODS](/viewer/python-net/groupdocs.viewer/filetype/ods/) | Το OpenDocument Spreadsheet (.ods) αντιπροσωπεύει τη μορφή εγγράφου λογιστικού φύλλου OpenDocument που μπορεί να επεξεργαστεί από τον χρήστη. Τα δεδομένα αποθηκεύονται μέσα σε αρχείο ODF σε σειρές και στήλες. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [FODS](/viewer/python-net/groupdocs.viewer/filetype/fods/) | OpenDocument Flat XML Spreadsheet (.fods) |
| [OTS](/viewer/python-net/groupdocs.viewer/filetype/ots/) | OpenDocument Spreadsheet Template (.ots) |
| [XLAM](/viewer/python-net/groupdocs.viewer/filetype/xlam/) | Microsoft Excel Add-in (.xlam) |
| [XLTM](/viewer/python-net/groupdocs.viewer/filetype/xltm/) | Το Microsoft Excel Macro-Enabled Template (.xltm) αντιπροσωπεύει αρχεία που δημιουργούνται από το Microsoft Excel ως αρχεία προτύπου με ενεργοποιημένες μακροεντολές. Τα αρχεία XLTM είναι παρόμοια με τα XLTX ως προς τη δομή, εκτός από το ότι τα δεύτερα δεν υποστηρίζουν τη δημιουργία προτύπων με μακροεντολές. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [XLT](/viewer/python-net/groupdocs.viewer/filetype/xlt/) | Το Microsoft Excel Template (.xlt) είναι αρχεία προτύπων που δημιουργούνται με το Microsoft Excel, μια εφαρμογή λογιστικού φύλλου που αποτελεί μέρος της σουίτας Microsoft Office. Το Microsoft Office 97-2003 υποστήριζε τη δημιουργία νέων αρχείων XLT καθώς και το άνοιγμά τους. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [XLTX](/viewer/python-net/groupdocs.viewer/filetype/xltx/) | Το Excel Open XML Spreadsheet Template (.xltx) αντιπροσωπεύει το Microsoft Excel Template που βασίζεται στις προδιαγραφές του αρχείου Office OpenXML. Χρησιμοποιείται για τη δημιουργία ενός τυπικού αρχείου προτύπου που μπορεί να αξιοποιηθεί για την παραγωγή αρχείων XLSX με τις ίδιες ρυθμίσεις όπως ορίζονται στο αρχείο XLTX. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [SXC](/viewer/python-net/groupdocs.viewer/filetype/sxc/) | StarOffice Calc Spreadsheet (.sxc) |
| [MPP](/viewer/python-net/groupdocs.viewer/filetype/mpp/) | Το αρχείο Microsoft Project (.mpp) είναι αρχείο δεδομένων του Microsoft Project που αποθηκεύει πληροφορίες σχετικές με τη διαχείριση έργων με ολοκληρωμένο τρόπο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [MPT](/viewer/python-net/groupdocs.viewer/filetype/mpt/) | Το πρότυπο Microsoft Project (.mpt) περιέχει βασικές πληροφορίες και δομή μαζί με ρυθμίσεις εγγράφου για τη δημιουργία αρχείων .MPP. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [MPX](/viewer/python-net/groupdocs.viewer/filetype/mpx/) | Το αρχείο Microsoft Project Exchange (.mpx) είναι μια μορφή αρχείου ASCII για τη μεταφορά πληροφοριών έργου μεταξύ του Microsoft Project (MSP) και άλλων εφαρμογών που υποστηρίζουν τη μορφή αρχείου MPX, όπως το Primavera Project Planner, το Sciforma και το Timerline Precision Estimating. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [AS_](/viewer/python-net/groupdocs.viewer/filetype/as_/) | Αρχείο ActionScript (.as) |
| [AS3](/viewer/python-net/groupdocs.viewer/filetype/as3/) | Αρχείο ActionScript (.as) |
| [ASM](/viewer/python-net/groupdocs.viewer/filetype/asm/) | Αρχείο πηγαίου κώδικα Assembly Language (.asm) |
| [BAT](/viewer/python-net/groupdocs.viewer/filetype/bat/) | Αρχείο δέσμης εντολών DOS (.bat) |
| [C](/viewer/python-net/groupdocs.viewer/filetype/c/) | Αρχείο πηγαίου κώδικα C/C++ (.c) |
| [CC](/viewer/python-net/groupdocs.viewer/filetype/cc/) | Αρχείο πηγαίου κώδικα C++ (.cc) |
| [CMAKE](/viewer/python-net/groupdocs.viewer/filetype/cmake/) | Αρχείο CMake (.cmake) |
| [CPP](/viewer/python-net/groupdocs.viewer/filetype/cpp/) | Αρχείο πηγαίου κώδικα C++ (.cpp) |
| [CS](/viewer/python-net/groupdocs.viewer/filetype/cs/) | Το αρχείο πηγαίου κώδικα C# (.cs) είναι ένα αρχείο πηγαίου κώδικα για τη γλώσσα προγραμματισμού C#. Εισήχθη από τη Microsoft για χρήση με το .NET Framework. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [VB](/viewer/python-net/groupdocs.viewer/filetype/vb/) | Το αρχείο στοιχείου έργου Visual Basic (.vb) είναι ένα αρχείο πηγαίου κώδικα δημιουργημένο στη γλώσσα Visual Basic, το οποίο δημιουργήθηκε από τη Microsoft για την ανάπτυξη εφαρμογών .NET. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [CSS](/viewer/python-net/groupdocs.viewer/filetype/css/) | Αρχείο Cascading Style Sheet (.css) |
| [CXX](/viewer/python-net/groupdocs.viewer/filetype/cxx/) | Αρχείο πηγαίου κώδικα C++ (.cxx) |
| [DIFF](/viewer/python-net/groupdocs.viewer/filetype/diff/) | Αρχείο διόρθωσης (.diff) |
| [ERB](/viewer/python-net/groupdocs.viewer/filetype/erb/) | Αρχείο σεναρίου Ruby ERB (.erb) |
| [GROOVY](/viewer/python-net/groupdocs.viewer/filetype/groovy/) | Αρχείο πηγαίου κώδικα Groovy (.groovy) |
| [H](/viewer/python-net/groupdocs.viewer/filetype/h/) | Αρχείο κεφαλίδας C/C++/Objective-C (.h) |
| [HAML](/viewer/python-net/groupdocs.viewer/filetype/haml/) | Αρχείο πηγαίου κώδικα Haml (.haml) |
| [HH](/viewer/python-net/groupdocs.viewer/filetype/hh/) | Αρχείο κεφαλίδας C++ (.hh) |
| [JAVA](/viewer/python-net/groupdocs.viewer/filetype/java/) | Αρχείο πηγαίου κώδικα Java (.java) |
| [JS](/viewer/python-net/groupdocs.viewer/filetype/js/) | Αρχείο JavaScript (.js) |
| [JSON](/viewer/python-net/groupdocs.viewer/filetype/json/) | Αρχείο JavaScript Object Notation (.json) |
| [LESS](/viewer/python-net/groupdocs.viewer/filetype/less/) | Αρχείο LESS Style Sheet (.less) |
| [LOG](/viewer/python-net/groupdocs.viewer/filetype/log/) | Αρχείο καταγραφής (.log) |
| [M](/viewer/python-net/groupdocs.viewer/filetype/m/) | Αρχείο Υλοποίησης Objective‑C (.m) |
| [MAKE](/viewer/python-net/groupdocs.viewer/filetype/make/) | Σενάριο Makefile Xcode (.make) |
| [MD](/viewer/python-net/groupdocs.viewer/filetype/md/) | Αρχείο Τεκμηρίωσης Markdown (.md) |
| [ML](/viewer/python-net/groupdocs.viewer/filetype/ml/) | Αρχείο Κώδικα Πηγής ML (.ml) |
| [MM](/viewer/python-net/groupdocs.viewer/filetype/mm/) | Αρχείο Πηγής Objective‑C++ (.mm) |
| [PHP](/viewer/python-net/groupdocs.viewer/filetype/php/) | Αρχείο Κώδικα Πηγής PHP (.php) |
| [PL](/viewer/python-net/groupdocs.viewer/filetype/pl/) | Σενάριο Perl (.pl) |
| [PROPERTIES](/viewer/python-net/groupdocs.viewer/filetype/properties/) | Αρχείο Ιδιοτήτων Java (.properties) |
| [PY](/viewer/python-net/groupdocs.viewer/filetype/py/) | Σενάριο Python (.py) |
| [RB](/viewer/python-net/groupdocs.viewer/filetype/rb/) | Κώδικας Πηγής Ruby (.rb) |
| [RST](/viewer/python-net/groupdocs.viewer/filetype/rst/) | Αρχείο reStructuredText (.rst) |
| [SASS](/viewer/python-net/groupdocs.viewer/filetype/sass/) | Αρχείο Syntactically Awesome StyleSheets (.sass) |
| [SCALA](/viewer/python-net/groupdocs.viewer/filetype/scala/) | Αρχείο Κώδικα Πηγής Scala (.scala) |
| [SCM](/viewer/python-net/groupdocs.viewer/filetype/scm/) | Αρχείο Κώδικα Πηγής Scheme (.scm) |
| [SCRIPT](/viewer/python-net/groupdocs.viewer/filetype/script/) | Αρχείο Γενικού Σεναρίου (.script) |
| [SH](/viewer/python-net/groupdocs.viewer/filetype/sh/) | Σενάριο Bash Shell (.sh) |
| [SML](/viewer/python-net/groupdocs.viewer/filetype/sml/) | Αρχείο Κώδικα Πηγής Standard ML (.sml) |
| [SQL](/viewer/python-net/groupdocs.viewer/filetype/sql/) | Αρχείο Δεδομένων Structured Query Language (.sql) |
| [VIM](/viewer/python-net/groupdocs.viewer/filetype/vim/) | Αρχείο Ρυθμίσεων Vim (.vim) |
| [YAML](/viewer/python-net/groupdocs.viewer/filetype/yaml/) | Έγγραφο YAML (.yaml) |
| [DOC](/viewer/python-net/groupdocs.viewer/filetype/doc/) | Microsoft Word Document (.doc) αντιπροσωπεύει έγγραφα που δημιουργούνται από το Microsoft Word ή άλλα έγγραφα επεξεργασίας κειμένου σε δυαδική μορφή αρχείου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [DOCX](/viewer/python-net/groupdocs.viewer/filetype/docx/) | Microsoft Word Open XML Document (.docx) είναι μια γνωστή μορφή για έγγραφα Microsoft Word. Εισήχθη το 2007 με την κυκλοφορία του Microsoft Office 2007, η δομή αυτής της νέας μορφής εγγράφου άλλαξε από απλό δυαδικό σε συνδυασμό αρχείων XML και δυαδικών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [CHM](/viewer/python-net/groupdocs.viewer/filetype/chm/) | Microsoft Compiled HTML Help File (.chm) είναι μια γνωστή μορφή για έγγραφα HELP (τεκμηρίωση για κάποια εφαρμογή). Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [DOCM](/viewer/python-net/groupdocs.viewer/filetype/docm/) | Word Open XML Macro‑Enabled Document (.docm) είναι έγγραφα που δημιουργούνται από Microsoft Word 2007 ή νεότερο, με δυνατότητα εκτέλεσης μακροεντολών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [DOT](/viewer/python-net/groupdocs.viewer/filetype/dot/) | Word Document Template (.dot) είναι αρχεία προτύπων που δημιουργούνται από το Microsoft Word για να έχουν προ‑μορφοποιημένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOC ή DOCX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου εδώ. |
| [DOTX](/viewer/python-net/groupdocs.viewer/filetype/dotx/) | Τα Word Open XML Document Template (.dotx) είναι αρχεία προτύπων που δημιουργούνται από το Microsoft Word για να έχουν προ-μορφοποιημένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOCX. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [DOTM](/viewer/python-net/groupdocs.viewer/filetype/dotm/) | Το Word Open XML Macro-Enabled Document Template (.dotm) αντιπροσωπεύει ένα αρχείο προτύπου που δημιουργήθηκε με το Microsoft Word 2007 ή νεότερο. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [RTF](/viewer/python-net/groupdocs.viewer/filetype/rtf/) | Το Rich Text Format File (.rtf) αντιπροσωπεύει μια μέθοδο κωδικοποίησης μορφοποιημένου κειμένου και γραφικών για χρήση σε εφαρμογές. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [TXT](/viewer/python-net/groupdocs.viewer/filetype/txt/) | Το Plain Text File (.txt) αντιπροσωπεύει ένα έγγραφο κειμένου που περιέχει ακατέργαστο κείμενο με τη μορφή γραμμών. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [ODT](/viewer/python-net/groupdocs.viewer/filetype/odt/) | Το OpenDocument Text Document (.odt) είναι τύπος εγγράφων που δημιουργούνται με εφαρμογές επεξεργασίας κειμένου και βασίζονται στο μορφότυπο OpenDocument Text File. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [OTT](/viewer/python-net/groupdocs.viewer/filetype/ott/) | Το OpenDocument Document Template (.ott) αντιπροσωπεύει έγγραφα προτύπων που δημιουργούνται από εφαρμογές σε συμμόρφωση με το πρότυπο μορφότυπο OpenDocument του OASIS. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [VCF](/viewer/python-net/groupdocs.viewer/filetype/vcf/) | Το vCard File (.vcf) είναι ένα ψηφιακό μορφότυπο αρχείου για αποθήκευση πληροφοριών επαφών. Το μορφότυπο χρησιμοποιείται ευρέως για ανταλλαγή δεδομένων μεταξύ δημοφιλών εφαρμογών ανταλλαγής πληροφοριών. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [AI](/viewer/python-net/groupdocs.viewer/filetype/ai/) | Το Adobe Illustrator (.ai) είναι ένα μορφότυπο αρχείου για σχέδια Adobe Illustrator. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [PSM1](/viewer/python-net/groupdocs.viewer/filetype/psm1/) | Το PowerShell script module (.psm1) είναι ένα μορφότυπο αρχείου για σενάρια μονάδων PowerShell. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [PS1](/viewer/python-net/groupdocs.viewer/filetype/ps1/) | Το PowerShell script file (.ps1) είναι ένα μορφότυπο αρχείου για αρχεία Cmdlet του Windows PowerShell. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |
| [PSD1](/viewer/python-net/groupdocs.viewer/filetype/psd1/) | Το PowerShell script module manifest (.psd1) είναι ένα μορφότυπο αρχείου για σενάρια manifest μονάδων PowerShell. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου εδώ. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

# Καθορίστε τον τύπο αρχείου (π.χ., Markdown) κατά τη φόρτωση του εγγράφου
load_options = LoadOptions(FileType.MD)

# Αποδώστε το έγγραφο σε PDF
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Δείτε επίσης
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
