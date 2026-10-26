---
title: "लाइसेंस"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "घटक को लाइसेंस करने और उसकी पूरी कार्यक्षमता को अनलॉक करने के लिए मेथड्स प्रदान करता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.viewer/license/
---
**Inheritance:**
java.lang.Object
```
public class License
```

घटक को लाइसेंस करने और उसकी पूरी कार्यक्षमता को अनलॉक करने के लिए मेथड्स प्रदान करता है।

License क्लास आपको GroupDocs.Viewer घटक पर एक वैध लाइसेंस लागू करने की अनुमति देती है, जिससे आप सभी सुविधाओं का उपयोग कर सकते हैं और किसी भी मूल्यांकन प्रतिबंध को हटा सकते हैं।

उदाहरण उपयोग:

```

 License license = new License();
 license.setLicense("path/to/license/file.lic");
 
```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [License()](#License--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [resetLicense()](#resetLicense--) |  |
| [setLicense(InputStream licenseStream)](#setLicense-java.io.InputStream-) | घटक को लाइसेंस देता है। |
| [setLicense(Path licensePath)](#setLicense-java.nio.file.Path-) | घटक को लाइसेंस देता है। |
| [setLicense(String licensePath)](#setLicense-java.lang.String-) | घटक को लाइसेंस देता है। |
| [setLicense(URL licenseUri)](#setLicense-java.net.URL-) | घटक को लाइसेंस देता है। |
| [isLicensed()](#isLicensed--) |  |
### License() {#License--}
```
public License()
```


### resetLicense() {#resetLicense--}
```
public static void resetLicense()
```




### setLicense(InputStream licenseStream) {#setLicense-java.io.InputStream-}
```
public final void setLicense(InputStream licenseStream)
```


घटक को लाइसेंस देता है।

निम्नलिखित उदाहरण दिखाता है कि लाइसेंस फ़ाइल की InputStream पास करके लाइसेंस कैसे सेट किया जाए।

लाइसेंसिंग के बारे में अधिक जानकारी के लिए कृपया [GroupDocs Licensing FAQ][] देखें। आप [Evaluation Limitations and Licensing][] दस्तावेज़ में GroupDocs.Viewer लाइसेंसिंग के विस्तृत विवरण भी पा सकते हैं।

**Example:**

```

 FileInputStream licenseStream = new FileInputStream("LicenseFile.lic");
 License license = new License();
 license.setLicense(licenseStream);
 
```


[GroupDocs Licensing FAQ]: https://purchase.groupdocs.com/faqs/licensing
[Evaluation Limitations and Licensing]: https://docs.groupdocs.com/display/viewernet/Evaluation+Limitations+and+Licensing+of+GroupDocs.Viewer

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licenseStream | java.io.InputStream | लाइसेंस स्ट्रीम। |

### setLicense(Path licensePath) {#setLicense-java.nio.file.Path-}
```
public final void setLicense(Path licensePath)
```


घटक को लाइसेंस देता है।

निर्दिष्ट लाइसेंस पथ का उपयोग करके घटक के लिए लाइसेंस सेट करता है।

**Note:** This method should be called before using any functionality of the component.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licensePath | java.nio.file.Path | लाइसेंस पथ। |

### setLicense(String licensePath) {#setLicense-java.lang.String-}
```
public final void setLicense(String licensePath)
```


घटक को लाइसेंस देता है।

इस मेथड को किसी भी कार्यक्षमता का उपयोग करने से पहले कॉल किया जाना चाहिए।

उदाहरण उपयोग:

```

 String licensePath = "GroupDocs.Viewer.lic";
 License license = new License();
 license.setLicense(licensePath);
 
```

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licensePath | java.lang.String | लाइसेंस पथ या URL। |

### setLicense(URL licenseUri) {#setLicense-java.net.URL-}
```
public void setLicense(URL licenseUri)
```


घटक को लाइसेंस देता है।

इस मेथड को किसी भी कार्यक्षमता का उपयोग करने से पहले कॉल किया जाना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| licenseUri | java.net.URL | लाइसेंस URI। |

### isLicensed() {#isLicensed--}
```
public final boolean isLicensed()
```




**Returns:**
boolean
