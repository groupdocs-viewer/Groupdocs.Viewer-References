---
title: "Mesuré"
second_title: "Référence API de GroupDocs.Viewer pour Java"
description: "Fournit des méthodes pour appliquer une licence à compteurs au composant GroupDocs.Viewer."
type: docs
weight: 11
url: /fr/java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Fournit des méthodes pour appliquer une licence à compteurs au composant GroupDocs.Viewer.


La licence mesurée vous permet de surveiller et de contrôler dynamiquement l'utilisation de GroupDocs.Viewer en fonction du nombre de pages de documents traitées, au lieu d'une licence traditionnelle par serveur ou par développeur.
Ce modèle de licence flexible convient aux scénarios où les besoins de traitement des documents varient dans le temps ou lorsque vous ne souhaitez payer que pour ce que vous utilisez.


Exemple d'utilisation :

````

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
````


## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Metered()](#Metered--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Récupère la quantité de mégaoctets (MB) traités. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Récupère le nombre de crédits consommés. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Active le produit avec des clés mesurées. |
|
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Récupère la quantité de mégaoctets (MB) traités.


Cette méthode renvoie la quantité totale de MB traités par le composant.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
````



**Returns:**
double - la quantité de MB traités.

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Récupère le nombre de crédits consommés.


Cette méthode renvoie le nombre total de crédits consommés par le composant.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
````



**Returns:**
double - le nombre de crédits consommés.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Active le produit avec des clés mesurées.


L'exemple suivant montre comment activer le produit avec des clés mesurées.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | publicKey | java.lang.String | La clé publique. |
|
|  | privateKey | java.lang.String | La clé privée. |
|

