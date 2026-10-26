---
title: "Security"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "PDF ドキュメントのセキュリティオプションを提供します。"
type: docs
weight: 29
url: /ja/nodejs-java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

PDF ドキュメントのセキュリティオプションを提供します。

Security クラスは、GroupDocs.Viewer コンポーネントの PDF ドキュメントに対してセキュリティ対策を適用するために使用できるさまざまな設定とオプションをカプセル化します。これらのオプションには、パスワード保護、権限設定などが含まれます。詳細については、[documentation][] を参照してください。

使用例:

```

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [Security()](#Security--) | Security クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDocumentOpenPassword()](#getDocumentOpenPassword--) | PDF ドキュメントを開くために必要なパスワードを取得します。 |
| [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | PDF ドキュメントを開くために必要なパスワードを設定します。 |
| [getPermissionsPassword()](#getPermissionsPassword--) | 権限設定を変更するために必要なパスワードを取得します。 |
| [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | 権限設定を変更するために必要なパスワードを設定します。 |
| [getPermissions()](#getPermissions--) | PDFドキュメントの印刷、変更、データ抽出などの権限を取得します。 |
| [setPermissions(int value)](#setPermissions-int-) | PDFドキュメントの印刷、変更、データ抽出などの権限を設定します。 |
### Security() {#Security--}
```
public Security()
```


Security クラスの新しいインスタンスを初期化します。

### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


PDF ドキュメントを開くために必要なパスワードを取得します。

コードサンプルについては、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - ドキュメントのオープンパスワードです。
### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


PDF ドキュメントを開くために必要なパスワードを設定します。

コードサンプルについては、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String | ドキュメントのオープンパスワードです。 |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


権限設定を変更するために必要なパスワードを取得します。

権限パスワードを使用すると、印刷、変更、データ抽出を制限できます。権限パスワードを使用して印刷、変更、データ抽出を制限します。コードサンプルについては、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - 権限パスワードです。
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


権限設定を変更するために必要なパスワードを設定します。

権限パスワードを使用すると、印刷、変更、データ抽出を制限できます。権限パスワードを使用して印刷、変更、データ抽出を制限します。コードサンプルについては、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String | 権限パスワードです。 |

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


PDFドキュメントの印刷、変更、データ抽出などの権限を取得します。

コードサンプルについては、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
int - PDFドキュメントの権限です。
### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


PDFドキュメントの印刷、変更、データ抽出などの権限を設定します。

コードサンプルについては、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int | PDFドキュメントの権限です。 |

