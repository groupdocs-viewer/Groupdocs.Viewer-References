---
title: "Page"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt eine einzelne Seite dar, die angezeigt werden kann."
type: docs
weight: 21
url: /de/nodejs-java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

Stellt eine einzelne Seite dar, die angezeigt werden kann.

Das Page-Interface definiert den Vertrag zum Zugreifen und Manipulieren einer einzelnen Seite, die in der GroupDocs.Viewer-Komponente angezeigt werden kann. Es stellt Methoden bereit, um Informationen wie die Seitennummer, die Größe und weitere Eigenschaften abzurufen.

Beispielhafte Verwendung:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is PageImpl.*
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getName()](#getName--) | Ruft den Namen des Arbeitsblatts oder der Seite ab. |
| [setName(String name)](#setName-java.lang.String-) | Setzt den Namen des Arbeitsblatts oder der Seite. |
| [getNumber()](#getNumber--) | Ruft die Seitennummer ab. |
| [setNumber(int number)](#setNumber-int-) | Setzt die Seitennummer. |
| [isVisible()](#isVisible--) | Ruft den Sichtbarkeitsindikator der Seite ab. |
| [setVisible(boolean visible)](#setVisible-boolean-) | Setzt den Sichtbarkeitsindikator der Seite. |
| [getWidth()](#getWidth--) | Ruft die Breite der Seite in Pixeln ab, wenn sie als JPG oder PNG angezeigt wird. |
| [setWidth(int width)](#setWidth-int-) | Setzt die Breite der Seite in Pixeln, wenn sie als JPG oder PNG angezeigt wird. |
| [getHeight()](#getHeight--) | Ruft die Höhe der Seite in Pixeln ab, wenn sie als JPG oder PNG angezeigt wird. |
| [setHeight(int height)](#setHeight-int-) | Setzt die Höhe der Seite in Pixeln, wenn sie als JPG oder PNG angezeigt wird. |
| [getLines()](#getLines--) | Ruft die Zeilen ab, die in der Seite enthalten sind, wenn sie als JPG oder PNG mit aktivierter Textextraktion angezeigt wird. |
| [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | Setzt die Zeilen, die in der Seite enthalten sind, wenn sie als JPG oder PNG mit aktivierter Textextraktion angezeigt wird. |
### getName() {#getName--}
```
public abstract String getName()
```


Ruft den Namen des Arbeitsblatts oder der Seite ab.

**Returns:**
java.lang.String - der Name des Arbeitsblatts oder der Seite.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Setzt den Namen des Arbeitsblatts oder der Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String | der zu setzende Name für das Arbeitsblatt oder die Seite. |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


Ruft die Seitennummer ab.

**Returns:**
int - die Seitennummer.
### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


Setzt die Seitennummer.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Nummer | int | die zu setzende Seitennummer. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Ruft den Sichtbarkeitsindikator der Seite ab.

**Returns:**
boolean - der Sichtbarkeitsindikator der Seite.
### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


Setzt den Sichtbarkeitsindikator der Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sichtbar | boolean | true, wenn die Seite sichtbar ist, sonst false. |

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Ruft die Breite der Seite in Pixeln ab, wenn sie als JPG oder PNG angezeigt wird.

**Returns:**
int - die Breite der Seite.
### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


Setzt die Breite der Seite in Pixeln, wenn sie als JPG oder PNG angezeigt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | int | die für die Seite festzulegende Breite. |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Ruft die Höhe der Seite in Pixeln ab, wenn sie als JPG oder PNG angezeigt wird.

**Returns:**
int - die Höhe der Seite.
### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


Setzt die Höhe der Seite in Pixeln, wenn sie als JPG oder PNG angezeigt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| height | int | die für die Seite festzulegende Höhe. |

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


Ruft die Zeilen ab, die in der Seite enthalten sind, wenn sie als JPG oder PNG mit aktivierter Textextraktion angezeigt wird.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - die Zeilen, die in der Seite enthalten sind.
### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


Setzt die Zeilen, die in der Seite enthalten sind, wenn sie als JPG oder PNG mit aktivierter Textextraktion angezeigt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zeilen | java.util.List<com.groupdocs.viewer.results.Line> | die Liste der Zeilen, die für die Seite festzulegen ist. |

