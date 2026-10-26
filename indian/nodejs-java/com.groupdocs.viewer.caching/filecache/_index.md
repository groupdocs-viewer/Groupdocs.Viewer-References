---
title: "FileCache"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "एक स्थानीय ऑन-डिस्क कैश को दर्शाता है।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

एक स्थानीय ऑन-डिस्क कैश को दर्शाता है।

FileCache क्लास GroupDocs.Viewer घटक में स्थानीय ऑन-डिस्क कैश का प्रतिनिधित्व करती है। यह डिस्क पर कैश्ड डेटा को संग्रहीत और पुनः प्राप्त करने की कार्यक्षमता प्रदान करती है जिससे दस्तावेज़ रेंडरिंग कुशल बनती है।

उदाहरण उपयोग:

```

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
```

FileCache का उपयोग करने के लिए, आपको इस क्लास की एक इंस्टेंस बनानी होगी और उसे ViewerSettings ऑब्जेक्ट को पास करना होगा। फिर Viewer ऑब्जेक्ट दस्तावेज़ रेंडरिंग के दौरान कैशिंग उद्देश्यों के लिए FileCache का उपयोग करेगा।

***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer. You can also implement your own custom cache by implementing the Cache interface.*
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | FileCache क्लास की नई इंस्टेंस बनाता है। |
| [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | FileCache क्लास की नई इंस्टेंस बनाता है। |
| [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | FileCache क्लास की नई इंस्टेंस बनाता है। |
| [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | FileCache क्लास की नई इंस्टेंस बनाता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getCachePath()](#getCachePath--) | कैश फ़ोल्डर का सापेक्ष या पूर्ण पथ प्राप्त करता है। |
| [getCacheSubFolder()](#getCacheSubFolder--) | कैश पथ में जोड़ने के लिए उप-फ़ोल्डर। |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | डेटा को स्थानीय डिस्क पर सीरियलाइज़ करता है। |
| [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | यदि मौजूद हो तो इस कुंजी से संबंधित डेटा को डीसीरियलाइज़ करता है। |
| [getKeys(String filter)](#getKeys-java.lang.String-) | फ़ाइलनाम में फ़िल्टर शामिल करने वाली सभी फ़ाइल नामों को लौटाता है। |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


FileCache क्लास की नई इंस्टेंस बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cachePath | java.lang.String | दस्तावेज़ कैश जहाँ संग्रहीत किया जाएगा, उसका सापेक्ष या पूर्ण पथ। |

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


FileCache क्लास की नई इंस्टेंस बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cachePath | java.nio.file.Path | दस्तावेज़ कैश जहाँ संग्रहीत किया जाएगा, उसका सापेक्ष या पूर्ण पथ। |

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


FileCache क्लास की नई इंस्टेंस बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cachePath | java.lang.String | दस्तावेज़ कैश जहाँ संग्रहीत किया जाएगा, उसका सापेक्ष या पूर्ण पथ। |
| cacheSubFolder | java.lang.String | cachePath में जोड़ने के लिए उप-फ़ोल्डर। |

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


FileCache क्लास की नई इंस्टेंस बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cachePath | java.nio.file.Path | दस्तावेज़ कैश जहाँ संग्रहीत किया जाएगा, उसका सापेक्ष या पूर्ण पथ। |
| cacheSubFolder | java.lang.String | cachePath में जोड़ने के लिए उप-फ़ोल्डर। |

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


कैश फ़ोल्डर का सापेक्ष या पूर्ण पथ प्राप्त करता है।

**Returns:**
java.lang.String - कैश फ़ोल्डर का पथ।
### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


कैश पथ में जोड़ने के लिए उप-फ़ोल्डर।

**Returns:**
java.lang.String - जोड़ने के लिए उप-फ़ोल्डर।
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


डेटा को स्थानीय डिस्क पर सीरियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | कैश प्रविष्टि के लिए अद्वितीय पहचानकर्ता। |
| value | java.lang.Object | सीरियलाइज़ करने के लिए वस्तु। |

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


यदि मौजूद हो तो इस कुंजी से संबंधित डेटा को डीसीरियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | java.lang.String | अनुरोधित प्रविष्टि की पहचान करने वाली कुंजी। |
| clazz | java.lang.Class<T> | अपेक्षित मान की क्लास। |

**Returns:**
T - प्राप्त मान या null।
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


फ़ाइलनाम में फ़िल्टर शामिल करने वाली सभी फ़ाइल नामों को लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filter | java.lang.String | उपयोग करने के लिए फ़िल्टर। |

**Returns:**
java.util.List<java.lang.String> - फ़ाइलनाम में फ़िल्टर शामिल करने वाले फ़ाइल नाम।
