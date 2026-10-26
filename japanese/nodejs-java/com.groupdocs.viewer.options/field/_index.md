---
title: "フィールド"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "メールメッセージのフィールド（例: From、To、Subject など）を表します。"
type: docs
weight: 40
url: /ja/nodejs-java/com.groupdocs.viewer.options/field/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Field extends Enum<Field>
```

メールメッセージのフィールド（例：From、To、Subject など）を表します。

Field 列挙体は GroupDocs.Viewer コンポーネントで一般的なメールメッセージ フィールドを表します。送信者、受信者、件名など、メールメッセージ内の特定情報を識別およびアクセスするために使用できる事前定義されたフィールドのセットを提供します。

詳細については、[documentation][] を参照してください。

使用例:

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
## フィールド

| フィールド | 説明 |
| --- | --- |
| [ANNIVERSARY](#ANNIVERSARY) | \"Anniversary\" フィールドを表します。 |
| [ATTACHMENTS](#ATTACHMENTS) | \"Attachments\" フィールドを表します。 |
| [BCC](#BCC) | \"Bcc\" フィールドを表します。 |
| [BIRTHDAY](#BIRTHDAY) | \"Birthday\" フィールドを表します。 |
| [BUSINESS](#BUSINESS) | \"Business\" フィールドを表します。 |
| [BUSINESS_ADDRESS](#BUSINESS-ADDRESS) | \"Business Address\" フィールドを表します。 |
| [BUSINESS_FAX](#BUSINESS-FAX) | \"Business Fax\" フィールドを表します。 |
| [BUSINESS_HOMEPAGE](#BUSINESS-HOMEPAGE) | \"BusinessHomepage\" フィールドを表します。 |
| [CC](#CC) | \"Cc\" フィールドを表します。 |
| [COMPANY](#COMPANY) | \"Company\" フィールドを表します。 |
| [DEPARTMENT](#DEPARTMENT) | \"Department\" フィールドを表します。 |
| [EMAIL](#EMAIL) | \"Email\" フィールドを表します。 |
| [EMAIL_DISPLAY_AS](#EMAIL-DISPLAY-AS) | \"Email Display As\" フィールドを表します。 |
| [EMAIL_2](#EMAIL-2) | \"Email2\" フィールドを表します。 |
| [EMAIL_2_DISPLAY_AS](#EMAIL-2-DISPLAY-AS) | \"Email2 Display As\" フィールドを表します。 |
| [EMAIL_3](#EMAIL-3) | \"Email3\" フィールドを表します。 |
| [EMAIL_3_DISPLAY_AS](#EMAIL-3-DISPLAY-AS) | \"Email3 Display As\" フィールドを表します。 |
| [END](#END) | \"End\" フィールドを表します。 |
| [FIRST_NAME](#FIRST-NAME) | \"First Name\" フィールドを表します。 |
| [FROM](#FROM) | \"From\" フィールドを表します。 |
| [FULL_NAME](#FULL-NAME) | \"Full Name\" フィールドを表します。 |
| [GENDER](#GENDER) | \"Gender\" フィールドを表します。 |
| [HOBBIES](#HOBBIES) | \"Hobbies\" フィールドを表します。 |
| [HOME](#HOME) | \"Home\" フィールドを表します。 |
| [HOME_ADDRESS](#HOME-ADDRESS) | \"Home Address\" フィールドを表します。 |
| [IMPORTANCE](#IMPORTANCE) | \"Importance\" フィールドを表します。 |
| [JOB_TITLE](#JOB-TITLE) | \"Job Title\" フィールドを表します。 |
| [LAST_NAME](#LAST-NAME) | \"Last Name\" フィールドを表します。 |
| [LOCATION](#LOCATION) | \"Location\" フィールドを表します。 |
| [MIDDLE_NAME](#MIDDLE-NAME) | \"Middle Name\" フィールドを表します。 |
| [MOBILE](#MOBILE) | \"Mobile\" フィールドを表します。 |
| [ORGANIZER](#ORGANIZER) | \"Organizer\" フィールドを表します。 |
| [OTHER_ADDRESS](#OTHER-ADDRESS) | \"Other Address\" フィールドを表します。 |
| [PERSONAL_HOMEPAGE](#PERSONAL-HOMEPAGE) | \"Personal Homepage\" フィールドを表します。 |
| [PROFESSION](#PROFESSION) | \"Profession\" フィールドを表します。 |
| [RECURRENCE](#RECURRENCE) | \"Recurrence\" フィールドを表します。 |
| [RECURRENCE_PATTERN](#RECURRENCE-PATTERN) | \"Recurrence Pattern\" フィールドを表します。 |
| [REQUIRED_ATTENDEES](#REQUIRED-ATTENDEES) | \"Required Attendees\" フィールドを表します。 |
| [SENT](#SENT) | \"Sent\" フィールドを表します。 |
| [SHOW_TIME_AS](#SHOW-TIME-AS) | \"Show Time As\" フィールドを表します。 |
| [SPOUSE_PARTNER](#SPOUSE-PARTNER) | \"Spouse/Partner\" フィールドを表します。 |
| [START](#START) | \"Start\" フィールドを表します。 |
| [SUBJECT](#SUBJECT) | \"Subject\" フィールドを表します。 |
| [TO](#TO) | \"To\" フィールドを表します。 |
| [USER_FIELD_1](#USER-FIELD-1) | \"User Field 1\" フィールドを表します。 |
| [USER_FIELD_2](#USER-FIELD-2) | \"User Field 2\" フィールドを表します。 |
| [USER_FIELD_3](#USER-FIELD-3) | \"User Field 3\" フィールドを表します。 |
| [USER_FIELD_4](#USER-FIELD-4) | \"User Field 4\" フィールドを表します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [getName()](#getName--) | フィールド名。 |
| [toString()](#toString--) | 現在のオブジェクトを表す文字列を返します。 |
### ANNIVERSARY {#ANNIVERSARY}
```
public static final Field ANNIVERSARY
```


\"Anniversary\" フィールドを表します。

### ATTACHMENTS {#ATTACHMENTS}
```
public static final Field ATTACHMENTS
```


\"Attachments\" フィールドを表します。

### BCC {#BCC}
```
public static final Field BCC
```


\"Bcc\" フィールドを表します。

### BIRTHDAY {#BIRTHDAY}
```
public static final Field BIRTHDAY
```


\"Birthday\" フィールドを表します。

### BUSINESS {#BUSINESS}
```
public static final Field BUSINESS
```


\"Business\" フィールドを表します。

### BUSINESS_ADDRESS {#BUSINESS-ADDRESS}
```
public static final Field BUSINESS_ADDRESS
```


\"Business Address\" フィールドを表します。

### BUSINESS_FAX {#BUSINESS-FAX}
```
public static final Field BUSINESS_FAX
```


\"Business Fax\" フィールドを表します。

### BUSINESS_HOMEPAGE {#BUSINESS-HOMEPAGE}
```
public static final Field BUSINESS_HOMEPAGE
```


\"BusinessHomepage\" フィールドを表します。

### CC {#CC}
```
public static final Field CC
```


\"Cc\" フィールドを表します。

### COMPANY {#COMPANY}
```
public static final Field COMPANY
```


\"Company\" フィールドを表します。

### DEPARTMENT {#DEPARTMENT}
```
public static final Field DEPARTMENT
```


\"Department\" フィールドを表します。

### EMAIL {#EMAIL}
```
public static final Field EMAIL
```


\"Email\" フィールドを表します。

### EMAIL_DISPLAY_AS {#EMAIL-DISPLAY-AS}
```
public static final Field EMAIL_DISPLAY_AS
```


\"Email Display As\" フィールドを表します。

### EMAIL_2 {#EMAIL-2}
```
public static final Field EMAIL_2
```


\"Email2\" フィールドを表します。

### EMAIL_2_DISPLAY_AS {#EMAIL-2-DISPLAY-AS}
```
public static final Field EMAIL_2_DISPLAY_AS
```


\"Email2 Display As\" フィールドを表します。

### EMAIL_3 {#EMAIL-3}
```
public static final Field EMAIL_3
```


\"Email3\" フィールドを表します。

### EMAIL_3_DISPLAY_AS {#EMAIL-3-DISPLAY-AS}
```
public static final Field EMAIL_3_DISPLAY_AS
```


\"Email3 Display As\" フィールドを表します。

### END {#END}
```
public static final Field END
```


\"End\" フィールドを表します。

### FIRST_NAME {#FIRST-NAME}
```
public static final Field FIRST_NAME
```


\"First Name\" フィールドを表します。

### FROM {#FROM}
```
public static final Field FROM
```


\"From\" フィールドを表します。

### FULL_NAME {#FULL-NAME}
```
public static final Field FULL_NAME
```


\"Full Name\" フィールドを表します。

### GENDER {#GENDER}
```
public static final Field GENDER
```


\"Gender\" フィールドを表します。

### HOBBIES {#HOBBIES}
```
public static final Field HOBBIES
```


\"Hobbies\" フィールドを表します。

### HOME {#HOME}
```
public static final Field HOME
```


\"Home\" フィールドを表します。

### HOME_ADDRESS {#HOME-ADDRESS}
```
public static final Field HOME_ADDRESS
```


\"Home Address\" フィールドを表します。

### IMPORTANCE {#IMPORTANCE}
```
public static final Field IMPORTANCE
```


\"Importance\" フィールドを表します。

### JOB_TITLE {#JOB-TITLE}
```
public static final Field JOB_TITLE
```


\"Job Title\" フィールドを表します。

### LAST_NAME {#LAST-NAME}
```
public static final Field LAST_NAME
```


\"Last Name\" フィールドを表します。

### LOCATION {#LOCATION}
```
public static final Field LOCATION
```


\"Location\" フィールドを表します。

### MIDDLE_NAME {#MIDDLE-NAME}
```
public static final Field MIDDLE_NAME
```


\"Middle Name\" フィールドを表します。

### MOBILE {#MOBILE}
```
public static final Field MOBILE
```


\"Mobile\" フィールドを表します。

### ORGANIZER {#ORGANIZER}
```
public static final Field ORGANIZER
```


\"Organizer\" フィールドを表します。

### OTHER_ADDRESS {#OTHER-ADDRESS}
```
public static final Field OTHER_ADDRESS
```


\"Other Address\" フィールドを表します。

### PERSONAL_HOMEPAGE {#PERSONAL-HOMEPAGE}
```
public static final Field PERSONAL_HOMEPAGE
```


\"Personal Homepage\" フィールドを表します。

### PROFESSION {#PROFESSION}
```
public static final Field PROFESSION
```


\"Profession\" フィールドを表します。

### RECURRENCE {#RECURRENCE}
```
public static final Field RECURRENCE
```


\"Recurrence\" フィールドを表します。

### RECURRENCE_PATTERN {#RECURRENCE-PATTERN}
```
public static final Field RECURRENCE_PATTERN
```


\"Recurrence Pattern\" フィールドを表します。

### REQUIRED_ATTENDEES {#REQUIRED-ATTENDEES}
```
public static final Field REQUIRED_ATTENDEES
```


\"Required Attendees\" フィールドを表します。

### SENT {#SENT}
```
public static final Field SENT
```


\"Sent\" フィールドを表します。

### SHOW_TIME_AS {#SHOW-TIME-AS}
```
public static final Field SHOW_TIME_AS
```


\"Show Time As\" フィールドを表します。

### SPOUSE_PARTNER {#SPOUSE-PARTNER}
```
public static final Field SPOUSE_PARTNER
```


\"Spouse/Partner\" フィールドを表します。

### START {#START}
```
public static final Field START
```


\"Start\" フィールドを表します。

### SUBJECT {#SUBJECT}
```
public static final Field SUBJECT
```


\"Subject\" フィールドを表します。

### TO {#TO}
```
public static final Field TO
```


\"To\" フィールドを表します。

### USER_FIELD_1 {#USER-FIELD-1}
```
public static final Field USER_FIELD_1
```


\"User Field 1\" フィールドを表します。

### USER_FIELD_2 {#USER-FIELD-2}
```
public static final Field USER_FIELD_2
```


\"User Field 2\" フィールドを表します。

### USER_FIELD_3 {#USER-FIELD-3}
```
public static final Field USER_FIELD_3
```


\"User Field 3\" フィールドを表します。

### USER_FIELD_4 {#USER-FIELD-4}
```
public static final Field USER_FIELD_4
```


\"User Field 4\" フィールドを表します。

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
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[Field](../../com.groupdocs.viewer.options/field)
### getName() {#getName--}
```
public final String getName()
```


フィールド名。

このメソッドはフィールドの名前を取得します。

**Returns:**
java.lang.String - フィールドの名前。
### toString() {#toString--}
```
public String toString()
```


現在のオブジェクトを表す文字列を返します。

**Returns:**
java.lang.String - 現在のオブジェクトを表す文字列。
