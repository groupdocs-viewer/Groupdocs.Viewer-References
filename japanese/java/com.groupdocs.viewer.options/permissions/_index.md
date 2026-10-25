---
title: "Permissions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "PDF ドキュメントの権限を定義します。"
type: docs
weight: 24
url: /ja/java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

PDF ドキュメントの権限を定義します。


Permissions クラスは、さまざまな権限を表す定数を提供します。
これらは GroupDocs.Viewer コンポーネントの PDF ドキュメントに適用できます。
これらの権限は PDF ドキュメントで実行できる操作を制御します、
印刷、テキストのコピー、注釈の変更などが含まれます。


使用例:

````

 int permissions = Permissions.DENY_PRINTING | Permissions.DENY_MODIFICATION;
 final Security security = new Security();
 security.setPermissions(permissions);
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
| [Permissions()](#Permissions--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [ALLOW_ALL](#ALLOW-ALL) | 印刷、変更、データ抽出を許可します。 |
|
|  | [DENY_PRINTING](#DENY-PRINTING) | 印刷を拒否します。 |
|
|  | [DENY_MODIFICATION](#DENY-MODIFICATION) | コンテンツの変更、フォームへの入力、注釈の追加または変更を拒否します。 |
|
|  | [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | テキストと画像の抽出を拒否します。 |
|
|  | [DENY_ALL](#DENY-ALL) | 印刷、変更、データ抽出を拒否します。 |
|
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


印刷、変更、データ抽出を許可します。


### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


印刷を拒否します。


### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


コンテンツの変更、フォームへの入力、注釈の追加または変更を拒否します。


### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


テキストと画像の抽出を拒否します。


### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


印刷、変更、データ抽出を拒否します。


