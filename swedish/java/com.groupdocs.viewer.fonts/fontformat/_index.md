---
title: "FontFormat"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Representerar alla teckensnittformat som kan finnas i klassen UsedFontInfo."
type: docs
weight: 11
url: /sv/java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

Representerar alla teckensnittformat som kan finnas i klassen UsedFontInfo.

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Unknown](#Unknown) | Okänt eller ogiltigt teckensnittformat. |
|
|  | [TrueType](#TrueType) | TrueType-teckensnittformat (TTF). |
|
|  | [OpenType](#OpenType) | OpenType-teckensnittformat (OTF). |
|
|  | [TrueTypeCollection](#TrueTypeCollection) | TrueType Collection-teckensnittformat (TTC). |
|
|  | [EmbeddedOpenType](#EmbeddedOpenType) | Inbäddat OpenType-teckensnittformat (EOT). |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [toString(int format)](#toString-int-) | Konverterar ett formatvärde till en människoläsbar sträng. |
|
### Unknown {#Unknown}
```
public static final int Unknown
```


Okänt eller ogiltigt teckensnittformat.


### TrueType {#TrueType}
```
public static final int TrueType
```


TrueType-teckensnittformat (TTF).


### OpenType {#OpenType}
```
public static final int OpenType
```


OpenType-teckensnittformat (OTF).


### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


TrueType Collection-teckensnittformat (TTC).


### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


Inbäddat OpenType-teckensnittformat (EOT).


### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


Konverterar ett formatvärde till en människoläsbar sträng.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | format | int | teckensnittformatvärdet |
|

**Returns:**
java.lang.String - en strängrepresentation av teckensnittformatet

