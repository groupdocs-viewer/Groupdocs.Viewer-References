---
title: "FileLogger"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "लॉग संदेशों को फ़ाइल में लिखता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

लॉग संदेशों को फ़ाइल में लिखता है।

FileLogger क्लास फ़ाइल में लॉग संदेश लिखने की कार्यक्षमता प्रदान करती है। यह ILogger इंटरफ़ेस को लागू करती है और एप्लिकेशन में विभिन्न घटनाओं और संदेशों को लॉग करने के लिए उपयोग की जा सकती है। लॉग संदेश निर्दिष्ट फ़ाइल में लिखे जाते हैं।

उदाहरण उपयोग:

```

 // Create a new instance of FileLogger with the specified log file path
 FileLogger fileLogger = new FileLogger("/path/to/logfile.txt");

 // Log an informational message
 fileLogger.debug("Debug message");

 // Log an error message
 fileLogger.error("Error message");

 // Check is logging warning messages enabled
 boolean warningEnabled = fileLogger.isWarningEnabled();
 
```

***Note:** The  FileLogger  class provides basic logging functionality. You can extend this class to add custom log levels or additional logging features as per your requirements.*
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | प्रदान किए गए फ़ाइल नाम द्वारा निर्दिष्ट फ़ाइल में संदेशों को लॉग करने वाला एक लॉगर बनाता है। |
| [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | निर्दिष्ट लॉगिंग स्तरों के साथ फ़ाइल में संदेशों को लॉग करने वाला एक लॉगर बनाता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
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
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


प्रदान किए गए फ़ाइल नाम द्वारा निर्दिष्ट फ़ाइल में संदेशों को लॉग करने वाला एक लॉगर बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | पथ सहित पूर्ण फ़ाइल नाम। |

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


निर्दिष्ट लॉगिंग स्तरों के साथ फ़ाइल में संदेशों को लॉग करने वाला एक लॉगर बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | पथ सहित पूर्ण फ़ाइल नाम। |
| isTraceEnabled | boolean | निर्दिष्ट करता है कि क्या ट्रेस स्तर का लॉगिंग सक्षम है। |
| isDebugEnabled | boolean | निर्दिष्ट करता है कि क्या डिबग स्तर का लॉगिंग सक्षम है। |
| isWarningEnabled | boolean | निर्दिष्ट करता है कि क्या चेतावनी स्तर का लॉगिंग सक्षम है। |
| isErrorEnabled | boolean | निर्दिष्ट करता है कि क्या त्रुटि स्तर का लॉगिंग सक्षम है। |

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


कंसोल में एक ट्रेस संदेश लिखता है। ट्रेस लॉग संदेश एप्लिकेशन प्रवाह के बारे में सामान्यतः उपयोगी जानकारी प्रदान करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | ट्रेस संदेश। |
| आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए आर्ग्युमेंट्स। वे पास करने के क्रम में \\{\\} प्लेसहोल्डर को बदलेंगे। |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
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
public boolean isTraceEnabled()
```


जाँचता है कि लॉगिंग के लिए ट्रेस लेवल सक्षम है या नहीं।

**Returns:**
boolean -  true  यदि ट्रेस स्तर सक्षम है,  false  अन्यथा।
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


कंसोल पर एक डिबग लॉग संदेश लिखता है। डिबग लॉग संदेश एप्लिकेशन प्रवाह में विभिन्न प्रक्रियाओं के बारे में जानकारी प्रदान करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | डिबग लॉग संदेश। |
| आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में \{\} प्लेसहोल्डर को बदल देंगे। |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
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
public boolean isDebugEnabled()
```


जाँचता है कि लॉगिंग के लिए डिबग लेवल सक्षम है या नहीं।

**Returns:**
boolean -  true  यदि डिबग स्तर सक्षम है,  false  अन्यथा।
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


कंसोल पर एक चेतावनी लॉग संदेश लिखता है। चेतावनी लॉग संदेश एप्लिकेशन प्रवाह में अप्रत्याशित और पुनर्प्राप्ति योग्य घटनाओं के बारे में जानकारी प्रदान करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | चेतावनी लॉग संदेश। |
| आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में \{\} प्लेसहोल्डर को बदल देंगे। |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
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
public boolean isWarningEnabled()
```


जाँचता है कि लॉगिंग के लिए चेतावनी लेवल सक्षम है या नहीं।

**Returns:**
boolean -  true  यदि चेतावनी स्तर सक्षम है,  false  अन्यथा।
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


कंसोल पर एक त्रुटि लॉग संदेश लिखता है। त्रुटि लॉग संदेश एप्लिकेशन प्रवाह में अपरिवर्तनीय घटनाओं के बारे में जानकारी प्रदान करते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | त्रुटि लॉग संदेश। |
| आर्ग्युमेंट्स | java.lang.Object[] | संदेश में बदलने के लिए तर्क। वे पास किए जाने के क्रम में \{\} प्लेसहोल्डर को बदल देंगे। |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
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
public boolean isErrorEnabled()
```


जाँचता है कि त्रुटि-स्तर की लॉगिंग सक्षम है या नहीं।

**Returns:**
boolean -  true  यदि त्रुटि-स्तर लॉगिंग सक्षम है,  false  अन्यथा।
