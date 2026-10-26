---
title: "com.groupdocs.viewer.interfaces"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "توفر الحزمة واجهات لإنشاء وإصدار المستند الناتج وموارده."
type: docs
weight: 15
url: /ar/nodejs-java/com.groupdocs.viewer.interfaces/
---

توفر الحزمة واجهات لإنشاء وإصدار المستند الناتج وموارده.

تُستخدم هذه الواجهات لإدارة إنشاء وإصدار التدفقات وعناوين URL المرتبطة بملف الإخراج والصفحات وموارد HTML.

الواجهات الرئيسية في هذه الحزمة هي:

 *  [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
 *  [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
 *  [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.

لمزيد من التفاصيل حول العمل مع هذه الواجهات وتخصيص مستند الإخراج ومعالجة الموارد في GroupDocs.Viewer، يرجى الرجوع إلى [GroupDocs.Viewer Documentation][].


[GroupDocs.Viewer Documentation]: https://docs.groupdocs.com/viewer/java/


## الواجهات

| واجهة | الوصف |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | يمثل واجهة تقوم بإنشاء تدفق يُستخدم لكتابة بيانات ملف الإخراج. |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | يمثل واجهة تقوم بإنشاء تدفق يُستخدم لكتابة بيانات صفحة الإخراج. |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | يمثل واجهة تقوم بإنشاء تدفق يُستخدم لكتابة بيانات موارد HTML للإخراج. |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | يمثل واجهة تقوم بإنشاء عنوان URL لمورد HTML. |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | يعلن عن واجهة لقراءة تدفق ملف. |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | يحدد الأساليب المطلوبة لإنشاء وإصدار تدفق ملف الإخراج. |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | يحدد الأساليب المطلوبة لإنشاء وإصدار تدفق صفحة الإخراج. |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | يطلق واجهة تم إنشاؤها بواسطة الطريقة المرتبطة بواجهة CreateFileStream. |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | يطلق تدفقًا تم إنشاؤه بواسطة الطريقة المرتبطة بواجهة CreatePageStream. |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | يطلق تدفقًا تم إنشاؤه بواسطة الطريقة المرتبطة بواجهة CreateResourceStream. |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | يحدد الطرق المطلوبة لإنشاء عنوان URL للموارد، وإنشاء، وإطلاق تدفق مورد HTML للإخراج. |
