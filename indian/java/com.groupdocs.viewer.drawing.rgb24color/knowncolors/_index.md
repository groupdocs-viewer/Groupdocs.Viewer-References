---
title: "KnownColors"
second_title: "GroupDocs.Viewer for Java API Reference"
description: 
type: docs
weight: 10
url: /hi/java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## Methods

| Method | विवरण |
| --- | --- |
|  | [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | स्ट्रिंग नाम द्वारा रंग खोजने का प्रयास करता है। |
|
|  | [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | RGB मान द्वारा रंग का नाम खोजने का प्रयास करता है। |
|
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


स्ट्रिंग नाम द्वारा रंग खोजने का प्रयास करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | कीवर्ड | java.lang.String | एक रंग का नाम। |
|
|  | output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | पाए गए रंग के लिए परिणाम कंटेनर, या विफलता पर CssLevel1.Black। |
|

**Returns:**
बूलियन - यदि रंग नाम द्वारा सफलतापूर्वक मिला हो तो True, अन्यथा false।

### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


RGB मान द्वारा रंग का नाम खोजने का प्रयास करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | एक रंग का उदाहरण। |
|
|  | नाम | java.lang.String[] | पाए गए रंग नाम के लिए परिणाम कंटेनर, या विफलता पर null। |
|

**Returns:**
बूलियन - यदि दिए गए रंग के लिए नाम सफलतापूर्वक मिला हो तो True, अन्यथा false।

