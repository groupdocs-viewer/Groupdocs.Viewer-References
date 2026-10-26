---
title: "Ressource"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt eine HTML‑Ressource wie Schriftart‑Stil‑Bild oder Grafiken dar."
type: docs
weight: 10
url: /de/nodejs-java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

Stellt eine HTML-Ressource wie Schriftart, Stil, Bild oder Grafik dar.

Die Resource-Klasse repräsentiert eine Ressource, die bei der HTML‑Renderung in der GroupDocs.Viewer‑Komponente verwendet wird. Sie kann verschiedene Arten von Ressourcen darstellen, wie Schriftarten, Stile, Bilder oder Grafiken, die im erzeugten HTML‑Ausgabe während des Render‑Vorgangs eingebunden oder referenziert werden.

Beispielhafte Verwendung:

```

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
 
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | Erstellt eine neue Instanz der  Resource  Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFileName()](#getFileName--) | Gibt den Dateinamen der Ressource zurück. |
| [setFileName(String fileName)](#setFileName-java.lang.String-) | Setzt den Dateinamen der Ressource. |
| [isNested()](#isNested--) | Gibt zurück, ob die Ressource in einer anderen Ressource enthalten ist, z. B. eine Schriftart‑Ressource, die in einer CSS‑ oder SVG‑Ressource enthalten ist. |
| [setNested(boolean nested)](#setNested-boolean-) | Setzt, ob die Ressource in einer anderen Ressource enthalten ist. |
| [toString()](#toString--) | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. |
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


Erstellt eine neue Instanz der  Resource  Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | java.lang.String | Der Ressourcen‑Dateiname. |
| verschachtelt | boolean | Gibt an, ob die Ressource in einer anderen Ressource enthalten ist, z. B. eine Schriftart‑Ressource, die in einer CSS‑ oder SVG‑Ressource enthalten ist. |

### getFileName() {#getFileName--}
```
public final String getFileName()
```


Gibt den Dateinamen der Ressource zurück.

**Returns:**
java.lang.String - der Dateiname der Ressource.
### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


Setzt den Dateinamen der Ressource.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | java.lang.String | Der neue Dateiname für die Ressource. |

### isNested() {#isNested--}
```
public final boolean isNested()
```


Gibt zurück, ob die Ressource in einer anderen Ressource enthalten ist, z. B. eine Schriftart‑Ressource, die in einer CSS‑ oder SVG‑Ressource enthalten ist.

**Returns:**
boolean - Ob die Ressource in einer anderen Ressource enthalten ist.
### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


Setzt, ob die Ressource in einer anderen Ressource enthalten ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| verschachtelt | boolean | Ob die Ressource als verschachtelt festgelegt werden soll. |

### toString() {#toString--}
```
public String toString()
```


Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt.

**Returns:**
java.lang.String - die Zeichenketten‑Darstellung des aktuellen Objekts.
