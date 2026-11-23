---
title: "FileLogger"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "लॉग संदेशों को फ़ाइल में लिखता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

लॉग संदेशों को फ़ाइल में लिखता है।


यह
FileLogger
क्लास फ़ाइल में लॉग संदेश लिखने की कार्यक्षमता प्रदान करती है। यह ILogger इंटरफ़ेस को लागू करती है।
और इसे किसी एप्लिकेशन में विभिन्न घटनाओं और संदेशों को लॉग करने के लिए उपयोग किया जा सकता है। लॉग संदेश निर्दिष्ट फ़ाइल में लिखे जाते हैं।


उदाहरण उपयोग:

````

 // Create a new instance of FileLogger with the specified log file path
 FileLogger fileLogger = new FileLogger("/path/to/logfile.txt");

 // Log an informational message
 fileLogger.debug("Debug message");

 // Log an error message
 fileLogger.error("Error message");

 // Check is logging warning messages enabled
 boolean warningEnabled = fileLogger.isWarningEnabled();
 
````


***Note:** The 
FileLogger
क्लास बुनियादी लॉगिंग कार्यक्षमता प्रदान करती है।
आप अपनी आवश्यकताओं के अनुसार इस क्लास को विस्तारित करके कस्टम लॉग स्तर या अतिरिक्त लॉगिंग सुविधाएँ जोड़ सकते हैं।*

## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | प्रदान किए गए फ़ाइल नाम द्वारा निर्दिष्ट फ़ाइल में संदेशों को लॉग करने वाला लॉगर बनाता है। |
|
|  | [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | निर्दिष्ट लॉगिंग स्तरों के साथ फ़ाइल में संदेशों को लॉग करने वाला लॉगर बनाता है। |
|
## Fields

| Field | विवरण |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Methods

| Method | विवरण |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | कंसोल में एक ट्रेस संदेश लिखता है। |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | कंसोल में एक ट्रेस लॉग संदेश लिखता है। |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | जाँचता है कि लॉगिंग के लिए ट्रेस स्तर सक्षम है या नहीं। |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | कंसोल में एक डिबग लॉग संदेश लिखता है। |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | कंसोल में एक डिबग लॉग संदेश लिखता है। |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | जाँचता है कि लॉगिंग के लिए डिबग स्तर सक्षम है या नहीं। |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | कंसोल में एक चेतावनी लॉग संदेश लिखता है। |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | कंसोल में एक चेतावनी लॉग संदेश लिखता है। |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | जाँचता है कि लॉगिंग के लिए चेतावनी स्तर सक्षम है या नहीं। |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | कंसोल में एक त्रुटि लॉग संदेश लिखता है। |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | कंसोल में एक त्रुटि लॉग संदेश लिखता है। |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | जाँचता है कि त्रुटि-स्तर की लॉगिंग सक्षम है या नहीं। |
|
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


प्रदान किए गए फ़ाइल नाम द्वारा निर्दिष्ट फ़ाइल में संदेशों को लॉग करने वाला लॉगर बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileName | java.lang.String | पथ सहित पूर्ण फ़ाइल नाम। |
|

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


निर्दिष्ट लॉगिंग स्तरों के साथ फ़ाइल में संदेशों को लॉग करने वाला लॉगर बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fileName | java.lang.String | पथ सहित पूर्ण फ़ाइल नाम। |
|
|  | isTraceEnabled | boolean | निर्दिष्ट करता है कि ट्रेस स्तर की लॉगिंग सक्षम है या नहीं। |
|
|  | isDebugEnabled | boolean | निर्दिष्ट करता है कि डिबग स्तर की लॉगिंग सक्षम है या नहीं। |
|
|  | isWarningEnabled | boolean | निर्दिष्ट करता है कि चेतावनी स्तर की लॉगिंग सक्षम है या नहीं। |
|
|  | isErrorEnabled | boolean | निर्दिष्ट करता है कि त्रुटि स्तर की लॉगिंग सक्षम है या नहीं। |
|

### MESSAGE {#MESSAGE}
```
public static final String MESSAGE
```


### EXCEPTION {#EXCEPTION}
```
public static final String EXCEPTION
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public void trace(String message, Object[] arguments)
```


कंसोल में एक ट्रेस संदेश लिखता है।
ट्रेस लॉग संदेश एप्लिकेशन प्रवाह के बारे में सामान्यतः उपयोगी जानकारी प्रदान करते हैं।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | ट्रेस संदेश। |
|
|  | आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास करने के क्रम में {} प्लेसहोल्डर को बदलेंगे। |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


कंसोल में एक ट्रेस लॉग संदेश लिखता है।
ट्रेस लॉग संदेश एप्लिकेशन प्रवाह के बारे में सामान्य रूप से उपयोगी जानकारी प्रदान करते हैं।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | ट्रेस लॉग संदेश से संबंधित अपवाद। |
|
|  | संदेश | java.lang.String | ट्रेस लॉग संदेश। |
|
|  | आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में {} प्लेसहोल्डर को बदलेंगे। |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


जाँचता है कि लॉगिंग के लिए ट्रेस स्तर सक्षम है या नहीं।


**Returns:**
boolean -  true  यदि ट्रेस स्तर सक्षम है,  false  अन्यथा।

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


कंसोल में एक डिबग लॉग संदेश लिखता है।
डिबग लॉग संदेश एप्लिकेशन प्रवाह में विभिन्न प्रक्रियाओं के बारे में जानकारी प्रदान करते हैं।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | डिबग लॉग संदेश। |
|
|  | आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में {} प्लेसहोल्डर को बदलेंगे। |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


कंसोल में एक डिबग लॉग संदेश लिखता है।
डिबग लॉग संदेश एप्लिकेशन प्रवाह में विभिन्न प्रक्रियाओं के बारे में जानकारी प्रदान करते हैं।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | डिबग लॉग संदेश से संबंधित अपवाद। |
|
|  | संदेश | java.lang.String | डिबग लॉग संदेश। |
|
|  | आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में {} प्लेसहोल्डर को बदलेंगे। |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


जाँचता है कि लॉगिंग के लिए डिबग स्तर सक्षम है या नहीं।


**Returns:**
boolean -  true  यदि डिबग स्तर सक्षम है,  false  अन्यथा।

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


कंसोल में एक चेतावनी लॉग संदेश लिखता है।
वॉर्निंग लॉग संदेश एप्लिकेशन प्रवाह में अप्रत्याशित और पुनर्प्राप्तीय घटनाओं के बारे में जानकारी प्रदान करते हैं।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | वॉर्निंग लॉग संदेश। |
|
|  | आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में {} प्लेसहोल्डर को बदलेंगे। |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


कंसोल में एक चेतावनी लॉग संदेश लिखता है।
वॉर्निंग लॉग संदेश एप्लिकेशन प्रवाह में अप्रत्याशित और पुनर्प्राप्तीय घटनाओं के बारे में जानकारी प्रदान करते हैं।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | वॉर्निंग लॉग संदेश से संबंधित अपवाद। |
|
|  | संदेश | java.lang.String | वॉर्निंग लॉग संदेश। |
|
|  | आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में {} प्लेसहोल्डर को बदलेंगे। |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


जाँचता है कि लॉगिंग के लिए चेतावनी स्तर सक्षम है या नहीं।


**Returns:**
boolean -  true  यदि वॉर्निंग स्तर सक्षम है,  false  अन्यथा।

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


कंसोल में एक त्रुटि लॉग संदेश लिखता है।
एरर लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं के बारे में जानकारी प्रदान करते हैं।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | संदेश | java.lang.String | एरर लॉग संदेश। |
|
|  | आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में {} प्लेसहोल्डर को बदलेंगे। |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


कंसोल में एक त्रुटि लॉग संदेश लिखता है।
एरर लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं के बारे में जानकारी प्रदान करते हैं।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | एरर लॉग संदेश से संबंधित अपवाद। |
|
|  | संदेश | java.lang.String | एरर लॉग संदेश। |
|
|  | आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में {} प्लेसहोल्डर को बदलेंगे। |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


जाँचता है कि त्रुटि-स्तर की लॉगिंग सक्षम है या नहीं।


**Returns:**
boolean -  true  यदि एरर-लेवल लॉगिंग सक्षम है,  false  अन्यथा।

