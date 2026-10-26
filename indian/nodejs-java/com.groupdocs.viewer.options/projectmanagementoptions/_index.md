---
title: "ProjectManagementOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "प्रोजेक्ट प्रबंधन फ़ाइलों को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 27
url: /hi/nodejs-java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

प्रोजेक्ट प्रबंधन फ़ाइलों को रेंडर करने के विकल्प प्रदान करता है।

ProjectManagementOptions क्लास विभिन्न सेटिंग्स और पैरामीटर को समाहित करती है जिन्हें GroupDocs.Viewer घटक में प्रोजेक्ट मैनेजमेंट फ़ाइलों (जैसे Microsoft Project या समान) की रेंडरिंग को नियंत्रित करने के लिए उपयोग किया जा सकता है। विवरण के लिए, देखें [documentation][].

उदाहरण उपयोग:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 ProjectManagementOptions projectManagementOptions = pngViewOptions.getProjectManagementOptions();
 projectManagementOptions.setPageSize(PageSize.A4);
 projectManagementOptions.setStartDate(new Date(2021, 11, 23));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ProjectManagementOptions()](#ProjectManagementOptions--) | ProjectManagementOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getPageSize()](#getPageSize--) | आउटपुट पेज आकार प्राप्त करता है। |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | आउटपुट पेज आकार सेट करता है। |
| [getTimeUnit()](#getTimeUnit--) | समय इकाई प्राप्त करता है। |
| [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | समय इकाई प्राप्त करता है। |
| [getStartDate()](#getStartDate--) | आउटपुट में शामिल किए जाने वाले Gantt Chart View की प्रारंभ तिथि प्राप्त करता है। |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | आउटपुट में शामिल किए जाने वाले Gantt Chart View की प्रारंभ तिथि सेट करता है। |
| [getEndDate()](#getEndDate--) | आउटपुट में शामिल किए जाने वाले Gantt Chart View की समाप्ति तिथि प्राप्त करता है। |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | आउटपुट में शामिल किए जाने वाले Gantt Chart View की समाप्ति तिथि सेट करता है। |
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


ProjectManagementOptions क्लास का एक नया इंस्टेंस प्रारंभ करता है।

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


आउटपुट पेज आकार प्राप्त करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


आउटपुट पेज आकार सेट करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | आउटपुट पेज आकार। |

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


समय इकाई प्राप्त करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.
### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


समय इकाई प्राप्त करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | समय इकाई। |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


आउटपुट में शामिल किए जाने वाले Gantt Chart View की प्रारंभ तिथि प्राप्त करता है।

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - Gantt Chart View की प्रारंभ तिथि।
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


आउटपुट में शामिल किए जाने वाले Gantt Chart View की प्रारंभ तिथि सेट करता है।

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date | Gantt Chart View की प्रारंभ तिथि। |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


आउटपुट में शामिल किए जाने वाले Gantt Chart View की समाप्ति तिथि प्राप्त करता है।

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - Gantt Chart View की समाप्ति तिथि।
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


आउटपुट में शामिल किए जाने वाले Gantt Chart View की समाप्ति तिथि सेट करता है।

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.Date | Gantt Chart View की समाप्ति तिथि। |

