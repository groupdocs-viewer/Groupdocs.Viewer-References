---
title: "A consumo"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Fornisce metodi per applicare una licenza a consumo al componente GroupDocs.Viewer."
type: docs
weight: 11
url: /it/nodejs-java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Fornisce metodi per applicare una licenza a consumo al componente GroupDocs.Viewer.

La licenza a consumo consente di monitorare e controllare dinamicamente l'utilizzo di GroupDocs.Viewer in base al numero di pagine di documento elaborate, invece di una licenza tradizionale per server o per sviluppatore. Questo modello di licenza flessibile è adatto a scenari in cui le esigenze di elaborazione dei documenti variano nel tempo o quando si desidera pagare solo per ciò che si utilizza.

Esempio di utilizzo:

```

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Metered()](#Metered--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Recupera la quantità di megabyte (MB) elaborati. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Recupera il conteggio dei crediti consumati. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Attiva il prodotto con chiavi a consumo. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Recupera la quantità di megabyte (MB) elaborati.

Questo metodo restituisce la quantità totale di MB elaborati dal componente.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
```

**Returns:**
double - la quantità di MB elaborati.
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Recupera il conteggio dei crediti consumati.

Questo metodo restituisce il conteggio totale dei crediti consumati dal componente.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
```

**Returns:**
double - il conteggio dei crediti consumati.
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Attiva il prodotto con chiavi a consumo.

L'esempio seguente dimostra come attivare il prodotto con chiavi a consumo.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| publicKey | java.lang.String | La chiave pubblica. |
| privateKey | java.lang.String | La chiave privata. |

