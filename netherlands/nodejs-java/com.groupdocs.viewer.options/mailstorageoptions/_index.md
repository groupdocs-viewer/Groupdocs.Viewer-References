---
title: "MailStorageOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Biedt opties voor het renderen van Mail-opslag Lotus Notes MBox-gegevensbestanden."
type: docs
weight: 19
url: /nl/nodejs-java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

Biedt opties voor het renderen van Mail-opslag (Lotus Notes, MBox) gegevensbestanden.

De MailStorageOptions klasse omvat verschillende instellingen en parameters die kunnen worden gebruikt om het renderen van Mail-opslaggegevensbestanden (zoals Lotus Notes of MBox) in de GroupDocs.Viewer component te beheersen.

Voor details, zie de [documentatie][].

Voorbeeldgebruik:

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
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTextFilter()](#getTextFilter--) | Haalt de trefwoorden op die worden gebruikt om berichten te filteren. |
| [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | Stelt de trefwoorden in die worden gebruikt om berichten te filteren. |
| [getAddressFilter()](#getAddressFilter--) | Haalt het e-mailadres op dat wordt gebruikt om berichten te filteren op afzender of ontvanger. |
| [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | Stelt het e-mailadres in dat wordt gebruikt om berichten te filteren op afzender of ontvanger. |
| [getMaxItems()](#getMaxItems--) | Haalt het maximale aantal berichten of items op dat moet worden gerenderd. |
| [setMaxItems(int maxItems)](#setMaxItems-int-) | Stelt het maximale aantal berichten of items in dat moet worden gerenderd. |
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


Haalt de trefwoorden op die worden gebruikt om berichten te filteren.

Gebruik deze eigenschap om alle berichten te renderen die specifieke tekst in het onderwerp of de inhoud bevatten. Zie voor een codevoorbeeld de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - de trefwoorden die worden gebruikt voor het filteren van berichten.
### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


Stelt de trefwoorden in die worden gebruikt om berichten te filteren.

Gebruik deze eigenschap om alle berichten te renderen die specifieke tekst in het onderwerp of de inhoud bevatten. Zie voor een codevoorbeeld de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| textFilter | java.lang.String | De trefwoorden die worden gebruikt voor het filteren van berichten. |

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


Haalt het e-mailadres op dat wordt gebruikt om berichten te filteren op afzender of ontvanger.

Gebruik deze eigenschap om alle berichten te renderen die specifieke tekst in het adres van de afzender of ontvanger bevatten. Zie voor een codevoorbeeld de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - het e-mailadres dat wordt gebruikt voor het filteren van berichten.
### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


Stelt het e-mailadres in dat wordt gebruikt om berichten te filteren op afzender of ontvanger.

Gebruik deze eigenschap om alle berichten te renderen die specifieke tekst in het adres van de afzender of ontvanger bevatten. Zie voor een codevoorbeeld de [documentatie][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| addressFilter | java.lang.String | Het e-mailadres dat wordt gebruikt voor het filteren van berichten. |

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


Haalt het maximale aantal berichten of items op dat moet worden gerenderd.

Lotus Notes-gegevensbestanden kunnen groot zijn, en het ophalen van alle berichten kan veel tijd kosten. Deze instelling beperkt het maximale aantal berichten of items dat wordt gerenderd.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Returns:**
int - het maximale aantal berichten of items om te renderen.
### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


Stelt het maximale aantal berichten of items in dat moet worden gerenderd.

Lotus Notes-gegevensbestanden kunnen groot zijn, en het ophalen van alle berichten kan veel tijd kosten. Deze instelling beperkt het maximale aantal berichten of items dat wordt gerenderd.

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| maxItems | int | Het maximale aantal berichten of items om te renderen. |

