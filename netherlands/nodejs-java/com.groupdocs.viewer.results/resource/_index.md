---
title: "Resource"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt een HTML-resource voor, zoals een lettertype, stijl, afbeelding of grafisch element."
type: docs
weight: 10
url: /nl/nodejs-java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

Stelt een HTML-bron voor, zoals lettertype, stijl, afbeelding of grafische elementen.

De Resource-klasse stelt een resource voor die wordt gebruikt bij HTML-rendering in de GroupDocs.Viewer-component. Het kan verschillende soorten resources vertegenwoordigen, zoals lettertypen, stijlen, afbeeldingen of grafische elementen, die zijn opgenomen of gerefereerd in de gegenereerde HTML-uitvoer tijdens het renderproces.

Voorbeeldgebruik:

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
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | Maakt een nieuw exemplaar van de  Resource  klasse aan. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFileName()](#getFileName--) | Retourneert de bestandsnaam van de resource. |
| [setFileName(String fileName)](#setFileName-java.lang.String-) | Stelt de bestandsnaam van de resource in. |
| [isNested()](#isNested--) | Retourneert of de resource zich binnen een andere resource bevindt, bijv. een lettertype‑resource die zich in een CSS‑ of SVG‑resource bevindt. |
| [setNested(boolean nested)](#setNested-boolean-) | Stelt in of de resource zich binnen een andere resource bevindt. |
| [toString()](#toString--) | Retourneert een string die het huidige object vertegenwoordigt. |
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


Maakt een nieuw exemplaar van de  Resource  klasse aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | De bestandsnaam van de resource. |
| genest | boolean | Geeft aan of de resource zich binnen een andere resource bevindt, bijv., een lettertype‑resource die zich in een CSS‑ of SVG‑resource bevindt. |

### getFileName() {#getFileName--}
```
public final String getFileName()
```


Retourneert de bestandsnaam van de resource.

**Returns:**
java.lang.String - de bestandsnaam van de resource.
### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


Stelt de bestandsnaam van de resource in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | De nieuwe bestandsnaam voor de resource. |

### isNested() {#isNested--}
```
public final boolean isNested()
```


Retourneert of de resource zich binnen een andere resource bevindt, bijv. een lettertype‑resource die zich in een CSS‑ of SVG‑resource bevindt.

**Returns:**
boolean - Of de resource zich binnen een andere resource bevindt.
### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


Stelt in of de resource zich binnen een andere resource bevindt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| genest | boolean | Of de resource als genest moet worden ingesteld. |

### toString() {#toString--}
```
public String toString()
```


Retourneert een string die het huidige object vertegenwoordigt.

**Returns:**
java.lang.String - de tekenreeksrepresentatie van het huidige object.
