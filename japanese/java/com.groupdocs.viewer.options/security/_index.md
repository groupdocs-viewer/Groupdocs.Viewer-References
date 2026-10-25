---
title: "Security"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "PDF ドキュメントのセキュリティオプションを提供します。"
type: docs
weight: 29
url: /ja/java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

PDF ドキュメントのセキュリティオプションを提供します。


Security クラスは、セキュリティ対策を適用するために使用できるさまざまな設定とオプションをカプセル化します
GroupDocs.Viewer コンポーネントの PDF ドキュメントに対してです。これらのオプションにはパスワード保護が含まれます、
権限、その他。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/) を参照してください。


使用例:

````

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Security()](#Security--) | 新しいインスタンスを初期化します |
Security
クラス。
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getDocumentOpenPassword()](#getDocumentOpenPassword--) | PDFドキュメントを開くために必要なパスワードを取得します。 |
|
|  | [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | PDFドキュメントを開くために必要なパスワードを設定します。 |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | 権限設定を変更するために必要なパスワードを取得します。 |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | 権限設定を変更するために必要なパスワードを設定します。 |
|
|  | [getPermissions()](#getPermissions--) | 印刷、変更、データ抽出などのPDFドキュメントの権限を取得します。 |
|
|  | [setPermissions(int value)](#setPermissions-int-) | 印刷、変更、データ抽出などのPDFドキュメントの権限を設定します。 |
|
### Security() {#Security--}
```
public Security()
```


新しいインスタンスを初期化します
Security
クラス。


### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


PDFドキュメントを開くために必要なパスワードを取得します。


コードサンプルについては、[documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/)をご覧ください。


**Returns:**
java.lang.String - ドキュメントのオープンパスワード。

### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


PDFドキュメントを開くために必要なパスワードを設定します。


コードサンプルについては、[documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | java.lang.String | ドキュメントのオープンパスワード。 |
|

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


権限設定を変更するために必要なパスワードを取得します。


権限パスワードを使用すると、印刷、変更、データ抽出を制限できます。
権限パスワードを使用して印刷、変更、データ抽出を制限します。コードサンプルについては、[documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/)をご覧ください。


**Returns:**
java.lang.String - 権限パスワード。

### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


権限設定を変更するために必要なパスワードを設定します。


権限パスワードを使用すると、印刷、変更、データ抽出を制限できます。
権限パスワードを使用して印刷、変更、データ抽出を制限します。コードサンプルについては、[documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | java.lang.String | 権限パスワード。 |
|

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


印刷、変更、データ抽出などのPDFドキュメントの権限を取得します。


コードサンプルについては、[documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/)をご覧ください。


**Returns:**
int - PDFドキュメントの権限。

### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


印刷、変更、データ抽出などのPDFドキュメントの権限を設定します。


コードサンプルについては、[documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/)をご覧ください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | int | PDFドキュメントの権限。 |
|

