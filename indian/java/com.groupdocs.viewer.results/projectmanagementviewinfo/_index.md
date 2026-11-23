---
title: "ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "MS Project दस्तावेज़ के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।"
type: docs
weight: 25
url: /hi/java/com.groupdocs.viewer.results/projectmanagementviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface ProjectManagementViewInfo extends ViewInfo
```

MS Project दस्तावेज़ के लिए दृश्य जानकारी का प्रतिनिधित्व करता है।


ProjectManagementViewInfo इंटरफ़ेस दृश्य जानकारी तक पहुँचने और उसे संशोधित करने के अनुबंध को परिभाषित करता है
GroupDocs.Viewer घटक में एक MS Project दस्तावेज़ के लिए। यह जानकारी प्राप्त करने के लिए विधियाँ प्रदान करता है
जैसे कि प्रारंभ और समाप्ति तिथियाँ, तथा अन्य गुण।


उदाहरण उपयोग:

````

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ProjectManagementViewInfo viewInfo = (ProjectManagementViewInfo) viewer.getViewInfo(ViewInfoOptions.forPngView());
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is ProjectManagementViewInfoImpl.*

## Methods

| Method | विवरण |
| --- | --- |
|  | [getStartDate()](#getStartDate--) | प्रोजेक्ट के शुरू होने की तिथि और समय प्राप्त करता है। |
|
|  | [setStartDate(Date startDate)](#setStartDate-java.util.Date-) | प्रोजेक्ट के लिए प्रारंभ तिथि और समय सेट करता है। |
|
|  | [getEndDate()](#getEndDate--) | प्रोजेक्ट के पूर्ण होने की तिथि और समय प्राप्त करता है। |
|
|  | [setEndDate(Date endDate)](#setEndDate-java.util.Date-) | प्रोजेक्ट के लिए समाप्ति तिथि और समय सेट करता है। |
|
### getStartDate() {#getStartDate--}
```
public abstract Date getStartDate()
```


प्रोजेक्ट के शुरू होने की तिथि और समय प्राप्त करता है।


**Returns:**
java.util.Date - प्रोजेक्ट की प्रारंभ तिथि और समय।

### setStartDate(Date startDate) {#setStartDate-java.util.Date-}
```
public abstract void setStartDate(Date startDate)
```


प्रोजेक्ट के लिए प्रारंभ तिथि और समय सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | startDate | java.util.Date | सेट की जाने वाली नई प्रारंभ तिथि और समय। |
|

### getEndDate() {#getEndDate--}
```
public abstract Date getEndDate()
```


प्रोजेक्ट के पूर्ण होने की तिथि और समय प्राप्त करता है।


**Returns:**
java.util.Date - प्रोजेक्ट की समाप्ति तिथि और समय।

### setEndDate(Date endDate) {#setEndDate-java.util.Date-}
```
public abstract void setEndDate(Date endDate)
```


प्रोजेक्ट के लिए समाप्ति तिथि और समय सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | endDate | java.util.Date | सेट की जाने वाली नई समाप्ति तिथि और समय। |
|

