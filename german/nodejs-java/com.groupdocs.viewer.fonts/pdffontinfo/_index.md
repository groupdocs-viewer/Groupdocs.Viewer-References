---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Kapselt Metainformationen und Binärdaten einer Schrift aus einem PDF-Dokument, das in die Viewer-Instanz geladen wurde."
type: docs
weight: 14
url: /de/nodejs-java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

Kapselt Metainformationen und Binärdaten einer Schrift aus einem PDF-Dokument, die in die Viewer-Instanz geladen wurden.

Diese Schrift wird im Dokumentinhalt verwendet und ist entweder:

 *  embedded inside the PDF document
 *  or installed in the operating system where GroupDocs.Viewer is running
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | Interner Konstruktor, der bei der PDF-Schriftextraktion verwendet wird. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Liefert den Schriftfamiliennamen. |
| [getStyle()](#getStyle--) | Liefert den Stil dieser Schrift. |
| [isEmbedded()](#isEmbedded--) | Gibt zurück, ob die Schrift im PDF-Dokument eingebettet ist. |
| [isInstalled()](#isInstalled--) | Gibt zurück, ob die Schrift im Betriebssystem installiert ist. |
| [getFormat()](#getFormat--) | Gibt das Dateiformat der Schrift zurück. |
| [getContent()](#getContent--) | Gibt den binären Inhalt der Schrift zurück. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialisiert diese Schrift als CSS @font-face-Regel. |
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


Interner Konstruktor, der bei der PDF-Schriftextraktion verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| familyName | java.lang.String | Schriftfamilienname |
| Stil | com.groupdocs.viewer.fonts.FontStyles | Stil (Regular, Bold, Italic, BoldItalic) |
| isEmbedded | boolean | true, wenn die Schrift im PDF eingebettet ist |
| isInstalled | boolean | true, wenn die Schrift im Betriebssystem installiert ist |
| content | byte[] | binäre Schriftartdaten (nullable) |
| format | int | Schriftdateiformat |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Liefert den Schriftfamiliennamen.

**Returns:**
java.lang.String - Familiennamen-String (niemals null oder leer)
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Liefert den Stil dieser Schrift.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles - der Schriftstil
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Gibt zurück, ob die Schrift im PDF-Dokument eingebettet ist.

**Returns:**
boolean - true, wenn eingebettet
### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


Gibt zurück, ob die Schrift im Betriebssystem installiert ist.

**Returns:**
boolean - true, wenn installiert
### getFormat() {#getFormat--}
```
public int getFormat()
```


Gibt das Dateiformat der Schrift zurück.

**Returns:**
int - das Schriftformat-Enum
### getContent() {#getContent--}
```
public byte[] getContent()
```


Gibt den binären Inhalt der Schrift zurück.

**Returns:**
byte[] - Byte-Array oder null, falls nicht verfügbar
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialisiert diese Schrift als CSS @font-face-Regel.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| output | java.io.Writer | Schreiber, in den das CSS geschrieben wird |

