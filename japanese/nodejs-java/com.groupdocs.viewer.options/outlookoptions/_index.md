---
title: "OutlookOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "Outlook データファイルのレンダリングオプションを提供します。"
type: docs
weight: 20
url: /ja/nodejs-java/com.groupdocs.viewer.options/outlookoptions/
---
**Inheritance:**
java.lang.Object
```
public class OutlookOptions
```

Outlook データファイルのレンダリングオプションを提供します。

OutlookOptions クラスは、GroupDocs.Viewer コンポーネントで Outlook データファイル（PST や OST ファイルなど）のレンダリングを制御するために使用できるさまざまな設定とパラメータをカプセル化します。

詳細については、[documentation][] を参照してください。

使用例:

```

 OutlookOptions options = new OutlookOptions();
 options.setAddressFilter("@gmail.com");
 options.setFolder("folderName");

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setOutlookOptions(options);

 try (Viewer viewer = new Viewer("mail.pst")) {
   viewer.view(htmlViewOptions);
   // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [OutlookOptions()](#OutlookOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFolder()](#getFolder--) | レンダリングするフォルダーの名前を取得します。 |
| [setFolder(String value)](#setFolder-java.lang.String-) | レンダリングするフォルダーの名前を設定します。 |
| [getTextFilter()](#getTextFilter--) | メッセージのフィルタリングに使用されるキーワードを取得します。 |
| [setTextFilter(String value)](#setTextFilter-java.lang.String-) | メッセージのフィルタリングに使用されるキーワードを取得します。 |
| [getAddressFilter()](#getAddressFilter--) | 送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを取得します。 |
| [setAddressFilter(String value)](#setAddressFilter-java.lang.String-) | 送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを設定します。 |
| [getMaxItemsInFolder()](#getMaxItemsInFolder--) | 1 つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数を取得します。 |
| [setMaxItemsInFolder(int value)](#setMaxItemsInFolder-int-) | 1 つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数を設定します。 |
### OutlookOptions() {#OutlookOptions--}
```
public OutlookOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


レンダリングするフォルダーの名前を取得します。レンダリングするフォルダーの名前（例：Inbox、Sent Item、Deleted Items）です。

Outlook データ ファイルをレンダリングする際、GroupDocs.Viewer はファイルに含まれるすべてのフォルダー（ネストされたフォルダーも含む）からメッセージをレンダリングします。このプロパティを使用して特定のフォルダーのアイテムをレンダリングします。コード例についてはこの [documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Returns:**
java.lang.String - レンダリングするフォルダーの名前です。
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


レンダリングするフォルダーの名前を設定します。レンダリングするフォルダーの名前（例: Inbox、Sent Item、Deleted Items）です。

Outlook データ ファイルをレンダリングする際、GroupDocs.Viewer はファイルに含まれるすべてのフォルダー（ネストされたフォルダーも含む）からメッセージをレンダリングします。このプロパティを使用して特定のフォルダーのアイテムをレンダリングします。コード例についてはこの [documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#render-a-specific-folder

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String | レンダリングするフォルダーの名前です。 |

### getTextFilter() {#getTextFilter--}
```
public final String getTextFilter()
```


メッセージのフィルタリングに使用されるキーワードを取得します。

このプロパティを使用して、件名または本文に特定のテキストを含むすべてのメッセージをレンダリングします。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - キーワードです。
### setTextFilter(String value) {#setTextFilter-java.lang.String-}
```
public final void setTextFilter(String value)
```


メッセージのフィルタリングに使用されるキーワードを取得します。

このプロパティを使用して、件名または本文に特定のテキストを含むすべてのメッセージをレンダリングします。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String | キーワードです。 |

### getAddressFilter() {#getAddressFilter--}
```
public final String getAddressFilter()
```


送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを取得します。

このプロパティを使用して、送信者\\ufffds または受信者\\ufffds アドレスに特定のテキストを含むすべてのメッセージをレンダリングします。コード例については [documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Returns:**
java.lang.String - メッセージをフィルタリングするために使用されるメールアドレスです。
### setAddressFilter(String value) {#setAddressFilter-java.lang.String-}
```
public final void setAddressFilter(String value)
```


送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを設定します。

このプロパティを使用して、送信者\\ufffds または受信者\\ufffds アドレスに特定のテキストを含むすべてのメッセージをレンダリングします。コード例については [documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#filter-messages

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String | メッセージをフィルタリングするために使用されるメールアドレスです。 |

### getMaxItemsInFolder() {#getMaxItemsInFolder--}
```
public final int getMaxItemsInFolder()
```


1 つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数を取得します。

Outlook データ ファイルは大きくなることがあり、すべてのメッセージを取得するのにかなりの時間がかかる場合があります。この設定は、レンダリングされるメッセージまたはアイテム（連絡先やタスクなど）の最大数を制限します。デフォルト値は 50 です。0 に設定するとすべてのメッセージをレンダリングします。コード例については [documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Returns:**
int - 1 つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数です。
### setMaxItemsInFolder(int value) {#setMaxItemsInFolder-int-}
```
public final void setMaxItemsInFolder(int value)
```


1 つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数を設定します。

Outlook データ ファイルは大きくなることがあり、すべてのメッセージを取得するのにかなりの時間がかかる場合があります。この設定は、レンダリングされるメッセージまたはアイテム（連絡先やタスクなど）の最大数を制限します。デフォルト値は 50 です。0 に設定するとすべてのメッセージをレンダリングします。コード例については [documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-outlook-data-files/#limit-the-number-of-folder-items-to-render

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int | 1 つのフォルダーからレンダリングできるメッセージまたはアイテムの最大数です。 |

