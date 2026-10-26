---
title: "FileLogger"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Γράφει μηνύματα καταγραφής σε αρχείο."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Γράφει μηνύματα καταγραφής σε αρχείο.

Η κλάση  FileLogger  παρέχει λειτουργικότητα για την εγγραφή μηνυμάτων καταγραφής σε αρχείο. Υλοποιεί τη διεπαφή ILogger και μπορεί να χρησιμοποιηθεί για την καταγραφή διαφόρων γεγονότων και μηνυμάτων σε μια εφαρμογή. Τα μηνύματα καταγραφής γράφονται στο καθορισμένο αρχείο.

Παράδειγμα χρήσης:

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
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Δημιουργεί έναν καταγραφέα που καταγράφει μηνύματα σε ένα αρχείο που καθορίζεται από το παρεχόμενο όνομα αρχείου. |
| [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Δημιουργεί έναν καταγραφέα που καταγράφει μηνύματα σε ένα αρχείο με καθορισμένα επίπεδα καταγραφής. |
## Fields

| Field | Περιγραφή |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα trace στην κονσόλα. |
| [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα trace log στην κονσόλα. |
| [isTraceEnabled()](#isTraceEnabled--) | Ελέγχει αν το επίπεδο trace είναι ενεργοποιημένο για καταγραφή. |
| [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα debug log στην κονσόλα. |
| [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα debug log στην κονσόλα. |
| [isDebugEnabled()](#isDebugEnabled--) | Ελέγχει αν το επίπεδο debug είναι ενεργοποιημένο για καταγραφή. |
| [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα warning log στην κονσόλα. |
| [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα warning log στην κονσόλα. |
| [isWarningEnabled()](#isWarningEnabled--) | Ελέγχει αν το επίπεδο warning είναι ενεργοποιημένο για καταγραφή. |
| [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα error log στην κονσόλα. |
| [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα error log στην κονσόλα. |
| [isErrorEnabled()](#isErrorEnabled--) | Ελέγχει αν η καταγραφή σε επίπεδο error είναι ενεργοποιημένη. |
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Δημιουργεί έναν καταγραφέα που καταγράφει μηνύματα σε ένα αρχείο που καθορίζεται από το παρεχόμενο όνομα αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Το πλήρες όνομα αρχείου με τη διαδρομή. |

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Δημιουργεί έναν καταγραφέα που καταγράφει μηνύματα σε ένα αρχείο με καθορισμένα επίπεδα καταγραφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Το πλήρες όνομα αρχείου με τη διαδρομή. |
| isTraceEnabled | boolean | Καθορίζει εάν η καταγραφή σε επίπεδο trace είναι ενεργοποιημένη. |
| isDebugEnabled | boolean | Καθορίζει εάν η καταγραφή σε επίπεδο debug είναι ενεργοποιημένη. |
| isWarningEnabled | boolean | Καθορίζει εάν η καταγραφή σε επίπεδο warning είναι ενεργοποιημένη. |
| isErrorEnabled | boolean | Καθορίζει εάν η καταγραφή σε επίπεδο error είναι ενεργοποιημένη. |

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


Γράφει ένα μήνυμα trace στην κονσόλα. Τα μηνύματα trace log παρέχουν γενικά χρήσιμες πληροφορίες για τη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα trace. |
| ορίσματα | java.lang.Object[] | Τα arguments που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα placeholders \{\} με τη σειρά που περνούν. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής trace στην κονσόλα. Τα μηνύματα καταγραφής trace παρέχουν γενικά χρήσιμες πληροφορίες σχετικά με τη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εξαίρεση | java.lang.Throwable | Η εξαίρεση που σχετίζεται με το μήνυμα καταγραφής trace. |
| μήνυμα | java.lang.String | Το μήνυμα καταγραφής trace. |
| ορίσματα | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα σύμβολα κράτησης θέσης \{\} με τη σειρά που περνιούνται. |

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Ελέγχει αν το επίπεδο trace είναι ενεργοποιημένο για καταγραφή.

**Returns:**
boolean -  true  αν το επίπεδο trace είναι ενεργοποιημένο,  false  διαφορετικά.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής debug στην κονσόλα. Τα μηνύματα καταγραφής debug παρέχουν πληροφορίες για διαφορετικές διαδικασίες στη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα καταγραφής debug. |
| ορίσματα | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα σύμβολα κράτησης θέσης \{\} με τη σειρά που περνιούνται. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής debug στην κονσόλα. Τα μηνύματα καταγραφής debug παρέχουν πληροφορίες για διαφορετικές διαδικασίες στη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εξαίρεση | java.lang.Throwable | Η εξαίρεση που σχετίζεται με το μήνυμα καταγραφής debug. |
| μήνυμα | java.lang.String | Το μήνυμα καταγραφής debug. |
| ορίσματα | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα σύμβολα κράτησης θέσης \{\} με τη σειρά που περνιούνται. |

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Ελέγχει αν το επίπεδο debug είναι ενεργοποιημένο για καταγραφή.

**Returns:**
boolean -  true  αν το επίπεδο debug είναι ενεργοποιημένο,  false  διαφορετικά.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής warning στην κονσόλα. Τα μηνύματα καταγραφής warning παρέχουν πληροφορίες για απρόσμενα και ανακτήσιμα γεγονότα στη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα καταγραφής warning. |
| ορίσματα | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα σύμβολα κράτησης θέσης \{\} με τη σειρά που περνιούνται. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής warning στην κονσόλα. Τα μηνύματα καταγραφής warning παρέχουν πληροφορίες για απρόσμενα και ανακτήσιμα γεγονότα στη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εξαίρεση | java.lang.Throwable | Η εξαίρεση που σχετίζεται με το μήνυμα καταγραφής warning. |
| μήνυμα | java.lang.String | Το μήνυμα καταγραφής warning. |
| ορίσματα | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα σύμβολα κράτησης θέσης \{\} με τη σειρά που περνιούνται. |

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Ελέγχει αν το επίπεδο warning είναι ενεργοποιημένο για καταγραφή.

**Returns:**
boolean -  true  αν το επίπεδο warning είναι ενεργοποιημένο,  false  διαφορετικά.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής error στην κονσόλα. Τα μηνύματα καταγραφής error παρέχουν πληροφορίες για μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα καταγραφής error. |
| ορίσματα | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα σύμβολα κράτησης θέσης \{\} με τη σειρά που περνιούνται. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής error στην κονσόλα. Τα μηνύματα καταγραφής error παρέχουν πληροφορίες για μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| εξαίρεση | java.lang.Throwable | Η εξαίρεση που σχετίζεται με το μήνυμα καταγραφής error. |
| μήνυμα | java.lang.String | Το μήνυμα καταγραφής error. |
| ορίσματα | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα σύμβολα κράτησης θέσης \{\} με τη σειρά που περνιούνται. |

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Ελέγχει αν η καταγραφή σε επίπεδο error είναι ενεργοποιημένη.

**Returns:**
boolean -  true  αν η καταγραφή σε επίπεδο error είναι ενεργοποιημένη,  false  διαφορετικά.
