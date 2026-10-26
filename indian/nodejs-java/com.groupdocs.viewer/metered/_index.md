---
title: "मेटर्ड"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "GroupDocs.Viewer घटक पर मीटरड लाइसेंस लागू करने के लिए मेथड्स प्रदान करता है।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.viewer/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

GroupDocs.Viewer घटक पर मीटरड लाइसेंस लागू करने के लिए मेथड्स प्रदान करता है।

मेटर्ड लाइसेंसिंग आपको पारंपरिक प्रति‑सर्वर या प्रति‑डेवलपर लाइसेंस के बजाय प्रोसेस किए गए दस्तावेज़ पृष्ठों की संख्या के आधार पर GroupDocs.Viewer के उपयोग की गतिशील रूप से निगरानी और नियंत्रण करने की अनुमति देता है। यह लचीला लाइसेंसिंग मॉडल उन परिस्थितियों के लिए उपयुक्त है जहाँ दस्तावेज़ प्रोसेसिंग आवश्यकताएँ समय के साथ बदलती रहती हैं या जब आप केवल उपयोग के अनुसार भुगतान करना चाहते हैं।

उदाहरण उपयोग:

```

 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 // Perform document processing operations using GroupDocs.Viewer
 // ...
 
```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Metered()](#Metered--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | प्रोसेस किए गए मेगाबाइट्स (MB) की मात्रा प्राप्त करता है। |
| [getConsumptionCredit()](#getConsumptionCredit--) | उपभोग किए गए क्रेडिट्स की गिनती प्राप्त करता है। |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Metered कुंजियों के साथ उत्पाद को सक्रिय करता है। |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


प्रोसेस किए गए मेगाबाइट्स (MB) की मात्रा प्राप्त करता है।

यह मेथड घटक द्वारा प्रोसेस किए गए कुल MB की मात्रा लौटाता है।

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double mbProcessed = Metered.getConsumptionQuantity();
 
```

**Returns:**
double - प्रोसेस किए गए MB की मात्रा।
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


उपभोग किए गए क्रेडिट्स की गिनती प्राप्त करता है।

यह मेथड घटक द्वारा उपभोग किए गए कुल क्रेडिट्स की गिनती लौटाता है।

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 double creditsConsumed = Metered.getConsumptionCredit();
 
```

**Returns:**
double - उपभोग किए गए क्रेडिट्स की गिनती।
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public final void setMeteredKey(String publicKey, String privateKey)
```


Metered कुंजियों के साथ उत्पाद को सक्रिय करता है।

निम्न उदाहरण दिखाता है कि Metered कुंजियों के साथ उत्पाद को कैसे सक्रिय किया जाए।

**Example:**

```

 String publicKey = "Public Key";
 String privateKey = "Private Key";
 Metered metered = new Metered();
 metered.setMeteredKey(publicKey, privateKey);
 
```

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| publicKey | java.lang.String | सार्वजनिक कुंजी। |
| privateKey | java.lang.String | निजी कुंजी। |

