---
title: "CacheableFactory"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αυτή η κλάση βοηθά στην προσαρμογή ."
type: docs
weight: 10
url: /el/java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

Αυτή η κλάση βοηθά στην προσαρμογή [Cache](../../com.groupdocs.viewer.caching/cache).


Μπορούν να υλοποιηθούν προσαρμοσμένα μοντέλα για σειριοποίηση με την υπερίσχυση μεθόδων σε αυτήν την κλάση ώστε να τα επιστρέφουν αντί για τα ενσωματωμένα.
Για να το επιτύχετε, επεκτείνετε το CacheableFactory και ενεργοποιήστε το περνώντας νέα παρουσία προσαρμοσμένης εργοστασίου στη μέθοδο [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory#setInstance-CacheableFactory-).


Παράδειγμα χρήσης:

````

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
````


Για περισσότερες λεπτομέρειες, οδηγίες και παραδείγματα σχετικά με την προσαρμογή του cache, παρακαλούμε ανατρέξτε στο
[GroupDocs.Viewer documentation](../https://docs.groupdocs.com/viewer/java/getting-started/).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getInstance()](#getInstance--) | Λαμβάνει μια παρουσία του |
CacheableFactory
που μπορεί να χρησιμοποιηθεί για τη δημιουργία αντικειμένων cacheable.
|
|  | [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | Ορίζει την παρουσία του |
CacheableFactory
για χρήση.
|
|  | [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | Δημιουργεί μια υλοποίηση της διεπαφής [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) για τον καθορισμένο τύπο αρχείου και τις σελίδες. |
|
| [newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)](#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-) |  |
|  | [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Δημιουργεί μια υλοποίηση της διεπαφής [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) για τον καθορισμένο τύπο αρχείου, τις σελίδες και τον αριθμό σημειώσεων. |
|
|  | [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Δημιουργεί μια υλοποίηση της διεπαφής [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) για τον καθορισμένο τύπο αρχείου, τις σελίδες και τους φακέλους. |
|
|  | [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | Δημιουργεί μια υλοποίηση της διεπαφής [Character](../../com.groupdocs.viewer.results/character) για τον καθορισμένο χαρακτήρα, τη θέση και τις διαστάσεις. |
|
|  | [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | Δημιουργεί μια υλοποίηση της διεπαφής [FileInfo](../../com.groupdocs.viewer.results/fileinfo) για τον καθορισμένο τύπο αρχείου. |
|
|  | [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | Δημιουργεί μια υλοποίηση της διεπαφής [Layer](../../com.groupdocs.viewer.results/layer) με το καθορισμένο όνομα και ορατότητα. |
|
|  | [newLayer(String name)](#newLayer-java.lang.String-) | Δημιουργεί μια υλοποίηση της διεπαφής [Layer](../../com.groupdocs.viewer.results/layer) με το καθορισμένο όνομα. |
|
|  | [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | Δημιουργεί μια υλοποίηση της διεπαφής [Layout](../../com.groupdocs.viewer.results/layout) με το καθορισμένο όνομα, πλάτος και ύψος. |
|
|  | [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | Δημιουργεί μια υλοποίηση της διεπαφής [Line](../../com.groupdocs.viewer.results/line) με την καθορισμένη γραμμή, θέση, διαστάσεις και λέξεις. |
|
|  | [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | Δημιουργεί μια υλοποίηση της διεπαφής [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | Δημιουργεί μια υλοποίηση της διεπαφής [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | Δημιουργεί μια υλοποίηση της διεπαφής [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | Δημιουργεί μια υλοποίηση της διεπαφής [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | Δημιουργεί μια υλοποίηση της διεπαφής [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) βάσει του καθορισμένου τύπου αρχείου, |
λίστα σελίδων και λίστα φακέλων.
|
|  | [newPage(int number, boolean visible)](#newPage-int-boolean-) | Δημιουργεί μια υλοποίηση της διεπαφής [Page](../../com.groupdocs.viewer.results/page) που αντιπροσωπεύει μια σελίδα με τον καθορισμένο αριθμό και ορατότητα. |
|
|  | [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | Δημιουργεί μια υλοποίηση της διεπαφής [Page](../../com.groupdocs.viewer.results/page) που αντιπροσωπεύει μια σελίδα με τον καθορισμένο αριθμό, όνομα και ορατότητα. |
|
|  | [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | Δημιουργεί μια υλοποίηση της διεπαφής [Page](../../com.groupdocs.viewer.results/page) που αντιπροσωπεύει μια σελίδα με τον καθορισμένο αριθμό, όνομα, ορατότητα, πλάτος και ύψος. |
|
|  | [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | Δημιουργεί μια υλοποίηση της διεπαφής [Page](../../com.groupdocs.viewer.results/page) που αντιπροσωπεύει μια σελίδα με τον καθορισμένο αριθμό, ορατότητα, πλάτος και ύψος. |
|
|  | [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Δημιουργεί μια υλοποίηση της διεπαφής [Page](../../com.groupdocs.viewer.results/page) που αντιπροσωπεύει μια σελίδα με τον καθορισμένο αριθμό, όνομα, ορατότητα, πλάτος, ύψος και γραμμές. |
|
|  | [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | Δημιουργεί μια υλοποίηση της διεπαφής [Page](../../com.groupdocs.viewer.results/page) που αντιπροσωπεύει μια σελίδα με τον καθορισμένο αριθμό, ορατότητα, πλάτος, ύψος και γραμμές. |
|
|  | [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | Δημιουργεί μια υλοποίηση της διεπαφής [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) με τον καθορισμένο τύπο αρχείου, σελίδες και σημαία επιτρεπόμενης εκτύπωσης. |
|
|  | [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | Δημιουργεί μια υλοποίηση της διεπαφής [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) με τον καθορισμένο τύπο αρχείου, σελίδες, στρώματα και διατάξεις. |
|
|  | [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | Δημιουργεί μια υλοποίηση της διεπαφής [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) με τον καθορισμένο τύπο αρχείου, σελίδες, ημερομηνία έναρξης και ημερομηνία λήξης. |
|
|  | [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | Δημιουργεί μια υλοποίηση της διεπαφής [TextElement](../../com.groupdocs.viewer.results/textelement) με την καθορισμένη τιμή, συντεταγμένες και διαστάσεις. |
|
|  | [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | Δημιουργεί μια υλοποίηση της διεπαφής MboxViewInfo με τον καθορισμένο τύπο αρχείου, σελίδες και αριθμό σημειώσεων. |
|
|  | [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | Δημιουργεί μια υλοποίηση της διεπαφής [Word](../../com.groupdocs.viewer.results/word) με την καθορισμένη λέξη, συντεταγμένες, διαστάσεις και χαρακτήρες. |
|
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


Λαμβάνει μια παρουσία του
CacheableFactory
που μπορεί να χρησιμοποιηθεί για τη δημιουργία αντικειμένων cacheable.


**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .

### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


Ορίζει την παρουσία του
CacheableFactory
για χρήση. Αυτό επιτρέπει προσαρμοσμένη υλοποίηση του cacheable factory.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | Η παρουσία του  CacheableFactory  που θα οριστεί. |
|

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


Δημιουργεί μια υλοποίηση της διεπαφής [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) για τον καθορισμένο τύπο αρχείου και τις σελίδες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Ο τύπος του αρχείου. |
|
|  | σελίδες | java.util.List<com.groupdocs.viewer.results.Page> | Η λίστα των σελίδων που αντιπροσωπεύουν τις σελίδες του εγγράφου. |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.

### newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from) {#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-}
```
public ViewInfo newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) |  |
| σελίδες | java.util.List<com.groupdocs.viewer.results.Page> |  |
| originalMessageDate | java.util.Date |  |
| θέμα | java.lang.String |  |
| από | java.lang.String |  |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Δημιουργεί μια υλοποίηση της διεπαφής [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) για τον καθορισμένο τύπο αρχείου, τις σελίδες και τον αριθμό σημειώσεων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Ο τύπος του αρχείου. |
|
|  | σελίδες | java.util.List<com.groupdocs.viewer.results.Page> | Η λίστα των σελίδων που αντιπροσωπεύουν τις σελίδες του εγγράφου. |
|
|  | notesCount | int | Ο αριθμός των Lotus Notes στο έγγραφο. |
|

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.

### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Δημιουργεί μια υλοποίηση της διεπαφής [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) για τον καθορισμένο τύπο αρχείου, τις σελίδες και τους φακέλους.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Ο τύπος του αρχείου. |
|
|  | σελίδες | java.util.List<com.groupdocs.viewer.results.Page> | Η λίστα των σελίδων που αντιπροσωπεύουν τις σελίδες του εγγράφου. |
|
|  | φάκελοι | java.util.List<java.lang.String> | Η λίστα των φακέλων στο αρχείο. |
|

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.

### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Character](../../com.groupdocs.viewer.results/character) για τον καθορισμένο χαρακτήρα, τη θέση και τις διαστάσεις.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | χαρακτήρας | char | Ο χαρακτήρας. |
|
|  | x | double | Η x-συντεταγμένη της θέσης του χαρακτήρα. |
|
|  | y | double | Η y-συντεταγμένη της θέσης του χαρακτήρα. |
|
|  | width | double | Το πλάτος του χαρακτήρα. |
|
|  | ύψος | double | Το ύψος του χαρακτήρα. |
|

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.

### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


Δημιουργεί μια υλοποίηση της διεπαφής [FileInfo](../../com.groupdocs.viewer.results/fileinfo) για τον καθορισμένο τύπο αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Ο τύπος του αρχείου. |
|

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.

### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Layer](../../com.groupdocs.viewer.results/layer) με το καθορισμένο όνομα και ορατότητα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Το όνομα του επιπέδου. |
|
|  | ορατό | boolean | Η ορατότητα του επιπέδου. |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Layer](../../com.groupdocs.viewer.results/layer) με το καθορισμένο όνομα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Το όνομα του επιπέδου. |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Layout](../../com.groupdocs.viewer.results/layout) με το καθορισμένο όνομα, πλάτος και ύψος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | όνομα | java.lang.String | Το όνομα της διάταξης. |
|
|  | width | double | Το πλάτος της διάταξης. |
|
|  | ύψος | double | Το ύψος της διάταξης. |
|

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.

### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Line](../../com.groupdocs.viewer.results/line) με την καθορισμένη γραμμή, θέση, διαστάσεις και λέξεις.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | γραμμή | java.lang.String | Το περιεχόμενο της γραμμής. |
|
|  | x | double | Η X-συντεταγμένη του πάνω αριστερού σημείου του ορθογωνίου που περιέχει τη γραμμή. |
|
|  | y | double | Η Y-συντεταγμένη του πάνω αριστερού σημείου του ορθογωνίου που περιέχει τη γραμμή. |
|
|  | width | double | The πλάτος του ορθογωνίου που περιέχει τη γραμμή (σε εικονοστοιχεία). |
|
|  | ύψος | double | Το ύψος του ορθογωνίου που περιέχει τη γραμμή (σε εικονοστοιχεία). |
|
|  | λέξεις | java.util.List<com.groupdocs.viewer.results.Word> | Οι λέξεις που περιέχονται στη γραμμή. |
|

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.

### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileName | java.lang.String | Το όνομα του συνημμένου. |
|
|  | filePath | java.lang.String | Η σχετική διαδρομή του συνημμένου, π.χ., "folder/file.docx". Όταν το αρχείο βρίσκεται στη ρίζα ενός αρχείου, σε ένα μήνυμα ηλεκτρονικού ταχυδρομείου ή σε ένα αρχείο δεδομένων, καθορίστε το όνομα αρχείου. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | id | java.lang.String | Το ID του συνημμένου. |
|
|  | fileName | java.lang.String | Το όνομα του συνημμένου. |
|
|  | filePath | java.lang.String | Η σχετική διαδρομή του συνημμένου, π.χ., "folder/file.docx". Όταν το αρχείο βρίσκεται στη ρίζα ενός αρχείου, σε ένα μήνυμα ηλεκτρονικού ταχυδρομείου ή σε ένα αρχείο δεδομένων, καθορίστε το όνομα αρχείου. |
|
|  | size | long | Το μέγεθος του συνημμένου. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Attachment](../../com.groupdocs.viewer.results/attachment).


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | id | java.lang.String | Το ID του συνημμένου. |
|
|  | fileName | java.lang.String | Το όνομα του συνημμένου. |
|
|  | filePath | java.nio.file.Path | Η σχετική ή απόλυτη διαδρομή του συνημμένου. |
|
|  | size | long | Το μέγεθος του συνημμένου. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Attachment](../../com.groupdocs.viewer.results/attachment). Το συνημμένο αντιπροσωπεύει ένα αρχείο που επισυνάπτεται σε ένα έγγραφο ή σε ένα μήνυμα ηλεκτρονικού ταχυδρομείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | id | java.lang.String | Το ID του συνημμένου. |
|
|  | fileName | java.lang.String | Το όνομα του συνημμένου. |
|
|  | filePath | java.lang.String | Η σχετική ή απόλυτη διαδρομή του συνημμένου. Μπορεί να είναι μια διαδρομή αρχείου μέσα σε φάκελο ή το ίδιο το όνομα αρχείου εάν το αρχείο βρίσκεται στη ρίζα ενός αρχείου, σε ένα μήνυμα ηλεκτρονικού ταχυδρομείου ή σε ένα αρχείο δεδομένων. |
|
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Ο τύπος του αρχείου συνημμένου. |
|
|  | size | long | Το μέγεθος του συνημμένου. |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


Δημιουργεί μια υλοποίηση της διεπαφής [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) βάσει του καθορισμένου τύπου αρχείου,
λίστα σελίδων και λίστα φακέλων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Ο τύπος του αρχείου. |
|
|  | σελίδες | java.util.List<com.groupdocs.viewer.results.Page> | Η λίστα των σελίδων. |
|
|  | φάκελοι | java.util.List<java.lang.String> | Η λίστα των φακέλων. |
|

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.

### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Page](../../com.groupdocs.viewer.results/page) που αντιπροσωπεύει μια σελίδα με τον καθορισμένο αριθμό και ορατότητα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | number | int | Ο αριθμός της σελίδας. |
|
|  | ορατό | boolean | Η σημαία ορατότητας. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Page](../../com.groupdocs.viewer.results/page) που αντιπροσωπεύει μια σελίδα με τον καθορισμένο αριθμό, όνομα και ορατότητα.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | number | int | Ο αριθμός της σελίδας. |
|
|  | όνομα | java.lang.String | Το όνομα της σελίδας. |
|
|  | ορατό | boolean | Η σημαία ορατότητας. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Page](../../com.groupdocs.viewer.results/page) που αντιπροσωπεύει μια σελίδα με τον καθορισμένο αριθμό, όνομα, ορατότητα, πλάτος και ύψος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | number | int | Ο αριθμός της σελίδας. |
|
|  | όνομα | java.lang.String | Το όνομα της σελίδας. |
|
|  | ορατό | boolean | Η σημαία ορατότητας. |
|
|  | width | int | Το πλάτος της σελίδας. |
|
|  | ύψος | int | Το ύψος της σελίδας. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Page](../../com.groupdocs.viewer.results/page) που αντιπροσωπεύει μια σελίδα με τον καθορισμένο αριθμό, ορατότητα, πλάτος και ύψος.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | number | int | Ο αριθμός της σελίδας. |
|
|  | ορατό | boolean | Η σημαία ορατότητας. |
|
|  | width | int | Το πλάτος της σελίδας. |
|
|  | ύψος | int | Το ύψος της σελίδας. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Page](../../com.groupdocs.viewer.results/page) που αντιπροσωπεύει μια σελίδα με τον καθορισμένο αριθμό, όνομα, ορατότητα, πλάτος, ύψος και γραμμές.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | number | int | Ο αριθμός της σελίδας. |
|
|  | όνομα | java.lang.String | Το όνομα της σελίδας. |
|
|  | ορατό | boolean | Η σημαία ορατότητας. |
|
|  | width | int | Το πλάτος της σελίδας. |
|
|  | ύψος | int | Το ύψος της σελίδας. |
|
|  | γραμμές | java.util.List<com.groupdocs.viewer.results.Line> | Οι γραμμές που περιέχονται στη σελίδα. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Page](../../com.groupdocs.viewer.results/page) που αντιπροσωπεύει μια σελίδα με τον καθορισμένο αριθμό, ορατότητα, πλάτος, ύψος και γραμμές.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | number | int | Ο αριθμός της σελίδας. |
|
|  | ορατό | boolean | Η σημαία ορατότητας. |
|
|  | width | int | Το πλάτος της σελίδας. |
|
|  | ύψος | int | Το ύψος της σελίδας. |
|
|  | γραμμές | java.util.List<com.groupdocs.viewer.results.Line> | Οι γραμμές που περιέχονται στη σελίδα. |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


Δημιουργεί μια υλοποίηση της διεπαφής [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) με τον καθορισμένο τύπο αρχείου, σελίδες και σημαία επιτρεπόμενης εκτύπωσης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Ο τύπος του αρχείου. |
|
|  | σελίδες | java.util.List<com.groupdocs.viewer.results.Page> | Η λίστα των σελίδων. |
|
|  | printingAllowed | boolean | Η σημαία που υποδεικνύει αν επιτρέπεται η εκτύπωση. |
|

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.

### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


Δημιουργεί μια υλοποίηση της διεπαφής [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) με τον καθορισμένο τύπο αρχείου, σελίδες, στρώματα και διατάξεις.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Ο τύπος του αρχείου. |
|
|  | σελίδες | java.util.List<com.groupdocs.viewer.results.Page> | Η λίστα των σελίδων. |
|
|  | επίπεδα | java.util.List<com.groupdocs.viewer.results.Layer> | Η λίστα των επιπέδων. |
|
|  | διατάξεις | java.util.List<com.groupdocs.viewer.results.Layout> | Η λίστα των διατάξεων. |
|

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.

### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


Δημιουργεί μια υλοποίηση της διεπαφής [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) με τον καθορισμένο τύπο αρχείου, σελίδες, ημερομηνία έναρξης και ημερομηνία λήξης.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Ο τύπος του αρχείου. |
|
|  | σελίδες | java.util.List<com.groupdocs.viewer.results.Page> | Η λίστα των σελίδων. |
|
|  | startDate | java.util.Date | Η ημερομηνία έναρξης. |
|
|  | endDate | java.util.Date | Η ημερομηνία λήξης. |
|

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.

### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


Δημιουργεί μια υλοποίηση της διεπαφής [TextElement](../../com.groupdocs.viewer.results/textelement) με την καθορισμένη τιμή, συντεταγμένες και διαστάσεις.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | T | Η τιμή. |
|
|  | x | double | Η συντεταγμένη X. |
|
|  | y | double | Η συντεταγμένη Y. |
|
|  | width | double | Το πλάτος. |
|
|  | ύψος | double | Το ύψος. |
|

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.

### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


Δημιουργεί μια υλοποίηση της διεπαφής MboxViewInfo με τον καθορισμένο τύπο αρχείου, σελίδες και αριθμό σημειώσεων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | Ο τύπος του αρχείου. |
|
|  | σελίδες | java.util.List<com.groupdocs.viewer.results.Page> | Η λίστα των σελίδων για προβολή. |
|
|  | notesCount | int | Ο αριθμός σημειώσεων που περιέχεται στο αρχείο αποθήκευσης βάσης δεδομένων Lotus. |
|

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - μια νέα παρουσία της υλοποίησης MboxViewInfo.

### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


Δημιουργεί μια υλοποίηση της διεπαφής [Word](../../com.groupdocs.viewer.results/word) με την καθορισμένη λέξη, συντεταγμένες, διαστάσεις και χαρακτήρες.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | λέξη | java.lang.String | Η λέξη. |
|
|  | x | double | Η συντεταγμένη X του υψηλότερου αριστερού σημείου στη διάταξη της σελίδας όπου αρχίζει το ορθογώνιο που περιέχει τη λέξη. |
|
|  | y | double | Η συντεταγμένη Y του υψηλότερου αριστερού σημείου στη διάταξη της σελίδας όπου αρχίζει το ορθογώνιο που περιέχει τη λέξη. |
|
|  | width | double | Το πλάτος του ορθογωνίου που περιέχει τη λέξη (σε εικονοστοιχεία). |
|
|  | ύψος | double | Το ύψος του ορθογωνίου που περιέχει τη λέξη (σε εικονοστοιχεία). |
|
|  | χαρακτήρες | java.util.List<com.groupdocs.viewer.results.Character> | Οι χαρακτήρες που περιέχονται στη λέξη. |
|

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.

