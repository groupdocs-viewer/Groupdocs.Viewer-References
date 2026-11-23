---
title: "FileReader"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يعلن عن واجهة لقراءة تدفق ملف."
type: docs
weight: 14
url: /ar/nodejs-java/com.groupdocs.viewer.interfaces/filereader/
---
**All Implemented Interfaces:**
java.io.Closeable
```
public interface FileReader extends Closeable
```

يعلن عن واجهة لقراءة تدفق ملف.

توفر واجهة FileReader طريقة لقراءة تدفق ملف. تُستخدم للوصول إلى محتويات الملف وقراءتها بطريقة متسلسلة. يجب على تطبيقات هذه الواجهة التعامل مع العمليات اللازمة لقراءة البيانات من الملف.

مثال على الاستخدام:

```

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
 
```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [read()](#read--) | يعيد InputStream يمثل تدفقًا قابلًا للقراءة للملف. |
| [close()](#close--) | يقوم بتحرير الكائن وإصدار أي موارد نظام مرتبطة به. |
### read() {#read--}
```
public abstract InputStream read()
```


يعيد InputStream يمثل تدفقًا قابلًا للقراءة للملف.

**Returns:**
java.io.InputStream - تدفق InputStream القابل للقراءة.
### close() {#close--}
```
public abstract void close()
```


يقوم بتحرير الكائن وإصدار أي موارد نظام مرتبطة به.

