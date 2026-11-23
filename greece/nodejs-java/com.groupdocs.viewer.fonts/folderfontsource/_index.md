---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Αναπαριστά έναν φάκελο που περιέχει γραμματοσειρές TrueType."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

Αναπαριστά έναν φάκελο που περιέχει γραμματοσειρές TrueType.

Η κλάση FolderFontSource χρησιμοποιείται για να καθορίσει τη θέση ενός φακέλου που περιέχει γραμματοσειρές TrueType. Επιτρέπει στο API του GroupDocs.Viewer να έχει πρόσβαση στις γραμματοσειρές που αποθηκεύονται στον καθορισμένο φάκελο για σκοπούς απόδοσης εγγράφων.

Παράδειγμα χρήσης:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | Αρχικοποιεί μια νέα παρουσία της κλάσης FolderFontSource. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Καθορίζει εάν δύο αντικείμενα FolderFontSource είναι τα ίδια. |
| [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Καθορίζει εάν δύο αντικείμενα FolderFontSource δεν είναι τα ίδια. |
| [getFolderPath()](#getFolderPath--) | Λαμβάνει τη διαδρομή προς το φάκελο που περιέχει γραμματοσειρές TrueType. |
| [getSearchOption()](#getSearchOption--) | Λαμβάνει την επιλογή αναζήτησης που καθορίζει εάν θα αναζητηθεί ο τρέχων φάκελος ή ο τρέχων φάκελος και όλοι οι υποφάκελοι. |
| [isRecursive()](#isRecursive--) | Ελέγχει εάν οι γραμματοσειρές θα αναζητηθούν αναδρομικά. |
| [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | Καθορίζει εάν το τρέχον FolderFontSource είναι το ίδιο με το καθορισμένο αντικείμενο FolderFontSource. |
| [equals(Object o)](#equals-java.lang.Object-) | Καθορίζει εάν το τρέχον FolderFontSource είναι το ίδιο με το καθορισμένο αντικείμενο. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για το τρέχον αντικείμενο FolderFontSource. |
| [toString()](#toString--) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης FolderFontSource.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| folderPath | java.lang.String | Διαδρομή προς το φάκελο που περιέχει γραμματοσειρές TrueType. |
| searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | Καθορίζει εάν θα αναζητηθεί ο τρέχων φάκελος ή ο τρέχων φάκελος και όλοι οι υποφάκελοι. |

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


Καθορίζει εάν δύο αντικείμενα FolderFontSource είναι τα ίδια.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Το αριστερό αντικείμενο FolderFontSource. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Το δεξί αντικείμενο FolderFontSource. |

**Returns:**
boolean - true εάν και τα δύο αντικείμενα FolderFontSource είναι τα ίδια· διαφορετικά, false.
### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


Καθορίζει εάν δύο αντικείμενα FolderFontSource δεν είναι τα ίδια.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Το αριστερό αντικείμενο FolderFontSource. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Το δεξί αντικείμενο FolderFontSource. |

**Returns:**
boolean - true εάν και τα δύο αντικείμενα FolderFontSource δεν είναι τα ίδια· διαφορετικά, false.
### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


Λαμβάνει τη διαδρομή προς το φάκελο που περιέχει γραμματοσειρές TrueType.

**Returns:**
java.lang.String - η διαδρομή προς το φάκελο που περιέχει γραμματοσειρές TrueType.
### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


Λαμβάνει την επιλογή αναζήτησης που καθορίζει εάν θα αναζητηθεί ο τρέχων φάκελος ή ο τρέχων φάκελος και όλοι οι υποφάκελοι.

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.
### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


Ελέγχει εάν οι γραμματοσειρές θα αναζητηθούν αναδρομικά.

**Returns:**
boolean - true εάν οι γραμματοσειρές θα αναζητηθούν αναδρομικά, false διαφορετικά.
### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


Καθορίζει εάν το τρέχον FolderFontSource είναι το ίδιο με το καθορισμένο αντικείμενο FolderFontSource.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Το αντικείμενο για σύγκριση με το τρέχον αντικείμενο FolderFontSource. |

**Returns:**
boolean - true εάν και τα δύο αντικείμενα FolderFontSource είναι τα ίδια· διαφορετικά, false
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Καθορίζει εάν το τρέχον FolderFontSource είναι το ίδιο με το καθορισμένο αντικείμενο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| o | java.lang.Object | Το αντικείμενο για σύγκριση με το τρέχον αντικείμενο FolderFontSource. |

**Returns:**
boolean - true εάν η παράμετρος obj είναι τύπου FolderFontSource και είναι η ίδια με το τρέχον αντικείμενο FolderFontSource· διαφορετικά, false
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για το τρέχον αντικείμενο FolderFontSource.

**Returns:**
int - ένας κωδικός κατακερματισμού για το τρέχον αντικείμενο FolderFontSource.
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο.

**Returns:**
java.lang.String - μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο.
