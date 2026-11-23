---
title: "EmailOptions"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Tillhandahåller alternativ för rendering av e-postmeddelanden."
type: docs
weight: 14
url: /sv/nodejs-java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

Tillhandahåller alternativ för rendering av e-postmeddelanden.

EmailOptions-klassen kapslar in olika inställningar och parametrar som kan användas för att kontrollera rendering av e‑postmeddelanden i GroupDocs.Viewer-komponenten.

För mer information, se [documentation][].

Exempel på användning:

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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmailOptions()](#EmailOptions--) | Initierar en ny instans av EmailOptions‑klassen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDateTimeFormat()](#getDateTimeFormat--) | Hämtar tidsformatet för datum‑ och tidsvärden. |
| [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | Hämtar tidsformatet för datum‑ och tidsvärden. |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | Hämtar tidszonsförskjutningen för meddelandet. |
| [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | Hämtar tidszonsminutförskjutningen för meddelandet. |
| [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | Hämtar tidszonsförskjutningen för meddelandet. |
| [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | Hämtar tidszonsförskjutningsminuterna för meddelandet. |
| [getPageSize()](#getPageSize--) | Hämtar storleken på utskriftsidan. |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Hämtar storleken på utskriftsidan. |
| [getFieldTextMap()](#getFieldTextMap--) | Hämtar mappningen mellan e‑postmeddelandefält och deras textrepresentationer. |
| [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | Ställer in mappningen mellan e‑postmeddelandefält och deras textrepresentationer. |
| [equals(Object o)](#equals-java.lang.Object-) | Åsidosätter equals()-metoden i Object‑klassen. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Åsidosätter toString()-metoden i Object‑klassen. |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


Initierar en ny instans av EmailOptions‑klassen. Denna konstruktor används för att skapa en ny instans av EmailOptions‑klassen med standardinställningar.

### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


Hämtar tidsformatet för datum‑ och tidsvärden.

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.lang.String - tidsformatet för datum‑ och tidsvärden.
### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


Hämtar tidsformatet för datum‑ och tidsvärden.

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dateTimeFormat | java.lang.String | Tidsformatet för datum‑ och tidsvärden. |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


Hämtar tidszonsförskjutningen för meddelandet.

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.util.TimeZone - tidszonsförskjutningen.
### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


Hämtar tidszonsminutförskjutningen för meddelandet.

**Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
int - tidszonsförskjutningen.
### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


Hämtar tidszonsförskjutningen för meddelandet.

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| timeZoneOffset | java.util.TimeZone | Tidszonsförskjutningen. |

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


Hämtar tidszonsförskjutningsminuterna för meddelandet.

**Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| offsetMinutes | int | Tidszonsförskjutningen. |

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Hämtar storleken på utskriftsidan.

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Hämtar storleken på utskriftsidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Sidstorleken. |

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


Hämtar mappningen mellan e‑postmeddelandefält och deras textrepresentationer.

**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - mappningen mellan e‑postmeddelandefält och deras textrepresentationer.
### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


Ställer in mappningen mellan e‑postmeddelandefält och deras textrepresentationer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | Mappningen mellan e-postmeddelandefält och deras textrepresentationer. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Åsidosätter equals()-metoden i Object‑klassen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | java.lang.Object | Objektet att jämföra med. |

**Returns:**
boolean - true om objekten är lika, false annars.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Beräknar hashkodsvärdet för detta objekt. Hashkoden baseras på objektets interna tillstånd och används i hashbaserade datastrukturer såsom hash‑mappar och hash‑set.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - hashkodsvärdet för detta objekt.
### toString() {#toString--}
```
public String toString()
```


Åsidosätter toString()-metoden i Object‑klassen.

**Returns:**
java.lang.String - en strängrepresentation av objektet.
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Returnerar en strängrepresentation av detta objekt.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stil | org.apache.commons.lang3.builder.ToStringStyle | Den ToStringStyle som ska användas för att generera strängrepresentationen. |

**Returns:**
java.lang.String - en strängrepresentation av detta objekt med den angivna ToStringStyle.
