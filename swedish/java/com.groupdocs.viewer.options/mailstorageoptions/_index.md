---
title: "MailStorageOptions"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tillhandahåller alternativ för att rendera Mail‑lagring Lotus Notes MBox‑datafiler."
type: docs
weight: 19
url: /sv/java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

Tillhandahåller alternativ för rendering av e-postlagring (Lotus Notes, MBox) datafiler.


MailStorageOptions‑klassen kapslar in olika inställningar och parametrar som kan användas
för att kontrollera rendering av e-postlagringsdatafiler (såsom Lotus Notes eller MBox) i GroupDocs.Viewer-komponenten.


För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options).


Exempel på användning:

````

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getTextFilter()](#getTextFilter--) | Hämtar nyckelorden som används för att filtrera meddelanden. |
|
|  | [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | Ställer in nyckelorden som används för att filtrera meddelanden. |
|
|  | [getAddressFilter()](#getAddressFilter--) | Hämtar e-postadressen som används för att filtrera meddelanden efter avsändare eller mottagare. |
|
|  | [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | Ställer in e-postadressen som används för att filtrera meddelanden efter avsändare eller mottagare. |
|
|  | [getMaxItems()](#getMaxItems--) | Hämtar det maximala antalet meddelanden eller objekt som ska renderas. |
|
|  | [setMaxItems(int maxItems)](#setMaxItems-int-) | Ställer in det maximala antalet meddelanden eller objekt som ska renderas. |
|
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


Hämtar nyckelorden som används för att filtrera meddelanden.


Använd den här egenskapen för att rendera alla meddelanden som innehåller specifik text i ämnet eller kroppen. För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Returns:**
java.lang.String - nyckelorden som används för att filtrera meddelanden.

### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


Ställer in nyckelorden som används för att filtrera meddelanden.


Använd den här egenskapen för att rendera alla meddelanden som innehåller specifik text i ämnet eller kroppen. För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | textFilter | java.lang.String | Nyckelorden som används för att filtrera meddelanden. |
|

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


Hämtar e-postadressen som används för att filtrera meddelanden efter avsändare eller mottagare.


Använd den här egenskapen för att rendera alla meddelanden som innehåller specifik text i avsändarens eller mottagarens adress. För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Returns:**
java.lang.String - e-postadressen som används för att filtrera meddelanden.

### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


Ställer in e-postadressen som används för att filtrera meddelanden efter avsändare eller mottagare.


Använd den här egenskapen för att rendera alla meddelanden som innehåller specifik text i avsändarens eller mottagarens adress. För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | addressFilter | java.lang.String | E-postadressen som används för att filtrera meddelanden. |
|

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


Hämtar det maximala antalet meddelanden eller objekt som ska renderas.


Lotus Notes-datafiler kan vara stora, och att hämta alla meddelanden kan ta avsevärt mycket tid.
Denna inställning begränsar det maximala antalet meddelanden eller objekt som renderas.


***Note:** The default value is 0, which means all messages will be rendered.*
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render).


**Returns:**
int - det maximala antalet meddelanden eller objekt att rendera.

### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


Ställer in det maximala antalet meddelanden eller objekt som ska renderas.


Lotus Notes-datafiler kan vara stora, och att hämta alla meddelanden kan ta avsevärt mycket tid.
Denna inställning begränsar det maximala antalet meddelanden eller objekt som renderas.


***Note:** The default value is 0, which means all messages will be rendered.*
För kodexempel, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | maxItems | int | Det maximala antalet meddelanden eller objekt att rendera. |
|

