---
title: "نظرة عامة على الميزات"
linkTitle: "Features overview"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "تحويل المستندات إلى HTML أو PDF أو PNG أو JPEG؛ استخراج النص؛ سرد المرفقات؛ وتطبيق الدورانات وإعادة الترتيب والعلامات المائية باستخدام GroupDocs.Viewer للبايثون عبر .NET."
type: docs
url: /ar/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Rendering Documents

المصطلح *rendering* في GroupDocs.Viewer يصف عملية تحويل المستند إلى تنسيق ملف يحافظ على حدود الصفحات. على سبيل المثال، عندما يتم تحويل ملف DOCX مكوّن من ثلاث صفحات إلى HTML، تكون النتيجة ثلاثة ملفات HTML — واحد لكل صفحة. راجع [دليل المطور]() للحصول على أمثلة قابلة للتنفيذ.

![Rendering diagram](https://docs.groupdocs.com/viewer/python-net/images/getting-started/features-overview/rendering.png)

### Rendering to HTML

يُعد التحويل إلى HTML الخيار الأفضل عندما تحتاج إلى:

- Build a web-based application and display document content inside a browser.
- Allow users to interact with the rendered text — select, copy, or search it.
- View document pages separately.
- Zoom in on a document without quality loss.
- Rotate, reorder, or watermark pages.

يقدم GroupDocs.Viewer للبايثون وضعين لإدارة موارد HTML:

- **HTML with external resources** — stores page resources (CSS, fonts, images) next to the HTML file so common resources are reused across pages. Reduces overall page size and speeds up loading.
- **HTML with embedded resources** — inlines every resource into the HTML file so each page is self-contained. Larger individual files but easier to distribute.

### Rendering to PNG or JPEG

يُعد التحويل إلى PNG أو JPEG الخيار الأفضل عندما تحتاج إلى:

- Support any type of application (desktop, web, mobile, CLI).
- Restrict interaction with rendered text — for example, to prevent copying. You can still extract a text layer separately if you want to overlay selectable text on the image.
- View document pages separately.
- Rotate, reorder, or watermark pages.

مقارنة سريعة بين تنسيقي الصورة الاثنين:

- **PNG** is a lossless raster format that supports full-colour images and transparency. PNG does not expose a quality setting. It is a good choice for line drawings, text, and iconic graphics at small file sizes.
- **JPEG** is a lossy compressed format whose quality can be tuned — lowering the quality removes detail and adds noise, but the file becomes smaller. JPEG is optimal for photographs and any image with a large colour range, and is a common web choice thanks to its compression ratio.

### Rendering to PDF

يقوم GroupDocs.Viewer بتحويل المستند إلى ملف PDF واحد. التحويل إلى PDF هو الخيار الأفضل عندما تحتاج إلى:

- Print documents.
- Send documents via email.
- Distribute all pages as a single file rather than a collection of per-page files.

## Retrieving Document Information

يكشف GroupDocs.Viewer للبايثون عن معلومات أساسية حول المستند المصدر — نوع الملف، عدد الصفحات، النص مع الإحداثيات، وأكثر — دون تحويل. راجع [احصل على معلومات المستند]().

المعلومات الخاصة بالتنسيق متاحة أيضًا:

- **Archive** — list of folders contained in the archive.
- **CAD** — list of layers and layouts in a CAD document.
- **Email** — list of folders contained in an Outlook data file.
- **PDF** — a flag that indicates whether document printing is allowed.
- **Project Management** — project start and end dates.

### Text extraction

يمكنك اختيار استخراج نص المستند عند التحويل إلى PNG أو JPEG. يتم إرجاع النص مع إحداثيات كل كلمة، مما يكون مفيدًا عند وضع طبقة نصية قابلة للتحديد فوق صورة الصفحة.

## Processing Attachments

في GroupDocs.Viewer، يغطي *attachments* مرفقات البريد الإلكتروني، والملفات المدمجة في ملفات PDF، والعناصر الفردية داخل الأرشيفات المضغوطة.

مع GroupDocs.Viewer يمكنك سرد وحفظ:

- Email attachments.
- Files embedded in PDF documents.
- Email messages contained in Outlook and Lotus Notes data files.
- Individual files inside archive containers.

راجع [معالجة المرفقات]() للحصول على مثال قابل للتنفيذ.

## Output Transformation

يأتي GroupDocs.Viewer للبايثون بمجموعة من الخيارات لتحويل كل صفحة تم تحويلها:

- **Rotate pages** — change page orientation when rendering to HTML, JPG, PNG, or PDF.
- **Add a text watermark** — stamp a text watermark on every rendered page.
- **Reorder pages** — render pages in any order you prefer, including when rendering to PDF.

## Caching Results

يدعم GroupDocs.Viewer للبايثون التخزين المؤقت لتسريع عمليات التحويل المتكررة وتقليل الحمل الكلي على التطبيق.

بشكل افتراضي، يتم تخزين الذاكرة المؤقتة على القرص المحلي. كما يكشف API العارض عن واجهات التخزين المؤقت التي يمكن تنفيذها لتخزين الطرف الثالث — FTP، Amazon S3، Dropbox، Google Drive، Microsoft Azure، Redis، أو أي نظام خلفي آخر.
