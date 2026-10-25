---
title: "ArchiveSecurityOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "アーカイブ抽出プロセスを制限するために使用できるクラスです。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.viewer.options/archivesecurityoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveSecurityOptions
```

アーカイブ抽出プロセスを制限するために使用できるクラスです。

ArchiveSecurityOptions クラスは、アーカイブの抽出を制限し、特定の制限を適用する方法を提供します。

使用例:

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

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ArchiveSecurityOptions()](#ArchiveSecurityOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getMaxAllowedEntryNameLength()](#getMaxAllowedEntryNameLength--) | このオプションは、アーカイブ エントリ名が持つことのできる最大長を指定します。 |
|
|  | [setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)](#setMaxAllowedEntryNameLength-int-) | アーカイブ エントリ名の最大許容長さを設定します。 |
|
|  | [getMaxAllowedEntrySize()](#getMaxAllowedEntrySize--) | アーカイブ エントリの最大許容サイズを取得します。 |
|
|  | [setMaxAllowedEntrySize(long maxAllowedEntrySize)](#setMaxAllowedEntrySize-long-) | アーカイブ エントリの最大許容サイズを設定します。 |
|
|  | [getMaxAllowedEntriesCount()](#getMaxAllowedEntriesCount--) | アーカイブ内のエントリの最大許容数を取得します。 |
|
|  | [setMaxAllowedEntriesCount(long maxAllowedEntriesCount)](#setMaxAllowedEntriesCount-long-) | アーカイブ内のエントリの最大許容数を設定します。 |
|
|  | [getMaxAllowedEntryCompressionRatio()](#getMaxAllowedEntryCompressionRatio--) | アーカイブ エントリの抽出時に許容される最大圧縮率を指定します。 |
|
|  | [setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)](#setMaxAllowedEntryCompressionRatio-double-) | アーカイブ エントリの抽出時に許容される最大圧縮率を指定します。 |
|
### ArchiveSecurityOptions() {#ArchiveSecurityOptions--}
```
public ArchiveSecurityOptions()
```


### getMaxAllowedEntryNameLength() {#getMaxAllowedEntryNameLength--}
```
public int getMaxAllowedEntryNameLength()
```


このオプションは、アーカイブ エントリ名が持つことのできる最大長を指定します。
エントリ名がこの制限を超えると、エラーが発生します。


***Note:** The default value for this option is 255.*


**Returns:**
int - アーカイブ エントリ名の最大許容長さです。

### setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength) {#setMaxAllowedEntryNameLength-int-}
```
public void setMaxAllowedEntryNameLength(int maxAllowedEntryNameLength)
```


アーカイブ エントリ名の最大許容長さを設定します。
最大許容長さは、アーカイブ エントリ名の長さの上限を指定します。
エントリ名の長さがこの上限を超えると、エラーが発生します。


***Note:** The default value for the maximum allowed entry name length is 255.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | maxAllowedEntryNameLength | int | 設定する最大アーカイブ エントリ名長さです。 |
|

### getMaxAllowedEntrySize() {#getMaxAllowedEntrySize--}
```
public long getMaxAllowedEntrySize()
```


アーカイブ エントリの最大許容サイズを取得します。
最大許容エントリサイズは、アーカイブ エントリのサイズの上限を指定します。
エントリのサイズがこの上限を超えると、エラーになります。


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Returns:**
long - 最大アーカイブ エントリサイズです。

### setMaxAllowedEntrySize(long maxAllowedEntrySize) {#setMaxAllowedEntrySize-long-}
```
public void setMaxAllowedEntrySize(long maxAllowedEntrySize)
```


アーカイブ エントリの最大許容サイズを設定します。
最大許容エントリサイズは、アーカイブ エントリのサイズの上限を指定します。
エントリのサイズがこの上限を超えると、エラーになります。


***Note:** The default value for the maximum allowed entry size is 10GB (10737418240 bytes).*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | maxAllowedEntrySize | long | 最大アーカイブ エントリサイズです。 |
|

### getMaxAllowedEntriesCount() {#getMaxAllowedEntriesCount--}
```
public long getMaxAllowedEntriesCount()
```


アーカイブ内のエントリの最大許容数を取得します。
最大許容エントリ数は、アーカイブが含むことのできるエントリ数の上限を指定します。
アーカイブがこの上限より多くのエントリを含む場合、抽出できません。


***Note:** The default value for the maximum allowed entries count is 1000.*


**Returns:**
long - アーカイブ内のエントリの最大数です。

### setMaxAllowedEntriesCount(long maxAllowedEntriesCount) {#setMaxAllowedEntriesCount-long-}
```
public void setMaxAllowedEntriesCount(long maxAllowedEntriesCount)
```


アーカイブ内のエントリの最大許容数を設定します。
最大許容エントリ数は、アーカイブが含むことのできるエントリ数の上限を指定します。
アーカイブがこの上限より多くのエントリを含む場合、抽出できません。


***Note:** The default value for the maximum allowed entries count is 1000.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | maxAllowedEntriesCount | long | アーカイブ内のエントリの最大数です。 |
|

### getMaxAllowedEntryCompressionRatio() {#getMaxAllowedEntryCompressionRatio--}
```
public double getMaxAllowedEntryCompressionRatio()
```


アーカイブ エントリの抽出時に許容される最大圧縮率を指定します。


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Returns:**
double - アーカイブエントリに許可される最大圧縮率です。

### setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio) {#setMaxAllowedEntryCompressionRatio-double-}
```
public void setMaxAllowedEntryCompressionRatio(double maxAllowedEntryCompressionRatio)
```


アーカイブ エントリの抽出時に許容される最大圧縮率を指定します。


***Note:** Archive entries with a compression ratio higher than the specified value cannot be extracted.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | maxAllowedEntryCompressionRatio | double | アーカイブエントリに許可される最大圧縮率です。 |
|

