---
title: Metered
second_title: GroupDocs.Viewer for Java API Reference
description: Provides methods for applying Metered license.
type: docs
weight: 11
url: /java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Provides methods for applying [Metered][] license. More about licensing: [GroupDocs Licensing FAQ][] More about GroupDocs.Viewer licensing: [Evaluation Limitations and Licensing][]


[Metered]: https://purchase.groupdocs.com/faqs/licensing/metered
[GroupDocs Licensing FAQ]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/viewer/java/evaluation-limitations-and-licensing-of-groupdocs-viewer/
## Constructors

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Retrieves amount of MBs processed. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Retrieves count of credits consumed. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Activates product with Metered keys. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Retrieves amount of MBs processed.

**Example:** 
Following example demonstrates how to retrieve amount of MBs processed.

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
```

**Returns:**
double
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Retrieves count of credits consumed.

**Example:** 
Following example demonstrates how to retrieve count of credits consumed.

```

   String publicKey = "Public Key";
   String privateKey = "Private Key";

   Metered metered = new Metered();
   metered.setMeteredKey(publicKey, privateKey);
   double creditsConsumed = Metered.getConsumptionCredit();
 
```

**Returns:**
double
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Activates product with Metered keys.

Following example demonstrates how to activate product with Metered keys.

```
String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | The public key. |
| privateKey | java.lang.String | The private key. |

