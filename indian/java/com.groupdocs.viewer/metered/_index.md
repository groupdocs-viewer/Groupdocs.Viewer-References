---
title: "मेटर्ड"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "GroupDocs.Viewer घटक पर मीटरयुक्त लाइसेंस लागू करने के लिए विधियाँ प्रदान करता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

GroupDocs.Viewer घटक पर मीटरयुक्त लाइसेंस लागू करने के लिए विधियाँ प्रदान करता है।


मेटर्ड लाइसेंसिंग आपको पारंपरिक प्रति‑सर्वर या प्रति‑डेवलपर लाइसेंस के बजाय प्रोसेस किए गए दस्तावेज़ पृष्ठों की संख्या के आधार पर GroupDocs.Viewer के उपयोग की गतिशील रूप से निगरानी और नियंत्रण करने की अनुमति देती है।
यह लचीला लाइसेंस मॉडल उन परिदृश्यों के लिए उपयुक्त है जहाँ दस्तावेज़ प्रोसेसिंग आवश्यकताएँ समय के साथ बदलती हैं या जब आप केवल उपयोग के अनुसार ही भुगतान करना चाहते हैं।


उदाहरण उपयोग:

````

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
| [Metered()](#Metered--) |  |
## Methods

| Method | विवरण |
| --- | --- |
|  | [getConsumptionQuantity()](#getConsumptionQuantity--) | प्रोसेस किए गए मेगाबाइट (MB) की मात्रा प्राप्त करता है। |
|
|  | [getConsumptionCredit()](#getConsumptionCredit--) | उपयोग किए गए क्रेडिट की गिनती प्राप्त करता है। |
|
|  | [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | मेटर्ड कुंजियों के साथ उत्पाद को सक्रिय करता है। |
|
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


प्रोसेस किए गए मेगाबाइट (MB) की मात्रा प्राप्त करता है।


यह मेथड घटक द्वारा प्रोसेस किए गए कुल MB की मात्रा लौटाता है।

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
````



**Returns:**
double - प्रोसेस किए गए MB की मात्रा।

### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


उपयोग किए गए क्रेडिट की गिनती प्राप्त करता है।


यह मेथड घटक द्वारा उपयोग किए गए कुल क्रेडिट की गिनती लौटाता है।

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
````



**Returns:**
double - उपयोग किए गए क्रेडिट की गिनती।

### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


मेटर्ड कुंजियों के साथ उत्पाद को सक्रिय करता है।


निम्न उदाहरण दिखाता है कि मेटर्ड कुंजियों के साथ उत्पाद को कैसे सक्रिय किया जाए।

**Example:**

````

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
````



**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | publicKey | java.lang.String | सार्वजनिक कुंजी। |
|
|  | privateKey | java.lang.String | निजी कुंजी। |
|

