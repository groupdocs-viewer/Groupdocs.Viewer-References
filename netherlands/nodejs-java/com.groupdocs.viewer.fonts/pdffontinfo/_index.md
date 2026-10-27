---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Omsluit meta‑informatie en binaire gegevens van één lettertype uit een PDF‑document dat in de Viewer‑instantie is geladen."
type: docs
weight: 14
url: /nl/nodejs-java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

Omvat meta-informatie en binaire gegevens van één lettertype uit een PDF-document, geladen in de Viewer-instantie.

Dit lettertype wordt gebruikt in de documentinhoud en is ofwel:

 *  embedded inside the PDF document
 *  or installed in the operating system where GroupDocs.Viewer is running
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | Interne constructor gebruikt bij PDF‑lettertype‑extractie. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Haalt de lettertypefamilienaam op. |
| [getStyle()](#getStyle--) | Haalt de stijl van dit lettertype op. |
| [isEmbedded()](#isEmbedded--) | Geeft terug of het lettertype is ingebed in het PDF‑document. |
| [isInstalled()](#isInstalled--) | Geeft terug of het lettertype is geïnstalleerd in het besturingssysteem. |
| [getFormat()](#getFormat--) | Geeft het bestandsformaat van het lettertype terug. |
| [getContent()](#getContent--) | Geeft de binaire inhoud van het lettertype terug. |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | Serialiseert dit lettertype als een CSS @font-face‑regel. |
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


Interne constructor gebruikt bij PDF‑lettertype‑extractie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| familyName | java.lang.String | lettertypefamilienaam |
| stijl | com.groupdocs.viewer.fonts.FontStyles | stijl (Regular, Bold, Italic, BoldItalic) |
| isEmbedded | boolean | true als het lettertype is ingebed in de PDF |
| isInstalled | boolean | true als het lettertype is geïnstalleerd in het besturingssysteem |
| inhoud | byte[] | binaire lettertypegegevens (nullable) |
| formaat | int | lettertypebestandsformaat |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Haalt de lettertypefamilienaam op.

**Returns:**
java.lang.String - familienaam‑string (nooit null of leeg)
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


Haalt de stijl van dit lettertype op.

**Returns:**
com.groupdocs.viewer.fonts.FontStyles - de lettertype‑stijl
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


Geeft terug of het lettertype is ingebed in het PDF‑document.

**Returns:**
boolean - true als ingebed
### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


Geeft terug of het lettertype is geïnstalleerd in het besturingssysteem.

**Returns:**
boolean - true als geïnstalleerd
### getFormat() {#getFormat--}
```
public int getFormat()
```


Geeft het bestandsformaat van het lettertype terug.

**Returns:**
int - de lettertype‑formaat‑enum
### getContent() {#getContent--}
```
public byte[] getContent()
```


Geeft de binaire inhoud van het lettertype terug.

**Returns:**
byte[] - byte-array of null als niet beschikbaar
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


Serialiseert dit lettertype als een CSS @font-face‑regel.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uitvoer | java.io.Writer | writer waarin CSS zal worden geschreven |

