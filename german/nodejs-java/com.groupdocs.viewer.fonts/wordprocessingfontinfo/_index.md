---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Kapselt Metainformationen und Binärdaten einer Schrift aus dem WordProcessing-Dokument, das in die Viewer-Instanz geladen wurde."
type: docs
weight: 17
url: /de/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Kapselt Metainformationen und Binärdaten einer Schrift aus dem WordProcessing-Dokument, das in die Viewer-Instanz geladen wurde. Diese Schrift wird im Dokumentinhalt verwendet und ist entweder im Dokument selbst eingebettet oder im Betriebssystem installiert, auf dem GroupDocs.Viewer läuft.

Unveränderliche Klasse. Ihre Instanzen werden von der öffentlichen API von GroupDocs.Viewer erzeugt und zurückgegeben und sollten normalerweise nicht vom Benutzer erstellt werden. Weitere Details finden Sie in der Dokumentation: https://docs.groupdocs.com/viewer/net/getting-used-fonts/
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Familienname der Schrift, ohne Stil, niemals null oder leer. |
| [getAltFamilyName()](#getAltFamilyName--) | Alternativer Familienname der Schriftart. |
| [getStyle()](#getStyle--) | Stil der Schriftart \u2014 kann Regular, Bold, Italic oder BoldItalic sein. |
| [isEmbedded()](#isEmbedded--) | Gibt an, ob diese Schriftart im Dokument eingebettet ist (true) oder eine Systemschriftart (false). |
| [getFormat()](#getFormat--) | Format dieser Schriftart. |
| [getContent()](#getContent--) | Inhalt dieser Schriftart als Byte-Array oder null, falls nicht verfügbar. |
| [getCharset()](#getCharset--) | Zeichensatz dieser Schriftart. |
| [toString()](#toString--) | Gibt Debug-Informationen zu dieser Schriftart im folgenden Template zurück: "name style, embedded/system, format" |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialisiert diese Schriftartinformationen als @font-face CSS-Regel und schreibt sie in den angegebenen Writer. |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Familienname der Schrift, ohne Stil, niemals null oder leer.

**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


Alternativer Familienname der Schriftart. Falls nicht vorhanden, wird ein leerer String zurückgegeben.

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Stil der Schriftart \u2014 kann Regular, Bold, Italic oder BoldItalic sein.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Gibt an, ob diese Schriftart im Dokument eingebettet ist (true) oder eine Systemschriftart (false).

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


Format dieser Schriftart. Wenn nur Metainformationen vorhanden sind und der Binärinhalt fehlt, kann FontFormat.UNKNOWN zurückgegeben werden.

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


Inhalt dieser Schriftart als Byte-Array oder null, falls nicht verfügbar.

**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


Zeichensatz dieser Schriftart.

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


Gibt Debug-Informationen zu dieser Schriftart im folgenden Template zurück: "name style, embedded/system, format"

**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialisiert diese Schriftartinformationen als @font-face CSS-Regel und schreibt sie in den angegebenen Writer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| output | java.io.Writer | Writer, der das serialisierte CSS empfängt. |

