---
title: "Обзор возможностей"
linkTitle: "Features overview"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Отображайте документы в HTML, PDF, PNG или JPEG; извлекайте текст; перечисляйте вложения; а также применяйте вращения, переупорядочивание и водяные знаки с помощью GroupDocs.Viewer для Python через .NET."
type: docs
url: /ru/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Rendering Documents

Термин *rendering* в GroupDocs.Viewer описывает процесс преобразования документа в файловый формат, сохраняющий границы страниц. Например, когда трехстраничный DOCX файл рендерится в HTML, результатом являются три HTML‑файла — по одному на страницу. Смотрите [Developer Guide]() для исполняемых примеров.

![Rendering diagram](https://docs.groupdocs.com/viewer/python-net/images/getting-started/features-overview/rendering.png)

### Rendering to HTML

Рендеринг в HTML — лучший выбор, когда вам нужно:

- Build a web-based application and display document content inside a browser.
- Allow users to interact with the rendered text — select, copy, or search it.
- View document pages separately.
- Zoom in on a document without quality loss.
- Rotate, reorder, or watermark pages.

GroupDocs.Viewer для Python предлагает два режима управления ресурсами HTML:

- **HTML with external resources** — stores page resources (CSS, fonts, images) next to the HTML file so common resources are reused across pages. Reduces overall page size and speeds up loading.
- **HTML with embedded resources** — inlines every resource into the HTML file so each page is self-contained. Larger individual files but easier to distribute.

### Rendering to PNG or JPEG

Рендеринг в PNG или JPEG — лучший выбор, когда вам нужно:

- Support any type of application (desktop, web, mobile, CLI).
- Restrict interaction with rendered text — for example, to prevent copying. You can still extract a text layer separately if you want to overlay selectable text on the image.
- View document pages separately.
- Rotate, reorder, or watermark pages.

Краткое сравнение двух форматов изображений:

- **PNG** is a lossless raster format that supports full-colour images and transparency. PNG does not expose a quality setting. It is a good choice for line drawings, text, and iconic graphics at small file sizes.
- **JPEG** is a lossy compressed format whose quality can be tuned — lowering the quality removes detail and adds noise, but the file becomes smaller. JPEG is optimal for photographs and any image with a large colour range, and is a common web choice thanks to its compression ratio.

### Rendering to PDF

GroupDocs.Viewer преобразует документ в один PDF‑файл. Рендеринг в PDF — лучший выбор, когда вам нужно:

- Print documents.
- Send documents via email.
- Distribute all pages as a single file rather than a collection of per-page files.

## Retrieving Document Information

GroupDocs.Viewer для Python предоставляет базовую информацию о исходном документе — тип файла, количество страниц, текст с координатами и многое другое — без рендеринга. Смотрите [Get Document Info]().

Информация, специфичная для формата, также доступна:

- **Archive** — list of folders contained in the archive.
- **CAD** — list of layers and layouts in a CAD document.
- **Email** — list of folders contained in an Outlook data file.
- **PDF** — a flag that indicates whether document printing is allowed.
- **Project Management** — project start and end dates.

### Text extraction

Вы можете выбрать извлечение текста документа при рендеринге в PNG или JPEG. Текст возвращается вместе с координатами каждого слова, что полезно при наложении выбираемого текстового слоя на изображение страницы.

## Processing Attachments

В GroupDocs.Viewer *attachments* охватывает вложения электронной почты, файлы, встроенные в PDF, и отдельные элементы внутри сжатых архивов.

С помощью GroupDocs.Viewer вы можете перечислять и сохранять:

- Email attachments.
- Files embedded in PDF documents.
- Email messages contained in Outlook and Lotus Notes data files.
- Individual files inside archive containers.

Смотрите [Processing Attachments]() для исполняемого примера.

## Output Transformation

GroupDocs.Viewer для Python поставляется с набором опций для преобразования каждой отрендеренной страницы:

- **Rotate pages** — change page orientation when rendering to HTML, JPG, PNG, or PDF.
- **Add a text watermark** — stamp a text watermark on every rendered page.
- **Reorder pages** — render pages in any order you prefer, including when rendering to PDF.

## Caching Results

GroupDocs.Viewer для Python поддерживает кэширование для ускорения повторных рендерингов и снижения общей нагрузки на приложение.

По умолчанию кэш хранится на локальном диске. API просмотрщика также предоставляет интерфейсы кэша, которые можно реализовать для сторонних хранилищ — FTP, Amazon S3, Dropbox, Google Drive, Microsoft Azure, Redis или любого другого бэкенда.
