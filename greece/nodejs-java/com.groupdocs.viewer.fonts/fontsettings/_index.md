---
title: "FontSettings"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Παρέχει μεθόδους για τη δουλειά με πηγές ώστε να εντοπίζει γραμματοσειρές TrueType."
type: docs
weight: 12
url: /el/nodejs-java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

Παρέχει μεθόδους για τη δουλειά με πηγές ώστε να εντοπίζει γραμματοσειρές TrueType.

Η κλάση FontSettings χρησιμοποιείται για τον καθορισμό και τη διαχείριση πηγών για την εύρεση γραμματοσειρών TrueType. Παρέχει μεθόδους για την προσθήκη και την επαναφορά πηγών γραμματοσειρών για το GroupDocs.Viewer API.

Παράδειγμα χρήσης:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | Ορίζει τις πηγές για την αναζήτηση γραμματοσειρών TrueType κατά την απόδοση εγγράφων. |
| [resetFontSources()](#resetFontSources--) | Επαναφέρει τις πηγές γραμματοσειρών που έχουν οριστεί προηγουμένως. |
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


Ορίζει τις πηγές για την αναζήτηση γραμματοσειρών TrueType κατά την απόδοση εγγράφων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | Οι πηγές γραμματοσειρών προς ορισμό. |

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


Επαναφέρει τις πηγές γραμματοσειρών που έχουν οριστεί προηγουμένως.

