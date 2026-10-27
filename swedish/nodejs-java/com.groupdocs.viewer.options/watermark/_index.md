---
title: "Watermark"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Representerar en textvattenstämpel."
type: docs
weight: 37
url: /sv/nodejs-java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

Representerar ett textvattenmärke. För detaljer, se [documentation][].

Klassen Watermark representerar ett textvattenmärke i GroupDocs.Viewer-komponenten. Den används för att definiera och tillämpa ett vattenmärke på dokumentens renderade utdata.

Exempel på användning:

```

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/add-text-watermark/
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Watermark(String text)](#Watermark-java.lang.String-) | Initierar en ny instans av klassen Watermark. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getText()](#getText--) | Returnerar vattenstämpelns text. |
| [getColor()](#getColor--) | Returnerar vattenstämpelns färg. |
| [getColorAsHex()](#getColorAsHex--) | Returnerar vattenstämpelns färg i hexformat. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Ställer in vattenstämpelns färg. |
| [setColor(String colorName)](#setColor-java.lang.String-) | Ställer in vattenstämpelns färg. |
| [getPosition()](#getPosition--) | Returnerar vattenstämpelns position. |
| [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | Ställer in vattenstämpelns position. |
| [getSize()](#getSize--) | Returnerar vattenstämpelns storlek. |
| [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | Ställer in vattenstämpelns storlek. |
| [getFontName()](#getFontName--) | Returnerar teckensnittets namn som används för vattenstämpeln. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Ställer in teckensnittets namn som används för vattenstämpeln. |
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Initierar en ny instans av klassen Watermark.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Vattenstämpelns text. |

### getText() {#getText--}
```
public final String getText()
```


Returnerar vattenstämpelns text. Denna metod hämtar texten för vattenstämpeln som tillämpas på dokumentet.

**Returns:**
java.lang.String - vattenstämpelns text.
### getColor() {#getColor--}
```
public final Color getColor()
```


Returnerar vattenstämpelns färg. Denna metod hämtar färgen för vattenstämpeln som tillämpas på dokumentet.

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.awt.Color - vattenstämpelns färg.
### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


Returnerar vattenstämpelns färg i hexformat. Denna metod hämtar färgen för vattenstämpeln som tillämpas på dokumentet.

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.lang.String - vattenstämpelns färg i hexformat.
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Ställer in vattenstämpelns färg. Denna metod sätter färgen för vattenstämpeln som tillämpas på dokumentet.

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.awt.Color | Vattenstämpelns färg att sätta. |

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Ställer in vattenstämpelns färg. Denna metod sätter färgen för vattenstämpeln som tillämpas på dokumentet.

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorName | java.lang.String | Vattenstämpelns färg att sätta. |

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


Returnerar vattenstämpelns position. Denna metod returnerar positionen för vattenstämpeln som tillämpas på dokumentet.

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.
### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


Ställer in vattenstämpelns position. Denna metod sätter positionen för vattenstämpeln som tillämpas på dokumentet.

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Position](../../com.groupdocs.viewer.options/position) | Vattenstämpelns position. |

### getSize() {#getSize--}
```
public final Size getSize()
```


Returnerar vattenstämpelns storlek. Denna metod hämtar storleken för vattenstämpeln som tillämpas på dokumentet.

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.
### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


Ställer in vattenstämpelns storlek. Denna metod anger storleken på vattenstämpeln som ska tillämpas på dokumentet.

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Size](../../com.groupdocs.viewer.options/size) | Vattenstämpelns storlek. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Returnerar teckensnittets namn som används för vattenstämpeln.

**Returns:**
java.lang.String - teckensnittets namn som används för vattenstämpeln.
### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Ställer in teckensnittets namn som används för vattenstämpeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String | Teckensnittets namn som används för vattenstämpeln. |

