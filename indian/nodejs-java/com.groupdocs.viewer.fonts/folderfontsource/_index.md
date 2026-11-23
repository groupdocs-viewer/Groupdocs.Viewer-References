---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "TrueType फ़ॉन्ट्स वाले फ़ोल्डर को दर्शाता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

TrueType फ़ॉन्ट्स वाले फ़ोल्डर को दर्शाता है।

FolderFontSource क्लास का उपयोग उन फ़ोल्डर स्थान को निर्दिष्ट करने के लिए किया जाता है जिसमें TrueType फ़ॉन्ट होते हैं। यह GroupDocs.Viewer API को निर्दिष्ट फ़ोल्डर में संग्रहीत फ़ॉन्ट तक दस्तावेज़ रेंडरिंग के उद्देश्य से पहुँचने की अनुमति देता है।

उदाहरण उपयोग:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | FolderFontSource क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | निर्धारित करता है कि दो FolderFontSource ऑब्जेक्ट समान हैं या नहीं। |
| [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | निर्धारित करता है कि दो FolderFontSource ऑब्जेक्ट समान नहीं हैं या नहीं। |
| [getFolderPath()](#getFolderPath--) | TrueType फ़ॉन्ट वाले फ़ोल्डर का पथ प्राप्त करता है। |
| [getSearchOption()](#getSearchOption--) | सर्च विकल्प प्राप्त करता है जो निर्धारित करता है कि वर्तमान फ़ोल्डर को खोजा जाए या वर्तमान फ़ोल्डर और सभी सबफ़ोल्डर को। |
| [isRecursive()](#isRecursive--) | जाँचता है कि फ़ॉन्ट पुनरावर्ती रूप से खोजे जाएंगे या नहीं। |
| [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | निर्धारित करता है कि वर्तमान FolderFontSource निर्दिष्ट FolderFontSource ऑब्जेक्ट के समान है या नहीं। |
| [equals(Object o)](#equals-java.lang.Object-) | निर्धारित करता है कि वर्तमान FolderFontSource निर्दिष्ट ऑब्जेक्ट के समान है या नहीं। |
| [hashCode()](#hashCode--) | वर्तमान FolderFontSource ऑब्जेक्ट के लिए हैश कोड लौटाता है। |
| [toString()](#toString--) | वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


FolderFontSource क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| folderPath | java.lang.String | TrueType फ़ॉन्ट वाले फ़ोल्डर का पथ। |
| searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | निर्धारित करता है कि वर्तमान फ़ोल्डर को खोजा जाए या वर्तमान फ़ोल्डर और सभी सबफ़ोल्डर को। |

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


निर्धारित करता है कि दो FolderFontSource ऑब्जेक्ट समान हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | बाएँ FolderFontSource ऑब्जेक्ट। |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | दाएँ FolderFontSource ऑब्जेक्ट। |

**Returns:**
boolean - true यदि दोनों FolderFontSource ऑब्जेक्ट समान हैं; अन्यथा false।
### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


निर्धारित करता है कि दो FolderFontSource ऑब्जेक्ट समान नहीं हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | बाएँ FolderFontSource ऑब्जेक्ट। |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | दाएँ FolderFontSource ऑब्जेक्ट। |

**Returns:**
boolean - true यदि दोनों FolderFontSource ऑब्जेक्ट समान नहीं हैं; अन्यथा false।
### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


TrueType फ़ॉन्ट वाले फ़ोल्डर का पथ प्राप्त करता है।

**Returns:**
java.lang.String - TrueType फ़ॉन्ट वाले फ़ोल्डर का पथ।
### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


सर्च विकल्प प्राप्त करता है जो निर्धारित करता है कि वर्तमान फ़ोल्डर को खोजा जाए या वर्तमान फ़ोल्डर और सभी सबफ़ोल्डर को।

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.
### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


जाँचता है कि फ़ॉन्ट पुनरावर्ती रूप से खोजे जाएंगे या नहीं।

**Returns:**
boolean - true यदि फ़ॉन्ट पुनरावर्ती रूप से खोजे जाएंगे, अन्यथा false।
### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


निर्धारित करता है कि वर्तमान FolderFontSource निर्दिष्ट FolderFontSource ऑब्जेक्ट के समान है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | वर्तमान FolderFontSource ऑब्जेक्ट के साथ तुलना करने के लिए ऑब्जेक्ट। |

**Returns:**
boolean - true यदि दोनों FolderFontSource ऑब्जेक्ट समान हैं; अन्यथा false
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


निर्धारित करता है कि वर्तमान FolderFontSource निर्दिष्ट ऑब्जेक्ट के समान है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| o | java.lang.Object | वर्तमान FolderFontSource ऑब्जेक्ट के साथ तुलना करने के लिए ऑब्जेक्ट। |

**Returns:**
boolean - true यदि obj पैरामीटर FolderFontSource प्रकार का है और वर्तमान FolderFontSource ऑब्जेक्ट के समान है; अन्यथा false
### hashCode() {#hashCode--}
```
public int hashCode()
```


वर्तमान FolderFontSource ऑब्जेक्ट के लिए हैश कोड लौटाता है।

**Returns:**
int - वर्तमान FolderFontSource ऑब्जेक्ट के लिए हैश कोड।
### toString() {#toString--}
```
public String toString()
```


वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है।

**Returns:**
java.lang.String - वर्तमान ऑब्जेक्ट का प्रतिनिधित्व करने वाली स्ट्रिंग।
