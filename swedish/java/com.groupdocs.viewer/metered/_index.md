---
title: "Måttbaserad"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Tillhandahåller metoder för att tillämpa en mätad licens på GroupDocs.Viewer-komponenten."
type: docs
weight: 11
url: /sv/java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Tillhandahåller metoder för att tillämpa en mätad licens på GroupDocs.Viewer-komponenten.


Måttbaserad licensiering gör det möjligt att dynamiskt övervaka och kontrollera användningen av GroupDocs.Viewer baserat på antalet bearbetade dokumentsidor istället för en traditionell per-server- eller per-utvecklarlicens.
Denna flexibla licensmodell är lämplig för scenarier där dokumentbearbetningsbehoven varierar över tid eller när du vill betala endast för det du använder.


Exempel på användning:

````

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
````


## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Metered()](#Metered--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Hämtar mängden megabyte (MB) som bearbetats. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Hämtar antalet förbrukade krediter. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Aktiverar produkten med måttbaserade nycklar. |
|
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Hämtar mängden megabyte (MB) som bearbetats.


Denna metod returnerar den totala mängden MB som komponenten har bearbetat.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
````



**Returns:**
double - mängden MB som bearbetats.

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Hämtar antalet förbrukade krediter.


Denna metod returnerar det totala antalet krediter som komponenten har förbrukat.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
````



**Returns:**
double - antalet förbrukade krediter.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Aktiverar produkten med måttbaserade nycklar.


Följande exempel visar hur man aktiverar produkten med måttbaserade nycklar.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | publicKey | java.lang.String | Den offentliga nyckeln. |
|
|  | privateKey | java.lang.String | Den privata nyckeln. |
|

