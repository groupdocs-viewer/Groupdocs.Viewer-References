---
title: "Resource"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Representerar HTML-resurs såsom teckensnitt, stil, bild eller grafik."
type: docs
weight: 10
url: /sv/java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

Representerar HTML-resurs såsom teckensnitt, stil, bild eller grafik.


Klassen Resource representerar en resurs som används i HTML-rendering i GroupDocs.Viewer‑komponenten.
Den kan representera olika typer av resurser, såsom teckensnitt, stilar, bilder eller grafik, som är inkluderade
eller refererade i den genererade HTML-utdata under renderingsprocessen.


Exempel på användning:

````

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forExternalResources(pageNumber -> , new ReleaseResourceStream() {
     @Override
     public void invoke(int pageNumber, Resource resource, OutputStream resourceStream) {
         // Handle resource
     }
 });
 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | Skapar en ny instans av |
Resource
klassen.
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFileName()](#getFileName--) | Returnerar filnamnet för resursen. |
|
|  | [setFileName(String fileName)](#setFileName-java.lang.String-) | Ställer in filnamnet för resursen. |
|
|  | [isNested()](#isNested--) | Returnerar om resursen finns inuti en annan resurs, t.ex. en teckensnittresurs som finns i en CSS‑ eller SVG‑resurs. |
|
|  | [setNested(boolean nested)](#setNested-boolean-) | Ställer in om resursen finns inuti en annan resurs. |
|
|  | [toString()](#toString--) | Returnerar en sträng som representerar det aktuella objektet. |
|
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


Skapar en ny instans av
Resource
klassen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileName | java.lang.String | Resursens filnamn. |
|
|  | nästlad | boolean | Indikerar om resursen finns inuti en annan resurs, t.ex. en teckensnittresurs som finns i en CSS‑ eller SVG‑resurs. |
|

### getFileName() {#getFileName--}
```
public final String getFileName()
```


Returnerar filnamnet för resursen.


**Returns:**
java.lang.String - filnamnet för resursen.

### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


Ställer in filnamnet för resursen.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fileName | java.lang.String | Det nya filnamnet för resursen. |
|

### isNested() {#isNested--}
```
public final boolean isNested()
```


Returnerar om resursen finns inuti en annan resurs, t.ex. en teckensnittresurs som finns i en CSS‑ eller SVG‑resurs.


**Returns:**
boolean - Om resursen finns inuti en annan resurs.

### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


Ställer in om resursen finns inuti en annan resurs.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | nästlad | boolean | Om resursen ska sättas som nästlad. |
|

### toString() {#toString--}
```
public String toString()
```


Returnerar en sträng som representerar det aktuella objektet.


**Returns:**
java.lang.String - strängrepresentationen av det aktuella objektet.

