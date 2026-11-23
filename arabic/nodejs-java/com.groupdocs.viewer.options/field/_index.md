---
title: "حقل"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يمثل حقول رسالة البريد الإلكتروني مثل e46g46 From To Subject وغيرها."
type: docs
weight: 40
url: /ar/nodejs-java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

يمثل حقول رسالة البريد الإلكتروني مثل من، إلى، الموضوع، إلخ.

يمثل تعداد Field الحقول الشائعة لرسائل البريد الإلكتروني في مكوّن GroupDocs.Viewer. يوفر مجموعة من الحقول المعرفة مسبقًا التي يمكن استخدامها لتحديد والوصول إلى معلومات محددة في رسائل البريد الإلكتروني، مثل المرسل، المستلم، الموضوع، وأكثر.

للتفاصيل، راجع [documentation][].

مثال على الاستخدام:

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
## الحقول

| حقل | الوصف |
| --- | --- |
| [ANNIVERSARY](#ANNIVERSARY) | يمثل الحقل "Anniversary". |
| [ATTACHMENTS](#ATTACHMENTS) | يمثل الحقل "Attachments". |
| [BCC](#BCC) | يمثل الحقل "Bcc". |
| [BIRTHDAY](#BIRTHDAY) | يمثل الحقل "Birthday". |
| [BUSINESS](#BUSINESS) | يمثل الحقل "Business". |
| [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | يمثل الحقل "Business Address". |
| [BUSINESS_FAX](#BUSINESS-FAX) | يمثل الحقل "Business Fax". |
| [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | يمثل الحقل "BusinessHomepage". |
| [CC](#CC) | يمثل الحقل "Cc". |
| [COMPANY](#COMPANY) | يمثل الحقل "Company". |
| [DEPARTMENT](#DEPARTMENT) | يمثل الحقل "Department". |
| [EMAIL](#EMAIL) | يمثل الحقل "Email". |
| [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | يمثل الحقل "Email Display As". |
| [EMAIL_2](#EMAIL-2) | يمثل الحقل "Email2". |
| [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | يمثل الحقل "Email2 Display As". |
| [EMAIL_3](#EMAIL-3) | يمثل الحقل "Email3". |
| [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | يمثل الحقل "Email3 Display As". |
| [END](#END) | يمثل الحقل "End". |
| [FIRST_NAME](#FIRST-NAME) | يمثل الحقل "First Name". |
| [FROM](#FROM) | يمثل الحقل "From". |
| [FULL_NAME](#FULL-NAME) | يمثل الحقل "Full Name". |
| [GENDER](#GENDER) | يمثل الحقل "Gender". |
| [HOBBIES](#HOBBIES) | يمثل الحقل "Hobbies". |
| [HOME](#HOME) | يمثل الحقل "Home". |
| [HOME_ADDRESS](#HOME-ADDRESS) | يمثل حقل "Home Address". |
| [IMPORTANCE](#IMPORTANCE) | يمثل حقل "Importance". |
| [JOB_TITLE](#JOB-TITLE) | يمثل حقل "Job Title". |
| [LAST_NAME](#LAST-NAME) | يمثل حقل "Last Name". |
| [LOCATION](#LOCATION) | يمثل حقل "Location". |
| [MIDDLE_NAME](#MIDDLE-NAME) | يمثل حقل "Middle Name". |
| [MOBILE](#MOBILE) | يمثل حقل "Mobile". |
| [ORGANIZER](#ORGANIZER) | يمثل حقل "Organizer". |
| [OTHER_ADDRESS](#OTHER-ADDRESS) | يمثل حقل "Other Address". |
| [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | يمثل حقل "Personal Homepage". |
| [PROFESSION](#PROFESSION) | يمثل حقل "Profession". |
| [RECURRENCE](#RECURRENCE) | يمثل حقل "Recurrence". |
| [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | يمثل حقل "Recurrence Pattern". |
| [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | يمثل حقل "Required Attendees". |
| [SENT](#SENT) | يمثل حقل "Sent". |
| [SHOW_TIME_AS](#SHOW-TIME-AS) | يمثل حقل "Show Time As". |
| [SPOUSE_PARTNER](#SPOUSE-PARTNER) | يمثل حقل "Spouse/Partner". |
| [START](#START) | يمثل حقل "Start". |
| [SUBJECT](#SUBJECT) | يمثل حقل "Subject". |
| [TO](#TO) | يمثل حقل "To". |
| [USER_FIELD_1](#USER-FIELD-1) | يمثل حقل "User Field 1". |
| [USER_FIELD_2](#USER-FIELD-2) | يمثل حقل "User Field 2". |
| [USER_FIELD_3](#USER-FIELD-3) | يمثل حقل "User Field 3". |
| [USER_FIELD_4](#USER-FIELD-4) | يمثل حقل "User Field 4". |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getName()](#getName--) | اسم الحقل. |
| [toString()](#toString--) | إرجاع سلسلة تمثل الكائن الحالي. |
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


يمثل الحقل "Anniversary".

### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


يمثل الحقل "Attachments".

### BCC {#BCC}
```
public static final Field BCC
```


يمثل الحقل "Bcc".

### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


يمثل الحقل "Birthday".

### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


يمثل الحقل "Business".

### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


يمثل الحقل "Business Address".

### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


يمثل الحقل "Business Fax".

### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


يمثل الحقل "BusinessHomepage".

### CC {#CC}
```
public static final Field CC
```


يمثل الحقل "Cc".

### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


يمثل الحقل "Company".

### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


يمثل الحقل "Department".

### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


يمثل الحقل "Email".

### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


يمثل الحقل "Email Display As".

### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


يمثل الحقل "Email2".

### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


يمثل الحقل "Email2 Display As".

### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


يمثل الحقل "Email3".

### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


يمثل الحقل "Email3 Display As".

### END {#END}
```
public static final Field END
```


يمثل الحقل "End".

### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


يمثل الحقل "First Name".

### FROM {#FROM}
```
public static final Field FROM
```


يمثل الحقل "From".

### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


يمثل الحقل "Full Name".

### GENDER {#GENDER}
```
public static final Field GENDER
```


يمثل الحقل "Gender".

### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


يمثل الحقل "Hobbies".

### HOME {#HOME}
```
public static final Field HOME
```


يمثل الحقل "Home".

### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


يمثل حقل "Home Address".

### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


يمثل حقل "Importance".

### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


يمثل حقل "Job Title".

### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


يمثل حقل "Last Name".

### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


يمثل حقل "Location".

### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


يمثل حقل "Middle Name".

### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


يمثل حقل "Mobile".

### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


يمثل حقل "Organizer".

### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


يمثل حقل "Other Address".

### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


يمثل حقل "Personal Homepage".

### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


يمثل حقل "Profession".

### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


يمثل حقل "Recurrence".

### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


يمثل حقل "Recurrence Pattern".

### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


يمثل حقل "Required Attendees".

### SENT {#SENT}
```
public static final Field SENT
```


يمثل حقل "Sent".

### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


يمثل حقل "Show Time As".

### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


يمثل حقل "Spouse/Partner".

### START {#START}
```
public static final Field START
```


يمثل حقل "Start".

### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


يمثل حقل "Subject".

### TO {#TO}
```
public static final Field TO
```


يمثل حقل "To".

### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


يمثل حقل "User Field 1".

### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


يمثل حقل "User Field 2".

### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


يمثل حقل "User Field 3".

### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


يمثل حقل "User Field 4".

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
| الاسم | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


اسم الحقل.

هذه الطريقة تسترجع اسم الحقل.

**Returns:**
java.lang.String - اسم الحقل.
### toString() {#toString--}
```
public String toString()
```


إرجاع سلسلة تمثل الكائن الحالي.

**Returns:**
java.lang.String - سلسلة تمثل الكائن الحالي.
