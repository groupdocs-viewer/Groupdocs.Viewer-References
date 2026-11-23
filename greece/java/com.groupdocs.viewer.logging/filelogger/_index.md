---
title: "FileLogger"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Γράφει μηνύματα καταγραφής σε ένα αρχείο."
type: docs
weight: 10
url: /el/java/com.groupdocs.viewer.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.foundation.logging.ILogger
```
public class FileLogger implements ILogger
```

Γράφει μηνύματα καταγραφής σε ένα αρχείο.


Το
FileLogger
Η κλάση παρέχει λειτουργικότητα για την εγγραφή μηνυμάτων καταγραφής σε αρχείο. Υλοποιεί το interface ILogger
και μπορεί να χρησιμοποιηθεί για την καταγραφή διαφόρων συμβάντων και μηνυμάτων σε μια εφαρμογή. Τα μηνύματα καταγραφής γράφονται στο καθορισμένο αρχείο.


Παράδειγμα χρήσης:

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
η κλάση παρέχει βασική λειτουργικότητα καταγραφής.
Μπορείτε να επεκτείνετε αυτήν την κλάση για να προσθέσετε προσαρμοσμένα επίπεδα καταγραφής ή πρόσθετες λειτουργίες καταγραφής σύμφωνα με τις απαιτήσεις σας.*

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | Δημιουργεί έναν καταγραφέα που καταγράφει μηνύματα σε ένα αρχείο που καθορίζεται από το παρεχόμενο όνομα αρχείου. |
|
|  | [FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)](#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-) | Δημιουργεί έναν καταγραφέα που καταγράφει μηνύματα σε ένα αρχείο με καθορισμένα επίπεδα καταγραφής. |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [MESSAGE](#MESSAGE) |  |
| [EXCEPTION](#EXCEPTION) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [trace(String message, Object[] arguments)](#trace-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα trace στην κονσόλα. |
|
|  | [trace(Throwable throwable, String message, Object[] arguments)](#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα καταγραφής trace στην κονσόλα. |
|
|  | [isTraceEnabled()](#isTraceEnabled--) | Ελέγχει αν το επίπεδο trace είναι ενεργοποιημένο για καταγραφή. |
|
|  | [debug(String message, Object[] arguments)](#debug-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα καταγραφής debug στην κονσόλα. |
|
|  | [debug(Throwable throwable, String message, Object[] arguments)](#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα καταγραφής debug στην κονσόλα. |
|
|  | [isDebugEnabled()](#isDebugEnabled--) | Ελέγχει αν το επίπεδο debug είναι ενεργοποιημένο για καταγραφή. |
|
|  | [warning(String message, Object[] arguments)](#warning-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα καταγραφής προειδοποίησης στην κονσόλα. |
|
|  | [warning(Throwable throwable, String message, Object[] arguments)](#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα καταγραφής προειδοποίησης στην κονσόλα. |
|
|  | [isWarningEnabled()](#isWarningEnabled--) | Ελέγχει αν το επίπεδο προειδοποίησης είναι ενεργοποιημένο για καταγραφή. |
|
|  | [error(String message, Object[] arguments)](#error-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα καταγραφής σφάλματος στην κονσόλα. |
|
|  | [error(Throwable throwable, String message, Object[] arguments)](#error-java.lang.Throwable-java.lang.String-java.lang.Object...-) | Γράφει ένα μήνυμα καταγραφής σφάλματος στην κονσόλα. |
|
|  | [isErrorEnabled()](#isErrorEnabled--) | Ελέγχει αν η καταγραφή σε επίπεδο σφάλματος είναι ενεργοποιημένη. |
|
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


Δημιουργεί έναν καταγραφέα που καταγράφει μηνύματα σε ένα αρχείο που καθορίζεται από το παρεχόμενο όνομα αρχείου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileName | java.lang.String | Το πλήρες όνομα αρχείου με τη διαδρομή. |
|

### FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled) {#FileLogger-java.lang.String-boolean-boolean-boolean-boolean-}
```
public FileLogger(String fileName, boolean isTraceEnabled, boolean isDebugEnabled, boolean isWarningEnabled, boolean isErrorEnabled)
```


Δημιουργεί έναν καταγραφέα που καταγράφει μηνύματα σε ένα αρχείο με καθορισμένα επίπεδα καταγραφής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | fileName | java.lang.String | Το πλήρες όνομα αρχείου με τη διαδρομή. |
|
|  | isTraceEnabled | boolean | Καθορίζει εάν η καταγραφή σε επίπεδο trace είναι ενεργοποιημένη. |
|
|  | isDebugEnabled | boolean | Καθορίζει εάν η καταγραφή σε επίπεδο debug είναι ενεργοποιημένη. |
|
|  | isWarningEnabled | boolean | Καθορίζει εάν η καταγραφή σε επίπεδο warning είναι ενεργοποιημένη. |
|
|  | isErrorEnabled | boolean | Καθορίζει εάν η καταγραφή σε επίπεδο error είναι ενεργοποιημένη. |
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


Γράφει ένα μήνυμα trace στην κονσόλα.
Τα μηνύματα καταγραφής trace παρέχουν γενικά χρήσιμες πληροφορίες σχετικά με τη ροή της εφαρμογής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Το μήνυμα trace. |
|
|  | arguments | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα {} σύμβολα κράτησης θέσης με τη σειρά που περνιούνται. |
|

### trace(Throwable throwable, String message, Object[] arguments) {#trace-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void trace(Throwable throwable, String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής trace στην κονσόλα.
Τα μηνύματα καταγραφής trace παρέχουν γενικά χρήσιμες πληροφορίες σχετικά με τη ροή της εφαρμογής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Η εξαίρεση που σχετίζεται με το μήνυμα καταγραφής trace. |
|
|  | μήνυμα | java.lang.String | Το μήνυμα καταγραφής trace. |
|
|  | arguments | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα {} σύμβολα κράτησης θέσης με τη σειρά που περνιούνται. |
|

### isTraceEnabled() {#isTraceEnabled--}
```
public boolean isTraceEnabled()
```


Ελέγχει αν το επίπεδο trace είναι ενεργοποιημένο για καταγραφή.


**Returns:**
boolean -  true  εάν το επίπεδο trace είναι ενεργό,  false  διαφορετικά.

### debug(String message, Object[] arguments) {#debug-java.lang.String-java.lang.Object...-}
```
public void debug(String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής debug στην κονσόλα.
Τα μηνύματα καταγραφής debug παρέχουν πληροφορίες σχετικά με διαφορετικές διεργασίες στη ροή της εφαρμογής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Το μήνυμα καταγραφής debug. |
|
|  | arguments | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα {} σύμβολα κράτησης θέσης με τη σειρά που περνιούνται. |
|

### debug(Throwable throwable, String message, Object[] arguments) {#debug-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void debug(Throwable throwable, String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής debug στην κονσόλα.
Τα μηνύματα καταγραφής debug παρέχουν πληροφορίες σχετικά με διαφορετικές διεργασίες στη ροή της εφαρμογής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Η εξαίρεση που σχετίζεται με το μήνυμα καταγραφής debug. |
|
|  | μήνυμα | java.lang.String | Το μήνυμα καταγραφής debug. |
|
|  | arguments | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα {} σύμβολα κράτησης θέσης με τη σειρά που περνιούνται. |
|

### isDebugEnabled() {#isDebugEnabled--}
```
public boolean isDebugEnabled()
```


Ελέγχει αν το επίπεδο debug είναι ενεργοποιημένο για καταγραφή.


**Returns:**
boolean -  true  εάν το επίπεδο debug είναι ενεργό,  false  διαφορετικά.

### warning(String message, Object[] arguments) {#warning-java.lang.String-java.lang.Object...-}
```
public void warning(String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής προειδοποίησης στην κονσόλα.
Τα μηνύματα καταγραφής warning παρέχουν πληροφορίες σχετικά με απρόσμενα και ανακτήσιμα γεγονότα στη ροή της εφαρμογής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Το μήνυμα καταγραφής warning. |
|
|  | arguments | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα {} σύμβολα κράτησης θέσης με τη σειρά που περνιούνται. |
|

### warning(Throwable throwable, String message, Object[] arguments) {#warning-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void warning(Throwable throwable, String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής προειδοποίησης στην κονσόλα.
Τα μηνύματα καταγραφής warning παρέχουν πληροφορίες σχετικά με απρόσμενα και ανακτήσιμα γεγονότα στη ροή της εφαρμογής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Η εξαίρεση που σχετίζεται με το μήνυμα καταγραφής warning. |
|
|  | μήνυμα | java.lang.String | Το μήνυμα καταγραφής warning. |
|
|  | arguments | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα {} σύμβολα κράτησης θέσης με τη σειρά που περνιούνται. |
|

### isWarningEnabled() {#isWarningEnabled--}
```
public boolean isWarningEnabled()
```


Ελέγχει αν το επίπεδο προειδοποίησης είναι ενεργοποιημένο για καταγραφή.


**Returns:**
boolean -  true  εάν το επίπεδο warning είναι ενεργό,  false  διαφορετικά.

### error(String message, Object[] arguments) {#error-java.lang.String-java.lang.Object...-}
```
public void error(String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής σφάλματος στην κονσόλα.
Τα μηνύματα καταγραφής error παρέχουν πληροφορίες σχετικά με μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | μήνυμα | java.lang.String | Το μήνυμα καταγραφής error. |
|
|  | arguments | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα {} σύμβολα κράτησης θέσης με τη σειρά που περνιούνται. |
|

### error(Throwable throwable, String message, Object[] arguments) {#error-java.lang.Throwable-java.lang.String-java.lang.Object...-}
```
public void error(Throwable throwable, String message, Object[] arguments)
```


Γράφει ένα μήνυμα καταγραφής σφάλματος στην κονσόλα.
Τα μηνύματα καταγραφής error παρέχουν πληροφορίες σχετικά με μη ανακτήσιμα γεγονότα στη ροή της εφαρμογής.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | throwable | java.lang.Throwable | Η εξαίρεση που σχετίζεται με το μήνυμα καταγραφής error. |
|
|  | μήνυμα | java.lang.String | Το μήνυμα καταγραφής error. |
|
|  | arguments | java.lang.Object[] | Τα ορίσματα που θα αντικατασταθούν στο μήνυμα. Θα αντικαταστήσουν τα {} σύμβολα κράτησης θέσης με τη σειρά που περνιούνται. |
|

### isErrorEnabled() {#isErrorEnabled--}
```
public boolean isErrorEnabled()
```


Ελέγχει αν η καταγραφή σε επίπεδο σφάλματος είναι ενεργοποιημένη.


**Returns:**
boolean -  true  εάν η καταγραφή σε επίπεδο error είναι ενεργή,  false  διαφορετικά.

