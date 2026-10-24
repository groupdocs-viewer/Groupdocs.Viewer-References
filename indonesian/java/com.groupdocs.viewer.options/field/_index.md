---
title: "Bidang"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Mewakili bidang pesan email e46g46 From To Subject dll."
type: docs
weight: 40
url: /id/java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

Mewakili bidang pesan email seperti Dari, Kepada, Subjek, dll.


Enum Field mewakili bidang pesan email umum dalam komponen GroupDocs.Viewer.
Ini menyediakan sekumpulan bidang yang telah ditentukan sebelumnya yang dapat digunakan untuk mengidentifikasi dan mengakses spesifik
informasi dalam pesan email, seperti pengirim, penerima, subjek, dan lainnya.


Untuk detail, lihat [dokumentasi](../https://docs.groupdocs.com/viewer/java/render-email-messages/#rename-fields-in-the-message-header).


Contoh penggunaan:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 EmailOptions emailOptions = htmlViewOptions.getEmailOptions();
 emailOptions.getFieldTextMap().put(Field.FROM, "Sender");

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Bidang

| Bidang | Deskripsi |
| --- | --- |
|  | [ANNIVERSARY](#ANNIVERSARY) | Mewakili bidang "Anniversary". |
|
|  | [ATTACHMENTS](#ATTACHMENTS) | Mewakili bidang "Attachments". |
|
|  | [BCC](#BCC) | Mewakili bidang "Bcc". |
|
|  | [BIRTHDAY](#BIRTHDAY) | Mewakili bidang "Birthday". |
|
|  | [BUSINESS](#BUSINESS) | Mewakili bidang "Business". |
|
|  | [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | Mewakili bidang "Business Address". |
|
|  | [BUSINESS_FAX](#BUSINESS-FAX) | Mewakili bidang "Business Fax". |
|
|  | [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | Mewakili bidang "BusinessHomepage". |
|
|  | [CC](#CC) | Mewakili bidang "Cc". |
|
|  | [COMPANY](#COMPANY) | Mewakili bidang "Company". |
|
|  | [DEPARTMENT](#DEPARTMENT) | Mewakili bidang "Department". |
|
|  | [EMAIL](#EMAIL) | Mewakili bidang "Email". |
|
|  | [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | Mewakili bidang "Email Display As". |
|
|  | [EMAIL_2](#EMAIL-2) | Mewakili bidang "Email2". |
|
|  | [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | Mewakili bidang "Email2 Display As". |
|
|  | [EMAIL_3](#EMAIL-3) | Mewakili bidang "Email3". |
|
|  | [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | Mewakili bidang "Email3 Display As". |
|
|  | [END](#END) | Mewakili bidang "End". |
|
|  | [FIRST_NAME](#FIRST-NAME) | Mewakili bidang "First Name". |
|
|  | [FROM](#FROM) | Mewakili bidang "From". |
|
|  | [FULL_NAME](#FULL-NAME) | Mewakili bidang "Full Name". |
|
|  | [GENDER](#GENDER) | Mewakili bidang "Gender". |
|
|  | [HOBBIES](#HOBBIES) | Mewakili bidang "Hobbies". |
|
|  | [HOME](#HOME) | Mewakili bidang "Home". |
|
|  | [HOME_ADDRESS](#HOME-ADDRESS) | Mewakili bidang "Home Address". |
|
|  | [IMPORTANCE](#IMPORTANCE) | Mewakili bidang "Importance". |
|
|  | [JOB_TITLE](#JOB-TITLE) | Mewakili bidang "Job Title". |
|
|  | [LAST_NAME](#LAST-NAME) | Mewakili bidang "Last Name". |
|
|  | [LOCATION](#LOCATION) | Mewakili bidang "Location". |
|
|  | [MIDDLE_NAME](#MIDDLE-NAME) | Mewakili bidang "Middle Name". |
|
|  | [MOBILE](#MOBILE) | Mewakili bidang "Mobile". |
|
|  | [ORGANIZER](#ORGANIZER) | Mewakili bidang "Organizer". |
|
|  | [OTHER_ADDRESS](#OTHER-ADDRESS) | Mewakili bidang "Other Address". |
|
|  | [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | Mewakili bidang "Personal Homepage". |
|
|  | [PROFESSION](#PROFESSION) | Mewakili bidang "Profession". |
|
|  | [RECURRENCE](#RECURRENCE) | Mewakili bidang "Recurrence". |
|
|  | [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | Mewakili bidang "Recurrence Pattern". |
|
|  | [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | Mewakili bidang "Required Attendees". |
|
|  | [SENT](#SENT) | Mewakili bidang "Sent". |
|
|  | [SHOW_TIME_AS](#SHOW-TIME-AS) | Mewakili bidang "Show Time As". |
|
|  | [SPOUSE_PARTNER](#SPOUSE-PARTNER) | Mewakili bidang "Spouse/Partner". |
|
|  | [START](#START) | Mewakili bidang "Start". |
|
|  | [SUBJECT](#SUBJECT) | Mewakili bidang "Subject". |
|
|  | [TO](#TO) | Mewakili bidang "To". |
|
|  | [USER_FIELD_1](#USER-FIELD-1) | Mewakili bidang "User Field 1". |
|
|  | [USER_FIELD_2](#USER-FIELD-2) | Mewakili bidang "User Field 2". |
|
|  | [USER_FIELD_3](#USER-FIELD-3) | Mewakili bidang "User Field 3". |
|
|  | [USER_FIELD_4](#USER-FIELD-4) | Mewakili bidang "User Field 4". |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getName()](#getName--) | Nama bidang. |
|
|  | [toString()](#toString--) | Mengembalikan string yang mewakili objek saat ini. |
|
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


Mewakili bidang "Home Address".


### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


Mewakili bidang "Importance".


### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


Mewakili bidang "Job Title".


### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


Mewakili bidang "Last Name".


### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


Mewakili bidang "Location".


### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


Mewakili bidang "Middle Name".


### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


Mewakili bidang "Mobile".


### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


Mewakili bidang "Organizer".


### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


Mewakili bidang "Other Address".


### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


Mewakili bidang "Personal Homepage".


### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


Mewakili bidang "Profession".


### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


Mewakili bidang "Recurrence".


### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


Mewakili bidang "Recurrence Pattern".


### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


Mewakili bidang "Required Attendees".


### SENT {#SENT}
```
public static final Field SENT
```


Mewakili bidang "Sent".


### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


Mewakili bidang "Show Time As".


### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


Mewakili bidang "Spouse/Partner".


### START {#START}
```
public static final Field START
```


Mewakili bidang "Start".


### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


Mewakili bidang "Subject".


### TO {#TO}
```
public static final Field TO
```


Mewakili bidang "To".


### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


Mewakili bidang "User Field 1".


### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


Mewakili bidang "User Field 2".


### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


Mewakili bidang "User Field 3".


### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


Mewakili bidang "User Field 4".


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

