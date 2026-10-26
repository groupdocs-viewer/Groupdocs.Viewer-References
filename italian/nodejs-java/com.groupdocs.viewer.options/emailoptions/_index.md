---
title: "EmailOptions"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Fornisce opzioni per il rendering di messaggi email."
type: docs
weight: 14
url: /it/nodejs-java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

Fornisce opzioni per il rendering di messaggi email.

La classe EmailOptions incapsula varie impostazioni e parametri che possono essere usati per controllare il rendering dei messaggi email nel componente GroupDocs.Viewer.

Per i dettagli, vedere la [documentazione][].

Esempio di utilizzo:

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
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmailOptions()](#EmailOptions--) | Inizializza una nuova istanza della classe EmailOptions. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDateTimeFormat()](#getDateTimeFormat--) | Ottiene il formato dell'ora per i valori di data e ora. |
| [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | Ottiene il formato dell'ora per i valori di data e ora. |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | Ottiene l'offset del fuso orario per il messaggio. |
| [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | Ottiene i minuti di offset del fuso orario per il messaggio. |
| [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | Ottiene l'offset del fuso orario per il messaggio. |
| [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | Ottiene i minuti di offset del fuso orario per il messaggio. |
| [getPageSize()](#getPageSize--) | Ottiene la dimensione della pagina di output. |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Ottiene la dimensione della pagina di output. |
| [getFieldTextMap()](#getFieldTextMap--) | Recupera la mappatura tra i campi del messaggio email e le loro rappresentazioni testuali. |
| [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | Imposta la mappatura tra i campi del messaggio email e le loro rappresentazioni testuali. |
| [equals(Object o)](#equals-java.lang.Object-) | Sovrascrive il metodo equals() della classe Object. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Sovrascrive il metodo toString() della classe Object. |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


Inizializza una nuova istanza della classe EmailOptions. Questo costruttore è usato per creare una nuova istanza della classe EmailOptions con le impostazioni predefinite.

### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


Ottiene il formato dell'ora per i valori di data e ora.

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.lang.String - il formato dell'ora per i valori di data e ora.
### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


Ottiene il formato dell'ora per i valori di data e ora.

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dateTimeFormat | java.lang.String | Il formato dell'ora per i valori di data e ora. |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


Ottiene l'offset del fuso orario per il messaggio.

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.util.TimeZone - l'offset del fuso orario.
### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


Ottiene i minuti di offset del fuso orario per il messaggio.

**Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
int - l'offset del fuso orario.
### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


Ottiene l'offset del fuso orario per il messaggio.

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| timeZoneOffset | java.util.TimeZone | L'offset del fuso orario. |

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


Ottiene i minuti di offset del fuso orario per il messaggio.

**Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| offsetMinutes | int | L'offset del fuso orario. |

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Ottiene la dimensione della pagina di output.

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Ottiene la dimensione della pagina di output.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | La dimensione della pagina. |

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


Recupera la mappatura tra i campi del messaggio email e le loro rappresentazioni testuali.

**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - la mappatura tra i campi del messaggio email e le loro rappresentazioni testuali.
### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


Imposta la mappatura tra i campi del messaggio email e le loro rappresentazioni testuali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | La mappatura tra i campi dei messaggi email e le loro rappresentazioni testuali. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Sovrascrive il metodo equals() della classe Object.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| o | java.lang.Object | L'oggetto da confrontare. |

**Returns:**
boolean - true se gli oggetti sono uguali, false altrimenti.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Calcola il valore del codice hash per questo oggetto. Il codice hash si basa sullo stato interno dell'oggetto ed è usato nelle strutture dati basate su hash come hash map e hash set.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - il valore del codice hash per questo oggetto.
### toString() {#toString--}
```
public String toString()
```


Sovrascrive il metodo toString() della classe Object.

**Returns:**
java.lang.String - una rappresentazione stringa dell'oggetto.
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Restituisce una rappresentazione stringa di questo oggetto.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stile | org.apache.commons.lang3.builder.ToStringStyle | Il ToStringStyle da usare per generare la rappresentazione stringa. |

**Returns:**
java.lang.String - una rappresentazione stringa di questo oggetto usando il ToStringStyle specificato.
