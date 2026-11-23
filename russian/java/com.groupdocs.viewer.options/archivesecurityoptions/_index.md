---
title: "ArchiveSecurityOptions"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Класс, который можно использовать для ограничения процесса извлечения архивов."
type: docs
weight: 11
url: /ru/java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Класс, который можно использовать для ограничения процесса извлечения архивов.

Класс ArchiveSecurityOptions предоставляет способ ограничить извлечение архивов и применять определённые ограничения.

Пример использования:

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

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | Эта опция указывает максимальную длину имени записи архива. |
|
|  | [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Устанавливает максимально допустимую длину имён записей архива. |
|
|  | [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Получает максимально допустимый размер записей архива. |
|
|  | [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Устанавливает максимально допустимый размер записей архива. |
|
|  | [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Получает максимально допустимое количество записей в архиве. |
|
|  | [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Устанавливает максимально допустимое количество записей в архиве. |
|
|  | [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Указывает максимальное коэффициент сжатия, разрешённый при извлечении записей архива. |
|
|  | [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Указывает максимальное коэффициент сжатия, разрешённый при извлечении записей архива. |
|
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


Эта опция указывает максимальную длину имени записи архива.
Если имя записи превышает этот предел, возникнет ошибка.


***Note:** The default value for this option is 255.*


**Returns:**
int — максимальная допустимая длина имён записей архива.

### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Устанавливает максимально допустимую длину имён записей архива.
Максимальная допустимая длина указывает предел длины имени записи архива.
Если длина имени записи превышает этот предел, возникнет ошибка.


***Note:** The default value for the maximum allowed entry name length is 255.*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | maxAllowedEntryNameLength | int | Максимальная длина имени записи архива, которую следует установить. |
|

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Получает максимально допустимый размер записей архива.
Максимальный допустимый размер записи указывает предел размера записи архива.
Если размер записи превышает этот предел, это приведёт к ошибке.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Returns:**
long - максимальный размер записи архива.

### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Устанавливает максимально допустимый размер записей архива.
Максимальный допустимый размер записи указывает предел размера записи архива.
Если размер записи превышает этот предел, это приведёт к ошибке.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | maxAllowedEntrySize | long | Максимальный размер записи архива. |
|

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Получает максимально допустимое количество записей в архиве.
Максимальное допустимое количество записей указывает ограничение на число записей, которые может содержать архив.
Если архив содержит больше записей, чем это ограничение, его нельзя извлечь.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Returns:**
long - максимальное количество записей в архиве.

### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Устанавливает максимально допустимое количество записей в архиве.
Максимальное допустимое количество записей указывает ограничение на число записей, которые может содержать архив.
Если архив содержит больше записей, чем это ограничение, его нельзя извлечь.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | maxAllowedEntriesCount | long | Максимальное количество записей в архиве. |
|

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Указывает максимальное коэффициент сжатия, разрешённый при извлечении записей архива.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Returns:**
double - максимальный допустимый коэффициент сжатия для записей архива.

### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Указывает максимальное коэффициент сжатия, разрешённый при извлечении записей архива.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | maxAllowedEntryCompressionRatio | double | Максимальный допустимый коэффициент сжатия для записей архива. |
|

