---
title: "Field"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Αναπαριστά τα πεδία μηνύματος email όπως e46g46 From To Subject κ.λπ."
type: docs
weight: 40
url: /el/nodejs-java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

Αναπαριστά τα πεδία μηνύματος email π.χ. Από, Προς, Θέμα κ.λπ.

Η απαρίθμηση Field αντιπροσωπεύει τα κοινά πεδία μηνυμάτων ηλεκτρονικού ταχυδρομείου στο στοιχείο GroupDocs.Viewer. Παρέχει ένα σύνολο προεπιλεγμένων πεδίων που μπορούν να χρησιμοποιηθούν για την ταυτοποίηση και πρόσβαση σε συγκεκριμένες πληροφορίες στα μηνύματα ηλεκτρονικού ταχυδρομείου, όπως ο αποστολέας, ο παραλήπτης, το θέμα και άλλα.

Για λεπτομέρειες, δείτε την [τεκμηρίωση][].

Παράδειγμα χρήσης:

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

| Field | Περιγραφή |
| --- | --- |
| [ANNIVERSARY](#ANNIVERSARY) | Αναπαριστά το πεδίο "Anniversary". |
| [ATTACHMENTS](#ATTACHMENTS) | Αναπαριστά το πεδίο "Attachments". |
| [BCC](#BCC) | Αναπαριστά το πεδίο "Bcc". |
| [BIRTHDAY](#BIRTHDAY) | Αναπαριστά το πεδίο "Birthday". |
| [BUSINESS](#BUSINESS) | Αναπαριστά το πεδίο "Business". |
| [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | Αναπαριστά το πεδίο "Business Address". |
| [BUSINESS_FAX](#BUSINESS-FAX) | Αναπαριστά το πεδίο "Business Fax". |
| [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | Αναπαριστά το πεδίο "BusinessHomepage". |
| [CC](#CC) | Αναπαριστά το πεδίο "Cc". |
| [COMPANY](#COMPANY) | Αναπαριστά το πεδίο "Company". |
| [DEPARTMENT](#DEPARTMENT) | Αναπαριστά το πεδίο "Department". |
| [EMAIL](#EMAIL) | Αναπαριστά το πεδίο "Email". |
| [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | Αναπαριστά το πεδίο "Email Display As". |
| [EMAIL_2](#EMAIL-2) | Αναπαριστά το πεδίο "Email2". |
| [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | Αναπαριστά το πεδίο "Email2 Display As". |
| [EMAIL_3](#EMAIL-3) | Αναπαριστά το πεδίο "Email3". |
| [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | Αναπαριστά το πεδίο "Email3 Display As". |
| [END](#END) | Αναπαριστά το πεδίο "End". |
| [FIRST_NAME](#FIRST-NAME) | Αναπαριστά το πεδίο "First Name". |
| [FROM](#FROM) | Αναπαριστά το πεδίο "From". |
| [FULL_NAME](#FULL-NAME) | Αναπαριστά το πεδίο "Full Name". |
| [GENDER](#GENDER) | Αναπαριστά το πεδίο "Gender". |
| [HOBBIES](#HOBBIES) | Αναπαριστά το πεδίο "Hobbies". |
| [HOME](#HOME) | Αναπαριστά το πεδίο "Home". |
| [HOME_ADDRESS](#HOME-ADDRESS) | Αντιπροσωπεύει το "Home Address" πεδίο. |
| [IMPORTANCE](#IMPORTANCE) | Αντιπροσωπεύει το "Importance" πεδίο. |
| [JOB_TITLE](#JOB-TITLE) | Αντιπροσωπεύει το "Job Title" πεδίο. |
| [LAST_NAME](#LAST-NAME) | Αντιπροσωπεύει το "Last Name" πεδίο. |
| [LOCATION](#LOCATION) | Αντιπροσωπεύει το "Location" πεδίο. |
| [MIDDLE_NAME](#MIDDLE-NAME) | Αντιπροσωπεύει το "Middle Name" πεδίο. |
| [MOBILE](#MOBILE) | Αντιπροσωπεύει το "Mobile" πεδίο. |
| [ORGANIZER](#ORGANIZER) | Αντιπροσωπεύει το "Organizer" πεδίο. |
| [OTHER_ADDRESS](#OTHER-ADDRESS) | Αντιπροσωπεύει το "Other Address" πεδίο. |
| [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | Αντιπροσωπεύει το "Personal Homepage" πεδίο. |
| [PROFESSION](#PROFESSION) | Αντιπροσωπεύει το "Profession" πεδίο. |
| [RECURRENCE](#RECURRENCE) | Αντιπροσωπεύει το "Recurrence" πεδίο. |
| [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | Αντιπροσωπεύει το "Recurrence Pattern" πεδίο. |
| [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | Αντιπροσωπεύει το "Required Attendees" πεδίο. |
| [SENT](#SENT) | Αντιπροσωπεύει το "Sent" πεδίο. |
| [SHOW_TIME_AS](#SHOW-TIME-AS) | Αντιπροσωπεύει το "Show Time As" πεδίο. |
| [SPOUSE_PARTNER](#SPOUSE-PARTNER) | Αντιπροσωπεύει το "Spouse/Partner" πεδίο. |
| [START](#START) | Αντιπροσωπεύει το "Start" πεδίο. |
| [SUBJECT](#SUBJECT) | Αντιπροσωπεύει το "Subject" πεδίο. |
| [TO](#TO) | Αντιπροσωπεύει το "To" πεδίο. |
| [USER_FIELD_1](#USER-FIELD-1) | Αντιπροσωπεύει το "User Field 1" πεδίο. |
| [USER_FIELD_2](#USER-FIELD-2) | Αντιπροσωπεύει το "User Field 2" πεδίο. |
| [USER_FIELD_3](#USER-FIELD-3) | Αντιπροσωπεύει το "User Field 3" πεδίο. |
| [USER_FIELD_4](#USER-FIELD-4) | Αντιπροσωπεύει το "User Field 4" πεδίο. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getName()](#getName--) | Όνομα πεδίου. |
| [toString()](#toString--) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


Αναπαριστά το πεδίο "Anniversary".

### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


Αναπαριστά το πεδίο "Attachments".

### BCC {#BCC}
```
public static final Field BCC
```


Αναπαριστά το πεδίο "Bcc".

### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


Αναπαριστά το πεδίο "Birthday".

### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


Αναπαριστά το πεδίο "Business".

### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


Αναπαριστά το πεδίο "Business Address".

### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


Αναπαριστά το πεδίο "Business Fax".

### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


Αναπαριστά το πεδίο "BusinessHomepage".

### CC {#CC}
```
public static final Field CC
```


Αναπαριστά το πεδίο "Cc".

### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


Αναπαριστά το πεδίο "Company".

### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


Αναπαριστά το πεδίο "Department".

### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


Αναπαριστά το πεδίο "Email".

### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


Αναπαριστά το πεδίο "Email Display As".

### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


Αναπαριστά το πεδίο "Email2".

### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


Αναπαριστά το πεδίο "Email2 Display As".

### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


Αναπαριστά το πεδίο "Email3".

### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


Αναπαριστά το πεδίο "Email3 Display As".

### END {#END}
```
public static final Field END
```


Αναπαριστά το πεδίο "End".

### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


Αναπαριστά το πεδίο "First Name".

### FROM {#FROM}
```
public static final Field FROM
```


Αναπαριστά το πεδίο "From".

### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


Αναπαριστά το πεδίο "Full Name".

### GENDER {#GENDER}
```
public static final Field GENDER
```


Αναπαριστά το πεδίο "Gender".

### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


Αναπαριστά το πεδίο "Hobbies".

### HOME {#HOME}
```
public static final Field HOME
```


Αναπαριστά το πεδίο "Home".

### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


Αντιπροσωπεύει το "Home Address" πεδίο.

### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


Αντιπροσωπεύει το "Importance" πεδίο.

### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


Αντιπροσωπεύει το "Job Title" πεδίο.

### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


Αντιπροσωπεύει το "Last Name" πεδίο.

### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


Αντιπροσωπεύει το "Location" πεδίο.

### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


Αντιπροσωπεύει το "Middle Name" πεδίο.

### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


Αντιπροσωπεύει το "Mobile" πεδίο.

### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


Αντιπροσωπεύει το "Organizer" πεδίο.

### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


Αντιπροσωπεύει το "Other Address" πεδίο.

### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


Αντιπροσωπεύει το "Personal Homepage" πεδίο.

### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


Αντιπροσωπεύει το "Profession" πεδίο.

### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


Αντιπροσωπεύει το "Recurrence" πεδίο.

### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


Αντιπροσωπεύει το "Recurrence Pattern" πεδίο.

### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


Αντιπροσωπεύει το "Required Attendees" πεδίο.

### SENT {#SENT}
```
public static final Field SENT
```


Αντιπροσωπεύει το "Sent" πεδίο.

### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


Αντιπροσωπεύει το "Show Time As" πεδίο.

### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


Αντιπροσωπεύει το "Spouse/Partner" πεδίο.

### START {#START}
```
public static final Field START
```


Αντιπροσωπεύει το "Start" πεδίο.

### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


Αντιπροσωπεύει το "Subject" πεδίο.

### TO {#TO}
```
public static final Field TO
```


Αντιπροσωπεύει το "To" πεδίο.

### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


Αντιπροσωπεύει το "User Field 1" πεδίο.

### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


Αντιπροσωπεύει το "User Field 2" πεδίο.

### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


Αντιπροσωπεύει το "User Field 3" πεδίο.

### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


Αντιπροσωπεύει το "User Field 4" πεδίο.

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| όνομα | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


Όνομα πεδίου.

Αυτή η μέθοδος ανακτά το όνομα του πεδίου.

**Returns:**
java.lang.String - το όνομα του πεδίου.
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο.

**Returns:**
java.lang.String - μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο.
