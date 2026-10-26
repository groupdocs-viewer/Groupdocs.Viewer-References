---
title: "FontFormat"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt alle Schriftformat‑Typen dar, die in der Klasse UsedFontInfo vorkommen können."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

Stellt alle Schriftformate dar, die in der Klasse UsedFontInfo vorhanden sein können.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Unknown](#Unknown) | Unbekanntes oder ungültiges Schriftformat. |
| [TrueType](#TrueType) | TrueType‑Schriftformat (TTF). |
| [OpenType](#OpenType) | OpenType‑Schriftformat (OTF). |
| [TrueTypeCollection](#TrueTypeCollection) | TrueType‑Collection‑Schriftformat (TTC). |
| [EmbeddedOpenType](#EmbeddedOpenType) | Embedded‑OpenType‑Schriftformat (EOT). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [toString(int format)](#toString-int-) | Konvertiert einen Formatwert in eine menschenlesbare Zeichenkette. |
### Unknown {#Unknown}
```
public static final int Unknown
```


Unbekanntes oder ungültiges Schriftformat.

### TrueType {#TrueType}
```
public static final int TrueType
```


TrueType‑Schriftformat (TTF).

### OpenType {#OpenType}
```
public static final int OpenType
```


OpenType‑Schriftformat (OTF).

### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


TrueType‑Collection‑Schriftformat (TTC).

### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


Embedded‑OpenType‑Schriftformat (EOT).

### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


Konvertiert einen Formatwert in eine menschenlesbare Zeichenkette.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | int | der Schriftformatwert |

**Returns:**
java.lang.String – eine String‑Darstellung des Schriftformats
