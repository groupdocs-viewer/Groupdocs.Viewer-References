---
title: "विशेषताओं का अवलोकन"
linkTitle: "Features overview"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "GroupDocs.Viewer for Python via .NET के साथ दस्तावेज़ों को HTML, PDF, PNG, या JPEG में रेंडर करें; टेक्स्ट निकालें; अटैचमेंट्स की सूची बनाएं; और रोटेशन, रीऑर्डर, और वॉटरमार्क लागू करें।"
type: docs
url: /hi/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Rendering Documents

GroupDocs.Viewer में *rendering* शब्द दस्तावेज़ को ऐसे फ़ाइल फ़ॉर्मेट में बदलने की प्रक्रिया को दर्शाता है जो पृष्ठ सीमाओं को बनाए रखता है। उदाहरण के लिए, जब तीन‑पृष्ठीय DOCX फ़ाइल को HTML में रेंडर किया जाता है, तो परिणाम तीन HTML फ़ाइलें होती हैं — प्रत्येक पृष्ठ के लिए एक। चलाने योग्य उदाहरणों के लिए [डेवलपर गाइड]() देखें।

![Rendering diagram](https://docs.groupdocs.com/viewer/python-net/images/getting-started/features-overview/rendering.png)

### Rendering to HTML

जब आपको आवश्यकता हो तो HTML में रेंडर करना सबसे अच्छा विकल्प है:

- Build a web-based application and display document content inside a browser.
- Allow users to interact with the rendered text — select, copy, or search it.
- View document pages separately.
- Zoom in on a document without quality loss.
- Rotate, reorder, or watermark pages.

GroupDocs.Viewer for Python दो HTML संसाधन‑प्रबंधन मोड प्रदान करता है:

- **HTML with external resources** — stores page resources (CSS, fonts, images) next to the HTML file so common resources are reused across pages. Reduces overall page size and speeds up loading.
- **HTML with embedded resources** — inlines every resource into the HTML file so each page is self-contained. Larger individual files but easier to distribute.

### Rendering to PNG or JPEG

जब आपको आवश्यकता हो तो PNG या JPEG में रेंडर करना सबसे अच्छा विकल्प है:

- Support any type of application (desktop, web, mobile, CLI).
- Restrict interaction with rendered text — for example, to prevent copying. You can still extract a text layer separately if you want to overlay selectable text on the image.
- View document pages separately.
- Rotate, reorder, or watermark pages.

दो इमेज फ़ॉर्मेट्स की त्वरित तुलना:

- **PNG** is a lossless raster format that supports full-colour images and transparency. PNG does not expose a quality setting. It is a good choice for line drawings, text, and iconic graphics at small file sizes.
- **JPEG** is a lossy compressed format whose quality can be tuned — lowering the quality removes detail and adds noise, but the file becomes smaller. JPEG is optimal for photographs and any image with a large colour range, and is a common web choice thanks to its compression ratio.

### Rendering to PDF

GroupDocs.Viewer दस्तावेज़ को एकल PDF फ़ाइल में रेंडर करता है। जब आपको आवश्यकता हो तो PDF में रेंडर करना सबसे अच्छा विकल्प है:

- Print documents.
- Send documents via email.
- Distribute all pages as a single file rather than a collection of per-page files.

## Retrieving Document Information

GroupDocs.Viewer for Python स्रोत दस्तावेज़ की मूल जानकारी — फ़ाइल प्रकार, पृष्ठ संख्या, निर्देशांक के साथ टेक्स्ट, और अधिक — बिना रेंडरिंग के प्रदान करता है। देखें [दस्तावेज़ जानकारी प्राप्त करें]().

फ़ॉर्मेट‑विशिष्ट जानकारी भी उपलब्ध है:

- **Archive** — list of folders contained in the archive.
- **CAD** — list of layers and layouts in a CAD document.
- **Email** — list of folders contained in an Outlook data file.
- **PDF** — a flag that indicates whether document printing is allowed.
- **Project Management** — project start and end dates.

### Text extraction

आप PNG या JPEG में रेंडर करते समय दस्तावेज़ टेक्स्ट निकालने का विकल्प चुन सकते हैं। टेक्स्ट शब्द‑वार निर्देशांक के साथ लौटाया जाता है, जो पृष्ठ इमेज पर चयन योग्य टेक्स्ट लेयर ओवरले करने में सहायक होता है।

## Processing Attachments

GroupDocs.Viewer में *attachments* ईमेल अटैचमेंट्स, PDFs में एम्बेडेड फ़ाइलें, और संकुचित आर्काइव्स के भीतर व्यक्तिगत आइटम शामिल करता है।

GroupDocs.Viewer के साथ आप सूची बना और सहेज सकते हैं:

- Email attachments.
- Files embedded in PDF documents.
- Email messages contained in Outlook and Lotus Notes data files.
- Individual files inside archive containers.

चलाने योग्य उदाहरण के लिए देखें [अटैचमेंट प्रोसेसिंग]().

## Output Transformation

GroupDocs.Viewer for Python प्रत्येक रेंडर किए गए पृष्ठ को बदलने के लिए विकल्पों का एक सेट प्रदान करता है:

- **Rotate pages** — change page orientation when rendering to HTML, JPG, PNG, or PDF.
- **Add a text watermark** — stamp a text watermark on every rendered page.
- **Reorder pages** — render pages in any order you prefer, including when rendering to PDF.

## Caching Results

GroupDocs.Viewer for Python कैशिंग का समर्थन करता है ताकि दोहराए गए रेंडरिंग को तेज़ किया जा सके और एप्लिकेशन पर कुल लोड कम हो।

डिफ़ॉल्ट रूप से, कैश स्थानीय डिस्क पर संग्रहीत होता है। व्यूअर API भी कैश इंटरफ़ेस प्रदान करता है जिन्हें तृतीय‑पक्ष स्टोरेज — FTP, Amazon S3, Dropbox, Google Drive, Microsoft Azure, Redis, या कोई अन्य बैकएंड — के लिए लागू किया जा सकता है।
