---
title: "Mätad"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Tillhandahåller metoder för att tillämpa mätlicens på GroupDocs.Viewer-komponenten."
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Tillhandahåller metoder för att tillämpa mätlicens på GroupDocs.Viewer-komponenten.

Mätad licensiering gör det möjligt att dynamiskt övervaka och kontrollera användningen av GroupDocs.Viewer baserat på antalet bearbetade dokumentsidor istället för en traditionell per‑server‑ eller per‑utvecklarlicens. Denna flexibla licensieringsmodell är lämplig för scenarier där dokumentbehandlingsbehoven varierar över tid eller när du vill betala endast för det du använder.

Exempel på användning:

```

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Metered()](#Metered--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Hämtar mängden megabyte (MB) som bearbetats. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Hämtar antalet krediter som förbrukats. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Aktiverar produkten med Metered-nycklar. |
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

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
```

**Returns:**
double - mängden MB som bearbetats.
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Hämtar antalet krediter som förbrukats.

Denna metod returnerar det totala antalet krediter som komponenten har förbrukat.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
```

**Returns:**
double - antalet krediter som förbrukats.
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Aktiverar produkten med Metered-nycklar.

Följande exempel visar hur man aktiverar produkten med Metered-nycklar.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
```

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicKey | java.lang.String | Den offentliga nyckeln. |
| privateKey | java.lang.String | Den privata nyckeln. |

