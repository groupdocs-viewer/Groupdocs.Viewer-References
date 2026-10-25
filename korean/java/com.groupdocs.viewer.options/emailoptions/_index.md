---
title: "EmailOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "이메일 메시지를 렌더링하기 위한 옵션을 제공합니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

이메일 메시지를 렌더링하기 위한 옵션을 제공합니다.


EmailOptions 클래스는 사용할 수 있는 다양한 설정 및 매개변수를 캡슐화합니다.
GroupDocs.Viewer 구성 요소에서 이메일 메시지 렌더링을 제어합니다.


자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/)을 참조하십시오.


사용 예시:

````

 EmailOptions options = new EmailOptions();
 options.setDateTimeFormat("MM d yyyy HH:mm tt");
 options.setPageSize(PageSize.A4);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setEmailOptions(options);

 try (Viewer viewer = new Viewer("email.msg")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [EmailOptions()](#EmailOptions--) | 새 인스턴스를 초기화합니다. |
EmailOptions
클래스.
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getDateTimeFormat()](#getDateTimeFormat--) | 날짜 및 시간 값에 대한 시간 형식을 가져옵니다. |
|
|  | [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | 날짜 및 시간 값에 대한 시간 형식을 가져옵니다. |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | 메시지에 대한 시간대 오프셋을 가져옵니다. |
|
|  | [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | 메시지에 대한 시간대 분 오프셋을 가져옵니다. |
|
|  | [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | 메시지에 대한 시간대 오프셋을 가져옵니다. |
|
|  | [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | 메시지에 대한 시간대 오프셋(분) 값을 가져옵니다. |
|
|  | [getPageSize()](#getPageSize--) | 출력 페이지의 크기를 가져옵니다. |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | 출력 페이지의 크기를 가져옵니다. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | 이메일 메시지 필드와 해당 텍스트 표현 사이의 매핑을 검색합니다. |
|
|  | [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | 이메일 메시지 필드와 해당 텍스트 표현 사이의 매핑을 설정합니다. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Object 클래스의 equals() 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | Object 클래스의 toString() 메서드를 재정의합니다. |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


새 인스턴스를 초기화합니다.
EmailOptions
클래스.
이 생성자는 새로운 인스턴스를 만들기 위해 사용됩니다.
EmailOptions
기본 설정을 가진 클래스.


### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


날짜 및 시간 값에 대한 시간 형식을 가져옵니다.
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
시간 형식이 설정되지 않은 경우 현재 시스템 형식이 사용됩니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.lang.String - 날짜 및 시간 값에 대한 시간 형식.

### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


날짜 및 시간 값에 대한 시간 형식을 가져옵니다.
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
시간 형식이 설정되지 않은 경우 현재 시스템 형식이 사용됩니다.
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | dateTimeFormat | java.lang.String | 날짜 및 시간 값에 대한 시간 형식. |
|

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


메시지에 대한 시간대 오프셋을 가져옵니다.
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.util.TimeZone - 시간대 오프셋.

### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


메시지에 대한 시간대 분 오프셋을 가져옵니다.
***Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC).
자세한 내용은 [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
int - 시간대 오프셋.

### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


메시지에 대한 시간대 오프셋을 가져옵니다.
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | timeZoneOffset | java.util.TimeZone | 시간대 오프셋. |
|

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


메시지에 대한 시간대 오프셋(분) 값을 가져옵니다.
***Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | offsetMinutes | int | 시간대 오프셋. |
|

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


출력 페이지의 크기를 가져옵니다.


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


출력 페이지의 크기를 가져옵니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | 페이지 크기. |
|

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


이메일 메시지 필드와 해당 텍스트 표현 사이의 매핑을 검색합니다.


**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - 이메일 메시지 필드와 해당 텍스트 표현 사이의 매핑.

### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


이메일 메시지 필드와 해당 텍스트 표현 사이의 매핑을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 값 | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | 이메일 메시지 필드와 해당 텍스트 표현 사이의 매핑. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Object 클래스의 equals() 메서드를 재정의합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | o | java.lang.Object | 비교할 객체. |
|

**Returns:**
boolean - 객체가 동일하면 true, 그렇지 않으면 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```


이 객체에 대한 해시 코드 값을 계산합니다. 해시 코드는 다음을 기반으로 합니다.
객체의 내부 상태이며 해시 기반 데이터 구조에서 사용됩니다
예: 해시 맵 및 해시 집합.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - 이 객체에 대한 해시 코드 값.

### toString() {#toString--}
```
public String toString()
```


Object 클래스의 toString() 메서드를 재정의합니다.


**Returns:**
java.lang.String - 객체의 문자열 표현.

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


이 객체의 문자열 표현을 반환합니다.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | style | org.apache.commons.lang3.builder.ToStringStyle | 문자열 표현을 생성할 때 사용할 ToStringStyle. |
|

**Returns:**
java.lang.String - 지정된 ToStringStyle을 사용하여 이 객체를 문자열로 표현한 결과.

