---
title: "टाइल"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "ड्राइंग क्षेत्र का प्रतिनिधित्व करता है।"
type: docs
weight: 33
url: /hi/nodejs-java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

ड्राइंग क्षेत्र का प्रतिनिधित्व करता है।

Tile क्लास GroupDocs.Viewer कंपोनेंट में एक ड्रॉइंग क्षेत्र का प्रतिनिधित्व करती है। इसका उपयोग दस्तावेज़ के भीतर एक विशिष्ट क्षेत्र या भाग को परिभाषित करने के लिए किया जाता है जिसे अलग से रेंडर या प्रोसेस करने की आवश्यकता होती है। विवरण के लिए, देखें [documentation][].

उदाहरण उपयोग:

```

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Tile क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getStartPointX()](#getStartPointX--) | टाइल के शुरू होने वाले ड्रॉइंग के सबसे नीचे बाएँ बिंदु का X निर्देशांक प्राप्त करता है। |
| [getStartPointY()](#getStartPointY--) | टाइल के शुरू होने वाले ड्रॉइंग के सबसे नीचे बाएँ बिंदु का Y निर्देशांक प्राप्त करता है। |
| [getWidth()](#getWidth--) | टाइल की चौड़ाई पिक्सेल में प्राप्त करता है। |
| [getHeight()](#getHeight--) | टाइल की ऊँचाई पिक्सेल में प्राप्त करता है। |
| [getEndPointX()](#getEndPointX--) | टाइल के समाप्त होने वाले ड्रॉइंग के सबसे ऊपर दाएँ बिंदु का X निर्देशांक लौटाता है। |
| [getEndPointY()](#getEndPointY--) | टाइल के समाप्त होने वाले ड्रॉइंग के सबसे ऊपर दाएँ बिंदु का Y निर्देशांक लौटाता है। |
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Tile क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

यह कंस्ट्रक्टर निर्दिष्ट प्रारंभ बिंदु, चौड़ाई और ऊँचाई के साथ एक नया टाइल ऑब्जेक्ट बनाता है। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startPointX | int | टाइल के शुरू होने वाले ड्रॉइंग के सबसे नीचे बाएँ बिंदु का X निर्देशांक। |
| startPointY | int | टाइल के शुरू होने वाले ड्रॉइंग के सबसे नीचे बाएँ बिंदु का Y निर्देशांक। |
| width | int | टाइल की चौड़ाई पिक्सेल में। |
| height | int | टाइल की ऊँचाई पिक्सेल में। |

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


टाइल के शुरू होने वाले ड्रॉइंग के सबसे नीचे बाएँ बिंदु का X निर्देशांक प्राप्त करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - सबसे नीचे बाएँ बिंदु का X निर्देशांक।
### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


टाइल के शुरू होने वाले ड्रॉइंग के सबसे नीचे बाएँ बिंदु का Y निर्देशांक प्राप्त करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - सबसे नीचे बाएँ बिंदु का Y निर्देशांक।
### getWidth() {#getWidth--}
```
public final int getWidth()
```


टाइल की चौड़ाई पिक्सेल में प्राप्त करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - टाइल की चौड़ाई।
### getHeight() {#getHeight--}
```
public final int getHeight()
```


टाइल की ऊँचाई पिक्सेल में प्राप्त करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - टाइल की ऊँचाई।
### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


टाइल के समाप्त होने वाले ड्रॉइंग के सबसे ऊपर दाएँ बिंदु का X निर्देशांक लौटाता है।

**Returns:**
int - सबसे ऊपर दाएँ बिंदु का X निर्देशांक।
### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


टाइल के समाप्त होने वाले ड्रॉइंग के सबसे ऊपर दाएँ बिंदु का Y निर्देशांक लौटाता है।

**Returns:**
int - सबसे दाएँ ऊँचे बिंदु का Y निर्देशांक।
