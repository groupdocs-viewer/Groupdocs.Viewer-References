---
title: Field
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Represents email message fields e46g46 From To Subject etc.
type: docs
weight: 37
url: /nodejs-java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

Represents email message fields e.g. From, To, Subject etc.

The Field enum represents common email message fields in the GroupDocs.Viewer component. It provides a set of predefined fields that can be used to identify and access specific information in email messages, such as the sender, recipient, subject, and more.

Example usage:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 EmailOptions emailOptions = htmlViewOptions.getEmailOptions();
 emailOptions.getFieldTextMap().put(Field.FROM, "Sender");

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Fields

| Field | Description |
| --- | --- |
| [ANNIVERSARY](#ANNIVERSARY) | Represents the "Anniversary" field. |
| [ATTACHMENTS](#ATTACHMENTS) | Represents the "Attachments" field. |
| [BCC](#BCC) | Represents the "Bcc" field. |
| [BIRTHDAY](#BIRTHDAY) | Represents the "Birthday" field. |
| [BUSINESS](#BUSINESS) | Represents the "Business" field. |
| [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | Represents the "Business Address" field. |
| [BUSINESS_FAX](#BUSINESS-FAX) | Represents the "Business Fax" field. |
| [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | Represents the "BusinessHomepage" field. |
| [CC](#CC) | Represents the "Cc" field. |
| [COMPANY](#COMPANY) | Represents the "Company" field. |
| [DEPARTMENT](#DEPARTMENT) | Represents the "Department" field. |
| [EMAIL](#EMAIL) | Represents the "Email" field. |
| [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | Represents the "Email Display As" field. |
| [EMAIL_2](#EMAIL-2) | Represents the "Email2" field. |
| [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | Represents the "Email2 Display As" field. |
| [EMAIL_3](#EMAIL-3) | Represents the "Email3" field. |
| [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | Represents the "Email3 Display As" field. |
| [END](#END) | Represents the "End" field. |
| [FIRST_NAME](#FIRST-NAME) | Represents the "First Name" field. |
| [FROM](#FROM) | Represents the "From" field. |
| [FULL_NAME](#FULL-NAME) | Represents the "Full Name" field. |
| [GENDER](#GENDER) | Represents the "Gender" field. |
| [HOBBIES](#HOBBIES) | Represents the "Hobbies" field. |
| [HOME](#HOME) | Represents the "Home" field. |
| [HOME_ADDRESS](#HOME-ADDRESS) | Represents the "Home Address" field. |
| [IMPORTANCE](#IMPORTANCE) | Represents the "Importance" field. |
| [JOB_TITLE](#JOB-TITLE) | Represents the "Job Title" field. |
| [LAST_NAME](#LAST-NAME) | Represents the "Last Name" field. |
| [LOCATION](#LOCATION) | Represents the "Location" field. |
| [MIDDLE_NAME](#MIDDLE-NAME) | Represents the "Middle Name" field. |
| [MOBILE](#MOBILE) | Represents the "Mobile" field. |
| [ORGANIZER](#ORGANIZER) | Represents the "Organizer" field. |
| [OTHER_ADDRESS](#OTHER-ADDRESS) | Represents the "Other Address" field. |
| [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | Represents the "Personal Homepage" field. |
| [PROFESSION](#PROFESSION) | Represents the "Profession" field. |
| [RECURRENCE](#RECURRENCE) | Represents the "Recurrence" field. |
| [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | Represents the "Recurrence Pattern" field. |
| [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | Represents the "Required Attendees" field. |
| [SENT](#SENT) | Represents the "Sent" field. |
| [SHOW_TIME_AS](#SHOW-TIME-AS) | Represents the "Show Time As" field. |
| [SPOUSE_PARTNER](#SPOUSE-PARTNER) | Represents the "Spouse/Partner" field. |
| [START](#START) | Represents the "Start" field. |
| [SUBJECT](#SUBJECT) | Represents the "Subject" field. |
| [TO](#TO) | Represents the "To" field. |
| [USER_FIELD_1](#USER-FIELD-1) | Represents the "User Field 1" field. |
| [USER_FIELD_2](#USER-FIELD-2) | Represents the "User Field 2" field. |
| [USER_FIELD_3](#USER-FIELD-3) | Represents the "User Field 3" field. |
| [USER_FIELD_4](#USER-FIELD-4) | Represents the "User Field 4" field. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getName()](#getName--) | Field name. |
| [toString()](#toString--) | Returns a string that represents the current object. |
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


Represents the "Anniversary" field.

### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


Represents the "Attachments" field.

### BCC {#BCC}
```
public static final Field BCC
```


Represents the "Bcc" field.

### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


Represents the "Birthday" field.

### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


Represents the "Business" field.

### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


Represents the "Business Address" field.

### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


Represents the "Business Fax" field.

### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


Represents the "BusinessHomepage" field.

### CC {#CC}
```
public static final Field CC
```


Represents the "Cc" field.

### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


Represents the "Company" field.

### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


Represents the "Department" field.

### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


Represents the "Email" field.

### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


Represents the "Email Display As" field.

### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


Represents the "Email2" field.

### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


Represents the "Email2 Display As" field.

### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


Represents the "Email3" field.

### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


Represents the "Email3 Display As" field.

### END {#END}
```
public static final Field END
```


Represents the "End" field.

### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


Represents the "First Name" field.

### FROM {#FROM}
```
public static final Field FROM
```


Represents the "From" field.

### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


Represents the "Full Name" field.

### GENDER {#GENDER}
```
public static final Field GENDER
```


Represents the "Gender" field.

### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


Represents the "Hobbies" field.

### HOME {#HOME}
```
public static final Field HOME
```


Represents the "Home" field.

### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


Represents the "Home Address" field.

### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


Represents the "Importance" field.

### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


Represents the "Job Title" field.

### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


Represents the "Last Name" field.

### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


Represents the "Location" field.

### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


Represents the "Middle Name" field.

### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


Represents the "Mobile" field.

### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


Represents the "Organizer" field.

### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


Represents the "Other Address" field.

### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


Represents the "Personal Homepage" field.

### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


Represents the "Profession" field.

### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


Represents the "Recurrence" field.

### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


Represents the "Recurrence Pattern" field.

### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


Represents the "Required Attendees" field.

### SENT {#SENT}
```
public static final Field SENT
```


Represents the "Sent" field.

### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


Represents the "Show Time As" field.

### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


Represents the "Spouse/Partner" field.

### START {#START}
```
public static final Field START
```


Represents the "Start" field.

### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


Represents the "Subject" field.

### TO {#TO}
```
public static final Field TO
```


Represents the "To" field.

### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


Represents the "User Field 1" field.

### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


Represents the "User Field 2" field.

### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


Represents the "User Field 3" field.

### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


Represents the "User Field 4" field.

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
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


Field name.

This method retrieves the name of the field.

**Returns:**
java.lang.String - the name of the field.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - a string that represents the current object.
