---
title: EmailOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering email messages.
type: docs
weight: 14
url: /java/com.groupdocs.viewer.options/emailoptions/
---
**Inheritance:**
java.lang.Object
```
public class EmailOptions
```

Provides options for rendering email messages.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmailOptions()](#EmailOptions--) | Initializes new instance of [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getDateTimeFormat()](#getDateTimeFormat--) | Time Format (can be include TimeZone) for example: 'MM d yyyy HH:mm tt', if not set - current system format is used |
| [setDateTimeFormat(String dateTimeFormat)](#setDateTimeFormat-java.lang.String-) | Time Format (can be include TimeZone) for example: 'MM d yyyy HH:mm tt', if not set - current system format is used |
| [getTimeZoneOffset()](#getTimeZoneOffset--) | Message time zone offset |
| [setTimeZoneOffset(TimeZone timeZoneOffset)](#setTimeZoneOffset-java.util.TimeZone-) | Message time zone offset |
| [getPageSize()](#getPageSize--) | The size of the output page. |
| [setPageSize(PageSize value)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | The size of the output page. |
| [getFieldTextMap()](#getFieldTextMap--) | The mapping between email message [Field](../../com.groupdocs.viewer.options/field) and field text representation. |
| [setFieldTextMap(Map<Field,String> value)](#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--) | The mapping between email message [Field](../../com.groupdocs.viewer.options/field) and field text representation. |
| [equals(Object o)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [toString()](#toString--) |  |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) |  |
### EmailOptions() {#EmailOptions--}
```
public EmailOptions()
```


Initializes new instance of [EmailOptions](../../com.groupdocs.viewer.options/emailoptions) class.

### getDateTimeFormat() {#getDateTimeFormat--}
```
public String getDateTimeFormat()
```


Time Format (can be include TimeZone) for example: 'MM d yyyy HH:mm tt', if not set - current system format is used

**Returns:**
java.lang.String
### setDateTimeFormat(String dateTimeFormat) {#setDateTimeFormat-java.lang.String-}
```
public void setDateTimeFormat(String dateTimeFormat)
```


Time Format (can be include TimeZone) for example: 'MM d yyyy HH:mm tt', if not set - current system format is used

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dateTimeFormat | java.lang.String |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public TimeZone getTimeZoneOffset()
```


Message time zone offset

**Returns:**
java.util.TimeZone
### setTimeZoneOffset(TimeZone timeZoneOffset) {#setTimeZoneOffset-java.util.TimeZone-}
```
public void setTimeZoneOffset(TimeZone timeZoneOffset)
```


Message time zone offset

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| timeZoneOffset | java.util.TimeZone |  |

### getPageSize() {#getPageSize--}
```
public final PageSize getPageSize()
```


The size of the output page.

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.
### setPageSize(PageSize value) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public final void setPageSize(PageSize value)
```


The size of the output page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PageSize](../../com.groupdocs.viewer.options/pagesize) | The size of the output page. |

### getFieldTextMap() {#getFieldTextMap--}
```
public final Map<Field,String> getFieldTextMap()
```


The mapping between email message [Field](../../com.groupdocs.viewer.options/field) and field text representation.

**Returns:**
java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String>
### setFieldTextMap(Map<Field,String> value) {#setFieldTextMap-java.util.Map-com.groupdocs.viewer.options.Field-java.lang.String--}
```
public final void setFieldTextMap(Map<Field,String> value)
```


The mapping between email message [Field](../../com.groupdocs.viewer.options/field) and field text representation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Map<com.groupdocs.viewer.options.Field,java.lang.String> |  |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| style | org.apache.commons.lang3.builder.ToStringStyle |  |

**Returns:**
java.lang.String
