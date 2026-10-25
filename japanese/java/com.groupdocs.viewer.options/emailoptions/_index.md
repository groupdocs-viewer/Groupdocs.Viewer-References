---
title: "EmailOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "メールメッセージのレンダリングオプションを提供します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

メールメッセージのレンダリングオプションを提供します。


EmailOptions クラスは、使用できるさまざまな設定とパラメータをカプセル化します。
GroupDocs.Viewer コンポーネントでメールメッセージのレンダリングを制御します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/) を参照してください。


使用例:

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


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [EmailOptions()](#EmailOptions--) | 新しいインスタンスを初期化します |
EmailOptions
クラス。
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getDateTimeFormat()](#getDateTimeFormat--) | 日付と時刻の値の時間形式を取得します。 |
|
|  | [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | 日付と時刻の値の時間形式を取得します。 |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | メッセージのタイムゾーンオフセットを取得します。 |
|
|  | [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | メッセージのタイムゾーン分オフセットを取得します。 |
|
|  | [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | メッセージのタイムゾーンオフセットを取得します。 |
|
|  | [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | メッセージのタイムゾーンオフセット（分）を取得します。 |
|
|  | [getPageSize()](#getPageSize--) | 出力ページのサイズを取得します。 |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | 出力ページのサイズを取得します。 |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | メールメッセージフィールドとそのテキスト表現とのマッピングを取得します。 |
|
|  | [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | メールメッセージフィールドとそのテキスト表現とのマッピングを設定します。 |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Object クラスの equals() メソッドをオーバーライドします。 |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | Object クラスの toString() メソッドをオーバーライドします。 |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


新しいインスタンスを初期化します
EmailOptions
クラス。
このコンストラクタは、新しいインスタンスを作成するために使用されます。
EmailOptions
デフォルト設定のクラスです。


### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


日付と時刻の値の時間形式を取得します。
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
時間形式が設定されていない場合、現在のシステム形式が使用されます。
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone)をご覧ください.*


**Returns:**
java.lang.String - 日付と時刻の値の時間形式です。

### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


日付と時刻の値の時間形式を取得します。
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
時間形式が設定されていない場合、現在のシステム形式が使用されます。
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone)をご覧ください.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | dateTimeFormat | java.lang.String | 日付と時刻の値の時間形式です。 |
|

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


メッセージのタイムゾーンオフセットを取得します。
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone)をご覧ください.*


**Returns:**
java.util.TimeZone - タイムゾーンのオフセットです。

### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


メッセージのタイムゾーン分オフセットを取得します。
***Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC).
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone)をご覧ください.*


**Returns:**
int - タイムゾーンのオフセットです。

### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


メッセージのタイムゾーンオフセットを取得します。
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | timeZoneOffset | java.util.TimeZone | タイムゾーンのオフセットです。 |
|

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


メッセージのタイムゾーンオフセット（分）を取得します。
***Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | offsetMinutes | int | タイムゾーンのオフセットです。 |
|

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


出力ページのサイズを取得します。


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


出力ページのサイズを取得します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | ページサイズです。 |
|

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


メールメッセージフィールドとそのテキスト表現とのマッピングを取得します。


**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - 電子メールメッセージフィールドとそのテキスト表現とのマッピングです。

### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


メールメッセージフィールドとそのテキスト表現とのマッピングを設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | 電子メールメッセージフィールドとそのテキスト表現とのマッピングです。 |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Object クラスの equals() メソッドをオーバーライドします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | o | java.lang.Object | 比較対象となるオブジェクトです。 |
|

**Returns:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false です。

### hashCode() {#hashCode--}
```
public int hashCode()
```


このオブジェクトのハッシュコード値を計算します。ハッシュコードは
オブジェクトの内部状態に基づき、ハッシュベースのデータ構造で使用されます
ハッシュマップやハッシュセットなどです。
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - このオブジェクトのハッシュコード値。

### toString() {#toString--}
```
public String toString()
```


Object クラスの toString() メソッドをオーバーライドします。


**Returns:**
java.lang.String - オブジェクトの文字列表現です。

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


このオブジェクトの文字列表現を返します。
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | スタイル | org.apache.commons.lang3.builder.ToStringStyle | 文字列表現を生成するために使用する ToStringStyle。 |
|

**Returns:**
java.lang.String - 指定された ToStringStyle を使用したこのオブジェクトの文字列表現。

