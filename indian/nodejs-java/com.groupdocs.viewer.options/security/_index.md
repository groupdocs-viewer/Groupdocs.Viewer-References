---
title: "Security"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "PDF दस्तावेज़ सुरक्षा विकल्प प्रदान करता है।"
type: docs
weight: 29
url: /hi/nodejs-java/com.groupdocs.viewer.options/security/
---
**Inheritance:**
java.lang.Object
```
public class Security
```

PDF दस्तावेज़ सुरक्षा विकल्प प्रदान करता है।

Security क्लास विभिन्न सेटिंग्स और विकल्पों को समाहित करती है जिन्हें GroupDocs.Viewer घटक में PDF दस्तावेज़ पर सुरक्षा उपाय लागू करने के लिए उपयोग किया जा सकता है। इन विकल्पों में पासवर्ड सुरक्षा, अनुमतियाँ, और अधिक शामिल हैं। विवरण के लिए, देखें [documentation][].

उदाहरण उपयोग:

```

 Security security = new Security();
 security.setDocumentOpenPassword("myPassword");
 security.setPermissions(Permissions.DENY_MODIFICATION);

 final PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setSecurity(security);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Security()](#Security--) | Security क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getDocumentOpenPassword()](#getDocumentOpenPassword--) | PDF दस्तावेज़ खोलने के लिए आवश्यक पासवर्ड प्राप्त करता है। |
| [setDocumentOpenPassword(String value)](#setDocumentOpenPassword-java.lang.String-) | PDF दस्तावेज़ खोलने के लिए आवश्यक पासवर्ड सेट करता है। |
| [getPermissionsPassword()](#getPermissionsPassword--) | अनुमति सेटिंग्स बदलने के लिए आवश्यक पासवर्ड प्राप्त करता है। |
| [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | अनुमति सेटिंग्स बदलने के लिए आवश्यक पासवर्ड सेट करता है। |
| [getPermissions()](#getPermissions--) | PDF दस्तावेज़ अनुमतियों को प्राप्त करता है जैसे प्रिंटिंग, संशोधन, और डेटा निष्कर्षण। |
| [setPermissions(int value)](#setPermissions-int-) | PDF दस्तावेज़ अनुमतियों को सेट करता है जैसे प्रिंटिंग, संशोधन, और डेटा निष्कर्षण। |
### Security() {#Security--}
```
public Security()
```


Security क्लास का एक नया इंस्टेंस प्रारंभ करता है।

### getDocumentOpenPassword() {#getDocumentOpenPassword--}
```
public final String getDocumentOpenPassword()
```


PDF दस्तावेज़ खोलने के लिए आवश्यक पासवर्ड प्राप्त करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - दस्तावेज़ खोलने का पासवर्ड।
### setDocumentOpenPassword(String value) {#setDocumentOpenPassword-java.lang.String-}
```
public final void setDocumentOpenPassword(String value)
```


PDF दस्तावेज़ खोलने के लिए आवश्यक पासवर्ड सेट करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String | दस्तावेज़ खोलने का पासवर्ड। |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


अनुमति सेटिंग्स बदलने के लिए आवश्यक पासवर्ड प्राप्त करता है।

एक अनुमतियों पासवर्ड का उपयोग करके, आप प्रिंटिंग, संशोधन, और डेटा निष्कर्षण को प्रतिबंधित कर सकते हैं। प्रिंटिंग, संशोधन और डेटा निष्कर्षण को प्रतिबंधित करने के लिए एक अनुमतियों पासवर्ड का उपयोग करें। कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
java.lang.String - अनुमतियों पासवर्ड।
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


अनुमति सेटिंग्स बदलने के लिए आवश्यक पासवर्ड सेट करता है।

एक अनुमतियों पासवर्ड का उपयोग करके, आप प्रिंटिंग, संशोधन, और डेटा निष्कर्षण को प्रतिबंधित कर सकते हैं। प्रिंटिंग, संशोधन और डेटा निष्कर्षण को प्रतिबंधित करने के लिए एक अनुमतियों पासवर्ड का उपयोग करें। कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String | अनुमतियों पासवर्ड। |

### getPermissions() {#getPermissions--}
```
public final int getPermissions()
```


PDF दस्तावेज़ अनुमतियों को प्राप्त करता है जैसे प्रिंटिंग, संशोधन, और डेटा निष्कर्षण।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
int - PDF दस्तावेज़ अनुमतियाँ।
### setPermissions(int value) {#setPermissions-int-}
```
public final void setPermissions(int value)
```


PDF दस्तावेज़ अनुमतियों को सेट करता है जैसे प्रिंटिंग, संशोधन, और डेटा निष्कर्षण।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int | PDF दस्तावेज़ अनुमतियाँ। |

