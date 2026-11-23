---
title: "ArchiveSecurityOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "فئة يمكن استخدامها لتقييد عملية استخراج الأرشيفات."
type: docs
weight: 11
url: /ar/java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

فئة يمكن استخدامها لتقييد عملية استخراج الأرشيفات.

توفر فئة ArchiveSecurityOptions طريقة لتقييد استخراج الأرشيفات وفرض بعض القيود.

مثال على الاستخدام:

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

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | تحدد هذه الخاصية الحد الأقصى للطول الذي يمكن أن يكون عليه اسم مدخل الأرشيف. |
|
|  | [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | يضبط الحد الأقصى المسموح به لطول أسماء مدخلات الأرشيف. |
|
|  | [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | يسترجع الحد الأقصى المسموح به لحجم مدخلات الأرشيف. |
|
|  | [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | يضبط الحد الأقصى المسموح به لحجم مدخلات الأرشيف. |
|
|  | [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | يسترجع الحد الأقصى المسموح به لعدد المدخلات في الأرشيف. |
|
|  | [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | يضبط الحد الأقصى المسموح به لعدد المدخلات في الأرشيف. |
|
|  | [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | يحدد نسبة الضغط القصوى المسموح بها لاستخراج مدخلات الأرشيف. |
|
|  | [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | يحدد نسبة الضغط القصوى المسموح بها لاستخراج مدخلات الأرشيف. |
|
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


تحدد هذه الخاصية الحد الأقصى للطول الذي يمكن أن يكون عليه اسم مدخل الأرشيف.
إذا تجاوز اسم المدخل هذا الحد، سيتسبب ذلك في حدوث خطأ.


***Note:** The default value for this option is 255.*


**Returns:**
int - الحد الأقصى المسموح به لطول أسماء مدخلات الأرشيف.

### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


يضبط الحد الأقصى المسموح به لطول أسماء مدخلات الأرشيف.
الحد الأقصى المسموح به يحدد القيد لطول اسم مدخل الأرشيف.
إذا تجاوز طول اسم المدخل هذا الحد، سيتسبب ذلك في حدوث خطأ.


***Note:** The default value for the maximum allowed entry name length is 255.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | maxAllowedEntryNameLength | int | الحد الأقصى لطول اسم مدخل الأرشيف الذي سيتم تعيينه. |
|

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


يسترجع الحد الأقصى المسموح به لحجم مدخلات الأرشيف.
الحد الأقصى المسموح به لحجم المدخل يحدد القيد لحجم مدخل الأرشيف.
إذا تجاوز حجم المدخل هذا الحد، سيتسبب ذلك في حدوث خطأ.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Returns:**
long - الحد الأقصى لحجم مدخل الأرشيف.

### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


يضبط الحد الأقصى المسموح به لحجم مدخلات الأرشيف.
الحد الأقصى المسموح به لحجم المدخل يحدد القيد لحجم مدخل الأرشيف.
إذا تجاوز حجم المدخل هذا الحد، سيتسبب ذلك في حدوث خطأ.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | maxAllowedEntrySize | long | الحد الأقصى لحجم مدخل الأرشيف. |
|

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


يسترجع الحد الأقصى المسموح به لعدد المدخلات في الأرشيف.
عدد المدخلات المسموح به كحد أقصى يحدد الحد لعدد المدخلات التي يمكن أن يحتويها الأرشيف.
إذا كان الأرشيف يحتوي على عدد مدخلات أكبر من هذا الحد، لا يمكن استخراجها.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Returns:**
long - الحد الأقصى لعدد المدخلات في الأرشيف.

### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


يضبط الحد الأقصى المسموح به لعدد المدخلات في الأرشيف.
عدد المدخلات المسموح به كحد أقصى يحدد الحد لعدد المدخلات التي يمكن أن يحتويها الأرشيف.
إذا كان الأرشيف يحتوي على عدد مدخلات أكبر من هذا الحد، لا يمكن استخراجها.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | maxAllowedEntriesCount | long | الحد الأقصى لعدد المدخلات في الأرشيف. |
|

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


يحدد نسبة الضغط القصوى المسموح بها لاستخراج مدخلات الأرشيف.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Returns:**
double - النسبة القصوى المسموح بها للضغط لمدخلات الأرشيف.

### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


يحدد نسبة الضغط القصوى المسموح بها لاستخراج مدخلات الأرشيف.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | maxAllowedEntryCompressionRatio | double | النسبة القصوى المسموح بها للضغط لمدخلات الأرشيف. |
|

