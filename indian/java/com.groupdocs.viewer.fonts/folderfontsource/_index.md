---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "TrueType फ़ॉन्ट्स वाले फ़ोल्डर का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

TrueType फ़ॉन्ट्स वाले फ़ोल्डर का प्रतिनिधित्व करता है।


FolderFontSource क्लास का उपयोग एक फ़ोल्डर स्थान निर्दिष्ट करने के लिए किया जाता है जिसमें TrueType फ़ॉन्ट्स होते हैं।
यह GroupDocs.Viewer API को निर्दिष्ट फ़ोल्डर में संग्रहीत फ़ॉन्ट्स तक पहुँचने की अनुमति देता है ताकि दस्तावेज़ रेंडरिंग उद्देश्यों के लिए उपयोग किया जा सके।


उदाहरण उपयोग:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | नए उदाहरण को प्रारंभ करता है |
FolderFontSource
class।
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | निर्धारित करता है कि दो |
FolderFontSource
ऑब्जेक्ट समान हैं।
|
|  | [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | निर्धारित करता है कि दो |
FolderFontSource
ऑब्जेक्ट समान नहीं हैं।
|
|  | [getFolderPath()](#getFolderPath--) | TrueType फ़ॉन्ट्स वाले फ़ोल्डर का पथ प्राप्त करता है। |
|
|  | [getSearchOption()](#getSearchOption--) | खोज विकल्प प्राप्त करता है जो निर्दिष्ट करता है कि वर्तमान फ़ोल्डर को खोजा जाए या वर्तमान फ़ोल्डर और सभी सबफ़ोल्डर्स को। |
|
|  | [isRecursive()](#isRecursive--) | जाँचता है कि फ़ॉन्ट्स को पुनरावर्ती रूप से खोजा जाएगा या नहीं। |
|
|  | [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | निर्धारित करता है कि वर्तमान |
FolderFontSource
निर्दिष्ट के समान है
FolderFontSource
ऑब्जेक्ट।
|
|  | [equals(Object o)](#equals-java.lang.Object-) | निर्धारित करता है कि वर्तमान |
FolderFontSource
निर्दिष्ट ऑब्जेक्ट के समान है।
|
|  | [hashCode()](#hashCode--) | वर्तमान के लिए हैश कोड लौटाता है |
FolderFontSource
ऑब्जेक्ट।
|
|  | [toString()](#toString--) | वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |
|
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


नए उदाहरण को प्रारंभ करता है
FolderFontSource
class।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | folderPath | java.lang.String | फ़ोल्डर का पथ जिसमें TrueType फ़ॉन्ट्स हैं। |
|
|  | searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | निर्दिष्ट करता है कि वर्तमान फ़ोल्डर को खोजा जाए, या वर्तमान फ़ोल्डर और सभी उप‑फ़ोल्डर। |
|

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


निर्धारित करता है कि दो
FolderFontSource
ऑब्जेक्ट समान हैं।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | बाएँ  FolderFontSource  ऑब्जेक्ट। |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | दाएँ  FolderFontSource  ऑब्जेक्ट। |
|

**Returns:**
boolean -  true  यदि दोनों  FolderFontSource  ऑब्जेक्ट समान हैं; अन्यथा,  false .

### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


निर्धारित करता है कि दो
FolderFontSource
ऑब्जेक्ट समान नहीं हैं।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | बाएँ  FolderFontSource  ऑब्जेक्ट। |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | दाएँ  FolderFontSource  ऑब्जेक्ट। |
|

**Returns:**
boolean -  true  यदि दोनों  FolderFontSource  ऑब्जेक्ट समान नहीं हैं; अन्यथा,  false .

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


TrueType फ़ॉन्ट्स वाले फ़ोल्डर का पथ प्राप्त करता है।


**Returns:**
java.lang.String - फ़ोल्डर का पथ जिसमें TrueType फ़ॉन्ट्स हैं।

### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


खोज विकल्प प्राप्त करता है जो निर्दिष्ट करता है कि वर्तमान फ़ोल्डर को खोजा जाए या वर्तमान फ़ोल्डर और सभी सबफ़ोल्डर्स को।


**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.

### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


जाँचता है कि फ़ॉन्ट्स को पुनरावर्ती रूप से खोजा जाएगा या नहीं।


**Returns:**
boolean -  true  यदि फ़ॉन्ट्स को पुनरावर्ती रूप से खोजा जाएगा,  false  अन्यथा।

### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


निर्धारित करता है कि वर्तमान
FolderFontSource
निर्दिष्ट के समान है
FolderFontSource
ऑब्जेक्ट।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | वर्तमान  FolderFontSource  ऑब्जेक्ट के साथ तुलना करने के लिए ऑब्जेक्ट। |
|

**Returns:**
boolean -  true  यदि दोनों  FolderFontSource  ऑब्जेक्ट समान हैं; अन्यथा,  false

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


निर्धारित करता है कि वर्तमान
FolderFontSource
निर्दिष्ट ऑब्जेक्ट के समान है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | o | java.lang.Object | वर्तमान  FolderFontSource  ऑब्जेक्ट के साथ तुलना करने के लिए ऑब्जेक्ट। |
|

**Returns:**
boolean -  true  यदि  obj  पैरामीटर का प्रकार  FolderFontSource  है और वह वर्तमान  FolderFontSource  ऑब्जेक्ट के समान है; अन्यथा,  false

### hashCode() {#hashCode--}
```
public int hashCode()
```


वर्तमान के लिए हैश कोड लौटाता है
FolderFontSource
ऑब्जेक्ट।


**Returns:**
int - वर्तमान  FolderFontSource  ऑब्जेक्ट के लिए हैश कोड।

### toString() {#toString--}
```
public String toString()
```


वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है।


**Returns:**
java.lang.String - एक स्ट्रिंग जो वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करती है।

