---
title: "Champ"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Représente les champs de message électronique e46g46 From To Subject etc."
type: docs
weight: 40
url: /fr/java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

Représente les champs du message électronique, p. ex. De, À, Sujet, etc.


L'énumération Field représente les champs de message électronique courants dans le composant GroupDocs.Viewer.
Il fournit un ensemble de champs prédéfinis qui peuvent être utilisés pour identifier et accéder à des éléments spécifiques
informations dans les messages électroniques, telles que l'expéditeur, le destinataire, l'objet, et plus encore.


Pour plus de détails, consultez la [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#rename-fields-in-the-message-header).


Exemple d'utilisation :

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 EmailOptions emailOptions = htmlViewOptions.getEmailOptions();
 emailOptions.getFieldTextMap().put(Field.FROM, "Sender");

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Champs

| Champ | Description |
| --- | --- |
|  | [ANNIVERSARY](#ANNIVERSARY) | Représente le champ "Anniversary". |
|
|  | [ATTACHMENTS](#ATTACHMENTS) | Représente le champ "Attachments". |
|
|  | [BCC](#BCC) | Représente le champ "Bcc". |
|
|  | [BIRTHDAY](#BIRTHDAY) | Représente le champ "Birthday". |
|
|  | [BUSINESS](#BUSINESS) | Représente le champ "Business". |
|
|  | [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | Représente le champ "Business Address". |
|
|  | [BUSINESS_FAX](#BUSINESS-FAX) | Représente le champ "Business Fax". |
|
|  | [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | Représente le champ "BusinessHomepage". |
|
|  | [CC](#CC) | Représente le champ "Cc". |
|
|  | [COMPANY](#COMPANY) | Représente le champ "Company". |
|
|  | [DEPARTMENT](#DEPARTMENT) | Représente le champ "Department". |
|
|  | [EMAIL](#EMAIL) | Représente le champ "Email". |
|
|  | [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | Représente le champ "Email Display As". |
|
|  | [EMAIL_2](#EMAIL-2) | Représente le champ "Email2". |
|
|  | [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | Représente le champ "Email2 Display As". |
|
|  | [EMAIL_3](#EMAIL-3) | Représente le champ "Email3". |
|
|  | [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | Représente le champ "Email3 Display As". |
|
|  | [END](#END) | Représente le champ "End". |
|
|  | [FIRST_NAME](#FIRST-NAME) | Représente le champ "First Name". |
|
|  | [FROM](#FROM) | Représente le champ "From". |
|
|  | [FULL_NAME](#FULL-NAME) | Représente le champ "Full Name". |
|
|  | [GENDER](#GENDER) | Représente le champ "Gender". |
|
|  | [HOBBIES](#HOBBIES) | Représente le champ "Hobbies". |
|
|  | [HOME](#HOME) | Représente le champ "Home". |
|
|  | [HOME_ADDRESS](#HOME-ADDRESS) | Représente le champ "Home Address". |
|
|  | [IMPORTANCE](#IMPORTANCE) | Représente le champ "Importance". |
|
|  | [JOB_TITLE](#JOB-TITLE) | Représente le champ "Job Title". |
|
|  | [LAST_NAME](#LAST-NAME) | Représente le champ "Last Name". |
|
|  | [LOCATION](#LOCATION) | Représente le champ "Location". |
|
|  | [MIDDLE_NAME](#MIDDLE-NAME) | Représente le champ "Middle Name". |
|
|  | [MOBILE](#MOBILE) | Représente le champ "Mobile". |
|
|  | [ORGANIZER](#ORGANIZER) | Représente le champ "Organizer". |
|
|  | [OTHER_ADDRESS](#OTHER-ADDRESS) | Représente le champ "Other Address". |
|
|  | [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | Représente le champ "Personal Homepage". |
|
|  | [PROFESSION](#PROFESSION) | Représente le champ "Profession". |
|
|  | [RECURRENCE](#RECURRENCE) | Représente le champ "Recurrence". |
|
|  | [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | Représente le champ "Recurrence Pattern". |
|
|  | [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | Représente le champ "Required Attendees". |
|
|  | [SENT](#SENT) | Représente le champ "Sent". |
|
|  | [SHOW_TIME_AS](#SHOW-TIME-AS) | Représente le champ "Show Time As". |
|
|  | [SPOUSE_PARTNER](#SPOUSE-PARTNER) | Représente le champ "Spouse/Partner". |
|
|  | [START](#START) | Représente le champ "Start". |
|
|  | [SUBJECT](#SUBJECT) | Représente le champ "Subject". |
|
|  | [TO](#TO) | Représente le champ "To". |
|
|  | [USER_FIELD_1](#USER-FIELD-1) | Représente le champ "User Field 1". |
|
|  | [USER_FIELD_2](#USER-FIELD-2) | Représente le champ "User Field 2". |
|
|  | [USER_FIELD_3](#USER-FIELD-3) | Représente le champ "User Field 3". |
|
|  | [USER_FIELD_4](#USER-FIELD-4) | Représente le champ "User Field 4". |
|
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getName()](#getName--) | Nom du champ. |
|
|  | [toString()](#toString--) | Renvoie une chaîne qui représente l'objet actuel. |
|
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


Représente le champ "Anniversary".


### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


Représente le champ "Attachments".


### BCC {#BCC}
```
public static final Field BCC
```


Représente le champ "Bcc".


### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


Représente le champ "Birthday".


### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


Représente le champ "Business".


### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


Représente le champ "Business Address".


### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


Représente le champ "Business Fax".


### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


Représente le champ "BusinessHomepage".


### CC {#CC}
```
public static final Field CC
```


Représente le champ "Cc".


### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


Représente le champ "Company".


### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


Représente le champ "Department".


### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


Représente le champ "Email".


### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


Représente le champ "Email Display As".


### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


Représente le champ "Email2".


### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


Représente le champ "Email2 Display As".


### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


Représente le champ "Email3".


### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


Représente le champ "Email3 Display As".


### END {#END}
```
public static final Field END
```


Représente le champ "End".


### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


Représente le champ "First Name".


### FROM {#FROM}
```
public static final Field FROM
```


Représente le champ "From".


### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


Représente le champ "Full Name".


### GENDER {#GENDER}
```
public static final Field GENDER
```


Représente le champ "Gender".


### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


Représente le champ "Hobbies".


### HOME {#HOME}
```
public static final Field HOME
```


Représente le champ "Home".


### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


Représente le champ "Home Address".


### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


Représente le champ "Importance".


### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


Représente le champ "Job Title".


### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


Représente le champ "Last Name".


### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


Représente le champ "Location".


### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


Représente le champ "Middle Name".


### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


Représente le champ "Mobile".


### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


Représente le champ "Organizer".


### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


Représente le champ "Other Address".


### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


Représente le champ "Personal Homepage".


### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


Représente le champ "Profession".


### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


Représente le champ "Recurrence".


### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


Représente le champ "Recurrence Pattern".


### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


Représente le champ "Required Attendees".


### SENT {#SENT}
```
public static final Field SENT
```


Représente le champ "Sent".


### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


Représente le champ "Show Time As".


### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


Représente le champ "Spouse/Partner".


### START {#START}
```
public static final Field START
```


Représente le champ "Start".


### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


Représente le champ "Subject".


### TO {#TO}
```
public static final Field TO
```


Représente le champ "To".


### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


Représente le champ "User Field 1".


### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


Représente le champ "User Field 2".


### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


Représente le champ "User Field 3".


### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


Représente le champ "User Field 4".


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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


Nom du champ.


Cette méthode récupère le nom du champ.


**Returns:**
java.lang.String - le nom du champ.

### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne qui représente l'objet actuel.


**Returns:**
java.lang.String - une chaîne qui représente l'objet actuel.

