---
title: Metered
second_title: GroupDocs.Viewer for Java API Reference
description: Provides methods for applying metered license to the GroupDocs.Viewer component.
type: docs
weight: 11
url: /java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Provides methods for applying metered license to the GroupDocs.Viewer component.

Metered licensing allows you to dynamically monitor and control the usage of GroupDocs.Viewer based on the number of document pages processed instead of a traditional per-server or per-developer license. This flexible licensing model is suitable for scenarios where the document processing requirements vary over time or when you want to pay only for what you use.

Example usage:

```

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Retrieves the amount of megabytes (MB) processed. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Retrieves the count of credits consumed. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Activates the product with Metered keys. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Retrieves the amount of megabytes (MB) processed.

This method returns the total amount of MB processed by the component.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
```

**Returns:**
double - the amount of MB processed.
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Retrieves the count of credits consumed.

This method returns the total count of credits consumed by the component.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
```

**Returns:**
double - the count of credits consumed.
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Activates the product with Metered keys.

Following example demonstrates how to activate product with Metered keys.

**Example:**

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

