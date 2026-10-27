---
title: "Metered"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Предоставляет методы применения измеряемой лицензии к компоненту GroupDocs.Viewer."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Предоставляет методы применения измеряемой лицензии к компоненту GroupDocs.Viewer.

Лицензирование по метрике позволяет динамически отслеживать и контролировать использование GroupDocs.Viewer на основе количества обработанных страниц документов вместо традиционной лицензии на сервер или разработчика. Эта гибкая модель лицензирования подходит для сценариев, когда требования к обработке документов меняются со временем, или когда вы хотите платить только за фактическое использование.

Пример использования:

```

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Metered()](#Metered--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Получает количество мегабайт (MB), обработанных. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Получает количество использованных кредитов. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Активирует продукт с измеряемыми ключами. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Получает количество мегабайт (MB), обработанных.

Этот метод возвращает общее количество мегабайт (MB), обработанных компонентом.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
```

**Returns:**
double — количество обработанных мегабайт.
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Получает количество использованных кредитов.

Этот метод возвращает общее количество использованных кредитов компонентом.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
```

**Returns:**
double — количество использованных кредитов.
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Активирует продукт с измеряемыми ключами.

Следующий пример демонстрирует, как активировать продукт с измеряемыми ключами.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
```

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| publicKey | java.lang.String | Публичный ключ. |
| privateKey | java.lang.String | Приватный ключ. |

