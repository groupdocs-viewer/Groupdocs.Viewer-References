---
title: "Watermark"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Représente un filigrane texte."
type: docs
weight: 37
url: /fr/java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

Représente un filigrane texte. Pour plus de détails, voir la [documentation](../https://docs.groupdocs.com/viewer/net/add-text-watermark/).


La classe Watermark représente un filigrane texte dans le composant GroupDocs.Viewer.
Elle est utilisée pour définir et appliquer un filigrane au rendu des documents.


Exemple d'utilisation :

````

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
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Watermark(String text)](#Watermark-java.lang.String-) | Initialise une nouvelle instance de |
Watermark
classe.
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getText()](#getText--) | Renvoie le texte du filigrane. |
|
|  | [getColor()](#getColor--) | Renvoie la couleur du filigrane. |
|
|  | [getColorAsHex()](#getColorAsHex--) | Renvoie la couleur du filigrane au format hexadécimal. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | Définit la couleur du filigrane. |
|
|  | [setColor(String colorName)](#setColor-java.lang.String-) | Définit la couleur du filigrane. |
|
|  | [getPosition()](#getPosition--) | Renvoie la position du filigrane. |
|
|  | [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | Définit la position du filigrane. |
|
|  | [getSize()](#getSize--) | Renvoie la taille du filigrane. |
|
|  | [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | Définit la taille du filigrane. |
|
|  | [getFontName()](#getFontName--) | Renvoie le nom de police utilisé pour le filigrane. |
|
|  | [setFontName(String value)](#setFontName-java.lang.String-) | Définit le nom de police utilisé pour le filigrane. |
|
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Initialise une nouvelle instance de
Watermark
classe.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | texte | java.lang.String | Le texte du filigrane. |
|

### getText() {#getText--}
```
public final String getText()
```


Renvoie le texte du filigrane.
Cette méthode récupère le texte du filigrane appliqué au document.


**Returns:**
java.lang.String - le texte du filigrane.

### getColor() {#getColor--}
```
public final Color getColor()
```


Renvoie la couleur du filigrane.
Cette méthode récupère la couleur du filigrane appliqué au document.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.awt.Color - la couleur du filigrane.

### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


Renvoie la couleur du filigrane au format hexadécimal.
Cette méthode récupère la couleur du filigrane appliqué au document.


***Note:** The default value is the red color obtained from Color#getRed().getRed().*


**Returns:**
java.lang.String - la couleur du filigrane au format hexadécimal.

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Définit la couleur du filigrane.
Cette méthode définit la couleur du filigrane appliqué au document.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.awt.Color | La couleur du filigrane à définir. |
|

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


Définit la couleur du filigrane.
Cette méthode définit la couleur du filigrane appliqué au document.


***Note:** The default value is obtained from Color#getRed().getRed().*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | colorName | java.lang.String | La couleur du filigrane à définir. |
|

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


Renvoie la position du filigrane.
Cette méthode renvoie la position du filigrane appliqué au document.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.

### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


Définit la position du filigrane.
Cette méthode définit la position du filigrane appliqué au document.


***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position#DIAGONAL).*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Position](../../com.groupdocs.viewer.options/position) | La position du filigrane. |
|

### getSize() {#getSize--}
```
public final Size getSize()
```


Renvoie la taille du filigrane.
Cette méthode récupère la taille du filigrane appliqué au document.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.

### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


Définit la taille du filigrane.
Cette méthode définit la taille du filigrane à appliquer au document.


***Note:** The default value is [Size.FULL_SIZE](../../com.groupdocs.viewer.options/size#FULL-SIZE).*


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [Size](../../com.groupdocs.viewer.options/size) | La taille du filigrane. |
|

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Renvoie le nom de police utilisé pour le filigrane.


**Returns:**
java.lang.String - le nom de police utilisé pour le filigrane.

### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


Définit le nom de police utilisé pour le filigrane.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.lang.String | Le nom de police utilisé pour le filigrane. |
|

