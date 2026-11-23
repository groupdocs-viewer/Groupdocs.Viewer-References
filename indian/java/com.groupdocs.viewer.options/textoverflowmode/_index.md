---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "स्प्रेडशीट दस्तावेज़ों को HTML में रेंडर करने के लिए टेक्स्ट ओवरफ़्लो मोड को परिभाषित करता है।"
type: docs
weight: 46
url: /hi/java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

स्प्रेडशीट दस्तावेज़ों को HTML में रेंडर करने के लिए टेक्स्ट ओवरफ़्लो मोड को परिभाषित करता है।


TextOverflowMode एनीम विभिन्न मोड्स को दर्शाता है जो GroupDocs.Viewer घटक में टेक्स्ट ओवरफ़्लो को संभालते हैं।
यह पूर्वनिर्धारित विकल्पों का एक सेट प्रदान करता है जिसे टेक्स्ट के उपलब्ध स्थान से अधिक हो जाने पर उसकी प्रदर्शनी को नियंत्रित करने के लिए उपयोग किया जा सकता है।
स्प्रेडशीट दस्तावेज़ों को HTML में रेंडर करने के दौरान कोशिकाओं में स्थान।
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


उदाहरण उपयोग:

````

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Fields

| Field | विवरण |
| --- | --- |
|  | [OVERLAY](#OVERLAY) | अगली कोशिकाओं को ओवरले करें चाहे वे खाली न हों। |
|
|  | [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | अगली कोशिकाओं को केवल तभी ओवरले करें जब वे खाली हों। |
|
|  | [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | कॉलम को टेक्स्ट के अनुसार विस्तारित करें। |
|
|  | [HIDE_TEXT](#HIDE-TEXT) | ओवरफ़्लो टेक्स्ट को छिपाएँ। |
|
## Methods

| Method | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


अगली कोशिकाओं को ओवरले करें चाहे वे खाली न हों।
यह मोड टेक्स्ट को सटे हुए कोशिकाओं में ओवरफ़्लो करने देता है, उनकी सामग्री की परवाह किए बिना।
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


अगली कोशिकाओं को केवल तभी ओवरले करें जब वे खाली हों।
यह मोड टेक्स्ट को सटे हुए कोशिकाओं में ओवरफ़्लो करने देता है केवल तभी जब वे कोशिकाएँ खाली हों।
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


कॉलम को टेक्स्ट के अनुसार विस्तारित करें।
यह मोड स्वचालित रूप से कॉलम की चौड़ाई को ओवरफ़्लो होने वाले टेक्स्ट को समायोजित करने के लिए बदलता है।
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


ओवरफ़्लो टेक्स्ट को छिपाएँ।
यह मोड ओवरफ़्लो टेक्स्ट को छिपाता है, जिससे वह प्रदर्शित न हो।
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


### values() {#values--}
```
public static TextOverflowMode[] values()
```




**Returns:**
com.groupdocs.viewer.options.TextOverflowMode[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TextOverflowMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
