---
title: "ArchiveSecurityOptions"
second_title: "Referensi API GroupDocs.Viewer for Java"
description: "Kelas yang dapat digunakan untuk membatasi proses ekstraksi arsip."
type: docs
weight: 11
url: /id/java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

Kelas yang dapat digunakan untuk membatasi proses ekstraksi arsip.

Kelas ArchiveSecurityOptions menyediakan cara untuk membatasi ekstraksi arsip dan menegakkan beberapa pembatasan.

Contoh penggunaan:

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

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | Opsi ini menentukan panjang maksimum yang dapat dimiliki nama entri arsip. |
|
|  | [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | Menetapkan panjang maksimum yang diizinkan untuk nama entri arsip. |
|
|  | [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | Mengambil ukuran maksimum yang diizinkan untuk entri arsip. |
|
|  | [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | Menetapkan ukuran maksimum yang diizinkan untuk entri arsip. |
|
|  | [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | Mengambil jumlah maksimum entri yang diizinkan dalam sebuah arsip. |
|
|  | [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | Menetapkan jumlah maksimum entri yang diizinkan dalam sebuah arsip. |
|
|  | [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | Menentukan rasio kompresi maksimum yang diizinkan untuk mengekstrak entri arsip. |
|
|  | [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | Menentukan rasio kompresi maksimum yang diizinkan untuk mengekstrak entri arsip. |
|
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


Opsi ini menentukan panjang maksimum yang dapat dimiliki nama entri arsip.
Jika nama entri melebihi batas ini, akan menyebabkan kesalahan.


***Note:** The default value for this option is 255.*


**Returns:**
int - panjang maksimum yang diizinkan untuk nama entri arsip.

### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


Menetapkan panjang maksimum yang diizinkan untuk nama entri arsip.
Panjang maksimum yang diizinkan menentukan batas untuk panjang nama entri arsip.
Jika panjang nama entri melebihi batas ini, akan menyebabkan kesalahan.


***Note:** The default value for the maximum allowed entry name length is 255.*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | maxAllowedEntryNameLength | int | Panjang maksimum nama entri arsip yang akan diatur. |
|

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


Mengambil ukuran maksimum yang diizinkan untuk entri arsip.
Ukuran entri maksimum yang diizinkan menentukan batas untuk ukuran entri arsip.
Jika ukuran entri melebihi batas ini, akan menghasilkan kesalahan.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Returns:**
long - ukuran entri arsip maksimum.

### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


Menetapkan ukuran maksimum yang diizinkan untuk entri arsip.
Ukuran entri maksimum yang diizinkan menentukan batas untuk ukuran entri arsip.
Jika ukuran entri melebihi batas ini, akan menghasilkan kesalahan.


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | maxAllowedEntrySize | long | Ukuran entri arsip maksimum. |
|

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


Mengambil jumlah maksimum entri yang diizinkan dalam sebuah arsip.
Jumlah entri maksimum yang diizinkan menentukan batas untuk jumlah entri yang dapat dimuat oleh sebuah arsip.
Jika sebuah arsip berisi lebih banyak entri daripada batas ini, arsip tersebut tidak dapat diekstrak.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Returns:**
long - jumlah maksimum entri dalam sebuah arsip.

### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


Menetapkan jumlah maksimum entri yang diizinkan dalam sebuah arsip.
Jumlah entri maksimum yang diizinkan menentukan batas untuk jumlah entri yang dapat dimuat oleh sebuah arsip.
Jika sebuah arsip berisi lebih banyak entri daripada batas ini, arsip tersebut tidak dapat diekstrak.


***Note:** The default value for the maximum allowed entries count is 1000.*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | maxAllowedEntriesCount | long | Jumlah maksimum entri dalam sebuah arsip. |
|

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


Menentukan rasio kompresi maksimum yang diizinkan untuk mengekstrak entri arsip.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Returns:**
double - rasio kompresi maksimum yang diizinkan untuk entri arsip.

### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


Menentukan rasio kompresi maksimum yang diizinkan untuk mengekstrak entri arsip.


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | maxAllowedEntryCompressionRatio | double | Rasio kompresi maksimum yang diizinkan untuk entri arsip. |
|

