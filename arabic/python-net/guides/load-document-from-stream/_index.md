---
title: "تحميل مستند من تدفق"
linkTitle: "Load from stream"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "تحميل المستندات مباشرةً من كائن شبيه بالملف — مقبض ملف مفتوح، BytesIO، أو أي تدفق — باستخدام GroupDocs.Viewer للبايثون عبر .NET."
type: docs
url: /ar/python-net/guides/load-document-from-stream/
is_root: false
weight: 60
---


يمكنك تحميل مستند من تدفق دون حفظه كملف على القرص. يمكنك استخدام هذه الميزة لتحميل مستند من مصادر مختلفة مثل URL، FTP، وما إلى ذلك.

لتحميل مستند من تدفق، اتبع الخطوات التالية:

1. تنفيذ طريقة للحصول على تدفق المستند.
2. استدعاء مُنشئ الفئة [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer). حدد الطريقة التي تم تنفيذها في الخطوة السابقة.

يظهر المقتطف البرمجي التالي كيفية تحميل مستند من تدفق:

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def load_document_from_stream():
    # فتح تدفق المستند
    stream = open("sample.docx", "rb")

    # عرض مستند من التدفق.
    with Viewer(stream) as viewer:
        options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
        viewer.view(options)

if __name__ == "__main__":
    load_document_from_stream()
```
{{< /tab >}}
{{< tab "sample.docx" >}}

`sample.docx` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/loading-documents/load-document-from-stream/sample.docx) لتنزيله.

{{< /tab >}}
{{< tab "load-document-from-stream-outputs.zip" >}}
```text
page_1.html (317 KB)
page_2.html (149 KB)
page_3.html (113 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/loading-documents/load-document-from-stream/load_document_from_stream/load-document-from-stream-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

انظر أيضًا إلى [Load document from URL]() للحصول على مثال عملي لتحميل مستند إلى تدفق `BytesIO` وعرضه دون كتابة أي شيء على القرص.
