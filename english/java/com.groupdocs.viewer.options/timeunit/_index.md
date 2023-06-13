---
title: TimeUnit
second_title: GroupDocs.Viewer for Java API Reference
description: Time unit of the project duration.
type: docs
weight: 43
url: /java/com.groupdocs.viewer.options/timeunit/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum TimeUnit extends Enum<TimeUnit>
```

Time unit of the project duration.

The TimeUnit enum represents different time units for specifying the duration of a project in the GroupDocs.Viewer component. It provides a set of predefined time units that can be used to represent and calculate the duration of a project, such as days, months and so on.

Example usage:

```

 HtmlViewOptions pdfViewOptions = HtmlViewOptions.forEmbeddedResources();
 ProjectManagementOptions projectManagementOptions = pdfViewOptions.getProjectManagementOptions();
 projectManagementOptions.setTimeUnit(TimeUnit.MONTHS);

 try (Viewer viewer = new Viewer("document.mpp")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Fields

| Field | Description |
| --- | --- |
| [UNSPECIFIED](#UNSPECIFIED) | The unknown time scale. |
| [DAYS](#DAYS) | Days time scale. |
| [THIRDS_OF_MONTHS](#THIRDS-OF-MONTHS) | Thirds of months time scale. |
| [MONTHS](#MONTHS) | Months time scale. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### UNSPECIFIED {#UNSPECIFIED}
```
public static final TimeUnit UNSPECIFIED
```


The unknown time scale. This time unit represents an unknown or unspecified time scale.

### DAYS {#DAYS}
```
public static final TimeUnit DAYS
```


Days time scale. This time unit represents a one-day interval.

### THIRDS_OF_MONTHS {#THIRDS-OF-MONTHS}
```
public static final TimeUnit THIRDS_OF_MONTHS
```


Thirds of months time scale. This time unit represents a one-third of the month interval.

### MONTHS {#MONTHS}
```
public static final TimeUnit MONTHS
```


Months time scale. This time unit represents a one-month interval.

### values() {#values--}
```
public static TimeUnit[] values()
```




**Returns:**
com.groupdocs.viewer.options.TimeUnit[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static TimeUnit valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[TimeUnit](../../com.groupdocs.viewer.options/timeunit)
