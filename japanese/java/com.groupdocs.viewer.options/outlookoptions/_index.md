---
title: "OutlookOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "Outlook データファイルのレンダリングオプションを提供します。"
type: docs
weight: 20
url: /ja/java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Outlook データファイルのレンダリングオプションを提供します。


OutlookOptions クラスは、使用できるさまざまな設定とパラメータをカプセル化します
GroupDocs.Viewer コンポーネントで Outlook データファイル（PST や OST ファイルなど）のレンダリングを制御するために使用できます。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options) を参照してください。


使用例:

````

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFolder()](#getFolder--) | レンダリングするフォルダーの名前を取得します。 |
|
|  | [setFolder(String value)](#setFolder-java.lang.String-) | レンダリングするフォルダーの名前を設定します。 |
|
|  | [getTextFilter()](#getTextFilter--) | メッセージをフィルタリングするために使用されるキーワードを取得します。 |
|
|  | [setTextFilter(String value)](#setTextFilter-java.lang.String-) | メッセージをフィルタリングするために使用されるキーワードを取得します。 |
|
|  | [getAddressFilter()](#getAddressFilter--) | 送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを取得します。 |
|
|  | [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | 送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを設定します。 |
|
|  | [getMaxItemsInFolder()](#getMaxItemsInFolder--) | 1 つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数を取得します。 |
|
|  | [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | 1 つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数を設定します。 |
|
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


レンダリングするフォルダーの名前を取得します。
レンダリングするフォルダーの名前（例: Inbox、Sent Item、Deleted Items）。


Outlook データファイルをレンダリングする際、GroupDocs.Viewer はファイルに含まれるすべてのフォルダー（ネストされたフォルダーを含む）からメッセージをレンダリングします。このプロパティを使用して特定のフォルダーからアイテムをレンダリングしてください。
コード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder) を参照してください。


**Returns:**
java.lang.String - レンダリングするフォルダーの名前です。

### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


レンダリングするフォルダーの名前を設定します。
レンダリングするフォルダーの名前（例: Inbox、Sent Item、Deleted Items）。


Outlook データファイルをレンダリングする際、GroupDocs.Viewer はファイルに含まれるすべてのフォルダー（ネストされたフォルダーを含む）からメッセージをレンダリングします。このプロパティを使用して特定のフォルダーからアイテムをレンダリングしてください。
コード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | java.lang.String | レンダリングするフォルダーの名前です。 |
|

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


メッセージをフィルタリングするために使用されるキーワードを取得します。


このプロパティを使用して、件名または本文に特定のテキストが含まれるすべてのメッセージをレンダリングします。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages) を参照してください。


**Returns:**
java.lang.String - キーワードです。

### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


メッセージをフィルタリングするために使用されるキーワードを取得します。


このプロパティを使用して、件名または本文に特定のテキストが含まれるすべてのメッセージをレンダリングします。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | java.lang.String | キーワードです。 |
|

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを取得します。


このプロパティを使用して、送信者\\ufffds または受信者\\ufffds アドレスに特定のテキストが含まれるすべてのメッセージをレンダリングします。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages) を参照してください。


**Returns:**
java.lang.String - メッセージをフィルタリングするために使用されるメールアドレスです。

### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを設定します。


このプロパティを使用して、送信者\\ufffds または受信者\\ufffds アドレスに特定のテキストが含まれるすべてのメッセージをレンダリングします。コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | java.lang.String | メッセージをフィルタリングするために使用されるメールアドレスです。 |
|

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


1 つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数を取得します。


Outlook データ ファイルは大きくなる可能性があり、すべてのメッセージを取得するのにかなり時間がかかることがあります。
この設定は、レンダリングされるメッセージまたはアイテム（連絡先やタスクなど）の最大数を制限します。
デフォルト値は 50 です。すべてのメッセージをレンダリングするには、値を 0 に設定してください。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render) を参照してください。


**Returns:**
int - 1 つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数です。

### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


1 つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数を設定します。


Outlook データ ファイルは大きくなる可能性があり、すべてのメッセージを取得するのにかなり時間がかかることがあります。
この設定は、レンダリングされるメッセージまたはアイテム（連絡先やタスクなど）の最大数を制限します。
デフォルト値は 50 です。すべてのメッセージをレンダリングするには、値を 0 に設定してください。
コード例については、[documentation](../https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | int | 1 つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数です。 |
|

