---
title: "Permissions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "PDF दस्तावेज़ अनुमतियों को परिभाषित करता है।"
type: docs
weight: 24
url: /hi/nodejs-java/com.groupdocs.viewer.options/permissions/
---
**Inheritance:**
java.lang.Object
```
public class Permissions
```

PDF दस्तावेज़ अनुमतियों को परिभाषित करता है।

Permissions क्लास उन स्थिरांक (constants) को प्रदान करती है जो GroupDocs.Viewer घटक में PDF दस्तावेज़ पर लागू किए जा सकने वाले विभिन्न अनुमतियों का प्रतिनिधित्व करती हैं। ये अनुमतियां PDF दस्तावेज़ पर किए जा सकने वाले कार्यों को नियंत्रित करती हैं, जैसे प्रिंटिंग, टेक्स्ट कॉपी करना, एनोटेशन संशोधित करना, आदि।

उदाहरण उपयोग:

```

 int permissions = Permissions.DENY_PRINTING | Permissions.DENY_MODIFICATION;
 final Security security = new Security();
 security.setPermissions(permissions);
 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Permissions()](#Permissions--) |  |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [ALLOW_ALL](#ALLOW-ALL) | प्रिंटिंग, संशोधन और डेटा निष्कर्षण की अनुमति दें। |
| [DENY_PRINTING](#DENY-PRINTING) | प्रिंटिंग को अस्वीकार करें। |
| [DENY_MODIFICATION](#DENY-MODIFICATION) | सामग्री संशोधन, फ़ॉर्म भरना, एनोटेशन जोड़ना या संशोधित करना अस्वीकार करें। |
| [DENY_DATA_EXTRACTION](#DENY-DATA-EXTRACTION) | टेक्स्ट और ग्राफ़िक्स निष्कर्षण को अस्वीकार करें। |
| [DENY_ALL](#DENY-ALL) | प्रिंटिंग, संशोधन और डेटा निष्कर्षण को अस्वीकार करें। |
### Permissions() {#Permissions--}
```
public Permissions()
```


### ALLOW_ALL {#ALLOW-ALL}
```
public static final int ALLOW_ALL
```


प्रिंटिंग, संशोधन और डेटा निष्कर्षण की अनुमति दें।

### DENY_PRINTING {#DENY-PRINTING}
```
public static final int DENY_PRINTING
```


प्रिंटिंग को अस्वीकार करें।

### DENY_MODIFICATION {#DENY-MODIFICATION}
```
public static final int DENY_MODIFICATION
```


सामग्री संशोधन, फ़ॉर्म भरना, एनोटेशन जोड़ना या संशोधित करना अस्वीकार करें।

### DENY_DATA_EXTRACTION {#DENY-DATA-EXTRACTION}
```
public static final int DENY_DATA_EXTRACTION
```


टेक्स्ट और ग्राफ़िक्स निष्कर्षण को अस्वीकार करें।

### DENY_ALL {#DENY-ALL}
```
public static final int DENY_ALL
```


प्रिंटिंग, संशोधन और डेटा निष्कर्षण को अस्वीकार करें।

