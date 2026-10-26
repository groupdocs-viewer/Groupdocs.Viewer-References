---
title: "Metered"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يوفر طرقًا لتطبيق ترخيص مقنن على مكوّن GroupDocs.Viewer."
type: docs
weight: 11
url: /ar/nodejs-java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

يوفر طرقًا لتطبيق ترخيص مقنن على مكوّن GroupDocs.Viewer.

يسمح الترخيص القائم على الاستخدام (Metered) لك بمراقبة والتحكم ديناميكياً في استخدام GroupDocs.Viewer بناءً على عدد صفحات المستند التي تم معالجتها بدلاً من ترخيص تقليدي لكل خادم أو لكل مطور. هذا النموذج المرن للترخيص مناسب للسيناريوهات التي تتغير فيها متطلبات معالجة المستندات بمرور الوقت أو عندما تريد الدفع فقط مقابل ما تستخدمه.

مثال على الاستخدام:

```

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [Metered()](#Metered--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | يسترجع مقدار الميجابايت (MB) المعالجة. |
| [getConsumptionCredit()](#getConsumptionCredit--) | يسترجع عدد الأرصدة المستهلكة. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | يفعل المنتج باستخدام مفاتيح القياس. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


يسترجع مقدار الميجابايت (MB) المعالجة.

تُعيد هذه الطريقة إجمالي مقدار الميجابايت المعالجة بواسطة المكوّن.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
```

**Returns:**
double - مقدار الميجابايت المعالجة.
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


يسترجع عدد الأرصدة المستهلكة.

تُعيد هذه الطريقة إجمالي عدد الأرصدة المستهلكة بواسطة المكوّن.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
```

**Returns:**
double - عدد الأرصدة المستهلكة.
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


يفعل المنتج باستخدام مفاتيح القياس.

المثال التالي يوضح كيفية تفعيل المنتج باستخدام مفاتيح القياس.

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| publicKey | java.lang.String | المفتاح العام. |
| privateKey | java.lang.String | المفتاح الخاص. |

