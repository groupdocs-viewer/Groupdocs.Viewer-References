---
title: ArchiveSecurityOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Class that can be used to limit archives extraction process.
type: docs
weight: 11
url: /java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Class that can be used to limit archives extraction process.

Note: Not each archive type supports all options.
## Constructors

| Constructor | Description |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | Archive entry name length can not be more than specified in this option. |
| [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Archive entry name length can not be more than specified in this option. |
| [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Archive entry size can not be more than specified in this option. |
| [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Archive entry size can not be more than specified in this option. |
| [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Archive that contains more entries, than specified in this option can not be extracted. |
| [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Archive that contains more entries, than specified in this option can not be extracted. |
| [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Archive entries which compression ratio is more, than specified in this option can not be extracted. |
| [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Archive entries which compression ratio is more, than specified in this option can not be extracted. |
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


Archive entry name length can not be more than specified in this option. Default value is 255.

**Returns:**
int - Maximum archive entry name length
### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Archive entry name length can not be more than specified in this option. Default value is 255.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxAllowedEntryNameLength | int | Maximum archive entry name length. |

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Archive entry size can not be more than specified in this option. Default value is 10Gb (10737418240L).

**Returns:**
long - Maximum archive entry size.
### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Archive entry size can not be more than specified in this option. Default value is 10Gb (10737418240L).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxAllowedEntrySize | long | Maximum archive entry size |

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Archive that contains more entries, than specified in this option can not be extracted. Default value is 1000.

**Returns:**
long - Maximum count of entries in an archive.
### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Archive that contains more entries, than specified in this option can not be extracted. Default value is 1000.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxAllowedEntriesCount | long | Maximum count of entries in an archive. |

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Archive entries which compression ratio is more, than specified in this option can not be extracted. Default value is 100.

**Returns:**
double - Maximum allowed entries compression ratio.
### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Archive entries which compression ratio is more, than specified in this option can not be extracted. Default value is 100.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxAllowedEntryCompressionRatio | double | Maximum allowed entries compression ratio. |

