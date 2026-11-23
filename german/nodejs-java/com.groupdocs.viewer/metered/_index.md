---
title: "Metered"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt Methoden zum Anwenden einer nutzungsbasierten Lizenz auf die GroupDocs.Viewer-Komponente bereit."
type: docs
weight: 11
url: /de/nodejs-java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Stellt Methoden zum Anwenden einer nutzungsbasierten Lizenz auf die GroupDocs.Viewer-Komponente bereit.

Metered-Lizenzierung ermöglicht es Ihnen, die Nutzung von GroupDocs.Viewer dynamisch zu überwachen und zu steuern, basierend auf der Anzahl der verarbeiteten Dokumentseiten, anstatt einer traditionellen Lizenz pro Server oder pro Entwickler. Dieses flexible Lizenzmodell ist für Szenarien geeignet, in denen die Anforderungen an die Dokumentenverarbeitung im Laufe der Zeit variieren oder wenn Sie nur für das bezahlen möchten, was Sie nutzen.

Beispielhafte Verwendung:

```

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Metered()](#Metered--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Ruft die Menge der verarbeiteten Megabytes (MB) ab. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Ruft die Anzahl der verbrauchten Credits ab. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Aktiviert das Produkt mit Metered-Schlüsseln. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Ruft die Menge der verarbeiteten Megabytes (MB) ab.

Diese Methode gibt die gesamte Menge an MB zurück, die von der Komponente verarbeitet wurde.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
```

**Returns:**
double – die Menge der verarbeiteten MB.
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Ruft die Anzahl der verbrauchten Credits ab.

Diese Methode gibt die gesamte Anzahl der von der Komponente verbrauchten Credits zurück.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
```

**Returns:**
double – die Anzahl der verbrauchten Credits.
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Aktiviert das Produkt mit Metered-Schlüsseln.

Das folgende Beispiel zeigt, wie das Produkt mit Metered-Schlüsseln aktiviert wird.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
```

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| publicKey | java.lang.String | Der öffentliche Schlüssel. |
| privateKey | java.lang.String | Der private Schlüssel. |

