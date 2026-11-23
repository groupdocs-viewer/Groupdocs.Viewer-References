---
title: "ViewerLogger"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Καθολικός καταγραφέας προβολέα."
type: docs
weight: 11
url: /el/nodejs-java/com.groupdocs.viewer.logging/viewerlogger/
---
**Inheritance:**
java.lang.Object
```
public class ViewerLogger
```

Καθολικός καταγραφέας προβολέα.

Η  ViewerLogger  κλάση παρέχει λειτουργικότητα για την καταγραφή μηνυμάτων σε έναν ενσωματωμένο ή προσαρμοσμένο από τον χρήστη καταγραφέα. Λειτουργεί ως ο παγκόσμιος καταγραφέας για το module viewer και μπορεί να χρησιμοποιηθεί για την καταγραφή διαφόρων συμβάντων και μηνυμάτων.

Παράδειγμα χρήσης:

```

 // Configure the viewer logger to use the default integrated logger
 ViewerLogger.setLogger(new FileLogger("/path/to/file.log"));

 // Log an debug message
 ViewerLogger.debug("Debug message");

 // Log an error message
 ViewerLogger.error("Error message");
 
```

***Note:** The  ViewerLogger  class can be configured to use a custom logger implementation by calling the [setLogger(ILogger)](../../com.groupdocs.viewer.logging/viewerlogger\#setLogger-ILogger-) method. By default, it uses the integrated logger provided by the viewer module.*
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ViewerLogger()](#ViewerLogger--) |  |
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
| [getLogger()](#getLogger--) | Αποκτά το στιγμιότυπο του καταγραφέα που θα χρησιμοποιηθεί για την καταγραφή μηνυμάτων. |
| [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Ορίζει το στιγμιότυπο του καταγραφέα που θα χρησιμοποιηθεί για την καταγραφή μηνυμάτων. |
### ViewerLogger() {#ViewerLogger--}
```
public ViewerLogger()
```


### trace(String message, Object[] arguments) {#trace-java.lang.String-java.lang.Object...-}
```
public static void trace(String message, Object[] arguments)
```


Γράφει ένα μήνυμα trace στην κονσόλα. Τα μηνύματα trace log παρέχουν γενικά χρήσιμες πληροφορίες για τη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα trace. |
| ορίσματα | java.lang.Object[] | Τα arguments που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα placeholders \{\} με τη σειρά που περνούν. |

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void trace(Throwable throwable, String message, Object[] arguments)
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
public static boolean isTraceEnabled()
```


Ελέγχει αν το επίπεδο trace είναι ενεργοποιημένο για καταγραφή.

**Returns:**
boolean -  true  αν το επίπεδο trace είναι ενεργοποιημένο,  false  διαφορετικά.
### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public static void debug(String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής debug στην κονσόλα. Τα μηνύματα καταγραφής debug παρέχουν πληροφορίες για διαφορετικές διαδικασίες στη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα καταγραφής debug. |
| ορίσματα | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα σύμβολα κράτησης θέσης \{\} με τη σειρά που περνιούνται. |

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void debug(Throwable throwable, String message, Object[] arguments)
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
public static boolean isDebugEnabled()
```


Ελέγχει αν το επίπεδο debug είναι ενεργοποιημένο για καταγραφή.

**Returns:**
boolean -  true  αν το επίπεδο debug είναι ενεργοποιημένο,  false  διαφορετικά.
### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public static void warning(String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής warning στην κονσόλα. Τα μηνύματα καταγραφής warning παρέχουν πληροφορίες για απρόσμενα και ανακτήσιμα γεγονότα στη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα καταγραφής warning. |
| ορίσματα | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα σύμβολα κράτησης θέσης \{\} με τη σειρά που περνιούνται. |

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void warning(Throwable throwable, String message, Object[] arguments)
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
public static boolean isWarningEnabled()
```


Ελέγχει αν το επίπεδο warning είναι ενεργοποιημένο για καταγραφή.

**Returns:**
boolean -  true  αν το επίπεδο warning είναι ενεργοποιημένο,  false  διαφορετικά.
### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public static void error(String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής error στην κονσόλα. Τα μηνύματα καταγραφής error παρέχουν πληροφορίες για μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| μήνυμα | java.lang.String | Το μήνυμα καταγραφής error. |
| ορίσματα | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα σύμβολα κράτησης θέσης \{\} με τη σειρά που περνιούνται. |

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public static void error(Throwable throwable, String message, Object[] arguments)
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
public static boolean isErrorEnabled()
```


Ελέγχει αν η καταγραφή σε επίπεδο error είναι ενεργοποιημένη.

**Returns:**
boolean -  true  αν η καταγραφή σε επίπεδο error είναι ενεργοποιημένη,  false  διαφορετικά.
### getLogger() {#getLogger--}
```
public static synchronized ILogger getLogger()
```


Λαμβάνει το αντικείμενο logger που θα χρησιμοποιηθεί για την καταγραφή μηνυμάτων. Το αντικείμενο logger μπορεί να χρησιμοποιηθεί για την καταγραφή μηνυμάτων διαφορετικών επιπέδων όπως trace, debug, warning και error.

**Returns:**
com.groupdocs.foundation.logging.ILogger - το αντικείμενο logger.
### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public static synchronized void setLogger(ILogger logger)
```


Ορίζει το αντικείμενο logger που θα χρησιμοποιηθεί για την καταγραφή μηνυμάτων. Το αντικείμενο logger μπορεί να χρησιμοποιηθεί για την καταγραφή μηνυμάτων διαφορετικών επιπέδων όπως trace, debug, warning και error.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| logger | com.groupdocs.foundation.logging.ILogger | Το αντικείμενο logger προς ορισμό. |

