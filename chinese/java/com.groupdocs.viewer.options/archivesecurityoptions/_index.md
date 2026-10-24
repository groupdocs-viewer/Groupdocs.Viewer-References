---
title: "ArchiveSecurityOptions"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "可用于限制归档提取过程的类。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

可用于限制归档提取过程的类。

ArchiveSecurityOptions 类提供了一种限制归档提取并强制执行某些限制的方法。

示例用法：

````

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
 
````


***Note:** Not each archive type supports all options.*

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | 此选项指定归档条目名称可以拥有的最大长度。 |
|
|  | [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | 设置归档条目名称的最大允许长度。 |
|
|  | [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | 检索归档条目的最大允许大小。 |
|
|  | [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | 设置归档条目的最大允许大小。 |
|
|  | [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | 检索归档中条目的最大允许计数。 |
|
|  | [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | 设置归档中条目的最大允许计数。 |
|
|  | [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | 指定提取归档条目时允许的最大压缩比。 |
|
|  | [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | 指定提取归档条目时允许的最大压缩比。 |
|
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


此选项指定归档条目名称可以拥有的最大长度。
如果条目名称超过此限制，将导致错误。


***Note:** The default value for this option is 255.*


**Returns:**
int - 归档条目名称的最大允许长度。

### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


设置归档条目名称的最大允许长度。
最大允许长度指定归档条目名称长度的限制。
如果条目名称的长度超过此限制，将导致错误。


***Note:** The default value for the maximum allowed entry name length is 255.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | maxAllowedEntryNameLength | int | 要设置的最大归档条目名称长度。 |
|

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


检索归档条目的最大允许大小。
最大允许条目大小指定归档条目大小的限制。
如果条目的大小超过此限制，将导致错误。


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Returns:**
long - 最大存档条目大小。

### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


设置归档条目的最大允许大小。
最大允许条目大小指定归档条目大小的限制。
如果条目的大小超过此限制，将导致错误。


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | maxAllowedEntrySize | long | 最大存档条目大小。 |
|

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


检索归档中条目的最大允许计数。
最大允许的条目计数指定了存档可以包含的条目数量的上限。
如果存档包含的条目超过此上限，则无法解压缩。


***Note:** The default value for the maximum allowed entries count is 1000.*


**Returns:**
long - 存档中最大条目数量。

### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


设置归档中条目的最大允许计数。
最大允许的条目计数指定了存档可以包含的条目数量的上限。
如果存档包含的条目超过此上限，则无法解压缩。


***Note:** The default value for the maximum allowed entries count is 1000.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | maxAllowedEntriesCount | long | 存档中最大条目数量。 |
|

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


指定提取归档条目时允许的最大压缩比。


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Returns:**
double - 存档条目允许的最大压缩比。

### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


指定提取归档条目时允许的最大压缩比。


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | maxAllowedEntryCompressionRatio | double | 存档条目允许的最大压缩比。 |
|

