---
title: "Resource"
second_title: "Riferimento API di GroupDocs.Viewer per Java"
description: "Rappresenta una risorsa HTML come font, stile, immagine o grafica."
type: docs
weight: 10
url: /it/java/com.groupdocs.viewer.results/resource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Serializable
```
public class Resource implements Serializable
```

Rappresenta una risorsa HTML come font, stile, immagine o grafica.


La classe Resource rappresenta una risorsa utilizzata nel rendering HTML nel componente GroupDocs.Viewer.
Può rappresentare vari tipi di risorse, come font, stili, immagini o grafiche, che sono incluse
o referenziate nell'output HTML generato durante il processo di rendering.


Esempio di utilizzo:

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


## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [Resource(String fileName, boolean nested)](#Resource-java.lang.String-boolean-) | Crea una nuova istanza di |
Resource
classe.
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getFileName()](#getFileName--) | Restituisce il nome file della risorsa. |
|
|  | [setFileName(String fileName)](#setFileName-java.lang.String-) | Imposta il nome file della risorsa. |
|
|  | [isNested()](#isNested--) | Restituisce se la risorsa si trova all'interno di un'altra risorsa, ad esempio una risorsa font che risiede in una risorsa CSS o SVG. |
|
|  | [setNested(boolean nested)](#setNested-boolean-) | Imposta se la risorsa si trova all'interno di un'altra risorsa. |
|
|  | [toString()](#toString--) | Restituisce una stringa che rappresenta l'oggetto corrente. |
|
### Resource(String fileName, boolean nested) {#Resource-java.lang.String-boolean-}
```
public Resource(String fileName, boolean nested)
```


Crea una nuova istanza di
Resource
classe.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileName | java.lang.String | Il nome file della risorsa. |
|
|  | annidato | boolean | Indica se la risorsa si trova all'interno di un'altra risorsa, ad esempio una risorsa font che risiede in una risorsa CSS o SVG. |
|

### getFileName() {#getFileName--}
```
public final String getFileName()
```


Restituisce il nome file della risorsa.


**Returns:**
java.lang.String - il nome file della risorsa.

### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public void setFileName(String fileName)
```


Imposta il nome file della risorsa.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | fileName | java.lang.String | Il nuovo nome file per la risorsa. |
|

### isNested() {#isNested--}
```
public final boolean isNested()
```


Restituisce se la risorsa si trova all'interno di un'altra risorsa, ad esempio una risorsa font che risiede in una risorsa CSS o SVG.


**Returns:**
boolean - Se la risorsa risiede all'interno di un'altra risorsa.

### setNested(boolean nested) {#setNested-boolean-}
```
public void setNested(boolean nested)
```


Imposta se la risorsa si trova all'interno di un'altra risorsa.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | annidato | boolean | Se la risorsa deve essere impostata come nidificata. |
|

### toString() {#toString--}
```
public String toString()
```


Restituisce una stringa che rappresenta l'oggetto corrente.


**Returns:**
java.lang.String - la rappresentazione stringa dell'oggetto corrente.

