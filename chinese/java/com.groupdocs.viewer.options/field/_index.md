---
title: "字段"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "表示电子邮件消息字段，例如 e46g46、From、To、Subject 等。"
type: docs
weight: 40
url: /zh/java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

表示电子邮件消息字段，例如 From、To、Subject 等。


Field 枚举表示 GroupDocs.Viewer 组件中常见的电子邮件消息字段。
它提供了一组预定义字段，可用于识别和访问特定的
电子邮件消息中的信息，例如发件人、收件人、主题等。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-email-messages/#rename-fields-in-the-message-header)。


示例用法：

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 EmailOptions emailOptions = htmlViewOptions.getEmailOptions();
 emailOptions.getFieldTextMap().put(Field.FROM, "Sender");

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 字段

| 字段 | 描述 |
| --- | --- |
|  | [ANNIVERSARY](#ANNIVERSARY) | 表示 "Anniversary" 字段。 |
|
|  | [ATTACHMENTS](#ATTACHMENTS) | 表示 "Attachments" 字段。 |
|
|  | [BCC](#BCC) | 表示 "Bcc" 字段。 |
|
|  | [BIRTHDAY](#BIRTHDAY) | 表示 "Birthday" 字段。 |
|
|  | [BUSINESS](#BUSINESS) | 表示 "Business" 字段。 |
|
|  | [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | 表示 "Business Address" 字段。 |
|
|  | [BUSINESS_FAX](#BUSINESS-FAX) | 表示 "Business Fax" 字段。 |
|
|  | [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | 表示 "BusinessHomepage" 字段。 |
|
|  | [CC](#CC) | 表示 "Cc" 字段。 |
|
|  | [COMPANY](#COMPANY) | 表示 "Company" 字段。 |
|
|  | [DEPARTMENT](#DEPARTMENT) | 表示 "Department" 字段。 |
|
|  | [EMAIL](#EMAIL) | 表示 "Email" 字段。 |
|
|  | [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | 表示 "Email Display As" 字段。 |
|
|  | [EMAIL_2](#EMAIL-2) | 表示 "Email2" 字段。 |
|
|  | [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | 表示 "Email2 Display As" 字段。 |
|
|  | [EMAIL_3](#EMAIL-3) | 表示 "Email3" 字段。 |
|
|  | [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | 表示 "Email3 Display As" 字段。 |
|
|  | [END](#END) | 表示 "End" 字段。 |
|
|  | [FIRST_NAME](#FIRST-NAME) | 表示 "First Name" 字段。 |
|
|  | [FROM](#FROM) | 表示 "From" 字段。 |
|
|  | [FULL_NAME](#FULL-NAME) | 表示 "Full Name" 字段。 |
|
|  | [GENDER](#GENDER) | 表示 "Gender" 字段。 |
|
|  | [HOBBIES](#HOBBIES) | 表示 "Hobbies" 字段。 |
|
|  | [HOME](#HOME) | 表示 "Home" 字段。 |
|
|  | [HOME_ADDRESS](#HOME-ADDRESS) | 表示 "Home Address" 字段。 |
|
|  | [IMPORTANCE](#IMPORTANCE) | 表示 "Importance" 字段。 |
|
|  | [JOB_TITLE](#JOB-TITLE) | 表示 "Job Title" 字段。 |
|
|  | [LAST_NAME](#LAST-NAME) | 表示 "Last Name" 字段。 |
|
|  | [LOCATION](#LOCATION) | 表示 "Location" 字段。 |
|
|  | [MIDDLE_NAME](#MIDDLE-NAME) | 表示 "Middle Name" 字段。 |
|
|  | [MOBILE](#MOBILE) | 表示 "Mobile" 字段。 |
|
|  | [ORGANIZER](#ORGANIZER) | 表示 "Organizer" 字段。 |
|
|  | [OTHER_ADDRESS](#OTHER-ADDRESS) | 表示 "Other Address" 字段。 |
|
|  | [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | 表示 "Personal Homepage" 字段。 |
|
|  | [PROFESSION](#PROFESSION) | 表示 "Profession" 字段。 |
|
|  | [RECURRENCE](#RECURRENCE) | 表示 "Recurrence" 字段。 |
|
|  | [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | 表示 "Recurrence Pattern" 字段。 |
|
|  | [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | 表示 "Required Attendees" 字段。 |
|
|  | [SENT](#SENT) | 表示 "Sent" 字段。 |
|
|  | [SHOW_TIME_AS](#SHOW-TIME-AS) | 表示 "Show Time As" 字段。 |
|
|  | [SPOUSE_PARTNER](#SPOUSE-PARTNER) | 表示 "Spouse/Partner" 字段。 |
|
|  | [START](#START) | 表示 "Start" 字段。 |
|
|  | [SUBJECT](#SUBJECT) | 表示 "Subject" 字段。 |
|
|  | [TO](#TO) | 表示 "To" 字段。 |
|
|  | [USER_FIELD_1](#USER-FIELD-1) | 表示 "User Field 1" 字段。 |
|
|  | [USER_FIELD_2](#USER-FIELD-2) | 表示 "User Field 2" 字段。 |
|
|  | [USER_FIELD_3](#USER-FIELD-3) | 表示 "User Field 3" 字段。 |
|
|  | [USER_FIELD_4](#USER-FIELD-4) | 表示 "User Field 4" 字段。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
|  | [getName()](#getName--) | 字段名称。 |
|
|  | [toString()](#toString--) | 返回一个表示当前对象的字符串。 |
|
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


表示 "Anniversary" 字段。


### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


表示 "Attachments" 字段。


### BCC {#BCC}
```
public static final Field BCC
```


表示 "Bcc" 字段。


### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


表示 "Birthday" 字段。


### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


表示 "Business" 字段。


### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


表示 "Business Address" 字段。


### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


表示 "Business Fax" 字段。


### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


表示 "BusinessHomepage" 字段。


### CC {#CC}
```
public static final Field CC
```


表示 "Cc" 字段。


### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


表示 "Company" 字段。


### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


表示 "Department" 字段。


### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


表示 "Email" 字段。


### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


表示 "Email Display As" 字段。


### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


表示 "Email2" 字段。


### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


表示 "Email2 Display As" 字段。


### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


表示 "Email3" 字段。


### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


表示 "Email3 Display As" 字段。


### END {#END}
```
public static final Field END
```


表示 "End" 字段。


### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


表示 "First Name" 字段。


### FROM {#FROM}
```
public static final Field FROM
```


表示 "From" 字段。


### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


表示 "Full Name" 字段。


### GENDER {#GENDER}
```
public static final Field GENDER
```


表示 "Gender" 字段。


### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


表示 "Hobbies" 字段。


### HOME {#HOME}
```
public static final Field HOME
```


表示 "Home" 字段。


### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


表示 "Home Address" 字段。


### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


表示 "Importance" 字段。


### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


表示 "Job Title" 字段。


### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


表示 "Last Name" 字段。


### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


表示 "Location" 字段。


### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


表示 "Middle Name" 字段。


### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


表示 "Mobile" 字段。


### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


表示 "Organizer" 字段。


### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


表示 "Other Address" 字段。


### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


表示 "Personal Homepage" 字段。


### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


表示 "Profession" 字段。


### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


表示 "Recurrence" 字段。


### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


表示 "Recurrence Pattern" 字段。


### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


表示 "Required Attendees" 字段。


### SENT {#SENT}
```
public static final Field SENT
```


表示 "Sent" 字段。


### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


表示 "Show Time As" 字段。


### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


表示 "Spouse/Partner" 字段。


### START {#START}
```
public static final Field START
```


表示 "Start" 字段。


### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


表示 "Subject" 字段。


### TO {#TO}
```
public static final Field TO
```


表示 "To" 字段。


### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


表示 "User Field 1" 字段。


### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


表示 "User Field 2" 字段。


### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


表示 "User Field 3" 字段。


### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


表示 "User Field 4" 字段。


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
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


字段名称。


此方法检索字段的名称。


**Returns:**
java.lang.String - 字段的名称。

### toString() {#toString--}
```
public String toString()
```


返回一个表示当前对象的字符串。


**Returns:**
java.lang.String - 表示当前对象的字符串。

