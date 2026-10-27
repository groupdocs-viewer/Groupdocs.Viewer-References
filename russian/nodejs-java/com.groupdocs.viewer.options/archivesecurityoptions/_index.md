---
title: "ArchiveSecurityOptions"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Класс, который можно использовать для ограничения процесса извлечения архивов."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Класс, который можно использовать для ограничения процесса извлечения архивов.

Класс ArchiveSecurityOptions предоставляет возможность ограничить извлечение архивов и применять определённые ограничения.

Пример использования:

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

***Note:** Not each archive type supports all options.*
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | Эта опция задаёт максимальную длину имени записи архива. |
| [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Устанавливает максимальную допустимую длину имён записей архива. |
| [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Получает максимальный допустимый размер записей архива. |
| [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Устанавливает максимальный допустимый размер записей архива. |
| [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Получает максимальное допустимое количество записей в архиве. |
| [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Устанавливает максимальное допустимое количество записей в архиве. |
| [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Указывает максимальное допустимое соотношение сжатия при извлечении записей архива. |
| [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Указывает максимальное допустимое соотношение сжатия при извлечении записей архива. |
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


Эта опция задаёт максимальную длину имени записи архива. Если имя записи превышает этот предел, будет возникать ошибка.

***Note:** The default value for this option is 255.*

**Returns:**
int — максимальная допустимая длина имён записей архива.
### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Устанавливает максимальную допустимую длину имен записей архива. Максимальная допустимая длина определяет предел для длины имени записи архива. Если длина имени записи превышает этот предел, возникнет ошибка.

***Note:** The default value for the maximum allowed entry name length is 255.*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxAllowedEntryNameLength | int | Максимальная длина имени записи архива, которую необходимо установить. |

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Получает максимальный допустимый размер записей архива. Максимальный допустимый размер записи определяет предел для размера записи архива. Если размер записи превышает этот предел, возникнет ошибка.

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Returns:**
long — максимальный размер записи архива.
### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Устанавливает максимальный допустимый размер записей архива. Максимальный допустимый размер записи определяет предел для размера записи архива. Если размер записи превышает этот предел, возникнет ошибка.

***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxAllowedEntrySize | long | Максимальный размер записи архива. |

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Получает максимальное допустимое количество записей в архиве. Максимальное допустимое количество записей определяет предел для числа записей, которые может содержать архив. Если архив содержит больше записей, чем этот предел, его нельзя будет извлечь.

***Note:** The default value for the maximum allowed entries count is 1000.*

**Returns:**
long — максимальное количество записей в архиве.
### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Устанавливает максимальное допустимое количество записей в архиве. Максимальное допустимое количество записей определяет предел для числа записей, которые может содержать архив. Если архив содержит больше записей, чем этот предел, его нельзя будет извлечь.

***Note:** The default value for the maximum allowed entries count is 1000.*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxAllowedEntriesCount | long | Максимальное количество записей в архиве. |

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Указывает максимальное допустимое соотношение сжатия при извлечении записей архива.

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Returns:**
double — максимальное допустимое коэффициент сжатия для записей архива.
### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Указывает максимальное допустимое соотношение сжатия при извлечении записей архива.

***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| maxAllowedEntryCompressionRatio | double | Максимальный допустимый коэффициент сжатия для записей архива. |

