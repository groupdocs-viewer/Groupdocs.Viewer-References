---
title: "Metered"
second_title: "GroupDocs.Viewer voor Node.js via Java API-referentie"
description: "Biedt methoden voor het toepassen van een meterlicentie op het GroupDocs.Viewer-component."
type: docs
weight: 11
url: /nl/nodejs-java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Biedt methoden voor het toepassen van een meterlicentie op het GroupDocs.Viewer-component.

Metered-licenties stellen u in staat om dynamisch het gebruik van GroupDocs.Viewer te monitoren en te beheersen op basis van het aantal verwerkte documentpagina's in plaats van een traditionele per-server- of per-ontwikkelaar-licentie. Dit flexibele licentiemodel is geschikt voor scenario's waarin de documentverwerkingsvereisten in de loop van de tijd variëren of wanneer u alleen wilt betalen voor wat u gebruikt.

Voorbeeldgebruik:

```

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Metered()](#Metered--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Haalt de hoeveelheid megabytes (MB) die verwerkt zijn op. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Haalt het aantal verbruikte credits op. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Activeert het product met Metered-sleutels. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Haalt de hoeveelheid megabytes (MB) die verwerkt zijn op.

Deze methode retourneert de totale hoeveelheid MB die door de component is verwerkt.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
```

**Returns:**
double - de hoeveelheid MB die verwerkt is.
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Haalt het aantal verbruikte credits op.

Deze methode retourneert het totale aantal verbruikte credits door de component.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
```

**Returns:**
double - het aantal verbruikte credits.
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Activeert het product met Metered-sleutels.

Het volgende voorbeeld laat zien hoe je het product met Metered-sleutels activeert.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| publicKey | java.lang.String | De openbare sleutel. |
| privateKey | java.lang.String | De privésleutel. |

