---
title: "Счётный"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Предоставляет методы для применения метрической лицензии к компоненту GroupDocs.Viewer."
type: docs
weight: 11
url: /ru/java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Предоставляет методы для применения метрической лицензии к компоненту GroupDocs.Viewer.


Metered лицензирование позволяет вам динамически контролировать и отслеживать использование GroupDocs.Viewer на основе количества обработанных страниц документов вместо традиционной лицензии на сервер или разработчика.
Эта гибкая модель лицензирования подходит для сценариев, когда требования к обработке документов меняются со временем, или когда вы хотите платить только за то, что используете.


Пример использования:

````

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Metered()](#Metered--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | Возвращает количество обработанных мегабайт (MB). |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | Возвращает количество использованных кредитов. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Активирует продукт с помощью Metered ключей. |
|
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Возвращает количество обработанных мегабайт (MB).


Этот метод возвращает общее количество обработанных MB компонентом.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
````



**Returns:**
double - количество обработанных MB.

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Возвращает количество использованных кредитов.


Этот метод возвращает общее количество использованных кредитов компонентом.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
````



**Returns:**
double - количество использованных кредитов.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Активирует продукт с помощью Metered ключей.


Следующий пример демонстрирует, как активировать продукт с Metered ключами.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | publicKey | java.lang.String | Публичный ключ. |
|
|  | privateKey | java.lang.String | Приватный ключ. |
|

