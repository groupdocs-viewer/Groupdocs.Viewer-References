---
title: "EmailOptions"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Optionen zum Rendern von E‑Mail‑Nachrichten bereit."
type: docs
weight: 14
url: /de/java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

Stellt Optionen zum Rendern von E‑Mail‑Nachrichten bereit.


Die EmailOptions-Klasse kapselt verschiedene Einstellungen und Parameter, die verwendet werden können
um die Darstellung von E-Mail-Nachrichten in der GroupDocs.Viewer-Komponente zu steuern.


Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


Beispielverwendung:

````

 EmailOptions options = new EmailOptions();
 options.setDateTimeFormat("MM d yyyy HH:mm tt");
 options.setPageSize(PageSize.A4);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setEmailOptions(options);

 try (Viewer viewer = new Viewer("email.msg")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [EmailOptions()](#EmailOptions--) | Initialisiert eine neue Instanz von |
EmailOptions
Klasse.
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getDateTimeFormat()](#getDateTimeFormat--) | Liefert das Zeitformat für die Datums- und Zeitwerte. |
|
|  | [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | Liefert das Zeitformat für die Datums- und Zeitwerte. |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | Liefert die Zeitzonenverschiebung für die Nachricht. |
|
|  | [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | Liefert die Minutenverschiebung der Zeitzone für die Nachricht. |
|
|  | [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | Liefert die Zeitzonenverschiebung für die Nachricht. |
|
|  | [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | Liefert die Zeitzonenverschiebung in Minuten für die Nachricht. |
|
|  | [getPageSize()](#getPageSize--) | Liefert die Größe der Ausgabeseite. |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Liefert die Größe der Ausgabeseite. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | Ruft die Zuordnung zwischen E-Mail-Nachrichtenfeldern und deren Textdarstellungen ab. |
|
|  | [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | Setzt die Zuordnung zwischen E-Mail-Nachrichtenfeldern und deren Textdarstellungen. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Überschreibt die equals()-Methode der Object-Klasse. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | Überschreibt die toString()-Methode der Object-Klasse. |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


Initialisiert eine neue Instanz von
EmailOptions
Klasse.
Dieser Konstruktor wird verwendet, um eine neue Instanz von
EmailOptions
Klasse mit Standardeinstellungen.


### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


Liefert das Zeitformat für die Datums- und Zeitwerte.
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
Wenn das Zeitformat nicht festgelegt ist, wird das aktuelle Systemformat verwendet.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.lang.String - das Zeitformat für Datums- und Zeitwerte.

### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


Liefert das Zeitformat für die Datums- und Zeitwerte.
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
Wenn das Zeitformat nicht festgelegt ist, wird das aktuelle Systemformat verwendet.
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | dateTimeFormat | java.lang.String | Das Zeitformat für Datums- und Zeitwerte. |
|

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


Liefert die Zeitzonenverschiebung für die Nachricht.
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.util.TimeZone - der Zeitzonen-Offset.

### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


Liefert die Minutenverschiebung der Zeitzone für die Nachricht.
***Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC).
Weitere Details finden Sie in der [Dokumentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
int - der Zeitzonen-Offset.

### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


Liefert die Zeitzonenverschiebung für die Nachricht.
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | timeZoneOffset | java.util.TimeZone | Der Zeitzonen-Offset. |
|

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


Liefert die Zeitzonenverschiebung in Minuten für die Nachricht.
***Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | offsetMinutes | int | Der Zeitzonen-Offset. |
|

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Liefert die Größe der Ausgabeseite.


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Liefert die Größe der Ausgabeseite.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Die Seitengröße. |
|

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


Ruft die Zuordnung zwischen E-Mail-Nachrichtenfeldern und deren Textdarstellungen ab.


**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - die Zuordnung zwischen E-Mail-Nachrichtenfeldern und deren Textdarstellungen.

### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


Setzt die Zuordnung zwischen E-Mail-Nachrichtenfeldern und deren Textdarstellungen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | value | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | Die Zuordnung zwischen E-Mail-Nachrichtenfeldern und deren Textdarstellungen. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Überschreibt die equals()-Methode der Object-Klasse.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | o | java.lang.Object | Das Objekt zum Vergleichen mit. |
|

**Returns:**
boolean - true, wenn die Objekte gleich sind, sonst false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Berechnet den Hashcode-Wert für dieses Objekt. Der Hashcode basiert auf
dem internen Zustand des Objekts und wird in hashbasierten Datenstrukturen verwendet
wie z.B. Hash-Maps und Hash-Sets.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - der Hashcode-Wert für dieses Objekt.

### toString() {#toString--}
```
public String toString()
```


Überschreibt die toString()-Methode der Object-Klasse.


**Returns:**
java.lang.String - eine String-Darstellung des Objekts.

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Gibt eine String-Darstellung dieses Objekts zurück.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | Stil | org.apache.commons.lang3.builder.ToStringStyle | Der ToStringStyle, der zur Erzeugung der String-Darstellung verwendet wird. |
|

**Returns:**
java.lang.String - eine String-Darstellung dieses Objekts unter Verwendung des angegebenen ToStringStyle.

