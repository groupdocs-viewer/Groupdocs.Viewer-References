---
title: "com.groupdocs.viewer.interfaces"
second_title: "GroupDocs.Viewer för Java API-referens"
description: "Paketet tillhandahåller gränssnitt för att instansiera och frigöra utdokumentet och dess resurser."
type: docs
weight: 17
url: /sv/java/com.groupdocs.viewer.interfaces/
---

Paketet tillhandahåller gränssnitt för att instansiera och frigöra utdokumentet och dess resurser.


Dessa gränssnitt används för att hantera skapandet och frigörandet av strömmar och URL:er som är associerade med utdatafilen, sidorna och HTML-resurserna.

De viktigaste gränssnitten i detta paket är:

* [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
* [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
* [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.


För mer detaljer om hur man arbetar med dessa gränssnitt och anpassar hanteringen av utdata-dokumentet och resurser i GroupDocs.Viewer,
Vänligen se [GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/).



## Gränssnitt

| Gränssnitt | Beskrivning |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | Representerar ett gränssnitt som instansierar en ström som används för att skriva utdatafilens data. |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | Representerar ett gränssnitt som instansierar en ström som används för att skriva utdata för siddata. |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | Representerar ett gränssnitt som instansierar en ström som används för att skriva utdata för HTML-resursdata. |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | Representerar ett gränssnitt som skapar en URL för en HTML-resurs. |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | Deklarerar ett gränssnitt för att läsa en filström. |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | Definierar metoder som krävs för att instansiera och frigöra en utdatafilström. |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | Definierar metoderna som krävs för att instansiera och frigöra en utdata sidström. |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | Frigör ett gränssnitt som instansierades av metoden som är associerad med gränssnittet CreateFileStream. |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | Frigör en ström som instansierades av metoden som är associerad med gränssnittet CreatePageStream. |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | Frigör en ström som instansierades av metoden som är associerad med gränssnittet CreateResourceStream. |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Definierar metoderna som krävs för att skapa en resurs-URL, instansiera och frigöra en utdata HTML-resursström. |
