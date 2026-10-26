---
title: "Bidang"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Mewakili bidang pesan email e46g46 From To Subject dll."
type: docs
weight: 40
url: /id/nodejs-java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

Mewakili bidang pesan email mis. Dari, Ke, Subjek, dll.

Enum Field mewakili bidang pesan email umum dalam komponen GroupDocs.Viewer. Ini menyediakan sekumpulan bidang yang telah ditentukan sebelumnya yang dapat digunakan untuk mengidentifikasi dan mengakses informasi spesifik dalam pesan email, seperti pengirim, penerima, subjek, dan lainnya.

Untuk detail, lihat [dokumentasi][].

Contoh penggunaan:

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
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [ANNIVERSARY](#ANNIVERSARY) | Mewakili bidang "Anniversary". |
| [ATTACHMENTS](#ATTACHMENTS) | Mewakili bidang "Attachments". |
| [BCC](#BCC) | Mewakili bidang "Bcc". |
| [BIRTHDAY](#BIRTHDAY) | Mewakili bidang "Birthday". |
| [BUSINESS](#BUSINESS) | Mewakili bidang "Business". |
| [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | Mewakili bidang "Business Address". |
| [BUSINESS_FAX](#BUSINESS-FAX) | Mewakili bidang "Business Fax". |
| [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | Mewakili bidang "BusinessHomepage". |
| [CC](#CC) | Mewakili bidang "Cc". |
| [COMPANY](#COMPANY) | Mewakili bidang "Company". |
| [DEPARTMENT](#DEPARTMENT) | Mewakili bidang "Department". |
| [EMAIL](#EMAIL) | Mewakili bidang "Email". |
| [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | Mewakili bidang "Email Display As". |
| [EMAIL_2](#EMAIL-2) | Mewakili bidang "Email2". |
| [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | Mewakili bidang "Email2 Display As". |
| [EMAIL_3](#EMAIL-3) | Mewakili bidang "Email3". |
| [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | Mewakili bidang "Email3 Display As". |
| [END](#END) | Mewakili bidang "End". |
| [FIRST_NAME](#FIRST-NAME) | Mewakili bidang "First Name". |
| [FROM](#FROM) | Mewakili bidang "From". |
| [FULL_NAME](#FULL-NAME) | Mewakili bidang "Full Name". |
| [GENDER](#GENDER) | Mewakili bidang "Gender". |
| [HOBBIES](#HOBBIES) | Mewakili bidang "Hobbies". |
| [HOME](#HOME) | Mewakili bidang "Home". |
| [HOME_ADDRESS](#HOME-ADDRESS) | Mewakili "Home Address" field. |
| [IMPORTANCE](#IMPORTANCE) | Mewakili "Importance" field. |
| [JOB_TITLE](#JOB-TITLE) | Mewakili "Job Title" field. |
| [LAST_NAME](#LAST-NAME) | Mewakili "Last Name" field. |
| [LOCATION](#LOCATION) | Mewakili "Location" field. |
| [MIDDLE_NAME](#MIDDLE-NAME) | Mewakili "Middle Name" field. |
| [MOBILE](#MOBILE) | Mewakili "Mobile" field. |
| [ORGANIZER](#ORGANIZER) | Mewakili "Organizer" field. |
| [OTHER_ADDRESS](#OTHER-ADDRESS) | Mewakili "Other Address" field. |
| [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | Mewakili "Personal Homepage" field. |
| [PROFESSION](#PROFESSION) | Mewakili "Profession" field. |
| [RECURRENCE](#RECURRENCE) | Mewakili "Recurrence" field. |
| [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | Mewakili "Recurrence Pattern" field. |
| [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | Mewakili "Required Attendees" field. |
| [SENT](#SENT) | Mewakili "Sent" field. |
| [SHOW_TIME_AS](#SHOW-TIME-AS) | Mewakili "Show Time As" field. |
| [SPOUSE_PARTNER](#SPOUSE-PARTNER) | Mewakili "Spouse/Partner" field. |
| [START](#START) | Mewakili "Start" field. |
| [SUBJECT](#SUBJECT) | Mewakili "Subject" field. |
| [TO](#TO) | Mewakili "To" field. |
| [USER_FIELD_1](#USER-FIELD-1) | Mewakili "User Field 1" field. |
| [USER_FIELD_2](#USER-FIELD-2) | Mewakili "User Field 2" field. |
| [USER_FIELD_3](#USER-FIELD-3) | Mewakili "User Field 3" field. |
| [USER_FIELD_4](#USER-FIELD-4) | Mewakili "User Field 4" field. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getName()](#getName--) | Nama bidang. |
| [toString()](#toString--) | Mengembalikan string yang mewakili objek saat ini. |
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


Mewakili bidang "Anniversary".

### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


Mewakili bidang "Attachments".

### BCC {#BCC}
```
public static final Field BCC
```


Mewakili bidang "Bcc".

### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


Mewakili bidang "Birthday".

### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


Mewakili bidang "Business".

### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


Mewakili bidang "Business Address".

### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


Mewakili bidang "Business Fax".

### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


Mewakili bidang "BusinessHomepage".

### CC {#CC}
```
public static final Field CC
```


Mewakili bidang "Cc".

### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


Mewakili bidang "Company".

### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


Mewakili bidang "Department".

### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


Mewakili bidang "Email".

### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


Mewakili bidang "Email Display As".

### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


Mewakili bidang "Email2".

### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


Mewakili bidang "Email2 Display As".

### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


Mewakili bidang "Email3".

### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


Mewakili bidang "Email3 Display As".

### END {#END}
```
public static final Field END
```


Mewakili bidang "End".

### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


Mewakili bidang "First Name".

### FROM {#FROM}
```
public static final Field FROM
```


Mewakili bidang "From".

### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


Mewakili bidang "Full Name".

### GENDER {#GENDER}
```
public static final Field GENDER
```


Mewakili bidang "Gender".

### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


Mewakili bidang "Hobbies".

### HOME {#HOME}
```
public static final Field HOME
```


Mewakili bidang "Home".

### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


Mewakili "Home Address" field.

### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


Mewakili "Importance" field.

### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


Mewakili "Job Title" field.

### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


Mewakili "Last Name" field.

### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


Mewakili "Location" field.

### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


Mewakili "Middle Name" field.

### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


Mewakili "Mobile" field.

### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


Mewakili "Organizer" field.

### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


Mewakili "Other Address" field.

### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


Mewakili "Personal Homepage" field.

### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


Mewakili "Profession" field.

### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


Mewakili "Recurrence" field.

### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


Mewakili "Recurrence Pattern" field.

### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


Mewakili "Required Attendees" field.

### SENT {#SENT}
```
public static final Field SENT
```


Mewakili "Sent" field.

### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


Mewakili "Show Time As" field.

### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


Mewakili "Spouse/Partner" field.

### START {#START}
```
public static final Field START
```


Mewakili "Start" field.

### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


Mewakili "Subject" field.

### TO {#TO}
```
public static final Field TO
```


Mewakili "To" field.

### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


Mewakili "User Field 1" field.

### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


Mewakili "User Field 2" field.

### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


Mewakili "User Field 3" field.

### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


Mewakili "User Field 4" field.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nama | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


Nama bidang.

Metode ini mengambil nama bidang.

**Returns:**
java.lang.String - nama bidang.
### toString() {#toString--}
```
public String toString()
```


Mengembalikan string yang mewakili objek saat ini.

**Returns:**
java.lang.String - string yang mewakili objek saat ini.
