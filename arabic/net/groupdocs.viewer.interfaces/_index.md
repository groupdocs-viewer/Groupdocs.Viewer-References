---
title: "GroupDocs.Viewer.Interfaces"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "النطاق يوفر واجهات لإنشاء وإصدار مستند الإخراج وموارده."
type: docs
weight: 60
url: /ar/net/groupdocs.viewer.interfaces/
---

توفر مساحة الاسم واجهات لإنشاء وإطلاق المستند الناتج وموارده.

## الفئات

| الفئة | الوصف |
| --- | --- |
| [CreateFileStream](./createfilestream) | يمثل الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات ملف الإخراج. |
| [CreatePageStream](./createpagestream) | يمثل الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات صفحة الإخراج. |
| [CreateResourceStream](./createresourcestream) | يمثل الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات مورد HTML للإخراج. |
| [CreateResourceUrl](./createresourceurl) | يمثل الطريقة التي تنشئ عنوان URL لمورد HTML. |
| [ReleaseFileStream](./releasefilestream) | يطلق الدفق الذي تم إنشاؤه بواسطة الطريقة المرتبطة بالمندوب [`CreateFileStream`](../groupdocs.viewer.interfaces/createfilestream). |
| [ReleasePageStream](./releasepagestream) | يطلق الدفق الذي تم إنشاؤه بواسطة الطريقة المرتبطة بالمندوب [`CreatePageStream`](../groupdocs.viewer.interfaces/createpagestream). |
| [ReleaseResourceStream](./releaseresourcestream) | يطلق الدفق الذي تم إنشاؤه بواسطة الطريقة المرتبطة بالمندوب [`CreateResourceStream`](../groupdocs.viewer.interfaces/createresourcestream). |
## الواجهات

| واجهة | الوصف |
| --- | --- |
| [IFileStreamFactory](./ifilestreamfactory) | يحدد الطرق المطلوبة لإنشاء وإطلاق دفق ملف الإخراج. |
| [IPageStreamFactory](./ipagestreamfactory) | يحدد الطرق المطلوبة لإنشاء وإطلاق دفق صفحة الإخراج. |
| [IResourceStreamFactory](./iresourcestreamfactory) | يحدد الطرق المطلوبة لإنشاء عنوان URL للمورد، وإنشاء وإطلاق دفق مورد HTML للإخراج. |

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
