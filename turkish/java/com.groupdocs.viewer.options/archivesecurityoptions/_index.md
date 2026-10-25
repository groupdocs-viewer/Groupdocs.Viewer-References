---
title: "ArchiveSecurityOptions"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Arşiv çıkarma sürecini sınırlamak için kullanılabilecek sınıf."
type: docs
weight: 11
url: /tr/java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Arşiv çıkarma sürecini sınırlamak için kullanılabilecek sınıf.

ArchiveSecurityOptions sınıfı, arşivlerin çıkarılmasını sınırlamak ve belirli kısıtlamaları uygulamak için bir yol sağlar.

Örnek kullanım:

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

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | Bu seçenek, bir arşiv girdi adının sahip olabileceği maksimum uzunluğu belirtir. |
|
|  | [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Arşiv girdi adları için izin verilen maksimum uzunluğu ayarlar. |
|
|  | [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Arşiv girdileri için izin verilen maksimum boyutu alır. |
|
|  | [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Arşiv girdileri için izin verilen maksimum boyutu ayarlar. |
|
|  | [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Bir arşivdeki izin verilen maksimum girdi sayısını alır. |
|
|  | [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Bir arşivdeki izin verilen maksimum girdi sayısını ayarlar. |
|
|  | [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Arşiv girdilerini çıkarmak için izin verilen maksimum sıkıştırma oranını belirtir. |
|
|  | [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Arşiv girdilerini çıkarmak için izin verilen maksimum sıkıştırma oranını belirtir. |
|
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


Bu seçenek, bir arşiv girdi adının sahip olabileceği maksimum uzunluğu belirtir.
Bir girdi adı bu sınırı aşarsa, bir hata oluşur.


***Note:** The default value for this option is 255.*


**Returns:**
int - arşiv girdi adları için izin verilen maksimum uzunluk.

### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Arşiv girdi adları için izin verilen maksimum uzunluğu ayarlar.
İzin verilen maksimum uzunluk, bir arşiv girdi adının uzunluğu için sınırı belirtir.
Bir girdi adının uzunluğu bu sınırı aşarsa, bir hata oluşur.


***Note:** The default value for the maximum allowed entry name length is 255.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | maxAllowedEntryNameLength | int | Ayarlanacak maksimum arşiv girdi adı uzunluğu. |
|

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Arşiv girdileri için izin verilen maksimum boyutu alır.
İzin verilen maksimum girdi boyutu, bir arşiv girdisinin boyutu için sınırı belirtir.
Bir girdi boyutu bu sınırı aşarsa, bir hata oluşur.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Returns:**
long - maksimum arşiv girdi boyutu.

### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Arşiv girdileri için izin verilen maksimum boyutu ayarlar.
İzin verilen maksimum girdi boyutu, bir arşiv girdisinin boyutu için sınırı belirtir.
Bir girdi boyutu bu sınırı aşarsa, bir hata oluşur.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | maxAllowedEntrySize | long | Maksimum arşiv girdi boyutu. |
|

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Bir arşivdeki izin verilen maksimum girdi sayısını alır.
İzin verilen maksimum girdi sayısı, bir arşivin içerebileceği girdi sayısı için sınırı belirtir.
Bir arşiv bu sınırdan daha fazla girdi içeriyorsa, çıkarılamaz.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Returns:**
long - bir arşivdeki maksimum girdi sayısı.

### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Bir arşivdeki izin verilen maksimum girdi sayısını ayarlar.
İzin verilen maksimum girdi sayısı, bir arşivin içerebileceği girdi sayısı için sınırı belirtir.
Bir arşiv bu sınırdan daha fazla girdi içeriyorsa, çıkarılamaz.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | maxAllowedEntriesCount | long | Arşivdeki girişlerin maksimum sayısı. |
|

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Arşiv girdilerini çıkarmak için izin verilen maksimum sıkıştırma oranını belirtir.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Returns:**
double - arşiv girişleri için izin verilen maksimum sıkıştırma oranı.

### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Arşiv girdilerini çıkarmak için izin verilen maksimum sıkıştırma oranını belirtir.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | maxAllowedEntryCompressionRatio | double | Arşiv girişleri için izin verilen maksimum sıkıştırma oranı. |
|

