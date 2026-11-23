---
title: "टाइल"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "ड्राइंग क्षेत्र का प्रतिनिधित्व करता है।"
type: docs
weight: 33
url: /hi/java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

ड्राइंग क्षेत्र का प्रतिनिधित्व करता है।


Tile क्लास GroupDocs.Viewer कंपोनेंट में एक ड्रॉइंग क्षेत्र का प्रतिनिधित्व करती है।
यह दस्तावेज़ के भीतर एक विशिष्ट क्षेत्र या क्षेत्र को परिभाषित करने के लिए उपयोग किया जाता है जिसे अलग से रेंडर या प्रोसेस करने की आवश्यकता होती है।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles)।


उदाहरण उपयोग:

````

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | नए उदाहरण को प्रारंभ करता है |
टाइल
class।
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [getStartPointX()](#getStartPointX--) | ड्रॉइंग पर सबसे निचले बाएँ बिंदु के X निर्देशांक को प्राप्त करता है जहाँ टाइल शुरू होती है। |
|
|  | [getStartPointY()](#getStartPointY--) | टाइल के शुरू होने वाले चित्र में सबसे निचले बाएँ बिंदु का Y निर्देशांक प्राप्त करता है। |
|
|  | [getWidth()](#getWidth--) | टाइल की चौड़ाई पिक्सेल में प्राप्त करता है। |
|
|  | [getHeight()](#getHeight--) | टाइल की ऊँचाई पिक्सेल में प्राप्त करता है। |
|
|  | [getEndPointX()](#getEndPointX--) | टाइल के समाप्त होने वाले चित्र में सबसे ऊँचे दाएँ बिंदु का X निर्देशांक लौटाता है। |
|
|  | [getEndPointY()](#getEndPointY--) | टाइल के समाप्त होने वाले चित्र में सबसे ऊँचे दाएँ बिंदु का Y निर्देशांक लौटाता है। |
|
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


नए उदाहरण को प्रारंभ करता है
टाइल
class।


यह कंस्ट्रक्टर निर्दिष्ट प्रारंभ बिंदु, चौड़ाई और ऊँचाई के साथ एक नया टाइल ऑब्जेक्ट बनाता है।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | startPointX | int | टाइल के शुरू होने वाले चित्र में सबसे निचले बाएँ बिंदु का X निर्देशांक। |
|
|  | startPointY | int | टाइल के शुरू होने वाले चित्र में सबसे निचले बाएँ बिंदु का Y निर्देशांक। |
|
|  | width | int | टाइल की चौड़ाई पिक्सेल में। |
|
|  | ऊँचाई | int | टाइल की ऊँचाई पिक्सेल में। |
|

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


ड्रॉइंग पर सबसे निचले बाएँ बिंदु के X निर्देशांक को प्राप्त करता है जहाँ टाइल शुरू होती है।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles)।


**Returns:**
int - सबसे निचले बाएँ बिंदु का X निर्देशांक।

### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


टाइल के शुरू होने वाले चित्र में सबसे निचले बाएँ बिंदु का Y निर्देशांक प्राप्त करता है।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles)।


**Returns:**
int - सबसे निचले बाएँ बिंदु का Y निर्देशांक।

### getWidth() {#getWidth--}
```
public final int getWidth()
```


टाइल की चौड़ाई पिक्सेल में प्राप्त करता है।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles)।


**Returns:**
int - टाइल की चौड़ाई।

### getHeight() {#getHeight--}
```
public final int getHeight()
```


टाइल की ऊँचाई पिक्सेल में प्राप्त करता है।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles)।


**Returns:**
int - टाइल की ऊँचाई।

### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


टाइल के समाप्त होने वाले चित्र में सबसे ऊँचे दाएँ बिंदु का X निर्देशांक लौटाता है।


**Returns:**
int - सबसे ऊँचे दाएँ बिंदु का X निर्देशांक।

### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


टाइल के समाप्त होने वाले चित्र में सबसे ऊँचे दाएँ बिंदु का Y निर्देशांक लौटाता है।


**Returns:**
int - सबसे ऊँचे दाएँ बिंदु का Y निर्देशांक।

