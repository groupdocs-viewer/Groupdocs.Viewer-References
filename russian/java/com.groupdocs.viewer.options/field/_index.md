---
title: "Поле"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Представляет поля сообщения электронной почты e46g46 From To Subject и т.д."
type: docs
weight: 40
url: /ru/java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

Представляет поля сообщения электронной почты, например From, To, Subject и т.д.


Перечисление Field представляет общие поля сообщения электронной почты в компоненте GroupDocs.Viewer.
Он предоставляет набор предопределённых полей, которые можно использовать для идентификации и доступа к конкретным
информация в электронных письмах, такая как отправитель, получатель, тема и многое другое.


Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/java/render-email-messages/#rename-fields-in-the-message-header).


Пример использования:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 EmailOptions emailOptions = htmlViewOptions.getEmailOptions();
 emailOptions.getFieldTextMap().put(Field.FROM, "Sender");

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Поля

| Поле | Описание |
| --- | --- |
|  | [ANNIVERSARY](#ANNIVERSARY) | Представляет поле "Anniversary". |
|
|  | [ATTACHMENTS](#ATTACHMENTS) | Представляет поле "Attachments". |
|
|  | [BCC](#BCC) | Представляет поле "Bcc". |
|
|  | [BIRTHDAY](#BIRTHDAY) | Представляет поле "Birthday". |
|
|  | [BUSINESS](#BUSINESS) | Представляет поле "Business". |
|
|  | [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | Представляет поле "Business Address". |
|
|  | [BUSINESS_FAX](#BUSINESS-FAX) | Представляет поле "Business Fax". |
|
|  | [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | Представляет поле "BusinessHomepage". |
|
|  | [CC](#CC) | Представляет поле "Cc". |
|
|  | [COMPANY](#COMPANY) | Представляет поле "Company". |
|
|  | [DEPARTMENT](#DEPARTMENT) | Представляет поле "Department". |
|
|  | [EMAIL](#EMAIL) | Представляет поле "Email". |
|
|  | [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | Представляет поле "Email Display As". |
|
|  | [EMAIL_2](#EMAIL-2) | Представляет поле "Email2". |
|
|  | [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | Представляет поле "Email2 Display As". |
|
|  | [EMAIL_3](#EMAIL-3) | Представляет поле "Email3". |
|
|  | [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | Представляет поле "Email3 Display As". |
|
|  | [END](#END) | Представляет поле "End". |
|
|  | [FIRST_NAME](#FIRST-NAME) | Представляет поле "First Name". |
|
|  | [FROM](#FROM) | Представляет поле "From". |
|
|  | [FULL_NAME](#FULL-NAME) | Представляет поле "Full Name". |
|
|  | [GENDER](#GENDER) | Представляет поле "Gender". |
|
|  | [HOBBIES](#HOBBIES) | Представляет поле "Hobbies". |
|
|  | [HOME](#HOME) | Представляет поле "Home". |
|
|  | [HOME_ADDRESS](#HOME-ADDRESS) | Представляет поле "Home Address". |
|
|  | [IMPORTANCE](#IMPORTANCE) | Представляет поле "Importance". |
|
|  | [JOB_TITLE](#JOB-TITLE) | Представляет поле "Job Title". |
|
|  | [LAST_NAME](#LAST-NAME) | Представляет поле "Last Name". |
|
|  | [LOCATION](#LOCATION) | Представляет поле "Location". |
|
|  | [MIDDLE_NAME](#MIDDLE-NAME) | Представляет поле "Middle Name". |
|
|  | [MOBILE](#MOBILE) | Представляет поле "Mobile". |
|
|  | [ORGANIZER](#ORGANIZER) | Представляет поле "Organizer". |
|
|  | [OTHER_ADDRESS](#OTHER-ADDRESS) | Представляет поле "Other Address". |
|
|  | [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | Представляет поле "Personal Homepage". |
|
|  | [PROFESSION](#PROFESSION) | Представляет поле "Profession". |
|
|  | [RECURRENCE](#RECURRENCE) | Представляет поле "Recurrence". |
|
|  | [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | Представляет поле "Recurrence Pattern". |
|
|  | [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | Представляет поле "Required Attendees". |
|
|  | [SENT](#SENT) | Представляет поле "Sent". |
|
|  | [SHOW_TIME_AS](#SHOW-TIME-AS) | Представляет поле "Show Time As". |
|
|  | [SPOUSE_PARTNER](#SPOUSE-PARTNER) | Представляет поле "Spouse/Partner". |
|
|  | [START](#START) | Представляет поле "Start". |
|
|  | [SUBJECT](#SUBJECT) | Представляет поле "Subject". |
|
|  | [TO](#TO) | Представляет поле "To". |
|
|  | [USER_FIELD_1](#USER-FIELD-1) | Представляет поле "User Field 1". |
|
|  | [USER_FIELD_2](#USER-FIELD-2) | Представляет поле "User Field 2". |
|
|  | [USER_FIELD_3](#USER-FIELD-3) | Представляет поле "User Field 3". |
|
|  | [USER_FIELD_4](#USER-FIELD-4) | Представляет поле "User Field 4". |
|
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getName()](#getName--) | Имя поля. |
|
|  | [toString()](#toString--) | Возвращает строку, представляющую текущий объект. |
|
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


Представляет поле "Anniversary".


### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


Представляет поле "Attachments".


### BCC {#BCC}
```
public static final Field BCC
```


Представляет поле "Bcc".


### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


Представляет поле "Birthday".


### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


Представляет поле "Business".


### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


Представляет поле "Business Address".


### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


Представляет поле "Business Fax".


### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


Представляет поле "BusinessHomepage".


### CC {#CC}
```
public static final Field CC
```


Представляет поле "Cc".


### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


Представляет поле "Company".


### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


Представляет поле "Department".


### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


Представляет поле "Email".


### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


Представляет поле "Email Display As".


### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


Представляет поле "Email2".


### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


Представляет поле "Email2 Display As".


### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


Представляет поле "Email3".


### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


Представляет поле "Email3 Display As".


### END {#END}
```
public static final Field END
```


Представляет поле "End".


### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


Представляет поле "First Name".


### FROM {#FROM}
```
public static final Field FROM
```


Представляет поле "From".


### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


Представляет поле "Full Name".


### GENDER {#GENDER}
```
public static final Field GENDER
```


Представляет поле "Gender".


### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


Представляет поле "Hobbies".


### HOME {#HOME}
```
public static final Field HOME
```


Представляет поле "Home".


### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


Представляет поле "Home Address".


### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


Представляет поле "Importance".


### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


Представляет поле "Job Title".


### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


Представляет поле "Last Name".


### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


Представляет поле "Location".


### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


Представляет поле "Middle Name".


### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


Представляет поле "Mobile".


### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


Представляет поле "Organizer".


### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


Представляет поле "Other Address".


### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


Представляет поле "Personal Homepage".


### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


Представляет поле "Profession".


### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


Представляет поле "Recurrence".


### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


Представляет поле "Recurrence Pattern".


### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


Представляет поле "Required Attendees".


### SENT {#SENT}
```
public static final Field SENT
```


Представляет поле "Sent".


### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


Представляет поле "Show Time As".


### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


Представляет поле "Spouse/Partner".


### START {#START}
```
public static final Field START
```


Представляет поле "Start".


### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


Представляет поле "Subject".


### TO {#TO}
```
public static final Field TO
```


Представляет поле "To".


### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


Представляет поле "User Field 1".


### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


Представляет поле "User Field 2".


### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


Представляет поле "User Field 3".


### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


Представляет поле "User Field 4".


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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


Имя поля.


Этот метод получает имя поля.


**Returns:**
java.lang.String — имя поля.

### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую текущий объект.


**Returns:**
java.lang.String — строка, представляющая текущий объект.

