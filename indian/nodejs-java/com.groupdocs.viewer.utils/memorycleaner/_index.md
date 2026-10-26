---
title: "MemoryCleaner"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "विभिन्न संसाधनों को साफ़ करके मेमोरी मुक्त करता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

विभिन्न संसाधनों को साफ़ करके मेमोरी मुक्त करता है।

यह क्लास हीप मेमोरी साफ करने, अस्थायी फ़ाइलें हटाने और फ़ॉन्ट रजिस्ट्री जानकारी साफ करने के लिए मेथड्स प्रदान करती है। इसमें वर्तमान थ्रेड के लिए थ्रेड-लोकल इंस्टेंस को सुरक्षित रूप से साफ करने का एक मेथड भी शामिल है।

उदाहरण उपयोग:

```

 // Clean heap memory, keeping font settings
 MemoryCleaner.clearKeepingFontSettings();

 // Clean heap memory and delete temp files
 MemoryCleaner.clear();

 // Clean heap memory from static PDF instances
 MemoryCleaner.clearStaticInstances();

 // Delete all temp files created by PDF in the system temp directory
 MemoryCleaner.clearAllTempFiles();

 // Clear font registry information from heap memory
 MemoryCleaner.clearFontRegistry();

 // Safely clear thread-local instances for the current thread
 MemoryCleaner.clearCurrentThreadLocals();
 
```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [clearKeepingFontSettings()](#clearKeepingFontSettings--) | स्थैतिक PDF इंस्टेंस (स्थैतिक और थ्रेड-लोकल) से हीप मेमोरी साफ करता है और सभी अस्थायी फ़ाइलें हटाता है। |
| [clear()](#clear--) | स्थैतिक PDF इंस्टेंस (स्थैतिक और थ्रेड-लोकल) से हीप मेमोरी साफ करता है और सभी अस्थायी फ़ाइलें हटाता है। |
| [clearStaticInstances()](#clearStaticInstances--) | स्थैतिक PDF इंस्टेंस से हीप मेमोरी साफ करता है। |
| [clearAllTempFiles()](#clearAllTempFiles--) | सिस्टम के अस्थायी डायरेक्टरी में GroupDocs.Viewer द्वारा बनाई गई अस्थायी फ़ाइलों को साफ करता है। |
| [clearFontRegistry()](#clearFontRegistry--) | हीप मेमोरी से फ़ॉन्ट रजिस्ट्री जानकारी साफ करता है। |
| [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | वर्तमान थ्रेड के लिए थ्रेड-लोकल इंस्टेंस से हीप मेमोरी को सुरक्षित रूप से साफ करता है। |
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


स्थैतिक PDF इंस्टेंस (स्थैतिक और थ्रेड-लोकल) से हीप मेमोरी साफ करता है और सभी अस्थायी फ़ाइलें हटाता है। यह मेथड फ़ॉन्ट सेटिंग्स को प्रभावित नहीं करता।

### clear() {#clear--}
```
public static void clear()
```


स्थैतिक PDF इंस्टेंस (स्थैतिक और थ्रेड-लोकल) से हीप मेमोरी साफ करता है और सभी अस्थायी फ़ाइलें हटाता है।

### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


स्थैतिक PDF इंस्टेंस से हीप मेमोरी साफ करता है।

### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


सिस्टम के अस्थायी डायरेक्टरी में GroupDocs.Viewer द्वारा बनाई गई अस्थायी फ़ाइलों को साफ करता है।

### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


हीप मेमोरी से फ़ॉन्ट रजिस्ट्री जानकारी साफ करता है।

### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


वर्तमान थ्रेड के लिए थ्रेड-लोकल इंस्टेंस से हीप मेमोरी को सुरक्षित रूप से साफ करता है।

