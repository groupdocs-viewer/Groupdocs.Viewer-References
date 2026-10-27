---
title: "FontFormat"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt alle lettertypeformaten voor die aanwezig kunnen zijn in de UsedFontInfo‑klasse."
type: docs
weight: 11
url: /nl/nodejs-java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

Stelt alle lettertypeformaten voor, die aanwezig kunnen zijn in de UsedFontInfo-klasse.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Unknown](#Unknown) | Onbekend of ongeldig lettertypeformaat. |
| [TrueType](#TrueType) | TrueType-lettertypeformaat (TTF). |
| [OpenType](#OpenType) | OpenType-lettertypeformaat (OTF). |
| [TrueTypeCollection](#TrueTypeCollection) | TrueType Collection-lettertypeformaat (TTC). |
| [EmbeddedOpenType](#EmbeddedOpenType) | Embedded OpenType-lettertypeformaat (EOT). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [toString(int format)](#toString-int-) | Converteert een formaatwaarde naar een menselijk leesbare tekenreeks. |
### Unknown {#Unknown}
```
public static final int Unknown
```


Onbekend of ongeldig lettertypeformaat.

### TrueType {#TrueType}
```
public static final int TrueType
```


TrueType-lettertypeformaat (TTF).

### OpenType {#OpenType}
```
public static final int OpenType
```


OpenType-lettertypeformaat (OTF).

### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


TrueType Collection-lettertypeformaat (TTC).

### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


Embedded OpenType-lettertypeformaat (EOT).

### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


Converteert een formaatwaarde naar een menselijk leesbare tekenreeks.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| formaat | int | de lettertypeformaatwaarde |

**Returns:**
java.lang.String - een tekenreeksrepresentatie van het lettertypeformaat
