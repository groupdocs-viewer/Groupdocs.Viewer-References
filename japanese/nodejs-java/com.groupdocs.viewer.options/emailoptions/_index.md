---
title: "EmailOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "メールメッセージのレンダリングオプションを提供します。"
type: docs
weight: 14
url: /ja/nodejs-java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

メールメッセージのレンダリングオプションを提供します。

EmailOptions クラスは、GroupDocs.Viewer コンポーネントでメールメッセージのレンダリングを制御するために使用できるさまざまな設定とパラメータをカプセル化します。

詳細については、[documentation][] を参照してください。

使用例:

```

 EmailOptions options = new EmailOptions();
 options.setDateTimeFormat("MM d yyyy HH:mm tt");
 options.setPageSize(PageSize.A4);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setEmailOptions(options);

 try (Viewer viewer = new Viewer("email.msg")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [EmailOptions()](#EmailOptions--) | EmailOptions クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDateTimeFormat()](#getDateTimeFormat--) | 日付と時刻の値の時間形式を取得します。 |
| [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | 日付と時刻の値の時間形式を取得します。 |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | メッセージのタイムゾーンオフセットを取得します。 |
| [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | メッセージのタイムゾーン分オフセットを取得します。 |
| [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | メッセージのタイムゾーンオフセットを取得します。 |
| [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | メッセージのタイムゾーンオフセット（分）を取得します。 |
| [getPageSize()](#getPageSize--) | 出力ページのサイズを取得します。 |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | 出力ページのサイズを取得します。 |
| [getFieldTextMap()](#getFieldTextMap--) | メールメッセージフィールドとそのテキスト表現とのマッピングを取得します。 |
| [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | メールメッセージフィールドとそのテキスト表現とのマッピングを設定します。 |
| [equals(Object o)](#equals-java.lang.Object-) | Object クラスの equals() メソッドをオーバーライドします。 |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Object クラスの toString() メソッドをオーバーライドします。 |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


EmailOptions クラスの新しいインスタンスを初期化します。このコンストラクタは、デフォルト設定で EmailOptions クラスの新しいインスタンスを作成するために使用されます。

### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


日付と時刻の値の時間形式を取得します。

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.lang.String - 日付と時刻の値の時間形式です。
### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


日付と時刻の値の時間形式を取得します。

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dateTimeFormat | java.lang.String | 日付と時刻の値の時間形式です。 |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


メッセージのタイムゾーンオフセットを取得します。

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
java.util.TimeZone - タイムゾーンオフセットです。
### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


メッセージのタイムゾーン分オフセットを取得します。

**Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC). For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone

**Returns:**
int - タイムゾーンオフセットです。
### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


メッセージのタイムゾーンオフセットを取得します。

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| timeZoneOffset | java.util.TimeZone | タイムゾーンオフセットです。 |

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


メッセージのタイムゾーンオフセット（分）を取得します。

**Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| offsetMinutes | int | タイムゾーンオフセットです。 |

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
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | ページサイズです。 |

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


メールメッセージフィールドとそのテキスト表現とのマッピングを取得します。

**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - メールメッセージフィールドとそのテキスト表現とのマッピングです。
### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


メールメッセージフィールドとそのテキスト表現とのマッピングを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | メールメッセージフィールドとそのテキスト表現のマッピングです。 |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Object クラスの equals() メソッドをオーバーライドします。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| o | java.lang.Object | 比較対象のオブジェクト。 |

**Returns:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


このオブジェクトのハッシュコード値を計算します。ハッシュコードはオブジェクトの内部状態に基づき、ハッシュマップやハッシュセットなどのハッシュベースのデータ構造で使用されます。

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

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

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| スタイル | org.apache.commons.lang3.builder.ToStringStyle | 文字列表現を生成するために使用する ToStringStyle。 |

**Returns:**
java.lang.String - 指定された ToStringStyle を使用したこのオブジェクトの文字列表現。
