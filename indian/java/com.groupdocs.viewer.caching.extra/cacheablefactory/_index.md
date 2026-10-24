---
title: "CacheableFactory"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "यह वर्ग अनुकूलित करने में मदद करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.viewer.caching.extra/cacheablefactory/
---
**Inheritance:**
java.lang.Object
```
public class CacheableFactory
```

यह वर्ग [Cache](../../com.groupdocs.viewer.caching/cache) को अनुकूलित करने में मदद करता है।


सीरियलाइज़ेशन के लिए कस्टम मॉडल इस वर्ग में विधियों को ओवरराइड करके लागू किए जा सकते हैं, ताकि वे एम्बेडेड मॉडलों के बजाय लौटाए जा सकें।
इसे प्राप्त करने के लिए, CacheableFactory को विस्तारित करें और इसे सक्रिय करें, कस्टम फ़ैक्टरी का नया इंस्टेंस [setInstance(CacheableFactory)](../../com.groupdocs.viewer.caching.extra/cacheablefactory#setInstance-CacheableFactory-) मेथड को पास करके।


उदाहरण उपयोग:

````

 CacheableFactory.setInstance(new YourCustomCacheableFactory());
 // Custom cacheable factory is now in use. You can start rendering documents.
 
````


कैश को अनुकूलित करने के बारे में अधिक विवरण, दिशानिर्देश, और उदाहरणों के लिए, कृपया देखें the
[GroupDocs.Viewer documentation](../https://docs.groupdocs.com/viewer/java/getting-started/).

## Constructors

| Constructor | विवरण |
| --- | --- |
| [CacheableFactory()](#CacheableFactory--) |  |
## Methods

| Method | विवरण |
| --- | --- |
|  | [getInstance()](#getInstance--) | एक इंस्टेंस प्राप्त करता है |
CacheableFactory
जिसका उपयोग कैशेबल ऑब्जेक्ट बनाने के लिए किया जा सकता है।
|
|  | [setInstance(CacheableFactory instance)](#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-) | इंस्टेंस सेट करता है |
CacheableFactory
उपयोग के लिए।
|
|  | [newViewInfo(FileType fileType, List<Page> pages)](#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--) | निर्दिष्ट फ़ाइल प्रकार और पृष्ठों के लिए [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
| [newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)](#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-) |  |
|  | [newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | निर्दिष्ट फ़ाइल प्रकार, पृष्ठों, और नोट्स की संख्या के लिए [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | निर्दिष्ट फ़ाइल प्रकार, पृष्ठों, और फ़ोल्डरों के लिए [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newCharacter(char character, double x, double y, double width, double height)](#newCharacter-char-double-double-double-double-) | निर्दिष्ट अक्षर, स्थिति, और आयामों के लिए [Character](../../com.groupdocs.viewer.results/character) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newFileInfo(FileType fileType)](#newFileInfo-com.groupdocs.viewer.FileType-) | निर्दिष्ट फ़ाइल प्रकार के लिए [FileInfo](../../com.groupdocs.viewer.results/fileinfo) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newLayer(String name, boolean visible)](#newLayer-java.lang.String-boolean-) | निर्दिष्ट नाम और दृश्यता के साथ [Layer](../../com.groupdocs.viewer.results/layer) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newLayer(String name)](#newLayer-java.lang.String-) | निर्दिष्ट नाम के साथ [Layer](../../com.groupdocs.viewer.results/layer) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newLayout(String name, double width, double height)](#newLayout-java.lang.String-double-double-) | निर्दिष्ट नाम, चौड़ाई और ऊँचाई के साथ [Layout](../../com.groupdocs.viewer.results/layout) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newLine(String line, double x, double y, double width, double height, List<Word> words)](#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--) | निर्दिष्ट लाइन, स्थिति, आयाम और शब्दों के साथ [Line](../../com.groupdocs.viewer.results/line) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newAttachment(String fileName, String filePath)](#newAttachment-java.lang.String-java.lang.String-) | [Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newAttachment(String id, String fileName, String filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-) | [Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newAttachment(String id, String fileName, Path filePath, long size)](#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-) | [Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newAttachment(String id, String fileName, String filePath, FileType fileType, long size)](#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-) | [Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)](#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--) | निर्दिष्ट फ़ाइल प्रकार के आधार पर [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है, |
पृष्ठों की सूची, और फ़ोल्डरों की सूची।
|
|  | [newPage(int number, boolean visible)](#newPage-int-boolean-) | निर्दिष्ट संख्या और दृश्यता वाले पृष्ठ को दर्शाने वाला [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newPage(int number, String name, boolean visible)](#newPage-int-java.lang.String-boolean-) | निर्दिष्ट संख्या, नाम और दृश्यता वाले पृष्ठ को दर्शाने वाला [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newPage(int number, String name, boolean visible, int width, int height)](#newPage-int-java.lang.String-boolean-int-int-) | निर्दिष्ट संख्या, नाम, दृश्यता, चौड़ाई और ऊँचाई वाले पृष्ठ को दर्शाने वाला [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newPage(int number, boolean visible, int width, int height)](#newPage-int-boolean-int-int-) | निर्दिष्ट संख्या, दृश्यता, चौड़ाई और ऊँचाई वाले पृष्ठ को दर्शाने वाला [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)](#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | निर्दिष्ट संख्या, नाम, दृश्यता, चौड़ाई, ऊँचाई और लाइनों वाले पृष्ठ को दर्शाने वाला [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newPage(int number, boolean visible, int width, int height, List<Line> lines)](#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--) | निर्दिष्ट संख्या, दृश्यता, चौड़ाई, ऊँचाई और लाइनों वाले पृष्ठ को दर्शाने वाला [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)](#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-) | निर्दिष्ट फ़ाइल प्रकार, पृष्ठ और प्रिंटिंग अनुमति फ़्लैग के साथ [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)](#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--) | निर्दिष्ट फ़ाइल प्रकार, पृष्ठ, लेयर और लेआउट के साथ [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)](#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-) | निर्दिष्ट फ़ाइल प्रकार, पृष्ठ, प्रारंभ तिथि और समाप्ति तिथि के साथ [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [<T>newTextElement(T value, double x, double y, double width, double height)](#-T-newTextElement-T-double-double-double-double-) | निर्दिष्ट मान, निर्देशांक और आयाम के साथ [TextElement](../../com.groupdocs.viewer.results/textelement) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)](#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-) | निर्दिष्ट फ़ाइल प्रकार, पृष्ठ और नोट्स गिनती के साथ MboxViewInfo इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
|  | [newWord(String word, double x, double y, double width, double height, List<Character> characters)](#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--) | निर्दिष्ट शब्द, निर्देशांक, आयाम और अक्षरों के साथ [Word](../../com.groupdocs.viewer.results/word) इंटरफ़ेस का कार्यान्वयन बनाता है। |
|
### CacheableFactory() {#CacheableFactory--}
```
public CacheableFactory()
```


### getInstance() {#getInstance--}
```
public static CacheableFactory getInstance()
```


एक इंस्टेंस प्राप्त करता है
CacheableFactory
जिसका उपयोग कैशेबल ऑब्जेक्ट बनाने के लिए किया जा सकता है।


**Returns:**
[CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) - an instance of  CacheableFactory .

### setInstance(CacheableFactory instance) {#setInstance-com.groupdocs.viewer.caching.extra.CacheableFactory-}
```
public static void setInstance(CacheableFactory instance)
```


इंस्टेंस सेट करता है
CacheableFactory
उपयोग के लिए। यह कैशेबल फ़ैक्टरी की कस्टम कार्यान्वयन की अनुमति देता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | instance | [CacheableFactory](../../com.groupdocs.viewer.caching.extra/cacheablefactory) | सेट करने के लिए  CacheableFactory  का उदाहरण। |
|

### newViewInfo(FileType fileType, List<Page> pages) {#newViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--}
```
public ViewInfo newViewInfo(FileType fileType, List<Page> pages)
```


निर्दिष्ट फ़ाइल प्रकार और पृष्ठों के लिए [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
|
|  | पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | दस्तावेज़ पृष्ठों का प्रतिनिधित्व करने वाले पृष्ठों की सूची। |
|

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo) - a new instance of the [ViewInfo](../../com.groupdocs.viewer.results/viewinfo) implementation.

### newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from) {#newEmailViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.lang.String-java.lang.String-}
```
public ViewInfo newEmailViewInfo(FileType fileType, List<Page> pages, Date originalMessageDate, String subject, String from)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) |  |
| पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> |  |
| originalMessageDate | java.util.Date |  |
| विषय | java.lang.String |  |
| से | java.lang.String |  |

**Returns:**
[ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
### newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newLotusNotesViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public LotusNotesViewInfo newLotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


निर्दिष्ट फ़ाइल प्रकार, पृष्ठों, और नोट्स की संख्या के लिए [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
|
|  | पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | दस्तावेज़ पृष्ठों का प्रतिनिधित्व करने वाले पृष्ठों की सूची। |
|
|  | notesCount | int | दस्तावेज़ में Lotus Notes की गिनती। |
|

**Returns:**
[LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) - a new instance of the [LotusNotesViewInfo](../../com.groupdocs.viewer.results/lotusnotesviewinfo) implementation.

### newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newArchiveViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public ArchiveViewInfo newArchiveViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


निर्दिष्ट फ़ाइल प्रकार, पृष्ठों, और फ़ोल्डरों के लिए [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
|
|  | पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | दस्तावेज़ पृष्ठों का प्रतिनिधित्व करने वाले पृष्ठों की सूची। |
|
|  | folders | java.util.List<java.lang.String> | आर्काइव में फ़ोल्डर्स की सूची। |
|

**Returns:**
[ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) - a new instance of the [ArchiveViewInfo](../../com.groupdocs.viewer.results/archiveviewinfo) implementation.

### newCharacter(char character, double x, double y, double width, double height) {#newCharacter-char-double-double-double-double-}
```
public Character newCharacter(char character, double x, double y, double width, double height)
```


निर्दिष्ट अक्षर, स्थिति, और आयामों के लिए [Character](../../com.groupdocs.viewer.results/character) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | character | char | वर्ण। |
|
|  | x | double | वर्ण की स्थिति का x-निर्देशांक। |
|
|  | y | double | वर्ण की स्थिति का y-निर्देशांक। |
|
|  | width | double | वर्ण की चौड़ाई। |
|
|  | ऊँचाई | double | वर्ण की ऊँचाई। |
|

**Returns:**
[Character](../../com.groupdocs.viewer.results/character) - a new instance of the [Character](../../com.groupdocs.viewer.results/character) implementation.

### newFileInfo(FileType fileType) {#newFileInfo-com.groupdocs.viewer.FileType-}
```
public FileInfo newFileInfo(FileType fileType)
```


निर्दिष्ट फ़ाइल प्रकार के लिए [FileInfo](../../com.groupdocs.viewer.results/fileinfo) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
|

**Returns:**
[FileInfo](../../com.groupdocs.viewer.results/fileinfo) - a new instance of the [FileInfo](../../com.groupdocs.viewer.results/fileinfo) implementation.

### newLayer(String name, boolean visible) {#newLayer-java.lang.String-boolean-}
```
public Layer newLayer(String name, boolean visible)
```


निर्दिष्ट नाम और दृश्यता के साथ [Layer](../../com.groupdocs.viewer.results/layer) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | लेयर का नाम। |
|
|  | visible | boolean | लेयर की दृश्यता। |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayer(String name) {#newLayer-java.lang.String-}
```
public Layer newLayer(String name)
```


निर्दिष्ट नाम के साथ [Layer](../../com.groupdocs.viewer.results/layer) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | लेयर का नाम। |
|

**Returns:**
[Layer](../../com.groupdocs.viewer.results/layer) - a new instance of the [Layer](../../com.groupdocs.viewer.results/layer) implementation.

### newLayout(String name, double width, double height) {#newLayout-java.lang.String-double-double-}
```
public Layout newLayout(String name, double width, double height)
```


निर्दिष्ट नाम, चौड़ाई और ऊँचाई के साथ [Layout](../../com.groupdocs.viewer.results/layout) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | लेआउट का नाम। |
|
|  | width | double | लेआउट की चौड़ाई। |
|
|  | ऊँचाई | double | लेआउट की ऊँचाई। |
|

**Returns:**
[Layout](../../com.groupdocs.viewer.results/layout) - a new instance of the [Layout](../../com.groupdocs.viewer.results/layout) implementation.

### newLine(String line, double x, double y, double width, double height, List<Word> words) {#newLine-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Word--}
```
public Line newLine(String line, double x, double y, double width, double height, List<Word> words)
```


निर्दिष्ट लाइन, स्थिति, आयाम और शब्दों के साथ [Line](../../com.groupdocs.viewer.results/line) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | line | java.lang.String | लाइन की सामग्री। |
|
|  | x | double | लाइन को सम्मिलित करने वाले आयत के शीर्ष-बाएँ बिंदु का X निर्देशांक। |
|
|  | y | double | लाइन को सम्मिलित करने वाले आयत के शीर्ष-बाएँ बिंदु का Y निर्देशांक। |
|
|  | width | double | रेखा को सम्मिलित करने वाले आयत की चौड़ाई (पिक्सेल में)। |
|
|  | ऊँचाई | double | रेखा को सम्मिलित करने वाले आयत की ऊँचाई (पिक्सेल में)। |
|
|  | शब्द | java.util.List<com.groupdocs.viewer.results.Word> | रेखा में सम्मिलित शब्द। |
|

**Returns:**
[Line](../../com.groupdocs.viewer.results/line) - a new instance of the [Line](../../com.groupdocs.viewer.results/line) implementation.

### newAttachment(String fileName, String filePath) {#newAttachment-java.lang.String-java.lang.String-}
```
public Attachment newAttachment(String fileName, String filePath)
```


[Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileName | java.lang.String | संलग्नक का नाम। |
|
|  | filePath | java.lang.String | संलग्नक का सापेक्ष पथ, उदाहरण के लिए "folder/file.docx"। जब फ़ाइल एक संग्रह के मूल में, ईमेल संदेश में, या डेटा फ़ाइल में स्थित हो, तो फ़ाइलनाम निर्दिष्ट करें। |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, long size)
```


[Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | id | java.lang.String | संलग्नक का आईडी। |
|
|  | fileName | java.lang.String | संलग्नक का नाम। |
|
|  | filePath | java.lang.String | संलग्नक का सापेक्ष पथ, उदाहरण के लिए "folder/file.docx"। जब फ़ाइल एक संग्रह के मूल में, ईमेल संदेश में, या डेटा फ़ाइल में स्थित हो, तो फ़ाइलनाम निर्दिष्ट करें। |
|
|  | size | long | संलग्नक का आकार। |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, Path filePath, long size) {#newAttachment-java.lang.String-java.lang.String-java.nio.file.Path-long-}
```
public Attachment newAttachment(String id, String fileName, Path filePath, long size)
```


[Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | id | java.lang.String | संलग्नक का आईडी। |
|
|  | fileName | java.lang.String | संलग्नक का नाम। |
|
|  | filePath | java.nio.file.Path | संलग्नक का सापेक्ष या पूर्ण पथ। |
|
|  | size | long | संलग्नक का आकार। |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newAttachment(String id, String fileName, String filePath, FileType fileType, long size) {#newAttachment-java.lang.String-java.lang.String-java.lang.String-com.groupdocs.viewer.FileType-long-}
```
public Attachment newAttachment(String id, String fileName, String filePath, FileType fileType, long size)
```


एक [Attachment](../../com.groupdocs.viewer.results/attachment) इंटरफ़ेस का कार्यान्वयन बनाता है। संलग्नक एक दस्तावेज़ या ईमेल संदेश से जुड़ी फ़ाइल को दर्शाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | id | java.lang.String | संलग्नक का आईडी। |
|
|  | fileName | java.lang.String | संलग्नक का नाम। |
|
|  | filePath | java.lang.String | संलग्नक का सापेक्ष या पूर्ण पथ। यह फ़ोल्डर के भीतर फ़ाइल पथ या फ़ाइलनाम स्वयं हो सकता है यदि फ़ाइल एक संग्रह के मूल में, ईमेल संदेश में, या डेटा फ़ाइल में स्थित हो। |
|
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | संलग्नक फ़ाइल का प्रकार। |
|
|  | size | long | संलग्नक का आकार। |
|

**Returns:**
[Attachment](../../com.groupdocs.viewer.results/attachment) - a new instance of the [Attachment](../../com.groupdocs.viewer.results/attachment) implementation.

### newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders) {#newOutlookViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-java.lang.String--}
```
public OutlookViewInfo newOutlookViewInfo(FileType fileType, List<Page> pages, List<String> folders)
```


निर्दिष्ट फ़ाइल प्रकार के आधार पर [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है,
पृष्ठों की सूची, और फ़ोल्डरों की सूची।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
|
|  | पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | पृष्ठों की सूची। |
|
|  | folders | java.util.List<java.lang.String> | फ़ोल्डरों की सूची। |
|

**Returns:**
[OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) - a new instance of the [OutlookViewInfo](../../com.groupdocs.viewer.results/outlookviewinfo) implementation.

### newPage(int number, boolean visible) {#newPage-int-boolean-}
```
public Page newPage(int number, boolean visible)
```


निर्दिष्ट संख्या और दृश्यता वाले पृष्ठ को दर्शाने वाला [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | number | int | पृष्ठ संख्या। |
|
|  | visible | boolean | दृश्यता फ़्लैग। |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible) {#newPage-int-java.lang.String-boolean-}
```
public Page newPage(int number, String name, boolean visible)
```


निर्दिष्ट संख्या, नाम और दृश्यता वाले पृष्ठ को दर्शाने वाला [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | number | int | पृष्ठ संख्या। |
|
|  | नाम | java.lang.String | पृष्ठ का नाम। |
|
|  | visible | boolean | दृश्यता फ़्लैग। |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height) {#newPage-int-java.lang.String-boolean-int-int-}
```
public Page newPage(int number, String name, boolean visible, int width, int height)
```


निर्दिष्ट संख्या, नाम, दृश्यता, चौड़ाई और ऊँचाई वाले पृष्ठ को दर्शाने वाला [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | number | int | पृष्ठ संख्या। |
|
|  | नाम | java.lang.String | पृष्ठ का नाम। |
|
|  | visible | boolean | दृश्यता फ़्लैग। |
|
|  | width | int | पृष्ठ की चौड़ाई। |
|
|  | ऊँचाई | int | पृष्ठ की ऊँचाई। |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height) {#newPage-int-boolean-int-int-}
```
public Page newPage(int number, boolean visible, int width, int height)
```


निर्दिष्ट संख्या, दृश्यता, चौड़ाई और ऊँचाई वाले पृष्ठ को दर्शाने वाला [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | number | int | पृष्ठ संख्या। |
|
|  | visible | boolean | दृश्यता फ़्लैग। |
|
|  | width | int | पृष्ठ की चौड़ाई। |
|
|  | ऊँचाई | int | पृष्ठ की ऊँचाई। |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, String name, boolean visible, int width, int height, List<Line> lines) {#newPage-int-java.lang.String-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, String name, boolean visible, int width, int height, List<Line> lines)
```


निर्दिष्ट संख्या, नाम, दृश्यता, चौड़ाई, ऊँचाई और लाइनों वाले पृष्ठ को दर्शाने वाला [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | number | int | पृष्ठ संख्या। |
|
|  | नाम | java.lang.String | पृष्ठ का नाम। |
|
|  | visible | boolean | दृश्यता फ़्लैग। |
|
|  | width | int | पृष्ठ की चौड़ाई। |
|
|  | ऊँचाई | int | पृष्ठ की ऊँचाई। |
|
|  | रेखाएँ | java.util.List<com.groupdocs.viewer.results.Line> | पृष्ठ में सम्मिलित लाइनों। |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPage(int number, boolean visible, int width, int height, List<Line> lines) {#newPage-int-boolean-int-int-java.util.List-com.groupdocs.viewer.results.Line--}
```
public Page newPage(int number, boolean visible, int width, int height, List<Line> lines)
```


निर्दिष्ट संख्या, दृश्यता, चौड़ाई, ऊँचाई और लाइनों वाले पृष्ठ को दर्शाने वाला [Page](../../com.groupdocs.viewer.results/page) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | number | int | पृष्ठ संख्या। |
|
|  | visible | boolean | दृश्यता फ़्लैग। |
|
|  | width | int | पृष्ठ की चौड़ाई। |
|
|  | ऊँचाई | int | पृष्ठ की ऊँचाई। |
|
|  | रेखाएँ | java.util.List<com.groupdocs.viewer.results.Line> | पृष्ठ में सम्मिलित लाइनों। |
|

**Returns:**
[Page](../../com.groupdocs.viewer.results/page) - a new instance of the [Page](../../com.groupdocs.viewer.results/page) implementation.

### newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed) {#newPdfViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--boolean-}
```
public PdfViewInfo newPdfViewInfo(FileType fileType, List<Page> pages, boolean printingAllowed)
```


निर्दिष्ट फ़ाइल प्रकार, पृष्ठ और प्रिंटिंग अनुमति फ़्लैग के साथ [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
|
|  | पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | पृष्ठों की सूची। |
|
|  | printingAllowed | boolean | प्रिंटिंग की अनुमति है या नहीं दर्शाने वाला फ़्लैग। |
|

**Returns:**
[PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) - a new instance of the [PdfViewInfo](../../com.groupdocs.viewer.results/pdfviewinfo) implementation.

### newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts) {#newCadViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.List-com.groupdocs.viewer.results.Layer--java.util.List-com.groupdocs.viewer.results.Layout--}
```
public CadViewInfo newCadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```


निर्दिष्ट फ़ाइल प्रकार, पृष्ठ, लेयर और लेआउट के साथ [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
|
|  | पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | पृष्ठों की सूची। |
|
|  | layers | java.util.List<com.groupdocs.viewer.results.Layer> | परतों की सूची। |
|
|  | layouts | java.util.List<com.groupdocs.viewer.results.Layout> | लेआउट्स की सूची। |
|

**Returns:**
[CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) - a new instance of the [CadViewInfo](../../com.groupdocs.viewer.results/cadviewinfo) implementation.

### newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate) {#newProjectManagementViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--java.util.Date-java.util.Date-}
```
public ProjectManagementViewInfo newProjectManagementViewInfo(FileType fileType, List<Page> pages, Date startDate, Date endDate)
```


निर्दिष्ट फ़ाइल प्रकार, पृष्ठ, प्रारंभ तिथि और समाप्ति तिथि के साथ [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल प्रकार। |
|
|  | पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | पृष्ठों की सूची। |
|
|  | startDate | java.util.Date | प्रारंभ तिथि। |
|
|  | endDate | java.util.Date | समाप्ति तिथि। |
|

**Returns:**
[ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) - a new instance of the [ProjectManagementViewInfo](../../com.groupdocs.viewer.results/projectmanagementviewinfo) implementation.

### <T>newTextElement(T value, double x, double y, double width, double height) {#-T-newTextElement-T-double-double-double-double-}
```
public TextElement<T> <T>newTextElement(T value, double x, double y, double width, double height)
```


निर्दिष्ट मान, निर्देशांक और आयाम के साथ [TextElement](../../com.groupdocs.viewer.results/textelement) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | T | मान। |
|
|  | x | double | X निर्देशांक। |
|
|  | y | double | Y निर्देशांक। |
|
|  | width | double | चौड़ाई। |
|
|  | ऊँचाई | double | ऊँचाई। |
|

**Returns:**
[TextElement](../../com.groupdocs.viewer.results/textelement) - a new instance of the [TextElement](../../com.groupdocs.viewer.results/textelement) implementation.

### newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount) {#newMboxViewInfo-com.groupdocs.viewer.FileType-java.util.List-com.groupdocs.viewer.results.Page--int-}
```
public MboxViewInfo newMboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
```


निर्दिष्ट फ़ाइल प्रकार, पृष्ठ और नोट्स गिनती के साथ MboxViewInfo इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.viewer/filetype) | फ़ाइल का प्रकार। |
|
|  | पृष्ठ | java.util.List<com.groupdocs.viewer.results.Page> | देखने के लिए पृष्ठों की सूची। |
|
|  | notesCount | int | Lotus डेटाबेस स्टोरेज फ़ाइल में सम्मिलित नोट्स की गिनती। |
|

**Returns:**
com.groupdocs.viewer.results.MboxViewInfo - MboxViewInfo कार्यान्वयन का एक नया उदाहरण।

### newWord(String word, double x, double y, double width, double height, List<Character> characters) {#newWord-java.lang.String-double-double-double-double-java.util.List-com.groupdocs.viewer.results.Character--}
```
public Word newWord(String word, double x, double y, double width, double height, List<Character> characters)
```


निर्दिष्ट शब्द, निर्देशांक, आयाम और अक्षरों के साथ [Word](../../com.groupdocs.viewer.results/word) इंटरफ़ेस का कार्यान्वयन बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | word | java.lang.String | शब्द। |
|
|  | x | double | पृष्ठ लेआउट में सबसे बाएँ ऊँचे बिंदु का X निर्देशांक जहाँ वह आयत शुरू होती है जो शब्द को सम्मिलित करती है। |
|
|  | y | double | पृष्ठ लेआउट में सबसे बाएँ ऊँचे बिंदु का Y निर्देशांक जहाँ वह आयत शुरू होती है जो शब्द को सम्मिलित करती है। |
|
|  | width | double | उस आयत की चौड़ाई जो शब्द को सम्मिलित करती है (पिक्सेल में)। |
|
|  | ऊँचाई | double | उस आयत की ऊँचाई जो शब्द को सम्मिलित करती है (पिक्सेल में)। |
|
|  | अक्षर | java.util.List<com.groupdocs.viewer.results.Character> | शब्द में सम्मिलित अक्षर। |
|

**Returns:**
[Word](../../com.groupdocs.viewer.results/word) - a new instance of the [Word](../../com.groupdocs.viewer.results/word) implementation.

