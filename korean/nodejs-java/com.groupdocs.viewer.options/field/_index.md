---
title: "필드"
second_title: "Node.js용 GroupDocs.Viewer (Java) API 레퍼런스"
description: "이메일 메시지 필드(e46g46 From, To, Subject 등)를 나타냅니다."
type: docs
weight: 40
url: /ko/nodejs-java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

이메일 메시지 필드(예: From, To, Subject 등)를 나타냅니다.

Field 열거형은 GroupDocs.Viewer 구성 요소에서 일반적인 이메일 메시지 필드를 나타냅니다. 이는 발신자, 수신자, 제목 등과 같은 이메일 메시지의 특정 정보를 식별하고 액세스하는 데 사용할 수 있는 미리 정의된 필드 집합을 제공합니다.

자세한 내용은 [documentation][].

예시 사용법:

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
## 필드

| 필드 | 설명 |
| --- | --- |
| [ANNIVERSARY](#ANNIVERSARY) | "Anniversary" 필드를 나타냅니다. |
| [ATTACHMENTS](#ATTACHMENTS) | "Attachments" 필드를 나타냅니다. |
| [BCC](#BCC) | "Bcc" 필드를 나타냅니다. |
| [BIRTHDAY](#BIRTHDAY) | "Birthday" 필드를 나타냅니다. |
| [BUSINESS](#BUSINESS) | "Business" 필드를 나타냅니다. |
| [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | "Business Address" 필드를 나타냅니다. |
| [BUSINESS_FAX](#BUSINESS-FAX) | "Business Fax" 필드를 나타냅니다. |
| [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | "BusinessHomepage" 필드를 나타냅니다. |
| [CC](#CC) | "Cc" 필드를 나타냅니다. |
| [COMPANY](#COMPANY) | "Company" 필드를 나타냅니다. |
| [DEPARTMENT](#DEPARTMENT) | "Department" 필드를 나타냅니다. |
| [EMAIL](#EMAIL) | "Email" 필드를 나타냅니다. |
| [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | "Email Display As" 필드를 나타냅니다. |
| [EMAIL_2](#EMAIL-2) | "Email2" 필드를 나타냅니다. |
| [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | "Email2 Display As" 필드를 나타냅니다. |
| [EMAIL_3](#EMAIL-3) | "Email3" 필드를 나타냅니다. |
| [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | "Email3 Display As" 필드를 나타냅니다. |
| [END](#END) | "End" 필드를 나타냅니다. |
| [FIRST_NAME](#FIRST-NAME) | "First Name" 필드를 나타냅니다. |
| [FROM](#FROM) | "From" 필드를 나타냅니다. |
| [FULL_NAME](#FULL-NAME) | "Full Name" 필드를 나타냅니다. |
| [GENDER](#GENDER) | "Gender" 필드를 나타냅니다. |
| [HOBBIES](#HOBBIES) | "Hobbies" 필드를 나타냅니다. |
| [HOME](#HOME) | "Home" 필드를 나타냅니다. |
| [HOME_ADDRESS](#HOME-ADDRESS) | \"Home Address\" 필드를 나타냅니다. |
| [IMPORTANCE](#IMPORTANCE) | \"Importance\" 필드를 나타냅니다. |
| [JOB_TITLE](#JOB-TITLE) | \"Job Title\" 필드를 나타냅니다. |
| [LAST_NAME](#LAST-NAME) | \"Last Name\" 필드를 나타냅니다. |
| [LOCATION](#LOCATION) | \"Location\" 필드를 나타냅니다. |
| [MIDDLE_NAME](#MIDDLE-NAME) | \"Middle Name\" 필드를 나타냅니다. |
| [MOBILE](#MOBILE) | \"Mobile\" 필드를 나타냅니다. |
| [ORGANIZER](#ORGANIZER) | \"Organizer\" 필드를 나타냅니다. |
| [OTHER_ADDRESS](#OTHER-ADDRESS) | \"Other Address\" 필드를 나타냅니다. |
| [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | \"Personal Homepage\" 필드를 나타냅니다. |
| [PROFESSION](#PROFESSION) | \"Profession\" 필드를 나타냅니다. |
| [RECURRENCE](#RECURRENCE) | \"Recurrence\" 필드를 나타냅니다. |
| [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | \"Recurrence Pattern\" 필드를 나타냅니다. |
| [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | \"Required Attendees\" 필드를 나타냅니다. |
| [SENT](#SENT) | \"Sent\" 필드를 나타냅니다. |
| [SHOW_TIME_AS](#SHOW-TIME-AS) | \"Show Time As\" 필드를 나타냅니다. |
| [SPOUSE_PARTNER](#SPOUSE-PARTNER) | \"Spouse/Partner\" 필드를 나타냅니다. |
| [START](#START) | \"Start\" 필드를 나타냅니다. |
| [SUBJECT](#SUBJECT) | \"Subject\" 필드를 나타냅니다. |
| [TO](#TO) | \"To\" 필드를 나타냅니다. |
| [USER_FIELD_1](#USER-FIELD-1) | \"User Field 1\" 필드를 나타냅니다. |
| [USER_FIELD_2](#USER-FIELD-2) | \"User Field 2\" 필드를 나타냅니다. |
| [USER_FIELD_3](#USER-FIELD-3) | \"User Field 3\" 필드를 나타냅니다. |
| [USER_FIELD_4](#USER-FIELD-4) | \"User Field 4\" 필드를 나타냅니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getName()](#getName--) | 필드 이름. |
| [toString()](#toString--) | 현재 객체를 나타내는 문자열을 반환합니다. |
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


"Anniversary" 필드를 나타냅니다.

### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


"Attachments" 필드를 나타냅니다.

### BCC {#BCC}
```
public static final Field BCC
```


"Bcc" 필드를 나타냅니다.

### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


"Birthday" 필드를 나타냅니다.

### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


"Business" 필드를 나타냅니다.

### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


"Business Address" 필드를 나타냅니다.

### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


"Business Fax" 필드를 나타냅니다.

### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


"BusinessHomepage" 필드를 나타냅니다.

### CC {#CC}
```
public static final Field CC
```


"Cc" 필드를 나타냅니다.

### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


"Company" 필드를 나타냅니다.

### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


"Department" 필드를 나타냅니다.

### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


"Email" 필드를 나타냅니다.

### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


"Email Display As" 필드를 나타냅니다.

### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


"Email2" 필드를 나타냅니다.

### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


"Email2 Display As" 필드를 나타냅니다.

### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


"Email3" 필드를 나타냅니다.

### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


"Email3 Display As" 필드를 나타냅니다.

### END {#END}
```
public static final Field END
```


"End" 필드를 나타냅니다.

### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


"First Name" 필드를 나타냅니다.

### FROM {#FROM}
```
public static final Field FROM
```


"From" 필드를 나타냅니다.

### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


"Full Name" 필드를 나타냅니다.

### GENDER {#GENDER}
```
public static final Field GENDER
```


"Gender" 필드를 나타냅니다.

### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


"Hobbies" 필드를 나타냅니다.

### HOME {#HOME}
```
public static final Field HOME
```


"Home" 필드를 나타냅니다.

### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


\"Home Address\" 필드를 나타냅니다.

### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


\"Importance\" 필드를 나타냅니다.

### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


\"Job Title\" 필드를 나타냅니다.

### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


\"Last Name\" 필드를 나타냅니다.

### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


\"Location\" 필드를 나타냅니다.

### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


\"Middle Name\" 필드를 나타냅니다.

### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


\"Mobile\" 필드를 나타냅니다.

### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


\"Organizer\" 필드를 나타냅니다.

### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


\"Other Address\" 필드를 나타냅니다.

### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


\"Personal Homepage\" 필드를 나타냅니다.

### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


\"Profession\" 필드를 나타냅니다.

### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


\"Recurrence\" 필드를 나타냅니다.

### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


\"Recurrence Pattern\" 필드를 나타냅니다.

### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


\"Required Attendees\" 필드를 나타냅니다.

### SENT {#SENT}
```
public static final Field SENT
```


\"Sent\" 필드를 나타냅니다.

### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


\"Show Time As\" 필드를 나타냅니다.

### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


\"Spouse/Partner\" 필드를 나타냅니다.

### START {#START}
```
public static final Field START
```


\"Start\" 필드를 나타냅니다.

### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


\"Subject\" 필드를 나타냅니다.

### TO {#TO}
```
public static final Field TO
```


\"To\" 필드를 나타냅니다.

### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


\"User Field 1\" 필드를 나타냅니다.

### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


\"User Field 2\" 필드를 나타냅니다.

### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


\"User Field 3\" 필드를 나타냅니다.

### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


\"User Field 4\" 필드를 나타냅니다.

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
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


필드 이름.

이 메서드는 필드의 이름을 가져옵니다.

**Returns:**
java.lang.String - 필드의 이름.
### toString() {#toString--}
```
public String toString()
```


현재 객체를 나타내는 문자열을 반환합니다.

**Returns:**
java.lang.String - 현재 객체를 나타내는 문자열.
