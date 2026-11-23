---
title: "Feld"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt E‑Mail‑Nachrichtenfelder e46g46 From To Subject usw. dar."
type: docs
weight: 40
url: /de/nodejs-java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

Stellt E‑Mail‑Nachrichtenfelder dar, z. B. Von, An, Betreff usw.

Das Field-Enum repräsentiert gängige E‑Mail‑Nachrichtenfelder in der GroupDocs.Viewer‑Komponente. Es stellt eine Menge vordefinierter Felder bereit, die verwendet werden können, um bestimmte Informationen in E‑Mail‑Nachrichten zu identifizieren und darauf zuzugreifen, wie z. B. den Absender, Empfänger, Betreff und mehr.

Weitere Details finden Sie in der [Dokumentation][].

Beispielhafte Verwendung:

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
## Felder

| Feld | Beschreibung |
| --- | --- |
| [ANNIVERSARY](#ANNIVERSARY) | Stellt das Feld \"Anniversary\" dar. |
| [ATTACHMENTS](#ATTACHMENTS) | Stellt das Feld \"Attachments\" dar. |
| [BCC](#BCC) | Stellt das Feld \"Bcc\" dar. |
| [BIRTHDAY](#BIRTHDAY) | Stellt das Feld \"Birthday\" dar. |
| [BUSINESS](#BUSINESS) | Stellt das Feld \"Business\" dar. |
| [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | Stellt das Feld \"Business Address\" dar. |
| [BUSINESS_FAX](#BUSINESS-FAX) | Stellt das Feld \"Business Fax\" dar. |
| [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | Stellt das Feld \"BusinessHomepage\" dar. |
| [CC](#CC) | Stellt das Feld \"Cc\" dar. |
| [COMPANY](#COMPANY) | Stellt das Feld \"Company\" dar. |
| [DEPARTMENT](#DEPARTMENT) | Stellt das Feld \"Department\" dar. |
| [EMAIL](#EMAIL) | Stellt das Feld \"Email\" dar. |
| [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | Stellt das Feld \"Email Display As\" dar. |
| [EMAIL_2](#EMAIL-2) | Stellt das Feld \"Email2\" dar. |
| [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | Stellt das Feld \"Email2 Display As\" dar. |
| [EMAIL_3](#EMAIL-3) | Stellt das Feld \"Email3\" dar. |
| [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | Stellt das Feld \"Email3 Display As\" dar. |
| [END](#END) | Stellt das Feld \"End\" dar. |
| [FIRST_NAME](#FIRST-NAME) | Stellt das Feld \"First Name\" dar. |
| [FROM](#FROM) | Stellt das Feld \"From\" dar. |
| [FULL_NAME](#FULL-NAME) | Stellt das Feld \"Full Name\" dar. |
| [GENDER](#GENDER) | Stellt das Feld \"Gender\" dar. |
| [HOBBIES](#HOBBIES) | Stellt das Feld \"Hobbies\" dar. |
| [HOME](#HOME) | Stellt das Feld \"Home\" dar. |
| [HOME_ADDRESS](#HOME-ADDRESS) | Stellt das Feld "Home Address" dar. |
| [IMPORTANCE](#IMPORTANCE) | Stellt das Feld "Importance" dar. |
| [JOB_TITLE](#JOB-TITLE) | Stellt das Feld "Job Title" dar. |
| [LAST_NAME](#LAST-NAME) | Stellt das Feld "Last Name" dar. |
| [LOCATION](#LOCATION) | Stellt das Feld "Location" dar. |
| [MIDDLE_NAME](#MIDDLE-NAME) | Stellt das Feld "Middle Name" dar. |
| [MOBILE](#MOBILE) | Stellt das Feld "Mobile" dar. |
| [ORGANIZER](#ORGANIZER) | Stellt das Feld "Organizer" dar. |
| [OTHER_ADDRESS](#OTHER-ADDRESS) | Stellt das Feld "Other Address" dar. |
| [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | Stellt das Feld "Personal Homepage" dar. |
| [PROFESSION](#PROFESSION) | Stellt das Feld "Profession" dar. |
| [RECURRENCE](#RECURRENCE) | Stellt das Feld "Recurrence" dar. |
| [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | Stellt das Feld "Recurrence Pattern" dar. |
| [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | Stellt das Feld "Required Attendees" dar. |
| [SENT](#SENT) | Stellt das Feld "Sent" dar. |
| [SHOW_TIME_AS](#SHOW-TIME-AS) | Stellt das Feld "Show Time As" dar. |
| [SPOUSE_PARTNER](#SPOUSE-PARTNER) | Stellt das Feld "Spouse/Partner" dar. |
| [START](#START) | Stellt das Feld "Start" dar. |
| [SUBJECT](#SUBJECT) | Stellt das Feld "Subject" dar. |
| [TO](#TO) | Stellt das Feld "To" dar. |
| [USER_FIELD_1](#USER-FIELD-1) | Stellt das Feld "User Field 1" dar. |
| [USER_FIELD_2](#USER-FIELD-2) | Stellt das Feld "User Field 2" dar. |
| [USER_FIELD_3](#USER-FIELD-3) | Stellt das Feld "User Field 3" dar. |
| [USER_FIELD_4](#USER-FIELD-4) | Stellt das Feld "User Field 4" dar. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getName()](#getName--) | Feldname. |
| [toString()](#toString--) | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. |
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


Stellt das Feld \"Anniversary\" dar.

### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


Stellt das Feld \"Attachments\" dar.

### BCC {#BCC}
```
public static final Field BCC
```


Stellt das Feld \"Bcc\" dar.

### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


Stellt das Feld \"Birthday\" dar.

### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


Stellt das Feld \"Business\" dar.

### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


Stellt das Feld \"Business Address\" dar.

### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


Stellt das Feld \"Business Fax\" dar.

### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


Stellt das Feld \"BusinessHomepage\" dar.

### CC {#CC}
```
public static final Field CC
```


Stellt das Feld \"Cc\" dar.

### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


Stellt das Feld \"Company\" dar.

### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


Stellt das Feld \"Department\" dar.

### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


Stellt das Feld \"Email\" dar.

### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


Stellt das Feld \"Email Display As\" dar.

### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


Stellt das Feld \"Email2\" dar.

### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


Stellt das Feld \"Email2 Display As\" dar.

### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


Stellt das Feld \"Email3\" dar.

### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


Stellt das Feld \"Email3 Display As\" dar.

### END {#END}
```
public static final Field END
```


Stellt das Feld \"End\" dar.

### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


Stellt das Feld \"First Name\" dar.

### FROM {#FROM}
```
public static final Field FROM
```


Stellt das Feld \"From\" dar.

### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


Stellt das Feld \"Full Name\" dar.

### GENDER {#GENDER}
```
public static final Field GENDER
```


Stellt das Feld \"Gender\" dar.

### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


Stellt das Feld \"Hobbies\" dar.

### HOME {#HOME}
```
public static final Field HOME
```


Stellt das Feld \"Home\" dar.

### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


Stellt das Feld "Home Address" dar.

### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


Stellt das Feld "Importance" dar.

### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


Stellt das Feld "Job Title" dar.

### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


Stellt das Feld "Last Name" dar.

### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


Stellt das Feld "Location" dar.

### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


Stellt das Feld "Middle Name" dar.

### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


Stellt das Feld "Mobile" dar.

### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


Stellt das Feld "Organizer" dar.

### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


Stellt das Feld "Other Address" dar.

### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


Stellt das Feld "Personal Homepage" dar.

### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


Stellt das Feld "Profession" dar.

### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


Stellt das Feld "Recurrence" dar.

### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


Stellt das Feld "Recurrence Pattern" dar.

### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


Stellt das Feld "Required Attendees" dar.

### SENT {#SENT}
```
public static final Field SENT
```


Stellt das Feld "Sent" dar.

### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


Stellt das Feld "Show Time As" dar.

### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


Stellt das Feld "Spouse/Partner" dar.

### START {#START}
```
public static final Field START
```


Stellt das Feld "Start" dar.

### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


Stellt das Feld "Subject" dar.

### TO {#TO}
```
public static final Field TO
```


Stellt das Feld "To" dar.

### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


Stellt das Feld "User Field 1" dar.

### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


Stellt das Feld "User Field 2" dar.

### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


Stellt das Feld "User Field 3" dar.

### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


Stellt das Feld "User Field 4" dar.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


Feldname.

Diese Methode ruft den Namen des Feldes ab.

**Returns:**
java.lang.String - der Name des Feldes.
### toString() {#toString--}
```
public String toString()
```


Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt.

**Returns:**
java.lang.String - eine Zeichenkette, die das aktuelle Objekt darstellt.
