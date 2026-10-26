---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Kapselt Metadaten und Binärdaten einer Schriftart, die in einem Presentation-Dokument verwendet wird, das in die Viewer-Instanz geladen wurde."
type: docs
weight: 15
url: /de/nodejs-java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Kapselt Metadaten und Binärdaten einer Schriftart, die in einem Presentation-Dokument verwendet wird, das in die Viewer-Instanz geladen wurde. Diese Schriftart wird im Dokumentinhalt verwendet und kann entweder im Dokument selbst eingebettet oder im Betriebssystem, auf dem GroupDocs.Viewer läuft, installiert sein.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Liefert den Schriftfamiliennamen (niemals null oder leer). |
| [getStyle()](#getStyle--) | Liefert den Stil der Schriftart: Regular, Bold, Italic oder BoldItalic. |
| [isEmbedded()](#isEmbedded--) | Gibt an, ob diese Schriftart im in die Viewer-Instanz geladenen Dokument eingebettet ist. |
| [getFormat()](#getFormat--) | Liefert das Schriftformat (TrueType, OpenType usw.). |
| [getContent()](#getContent--) | Liefert den binären Schriftinhalt oder null, falls die Schriftartdaten nicht verfügbar sind. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialisiert diese Schriftartinformationen in eine CSS @font-face-Regel unter Verwendung des angegebenen Writers. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Liefert den Schriftfamiliennamen (niemals null oder leer).

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Liefert den Stil der Schriftart: Regular, Bold, Italic oder BoldItalic.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Gibt an, ob diese Schriftart im in die Viewer-Instanz geladenen Dokument eingebettet ist. Hinweis: Spreadsheet-Dokumente können keine eingebetteten Schriftarten enthalten, daher wird für sie stets false zurückgegeben.

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Liefert das Schriftformat (TrueType, OpenType usw.). Wenn nur Metadaten verfügbar sind, wird FontFormat.Unknown zurückgegeben.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Liefert den binären Schriftinhalt oder null, falls die Schriftartdaten nicht verfügbar sind.

**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialisiert diese Schriftartinformationen in eine CSS @font-face-Regel unter Verwendung des angegebenen Writers.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| output | java.io.Writer | Writer, in den das CSS geschrieben wird (darf nicht null sein) |

