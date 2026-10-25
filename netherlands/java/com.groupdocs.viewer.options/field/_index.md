---
title: "Veld"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Stelt e‑mailberichtvelden e46g46 From To Subject enz. voor."
type: docs
weight: 40
url: /nl/java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

Stelt e‑mailberichtvelden voor, bijv. Van, Aan, Onderwerp enz.


De Field‑enum vertegenwoordigt veelvoorkomende e‑mailberichtvelden in de GroupDocs.Viewer‑component.
Het biedt een reeks vooraf gedefinieerde velden die kunnen worden gebruikt om specifieke te identificeren en te benaderen
informatie in e-mailberichten, zoals de afzender, ontvanger, onderwerp en meer.


Voor details, zie de [documentatie](../https://docs.groupdocs.com/viewer/java/render-email-messages/#rename-fields-in-the-message-header).


Voorbeeldgebruik:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 EmailOptions emailOptions = htmlViewOptions.getEmailOptions();
 emailOptions.getFieldTextMap().put(Field.FROM, "Sender");

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [ANNIVERSARY](#ANNIVERSARY) | Stelt het "Anniversary" veld voor. |
|
|  | [ATTACHMENTS](#ATTACHMENTS) | Stelt het "Attachments" veld voor. |
|
|  | [BCC](#BCC) | Stelt het "Bcc" veld voor. |
|
|  | [BIRTHDAY](#BIRTHDAY) | Stelt het "Birthday" veld voor. |
|
|  | [BUSINESS](#BUSINESS) | Stelt het "Business" veld voor. |
|
|  | [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | Stelt het "Business Address" veld voor. |
|
|  | [BUSINESS_FAX](#BUSINESS-FAX) | Stelt het "Business Fax" veld voor. |
|
|  | [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | Stelt het "BusinessHomepage" veld voor. |
|
|  | [CC](#CC) | Stelt het "Cc" veld voor. |
|
|  | [COMPANY](#COMPANY) | Stelt het "Company" veld voor. |
|
|  | [DEPARTMENT](#DEPARTMENT) | Stelt het "Department" veld voor. |
|
|  | [EMAIL](#EMAIL) | Stelt het "Email" veld voor. |
|
|  | [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | Stelt het "Email Display As" veld voor. |
|
|  | [EMAIL_2](#EMAIL-2) | Stelt het "Email2" veld voor. |
|
|  | [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | Stelt het "Email2 Display As" veld voor. |
|
|  | [EMAIL_3](#EMAIL-3) | Stelt het "Email3" veld voor. |
|
|  | [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | Stelt het "Email3 Display As" veld voor. |
|
|  | [END](#END) | Stelt het "End" veld voor. |
|
|  | [FIRST_NAME](#FIRST-NAME) | Stelt het "First Name" veld voor. |
|
|  | [FROM](#FROM) | Stelt het "From" veld voor. |
|
|  | [FULL_NAME](#FULL-NAME) | Stelt het "Full Name" veld voor. |
|
|  | [GENDER](#GENDER) | Stelt het "Gender" veld voor. |
|
|  | [HOBBIES](#HOBBIES) | Stelt het "Hobbies" veld voor. |
|
|  | [HOME](#HOME) | Vertegenwoordigt het "Home" veld. |
|
|  | [HOME_ADDRESS](#HOME-ADDRESS) | Vertegenwoordigt het "Home Address" veld. |
|
|  | [IMPORTANCE](#IMPORTANCE) | Vertegenwoordigt het "Importance" veld. |
|
|  | [JOB_TITLE](#JOB-TITLE) | Vertegenwoordigt het "Job Title" veld. |
|
|  | [LAST_NAME](#LAST-NAME) | Vertegenwoordigt het "Last Name" veld. |
|
|  | [LOCATION](#LOCATION) | Vertegenwoordigt het "Location" veld. |
|
|  | [MIDDLE_NAME](#MIDDLE-NAME) | Vertegenwoordigt het "Middle Name" veld. |
|
|  | [MOBILE](#MOBILE) | Vertegenwoordigt het "Mobile" veld. |
|
|  | [ORGANIZER](#ORGANIZER) | Vertegenwoordigt het "Organizer" veld. |
|
|  | [OTHER_ADDRESS](#OTHER-ADDRESS) | Vertegenwoordigt het "Other Address" veld. |
|
|  | [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | Vertegenwoordigt het "Personal Homepage" veld. |
|
|  | [PROFESSION](#PROFESSION) | Vertegenwoordigt het "Profession" veld. |
|
|  | [RECURRENCE](#RECURRENCE) | Vertegenwoordigt het "Recurrence" veld. |
|
|  | [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | Vertegenwoordigt het "Recurrence Pattern" veld. |
|
|  | [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | Vertegenwoordigt het "Required Attendees" veld. |
|
|  | [SENT](#SENT) | Vertegenwoordigt het "Sent" veld. |
|
|  | [SHOW_TIME_AS](#SHOW-TIME-AS) | Vertegenwoordigt het "Show Time As" veld. |
|
|  | [SPOUSE_PARTNER](#SPOUSE-PARTNER) | Vertegenwoordigt het "Spouse/Partner" veld. |
|
|  | [START](#START) | Vertegenwoordigt het "Start" veld. |
|
|  | [SUBJECT](#SUBJECT) | Vertegenwoordigt het "Subject" veld. |
|
|  | [TO](#TO) | Vertegenwoordigt het "To" veld. |
|
|  | [USER_FIELD_1](#USER-FIELD-1) | Vertegenwoordigt het "User Field 1" veld. |
|
|  | [USER_FIELD_2](#USER-FIELD-2) | Vertegenwoordigt het "User Field 2" veld. |
|
|  | [USER_FIELD_3](#USER-FIELD-3) | Vertegenwoordigt het "User Field 3" veld. |
|
|  | [USER_FIELD_4](#USER-FIELD-4) | Vertegenwoordigt het "User Field 4" veld. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getName()](#getName--) | Veldnaam. |
|
|  | [toString()](#toString--) | Retourneert een string die het huidige object vertegenwoordigt. |
|
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


Stelt het "Anniversary" veld voor.


### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


Stelt het "Attachments" veld voor.


### BCC {#BCC}
```
public static final Field BCC
```


Stelt het "Bcc" veld voor.


### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


Stelt het "Birthday" veld voor.


### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


Stelt het "Business" veld voor.


### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


Stelt het "Business Address" veld voor.


### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


Stelt het "Business Fax" veld voor.


### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


Stelt het "BusinessHomepage" veld voor.


### CC {#CC}
```
public static final Field CC
```


Stelt het "Cc" veld voor.


### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


Stelt het "Company" veld voor.


### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


Stelt het "Department" veld voor.


### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


Stelt het "Email" veld voor.


### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


Stelt het "Email Display As" veld voor.


### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


Stelt het "Email2" veld voor.


### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


Stelt het "Email2 Display As" veld voor.


### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


Stelt het "Email3" veld voor.


### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


Stelt het "Email3 Display As" veld voor.


### END {#END}
```
public static final Field END
```


Stelt het "End" veld voor.


### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


Stelt het "First Name" veld voor.


### FROM {#FROM}
```
public static final Field FROM
```


Stelt het "From" veld voor.


### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


Stelt het "Full Name" veld voor.


### GENDER {#GENDER}
```
public static final Field GENDER
```


Stelt het "Gender" veld voor.


### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


Stelt het "Hobbies" veld voor.


### HOME {#HOME}
```
public static final Field HOME
```


Vertegenwoordigt het "Home" veld.


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
| name | java.lang.String |  |

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

