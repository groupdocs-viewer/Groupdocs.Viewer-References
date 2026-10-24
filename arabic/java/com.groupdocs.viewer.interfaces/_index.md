---
title: "com.groupdocs.viewer.interfaces"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "توفر الحزمة واجهات لإنشاء وإصدار المستند الناتج وموارده."
type: docs
weight: 17
url: /ar/java/com.groupdocs.viewer.interfaces/
---

توفر الحزمة واجهات لإنشاء وإصدار المستند الناتج وموارده.


تُستخدم هذه الواجهات لإدارة إنشاء وإصدار التدفقات وعناوين URL المرتبطة بملف الإخراج والصفحات والموارد HTML.

الواجهات الرئيسية في هذه الحزمة هي:

* [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
* [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
* [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.


لمزيد من التفاصيل حول العمل بهذه الواجهات وتخصيص مستند الإخراج ومعالجة الموارد في GroupDocs.Viewer،
يرجى الرجوع إلى [GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/).



## الواجهات

| واجهة | الوصف |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | يمثل واجهة تُنشئ تدفقًا يُستخدم لكتابة بيانات ملف الإخراج. |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | يمثل واجهة تُنشئ تدفقًا يُستخدم لكتابة بيانات صفحة الإخراج. |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | يمثل واجهة تُنشئ تدفقًا يُستخدم لكتابة بيانات مورد HTML للإخراج. |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | يمثل واجهة تُنشئ عنوان URL لمورد HTML. |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | يعلن عن واجهة لقراءة تدفق ملف. |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | يحدد الطرق المطلوبة لإنشاء وإصدار تدفق ملف الإخراج. |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | يحدد الطرق المطلوبة لإنشاء وإصدار تدفق صفحة الإخراج. |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | يُصدر واجهة تم إنشاؤها بواسطة الطريقة المرتبطة بواجهة CreateFileStream. |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | يُصدر تدفقًا تم إنشاؤه بواسطة الطريقة المرتبطة بواجهة CreatePageStream. |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | يُصدر تدفقًا تم إنشاؤه بواسطة الطريقة المرتبطة بواجهة CreateResourceStream. |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | يحدد الطرق المطلوبة لإنشاء عنوان URL للمورد، وإنشاء وإصدار تدفق مورد HTML للإخراج. |
