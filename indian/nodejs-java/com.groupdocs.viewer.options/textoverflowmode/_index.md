---
title: "TextOverflowMode"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "स्प्रेडशीट दस्तावेज़ों को HTML में रेंडर करने के लिए टेक्स्ट ओवरफ़्लो मोड निर्धारित करता है।"
type: docs
weight: 46
url: /hi/nodejs-java/com.groupdocs.viewer.options/textoverflowmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TextOverflowMode extends Enum<TextOverflowMode>
```

स्प्रेडशीट दस्तावेज़ों को HTML में रेंडर करने के लिए टेक्स्ट ओवरफ़्लो मोड निर्धारित करता है।

TextOverflowMode enum विभिन्न मोड्स को दर्शाता है जो GroupDocs.Viewer घटक में टेक्स्ट ओवरफ़्लो को संभालते हैं। यह पूर्वनिर्धारित विकल्पों का सेट प्रदान करता है जिसका उपयोग स्प्रेडशीट दस्तावेज़ों को HTML में रेंडर करते समय कोशिकाओं में उपलब्ध स्थान से अधिक टेक्स्ट को कैसे प्रदर्शित किया जाए, नियंत्रित करने के लिए किया जा सकता है। विवरण के लिए, देखें [documentation][].

उदाहरण उपयोग:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();

 htmlViewOptions.setSpreadsheetOptions(SpreadsheetOptions.forOnePagePerSheet());
 htmlViewOptions.getSpreadsheetOptions().setTextOverflowMode(TextOverflowMode.HIDE_TEXT);

 try (Viewer viewer = new Viewer("document.xlsx")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [OVERLAY](#OVERLAY) | अगली कोशिकाओं को ओवरले करें चाहे वे खाली न हों। |
| [OVERLAY_IF_NEXT_IS_EMPTY](#OVERLAY-IF-NEXT-IS-EMPTY) | अगली कोशिकाओं को केवल तभी ओवरले करें जब वे खाली हों। |
| [AUTO_FIT_COLUMN](#AUTO-FIT-COLUMN) | पाठ को फिट करने के लिए कॉलम का विस्तार करें। |
| [HIDE_TEXT](#HIDE-TEXT) | ओवरफ़्लो टेक्स्ट को छुपाएँ। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### OVERLAY {#OVERLAY}
```
public static final TextOverflowMode OVERLAY
```


अगली कोशिकाओं को ओवरले करें चाहे वे खाली न हों। यह मोड टेक्स्ट को पड़ोसी कोशिकाओं में ओवरफ़्लो करने की अनुमति देता है, चाहे उनकी सामग्री कुछ भी हो।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### OVERLAY_IF_NEXT_IS_EMPTY {#OVERLAY-IF-NEXT-IS-EMPTY}
```
public static final TextOverflowMode OVERLAY_IF_NEXT_IS_EMPTY
```


अगली कोशिकाओं को केवल तभी ओवरले करें जब वे खाली हों। यह मोड टेक्स्ट को पड़ोसी कोशिकाओं में ओवरफ़्लो करने की अनुमति देता है केवल तब जब वे कोशिकाएँ खाली हों।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### AUTO_FIT_COLUMN {#AUTO-FIT-COLUMN}
```
public static final TextOverflowMode AUTO_FIT_COLUMN
```


पाठ को फिट करने के लिए कॉलम का विस्तार करें। यह मोड स्वचालित रूप से कॉलम की चौड़ाई को ओवरफ़्लो होने वाले टेक्स्ट को समायोजित करने के लिए समायोजित करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

### HIDE_TEXT {#HIDE-TEXT}
```
public static final TextOverflowMode HIDE_TEXT
```


ओवरफ़्लो टेक्स्ट को छुपाएँ। यह मोड ओवरफ़्लो होने वाले टेक्स्ट को छुपाता है, जिससे वह प्रदर्शित न हो।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode)
