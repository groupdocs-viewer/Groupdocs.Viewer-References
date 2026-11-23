---
title: "MailStorageOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "Mail ストレージの Lotus Notes MBox データファイルのレンダリングオプションを提供します。"
type: docs
weight: 19
url: /ja/nodejs-java/com.groupdocs.viewer.options/mailstorageoptions/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageOptions
```

メールストレージ（Lotus Notes、MBox）データファイルのレンダリングオプションを提供します。

MailStorageOptions クラスは、Mail ストレージデータファイル（Lotus Notes や MBox など）のレンダリングを制御するために使用できる、さまざまな設定とパラメータをカプセル化します。GroupDocs.Viewer コンポーネント内で使用されます。

詳細については、[documentation][] を参照してください。

使用例:

```

 MailStorageOptions options = new MailStorageOptions();
 options.setAddressFilter("@gmail.com");
 options.setMaxItems(10);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setMailStorageOptions(options);

 try (Viewer viewer = new Viewer("mail.msg")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#specify-rendering-options
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [MailStorageOptions()](#MailStorageOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getTextFilter()](#getTextFilter--) | メッセージのフィルタリングに使用されるキーワードを取得します。 |
| [setTextFilter(String textFilter)](#setTextFilter-java.lang.String-) | メッセージのフィルタリングに使用されるキーワードを設定します。 |
| [getAddressFilter()](#getAddressFilter--) | 送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを取得します。 |
| [setAddressFilter(String addressFilter)](#setAddressFilter-java.lang.String-) | 送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを設定します。 |
| [getMaxItems()](#getMaxItems--) | レンダリングするメッセージまたは項目の最大数を取得します。 |
| [setMaxItems(int maxItems)](#setMaxItems-int-) | レンダリングするメッセージまたは項目の最大数を設定します。 |
### MailStorageOptions() {#MailStorageOptions--}
```
public MailStorageOptions()
```


### getTextFilter() {#getTextFilter--}
```
public String getTextFilter()
```


メッセージのフィルタリングに使用されるキーワードを取得します。

このプロパティを使用して、件名または本文に特定のテキストを含むすべてのメッセージをレンダリングします。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - メッセージのフィルタリングに使用されるキーワードです。
### setTextFilter(String textFilter) {#setTextFilter-java.lang.String-}
```
public void setTextFilter(String textFilter)
```


メッセージのフィルタリングに使用されるキーワードを設定します。

このプロパティを使用して、件名または本文に特定のテキストを含むすべてのメッセージをレンダリングします。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| textFilter | java.lang.String | メッセージのフィルタリングに使用されるキーワードです。 |

### getAddressFilter() {#getAddressFilter--}
```
public String getAddressFilter()
```


送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを取得します。

このプロパティを使用して、送信者または受信者のアドレスに特定のテキストを含むすべてのメッセージをレンダリングします。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Returns:**
java.lang.String - メッセージのフィルタリングに使用されるメールアドレスです。
### setAddressFilter(String addressFilter) {#setAddressFilter-java.lang.String-}
```
public void setAddressFilter(String addressFilter)
```


送信者または受信者でメッセージをフィルタリングするために使用されるメールアドレスを設定します。

このプロパティを使用して、送信者または受信者のアドレスに特定のテキストを含むすべてのメッセージをレンダリングします。コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#filter-messages

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| addressFilter | java.lang.String | メッセージのフィルタリングに使用されるメールアドレスです。 |

### getMaxItems() {#getMaxItems--}
```
public int getMaxItems()
```


レンダリングするメッセージまたは項目の最大数を取得します。

Lotus Notes のデータファイルは大きくなることがあり、すべてのメッセージを取得するのにかなりの時間がかかる場合があります。この設定は、レンダリングされるメッセージまたはアイテムの最大数を制限します。

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Returns:**
int - レンダリングするメッセージまたはアイテムの最大数です。
### setMaxItems(int maxItems) {#setMaxItems-int-}
```
public void setMaxItems(int maxItems)
```


レンダリングするメッセージまたは項目の最大数を設定します。

Lotus Notes のデータファイルは大きくなることがあり、すべてのメッセージを取得するのにかなりの時間がかかる場合があります。この設定は、レンダリングされるメッセージまたはアイテムの最大数を制限します。

***Note:** The default value is 0, which means all messages will be rendered.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-lotus-notes-database-files/#limit-the-number-of-items-to-render

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| maxItems | int | レンダリングするメッセージまたはアイテムの最大数です。 |

