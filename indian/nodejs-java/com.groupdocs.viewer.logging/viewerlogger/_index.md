---
title: "ViewerLogger"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "वैश्विक व्यूअर लॉगर।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

वैश्विक व्यूअर लॉगर।

ViewerLogger क्लास एकीकृत या उपयोगकर्ता-परिभाषित लॉगर में संदेश लॉग करने की कार्यक्षमता प्रदान करती है। यह व्यूअर मॉड्यूल के लिए वैश्विक लॉगर के रूप में कार्य करती है और विभिन्न घटनाओं और संदेशों को लॉग करने के लिए उपयोग की जा सकती है।

उदाहरण उपयोग:

```

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
```

***Note:** The  ViewerLogger  class can be configured to use a custom logger implementation by calling the [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger\#setLogger-ILogger-) method. By default, it uses the integrated logger provided by the viewer module.*
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | कंसोल में एक ट्रेस संदेश लिखता है। |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | कंसोल में एक ट्रेस लॉग संदेश लिखता है। |
| [isTraceEnabled()](#isTraceEnabled--) | जाँचता है कि लॉगिंग के लिए ट्रेस लेवल सक्षम है या नहीं। |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | कंसोल में एक डिबग लॉग संदेश लिखता है। |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | कंसोल में एक डिबग लॉग संदेश लिखता है। |
| [isDebugEnabled()](#isDebugEnabled--) | जाँचता है कि लॉगिंग के लिए डिबग लेवल सक्षम है या नहीं। |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | कंसोल में एक चेतावनी लॉग संदेश लिखता है। |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | कंसोल में एक चेतावनी लॉग संदेश लिखता है। |
| [isWarningEnabled()](#isWarningEnabled--) | जाँचता है कि लॉगिंग के लिए चेतावनी लेवल सक्षम है या नहीं। |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | कंसोल में एक त्रुटि लॉग संदेश लिखता है। |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | कंसोल में एक त्रुटि लॉग संदेश लिखता है। |
| [isErrorEnabled()](#isErrorEnabled--) | जाँचता है कि त्रुटि-स्तर की लॉगिंग सक्षम है या नहीं। |
| [getLogger()](#getLogger--) | लॉग संदेशों के लिए उपयोग किए जाने वाले लॉगर इंस्टेंस को प्राप्त करता है। |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | लॉग संदेशों के लिए उपयोग किए जाने वाले लॉगर इंस्टेंस को सेट करता है। |
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


कंसोल में एक ट्रेस संदेश लिखता है। ट्रेस लॉग संदेश एप्लिकेशन प्रवाह के बारे में सामान्यतः उपयोगी जानकारी प्रदान करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | ट्रेस संदेश। |
| आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए आर्ग्युमेंट्स। वे पास करने के क्रम में \\{\\} प्लेसहोल्डर को बदलेंगे। |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
```


कंसोल पर एक ट्रेस लॉग संदेश लिखता है। ट्रेस लॉग संदेश एप्लिकेशन प्रवाह के बारे में सामान्य रूप से उपयोगी जानकारी प्रदान करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| throwable | java.lang.Throwable | ट्रेस लॉग संदेश से संबंधित अपवाद। |
| संदेश | java.lang.String | ट्रेस लॉग संदेश। |
| आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में \{\} प्लेसहोल्डर को बदल देंगे। |

### isTraceEnabled() {#isTraceEnabled--}
```
public static boolean isTraceEnabled()
```


जाँचता है कि लॉगिंग के लिए ट्रेस लेवल सक्षम है या नहीं।

**Returns:**
boolean -  true  यदि ट्रेस स्तर सक्षम है,  false  अन्यथा।
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


कंसोल पर एक डिबग लॉग संदेश लिखता है। डिबग लॉग संदेश एप्लिकेशन प्रवाह में विभिन्न प्रक्रियाओं के बारे में जानकारी प्रदान करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | डिबग लॉग संदेश। |
| आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में \{\} प्लेसहोल्डर को बदल देंगे। |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
```


कंसोल पर एक डिबग लॉग संदेश लिखता है। डिबग लॉग संदेश एप्लिकेशन प्रवाह में विभिन्न प्रक्रियाओं के बारे में जानकारी प्रदान करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| throwable | java.lang.Throwable | डिबग लॉग संदेश से संबंधित अपवाद। |
| संदेश | java.lang.String | डिबग लॉग संदेश। |
| आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में \{\} प्लेसहोल्डर को बदल देंगे। |

### isDebugEnabled() {#isDebugEnabled--}
```
public static boolean isDebugEnabled()
```


जाँचता है कि लॉगिंग के लिए डिबग लेवल सक्षम है या नहीं।

**Returns:**
boolean -  true  यदि डिबग स्तर सक्षम है,  false  अन्यथा।
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


कंसोल पर एक चेतावनी लॉग संदेश लिखता है। चेतावनी लॉग संदेश एप्लिकेशन प्रवाह में अप्रत्याशित और पुनर्प्राप्ति योग्य घटनाओं के बारे में जानकारी प्रदान करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | चेतावनी लॉग संदेश। |
| आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में \{\} प्लेसहोल्डर को बदल देंगे। |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
```


कंसोल पर एक चेतावनी लॉग संदेश लिखता है। चेतावनी लॉग संदेश एप्लिकेशन प्रवाह में अप्रत्याशित और पुनर्प्राप्ति योग्य घटनाओं के बारे में जानकारी प्रदान करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| throwable | java.lang.Throwable | चेतावनी लॉग संदेश से संबंधित अपवाद। |
| संदेश | java.lang.String | चेतावनी लॉग संदेश। |
| आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में \{\} प्लेसहोल्डर को बदल देंगे। |

### isWarningEnabled() {#isWarningEnabled--}
```
public static boolean isWarningEnabled()
```


जाँचता है कि लॉगिंग के लिए चेतावनी लेवल सक्षम है या नहीं।

**Returns:**
boolean -  true  यदि चेतावनी स्तर सक्षम है,  false  अन्यथा।
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


कंसोल पर एक त्रुटि लॉग संदेश लिखता है। त्रुटि लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं के बारे में जानकारी प्रदान करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | त्रुटि लॉग संदेश। |
| आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में \{\} प्लेसहोल्डर को बदल देंगे। |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
```


कंसोल पर एक त्रुटि लॉग संदेश लिखता है। त्रुटि लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं के बारे में जानकारी प्रदान करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| throwable | java.lang.Throwable | त्रुटि लॉग संदेश से संबंधित अपवाद। |
| संदेश | java.lang.String | त्रुटि लॉग संदेश। |
| आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में \{\} प्लेसहोल्डर को बदल देंगे। |

### isErrorEnabled() {#isErrorEnabled--}
```
public static boolean isErrorEnabled()
```


जाँचता है कि त्रुटि-स्तर की लॉगिंग सक्षम है या नहीं।

**Returns:**
boolean -  true  यदि त्रुटि-स्तर लॉगिंग सक्षम है,  false  अन्यथा।
### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


लॉगर इंस्टेंस प्राप्त करता है जिसका उपयोग संदेशों को लॉग करने के लिए किया जाएगा। लॉगर इंस्टेंस को विभिन्न स्तरों जैसे ट्रेस, डिबग, चेतावनी, और त्रुटि के संदेशों को लॉग करने के लिए उपयोग किया जा सकता है।

**Returns:**
com.groupdocs.foundation.logging.ILogger - लॉगर इंस्टेंस।
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


लॉगर इंस्टेंस सेट करता है जिसका उपयोग संदेशों को लॉग करने के लिए किया जाएगा। लॉगर इंस्टेंस को विभिन्न स्तरों जैसे ट्रेस, डिबग, चेतावनी, और त्रुटि के संदेशों को लॉग करने के लिए उपयोग किया जा सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| लॉगर | com.groupdocs.foundation.logging.ILogger | सेट करने के लिए लॉगर इंस्टेंस। |

