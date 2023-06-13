---
title: ArchiveSecurityOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Class that can be used to limit the archives extraction process.
type: docs
weight: 11
url: /java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Class that can be used to limit the archives extraction process.

The ArchiveSecurityOptions class provides a way to limit the extraction of archives and enforce certain restrictions.

Example usage:

```

 ArchiveSecurityOptions securityOptions = new ArchiveSecurityOptions();
 securityOptions.setMaxAllowedEntryNameLength(255);
 securityOptions.setMaxAllowedEntrySize(10737418240L);
 securityOptions.setMaxAllowedEntriesCount(1000);
 securityOptions.setMaxAllowedEntryCompressionRatio(100);

 final LoadOptions loadOptions = new LoadOptions();
 loadOptions.setArchiveSecurityOptions(securityOptions);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     // Use the viewer object for archive document rendering
 }
 
```

Note: Not each archive type supports all options.
## Constructors

| Constructor | Description |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | This option specifies the maximum length that an archive entry name can have. |
| [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Sets the maximum allowed length for the archive entry names. |
| [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Retrieves the maximum allowed size for archive entries. |
| [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Sets the maximum allowed size for archive entries. |
| [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Retrieves the maximum allowed count of entries in an archive. |
| [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Sets the maximum allowed count of entries in an archive. |
| [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Specifies the maximum compression ratio allowed for extracting archive entries. |
| [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Specifies the maximum compression ratio allowed for extracting archive entries. |
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


This option specifies the maximum length that an archive entry name can have. If an entry name exceeds this limit, it will cause an error.

***Note:** The default value for this option is 255.*

**Returns:**
int - the maximum allowed length for the archive entry names.
### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Sets the maximum allowed length for the archive entry names. The maximum allowed length specifies the limit for the length of an archive entry name. If the length of an entry name exceeds this limit, it will cause an error.

***Note:** The default value for the maximum allowed entry name length is 255.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxAllowedEntryNameLength | int | The maximum archive entry name length to be set. |

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Retrieves the maximum allowed size for archive entries. The maximum allowed entry size specifies the limit for the size of an archive entry. If the size of an entry exceeds this limit, it will result in an error.

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Returns:**
long - the maximum archive entry size.
### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Sets the maximum allowed size for archive entries. The maximum allowed entry size specifies the limit for the size of an archive entry. If the size of an entry exceeds this limit, it will result in an error.

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxAllowedEntrySize | long | The maximum archive entry size. |

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Retrieves the maximum allowed count of entries in an archive. The maximum allowed entries count specifies the limit for the number of entries that an archive can contain. If an archive contains more entries than this limit, it cannot be extracted.

***Note:** The default value for the maximum allowed entries count is 1000.*

**Returns:**
long - the maximum count of entries in an archive.
### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Sets the maximum allowed count of entries in an archive. The maximum allowed entries count specifies the limit for the number of entries that an archive can contain. If an archive contains more entries than this limit, it cannot be extracted.

***Note:** The default value for the maximum allowed entries count is 1000.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxAllowedEntriesCount | long | The maximum count of entries in an archive. |

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Specifies the maximum compression ratio allowed for extracting archive entries.

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Returns:**
double - the maximum allowed compression ratio for archive entries.
### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Specifies the maximum compression ratio allowed for extracting archive entries.

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxAllowedEntryCompressionRatio | double | The maximum allowed compression ratio for archive entries. |

