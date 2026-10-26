---
title: "CacheableFactory"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "यह क्लास कस्टमाइज़ करने में मदद करती है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

यह क्लास कस्टमाइज़ करने में मदद करती है [Cache](../../com.groupdocs.viewer.caching/cache).

सीरियलाइज़ेशन के लिए कस्टम मॉडल्स को इस क्लास में मेथड्स को ओवरराइड करके लागू किया जा सकता है ताकि वे एम्बेडेड मॉडलों के बजाय लौटाए जाएँ। इसे प्राप्त करने के लिए, CacheableFactory को विस्तारित करें और कस्टम फ़ैक्टरी का नया इंस्टेंस [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory\#setInstance-CacheableFactory-) मेथड को पास करके इसे सक्रिय करें।

उदाहरण उपयोग:

```

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
```

कैश को कस्टमाइज़ करने के बारे में अधिक विवरण, दिशानिर्देश और उदाहरणों के लिए कृपया [GroupDocs.Viewer documentation][] देखें।


[GroupDocs.Viewer documentation]: https://docs.groupdocs.com/viewer/java/getting-started/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getInstance()](#getInstance--) | CacheableFactory का एक इंस्टेंस प्राप्त करता है जिसका उपयोग कैशेबल ऑब्जेक्ट्स बनाने के लिए किया जा सकता है। |
| [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | उपयोग किए जाने वाले CacheableFactory के इंस्टेंस को सेट करता है। |
| [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | निर्दिष्ट फ़ाइल प्रकार और पेजों के लिए [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | निर्दिष्ट फ़ाइल प्रकार, पेज और नोट्स की संख्या के लिए [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | निर्दिष्ट फ़ाइल प्रकार, पेज और फ़ोल्डर्स के लिए [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | निर्दिष्ट कैरेक्टर, पोजीशन और डायमेंशन्स के लिए [Character](../../com.groupdocs.viewer.results/character) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | निर्दिष्ट फ़ाइल प्रकार के लिए [FileInfo](../../com.groupdocs.viewer.results/fileinfo) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | निर्दिष्ट नाम और विज़िबिलिटी के साथ [Layer](../../com.groupdocs.viewer.results/layer) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newLayer(String name)](#newLayer-java.lang.String-) | निर्दिष्ट नाम के साथ [Layer](../../com.groupdocs.viewer.results/layer) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | निर्दिष्ट नाम, चौड़ाई और ऊँचाई के साथ [Layout](../../com.groupdocs.viewer.results/layout) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | निर्दिष्ट लाइन, पोजीशन, डायमेंशन्स और शब्दों के साथ [Line](../../com.groupdocs.viewer.results/line) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | निर्दिष्ट [Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | निर्दिष्ट [Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | निर्दिष्ट [Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | निर्दिष्ट [Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | निर्दिष्ट फ़ाइल प्रकार, पेजों की सूची और फ़ोल्डर्स की सूची के आधार पर [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newPage(int number, boolean visible)](#newPage-int-boolean-) | निर्दिष्ट नंबर और विज़िबिलिटी वाले पेज को दर्शाने वाले [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | निर्दिष्ट नंबर, नाम और विज़िबिलिटी वाले पेज को दर्शाने वाले [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | निर्दिष्ट नंबर, नाम, विज़िबिलिटी, चौड़ाई और ऊँचाई वाले पेज को दर्शाने वाले [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है। |
| [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | निर्दिष्ट संख्या, दृश्यता, चौड़ाई और ऊँचाई के साथ एक पृष्ठ का प्रतिनिधित्व करने वाले [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है। |
| [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | निर्दिष्ट संख्या, नाम, दृश्यता, चौड़ाई, ऊँचाई और रेखाओं के साथ एक पृष्ठ का प्रतिनिधित्व करने वाले [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है। |
| [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | निर्दिष्ट संख्या, दृश्यता, चौड़ाई, ऊँचाई और रेखाओं के साथ एक पृष्ठ का प्रतिनिधित्व करने वाले [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है। |
| [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | निर्दिष्ट फ़ाइल प्रकार, पृष्ठ और प्रिंटिंग अनुमति फ़्लैग के साथ [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है। |
| [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | निर्दिष्ट फ़ाइल प्रकार, पृष्ठ, लेयर और लेआउट के साथ [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है। |
| [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | निर्दिष्ट फ़ाइल प्रकार, पृष्ठ, प्रारंभ तिथि और समाप्ति तिथि के साथ [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है। |
| [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | निर्दिष्ट मान, निर्देशांक और आयामों के साथ [TextElement](../../com.groupdocs.viewer.results/textelement) इंटरफ़ेस का कार्यान्वयन बनाता है। |
| [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | निर्दिष्ट फ़ाइल प्रकार, पृष्ठ और नोट्स गिनती के साथ MboxViewInfo इंटरफ़ेस का कार्यान्वयन बनाता है। |
| [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | निर्दिष्ट शब्द, निर्देशांक, आयाम और अक्षरों के साथ [Word](../../com.groupdocs.viewer.results/word) इंटरफ़ेस का कार्यान्वयन बनाता है। |
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


CacheableFactory का एक इंस्टेंस प्राप्त करता है जिसका उपयोग कैशेबल ऑब्जेक्ट्स बनाने के लिए किया जा सकता है।

**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .
### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


उपयोग के लिए CacheableFactory का इंस्टेंस सेट करता है। यह कैशेबल फ़ैक्ट्री का कस्टम कार्यान्वयन संभव बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | सेट करने के लिए CacheableFactory का इंस्टेंस। |

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


निर्दिष्ट फ़ाइल प्रकार और पेजों के लिए [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
| पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | दस्तावेज़ पृष्ठों का प्रतिनिधित्व करने वाले पृष्ठों की सूची। |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


निर्दिष्ट फ़ाइल प्रकार, पेज और नोट्स की संख्या के लिए [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
| पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | दस्तावेज़ पृष्ठों का प्रतिनिधित्व करने वाले पृष्ठों की सूची। |
| notesCount | int | दस्तावेज़ में Lotus Notes की गिनती। |

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.
### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


निर्दिष्ट फ़ाइल प्रकार, पेज और फ़ोल्डर्स के लिए [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
| पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | दस्तावेज़ पृष्ठों का प्रतिनिधित्व करने वाले पृष्ठों की सूची। |
| फ़ोल्डर | java.util.List<java.lang.String> | आर्काइव में फ़ोल्डर की सूची। |

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.
### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


निर्दिष्ट कैरेक्टर, पोजीशन और डायमेंशन्स के लिए [Character](../../com.groupdocs.viewer.results/character) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| अक्षर | char | अक्षर। |
| x | double | अक्षर स्थिति का x-निर्देशांक। |
| y | double | अक्षर स्थिति का y-निर्देशांक। |
| width | double | अक्षर की चौड़ाई। |
| height | double | अक्षर की ऊँचाई। |

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.
### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


निर्दिष्ट फ़ाइल प्रकार के लिए [FileInfo](../../com.groupdocs.viewer.results/fileinfo) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.
### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


निर्दिष्ट नाम और विज़िबिलिटी के साथ [Layer](../../com.groupdocs.viewer.results/layer) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | लेयर का नाम। |
| दृश्यमान | boolean | लेयर की दृश्यता। |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


निर्दिष्ट नाम के साथ [Layer](../../com.groupdocs.viewer.results/layer) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | लेयर का नाम। |

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.
### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


निर्दिष्ट नाम, चौड़ाई और ऊँचाई के साथ [Layout](../../com.groupdocs.viewer.results/layout) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | लेआउट का नाम। |
| width | double | लेआउट की चौड़ाई। |
| height | double | लेआउट की ऊँचाई। |

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.
### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


निर्दिष्ट लाइन, पोजीशन, डायमेंशन्स और शब्दों के साथ [Line](../../com.groupdocs.viewer.results/line) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| लाइन | java.lang.String | लाइन की सामग्री। |
| x | double | लाइन को सम्मिलित करने वाले आयत के ऊपर-बाएँ बिंदु का X निर्देशांक। |
| y | double | लाइन को सम्मिलित करने वाले आयत के ऊपर-बाएँ बिंदु का Y निर्देशांक। |
| width | double | लाइन को सम्मिलित करने वाले आयत की चौड़ाई (पिक्सेल में)। |
| height | double | लाइन को सम्मिलित करने वाले आयत की ऊँचाई (पिक्सेल में)। |
| शब्द | java.util.List<com.groupdocs.viewer.results.Word> | लाइन में मौजूद शब्द। |

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.
### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


निर्दिष्ट [Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | संलग्नक का नाम। |
| फ़ाइल पथ | java.lang.String | संलग्नक का सापेक्ष पथ, उदाहरण के लिए "folder/file.docx"। जब फ़ाइल एक संग्रह के मूल में, ईमेल संदेश में, या डेटा फ़ाइल में स्थित हो, तो फ़ाइलनाम निर्दिष्ट करें। |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


निर्दिष्ट [Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| आईडी | java.lang.String | संलग्नक की आईडी। |
| fileName | java.lang.String | संलग्नक का नाम। |
| फ़ाइल पथ | java.lang.String | संलग्नक का सापेक्ष पथ, उदाहरण के लिए "folder/file.docx"। जब फ़ाइल एक संग्रह के मूल में, ईमेल संदेश में, या डेटा फ़ाइल में स्थित हो, तो फ़ाइलनाम निर्दिष्ट करें। |
| आकार | long | संलग्नक का आकार। |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


निर्दिष्ट [Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| आईडी | java.lang.String | संलग्नक की आईडी। |
| fileName | java.lang.String | संलग्नक का नाम। |
| फ़ाइल पथ | java.nio.file.Path | संलग्नक का सापेक्ष या पूर्ण पथ। |
| आकार | long | संलग्नक का आकार। |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


एक [Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का कार्यान्वयन बनाता है। अटैचमेंट एक फ़ाइल को दर्शाता है जो दस्तावेज़ या ईमेल संदेश में संलग्न होती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| आईडी | java.lang.String | संलग्नक की आईडी। |
| fileName | java.lang.String | संलग्नक का नाम। |
| फ़ाइल पथ | java.lang.String | अटैचमेंट का सापेक्ष या पूर्ण पथ। यह फ़ोल्डर के भीतर फ़ाइल पथ या फ़ाइलनाम हो सकता है यदि फ़ाइल आर्काइव की जड़ में, ईमेल संदेश में, या डेटा फ़ाइल में स्थित हो। |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | अटैचमेंट फ़ाइल का प्रकार। |
| आकार | long | संलग्नक का आकार। |

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.
### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


निर्दिष्ट फ़ाइल प्रकार, पेजों की सूची और फ़ोल्डर्स की सूची के आधार पर [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
| पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | पृष्ठों की सूची। |
| फ़ोल्डर | java.util.List<java.lang.String> | फ़ोल्डरों की सूची। |

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.
### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


निर्दिष्ट नंबर और विज़िबिलिटी वाले पेज को दर्शाने वाले [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संख्या | int | पृष्ठ संख्या। |
| दृश्यमान | boolean | दृश्यता फ़्लैग। |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


निर्दिष्ट नंबर, नाम और विज़िबिलिटी वाले पेज को दर्शाने वाले [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संख्या | int | पृष्ठ संख्या। |
| नाम | java.lang.String | पृष्ठ नाम। |
| दृश्यमान | boolean | दृश्यता फ़्लैग। |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


निर्दिष्ट नंबर, नाम, विज़िबिलिटी, चौड़ाई और ऊँचाई वाले पेज को दर्शाने वाले [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का एक इम्प्लीमेंटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संख्या | int | पृष्ठ संख्या। |
| नाम | java.lang.String | पृष्ठ नाम। |
| दृश्यमान | boolean | दृश्यता फ़्लैग। |
| width | int | पृष्ठ की चौड़ाई। |
| height | int | पृष्ठ की ऊँचाई। |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


निर्दिष्ट संख्या, दृश्यता, चौड़ाई और ऊँचाई के साथ एक पृष्ठ का प्रतिनिधित्व करने वाले [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संख्या | int | पृष्ठ संख्या। |
| दृश्यमान | boolean | दृश्यता फ़्लैग। |
| width | int | पृष्ठ की चौड़ाई। |
| height | int | पृष्ठ की ऊँचाई। |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


निर्दिष्ट संख्या, नाम, दृश्यता, चौड़ाई, ऊँचाई और रेखाओं के साथ एक पृष्ठ का प्रतिनिधित्व करने वाले [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संख्या | int | पृष्ठ संख्या। |
| नाम | java.lang.String | पृष्ठ नाम। |
| दृश्यमान | boolean | दृश्यता फ़्लैग। |
| width | int | पृष्ठ की चौड़ाई। |
| height | int | पृष्ठ की ऊँचाई। |
| पंक्तियाँ | java.util.List<com.groupdocs.viewer.results.Line> | पृष्ठ में सम्मिलित पंक्तियाँ। |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


निर्दिष्ट संख्या, दृश्यता, चौड़ाई, ऊँचाई और रेखाओं के साथ एक पृष्ठ का प्रतिनिधित्व करने वाले [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संख्या | int | पृष्ठ संख्या। |
| दृश्यमान | boolean | दृश्यता फ़्लैग। |
| width | int | पृष्ठ की चौड़ाई। |
| height | int | पृष्ठ की ऊँचाई। |
| पंक्तियाँ | java.util.List<com.groupdocs.viewer.results.Line> | पृष्ठ में सम्मिलित पंक्तियाँ। |

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.
### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


निर्दिष्ट फ़ाइल प्रकार, पृष्ठ और प्रिंटिंग अनुमति फ़्लैग के साथ [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
| पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | पृष्ठों की सूची। |
| printingAllowed | boolean | फ़्लैग जो दर्शाता है कि प्रिंटिंग की अनुमति है या नहीं। |

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.
### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


निर्दिष्ट फ़ाइल प्रकार, पृष्ठ, लेयर और लेआउट के साथ [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
| पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | पृष्ठों की सूची। |
| परतें | java.util.List<com.groupdocs.viewer.results.Layer> | परतों की सूची। |
| लेआउट्स | java.util.List<com.groupdocs.viewer.results.Layout> | लेआउट्स की सूची। |

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.
### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


निर्दिष्ट फ़ाइल प्रकार, पृष्ठ, प्रारंभ तिथि और समाप्ति तिथि के साथ [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
| पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | पृष्ठों की सूची। |
| startDate | java.util.Date | आरंभ तिथि। |
| endDate | java.util.Date | समाप्ति तिथि। |

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.
### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


निर्दिष्ट मान, निर्देशांक और आयामों के साथ [TextElement](../../com.groupdocs.viewer.results/textelement) इंटरफ़ेस का कार्यान्वयन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | T | मान। |
| x | double | X निर्देशांक। |
| y | double | Y निर्देशांक। |
| width | double | चौड़ाई। |
| height | double | ऊँचाई। |

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.
### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


निर्दिष्ट फ़ाइल प्रकार, पृष्ठ और नोट्स गिनती के साथ MboxViewInfo इंटरफ़ेस का कार्यान्वयन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल का प्रकार। |
| पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | देखने के लिए पृष्ठों की सूची। |
| notesCount | int | Lotus डेटाबेस स्टोरेज फ़ाइल में मौजूद नोट्स की संख्या। |

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - MboxViewInfo कार्यान्वयन का एक नया उदाहरण।
### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


निर्दिष्ट शब्द, निर्देशांक, आयाम और अक्षरों के साथ [Word](../../com.groupdocs.viewer.results/word) इंटरफ़ेस का कार्यान्वयन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| शब्द | java.lang.String | शब्द। |
| x | double | पृष्ठ लेआउट पर शब्द को सम्मिलित करने वाले आयत के शुरू होने वाले सबसे बाएँ ऊपरी बिंदु का X निर्देशांक। |
| y | double | पृष्ठ लेआउट पर शब्द को सम्मिलित करने वाले आयत के शुरू होने वाले सबसे बाएँ ऊपरी बिंदु का Y निर्देशांक। |
| width | double | शब्द को सम्मिलित करने वाले आयत की चौड़ाई (पिक्सेल में)। |
| height | double | शब्द को सम्मिलित करने वाले आयत की ऊँचाई (पिक्सेल में)। |
| अक्षर | java.util.List<com.groupdocs.viewer.results.Character> | शब्द में सम्मिलित अक्षर। |

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.
