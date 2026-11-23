---
title: "ProjectManagementOptions"
second_title: "GroupDocs.Viewer για Node.js μέσω Java αναφορά API"
description: "Παρέχει επιλογές για την απόδοση αρχείων διαχείρισης έργου."
type: docs
weight: 27
url: /el/nodejs-java/com.groupdocs.viewer.options/projectmanagementoptions/
---
**Inheritance:**
java.lang.Object
```
public class ProjectManagementOptions
```

Παρέχει επιλογές για την απόδοση αρχείων διαχείρισης έργου.

Η κλάση ProjectManagementOptions περιλαμβάνει διάφορες ρυθμίσεις και παραμέτρους που μπορούν να χρησιμοποιηθούν για τον έλεγχο της απόδοσης αρχείων διαχείρισης έργων (όπως το Microsoft Project ή παρόμοια) στο στοιχείο GroupDocs.Viewer. Για λεπτομέρειες, δείτε την [documentation][].

Παράδειγμα χρήσης:

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
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ProjectManagementOptions()](#ProjectManagementOptions--) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  ProjectManagementOptions . |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getPageSize()](#getPageSize--) | Ανακτά το μέγεθος της εξαγόμενης σελίδας. |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Ορίζει το μέγεθος της εξαγόμενης σελίδας. |
| [getTimeUnit()](#getTimeUnit--) | Ανακτά τη μονάδα χρόνου. |
| [setTimeUnit(TimeUnit value)](#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-) | Ανακτά τη μονάδα χρόνου. |
| [getStartDate()](#getStartDate--) | Ανακτά την ημερομηνία έναρξης της προβολής Gantt Chart που θα συμπεριληφθεί στην έξοδο. |
| [setStartDate(Date value)](#setStartDate-java.util.Date-) | Ορίζει την ημερομηνία έναρξης της προβολής Gantt Chart που θα συμπεριληφθεί στην έξοδο. |
| [getEndDate()](#getEndDate--) | Ανακτά την ημερομηνία λήξης της προβολής Gantt Chart που θα συμπεριληφθεί στην έξοδο. |
| [setEndDate(Date value)](#setEndDate-java.util.Date-) | Ορίζει την ημερομηνία λήξης της προβολής Gantt Chart που θα συμπεριληφθεί στην έξοδο. |
### ProjectManagementOptions() {#ProjectManagementOptions--}
```
public ProjectManagementOptions()
```


Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης  ProjectManagementOptions .

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Ανακτά το μέγεθος της εξαγόμενης σελίδας.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the output page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Ορίζει το μέγεθος της εξαγόμενης σελίδας.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#specify-the-output-page-size

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Το μέγεθος της εξαγόμενης σελίδας. |

### getTimeUnit() {#getTimeUnit--}
```
public final TimeUnit getTimeUnit()
```


Ανακτά τη μονάδα χρόνου.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit) - the time unit.
### setTimeUnit(TimeUnit value) {#setTimeUnit-com.groupdocs.viewer.options.TimeUnit-}
```
public final void setTimeUnit(TimeUnit value)
```


Ανακτά τη μονάδα χρόνου.

Για παράδειγμα κώδικα, δείτε την [τεκμηρίωση][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#adjust-the-time-unit

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TimeUnit](../../com.groupdocs.viewer.options/timeunit) | Η μονάδα χρόνου. |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


Ανακτά την ημερομηνία έναρξης της προβολής Gantt Chart που θα συμπεριληφθεί στην έξοδο.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - η ημερομηνία έναρξης της προβολής Gantt Chart.
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


Ορίζει την ημερομηνία έναρξης της προβολής Gantt Chart που θα συμπεριληφθεί στην έξοδο.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.Date | Η ημερομηνία έναρξης της προβολής Gantt Chart. |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


Ανακτά την ημερομηνία λήξης της προβολής Gantt Chart που θα συμπεριληφθεί στην έξοδο.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Returns:**
java.util.Date - η ημερομηνία λήξης της προβολής Gantt Chart.
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


Ορίζει την ημερομηνία λήξης της προβολής Gantt Chart που θα συμπεριληφθεί στην έξοδο.

***Note:** Use this option when you need to render a specific time interval of the project within the Gantt Chart View.* For code sample, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-ms-project-files/#render-specific-dates

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | java.util.Date | Η ημερομηνία λήξης της προβολής Gantt Chart. |

