---
title: "Field"
second_title: "GroupDocs.Viewer için Node.js üzerinden Java API Referansı"
description: "E-posta mesajı alanlarını temsil eder: e46g46 From To Subject vb."
type: docs
weight: 40
url: /tr/nodejs-java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

E-posta mesajı alanlarını temsil eder, ör. From, To, Subject vb.

Field enum'ı, GroupDocs.Viewer bileşeninde ortak e-posta mesajı alanlarını temsil eder. Gönderici, alıcı, konu ve daha fazlası gibi e-posta mesajlarında belirli bilgileri tanımlamak ve erişmek için kullanılabilecek önceden tanımlanmış bir dizi alan sağlar.

Ayrıntılar için, [documentation][].

Örnek kullanım:

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
## Fields

| Field | Açıklama |
| --- | --- |
| [ANNIVERSARY](#ANNIVERSARY) | "Anniversary" alanını temsil eder. |
| [ATTACHMENTS](#ATTACHMENTS) | "Attachments" alanını temsil eder. |
| [BCC](#BCC) | "Bcc" alanını temsil eder. |
| [BIRTHDAY](#BIRTHDAY) | "Birthday" alanını temsil eder. |
| [BUSINESS](#BUSINESS) | "Business" alanını temsil eder. |
| [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | "Business Address" alanını temsil eder. |
| [BUSINESS_FAX](#BUSINESS-FAX) | "Business Fax" alanını temsil eder. |
| [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | "BusinessHomepage" alanını temsil eder. |
| [CC](#CC) | "Cc" alanını temsil eder. |
| [COMPANY](#COMPANY) | "Company" alanını temsil eder. |
| [DEPARTMENT](#DEPARTMENT) | "Department" alanını temsil eder. |
| [EMAIL](#EMAIL) | "Email" alanını temsil eder. |
| [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | "Email Display As" alanını temsil eder. |
| [EMAIL_2](#EMAIL-2) | "Email2" alanını temsil eder. |
| [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | "Email2 Display As" alanını temsil eder. |
| [EMAIL_3](#EMAIL-3) | "Email3" alanını temsil eder. |
| [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | "Email3 Display As" alanını temsil eder. |
| [END](#END) | "End" alanını temsil eder. |
| [FIRST_NAME](#FIRST-NAME) | "First Name" alanını temsil eder. |
| [FROM](#FROM) | "From" alanını temsil eder. |
| [FULL_NAME](#FULL-NAME) | "Full Name" alanını temsil eder. |
| [GENDER](#GENDER) | "Gender" alanını temsil eder. |
| [HOBBIES](#HOBBIES) | "Hobbies" alanını temsil eder. |
| [HOME](#HOME) | "Home" alanını temsil eder. |
| [HOME_ADDRESS](#HOME-ADDRESS) | "Home Address" alanını temsil eder. |
| [IMPORTANCE](#IMPORTANCE) | "Importance" alanını temsil eder. |
| [JOB_TITLE](#JOB-TITLE) | "Job Title" alanını temsil eder. |
| [LAST_NAME](#LAST-NAME) | "Last Name" alanını temsil eder. |
| [LOCATION](#LOCATION) | "Location" alanını temsil eder. |
| [MIDDLE_NAME](#MIDDLE-NAME) | "Middle Name" alanını temsil eder. |
| [MOBILE](#MOBILE) | "Mobile" alanını temsil eder. |
| [ORGANIZER](#ORGANIZER) | "Organizer" alanını temsil eder. |
| [OTHER_ADDRESS](#OTHER-ADDRESS) | "Other Address" alanını temsil eder. |
| [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | "Personal Homepage" alanını temsil eder. |
| [PROFESSION](#PROFESSION) | "Profession" alanını temsil eder. |
| [RECURRENCE](#RECURRENCE) | "Recurrence" alanını temsil eder. |
| [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | "Recurrence Pattern" alanını temsil eder. |
| [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | "Required Attendees" alanını temsil eder. |
| [SENT](#SENT) | "Sent" alanını temsil eder. |
| [SHOW_TIME_AS](#SHOW-TIME-AS) | "Show Time As" alanını temsil eder. |
| [SPOUSE_PARTNER](#SPOUSE-PARTNER) | "Spouse/Partner" alanını temsil eder. |
| [START](#START) | "Start" alanını temsil eder. |
| [SUBJECT](#SUBJECT) | "Subject" alanını temsil eder. |
| [TO](#TO) | "To" alanını temsil eder. |
| [USER_FIELD_1](#USER-FIELD-1) | "User Field 1" alanını temsil eder. |
| [USER_FIELD_2](#USER-FIELD-2) | "User Field 2" alanını temsil eder. |
| [USER_FIELD_3](#USER-FIELD-3) | "User Field 3" alanını temsil eder. |
| [USER_FIELD_4](#USER-FIELD-4) | "User Field 4" alanını temsil eder. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getName()](#getName--) | Alan adı. |
| [toString()](#toString--) | Geçerli nesneyi temsil eden bir dize döndürür. |
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


"Anniversary" alanını temsil eder.

### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


"Attachments" alanını temsil eder.

### BCC {#BCC}
```
public static final Field BCC
```


"Bcc" alanını temsil eder.

### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


"Birthday" alanını temsil eder.

### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


"Business" alanını temsil eder.

### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


"Business Address" alanını temsil eder.

### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


"Business Fax" alanını temsil eder.

### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


"BusinessHomepage" alanını temsil eder.

### CC {#CC}
```
public static final Field CC
```


"Cc" alanını temsil eder.

### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


"Company" alanını temsil eder.

### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


"Department" alanını temsil eder.

### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


"Email" alanını temsil eder.

### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


"Email Display As" alanını temsil eder.

### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


"Email2" alanını temsil eder.

### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


"Email2 Display As" alanını temsil eder.

### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


"Email3" alanını temsil eder.

### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


"Email3 Display As" alanını temsil eder.

### END {#END}
```
public static final Field END
```


"End" alanını temsil eder.

### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


"First Name" alanını temsil eder.

### FROM {#FROM}
```
public static final Field FROM
```


"From" alanını temsil eder.

### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


"Full Name" alanını temsil eder.

### GENDER {#GENDER}
```
public static final Field GENDER
```


"Gender" alanını temsil eder.

### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


"Hobbies" alanını temsil eder.

### HOME {#HOME}
```
public static final Field HOME
```


"Home" alanını temsil eder.

### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


"Home Address" alanını temsil eder.

### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


"Importance" alanını temsil eder.

### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


"Job Title" alanını temsil eder.

### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


"Last Name" alanını temsil eder.

### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


"Location" alanını temsil eder.

### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


"Middle Name" alanını temsil eder.

### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


"Mobile" alanını temsil eder.

### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


"Organizer" alanını temsil eder.

### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


"Other Address" alanını temsil eder.

### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


"Personal Homepage" alanını temsil eder.

### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


"Profession" alanını temsil eder.

### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


"Recurrence" alanını temsil eder.

### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


"Recurrence Pattern" alanını temsil eder.

### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


"Required Attendees" alanını temsil eder.

### SENT {#SENT}
```
public static final Field SENT
```


"Sent" alanını temsil eder.

### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


"Show Time As" alanını temsil eder.

### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


"Spouse/Partner" alanını temsil eder.

### START {#START}
```
public static final Field START
```


"Start" alanını temsil eder.

### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


"Subject" alanını temsil eder.

### TO {#TO}
```
public static final Field TO
```


"To" alanını temsil eder.

### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


"User Field 1" alanını temsil eder.

### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


"User Field 2" alanını temsil eder.

### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


"User Field 3" alanını temsil eder.

### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


"User Field 4" alanını temsil eder.

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


Alan adı.

Bu yöntem, alanın adını alır.

**Returns:**
java.lang.String - alanın adı.
### toString() {#toString--}
```
public String toString()
```


Geçerli nesneyi temsil eden bir dize döndürür.

**Returns:**
java.lang.String - geçerli nesneyi temsil eden bir dize.
