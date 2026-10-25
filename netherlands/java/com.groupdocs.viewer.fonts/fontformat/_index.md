---
title: "FontFormat"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Stelt alle lettertype‑formaten voor die aanwezig kunnen zijn in de UsedFontInfo‑klasse."
type: docs
weight: 11
url: /nl/java/com.groupdocs.viewer.fonts/fontformat/
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
|  | [Unknown](#Unknown) | Onbekend of ongeldig lettertype‑formaat. |
|
|  | [TrueType](#TrueType) | TrueType‑lettertypeformaat (TTF). |
|
|  | [OpenType](#OpenType) | OpenType‑lettertypeformaat (OTF). |
|
|  | [TrueTypeCollection](#TrueTypeCollection) | TrueType‑Collectie‑lettertypeformaat (TTC). |
|
|  | [EmbeddedOpenType](#EmbeddedOpenType) | Embedded OpenType‑lettertypeformaat (EOT). |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [toString(int format)](#toString-int-) | Converteert een formaatwaarde naar een menselijk leesbare tekenreeks. |
|
### Unknown {#Unknown}
```
public static final int Unknown
```


Onbekend of ongeldig lettertype‑formaat.


### TrueType {#TrueType}
```
public static final int TrueType
```


TrueType‑lettertypeformaat (TTF).


### OpenType {#OpenType}
```
public static final int OpenType
```


OpenType‑lettertypeformaat (OTF).


### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


TrueType‑Collectie‑lettertypeformaat (TTC).


### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


Embedded OpenType‑lettertypeformaat (EOT).


### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


Converteert een formaatwaarde naar een menselijk leesbare tekenreeks.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | formaat | int | de lettertype‑formaatwaarde |
|

**Returns:**
java.lang.String - een tekenreeksrepresentatie van het lettertype‑formaat

