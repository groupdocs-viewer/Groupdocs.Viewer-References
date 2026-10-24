---
title: "FileReader"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يعلن عن واجهة لقراءة تدفق ملف."
type: docs
weight: 14
url: /ar/java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

يعلن عن واجهة لقراءة تدفق ملف.


توفر واجهة FileReader طريقة لقراءة تدفق ملف. تُستخدم للوصول إلى محتويات الملف وقراءتها
من ملف بطريقة تسلسلية. يجب على تطبيقات هذه الواجهة التعامل مع العمليات اللازمة لقراءة البيانات من ملف.


مثال على الاستخدام:

````

 FileReader fileReader = new FileReader() {
     @Override
     public InputStream read() {
         // Create document stream
     }

     @Override
     public void close() {
         // Close the stream
     }
 };
 try (Viewer viewer = new Viewer(fileReader, new ViewerSettings())){
     // Process document
 }
 
````


## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [read()](#read--) | يرجع InputStream يمثل تدفقًا قابلًا للقراءة للملف. |
|
|  | [close()](#close--) | يُفرغ الكائن ويُطلق أي موارد نظام مرتبطة به. |
|
### read() {#read--}
```
public abstract InputStream read()
```


يرجع InputStream يمثل تدفقًا قابلًا للقراءة للملف.


**Returns:**
java.io.InputStream - تدفق InputStream القابل للقراءة.

### close() {#close--}
```
public abstract void close()
```


يُفرغ الكائن ويُطلق أي موارد نظام مرتبطة به.


