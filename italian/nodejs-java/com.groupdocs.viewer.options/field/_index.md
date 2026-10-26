---
title: "Campo"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Rappresenta i campi del messaggio email e46g46 From To Subject ecc."
type: docs
weight: 40
url: /it/nodejs-java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

Rappresenta i campi del messaggio email, ad es. Da, A, Oggetto, ecc.

L'enumerazione Field rappresenta i campi comuni dei messaggi email nel componente GroupDocs.Viewer. Fornisce un insieme di campi predefiniti che possono essere utilizzati per identificare e accedere a informazioni specifiche nei messaggi email, come il mittente, il destinatario, l'oggetto e altro.

Per i dettagli, vedere la [documentazione][].

Esempio di utilizzo:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 EmailOptions emailOptions = htmlViewOptions.getEmailOptions();
 emailOptions.getFieldTextMap().put(Field.FROM, "Sender");

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#rename-fields-in-the-message-header
## Campi

| Campo | Descrizione |
| --- | --- |
| [ANNIVERSARY](#ANNIVERSARY) | Rappresenta il campo "Anniversary". |
| [ATTACHMENTS](#ATTACHMENTS) | Rappresenta il campo "Attachments". |
| [BCC](#BCC) | Rappresenta il campo "Bcc". |
| [BIRTHDAY](#BIRTHDAY) | Rappresenta il campo "Birthday". |
| [BUSINESS](#BUSINESS) | Rappresenta il campo "Business". |
| [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | Rappresenta il campo "Business Address". |
| [BUSINESS_FAX](#BUSINESS-FAX) | Rappresenta il campo "Business Fax". |
| [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | Rappresenta il campo "BusinessHomepage". |
| [CC](#CC) | Rappresenta il campo "Cc". |
| [COMPANY](#COMPANY) | Rappresenta il campo "Company". |
| [DEPARTMENT](#DEPARTMENT) | Rappresenta il campo "Department". |
| [EMAIL](#EMAIL) | Rappresenta il campo "Email". |
| [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | Rappresenta il campo "Email Display As". |
| [EMAIL_2](#EMAIL-2) | Rappresenta il campo "Email2". |
| [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | Rappresenta il campo "Email2 Display As". |
| [EMAIL_3](#EMAIL-3) | Rappresenta il campo "Email3". |
| [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | Rappresenta il campo "Email3 Display As". |
| [END](#END) | Rappresenta il campo "End". |
| [FIRST_NAME](#FIRST-NAME) | Rappresenta il campo "First Name". |
| [FROM](#FROM) | Rappresenta il campo "From". |
| [FULL_NAME](#FULL-NAME) | Rappresenta il campo "Full Name". |
| [GENDER](#GENDER) | Rappresenta il campo "Gender". |
| [HOBBIES](#HOBBIES) | Rappresenta il campo "Hobbies". |
| [HOME](#HOME) | Rappresenta il campo "Home". |
| [HOME_ADDRESS](#HOME-ADDRESS) | Rappresenta il campo "Home Address". |
| [IMPORTANCE](#IMPORTANCE) | Rappresenta il campo "Importance". |
| [JOB_TITLE](#JOB-TITLE) | Rappresenta il campo "Job Title". |
| [LAST_NAME](#LAST-NAME) | Rappresenta il campo "Last Name". |
| [LOCATION](#LOCATION) | Rappresenta il campo "Location". |
| [MIDDLE_NAME](#MIDDLE-NAME) | Rappresenta il campo "Middle Name". |
| [MOBILE](#MOBILE) | Rappresenta il campo "Mobile". |
| [ORGANIZER](#ORGANIZER) | Rappresenta il campo "Organizer". |
| [OTHER_ADDRESS](#OTHER-ADDRESS) | Rappresenta il campo "Other Address". |
| [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | Rappresenta il campo "Personal Homepage". |
| [PROFESSION](#PROFESSION) | Rappresenta il campo "Profession". |
| [RECURRENCE](#RECURRENCE) | Rappresenta il campo "Recurrence". |
| [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | Rappresenta il campo "Recurrence Pattern". |
| [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | Rappresenta il campo "Required Attendees". |
| [SENT](#SENT) | Rappresenta il campo "Sent". |
| [SHOW_TIME_AS](#SHOW-TIME-AS) | Rappresenta il campo "Show Time As". |
| [SPOUSE_PARTNER](#SPOUSE-PARTNER) | Rappresenta il campo "Spouse/Partner". |
| [START](#START) | Rappresenta il campo "Start". |
| [SUBJECT](#SUBJECT) | Rappresenta il campo "Subject". |
| [TO](#TO) | Rappresenta il campo "To". |
| [USER_FIELD_1](#USER-FIELD-1) | Rappresenta il campo "User Field 1". |
| [USER_FIELD_2](#USER-FIELD-2) | Rappresenta il campo "User Field 2". |
| [USER_FIELD_3](#USER-FIELD-3) | Rappresenta il campo "User Field 3". |
| [USER_FIELD_4](#USER-FIELD-4) | Rappresenta il campo "User Field 4". |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getName()](#getName--) | Nome campo. |
| [toString()](#toString--) | Restituisce una stringa che rappresenta l'oggetto corrente. |
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


Rappresenta il campo "Anniversary".

### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


Rappresenta il campo "Attachments".

### BCC {#BCC}
```
public static final Field BCC
```


Rappresenta il campo "Bcc".

### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


Rappresenta il campo "Birthday".

### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


Rappresenta il campo "Business".

### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


Rappresenta il campo "Business Address".

### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


Rappresenta il campo "Business Fax".

### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


Rappresenta il campo "BusinessHomepage".

### CC {#CC}
```
public static final Field CC
```


Rappresenta il campo "Cc".

### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


Rappresenta il campo "Company".

### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


Rappresenta il campo "Department".

### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


Rappresenta il campo "Email".

### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


Rappresenta il campo "Email Display As".

### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


Rappresenta il campo "Email2".

### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


Rappresenta il campo "Email2 Display As".

### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


Rappresenta il campo "Email3".

### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


Rappresenta il campo "Email3 Display As".

### END {#END}
```
public static final Field END
```


Rappresenta il campo "End".

### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


Rappresenta il campo "First Name".

### FROM {#FROM}
```
public static final Field FROM
```


Rappresenta il campo "From".

### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


Rappresenta il campo "Full Name".

### GENDER {#GENDER}
```
public static final Field GENDER
```


Rappresenta il campo "Gender".

### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


Rappresenta il campo "Hobbies".

### HOME {#HOME}
```
public static final Field HOME
```


Rappresenta il campo "Home".

### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


Rappresenta il campo "Home Address".

### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


Rappresenta il campo "Importance".

### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


Rappresenta il campo "Job Title".

### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


Rappresenta il campo "Last Name".

### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


Rappresenta il campo "Location".

### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


Rappresenta il campo "Middle Name".

### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


Rappresenta il campo "Mobile".

### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


Rappresenta il campo "Organizer".

### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


Rappresenta il campo "Other Address".

### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


Rappresenta il campo "Personal Homepage".

### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


Rappresenta il campo "Profession".

### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


Rappresenta il campo "Recurrence".

### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


Rappresenta il campo "Recurrence Pattern".

### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


Rappresenta il campo "Required Attendees".

### SENT {#SENT}
```
public static final Field SENT
```


Rappresenta il campo "Sent".

### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


Rappresenta il campo "Show Time As".

### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


Rappresenta il campo "Spouse/Partner".

### START {#START}
```
public static final Field START
```


Rappresenta il campo "Start".

### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


Rappresenta il campo "Subject".

### TO {#TO}
```
public static final Field TO
```


Rappresenta il campo "To".

### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


Rappresenta il campo "User Field 1".

### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


Rappresenta il campo "User Field 2".

### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


Rappresenta il campo "User Field 3".

### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


Rappresenta il campo "User Field 4".

### values() {#values--}
```
public static Field[] values()
```




**Returns:**
com.groupdocs.viewer.options.Field[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Field valueOf(String name)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


Nome campo.

Questo metodo recupera il nome del campo.

**Returns:**
java.lang.String - il nome del campo.
### toString() {#toString--}
```
public String toString()
```


Restituisce una stringa che rappresenta l'oggetto corrente.

**Returns:**
java.lang.String - una stringa che rappresenta l'oggetto corrente.
