---
title: "Ikhtisar Fitur"
linkTitle: "Features overview"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Render dokumen ke HTML, PDF, PNG, atau JPEG; ekstrak teks; daftar lampiran; dan terapkan rotasi, penataan ulang, serta watermark dengan GroupDocs.Viewer untuk Python via .NET."
type: docs
url: /id/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Rendering Documents

Istilah *rendering* dalam GroupDocs.Viewer menggambarkan proses mengonversi dokumen ke format file yang mempertahankan batas halaman. Misalnya, ketika file DOCX tiga halaman dirender ke HTML, hasilnya tiga file HTML — satu per halaman. Lihat [Developer Guide]() untuk contoh yang dapat dijalankan.

![Rendering diagram](https://docs.groupdocs.com/viewer/python-net/images/getting-started/features-overview/rendering.png)

### Rendering to HTML

Rendering ke HTML adalah pilihan terbaik ketika Anda perlu:

- Build a web-based application and display document content inside a browser.
- Allow users to interact with the rendered text — select, copy, or search it.
- View document pages separately.
- Zoom in on a document without quality loss.
- Rotate, reorder, or watermark pages.

GroupDocs.Viewer untuk Python menawarkan dua mode manajemen sumber daya HTML:

- **HTML with external resources** — stores page resources (CSS, fonts, images) next to the HTML file so common resources are reused across pages. Reduces overall page size and speeds up loading.
- **HTML with embedded resources** — inlines every resource into the HTML file so each page is self-contained. Larger individual files but easier to distribute.

### Rendering to PNG or JPEG

Rendering ke PNG atau JPEG adalah pilihan terbaik ketika Anda perlu:

- Support any type of application (desktop, web, mobile, CLI).
- Restrict interaction with rendered text — for example, to prevent copying. You can still extract a text layer separately if you want to overlay selectable text on the image.
- View document pages separately.
- Rotate, reorder, or watermark pages.

Perbandingan cepat dari dua format gambar:

- **PNG** is a lossless raster format that supports full-colour images and transparency. PNG does not expose a quality setting. It is a good choice for line drawings, text, and iconic graphics at small file sizes.
- **JPEG** is a lossy compressed format whose quality can be tuned — lowering the quality removes detail and adds noise, but the file becomes smaller. JPEG is optimal for photographs and any image with a large colour range, and is a common web choice thanks to its compression ratio.

### Rendering to PDF

GroupDocs.Viewer merender dokumen menjadi satu file PDF. Rendering ke PDF adalah pilihan terbaik ketika Anda perlu:

- Print documents.
- Send documents via email.
- Distribute all pages as a single file rather than a collection of per-page files.

## Retrieving Document Information

GroupDocs.Viewer untuk Python menampilkan informasi dasar tentang dokumen sumber — tipe file, jumlah halaman, teks dengan koordinat, dan lainnya — tanpa rendering. Lihat [Get Document Info]().

Informasi spesifik format juga tersedia:

- **Archive** — list of folders contained in the archive.
- **CAD** — list of layers and layouts in a CAD document.
- **Email** — list of folders contained in an Outlook data file.
- **PDF** — a flag that indicates whether document printing is allowed.
- **Project Management** — project start and end dates.

### Text extraction

Anda dapat memilih untuk mengekstrak teks dokumen saat rendering ke PNG atau JPEG. Teks dikembalikan bersama koordinat per kata, yang berguna saat menambahkan lapisan teks yang dapat dipilih di atas gambar halaman.

## Processing Attachments

Dalam GroupDocs.Viewer, *attachments* mencakup lampiran email, file yang disematkan dalam PDF, dan item individual di dalam arsip terkompresi.

Dengan GroupDocs.Viewer Anda dapat mendaftar dan menyimpan:

- Email attachments.
- Files embedded in PDF documents.
- Email messages contained in Outlook and Lotus Notes data files.
- Individual files inside archive containers.

Lihat [Processing Attachments]() untuk contoh yang dapat dijalankan.

## Output Transformation

GroupDocs.Viewer untuk Python menyediakan serangkaian opsi untuk mengubah setiap halaman yang dirender:

- **Rotate pages** — change page orientation when rendering to HTML, JPG, PNG, or PDF.
- **Add a text watermark** — stamp a text watermark on every rendered page.
- **Reorder pages** — render pages in any order you prefer, including when rendering to PDF.

## Caching Results

GroupDocs.Viewer untuk Python mendukung caching untuk mempercepat rendering berulang dan mengurangi beban keseluruhan pada aplikasi.

Secara default, cache disimpan di disk lokal. API viewer juga menyediakan antarmuka cache yang dapat diimplementasikan untuk penyimpanan pihak ketiga — FTP, Amazon S3, Dropbox, Google Drive, Microsoft Azure, Redis, atau backend lainnya.
