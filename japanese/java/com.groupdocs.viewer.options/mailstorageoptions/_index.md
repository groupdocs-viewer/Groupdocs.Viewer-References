---
title: "MailStorageOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "Mail ストレージの Lotus Notes MBox データファイルをレンダリングするためのオプションを提供します。"
type: docs
weight: 19
url: /ja/java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

メールストレージ（Lotus Notes、MBox）データファイルのレンダリングオプションを提供します。


MailStorageOptions クラスは、使用できるさまざまな設定とパラメータをカプセル化します。
GroupDocs.Viewer コンポーネント内で、Mail ストレージデータファイル（例：Lotus Notes や MBox）のレンダリングを制御します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options) を参照してください。


使用例:

````

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getTextFilter()](#getTextFilter--) | メッセージをフィルタリングするために使用されるキーワードを取得します。 |
|
|  | [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | メッセージをフィルタリングするために使用されるキーワードを設定します。 |
|
|  | [getAddressFilter()](#getAddressFilter--) | 送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを取得します。 |
|
|  | [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | 送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを設定します。 |
|
|  | [getMaxItems()](#getMaxItems--) | レンダリングするメッセージまたはアイテムの最大数を取得します。 |
|
|  | [setMaxItems(int maxItems)](#setMaxItems-int-) | レンダリングするメッセージまたはアイテムの最大数を設定します。 |
|
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


メッセージをフィルタリングするために使用されるキーワードを取得します。


このプロパティを使用して、件名または本文に特定のテキストが含まれるすべてのメッセージをレンダリングします。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages) を参照してください。


**Returns:**
java.lang.String - メッセージのフィルタリングに使用されるキーワードです。

### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


メッセージをフィルタリングするために使用されるキーワードを設定します。


このプロパティを使用して、件名または本文に特定のテキストが含まれるすべてのメッセージをレンダリングします。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | textFilter | java.lang.String | メッセージのフィルタリングに使用されるキーワードです。 |
|

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを取得します。


このプロパティを使用して、送信者\\u2019s または受信者\\u2019s のアドレスに特定のテキストが含まれるすべてのメッセージをレンダリングします。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages) を参照してください。


**Returns:**
java.lang.String - メッセージのフィルタリングに使用されるメールアドレスです。

### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを設定します。


このプロパティを使用して、送信者\\u2019s または受信者\\u2019s のアドレスに特定のテキストが含まれるすべてのメッセージをレンダリングします。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | addressFilter | java.lang.String | メッセージのフィルタリングに使用されるメールアドレスです。 |
|

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


レンダリングするメッセージまたはアイテムの最大数を取得します。


Lotus Notes のデータファイルは大きくなることがあり、すべてのメッセージを取得するのにかなりの時間がかかる場合があります。
この設定は、レンダリングされるメッセージまたはアイテムの最大数を制限します。


***Note:** The default value is 0, which means all messages will be rendered.*
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render) を参照してください。


**Returns:**
int - レンダリングするメッセージまたはアイテムの最大数です。

### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


レンダリングするメッセージまたはアイテムの最大数を設定します。


Lotus Notes のデータファイルは大きくなることがあり、すべてのメッセージを取得するのにかなりの時間がかかる場合があります。
この設定は、レンダリングされるメッセージまたはアイテムの最大数を制限します。


***Note:** The default value is 0, which means all messages will be rendered.*
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | maxItems | int | レンダリングするメッセージまたはアイテムの最大数です。 |
|

