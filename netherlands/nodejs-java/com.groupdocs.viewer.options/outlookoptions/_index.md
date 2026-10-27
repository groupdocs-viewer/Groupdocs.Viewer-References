---
title: "OutlookOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Biedt opties voor het renderen van Outlook-gegevensbestanden."
type: docs
weight: 20
url: /nl/nodejs-java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Biedt opties voor het renderen van Outlook-gegevensbestanden.

De OutlookOptions-klasse omvat verschillende instellingen en parameters die kunnen worden gebruikt om de weergave van Outlook-gegevensbestanden (zoals PST- of OST-bestanden) in de GroupDocs.Viewer-component te regelen.

Voor details, zie de [documentatie][].

Voorbeeldgebruik:

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
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFolder()](#getFolder--) | Haalt de naam van de map op die moet worden weergegeven. |
| [setFolder(String value)](#setFolder-java.lang.String-) | Stelt de naam van de map in die moet worden weergegeven. |
| [getTextFilter()](#getTextFilter--) | Haalt de trefwoorden op die worden gebruikt om berichten te filteren. |
| [setTextFilter(String value)](#setTextFilter-java.lang.String-) | Haalt de trefwoorden op die worden gebruikt om berichten te filteren. |
| [getAddressFilter()](#getAddressFilter--) | Haalt het e-mailadres op dat wordt gebruikt om berichten te filteren op afzender of ontvanger. |
| [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | Stelt het e-mailadres in dat wordt gebruikt om berichten te filteren op afzender of ontvanger. |
| [getMaxItemsInFolder()](#getMaxItemsInFolder--) | Haalt het maximale aantal berichten of items op dat uit één map kan worden weergegeven. |
| [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | Stelt het maximale aantal berichten of items in dat uit één map kan worden weergegeven. |
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


Haalt de naam van de map op die moet worden weergegeven. De naam van de map (bijv. Postvak IN, Verzonden items of Verwijderde items) die moet worden weergegeven.

Bij het renderen van een Outlook-gegevensbestand rendert GroupDocs.Viewer berichten uit alle mappen die in het bestand staan (inclusief geneste mappen). Gebruik deze eigenschap om items uit een specifieke map te renderen. Zie voor een codevoorbeeld deze [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Returns:**
java.lang.String - de naam van de map die moet worden gerenderd.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Stelt de naam van de map in die moet worden gerenderd. De naam van de map (bijv. Inbox, Verzonden items of Verwijderde items) die moet worden gerenderd.

Bij het renderen van een Outlook-gegevensbestand rendert GroupDocs.Viewer berichten uit alle mappen die in het bestand staan (inclusief geneste mappen). Gebruik deze eigenschap om items uit een specifieke map te renderen. Zie voor een codevoorbeeld deze [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String | De naam van de map die moet worden gerenderd. |

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


Haalt de trefwoorden op die worden gebruikt om berichten te filteren.

Gebruik deze eigenschap om alle berichten te renderen die specifieke tekst in het onderwerp of de inhoud bevatten. Zie voor een codevoorbeeld de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - de trefwoorden.
### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


Haalt de trefwoorden op die worden gebruikt om berichten te filteren.

Gebruik deze eigenschap om alle berichten te renderen die specifieke tekst in het onderwerp of de inhoud bevatten. Zie voor een codevoorbeeld de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String | De trefwoorden. |

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


Haalt het e-mailadres op dat wordt gebruikt om berichten te filteren op afzender of ontvanger.

Gebruik deze eigenschap om alle berichten te renderen die specifieke tekst bevatten in het adres van de afzender\ufffds of ontvanger\ufffds. Zie voor een codevoorbeeld de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - het e-mailadres dat wordt gebruikt om berichten te filteren.
### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


Stelt het e-mailadres in dat wordt gebruikt om berichten te filteren op afzender of ontvanger.

Gebruik deze eigenschap om alle berichten te renderen die specifieke tekst bevatten in het adres van de afzender\ufffds of ontvanger\ufffds. Zie voor een codevoorbeeld de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String | Het e-mailadres dat wordt gebruikt om berichten te filteren. |

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


Haalt het maximale aantal berichten of items op dat uit één map kan worden weergegeven.

Outlook-gegevensbestanden kunnen groot zijn en het ophalen van alle berichten kan veel tijd kosten. Deze instelling beperkt het maximale aantal berichten of items (zoals contactpersonen en taken) dat wordt gerenderd. De standaardwaarde is 50. Stel de waarde in op 0 om alle berichten te renderen. Zie voor een codevoorbeeld de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Returns:**
int - het maximale aantal berichten of items dat uit één map kan worden gerenderd.
### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


Stelt het maximale aantal berichten of items in dat uit één map kan worden weergegeven.

Outlook-gegevensbestanden kunnen groot zijn en het ophalen van alle berichten kan veel tijd kosten. Deze instelling beperkt het maximale aantal berichten of items (zoals contactpersonen en taken) dat wordt gerenderd. De standaardwaarde is 50. Stel de waarde in op 0 om alle berichten te renderen. Zie voor een codevoorbeeld de [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | Het maximale aantal berichten of items dat uit één map kan worden gerenderd. |

