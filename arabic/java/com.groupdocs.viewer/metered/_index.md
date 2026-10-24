---
title: "مقاس"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر طرقًا لتطبيق ترخيص مقنن على مكوّن GroupDocs.Viewer."
type: docs
weight: 11
url: /ar/java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

يوفر طرقًا لتطبيق ترخيص مقنن على مكوّن GroupDocs.Viewer.


تسمح الترخيص القائم على القياس لك بمراقبة والتحكم الديناميكي في استخدام GroupDocs.Viewer بناءً على عدد صفحات المستند التي تم معالجتها بدلاً من الترخيص التقليدي لكل خادم أو لكل مطور.
هذا النموذج المرن للترخيص مناسب للسيناريوهات التي تتغير فيها متطلبات معالجة المستندات مع مرور الوقت أو عندما ترغب في الدفع فقط مقابل ما تستخدمه.


مثال على الاستخدام:

````

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Metered()](#Metered--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | يسترجع مقدار الميجابايت (MB) المعالجة. |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | يسترجع عدد الأرصدة المستهلكة. |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | يفعل المنتج باستخدام مفاتيح مقاس. |
|
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


يسترجع مقدار الميجابايت (MB) المعالجة.


تُعيد هذه الطريقة إجمالي مقدار الميجابايت (MB) المعالجة بواسطة المكوّن.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
````



**Returns:**
double - مقدار الميجابايت المعالجة.

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


يسترجع عدد الأرصدة المستهلكة.


تُعيد هذه الطريقة إجمالي عدد الأرصدة المستهلكة بواسطة المكوّن.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
````



**Returns:**
double - عدد الأرصدة المستهلكة.

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


يفعل المنتج باستخدام مفاتيح مقاس.


المثال التالي يوضح كيفية تفعيل المنتج باستخدام مفاتيح مقاس.

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | publicKey | java.lang.String | المفتاح العام. |
|
|  | privateKey | java.lang.String | المفتاح الخاص. |
|

