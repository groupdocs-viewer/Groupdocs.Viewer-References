---
title: "Özellikler Genel Bakışı"
linkTitle: "Features overview"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "GroupDocs.Viewer for Python via .NET ile belgeleri HTML, PDF, PNG veya JPEG formatına dönüştürün; metin çıkarın; ekleri listeleyin; ve döndürme, yeniden sıralama ve filigran uygulayın."
type: docs
url: /tr/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Rendering Documents

GroupDocs.Viewer'da *rendering* terimi, bir belgeyi sayfa sınırlarını koruyan bir dosya formatına dönüştürme sürecini tanımlar. Örneğin, üç sayfalı bir DOCX dosyası HTML'ye render edildiğinde, sonuç üç HTML dosyası olur — sayfa başına bir. Çalıştırılabilir örnekler için [Developer Guide]() bölümüne bakın.

![Rendering diagram](https://docs.groupdocs.com/viewer/python-net/images/getting-started/features-overview/rendering.png)

### Rendering to HTML

HTML'ye render etmek, şunlara ihtiyacınız olduğunda en iyi seçimdir:

- Build a web-based application and display document content inside a browser.
- Allow users to interact with the rendered text — select, copy, or search it.
- View document pages separately.
- Zoom in on a document without quality loss.
- Rotate, reorder, or watermark pages.

GroupDocs.Viewer for Python iki HTML kaynak yönetimi modu sunar:

- **HTML with external resources** — stores page resources (CSS, fonts, images) next to the HTML file so common resources are reused across pages. Reduces overall page size and speeds up loading.
- **HTML with embedded resources** — inlines every resource into the HTML file so each page is self-contained. Larger individual files but easier to distribute.

### Rendering to PNG or JPEG

PNG veya JPEG'e render etmek, şunlara ihtiyacınız olduğunda en iyi seçimdir:

- Support any type of application (desktop, web, mobile, CLI).
- Restrict interaction with rendered text — for example, to prevent copying. You can still extract a text layer separately if you want to overlay selectable text on the image.
- View document pages separately.
- Rotate, reorder, or watermark pages.

İki görüntü formatının hızlı karşılaştırması:

- **PNG** is a lossless raster format that supports full-colour images and transparency. PNG does not expose a quality setting. It is a good choice for line drawings, text, and iconic graphics at small file sizes.
- **JPEG** is a lossy compressed format whose quality can be tuned — lowering the quality removes detail and adds noise, but the file becomes smaller. JPEG is optimal for photographs and any image with a large colour range, and is a common web choice thanks to its compression ratio.

### Rendering to PDF

GroupDocs.Viewer bir belgeyi tek bir PDF dosyasına render eder. PDF'ye render etmek, şunlara ihtiyacınız olduğunda en iyi seçimdir:

- Print documents.
- Send documents via email.
- Distribute all pages as a single file rather than a collection of per-page files.

## Retrieving Document Information

GroupDocs.Viewer for Python, bir kaynak belge hakkında temel bilgileri — dosya türü, sayfa sayısı, koordinatlarla metin ve daha fazlasını — render etmeden sunar. [Get Document Info]() bölümüne bakın.

Biçime özgü bilgiler de mevcuttur:

- **Archive** — list of folders contained in the archive.
- **CAD** — list of layers and layouts in a CAD document.
- **Email** — list of folders contained in an Outlook data file.
- **PDF** — a flag that indicates whether document printing is allowed.
- **Project Management** — project start and end dates.

### Text extraction

PNG veya JPEG'e render ederken belge metnini çıkarmayı seçebilirsiniz. Metin, kelime bazında koordinatlarla birlikte döndürülür; bu, sayfa görüntüsü üzerine seçilebilir bir metin katmanı yerleştirirken faydalıdır.

## Processing Attachments

GroupDocs.Viewer'da *attachments* e-posta eklerini, PDF'lere gömülü dosyaları ve sıkıştırılmış arşivlerdeki bireysel öğeleri kapsar.

GroupDocs.Viewer ile şunları listeleyebilir ve kaydedebilirsiniz:

- Email attachments.
- Files embedded in PDF documents.
- Email messages contained in Outlook and Lotus Notes data files.
- Individual files inside archive containers.

Çalıştırılabilir bir örnek için [Processing Attachments]() bölümüne bakın.

## Output Transformation

GroupDocs.Viewer for Python, her render edilen sayfayı dönüştürmek için bir dizi seçenek sunar:

- **Rotate pages** — change page orientation when rendering to HTML, JPG, PNG, or PDF.
- **Add a text watermark** — stamp a text watermark on every rendered page.
- **Reorder pages** — render pages in any order you prefer, including when rendering to PDF.

## Caching Results

GroupDocs.Viewer for Python, tekrar eden render işlemlerini hızlandırmak ve uygulamanın genel yükünü azaltmak için önbellekleme destekler.

Varsayılan olarak, önbellek yerel diskte saklanır. Görüntüleyici API'si ayrıca üçüncü taraf depolama için uygulanabilecek önbellek arayüzleri sunar — FTP, Amazon S3, Dropbox, Google Drive, Microsoft Azure, Redis veya başka bir arka uç.
