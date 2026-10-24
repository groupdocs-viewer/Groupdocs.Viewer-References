---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Kapselt Metainformationen und Binärdaten einer Schriftart aus einem PDF-Dokument, das in die Viewer-Instanz geladen wurde."
type: docs
weight: 14
url: /de/java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

Kapselt Metainformationen und Binärdaten einer Schriftart aus einem PDF-Dokument, das in die Viewer-Instanz geladen wurde.


Diese Schriftart wird im Dokumentinhalt verwendet und ist entweder:

* embedded inside the PDF document
* or installed in the operating system where GroupDocs.Viewer is running

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | Interner Konstruktor, der bei der PDF-Schriftart-Extraktion verwendet wird. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Gibt den Schriftfamiliennamen zurück. |
|
|  | [getStyle()](#getStyle--) | Gibt den Stil dieser Schriftart zurück. |
|
|  | [isEmbedded()](#isEmbedded--) | Gibt zurück, ob die Schriftart im PDF-Dokument eingebettet ist. |
|
|  | [isInstalled()](#isInstalled--) | Gibt zurück, ob die Schriftart im Betriebssystem installiert ist. |
|
|  | [getFormat()](#getFormat--) | Gibt das Dateiformat der Schriftart zurück. |
|
|  | [getContent()](#getContent--) | Gibt den Binärinhalt der Schriftart zurück. |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialisiert diese Schriftart als CSS  @font-face  Regel. |
|
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


Interner Konstruktor, der bei der PDF-Schriftart-Extraktion verwendet wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | familyName | java.lang.String | Schriftfamilienname |
|
|  | Stil | com.groupdocs.viewer.fonts.FontStyles | Stil (Regular, Bold, Italic, BoldItalic) |
|
|  | isEmbedded | boolesch | true, wenn die Schrift im PDF eingebettet ist |
|
|  | isInstalled | boolesch | true, wenn die Schrift im Betriebssystem installiert ist |
|
|  | Inhalt | byte[] | binäre Schriftartdaten (nullable) |
|
|  | Format | int | Schriftdateiformat |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Gibt den Schriftfamiliennamen zurück.


**Returns:**
java.lang.String - Familiennamen-String (niemals null oder leer)

### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Gibt den Stil dieser Schriftart zurück.


**Returns:**
com.groupdocs.viewer.fonts.FontStyles - der Schriftstil

### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Gibt zurück, ob die Schriftart im PDF-Dokument eingebettet ist.


**Returns:**
boolean - true, wenn eingebettet

### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


Gibt zurück, ob die Schriftart im Betriebssystem installiert ist.


**Returns:**
boolean - true, wenn installiert

### getFormat() {#getFormat--}
```
public int getFormat()
```


Gibt das Dateiformat der Schriftart zurück.


**Returns:**
int - das Schriftformat-Enum

### getContent() {#getContent--}
```
public byte[] getContent()
```


Gibt den Binärinhalt der Schriftart zurück.


**Returns:**
byte[] - Byte-Array oder null, wenn nicht verfügbar

### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialisiert diese Schriftart als CSS  @font-face  Regel.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Ausgabe | java.io.Writer | Writer, in den CSS geschrieben wird |
|

