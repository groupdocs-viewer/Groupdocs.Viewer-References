---
title: "PathUtils"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Η κλάση PathUtils παρέχει βοηθητικές μεθόδους για εργασία με διαδρομές αρχείων."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

Η κλάση PathUtils παρέχει βοηθητικές μεθόδους για εργασία με διαδρομές αρχείων.

Η κλάση PathUtils περιέχει στατικές μεθόδους που σας επιτρέπουν να εκτελείτε διάφορες λειτουργίες σε διαδρομές αρχείων στο στοιχείο GroupDocs.Viewer.

Παράδειγμα χρήσης:

```

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
```
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [combine(String[] params)](#combine-java.lang.String...-) | Συνδυάστε τμήματα διαδρομών χρησιμοποιώντας διαχωριστικό. |
| [getFileName(String path)](#getFileName-java.lang.String-) | Λαμβάνει το όνομα αρχείου. |
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


Συνδυάστε τμήματα διαδρομών χρησιμοποιώντας διαχωριστικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| παράμετροι | java.lang.String[] | τα τμήματα διαδρομών |

**Returns:**
java.lang.String - η διαδρομή αποτελέσματος
### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


Λαμβάνει το όνομα αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | java.lang.String | η διαδρομή |

**Returns:**
java.lang.String - το όνομα αρχείου
