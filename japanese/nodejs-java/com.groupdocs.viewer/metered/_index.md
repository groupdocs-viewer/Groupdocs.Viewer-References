---
title: "従量課金"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "GroupDocs.Viewer コンポーネントに従量制ライセンスを適用するためのメソッドを提供します。"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

GroupDocs.Viewer コンポーネントに従量制ライセンスを適用するためのメソッドを提供します。

従量課金ライセンスは、従来のサーバー単位または開発者単位のライセンスではなく、処理されたドキュメントページ数に基づいて GroupDocs.Viewer の使用量を動的に監視および制御できるようにします。この柔軟なライセンスモデルは、ドキュメント処理の要件が時間とともに変化するシナリオや、使用した分だけ支払いたい場合に適しています。

使用例:

```

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
```
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [Metered()](#Metered--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 処理されたメガバイト (MB) の量を取得します。 |
| [getConsumptionCredit()](#getConsumptionCredit--) | 消費されたクレジットの数を取得します。 |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Metered keys を使用して製品を有効化します。 |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


処理されたメガバイト (MB) の量を取得します。

このメソッドはコンポーネントによって処理された MB の総量を返します。

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
```

**Returns:**
double - 処理された MB の量。
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


消費されたクレジットの数を取得します。

このメソッドはコンポーネントによって消費されたクレジットの総数を返します。

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
```

**Returns:**
double - 消費されたクレジットの数。
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Metered keys を使用して製品を有効化します。

以下の例は Metered keys を使用して製品を有効化する方法を示しています。

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
```

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| publicKey | java.lang.String | 公開鍵です。 |
| privateKey | java.lang.String | 秘密鍵です。 |

