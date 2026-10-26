---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "व्यूअर घटक के व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।"
type: docs
weight: 13
url: /hi/nodejs-java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

व्यूअर घटक के व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।

ViewerSettings क्लास दस्तावेज़ रेंडरिंग प्रक्रिया के दौरान GroupDocs.Viewer घटक के व्यवहार को अनुकूलित करने के लिए विकल्प और गुण प्रदान करती है। आप इस क्लास का उपयोग विभिन्न सेटिंग्स, जैसे logger, कस्टम कैश इम्प्लीमेंटेशन, और अधिक, निर्दिष्ट करने के लिए कर सकते हैं।

उदाहरण उपयोग:

```

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | ViewerSettings क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | ViewerSettings क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | ViewerSettings क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [ViewerSettings()](#ViewerSettings--) | ViewerSettings क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getLogger()](#getLogger--) | लॉगिंग (Errors, Warnings, Traces) के लिए उपयोग की जाने वाली logger इम्प्लीमेंटेशन प्राप्त करता है। |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | लॉगिंग (Errors, Warnings, Traces) के लिए उपयोग की जाने वाली logger इम्प्लीमेंटेशन सेट करता है। |
| [getCache()](#getCache--) | रेंडरिंग परिणामों को संग्रहीत करने के लिए उपयोग की जाने वाली कैश इम्प्लीमेंटेशन प्राप्त करता है। |
| [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | रेंडरिंग परिणामों को संग्रहीत करने के लिए उपयोग की जाने वाली कैश इम्प्लीमेंटेशन सेट करता है। |
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


ViewerSettings क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | कैश। |
| लॉगर | com.groupdocs.foundation.logging.ILogger | logger। |

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


ViewerSettings क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| लॉगर | com.groupdocs.foundation.logging.ILogger | logger। |

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


ViewerSettings क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | कैश। |

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


ViewerSettings क्लास का एक नया इंस्टेंस प्रारंभ करता है।

### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


लॉगिंग (Errors, Warnings, Traces) के लिए उपयोग की जाने वाली logger इम्प्लीमेंटेशन प्राप्त करता है।

**Returns:**
com.groupdocs.foundation.logging.ILogger - logger इम्प्लीमेंटेशन।
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


लॉगिंग (Errors, Warnings, Traces) के लिए उपयोग की जाने वाली logger इम्प्लीमेंटेशन सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| लॉगर | com.groupdocs.foundation.logging.ILogger | सेट करने के लिए logger इम्प्लीमेंटेशन। |

### getCache() {#getCache--}
```
public final Cache getCache()
```


रेंडरिंग परिणामों को संग्रहीत करने के लिए उपयोग की जाने वाली कैश इम्प्लीमेंटेशन प्राप्त करता है।

**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.
### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


रेंडरिंग परिणामों को संग्रहीत करने के लिए उपयोग की जाने वाली कैश इम्प्लीमेंटेशन सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cache | [Cache](../../com.groupdocs.viewer.caching/cache) | कैश इम्प्लीमेंटेशन। |

