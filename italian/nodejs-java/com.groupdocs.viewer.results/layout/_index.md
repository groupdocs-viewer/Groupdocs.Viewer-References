---
title: "Layout"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Rappresenta un layout contenuto in un disegno CAD."
type: docs
weight: 17
url: /it/nodejs-java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

Rappresenta un layout contenuto in un disegno CAD.

L'interfaccia Layout definisce il contratto per accedere e manipolare un layout all'interno di un disegno CAD nel componente GroupDocs.Viewer. Fornisce metodi per recuperare informazioni come il nome del layout, le dimensioni e altre proprietà.

Esempio di utilizzo:

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layouts = viewInfo.getLayouts();
     for (Layout layout : layouts) {
         // Use the layout object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LayoutImpl.*
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getName()](#getName--) | Recupera il nome del layout. |
| [setName(String name)](#setName-java.lang.String-) | Imposta il nome del layout. |
| [getWidth()](#getWidth--) | Recupera la larghezza del layout. |
| [setWidth(double width)](#setWidth-double-) | Imposta la larghezza del layout. |
| [getHeight()](#getHeight--) | Recupera l'altezza del layout. |
| [setHeight(double height)](#setHeight-double-) | Imposta l'altezza del layout. |
| [equals(Object other)](#equals-java.lang.Object-) | Verifica se questo oggetto è uguale all'oggetto fornito. |
### getName() {#getName--}
```
public abstract String getName()
```


Recupera il nome del layout.

**Returns:**
java.lang.String - il nome del layout.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Imposta il nome del layout.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Il nome da impostare per il layout. |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Recupera la larghezza del layout.

**Returns:**
double - la larghezza del layout.
### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


Imposta la larghezza del layout.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| width | double | La larghezza da impostare per il layout. |

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Recupera l'altezza del layout.

**Returns:**
double - l'altezza del layout.
### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


Imposta l'altezza del layout.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| height | double | L'altezza da impostare per il layout. |

### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Verifica se questo oggetto è uguale all'oggetto fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| altro | java.lang.Object | L'oggetto da confrontare. |

**Returns:**
boolean -  true  se gli oggetti sono uguali,  false  altrimenti.
