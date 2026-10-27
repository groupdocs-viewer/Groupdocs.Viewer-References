---
title: "com.groupdocs.viewer.interfaces"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Пакет предоставляет интерфейсы для создания и освобождения выходного документа и его ресурсов."
type: docs
weight: 15
url: /ru/nodejs-java/com.groupdocs.viewer.interfaces/
---

Пакет предоставляет интерфейсы для создания и освобождения выходного документа и его ресурсов.

Эти интерфейсы используются для управления созданием и освобождением потоков и URL, связанных с выходным файлом, страницами и HTML-ресурсами.

Основные интерфейсы в этом пакете:

 *  [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
 *  [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
 *  [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.

Для получения более подробной информации о работе с этими интерфейсами и настройке вывода документа и обработки ресурсов в GroupDocs.Viewer, пожалуйста, обратитесь к [GroupDocs.Viewer Documentation][].


[GroupDocs.Viewer Documentation]: https://docs.groupdocs.com/viewer/java/


## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | Представляет интерфейс, который создает поток, используемый для записи данных выходного файла. |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | Представляет интерфейс, который создает поток, используемый для записи данных выходной страницы. |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | Представляет интерфейс, который создает поток, используемый для записи данных выходного HTML‑ресурса. |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | Представляет интерфейс, который создает URL для HTML‑ресурса. |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | Объявляет интерфейс для чтения файлового потока. |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | Определяет методы, необходимые для создания и освобождения выходного файлового потока. |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | Определяет методы, необходимые для создания и освобождения выходного потока страницы. |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | Освобождает интерфейс, который был создан методом, связанным с интерфейсом CreateFileStream. |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | Освобождает поток, который был создан методом, связанным с интерфейсом CreatePageStream. |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | Освобождает поток, который был создан методом, связанным с интерфейсом CreateResourceStream. |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Определяет методы, необходимые для создания URL ресурса, создания и освобождения выходного потока HTML‑ресурса. |
