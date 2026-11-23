---
title: "अटैचमेंट्स सहेजें"
linkTitle: "Save attachments"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "ईमेल, Outlook फ़ाइलों, अभिलेखों और PDF से अटैचमेंट प्राप्त करें और सहेजें।"
type: docs
url: /hi/python-net/guides/how-to-extract-and-save-attachments/
is_root: false
weight: 110
---


अटैचमेंट प्राप्त करने और सहेजने के लिए, इन चरणों का पालन करें:

1. [Viewer](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/) ऑब्जेक्ट को इंस्टैंशिएट करें। वह फ़ाइल निर्दिष्ट करें जिसमें अटैचमेंट हों।
2. [get_attachments](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) मेथड को कॉल करें। यह अटैचमेंट संग्रह लौटाता है।
3. संग्रह के माध्यम से इटरेट करें। अटैचमेंट सहेजने के लिए, [save_attachment](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods) मेथड को कॉल करें।

निम्नलिखित कोड स्निपेट दिखाता है कि MSG फ़ाइल से सभी अटैचमेंट कैसे प्राप्त और सहेजे जाएँ:

नोट: प्रदान किया गया कोड स्निपेट उन सभी फ़ॉर्मेट परिवारों के लिए उपयुक्त है जो अटैचमेंट का समर्थन करते हैं: ईमेल, Outlook डेटा फ़ाइलें, अभिलेख और PDF दस्तावेज़।

{{< tabs "example1">}}
{{< tab "Python" >}}
```python
from groupdocs.viewer import Viewer

def extract_and_save_attachments():
    # अटैचमेंट के साथ दस्तावेज़ लोड करें
    with Viewer("with_attachments.msg") as viewer:
        attachments = viewer.get_attachments()

        print("\nAttachments:")
        for attachment in attachments:
            print(attachment)
            # अटैचमेंट को डिस्क पर सहेजें
            viewer.save_attachment(attachment, f"./attachments/{attachment.file_name}")

    print(f"\nAttachments retrieved successfully.")

if __name__ == "__main__":
    extract_and_save_attachments()
```
{{< /tab >}}
{{< tab "with_attachments.msg" >}}

`with_attachments.msg` इस उदाहरण में उपयोग की गई नमूना फ़ाइल है। इसे डाउनलोड करने के लिए [यहाँ](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/processing-attachments/with_attachments.msg) क्लिक करें।

{{< /tab >}}
{{< tab "extract-and-save-attachments-outputs.zip" >}}
```text
attachments/attachment-image.png (26 KB)
attachments/attachment-word.doc (220 KB)
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/processing-attachments/how-to-extract-and-save-attachments/extract_and_save_attachments/extract-and-save-attachments-outputs.zip)
{{< /tab >}}
{{< /tabs >}}
