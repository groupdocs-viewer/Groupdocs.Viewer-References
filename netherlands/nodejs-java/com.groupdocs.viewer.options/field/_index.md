---
title: "Veld"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Stelt e‑mailberichtvelden voor, zoals e46g46 From To Subject enz."
type: docs
weight: 40
url: /nl/nodejs-java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

Stelt e-mailberichtvelden voor, bijv. Van, Aan, Onderwerp enz.

De Field-enumeratie vertegenwoordigt veelvoorkomende e-mailberichtvelden in de GroupDocs.Viewer-component. Het biedt een set vooraf gedefinieerde velden die kunnen worden gebruikt om specifieke informatie in e-mailberichten te identificeren en te benaderen, zoals de afzender, ontvanger, onderwerp en meer.

Voor details, zie de [documentatie][].

Voorbeeldgebruik:

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
## Velden

| Veld | Beschrijving |
| --- | --- |
| [ANNIVERSARY](#ANNIVERSARY) | Vertegenwoordigt het "Anniversary"-veld. |
| [ATTACHMENTS](#ATTACHMENTS) | Vertegenwoordigt het "Attachments"-veld. |
| [BCC](#BCC) | Vertegenwoordigt het "Bcc"-veld. |
| [BIRTHDAY](#BIRTHDAY) | Vertegenwoordigt het "Birthday"-veld. |
| [BUSINESS](#BUSINESS) | Vertegenwoordigt het "Business"-veld. |
| [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | Vertegenwoordigt het "Business Address"-veld. |
| [BUSINESS_FAX](#BUSINESS-FAX) | Vertegenwoordigt het "Business Fax"-veld. |
| [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | Vertegenwoordigt het "BusinessHomepage"-veld. |
| [CC](#CC) | Vertegenwoordigt het "Cc"-veld. |
| [COMPANY](#COMPANY) | Vertegenwoordigt het "Company"-veld. |
| [DEPARTMENT](#DEPARTMENT) | Vertegenwoordigt het "Department"-veld. |
| [EMAIL](#EMAIL) | Vertegenwoordigt het "Email"-veld. |
| [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | Vertegenwoordigt het "Email Display As"-veld. |
| [EMAIL_2](#EMAIL-2) | Vertegenwoordigt het "Email2"-veld. |
| [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | Vertegenwoordigt het "Email2 Display As"-veld. |
| [EMAIL_3](#EMAIL-3) | Vertegenwoordigt het "Email3"-veld. |
| [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | Vertegenwoordigt het "Email3 Display As"-veld. |
| [END](#END) | Vertegenwoordigt het "End"-veld. |
| [FIRST_NAME](#FIRST-NAME) | Vertegenwoordigt het "First Name"-veld. |
| [FROM](#FROM) | Vertegenwoordigt het "From"-veld. |
| [FULL_NAME](#FULL-NAME) | Vertegenwoordigt het "Full Name"-veld. |
| [GENDER](#GENDER) | Vertegenwoordigt het "Gender"-veld. |
| [HOBBIES](#HOBBIES) | Vertegenwoordigt het "Hobbies"-veld. |
| [HOME](#HOME) | Vertegenwoordigt het "Home"-veld. |
| [HOME_ADDRESS](#HOME-ADDRESS) | Vertegenwoordigt het "Home Address" veld. |
| [IMPORTANCE](#IMPORTANCE) | Vertegenwoordigt het "Importance" veld. |
| [JOB_TITLE](#JOB-TITLE) | Vertegenwoordigt het "Job Title" veld. |
| [LAST_NAME](#LAST-NAME) | Vertegenwoordigt het "Last Name" veld. |
| [LOCATION](#LOCATION) | Vertegenwoordigt het "Location" veld. |
| [MIDDLE_NAME](#MIDDLE-NAME) | Vertegenwoordigt het "Middle Name" veld. |
| [MOBILE](#MOBILE) | Vertegenwoordigt het "Mobile" veld. |
| [ORGANIZER](#ORGANIZER) | Vertegenwoordigt het "Organizer" veld. |
| [OTHER_ADDRESS](#OTHER-ADDRESS) | Vertegenwoordigt het "Other Address" veld. |
| [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | Vertegenwoordigt het "Personal Homepage" veld. |
| [PROFESSION](#PROFESSION) | Vertegenwoordigt het "Profession" veld. |
| [RECURRENCE](#RECURRENCE) | Vertegenwoordigt het "Recurrence" veld. |
| [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | Vertegenwoordigt het "Recurrence Pattern" veld. |
| [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | Vertegenwoordigt het "Required Attendees" veld. |
| [SENT](#SENT) | Vertegenwoordigt het "Sent" veld. |
| [SHOW_TIME_AS](#SHOW-TIME-AS) | Vertegenwoordigt het "Show Time As" veld. |
| [SPOUSE_PARTNER](#SPOUSE-PARTNER) | Vertegenwoordigt het "Spouse/Partner" veld. |
| [START](#START) | Vertegenwoordigt het "Start" veld. |
| [SUBJECT](#SUBJECT) | Vertegenwoordigt het "Subject" veld. |
| [TO](#TO) | Vertegenwoordigt het "To" veld. |
| [USER_FIELD_1](#USER-FIELD-1) | Vertegenwoordigt het "User Field 1" veld. |
| [USER_FIELD_2](#USER-FIELD-2) | Vertegenwoordigt het "User Field 2" veld. |
| [USER_FIELD_3](#USER-FIELD-3) | Vertegenwoordigt het "User Field 3" veld. |
| [USER_FIELD_4](#USER-FIELD-4) | Vertegenwoordigt het "User Field 4" veld. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getName()](#getName--) | Veldnaam. |
| [toString()](#toString--) | Retourneert een string die het huidige object vertegenwoordigt. |
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


Vertegenwoordigt het "Anniversary"-veld.

### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


Vertegenwoordigt het "Attachments"-veld.

### BCC {#BCC}
```
public static final Field BCC
```


Vertegenwoordigt het "Bcc"-veld.

### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


Vertegenwoordigt het "Birthday"-veld.

### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


Vertegenwoordigt het "Business"-veld.

### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


Vertegenwoordigt het "Business Address"-veld.

### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


Vertegenwoordigt het "Business Fax"-veld.

### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


Vertegenwoordigt het "BusinessHomepage"-veld.

### CC {#CC}
```
public static final Field CC
```


Vertegenwoordigt het "Cc"-veld.

### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


Vertegenwoordigt het "Company"-veld.

### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


Vertegenwoordigt het "Department"-veld.

### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


Vertegenwoordigt het "Email"-veld.

### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


Vertegenwoordigt het "Email Display As"-veld.

### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


Vertegenwoordigt het "Email2"-veld.

### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


Vertegenwoordigt het "Email2 Display As"-veld.

### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


Vertegenwoordigt het "Email3"-veld.

### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


Vertegenwoordigt het "Email3 Display As"-veld.

### END {#END}
```
public static final Field END
```


Vertegenwoordigt het "End"-veld.

### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


Vertegenwoordigt het "First Name"-veld.

### FROM {#FROM}
```
public static final Field FROM
```


Vertegenwoordigt het "From"-veld.

### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


Vertegenwoordigt het "Full Name"-veld.

### GENDER {#GENDER}
```
public static final Field GENDER
```


Vertegenwoordigt het "Gender"-veld.

### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


Vertegenwoordigt het "Hobbies"-veld.

### HOME {#HOME}
```
public static final Field HOME
```


Vertegenwoordigt het "Home"-veld.

### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


Vertegenwoordigt het "Home Address" veld.

### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


Vertegenwoordigt het "Importance" veld.

### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


Vertegenwoordigt het "Job Title" veld.

### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


Vertegenwoordigt het "Last Name" veld.

### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


Vertegenwoordigt het "Location" veld.

### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


Vertegenwoordigt het "Middle Name" veld.

### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


Vertegenwoordigt het "Mobile" veld.

### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


Vertegenwoordigt het "Organizer" veld.

### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


Vertegenwoordigt het "Other Address" veld.

### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


Vertegenwoordigt het "Personal Homepage" veld.

### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


Vertegenwoordigt het "Profession" veld.

### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


Vertegenwoordigt het "Recurrence" veld.

### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


Vertegenwoordigt het "Recurrence Pattern" veld.

### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


Vertegenwoordigt het "Required Attendees" veld.

### SENT {#SENT}
```
public static final Field SENT
```


Vertegenwoordigt het "Sent" veld.

### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


Vertegenwoordigt het "Show Time As" veld.

### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


Vertegenwoordigt het "Spouse/Partner" veld.

### START {#START}
```
public static final Field START
```


Vertegenwoordigt het "Start" veld.

### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


Vertegenwoordigt het "Subject" veld.

### TO {#TO}
```
public static final Field TO
```


Vertegenwoordigt het "To" veld.

### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


Vertegenwoordigt het "User Field 1" veld.

### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


Vertegenwoordigt het "User Field 2" veld.

### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


Vertegenwoordigt het "User Field 3" veld.

### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


Vertegenwoordigt het "User Field 4" veld.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


Veldnaam.

Deze methode haalt de naam van het veld op.

**Returns:**
java.lang.String - de naam van het veld.
### toString() {#toString--}
```
public String toString()
```


Retourneert een string die het huidige object vertegenwoordigt.

**Returns:**
java.lang.String - een string die het huidige object vertegenwoordigt.
