---
title: "خاصية disable_font_license_verifications"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "الخاصية تُعطل أي قيود ترخيص لجميع الخطوط في مستند XPS/OXPS الحالي."
type: docs
url: /ar/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

الخاصية تُعطل أي قيود ترخيص لجميع الخطوط في مستند XPS/OXPS الحالي.

العديد من العمليات المتعلقة بالخطوط لا يمكن تنفيذها إذا كانت محظورة بموجب ترخيص الخط. على سبيل المثال، لا يمكن تضمين بعض الخطوط في مستند PDF إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. يتيح لك هذا الخيار تخطي التحقق من هذه القواعد.

كن حذرًا عند استخدام هذه العلامة. عندما يتم تعيينها، يعني ذلك أن الشخص الذي يضع هذه العلامة يتحمل جميع المسؤولية عن أي انتهاكات محتملة للترخيص أو القانون. يُنصح بشدة باستخدام هذه العلامة فقط عندما تكون واثقًا تمامًا من أنك لا تنتهك قانون حقوق النشر. القيمة الافتراضية هي `False`.

للحصول على مثال على الشيفرة، راجع الوثائق على https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### انظر أيضًا
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
