---
title: GroupDocs.Viewer.Interfaces
second_title: GroupDocs.Viewer för .NET API-referens
description: Namnutrymmet tillhandahåller gränssnitt för att instansiera och frigöra utdatadokument och dess resurser.
type: docs
weight: 50
url: /sv/net/groupdocs.viewer.interfaces/
---
Namnutrymmet tillhandahåller gränssnitt för att instansiera och frigöra utdatadokument och dess resurser.

## Klasser

| Klass | Beskrivning |
| --- | --- |
| [CreateFileStream](./createfilestream) | Representerar metoden som instansierar ström som används för att skriva utdatafilsdata. |
| [CreatePageStream](./createpagestream) | Representerar metoden som instansierar ström som används för att skriva utdatasida. |
| [CreateResourceStream](./createresourcestream) | Representerar metoden som instansierar ström som används för att skriva ut HTML-resursdata. |
| [CreateResourceUrl](./createresourceurl) | Representerar metoden som skapar URL för HTML-resurs. |
| [ReleaseFileStream](./releasefilestream) | Frigör ström som instansierades av metoden som är associerad med[`CreateFileStream`](../groupdocs.viewer.interfaces/createfilestream) delegat. |
| [ReleasePageStream](./releasepagestream) | Frigör ström som instansierades av metoden som är associerad med[`CreatePageStream`](../groupdocs.viewer.interfaces/createpagestream) delegat. |
| [ReleaseResourceStream](./releaseresourcestream) | Frigör ström som instansierades av metoden som är associerad med[`CreateResourceStream`](../groupdocs.viewer.interfaces/createresourcestream) delegat. |
## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [IFileStreamFactory](./ifilestreamfactory) | Definierar metoderna som krävs för att instansiera och släppa utdatafilström. |
| [IPageStreamFactory](./ipagestreamfactory) | Definierar metoderna som krävs för att instansiera och släppa utgående sidström. |
| [IResourceStreamFactory](./iresourcestreamfactory) | Definierar metoderna som krävs för att skapa resurs-URL, instansiera och släppa ut HTML-resursström. |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->