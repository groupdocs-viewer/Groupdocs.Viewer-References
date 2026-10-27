---
title: "EmailOptions"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Biedt opties voor het renderen van e-mailberichten."
type: docs
weight: 14
url: /nl/nodejs-java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

Biedt opties voor het renderen van e-mailberichten.

De EmailOptions-klasse omvat verschillende instellingen en parameters die kunnen worden gebruikt om de weergave van e-mailberichten in de GroupDocs.Viewer-component te controleren.

Voor details, zie de [documentatie][].

Voorbeeldgebruik:

```

 EmailOptions options = new EmailOptions();
 options.setDateTimeFormat("MM d yyyy HH:mm tt");
 options.setPageSize(PageSize.A4);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setEmailOptions(options);

 try (Viewer viewer = new Viewer("email.msg")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [EmailOptions()](#EmailOptions--) | Initialiseert een nieuw exemplaar van de  EmailOptions  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDateTimeFormat()](#getDateTimeFormat--) | Haalt het tijdformaat op voor de datum- en tijdwaarden. |
| [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | Haalt het tijdformaat op voor de datum- en tijdwaarden. |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | Haalt de tijdzone-offset op voor het bericht. |
| [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | Haalt de minuten-offset van de tijdzone op voor het bericht. |
| [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | Haalt de tijdzone-offset op voor het bericht. |
| [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | Haalt de offset in minuten van de tijdzone op voor het bericht. |
| [getPageSize()](#getPageSize--) | Haalt de grootte van de uitvoerpagina op. |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Haalt de grootte van de uitvoerpagina op. |
| [getFieldTextMap()](#getFieldTextMap--) | Haalt de mapping op tussen e-mailberichtvelden en hun tekstuele weergaven. |
| [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | Stelt de mapping in tussen e-mailberichtvelden en hun tekstuele weergaven. |
| [equals(Object o)](#equals-java.lang.Object-) | Overschrijft de equals()-methode van de Object-klasse. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Overschrijft de toString()-methode van de Object-klasse. |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


Initialiseert een nieuw exemplaar van de  EmailOptions  klasse. Deze constructor wordt gebruikt om een nieuw exemplaar van de  EmailOptions  klasse te maken met standaardinstellingen.

### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


Haalt het tijdformaat op voor de datum- en tijdwaarden.

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.lang.String - het tijdformaat voor datum- en tijdwaarden.
### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


Haalt het tijdformaat op voor de datum- en tijdwaarden.

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| dateTimeFormat | java.lang.String | Het tijdformaat voor datum- en tijdwaarden. |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


Haalt de tijdzone-offset op voor het bericht.

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.util.TimeZone - de tijdzone-offset.
### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


Haalt de minuten-offset van de tijdzone op voor het bericht.

**Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
int - de tijdzone-offset.
### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


Haalt de tijdzone-offset op voor het bericht.

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| timeZoneOffset | java.util.TimeZone | De tijdzone-offset. |

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


Haalt de offset in minuten van de tijdzone op voor het bericht.

**Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| offsetMinutes | int | De tijdzone-offset. |

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Haalt de grootte van de uitvoerpagina op.

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Haalt de grootte van de uitvoerpagina op.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | De paginagrootte. |

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


Haalt de mapping op tussen e-mailberichtvelden en hun tekstuele weergaven.

**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - de mapping tussen e-mailberichtvelden en hun tekstuele weergaven.
### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


Stelt de mapping in tussen e-mailberichtvelden en hun tekstuele weergaven.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | De mapping tussen e-mailberichtvelden en hun tekstrepresentaties. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Overschrijft de equals()-methode van de Object-klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| o | java.lang.Object | Het object om mee te vergelijken. |

**Returns:**
boolean - true als de objecten gelijk zijn, false anders.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Berekent de hashcode-waarde voor dit object. De hashcode is gebaseerd op de interne staat van het object en wordt gebruikt in hash-gebaseerde datastructuren zoals hash‑maps en hash‑sets.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - de hashcode-waarde voor dit object.
### toString() {#toString--}
```
public String toString()
```


Overschrijft de toString()-methode van de Object-klasse.

**Returns:**
java.lang.String - een stringrepresentatie van het object.
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Retourneert een tekenreeksrepresentatie van dit object.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stijl | org.apache.commons.lang3.builder.ToStringStyle | De ToStringStyle die gebruikt moet worden voor het genereren van de tekenreeksrepresentatie. |

**Returns:**
java.lang.String - een tekenreeksrepresentatie van dit object met de opgegeven ToStringStyle.
