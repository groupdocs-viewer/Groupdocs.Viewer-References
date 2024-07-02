---
title: EmailOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Provides options for rendering email messages.
type: docs
weight: 14
url: /nodejs-java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

Provides options for rendering email messages.

The EmailOptions class encapsulates various settings and parameters that can be used to control the rendering of email messages in the GroupDocs.Viewer component.

Example usage:

```

 EmailOptions options = new EmailOptions();
 options.setDateTimeFormat("MM d yyyy HH:mm tt");
 options.setPageSize(PageSize.A4);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setEmailOptions(options);

 try (Viewer viewer = new Viewer("email.msg")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [EmailOptions()](#EmailOptions--) | Initializes a new instance of the  EmailOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [getDateTimeFormat()](#getDateTimeFormat--) | Gets the time format for the date and time values. |
| [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | Gets the time format for the date and time values. |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | Gets the time zone offset for the message. |
| [getTimeZoneOffsetMinutes()](#getTimeZoneOffsetMinutes--) | Gets the time zone minutes offset minutes for the message. |
| [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | Gets the time zone offset for the message. |
| [setTimeZoneOffset(int offsetMinutes)](#setTimeZoneOffset-int-) | Gets the time zone offset minutes offset for the message. |
| [getPageSize()](#getPageSize--) | Gets the size of the output page. |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Gets the size of the output page. |
| [getFieldTextMap()](#getFieldTextMap--) | Retrieves the mapping between email message fields and their text representations. |
| [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | Sets the mapping between email message fields and their text representations. |
| [equals(Object o)](#equals-java.lang.Object-) | Overrides the equals() method of the Object class. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Overrides the toString() method of the Object class. |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


Initializes a new instance of the  EmailOptions  class. This constructor is used to create a new instance of the  EmailOptions  class with default settings.

### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


Gets the time format for the date and time values.

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used.

**Returns:**
java.lang.String - the time format for date and time values.
### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


Gets the time format for the date and time values.

**Note:** The time format is specified using a pattern, such as 'MM d yyyy HH:mm tt'. If the time format is not set, the current system format will be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dateTimeFormat | java.lang.String | The time format for date and time values. |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


Gets the time zone offset for the message.

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Returns:**
java.util.TimeZone - the time zone offset.
### getTimeZoneOffsetMinutes() {#getTimeZoneOffsetMinutes--}
```
public int getTimeZoneOffsetMinutes()
```


Gets the time zone minutes offset minutes for the message.

**Note:** The time zone offset minutes represents the minutes difference between the message's time and Coordinated Universal Time (UTC).

**Returns:**
int - the time zone offset.
### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


Gets the time zone offset for the message.

**Note:** The time zone offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| timeZoneOffset | java.util.TimeZone | The time zone offset. |

### setTimeZoneOffset(int offsetMinutes) {#setTimeZoneOffset-int-}
```
public void setTimeZoneOffset(int offsetMinutes)
```


Gets the time zone offset minutes offset for the message.

**Note:** The time zone minutes offset represents the time difference between the message's time and Coordinated Universal Time (UTC).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| offsetMinutes | int | The time zone offset. |

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


Gets the size of the output page.

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - the page size.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


Gets the size of the output page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | The page size. |

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


Retrieves the mapping between email message fields and their text representations.

**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> - the mapping between email message fields and their text representations.
### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


Sets the mapping between email message fields and their text representations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> | The mapping between email message fields and their text representations. |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Overrides the equals() method of the Object class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | The object to compare with. |

**Returns:**
boolean - true if the objects are equal, false otherwise.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Computes the hash code value for this object. The hash code is based on the internal state of the object and is used in hash-based data structures such as hash maps and hash sets.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - the hash code value for this object.
### toString() {#toString--}
```
public String toString()
```


Overrides the toString() method of the Object class.

**Returns:**
java.lang.String - a string representation of the object.
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


Returns a string representation of this object.

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| style | org.apache.commons.lang3.builder.ToStringStyle | The ToStringStyle to use for generating the string representation. |

**Returns:**
java.lang.String - a string representation of this object using the specified ToStringStyle.
