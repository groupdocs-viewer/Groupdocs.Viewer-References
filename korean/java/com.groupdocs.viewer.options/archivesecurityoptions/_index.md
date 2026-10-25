---
title: "ArchiveSecurityOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "아카이브 추출 프로세스를 제한하는 데 사용할 수 있는 클래스입니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

아카이브 추출 프로세스를 제한하는 데 사용할 수 있는 클래스입니다.

ArchiveSecurityOptions 클래스는 아카이브 추출을 제한하고 특정 제한을 적용하는 방법을 제공합니다.

사용 예시:

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

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | 이 옵션은 아카이브 항목 이름이 가질 수 있는 최대 길이를 지정합니다. |
|
|  | [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | 아카이브 항목 이름에 허용되는 최대 길이를 설정합니다. |
|
|  | [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | 아카이브 항목에 허용되는 최대 크기를 검색합니다. |
|
|  | [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | 아카이브 항목에 허용되는 최대 크기를 설정합니다. |
|
|  | [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | 아카이브 내 항목의 허용되는 최대 개수를 검색합니다. |
|
|  | [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | 아카이브 내 항목의 허용되는 최대 개수를 설정합니다. |
|
|  | [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | 아카이브 항목을 추출할 때 허용되는 최대 압축 비율을 지정합니다. |
|
|  | [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | 아카이브 항목을 추출할 때 허용되는 최대 압축 비율을 지정합니다. |
|
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


이 옵션은 아카이브 항목 이름이 가질 수 있는 최대 길이를 지정합니다.
항목 이름이 이 제한을 초과하면 오류가 발생합니다.


***Note:** The default value for this option is 255.*


**Returns:**
int - 아카이브 항목 이름에 허용되는 최대 길이.

### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


아카이브 항목 이름에 허용되는 최대 길이를 설정합니다.
허용되는 최대 길이는 아카이브 항목 이름 길이의 제한을 지정합니다.
항목 이름의 길이가 이 제한을 초과하면 오류가 발생합니다.


***Note:** The default value for the maximum allowed entry name length is 255.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | maxAllowedEntryNameLength | int | 설정할 최대 아카이브 항목 이름 길이. |
|

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


아카이브 항목에 허용되는 최대 크기를 검색합니다.
허용되는 최대 항목 크기는 아카이브 항목 크기의 제한을 지정합니다.
항목의 크기가 이 제한을 초과하면 오류가 발생합니다.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Returns:**
long - 최대 아카이브 항목 크기.

### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


아카이브 항목에 허용되는 최대 크기를 설정합니다.
허용되는 최대 항목 크기는 아카이브 항목 크기의 제한을 지정합니다.
항목의 크기가 이 제한을 초과하면 오류가 발생합니다.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | maxAllowedEntrySize | long | 최대 아카이브 항목 크기. |
|

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


아카이브 내 항목의 허용되는 최대 개수를 검색합니다.
최대 허용 항목 수는 아카이브가 포함할 수 있는 항목 수의 제한을 지정합니다.
아카이브가 이 제한보다 더 많은 항목을 포함하면 추출할 수 없습니다.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Returns:**
long - 아카이브 내 최대 항목 수.

### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


아카이브 내 항목의 허용되는 최대 개수를 설정합니다.
최대 허용 항목 수는 아카이브가 포함할 수 있는 항목 수의 제한을 지정합니다.
아카이브가 이 제한보다 더 많은 항목을 포함하면 추출할 수 없습니다.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | maxAllowedEntriesCount | long | 아카이브 내 최대 항목 수. |
|

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


아카이브 항목을 추출할 때 허용되는 최대 압축 비율을 지정합니다.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Returns:**
double - 아카이브 항목에 대한 최대 허용 압축 비율.

### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


아카이브 항목을 추출할 때 허용되는 최대 압축 비율을 지정합니다.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | maxAllowedEntryCompressionRatio | double | 아카이브 항목에 대한 최대 허용 압축 비율. |
|

