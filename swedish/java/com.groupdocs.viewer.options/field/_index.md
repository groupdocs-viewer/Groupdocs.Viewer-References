---
title: "Fält"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Representerar e‑postmeddelandefält e46g46 From To Subject etc."
type: docs
weight: 40
url: /sv/java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

Representerar e-postmeddelandefält, t.ex. Från, Till, Ämne osv.


Enum‑typen Field representerar vanliga e‑postmeddelandefält i GroupDocs.Viewer‑komponenten.
Den tillhandahåller en uppsättning fördefinierade fält som kan användas för att identifiera och komma åt specifika
information i e‑postmeddelanden, såsom avsändare, mottagare, ämne och mer.


För detaljer, se [dokumentationen](../https://docs.groupdocs.com/viewer/java/render-email-messages/#rename-fields-in-the-message-header).


Exempel på användning:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 EmailOptions emailOptions = htmlViewOptions.getEmailOptions();
 emailOptions.getFieldTextMap().put(Field.FROM, "Sender");

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [ANNIVERSARY](#ANNIVERSARY) | Representerar fältet "Anniversary". |
|
|  | [ATTACHMENTS](#ATTACHMENTS) | Representerar fältet "Attachments". |
|
|  | [BCC](#BCC) | Representerar fältet "Bcc". |
|
|  | [BIRTHDAY](#BIRTHDAY) | Representerar fältet "Birthday". |
|
|  | [BUSINESS](#BUSINESS) | Representerar fältet "Business". |
|
|  | [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | Representerar fältet "Business Address". |
|
|  | [BUSINESS_FAX](#BUSINESS-FAX) | Representerar fältet "Business Fax". |
|
|  | [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | Representerar fältet "BusinessHomepage". |
|
|  | [CC](#CC) | Representerar fältet "Cc". |
|
|  | [COMPANY](#COMPANY) | Representerar fältet "Company". |
|
|  | [DEPARTMENT](#DEPARTMENT) | Representerar fältet "Department". |
|
|  | [EMAIL](#EMAIL) | Representerar fältet "Email". |
|
|  | [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | Representerar fältet "Email Display As". |
|
|  | [EMAIL_2](#EMAIL-2) | Representerar fältet "Email2". |
|
|  | [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | Representerar fältet "Email2 Display As". |
|
|  | [EMAIL_3](#EMAIL-3) | Representerar fältet "Email3". |
|
|  | [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | Representerar fältet "Email3 Display As". |
|
|  | [END](#END) | Representerar fältet "End". |
|
|  | [FIRST_NAME](#FIRST-NAME) | Representerar fältet "First Name". |
|
|  | [FROM](#FROM) | Representerar fältet "From". |
|
|  | [FULL_NAME](#FULL-NAME) | Representerar fältet "Full Name". |
|
|  | [GENDER](#GENDER) | Representerar fältet "Gender". |
|
|  | [HOBBIES](#HOBBIES) | Representerar fältet "Hobbies". |
|
|  | [HOME](#HOME) | Representerar fältet "Home". |
|
|  | [HOME_ADDRESS](#HOME-ADDRESS) | Representerar fältet "Home Address". |
|
|  | [IMPORTANCE](#IMPORTANCE) | Representerar fältet "Importance". |
|
|  | [JOB_TITLE](#JOB-TITLE) | Representerar fältet "Job Title". |
|
|  | [LAST_NAME](#LAST-NAME) | Representerar fältet "Last Name". |
|
|  | [LOCATION](#LOCATION) | Representerar fältet "Location". |
|
|  | [MIDDLE_NAME](#MIDDLE-NAME) | Representerar fältet "Middle Name". |
|
|  | [MOBILE](#MOBILE) | Representerar fältet "Mobile". |
|
|  | [ORGANIZER](#ORGANIZER) | Representerar fältet "Organizer". |
|
|  | [OTHER_ADDRESS](#OTHER-ADDRESS) | Representerar fältet "Other Address". |
|
|  | [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | Representerar fältet "Personal Homepage". |
|
|  | [PROFESSION](#PROFESSION) | Representerar fältet "Profession". |
|
|  | [RECURRENCE](#RECURRENCE) | Representerar fältet "Recurrence". |
|
|  | [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | Representerar fältet "Recurrence Pattern". |
|
|  | [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | Representerar fältet "Required Attendees". |
|
|  | [SENT](#SENT) | Representerar fältet "Sent". |
|
|  | [SHOW_TIME_AS](#SHOW-TIME-AS) | Representerar fältet "Show Time As". |
|
|  | [SPOUSE_PARTNER](#SPOUSE-PARTNER) | Representerar fältet "Spouse/Partner". |
|
|  | [START](#START) | Representerar fältet "Start". |
|
|  | [SUBJECT](#SUBJECT) | Representerar fältet "Subject". |
|
|  | [TO](#TO) | Representerar fältet "To". |
|
|  | [USER_FIELD_1](#USER-FIELD-1) | Representerar fältet "User Field 1". |
|
|  | [USER_FIELD_2](#USER-FIELD-2) | Representerar fältet "User Field 2". |
|
|  | [USER_FIELD_3](#USER-FIELD-3) | Representerar fältet "User Field 3". |
|
|  | [USER_FIELD_4](#USER-FIELD-4) | Representerar fältet "User Field 4". |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getName()](#getName--) | Fältnamn. |
|
|  | [toString()](#toString--) | Returnerar en sträng som representerar det aktuella objektet. |
|
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


Representerar fältet "Home Address".


### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


Representerar fältet "Importance".


### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


Representerar fältet "Job Title".


### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


Representerar fältet "Last Name".


### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


Representerar fältet "Location".


### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


Representerar fältet "Middle Name".


### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


Representerar fältet "Mobile".


### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


Representerar fältet "Organizer".


### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


Representerar fältet "Other Address".


### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


Representerar fältet "Personal Homepage".


### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


Representerar fältet "Profession".


### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


Representerar fältet "Recurrence".


### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


Representerar fältet "Recurrence Pattern".


### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


Representerar fältet "Required Attendees".


### SENT {#SENT}
```
public static final Field SENT
```


Representerar fältet "Sent".


### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


Representerar fältet "Show Time As".


### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


Representerar fältet "Spouse/Partner".


### START {#START}
```
public static final Field START
```


Representerar fältet "Start".


### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


Representerar fältet "Subject".


### TO {#TO}
```
public static final Field TO
```


Representerar fältet "To".


### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


Representerar fältet "User Field 1".


### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


Representerar fältet "User Field 2".


### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


Representerar fältet "User Field 3".


### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


Representerar fältet "User Field 4".


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

