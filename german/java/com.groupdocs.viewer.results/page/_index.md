---
title: "Seite"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt eine einzelne Seite dar, die angezeigt werden kann."
type: docs
weight: 23
url: /de/java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

Stellt eine einzelne Seite dar, die angezeigt werden kann.


Das Seiten-Interface definiert den Vertrag für den Zugriff auf und die Manipulation einer einzelnen Seite
die in der GroupDocs.Viewer‑Komponente angezeigt werden kann. Es bietet Methoden zum Abrufen
von Informationen wie Seitenzahl, Größe und anderen Eigenschaften.


Beispielverwendung:

````

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
````


***Note:** The default implementation of this interface is PageImpl.*

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getName()](#getName--) | Ruft den Namen des Arbeitsblatts oder der Seite ab. |
|
|  | [setName(String name)](#setName-java.lang.String-) | Setzt den Namen des Arbeitsblatts oder der Seite. |
|
|  | [getNumber()](#getNumber--) | Ruft die Seitenzahl ab. |
|
|  | [setNumber(int number)](#setNumber-int-) | Setzt die Seitenzahl. |
|
|  | [isVisible()](#isVisible--) | Ruft den Sichtbarkeitsindikator der Seite ab. |
|
|  | [setVisible(boolean visible)](#setVisible-boolean-) | Setzt den Sichtbarkeitsindikator der Seite. |
|
|  | [getWidth()](#getWidth--) | Ruft die Breite der Seite in Pixeln ab, wenn sie als JPG oder PNG angezeigt wird. |
|
|  | [setWidth(int width)](#setWidth-int-) | Legt die Breite der Seite in Pixeln fest, wenn sie als JPG oder PNG angezeigt wird. |
|
|  | [getHeight()](#getHeight--) | Ruft die Höhe der Seite in Pixeln ab, wenn sie als JPG oder PNG angezeigt wird. |
|
|  | [setHeight(int height)](#setHeight-int-) | Legt die Höhe der Seite in Pixeln fest, wenn sie als JPG oder PNG angezeigt wird. |
|
|  | [getLines()](#getLines--) | Ruft die Zeilen ab, die in der Seite enthalten sind, wenn sie als JPG oder PNG mit aktivierter Textextraktion angezeigt wird. |
|
|  | [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | Legt die Zeilen fest, die in der Seite enthalten sind, wenn sie als JPG oder PNG mit aktivierter Textextraktion angezeigt wird. |
|
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
|  | Name | java.lang.String | Der Name, der für das Arbeitsblatt oder die Seite festgelegt werden soll. |
|

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


Ruft die Seitenzahl ab.


**Returns:**
int - die Seitennummer.

### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


Setzt die Seitenzahl.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | number | int | Die zu setzende Seitennummer. |
|

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
|  | sichtbar | boolesch | true, wenn die Seite sichtbar ist, sonst false. |
|

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


Legt die Breite der Seite in Pixeln fest, wenn sie als JPG oder PNG angezeigt wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | width | int | Die für die Seite festzulegende Breite. |
|

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


Legt die Höhe der Seite in Pixeln fest, wenn sie als JPG oder PNG angezeigt wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | height | int | Die für die Seite festzulegende Höhe. |
|

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


Ruft die Zeilen ab, die in der Seite enthalten sind, wenn sie als JPG oder PNG mit aktivierter Textextraktion angezeigt wird.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - die in der Seite enthaltenen Zeilen.

### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


Legt die Zeilen fest, die in der Seite enthalten sind, wenn sie als JPG oder PNG mit aktivierter Textextraktion angezeigt wird.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | lines | java.util.List<com.groupdocs.viewer.results.Line> | Die Liste der Zeilen, die für die Seite festgelegt werden soll. |
|

