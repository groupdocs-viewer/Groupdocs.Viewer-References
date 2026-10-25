---
title: "Campo"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Representa los campos de mensaje de correo electrónico e46g46 From To Subject etc."
type: docs
weight: 40
url: /es/java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

Representa los campos del mensaje de correo electrónico, p. ej., De, Para, Asunto, etc.


El enum Field representa los campos comunes de mensajes de correo electrónico en el componente GroupDocs.Viewer.
Proporciona un conjunto de campos predefinidos que pueden usarse para identificar y acceder a elementos específicos
información en mensajes de correo electrónico, como el remitente, el destinatario, el asunto y más.


Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-email-messages/#rename-fields-in-the-message-header).


Ejemplo de uso:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 EmailOptions emailOptions = htmlViewOptions.getEmailOptions();
 emailOptions.getFieldTextMap().put(Field.FROM, "Sender");

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Campos

| Campo | Descripción |
| --- | --- |
|  | [ANNIVERSARY](#ANNIVERSARY) | Representa el campo "Anniversary". |
|
|  | [ATTACHMENTS](#ATTACHMENTS) | Representa el campo "Attachments". |
|
|  | [BCC](#BCC) | Representa el campo "Bcc". |
|
|  | [BIRTHDAY](#BIRTHDAY) | Representa el campo "Birthday". |
|
|  | [BUSINESS](#BUSINESS) | Representa el campo "Business". |
|
|  | [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | Representa el campo "Business Address". |
|
|  | [BUSINESS_FAX](#BUSINESS-FAX) | Representa el campo "Business Fax". |
|
|  | [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | Representa el campo "BusinessHomepage". |
|
|  | [CC](#CC) | Representa el campo "Cc". |
|
|  | [COMPANY](#COMPANY) | Representa el campo "Company". |
|
|  | [DEPARTMENT](#DEPARTMENT) | Representa el campo "Department". |
|
|  | [EMAIL](#EMAIL) | Representa el campo "Email". |
|
|  | [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | Representa el campo "Email Display As". |
|
|  | [EMAIL_2](#EMAIL-2) | Representa el campo "Email2". |
|
|  | [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | Representa el campo "Email2 Display As". |
|
|  | [EMAIL_3](#EMAIL-3) | Representa el campo "Email3". |
|
|  | [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | Representa el campo "Email3 Display As". |
|
|  | [END](#END) | Representa el campo "End". |
|
|  | [FIRST_NAME](#FIRST-NAME) | Representa el campo "First Name". |
|
|  | [FROM](#FROM) | Representa el campo "From". |
|
|  | [FULL_NAME](#FULL-NAME) | Representa el campo "Full Name". |
|
|  | [GENDER](#GENDER) | Representa el campo "Gender". |
|
|  | [HOBBIES](#HOBBIES) | Representa el campo "Hobbies". |
|
|  | [HOME](#HOME) | Representa el campo "Home". |
|
|  | [HOME_ADDRESS](#HOME-ADDRESS) | Representa el campo "Home Address". |
|
|  | [IMPORTANCE](#IMPORTANCE) | Representa el campo "Importance". |
|
|  | [JOB_TITLE](#JOB-TITLE) | Representa el campo "Job Title". |
|
|  | [LAST_NAME](#LAST-NAME) | Representa el campo "Last Name". |
|
|  | [LOCATION](#LOCATION) | Representa el campo "Location". |
|
|  | [MIDDLE_NAME](#MIDDLE-NAME) | Representa el campo "Middle Name". |
|
|  | [MOBILE](#MOBILE) | Representa el campo "Mobile". |
|
|  | [ORGANIZER](#ORGANIZER) | Representa el campo "Organizer". |
|
|  | [OTHER_ADDRESS](#OTHER-ADDRESS) | Representa el campo "Other Address". |
|
|  | [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | Representa el campo "Personal Homepage". |
|
|  | [PROFESSION](#PROFESSION) | Representa el campo "Profession". |
|
|  | [RECURRENCE](#RECURRENCE) | Representa el campo "Recurrence". |
|
|  | [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | Representa el campo "Recurrence Pattern". |
|
|  | [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | Representa el campo "Required Attendees". |
|
|  | [SENT](#SENT) | Representa el campo "Sent". |
|
|  | [SHOW_TIME_AS](#SHOW-TIME-AS) | Representa el campo "Show Time As". |
|
|  | [SPOUSE_PARTNER](#SPOUSE-PARTNER) | Representa el campo "Spouse/Partner". |
|
|  | [START](#START) | Representa el campo "Start". |
|
|  | [SUBJECT](#SUBJECT) | Representa el campo "Subject". |
|
|  | [TO](#TO) | Representa el campo "To". |
|
|  | [USER_FIELD_1](#USER-FIELD-1) | Representa el campo "User Field 1". |
|
|  | [USER_FIELD_2](#USER-FIELD-2) | Representa el campo "User Field 2". |
|
|  | [USER_FIELD_3](#USER-FIELD-3) | Representa el campo "User Field 3". |
|
|  | [USER_FIELD_4](#USER-FIELD-4) | Representa el campo "User Field 4". |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getName()](#getName--) | Nombre del campo. |
|
|  | [toString()](#toString--) | Devuelve una cadena que representa el objeto actual. |
|
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


Representa el campo "Anniversary".


### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


Representa el campo "Attachments".


### BCC {#BCC}
```
public static final Field BCC
```


Representa el campo "Bcc".


### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


Representa el campo "Birthday".


### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


Representa el campo "Business".


### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


Representa el campo "Business Address".


### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


Representa el campo "Business Fax".


### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


Representa el campo "BusinessHomepage".


### CC {#CC}
```
public static final Field CC
```


Representa el campo "Cc".


### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


Representa el campo "Company".


### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


Representa el campo "Department".


### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


Representa el campo "Email".


### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


Representa el campo "Email Display As".


### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


Representa el campo "Email2".


### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


Representa el campo "Email2 Display As".


### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


Representa el campo "Email3".


### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


Representa el campo "Email3 Display As".


### END {#END}
```
public static final Field END
```


Representa el campo "End".


### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


Representa el campo "First Name".


### FROM {#FROM}
```
public static final Field FROM
```


Representa el campo "From".


### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


Representa el campo "Full Name".


### GENDER {#GENDER}
```
public static final Field GENDER
```


Representa el campo "Gender".


### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


Representa el campo "Hobbies".


### HOME {#HOME}
```
public static final Field HOME
```


Representa el campo "Home".


### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


Representa el campo "Home Address".


### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


Representa el campo "Importance".


### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


Representa el campo "Job Title".


### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


Representa el campo "Last Name".


### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


Representa el campo "Location".


### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


Representa el campo "Middle Name".


### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


Representa el campo "Mobile".


### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


Representa el campo "Organizer".


### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


Representa el campo "Other Address".


### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


Representa el campo "Personal Homepage".


### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


Representa el campo "Profession".


### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


Representa el campo "Recurrence".


### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


Representa el campo "Recurrence Pattern".


### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


Representa el campo "Required Attendees".


### SENT {#SENT}
```
public static final Field SENT
```


Representa el campo "Sent".


### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


Representa el campo "Show Time As".


### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


Representa el campo "Spouse/Partner".


### START {#START}
```
public static final Field START
```


Representa el campo "Start".


### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


Representa el campo "Subject".


### TO {#TO}
```
public static final Field TO
```


Representa el campo "To".


### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


Representa el campo "User Field 1".


### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


Representa el campo "User Field 2".


### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


Representa el campo "User Field 3".


### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


Representa el campo "User Field 4".


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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


Nombre del campo.


Este método recupera el nombre del campo.


**Returns:**
java.lang.String - el nombre del campo.

### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que representa el objeto actual.


**Returns:**
java.lang.String - una cadena que representa el objeto actual.

