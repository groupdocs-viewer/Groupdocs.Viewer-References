---
title: "ViewerSettings"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "Viewer घटक के व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Viewer घटक के व्यवहार को अनुकूलित करने के लिए सेटिंग्स को परिभाषित करता है।


ViewerSettings क्लास दस्तावेज़ रेंडरिंग प्रक्रिया के दौरान GroupDocs.Viewer घटक के व्यवहार को अनुकूलित करने के लिए विकल्प और गुण प्रदान करती है।
आप इस क्लास का उपयोग विभिन्न सेटिंग्स, जैसे लॉगर, कस्टम कैश इम्प्लीमेंटेशन, आदि निर्दिष्ट करने के लिए कर सकते हैं।


उदाहरण उपयोग:

````

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | नए उदाहरण को प्रारंभ करता है |
ViewerSettings
class।
|
|  | [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | नए उदाहरण को प्रारंभ करता है |
ViewerSettings
class।
|
|  | [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | नए उदाहरण को प्रारंभ करता है |
ViewerSettings
class।
|
|  | [ViewerSettings()](#ViewerSettings--) | नए उदाहरण को प्रारंभ करता है |
ViewerSettings
class।
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [getLogger()](#getLogger--) | लॉगिंग (त्रुटियाँ, चेतावनियाँ, ट्रेस) के लिए उपयोग किए जाने वाले लॉगर इम्प्लीमेंटेशन को प्राप्त करता है। |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | लॉगिंग (त्रुटियाँ, चेतावनियाँ, ट्रेस) के लिए उपयोग किए जाने वाले लॉगर इम्प्लीमेंटेशन को सेट करता है। |
|
|  | [getCache()](#getCache--) | रेंडरिंग परिणामों को संग्रहीत करने के लिए उपयोग किए जाने वाले कैश इम्प्लीमेंटेशन को प्राप्त करता है। |
|
|  | [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | रेंडरिंग परिणामों को संग्रहीत करने के लिए उपयोग किए जाने वाले कैश इम्प्लीमेंटेशन को सेट करता है। |
|
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


नए उदाहरण को प्रारंभ करता है
ViewerSettings
class।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | कैश। |
|
|  | लॉगर | com.groupdocs.foundation.logging.ILogger | लॉगर। |
|

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


नए उदाहरण को प्रारंभ करता है
ViewerSettings
class।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | लॉगर | com.groupdocs.foundation.logging.ILogger | लॉगर। |
|

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


नए उदाहरण को प्रारंभ करता है
ViewerSettings
class।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | कैश। |
|

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


नए उदाहरण को प्रारंभ करता है
ViewerSettings
class।


### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


लॉगिंग (त्रुटियाँ, चेतावनियाँ, ट्रेस) के लिए उपयोग किए जाने वाले लॉगर इम्प्लीमेंटेशन को प्राप्त करता है।


**Returns:**
com.groupdocs.foundation.logging.ILogger - लॉगर इम्प्लीमेंटेशन।

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


लॉगिंग (त्रुटियाँ, चेतावनियाँ, ट्रेस) के लिए उपयोग किए जाने वाले लॉगर इम्प्लीमेंटेशन को सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | लॉगर | com.groupdocs.foundation.logging.ILogger | सेट करने के लिए लॉगर इम्प्लीमेंटेशन। |
|

### getCache() {#getCache--}
```
public final Cache getCache()
```


रेंडरिंग परिणामों को संग्रहीत करने के लिए उपयोग किए जाने वाले कैश इम्प्लीमेंटेशन को प्राप्त करता है।


**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.

### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


रेंडरिंग परिणामों को संग्रहीत करने के लिए उपयोग किए जाने वाले कैश इम्प्लीमेंटेशन को सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | कैश कार्यान्वयन। |
|

