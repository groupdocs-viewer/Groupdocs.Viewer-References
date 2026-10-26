---
title: "MailStorageOptions"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Fornisce opzioni per il rendering di file di dati Mail storage Lotus Notes MBox."
type: docs
weight: 19
url: /it/nodejs-java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

Fornisce opzioni per il rendering di file di dati di archivi di posta (Lotus Notes, MBox).

La classe MailStorageOptions incapsula varie impostazioni e parametri che possono essere utilizzati per controllare il rendering dei file di dati Mail storage (come Lotus Notes o MBox) nel componente GroupDocs.Viewer.

Per i dettagli, vedere la [documentazione][].

Esempio di utilizzo:

```

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTextFilter()](#getTextFilter--) | Ottiene le parole chiave utilizzate per filtrare i messaggi. |
| [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | Imposta le parole chiave utilizzate per filtrare i messaggi. |
| [getAddressFilter()](#getAddressFilter--) | Ottiene l'indirizzo email utilizzato per filtrare i messaggi per mittente o destinatario. |
| [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | Imposta l'indirizzo email utilizzato per filtrare i messaggi per mittente o destinatario. |
| [getMaxItems()](#getMaxItems--) | Ottiene il numero massimo di messaggi o elementi da renderizzare. |
| [setMaxItems(int maxItems)](#setMaxItems-int-) | Imposta il numero massimo di messaggi o elementi da renderizzare. |
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


Ottiene le parole chiave utilizzate per filtrare i messaggi.

Utilizza questa proprietà per renderizzare tutti i messaggi che contengono testo specifico nell'oggetto o nel corpo. Per un esempio di codice, vedi la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - le parole chiave utilizzate per filtrare i messaggi.
### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


Imposta le parole chiave utilizzate per filtrare i messaggi.

Utilizza questa proprietà per renderizzare tutti i messaggi che contengono testo specifico nell'oggetto o nel corpo. Per un esempio di codice, vedi la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textFilter | java.lang.String | Le parole chiave utilizzate per filtrare i messaggi. |

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


Ottiene l'indirizzo email utilizzato per filtrare i messaggi per mittente o destinatario.

Utilizza questa proprietà per renderizzare tutti i messaggi che contengono testo specifico nell'indirizzo del mittente\u2019s o del destinatario\u2019s. Per un esempio di codice, vedi la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - l'indirizzo email utilizzato per filtrare i messaggi.
### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


Imposta l'indirizzo email utilizzato per filtrare i messaggi per mittente o destinatario.

Utilizza questa proprietà per renderizzare tutti i messaggi che contengono testo specifico nell'indirizzo del mittente\u2019s o del destinatario\u2019s. Per un esempio di codice, vedi la [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| addressFilter | java.lang.String | L'indirizzo email utilizzato per filtrare i messaggi. |

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


Ottiene il numero massimo di messaggi o elementi da renderizzare.

I file di dati di Lotus Notes possono essere grandi e il recupero di tutti i messaggi può richiedere molto tempo. Questa impostazione limita il numero massimo di messaggi o elementi che vengono renderizzati.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Returns:**
int - il numero massimo di messaggi o elementi da renderizzare.
### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


Imposta il numero massimo di messaggi o elementi da renderizzare.

I file di dati di Lotus Notes possono essere grandi e il recupero di tutti i messaggi può richiedere molto tempo. Questa impostazione limita il numero massimo di messaggi o elementi che vengono renderizzati.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| maxItems | int | Il numero massimo di messaggi o elementi da renderizzare. |

