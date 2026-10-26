---
title: "计量"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "提供将计量授权应用于 GroupDocs.Viewer 组件的方法。"
type: docs
weight: 11
url: /zh/nodejs-java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

提供将计量授权应用于 GroupDocs.Viewer 组件的方法。

计量授权允许您基于处理的文档页数动态监控和控制 GroupDocs.Viewer 的使用，而不是传统的每服务器或每开发者授权。此灵活的授权模式适用于文档处理需求随时间变化的场景，或当您只想为实际使用的部分付费时。

示例用法：

```

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Metered()](#Metered--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 检索已处理的兆字节 (MB) 数量。 |
| [getConsumptionCredit()](#getConsumptionCredit--) | 检索已消耗的积分数量。 |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 使用计量密钥激活产品。 |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


检索已处理的兆字节 (MB) 数量。

此方法返回组件已处理的 MB 总量。

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
```

**Returns:**
double - 已处理的 MB 数量。
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


检索已消耗的积分数量。

此方法返回组件已消耗的积分总数。

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
```

**Returns:**
double - 已消耗的积分数量。
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


使用计量密钥激活产品。

以下示例演示如何使用计量密钥激活产品。

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| publicKey | java.lang.String | 公共密钥。 |
| privateKey | java.lang.String | 私有密钥。 |

