---
title: "Fält"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Representerar e-postmeddelandefält e46g46 From To Subject etc."
type: docs
weight: 40
url: /sv/nodejs-java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

Representerar e-postmeddelandefält, t.ex. Från, Till, Ämne osv.

Field‑enumet representerar vanliga e‑postmeddelandefält i GroupDocs.Viewer‑komponenten. Det tillhandahåller en uppsättning fördefinierade fält som kan användas för att identifiera och komma åt specifik information i e‑postmeddelanden, såsom avsändare, mottagare, ämne och mer.

För mer information, se [documentation][].

Exempel på användning:

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
## Fält

| Fält | Beskrivning |
| --- | --- |
| [ANNIVERSARY](#ANNIVERSARY) | Representerar fältet "Anniversary". |
| [ATTACHMENTS](#ATTACHMENTS) | Representerar fältet "Attachments". |
| [BCC](#BCC) | Representerar fältet "Bcc". |
| [BIRTHDAY](#BIRTHDAY) | Representerar fältet "Birthday". |
| [BUSINESS](#BUSINESS) | Representerar fältet "Business". |
| [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | Representerar fältet "Business Address". |
| [BUSINESS_FAX](#BUSINESS-FAX) | Representerar fältet "Business Fax". |
| [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | Representerar fältet "BusinessHomepage". |
| [CC](#CC) | Representerar fältet "Cc". |
| [COMPANY](#COMPANY) | Representerar fältet "Company". |
| [DEPARTMENT](#DEPARTMENT) | Representerar fältet "Department". |
| [EMAIL](#EMAIL) | Representerar fältet "Email". |
| [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | Representerar fältet "Email Display As". |
| [EMAIL_2](#EMAIL-2) | Representerar fältet "Email2". |
| [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | Representerar fältet "Email2 Display As". |
| [EMAIL_3](#EMAIL-3) | Representerar fältet "Email3". |
| [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | Representerar fältet "Email3 Display As". |
| [END](#END) | Representerar fältet "End". |
| [FIRST_NAME](#FIRST-NAME) | Representerar fältet "First Name". |
| [FROM](#FROM) | Representerar fältet "From". |
| [FULL_NAME](#FULL-NAME) | Representerar fältet "Full Name". |
| [GENDER](#GENDER) | Representerar fältet "Gender". |
| [HOBBIES](#HOBBIES) | Representerar fältet "Hobbies". |
| [HOME](#HOME) | Representerar fältet "Home". |
| [HOME_ADDRESS](#HOME-ADDRESS) | Representerar "Home Address"-fältet. |
| [IMPORTANCE](#IMPORTANCE) | Representerar "Importance"-fältet. |
| [JOB_TITLE](#JOB-TITLE) | Representerar "Job Title"-fältet. |
| [LAST_NAME](#LAST-NAME) | Representerar "Last Name"-fältet. |
| [LOCATION](#LOCATION) | Representerar "Location"-fältet. |
| [MIDDLE_NAME](#MIDDLE-NAME) | Representerar "Middle Name"-fältet. |
| [MOBILE](#MOBILE) | Representerar "Mobile"-fältet. |
| [ORGANIZER](#ORGANIZER) | Representerar "Organizer"-fältet. |
| [OTHER_ADDRESS](#OTHER-ADDRESS) | Representerar "Other Address"-fältet. |
| [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | Representerar "Personal Homepage"-fältet. |
| [PROFESSION](#PROFESSION) | Representerar "Profession"-fältet. |
| [RECURRENCE](#RECURRENCE) | Representerar "Recurrence"-fältet. |
| [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | Representerar "Recurrence Pattern"-fältet. |
| [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | Representerar "Required Attendees"-fältet. |
| [SENT](#SENT) | Representerar "Sent"-fältet. |
| [SHOW_TIME_AS](#SHOW-TIME-AS) | Representerar "Show Time As"-fältet. |
| [SPOUSE_PARTNER](#SPOUSE-PARTNER) | Representerar "Spouse/Partner"-fältet. |
| [START](#START) | Representerar "Start"-fältet. |
| [SUBJECT](#SUBJECT) | Representerar "Subject"-fältet. |
| [TO](#TO) | Representerar "To"-fältet. |
| [USER_FIELD_1](#USER-FIELD-1) | Representerar "User Field 1"-fältet. |
| [USER_FIELD_2](#USER-FIELD-2) | Representerar "User Field 2"-fältet. |
| [USER_FIELD_3](#USER-FIELD-3) | Representerar "User Field 3"-fältet. |
| [USER_FIELD_4](#USER-FIELD-4) | Representerar "User Field 4"-fältet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getName()](#getName--) | Fältnamn. |
| [toString()](#toString--) | Returnerar en sträng som representerar det aktuella objektet. |
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


Representerar fältet "Anniversary".

### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


Representerar fältet "Attachments".

### BCC {#BCC}
```
public static final Field BCC
```


Representerar fältet "Bcc".

### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


Representerar fältet "Birthday".

### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


Representerar fältet "Business".

### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


Representerar fältet "Business Address".

### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


Representerar fältet "Business Fax".

### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


Representerar fältet "BusinessHomepage".

### CC {#CC}
```
public static final Field CC
```


Representerar fältet "Cc".

### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


Representerar fältet "Company".

### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


Representerar fältet "Department".

### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


Representerar fältet "Email".

### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


Representerar fältet "Email Display As".

### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


Representerar fältet "Email2".

### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


Representerar fältet "Email2 Display As".

### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


Representerar fältet "Email3".

### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


Representerar fältet "Email3 Display As".

### END {#END}
```
public static final Field END
```


Representerar fältet "End".

### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


Representerar fältet "First Name".

### FROM {#FROM}
```
public static final Field FROM
```


Representerar fältet "From".

### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


Representerar fältet "Full Name".

### GENDER {#GENDER}
```
public static final Field GENDER
```


Representerar fältet "Gender".

### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


Representerar fältet "Hobbies".

### HOME {#HOME}
```
public static final Field HOME
```


Representerar fältet "Home".

### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


Representerar "Home Address"-fältet.

### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


Representerar "Importance"-fältet.

### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


Representerar "Job Title"-fältet.

### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


Representerar "Last Name"-fältet.

### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


Representerar "Location"-fältet.

### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


Representerar "Middle Name"-fältet.

### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


Representerar "Mobile"-fältet.

### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


Representerar "Organizer"-fältet.

### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


Representerar "Other Address"-fältet.

### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


Representerar "Personal Homepage"-fältet.

### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


Representerar "Profession"-fältet.

### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


Representerar "Recurrence"-fältet.

### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


Representerar "Recurrence Pattern"-fältet.

### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


Representerar "Required Attendees"-fältet.

### SENT {#SENT}
```
public static final Field SENT
```


Representerar "Sent"-fältet.

### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


Representerar "Show Time As"-fältet.

### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


Representerar "Spouse/Partner"-fältet.

### START {#START}
```
public static final Field START
```


Representerar "Start"-fältet.

### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


Representerar "Subject"-fältet.

### TO {#TO}
```
public static final Field TO
```


Representerar "To"-fältet.

### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


Representerar "User Field 1"-fältet.

### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


Representerar "User Field 2"-fältet.

### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


Representerar "User Field 3"-fältet.

### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


Representerar "User Field 4"-fältet.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


Fältnamn.

Denna metod hämtar fältets namn.

**Returns:**
java.lang.String - fältets namn.
### toString() {#toString--}
```
public String toString()
```


Returnerar en sträng som representerar det aktuella objektet.

**Returns:**
java.lang.String - en sträng som representerar det aktuella objektet.
