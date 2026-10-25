---
title: "ライセンス"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "コンポーネントのライセンス付与と完全機能の有効化のためのメソッドを提供します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

コンポーネントのライセンス付与と完全機能の有効化のためのメソッドを提供します。


License クラスを使用すると、GroupDocs.Viewer コンポーネントに有効なライセンスを適用でき、すべての機能を利用でき、評価版の制限を解除できます。


使用例:

````

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [License()](#License--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
|  | [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | コンポーネントにライセンスを適用します。 |
|
|  | [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | コンポーネントにライセンスを適用します。 |
|
|  | [setLicense(String licensePath)](#setLicense-java.lang.String-) | コンポーネントにライセンスを適用します。 |
|
|  | [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | コンポーネントにライセンスを適用します。 |
|
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


コンポーネントにライセンスを適用します。


次の例は、ライセンスファイルの InputStream を渡してライセンスを設定する方法を示しています。


ライセンスに関する詳細情報は、以下をご参照ください
[GroupDocs Licensing FAQ](../https://purchase.groupdocs.com/faqs/licensing).
GroupDocs.Viewer のライセンスに関する詳細情報は、以下で確認できます
[Evaluation Limitations and Licensing](../https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer) documentation.

**Example:**

````

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
````



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | licenseStream | java.io.InputStream | ライセンスストリームです。 |
|

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


コンポーネントにライセンスを適用します。


指定されたライセンスパスを使用してコンポーネントのライセンスを設定します。


**Note:** This method should be called before using any functionality of the component.


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | licensePath | java.nio.file.Path | ライセンス パスです。 |
|

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


コンポーネントにライセンスを適用します。


このメソッドは、任意の機能を使用する前に呼び出す必要があります。


使用例:

````

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
````

<br />



**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | licensePath | java.lang.String | ライセンス パスまたは URLです。 |
|

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


コンポーネントにライセンスを適用します。


このメソッドは、任意の機能を使用する前に呼び出す必要があります。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | licenseUri | java.net.URL | ライセンス URIです。 |
|

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
