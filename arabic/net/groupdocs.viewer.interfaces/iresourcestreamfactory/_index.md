---
title: "IResourceStreamFactory"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحدد الطرق المطلوبة لإنشاء عنوان URL للمورد وتثبيته وإطلاق تدفق مورد HTML الناتج."
type: docs
weight: 770
url: /ar/net/groupdocs.viewer.interfaces/iresourcestreamfactory/
---

## IResourceStreamFactory interface

يحدد الطرق المطلوبة لإنشاء عنوان URL للمورد، وإنشاء وإطلاق دفق مورد HTML للإخراج.

```csharp
public interface IResourceStreamFactory
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourcestream)(int, Resource) | ينشئ التدفق المستخدم لكتابة بيانات مورد HTML الناتج. |
| [CreateResourceUrl](../../groupdocs.viewer.interfaces/iresourcestreamfactory/createresourceurl)(int, Resource) | ينشئ عنوان URL لمورد HTML. |
| [ReleaseResourceStream](../../groupdocs.viewer.interfaces/iresourcestreamfactory/releaseresourcestream)(int, Resource, Stream) | يطلق التدفق الذي أنشأته الطريقة [`CreateResourceStream`](./createresourcestream). |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
