---
title: "Medido"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona métodos para aplicar una licencia medida al componente GroupDocs.Viewer."
type: docs
weight: 11
url: /es/java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Proporciona métodos para aplicar una licencia medida al componente GroupDocs.Viewer.


La licencia medida permite monitorear y controlar dinámicamente el uso de GroupDocs.Viewer basado en el número de páginas de documentos procesadas en lugar de una licencia tradicional por servidor o por desarrollador.
Este modelo de licencia flexible es adecuado para escenarios donde los requisitos de procesamiento de documentos varían con el tiempo o cuando desea pagar solo por lo que usa.


Ejemplo de uso:

````

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
| [Metered()](#Metered--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Recupera la cantidad de megabytes (MB) procesados. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Recupera el recuento de créditos consumidos. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Activa el producto con claves Medidas. |
|
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Recupera la cantidad de megabytes (MB) procesados.


Este método devuelve la cantidad total de MB procesados por el componente.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
````



**Returns:**
double - la cantidad de MB procesados.

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Recupera el recuento de créditos consumidos.


Este método devuelve el recuento total de créditos consumidos por el componente.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
````



**Returns:**
double - el recuento de créditos consumidos.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Activa el producto con claves Medidas.


El siguiente ejemplo muestra cómo activar el producto con claves Medidas.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | publicKey | java.lang.String | La clave pública. |
|
|  | privateKey | java.lang.String | La clave privada. |
|

