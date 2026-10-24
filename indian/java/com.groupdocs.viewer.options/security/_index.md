---
title: "Security"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "PDF दस्तावेज़ सुरक्षा विकल्प प्रदान करता है।"
type: docs
weight: 29
url: /hi/java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

PDF दस्तावेज़ सुरक्षा विकल्प प्रदान करता है।


Security क्लास विभिन्न सेटिंग्स और विकल्पों को समाहित करती है जिन्हें सुरक्षा उपाय लागू करने के लिए उपयोग किया जा सकता है।
GroupDocs.Viewer घटक में एक PDF दस्तावेज़ पर। इन विकल्पों में पासवर्ड सुरक्षा शामिल है,
अनुमतियाँ, और अधिक।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


उदाहरण उपयोग:

````

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [Security()](#Security--) | नए उदाहरण को प्रारंभ करता है |
Security
class।
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [getDocumentOpenPassword()](#getDocumentOpenPassword--) | PDF दस्तावेज़ खोलने के लिए आवश्यक पासवर्ड प्राप्त करता है। |
|
|  | [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | PDF दस्तावेज़ खोलने के लिए आवश्यक पासवर्ड सेट करता है। |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | अनुमति सेटिंग्स बदलने के लिए आवश्यक पासवर्ड प्राप्त करता है। |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | अनुमति सेटिंग्स बदलने के लिए आवश्यक पासवर्ड सेट करता है। |
|
|  | [getPermissions()](#getPermissions--) | PDF दस्तावेज़ की अनुमतियाँ प्राप्त करता है जैसे प्रिंटिंग, संशोधन, और डेटा निष्कर्षण। |
|
|  | [setPermissions(int value)](#setPermissions-int-) | PDF दस्तावेज़ की अनुमतियाँ सेट करता है जैसे प्रिंटिंग, संशोधन, और डेटा निष्कर्षण। |
|
### Security() {#Security--}
```
public Security()
```


नए उदाहरण को प्रारंभ करता है
Security
class।


### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


PDF दस्तावेज़ खोलने के लिए आवश्यक पासवर्ड प्राप्त करता है।


कोड नमूने के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - दस्तावेज़ खोलने का पासवर्ड।

### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


PDF दस्तावेज़ खोलने के लिए आवश्यक पासवर्ड सेट करता है।


कोड नमूने के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | दस्तावेज़ खोलने का पासवर्ड। |
|

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


अनुमति सेटिंग्स बदलने के लिए आवश्यक पासवर्ड प्राप्त करता है।


परमिशन पासवर्ड का उपयोग करके, आप प्रिंटिंग, संशोधन, और डेटा निष्कर्षण को प्रतिबंधित कर सकते हैं।
प्रिंटिंग, संशोधन और डेटा निष्कर्षण को प्रतिबंधित करने के लिए एक परमिशन पासवर्ड का उपयोग करें। कोड नमूने के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
java.lang.String - परमिशन पासवर्ड।

### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


अनुमति सेटिंग्स बदलने के लिए आवश्यक पासवर्ड सेट करता है।


परमिशन पासवर्ड का उपयोग करके, आप प्रिंटिंग, संशोधन, और डेटा निष्कर्षण को प्रतिबंधित कर सकते हैं।
प्रिंटिंग, संशोधन और डेटा निष्कर्षण को प्रतिबंधित करने के लिए एक परमिशन पासवर्ड का उपयोग करें। कोड नमूने के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | परमिशन पासवर्ड। |
|

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


PDF दस्तावेज़ की अनुमतियाँ प्राप्त करता है जैसे प्रिंटिंग, संशोधन, और डेटा निष्कर्षण।


कोड नमूने के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
int - PDF दस्तावेज़ की अनुमतियाँ।

### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


PDF दस्तावेज़ की अनुमतियाँ सेट करता है जैसे प्रिंटिंग, संशोधन, और डेटा निष्कर्षण।


कोड नमूने के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | int | PDF दस्तावेज़ की अनुमतियाँ। |
|

