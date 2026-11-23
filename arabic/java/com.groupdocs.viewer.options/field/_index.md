---
title: "حقل"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل حقول رسالة البريد الإلكتروني e46g46 From To Subject إلخ."
type: docs
weight: 40
url: /ar/java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

يمثل حقول رسالة البريد الإلكتروني مثل من، إلى، الموضوع، إلخ.


يمثل تعداد Field الحقول الشائعة لرسائل البريد الإلكتروني في مكوّن GroupDocs.Viewer.
يوفر مجموعة من الحقول المعرفة مسبقًا التي يمكن استخدامها لتحديد والوصول إلى عناصر محددة
معلومات في رسائل البريد الإلكتروني، مثل المرسل، المستلم، الموضوع، وأكثر.


للتفاصيل، انظر الـ [التوثيق](../https://docs.groupdocs.com/viewer/java/render-email-messages/#rename-fields-in-the-message-header).


مثال على الاستخدام:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 EmailOptions emailOptions = htmlViewOptions.getEmailOptions();
 emailOptions.getFieldTextMap().put(Field.FROM, "Sender");

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## الحقول

| حقل | الوصف |
| --- | --- |
|  | [ANNIVERSARY](#ANNIVERSARY) | يمثل حقل "Anniversary". |
|
|  | [ATTACHMENTS](#ATTACHMENTS) | يمثل حقل "Attachments". |
|
|  | [BCC](#BCC) | يمثل حقل "Bcc". |
|
|  | [BIRTHDAY](#BIRTHDAY) | يمثل حقل "Birthday". |
|
|  | [BUSINESS](#BUSINESS) | يمثل حقل "Business". |
|
|  | [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | يمثل حقل "Business Address". |
|
|  | [BUSINESS_FAX](#BUSINESS-FAX) | يمثل حقل "Business Fax". |
|
|  | [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | يمثل حقل "BusinessHomepage". |
|
|  | [CC](#CC) | يمثل حقل "Cc". |
|
|  | [COMPANY](#COMPANY) | يمثل حقل "Company". |
|
|  | [DEPARTMENT](#DEPARTMENT) | يمثل حقل "Department". |
|
|  | [EMAIL](#EMAIL) | يمثل حقل "Email". |
|
|  | [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | يمثل حقل "Email Display As". |
|
|  | [EMAIL_2](#EMAIL-2) | يمثل حقل "Email2". |
|
|  | [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | يمثل حقل "Email2 Display As". |
|
|  | [EMAIL_3](#EMAIL-3) | يمثل حقل "Email3". |
|
|  | [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | يمثل حقل "Email3 Display As". |
|
|  | [END](#END) | يمثل حقل "End". |
|
|  | [FIRST_NAME](#FIRST-NAME) | يمثل حقل "First Name". |
|
|  | [FROM](#FROM) | يمثل حقل "From". |
|
|  | [FULL_NAME](#FULL-NAME) | يمثل حقل "Full Name". |
|
|  | [GENDER](#GENDER) | يمثل حقل "Gender". |
|
|  | [HOBBIES](#HOBBIES) | يمثل حقل "Hobbies". |
|
|  | [HOME](#HOME) | يمثل الحقل "Home". |
|
|  | [HOME_ADDRESS](#HOME-ADDRESS) | يمثل الحقل "Home Address". |
|
|  | [IMPORTANCE](#IMPORTANCE) | يمثل الحقل "Importance". |
|
|  | [JOB_TITLE](#JOB-TITLE) | يمثل الحقل "Job Title". |
|
|  | [LAST_NAME](#LAST-NAME) | يمثل الحقل "Last Name". |
|
|  | [LOCATION](#LOCATION) | يمثل الحقل "Location". |
|
|  | [MIDDLE_NAME](#MIDDLE-NAME) | يمثل الحقل "Middle Name". |
|
|  | [MOBILE](#MOBILE) | يمثل الحقل "Mobile". |
|
|  | [ORGANIZER](#ORGANIZER) | يمثل الحقل "Organizer". |
|
|  | [OTHER_ADDRESS](#OTHER-ADDRESS) | يمثل الحقل "Other Address". |
|
|  | [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | يمثل الحقل "Personal Homepage". |
|
|  | [PROFESSION](#PROFESSION) | يمثل الحقل "Profession". |
|
|  | [RECURRENCE](#RECURRENCE) | يمثل الحقل "Recurrence". |
|
|  | [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | يمثل الحقل "Recurrence Pattern". |
|
|  | [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | يمثل الحقل "Required Attendees". |
|
|  | [SENT](#SENT) | يمثل الحقل "Sent". |
|
|  | [SHOW_TIME_AS](#SHOW-TIME-AS) | يمثل الحقل "Show Time As". |
|
|  | [SPOUSE_PARTNER](#SPOUSE-PARTNER) | يمثل الحقل "Spouse/Partner". |
|
|  | [START](#START) | يمثل الحقل "Start". |
|
|  | [SUBJECT](#SUBJECT) | يمثل الحقل "Subject". |
|
|  | [TO](#TO) | يمثل الحقل "To". |
|
|  | [USER_FIELD_1](#USER-FIELD-1) | يمثل الحقل "User Field 1". |
|
|  | [USER_FIELD_2](#USER-FIELD-2) | يمثل الحقل "User Field 2". |
|
|  | [USER_FIELD_3](#USER-FIELD-3) | يمثل الحقل "User Field 3". |
|
|  | [USER_FIELD_4](#USER-FIELD-4) | يمثل الحقل "User Field 4". |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getName()](#getName--) | اسم الحقل. |
|
|  | [toString()](#toString--) | إرجاع سلسلة تمثل الكائن الحالي. |
|
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


يمثل حقل "Anniversary".


### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


يمثل حقل "Attachments".


### BCC {#BCC}
```
public static final Field BCC
```


يمثل حقل "Bcc".


### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


يمثل حقل "Birthday".


### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


يمثل حقل "Business".


### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


يمثل حقل "Business Address".


### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


يمثل حقل "Business Fax".


### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


يمثل حقل "BusinessHomepage".


### CC {#CC}
```
public static final Field CC
```


يمثل حقل "Cc".


### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


يمثل حقل "Company".


### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


يمثل حقل "Department".


### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


يمثل حقل "Email".


### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


يمثل حقل "Email Display As".


### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


يمثل حقل "Email2".


### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


يمثل حقل "Email2 Display As".


### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


يمثل حقل "Email3".


### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


يمثل حقل "Email3 Display As".


### END {#END}
```
public static final Field END
```


يمثل حقل "End".


### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


يمثل حقل "First Name".


### FROM {#FROM}
```
public static final Field FROM
```


يمثل حقل "From".


### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


يمثل حقل "Full Name".


### GENDER {#GENDER}
```
public static final Field GENDER
```


يمثل حقل "Gender".


### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


يمثل حقل "Hobbies".


### HOME {#HOME}
```
public static final Field HOME
```


يمثل الحقل "Home".


### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


يمثل الحقل "Home Address".


### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


يمثل الحقل "Importance".


### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


يمثل الحقل "Job Title".


### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


يمثل الحقل "Last Name".


### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


يمثل الحقل "Location".


### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


يمثل الحقل "Middle Name".


### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


يمثل الحقل "Mobile".


### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


يمثل الحقل "Organizer".


### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


يمثل الحقل "Other Address".


### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


يمثل الحقل "Personal Homepage".


### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


يمثل الحقل "Profession".


### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


يمثل الحقل "Recurrence".


### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


يمثل الحقل "Recurrence Pattern".


### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


يمثل الحقل "Required Attendees".


### SENT {#SENT}
```
public static final Field SENT
```


يمثل الحقل "Sent".


### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


يمثل الحقل "Show Time As".


### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


يمثل الحقل "Spouse/Partner".


### START {#START}
```
public static final Field START
```


يمثل الحقل "Start".


### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


يمثل الحقل "Subject".


### TO {#TO}
```
public static final Field TO
```


يمثل الحقل "To".


### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


يمثل الحقل "User Field 1".


### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


يمثل الحقل "User Field 2".


### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


يمثل الحقل "User Field 3".


### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


يمثل الحقل "User Field 4".


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
| معامل | نوع | الوصف |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


اسم الحقل.


تسترجع هذه الطريقة اسم الحقل.


**Returns:**
java.lang.String - اسم الحقل.

### toString() {#toString--}
```
public String toString()
```


إرجاع سلسلة تمثل الكائن الحالي.


**Returns:**
java.lang.String - سلسلة تمثل الكائن الحالي.

