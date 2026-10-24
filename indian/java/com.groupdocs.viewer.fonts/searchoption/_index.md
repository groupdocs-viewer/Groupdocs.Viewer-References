---
title: "SearchOption"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "निर्दिष्ट करता है कि वर्तमान फ़ोल्डर या वर्तमान फ़ोल्डर और सभी उपफ़ोल्डर खोजे जाएँ।"
type: docs
weight: 21
url: /hi/java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

निर्दिष्ट करता है कि वर्तमान फ़ोल्डर को खोजा जाए या वर्तमान फ़ोल्डर और सभी सबफ़ोल्डर।


SearchOption enum का उपयोग GroupDocs.Viewer API में फ़ॉन्ट खोज ऑपरेशन की सीमा निर्दिष्ट करने के लिए किया जाता है।


उदाहरण उपयोग:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*

## Fields

| Field | विवरण |
| --- | --- |
|  | [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | खोज में केवल वर्तमान फ़ोल्डर शामिल करता है। |
|
|  | [ALL_FOLDERS](#ALL-FOLDERS) | खोज में वर्तमान फ़ोल्डर और सभी उपफ़ोल्डर शामिल करता है। |
|
## Methods

| Method | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


खोज में केवल वर्तमान फ़ोल्डर शामिल करता है।


### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


खोज में वर्तमान फ़ोल्डर और सभी उपफ़ोल्डर शामिल करता है।


### values() {#values--}
```
public static SearchOption[] values()
```




**Returns:**
com.groupdocs.viewer.fonts.SearchOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static SearchOption valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
