---
title: "com.groupdocs.viewer.interfaces"
second_title: "GroupDocs.Viewer untuk Node.js melalui Java Referensi API"
description: "Paket ini menyediakan antarmuka untuk menginstansiasi dan melepaskan dokumen output serta sumber dayanya."
type: docs
weight: 15
url: /id/nodejs-java/com.groupdocs.viewer.interfaces/
---

Paket ini menyediakan antarmuka untuk menginstansiasi dan melepaskan dokumen output serta sumber dayanya.

Antarmuka ini digunakan untuk mengelola pembuatan dan pelepasan aliran serta URL yang terkait dengan file output, halaman, dan sumber daya HTML.

Antarmuka utama dalam paket ini adalah:

 *  [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
 *  [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
 *  [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.

Untuk detail lebih lanjut tentang cara bekerja dengan antarmuka ini dan menyesuaikan dokumen output serta penanganan sumber daya di GroupDocs.Viewer, silakan merujuk ke [GroupDocs.Viewer Documentation][].


[GroupDocs.Viewer Documentation]: https://docs.groupdocs.com/viewer/java/


## Antarmuka

| Antarmuka | Deskripsi |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | Mewakili antarmuka yang menginstansiasi aliran yang digunakan untuk menulis data file output. |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | Mewakili antarmuka yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | Mewakili antarmuka yang menginstansiasi aliran yang digunakan untuk menulis data sumber daya HTML output. |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | Mewakili antarmuka yang membuat URL untuk sumber daya HTML. |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | Menyatakan antarmuka untuk membaca aliran file. |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | Mendefinisikan metode yang diperlukan untuk menginstansiasi dan melepaskan aliran file output. |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | Mendefinisikan metode yang diperlukan untuk menginstansiasi dan melepaskan aliran halaman output. |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | Melepaskan antarmuka yang diinstansiasi oleh metode yang terkait dengan antarmuka CreateFileStream. |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | Melepaskan aliran yang diinstansiasi oleh metode yang terkait dengan antarmuka CreatePageStream. |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | Melepaskan aliran yang diinstansiasi oleh metode yang terkait dengan antarmuka CreateResourceStream. |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Mendefinisikan metode yang diperlukan untuk membuat URL sumber daya, menginstansiasi, dan melepaskan aliran sumber daya HTML output. |
