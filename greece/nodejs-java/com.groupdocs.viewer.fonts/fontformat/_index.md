---
title: "FontFormat"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Αναπαριστά όλες τις μορφές γραμματοσειρών που μπορεί να υπάρχουν στην κλάση UsedFontInfo."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

Αναπαριστά όλες τις μορφές γραμματοσειρών, που μπορεί να υπάρχουν στην κλάση UsedFontInfo.
## Fields

| Field | Περιγραφή |
| --- | --- |
| [Unknown](#Unknown) | Άγνωστη ή μη έγκυρη μορφή γραμματοσειράς. |
| [TrueType](#TrueType) | Μορφή γραμματοσειράς TrueType (TTF). |
| [OpenType](#OpenType) | Μορφή γραμματοσειράς OpenType (OTF). |
| [TrueTypeCollection](#TrueTypeCollection) | Μορφή γραμματοσειράς TrueType Collection (TTC). |
| [EmbeddedOpenType](#EmbeddedOpenType) | Μορφή ενσωματωμένης γραμματοσειράς OpenType (EOT). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [toString(int format)](#toString-int-) | Μετατρέπει μια τιμή μορφής σε αναγνώσιμη από άνθρωπο συμβολοσειρά. |
### Unknown {#Unknown}
```
public static final int Unknown
```


Άγνωστη ή μη έγκυρη μορφή γραμματοσειράς.

### TrueType {#TrueType}
```
public static final int TrueType
```


Μορφή γραμματοσειράς TrueType (TTF).

### OpenType {#OpenType}
```
public static final int OpenType
```


Μορφή γραμματοσειράς OpenType (OTF).

### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


Μορφή γραμματοσειράς TrueType Collection (TTC).

### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


Μορφή ενσωματωμένης γραμματοσειράς OpenType (EOT).

### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


Μετατρέπει μια τιμή μορφής σε αναγνώσιμη από άνθρωπο συμβολοσειρά.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μορφή | int | η τιμή μορφής γραμματοσειράς |

**Returns:**
java.lang.String - μια αναπαράσταση συμβολοσειράς της μορφής γραμματοσειράς
