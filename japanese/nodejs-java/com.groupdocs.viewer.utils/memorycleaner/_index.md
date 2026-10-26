---
title: "MemoryCleaner"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "さまざまなリソースをクリーンアップしてメモリを解放します。"
type: docs
weight: 10
url: /ja/nodejs-java/com.groupdocs.viewer.utils/memorycleaner/
---
**Inheritance:**
java.lang.Object
```
public final class MemoryCleaner
```

さまざまなリソースをクリーンアップしてメモリを解放します。

このクラスは、ヒープメモリをクリアし、テンポラリファイルを削除し、フォントレジストリ情報をクリアするメソッドを提供します。また、現在のスレッドのスレッドローカルインスタンスを安全にクリアするメソッドも含まれています。

使用例:

```

 // Clean heap memory, keeping font settings
 MemoryCleaner.clearKeepingFontSettings();

 // Clean heap memory and delete temp files
 MemoryCleaner.clear();

 // Clean heap memory from static PDF instances
 MemoryCleaner.clearStaticInstances();

 // Delete all temp files created by PDF in the system temp directory
 MemoryCleaner.clearAllTempFiles();

 // Clear font registry information from heap memory
 MemoryCleaner.clearFontRegistry();

 // Safely clear thread-local instances for the current thread
 MemoryCleaner.clearCurrentThreadLocals();
 
```
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [MemoryCleaner()](#MemoryCleaner--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [clearKeepingFontSettings()](#clearKeepingFontSettings--) | 静的 PDF インスタンス（static と threadLocal）からヒープメモリをクリアし、すべてのテンポラリファイルを削除します。 |
| [clear()](#clear--) | 静的 PDF インスタンス（static と threadLocal）からヒープメモリをクリアし、すべてのテンポラリファイルを削除します。 |
| [clearStaticInstances()](#clearStaticInstances--) | 静的 PDF インスタンスからヒープメモリをクリアします。 |
| [clearAllTempFiles()](#clearAllTempFiles--) | システムのテンポラリディレクトリに GroupDocs.Viewer が作成したテンポラリファイルをクリアします。 |
| [clearFontRegistry()](#clearFontRegistry--) | ヒープメモリからフォントレジストリ情報をクリアします。 |
| [clearCurrentThreadLocals()](#clearCurrentThreadLocals--) | 現在のスレッドのスレッドローカルインスタンスからヒープメモリを安全にクリアします。 |
### MemoryCleaner() {#MemoryCleaner--}
```
public MemoryCleaner()
```


### clearKeepingFontSettings() {#clearKeepingFontSettings--}
```
public static void clearKeepingFontSettings()
```


静的 PDF インスタンス（static と threadLocal）からヒープメモリをクリアし、すべてのテンポラリファイルを削除します。このメソッドはフォント設定に影響しません。

### clear() {#clear--}
```
public static void clear()
```


静的 PDF インスタンス（static と threadLocal）からヒープメモリをクリアし、すべてのテンポラリファイルを削除します。

### clearStaticInstances() {#clearStaticInstances--}
```
public static void clearStaticInstances()
```


静的 PDF インスタンスからヒープメモリをクリアします。

### clearAllTempFiles() {#clearAllTempFiles--}
```
public static void clearAllTempFiles()
```


システムのテンポラリディレクトリに GroupDocs.Viewer が作成したテンポラリファイルをクリアします。

### clearFontRegistry() {#clearFontRegistry--}
```
public static void clearFontRegistry()
```


ヒープメモリからフォントレジストリ情報をクリアします。

### clearCurrentThreadLocals() {#clearCurrentThreadLocals--}
```
public static void clearCurrentThreadLocals()
```


現在のスレッドのスレッドローカルインスタンスからヒープメモリを安全にクリアします。

