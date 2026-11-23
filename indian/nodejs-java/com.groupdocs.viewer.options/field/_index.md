---
title: "फ़ील्ड"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "ईमेल संदेश फ़ील्ड जैसे From, To, Subject आदि को दर्शाता है।"
type: docs
weight: 40
url: /hi/nodejs-java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

ईमेल संदेश फ़ील्ड्स जैसे From, To, Subject आदि का प्रतिनिधित्व करता है।

Field enum समूहDocs.Viewer घटक में सामान्य ईमेल संदेश फ़ील्ड का प्रतिनिधित्व करता है। यह पूर्वनिर्धारित फ़ील्ड का एक सेट प्रदान करता है जिसका उपयोग ईमेल संदेशों में विशिष्ट जानकारी, जैसे प्रेषक, प्राप्तकर्ता, विषय, आदि की पहचान और पहुँच के लिए किया जा सकता है।

विवरण के लिए, देखें [documentation][].

उदाहरण उपयोग:

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
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ANNIVERSARY](#ANNIVERSARY) | "Anniversary" फ़ील्ड का प्रतिनिधित्व करता है। |
| [ATTACHMENTS](#ATTACHMENTS) | "Attachments" फ़ील्ड का प्रतिनिधित्व करता है। |
| [BCC](#BCC) | "Bcc" फ़ील्ड का प्रतिनिधित्व करता है। |
| [BIRTHDAY](#BIRTHDAY) | "Birthday" फ़ील्ड का प्रतिनिधित्व करता है। |
| [BUSINESS](#BUSINESS) | "Business" फ़ील्ड का प्रतिनिधित्व करता है। |
| [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | "Business Address" फ़ील्ड का प्रतिनिधित्व करता है। |
| [BUSINESS_FAX](#BUSINESS-FAX) | "Business Fax" फ़ील्ड का प्रतिनिधित्व करता है। |
| [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | "BusinessHomepage" फ़ील्ड का प्रतिनिधित्व करता है। |
| [CC](#CC) | "Cc" फ़ील्ड का प्रतिनिधित्व करता है। |
| [COMPANY](#COMPANY) | "Company" फ़ील्ड का प्रतिनिधित्व करता है। |
| [DEPARTMENT](#DEPARTMENT) | "Department" फ़ील्ड का प्रतिनिधित्व करता है। |
| [EMAIL](#EMAIL) | "Email" फ़ील्ड का प्रतिनिधित्व करता है। |
| [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | "Email Display As" फ़ील्ड का प्रतिनिधित्व करता है। |
| [EMAIL_2](#EMAIL-2) | "Email2" फ़ील्ड का प्रतिनिधित्व करता है। |
| [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | "Email2 Display As" फ़ील्ड का प्रतिनिधित्व करता है। |
| [EMAIL_3](#EMAIL-3) | "Email3" फ़ील्ड का प्रतिनिधित्व करता है। |
| [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | "Email3 Display As" फ़ील्ड का प्रतिनिधित्व करता है। |
| [END](#END) | "End" फ़ील्ड का प्रतिनिधित्व करता है। |
| [FIRST_NAME](#FIRST-NAME) | "First Name" फ़ील्ड का प्रतिनिधित्व करता है। |
| [FROM](#FROM) | "From" फ़ील्ड का प्रतिनिधित्व करता है। |
| [FULL_NAME](#FULL-NAME) | "Full Name" फ़ील्ड का प्रतिनिधित्व करता है। |
| [GENDER](#GENDER) | "Gender" फ़ील्ड का प्रतिनिधित्व करता है। |
| [HOBBIES](#HOBBIES) | "Hobbies" फ़ील्ड का प्रतिनिधित्व करता है। |
| [HOME](#HOME) | "Home" फ़ील्ड का प्रतिनिधित्व करता है। |
| [HOME_ADDRESS](#HOME-ADDRESS) | "Home Address" फ़ील्ड का प्रतिनिधित्व करता है। |
| [IMPORTANCE](#IMPORTANCE) | "Importance" फ़ील्ड का प्रतिनिधित्व करता है। |
| [JOB_TITLE](#JOB-TITLE) | "Job Title" फ़ील्ड का प्रतिनिधित्व करता है। |
| [LAST_NAME](#LAST-NAME) | "Last Name" फ़ील्ड का प्रतिनिधित्व करता है। |
| [LOCATION](#LOCATION) | "Location" फ़ील्ड का प्रतिनिधित्व करता है। |
| [MIDDLE_NAME](#MIDDLE-NAME) | "Middle Name" फ़ील्ड का प्रतिनिधित्व करता है। |
| [MOBILE](#MOBILE) | "Mobile" फ़ील्ड का प्रतिनिधित्व करता है। |
| [ORGANIZER](#ORGANIZER) | "Organizer" फ़ील्ड का प्रतिनिधित्व करता है। |
| [OTHER_ADDRESS](#OTHER-ADDRESS) | "Other Address" फ़ील्ड का प्रतिनिधित्व करता है। |
| [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | "Personal Homepage" फ़ील्ड का प्रतिनिधित्व करता है। |
| [PROFESSION](#PROFESSION) | "Profession" फ़ील्ड का प्रतिनिधित्व करता है। |
| [RECURRENCE](#RECURRENCE) | "Recurrence" फ़ील्ड का प्रतिनिधित्व करता है। |
| [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | "Recurrence Pattern" फ़ील्ड का प्रतिनिधित्व करता है। |
| [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | "Required Attendees" फ़ील्ड का प्रतिनिधित्व करता है। |
| [SENT](#SENT) | "Sent" फ़ील्ड का प्रतिनिधित्व करता है। |
| [SHOW_TIME_AS](#SHOW-TIME-AS) | "Show Time As" फ़ील्ड का प्रतिनिधित्व करता है। |
| [SPOUSE_PARTNER](#SPOUSE-PARTNER) | "Spouse/Partner" फ़ील्ड का प्रतिनिधित्व करता है। |
| [START](#START) | "Start" फ़ील्ड का प्रतिनिधित्व करता है। |
| [SUBJECT](#SUBJECT) | "Subject" फ़ील्ड का प्रतिनिधित्व करता है। |
| [TO](#TO) | "To" फ़ील्ड का प्रतिनिधित्व करता है। |
| [USER_FIELD_1](#USER-FIELD-1) | "User Field 1" फ़ील्ड का प्रतिनिधित्व करता है। |
| [USER_FIELD_2](#USER-FIELD-2) | "User Field 2" फ़ील्ड का प्रतिनिधित्व करता है। |
| [USER_FIELD_3](#USER-FIELD-3) | "User Field 3" फ़ील्ड का प्रतिनिधित्व करता है। |
| [USER_FIELD_4](#USER-FIELD-4) | "User Field 4" फ़ील्ड का प्रतिनिधित्व करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getName()](#getName--) | फ़ील्ड नाम। |
| [toString()](#toString--) | वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


"Anniversary" फ़ील्ड का प्रतिनिधित्व करता है।

### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


"Attachments" फ़ील्ड का प्रतिनिधित्व करता है।

### BCC {#BCC}
```
public static final Field BCC
```


"Bcc" फ़ील्ड का प्रतिनिधित्व करता है।

### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


"Birthday" फ़ील्ड का प्रतिनिधित्व करता है।

### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


"Business" फ़ील्ड का प्रतिनिधित्व करता है।

### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


"Business Address" फ़ील्ड का प्रतिनिधित्व करता है।

### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


"Business Fax" फ़ील्ड का प्रतिनिधित्व करता है।

### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


"BusinessHomepage" फ़ील्ड का प्रतिनिधित्व करता है।

### CC {#CC}
```
public static final Field CC
```


"Cc" फ़ील्ड का प्रतिनिधित्व करता है।

### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


"Company" फ़ील्ड का प्रतिनिधित्व करता है।

### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


"Department" फ़ील्ड का प्रतिनिधित्व करता है।

### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


"Email" फ़ील्ड का प्रतिनिधित्व करता है।

### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


"Email Display As" फ़ील्ड का प्रतिनिधित्व करता है।

### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


"Email2" फ़ील्ड का प्रतिनिधित्व करता है।

### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


"Email2 Display As" फ़ील्ड का प्रतिनिधित्व करता है।

### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


"Email3" फ़ील्ड का प्रतिनिधित्व करता है।

### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


"Email3 Display As" फ़ील्ड का प्रतिनिधित्व करता है।

### END {#END}
```
public static final Field END
```


"End" फ़ील्ड का प्रतिनिधित्व करता है।

### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


"First Name" फ़ील्ड का प्रतिनिधित्व करता है।

### FROM {#FROM}
```
public static final Field FROM
```


"From" फ़ील्ड का प्रतिनिधित्व करता है।

### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


"Full Name" फ़ील्ड का प्रतिनिधित्व करता है।

### GENDER {#GENDER}
```
public static final Field GENDER
```


"Gender" फ़ील्ड का प्रतिनिधित्व करता है।

### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


"Hobbies" फ़ील्ड का प्रतिनिधित्व करता है।

### HOME {#HOME}
```
public static final Field HOME
```


"Home" फ़ील्ड का प्रतिनिधित्व करता है।

### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


"Home Address" फ़ील्ड का प्रतिनिधित्व करता है।

### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


"Importance" फ़ील्ड का प्रतिनिधित्व करता है।

### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


"Job Title" फ़ील्ड का प्रतिनिधित्व करता है।

### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


"Last Name" फ़ील्ड का प्रतिनिधित्व करता है।

### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


"Location" फ़ील्ड का प्रतिनिधित्व करता है।

### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


"Middle Name" फ़ील्ड का प्रतिनिधित्व करता है।

### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


"Mobile" फ़ील्ड का प्रतिनिधित्व करता है।

### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


"Organizer" फ़ील्ड का प्रतिनिधित्व करता है।

### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


"Other Address" फ़ील्ड का प्रतिनिधित्व करता है।

### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


"Personal Homepage" फ़ील्ड का प्रतिनिधित्व करता है।

### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


"Profession" फ़ील्ड का प्रतिनिधित्व करता है।

### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


"Recurrence" फ़ील्ड का प्रतिनिधित्व करता है।

### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


"Recurrence Pattern" फ़ील्ड का प्रतिनिधित्व करता है।

### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


"Required Attendees" फ़ील्ड का प्रतिनिधित्व करता है।

### SENT {#SENT}
```
public static final Field SENT
```


"Sent" फ़ील्ड का प्रतिनिधित्व करता है।

### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


"Show Time As" फ़ील्ड का प्रतिनिधित्व करता है।

### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


"Spouse/Partner" फ़ील्ड का प्रतिनिधित्व करता है।

### START {#START}
```
public static final Field START
```


"Start" फ़ील्ड का प्रतिनिधित्व करता है।

### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


"Subject" फ़ील्ड का प्रतिनिधित्व करता है।

### TO {#TO}
```
public static final Field TO
```


"To" फ़ील्ड का प्रतिनिधित्व करता है।

### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


"User Field 1" फ़ील्ड का प्रतिनिधित्व करता है।

### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


"User Field 2" फ़ील्ड का प्रतिनिधित्व करता है।

### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


"User Field 3" फ़ील्ड का प्रतिनिधित्व करता है।

### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


"User Field 4" फ़ील्ड का प्रतिनिधित्व करता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


फ़ील्ड नाम।

यह मेथड फ़ील्ड का नाम प्राप्त करता है।

**Returns:**
java.lang.String - फ़ील्ड का नाम।
### toString() {#toString--}
```
public String toString()
```


वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है।

**Returns:**
java.lang.String - वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करने वाली स्ट्रिंग।
