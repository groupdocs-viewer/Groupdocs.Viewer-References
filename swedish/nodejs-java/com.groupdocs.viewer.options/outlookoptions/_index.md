---
title: "OutlookOptions"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för rendering av Outlook-datafiler."
type: docs
weight: 20
url: /sv/nodejs-java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Tillhandahåller alternativ för rendering av Outlook-datafiler.

Klassen OutlookOptions kapslar in olika inställningar och parametrar som kan användas för att kontrollera rendering av Outlook-datafiler (såsom PST- eller OST-filer) i GroupDocs.Viewer-komponenten.

För mer information, se [documentation][].

Exempel på användning:

```

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFolder()](#getFolder--) | Hämtar namnet på mappen som ska renderas. |
| [setFolder(String value)](#setFolder-java.lang.String-) | Ställer in namnet på mappen som ska renderas. |
| [getTextFilter()](#getTextFilter--) | Hämtar nyckelorden som används för att filtrera meddelanden. |
| [setTextFilter(String value)](#setTextFilter-java.lang.String-) | Hämtar nyckelorden som används för att filtrera meddelanden. |
| [getAddressFilter()](#getAddressFilter--) | Hämtar e‑postadressen som används för att filtrera meddelanden efter avsändare eller mottagare. |
| [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | Ställer in e‑postadressen som används för att filtrera meddelanden efter avsändare eller mottagare. |
| [getMaxItemsInFolder()](#getMaxItemsInFolder--) | Hämtar det maximala antalet meddelanden eller objekt som kan renderas från en mapp. |
| [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | Ställer in det maximala antalet meddelanden eller objekt som kan renderas från en mapp. |
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Hämtar namnet på mappen som ska renderas. Namnet på mappen (t.ex. Inkorg, Skickade objekt eller Borttagna objekt) som ska renderas.

När du renderar en Outlook-datafil renderar GroupDocs.Viewer meddelanden från alla mappar som finns i filen (inklusive nästlade mappar). Använd den här egenskapen för att rendera objekt från en specifik mapp. För kodexempel, se denna [dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Returns:**
java.lang.String - namnet på mappen som ska renderas.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Ställer in namnet på mappen som ska renderas. Namnet på mappen (t.ex. Inbox, Sent Item eller Deleted Items) som ska renderas.

När du renderar en Outlook-datafil renderar GroupDocs.Viewer meddelanden från alla mappar som finns i filen (inklusive nästlade mappar). Använd den här egenskapen för att rendera objekt från en specifik mapp. För kodexempel, se denna [dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String | Namnet på mappen som ska renderas. |

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


Hämtar nyckelorden som används för att filtrera meddelanden.

Använd den här egenskapen för att rendera alla meddelanden som innehåller specifik text i ämnet eller i brödtexten. För kodexempel, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - nyckelorden.
### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


Hämtar nyckelorden som används för att filtrera meddelanden.

Använd den här egenskapen för att rendera alla meddelanden som innehåller specifik text i ämnet eller i brödtexten. För kodexempel, se [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String | Nyckelorden. |

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


Hämtar e‑postadressen som används för att filtrera meddelanden efter avsändare eller mottagare.

Använd den här egenskapen för att rendera alla meddelanden som innehåller specifik text i avsändar\ufffds eller mottagar\ufffds adressen. För kodexempel, se [dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - e-postadressen som används för att filtrera meddelanden.
### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


Ställer in e‑postadressen som används för att filtrera meddelanden efter avsändare eller mottagare.

Använd den här egenskapen för att rendera alla meddelanden som innehåller specifik text i avsändar\ufffds eller mottagar\ufffds adressen. För kodexempel, se [dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String | E-postadressen som används för att filtrera meddelanden. |

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


Hämtar det maximala antalet meddelanden eller objekt som kan renderas från en mapp.

Outlook-datafiler kan vara stora och att hämta alla meddelanden kan ta betydande tid. Den här inställningen begränsar det maximala antalet meddelanden eller objekt (såsom kontakter och uppgifter) som renderas. Standardvärdet är 50. Sätt värdet till 0 för att rendera alla meddelanden. För kodexempel, se [dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Returns:**
int - det maximala antalet meddelanden eller objekt som kan renderas från en mapp.
### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


Ställer in det maximala antalet meddelanden eller objekt som kan renderas från en mapp.

Outlook-datafiler kan vara stora och att hämta alla meddelanden kan ta betydande tid. Den här inställningen begränsar det maximala antalet meddelanden eller objekt (såsom kontakter och uppgifter) som renderas. Standardvärdet är 50. Sätt värdet till 0 för att rendera alla meddelanden. För kodexempel, se [dokumentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | Det maximala antalet meddelanden eller objekt som kan renderas från en mapp. |

