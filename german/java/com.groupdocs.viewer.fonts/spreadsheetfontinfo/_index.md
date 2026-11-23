---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Kapselt Metainformationen und Binärdaten einer Schriftart aus dem Tabellenkalkulationsdokument, das in die Viewer-Instanz geladen wurde."
type: docs
weight: 16
url: /de/java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Kapselt Metainformationen und Binärdaten einer Schriftart aus dem Tabellenkalkulationsdokument, das in die Viewer-Instanz geladen wurde. Tabellenkalkulationsdokumente können keine eingebetteten Schriftarten haben, daher ist diese spezielle Schriftart, falls sie von der Methode Viewer.getAllFonts() zurückgegeben wird, im Betriebssystem installiert, in dem GroupDocs.Viewer ausgeführt wird.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Familienname der Schrift, ohne Stil, niemals null oder leer. |
|
|  | [getStyle()](#getStyle--) | Stil dieser Schriftart \u2014 kann Regular, Bold, Italic oder BoldItalic sein. |
|
|  | [isStrikeout()](#isStrikeout--) | Gibt an, ob die Schriftart ein einzelnes Durchstreichen aufweist. |
|
|  | [isUnderline()](#isUnderline--) | Gibt an, ob die Schriftart unterstrichen ist. |
|
|  | [getColor()](#getColor--) | Farbe dieser Schriftart. |
|
|  | [getCharset()](#getCharset--) | Zeichensatz dieser Schriftart. |
|
|  | [getContent()](#getContent--) | Inhalt dieser Schriftart als Byte-Array. |
|
|  | [getFormat()](#getFormat--) | Format dieser Schriftart. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialisiert diese Schriftart-Informationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Writer. |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Familienname der Schrift, ohne Stil, niemals null oder leer.


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Stil dieser Schriftart \u2014 kann Regular, Bold, Italic oder BoldItalic sein.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


Gibt an, ob die Schriftart ein einzelnes Durchstreichen aufweist.


**Returns:**
boolesch
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Gibt an, ob die Schriftart unterstrichen ist.


**Returns:**
boolesch
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


Farbe dieser Schriftart.


**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### getCharset() {#getCharset--}
```
public int getCharset()
```


Zeichensatz dieser Schriftart.


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Inhalt dieser Schriftart als Byte-Array. Kann null sein, wenn nur Metainformationen verfügbar sind.


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


Format dieser Schriftart.


**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialisiert diese Schriftart-Informationen als @font-face‑At‑Rule und schreibt sie in den angegebenen Writer.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Ausgabe | java.io.Writer | Gerät, in das serialisierte Textdaten geschrieben werden. |
|

