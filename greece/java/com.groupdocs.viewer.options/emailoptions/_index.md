---
title: "EmailOptions"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Παρέχει επιλογές για την απόδοση μηνυμάτων ηλεκτρονικού ταχυδρομείου."
type: docs
weight: 14
url: /el/java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

Παρέχει επιλογές για την απόδοση μηνυμάτων ηλεκτρονικού ταχυδρομείου.


Η κλάση EmailOptions περιλαμβάνει διάφορες ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν
για να ελέγχει την απόδοση των μηνυμάτων ηλεκτρονικού ταχυδρομείου στο στοιχείο GroupDocs.Viewer.


Για λεπτομέρειες, δείτε το [documentation](../https://docs.groupdocs.com/viewer/java/render-email-messages/).


Παράδειγμα χρήσης:

````

 EmailOptions options = new EmailOptions();
 options.setDateTimeFormat("MM d yyyy HH:mm tt");
 options.setPageSize(PageSize.A4);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setEmailOptions(options);

 try (Viewer viewer = new Viewer("email.msg")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [EmailOptions()](#EmailOptions--) | Αρχικοποιεί μια νέα παρουσία του |
EmailOptions
κλάσης.
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getDateTimeFormat()](#getDateTimeFormat--) | Λαμβάνει τη μορφή ώρας για τις τιμές ημερομηνίας και ώρας. |
|
|  | [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | Λαμβάνει τη μορφή ώρας για τις τιμές ημερομηνίας και ώρας. |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | Λαμβάνει τη διαφορά ζώνης ώρας για το μήνυμα. |
|
|  | [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | Λαμβάνει τη διαφορά λεπτών ζώνης ώρας για το μήνυμα. |
|
|  | [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | Λαμβάνει τη διαφορά ζώνης ώρας για το μήνυμα. |
|
|  | [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | Λαμβάνει το offset σε λεπτά της ζώνης ώρας για το μήνυμα. |
|
|  | [getPageSize()](#getPageSize--) | Λαμβάνει το μέγεθος της σελίδας εξόδου. |
|
|  | [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Λαμβάνει το μέγεθος της σελίδας εξόδου. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | Ανακτά τη χαρτογράφηση μεταξύ των πεδίων του μηνύματος email και των κειμενικών τους αναπαραστάσεων. |
|
|  | [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | Ορίζει τη χαρτογράφηση μεταξύ των πεδίων του μηνύματος email και των κειμενικών τους αναπαραστάσεων. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Αντικαθιστά τη μέθοδο equals() της κλάσης Object. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | Αντικαθιστά τη μέθοδο toString() της κλάσης Object. |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


Αρχικοποιεί μια νέα παρουσία του
EmailOptions
κλάσης.
Αυτός ο κατασκευαστής χρησιμοποιείται για τη δημιουργία μιας νέας στιγμής της
EmailOptions
κλάσης με προεπιλεγμένες ρυθμίσεις.


### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


Λαμβάνει τη μορφή ώρας για τις τιμές ημερομηνίας και ώρας.
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
Εάν η μορφή ώρας δεν έχει οριστεί, θα χρησιμοποιηθεί η τρέχουσα μορφή του συστήματος.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.lang.String - η μορφή ώρας για τιμές ημερομηνίας και ώρας.

### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


Λαμβάνει τη μορφή ώρας για τις τιμές ημερομηνίας και ώρας.
***Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'.
Εάν η μορφή ώρας δεν έχει οριστεί, θα χρησιμοποιηθεί η τρέχουσα μορφή του συστήματος.
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | dateTimeFormat | java.lang.String | Η μορφή ώρας για τιμές ημερομηνίας και ώρας. |
|

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


Λαμβάνει τη διαφορά ζώνης ώρας για το μήνυμα.
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
java.util.TimeZone - το offset της ζώνης ώρας.

### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


Λαμβάνει τη διαφορά λεπτών ζώνης ώρας για το μήνυμα.
***Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC).
Για λεπτομέρειες, δείτε την [τεκμηρίωση](../https://docs.groupdocs.com/viewer/java/render-email-messages/#specify-the-date-and-time-format-and-change-the-time-zone).*


**Returns:**
int - το offset της ζώνης ώρας.

### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


Λαμβάνει τη διαφορά ζώνης ώρας για το μήνυμα.
***Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | timeZoneOffset | java.util.TimeZone | Το offset της ζώνης ώρας. |
|

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


Λαμβάνει το offset σε λεπτά της ζώνης ώρας για το μήνυμα.
***Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | offsetMinutes | int | Το offset της ζώνης ώρας. |
|

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Λαμβάνει το μέγεθος της σελίδας εξόδου.


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.

### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Λαμβάνει το μέγεθος της σελίδας εξόδου.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Το μέγεθος της σελίδας. |
|

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


Ανακτά τη χαρτογράφηση μεταξύ των πεδίων του μηνύματος email και των κειμενικών τους αναπαραστάσεων.


**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - η χαρτογράφηση μεταξύ των πεδίων του μηνύματος email και των κειμενικών τους αναπαραστάσεων.

### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


Ορίζει τη χαρτογράφηση μεταξύ των πεδίων του μηνύματος email και των κειμενικών τους αναπαραστάσεων.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | Η χαρτογράφηση μεταξύ των πεδίων του μηνύματος email και των κειμενικών τους αναπαραστάσεων. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Αντικαθιστά τη μέθοδο equals() της κλάσης Object.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | o | java.lang.Object | Το αντικείμενο για σύγκριση. |
|

**Returns:**
boolean - true εάν τα αντικείμενα είναι ίσα, false διαφορετικά.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Υπολογίζει την τιμή του κώδικα κατακερματισμού για αυτό το αντικείμενο. Ο κώδικας κατακερματισμού βασίζεται σε
την εσωτερική κατάσταση του αντικειμένου και χρησιμοποιείται σε δομές δεδομένων βασισμένες σε κατακερματισμό
όπως οι hash maps και τα hash sets.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - η τιμή του κώδικα κατακερματισμού για αυτό το αντικείμενο.

### toString() {#toString--}
```
public String toString()
```


Αντικαθιστά τη μέθοδο toString() της κλάσης Object.


**Returns:**
java.lang.String - μια αναπαράσταση σε συμβολοσειρά του αντικειμένου.

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Επιστρέφει μια αναπαράσταση συμβολοσειράς αυτού του αντικειμένου.
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | στυλ | org.apache.commons.lang3.builder.ToStringStyle | Το ToStringStyle που θα χρησιμοποιηθεί για τη δημιουργία της αναπαράστασης συμβολοσειράς. |
|

**Returns:**
java.lang.String - μια αναπαράσταση συμβολοσειράς αυτού του αντικειμένου χρησιμοποιώντας το καθορισμένο ToStringStyle.

