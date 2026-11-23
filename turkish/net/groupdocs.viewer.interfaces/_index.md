---
title: "GroupDocs.Viewer.Interfaces"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Bu ad alanı, çıktı belgesini ve kaynaklarını örneklemek ve serbest bırakmak için arabirimler sağlar."
type: docs
weight: 60
url: /tr/net/groupdocs.viewer.interfaces/
---

Ad alanı, çıktı belgesini ve kaynaklarını oluşturmak ve serbest bırakmak için arayüzler sağlar.

## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [CreateFileStream](./createfilestream) | Çıktı dosya verilerini yazmak için kullanılan akışı örnekleyen yöntemi temsil eder. |
| [CreatePageStream](./createpagestream) | Çıktı sayfa verilerini yazmak için kullanılan akışı örnekleyen yöntemi temsil eder. |
| [CreateResourceStream](./createresourcestream) | Çıktı HTML kaynağı verilerini yazmak için kullanılan akışı örnekleyen yöntemi temsil eder. |
| [CreateResourceUrl](./createresourceurl) | HTML kaynağı için URL oluşturan yöntemi temsil eder. |
| [ReleaseFileStream](./releasefilestream) | [`CreateFileStream`](../groupdocs.viewer.interfaces/createfilestream) temsilcisiyle ilişkili yöntem tarafından örneklenen akışı serbest bırakır. |
| [ReleasePageStream](./releasepagestream) | [`CreatePageStream`](../groupdocs.viewer.interfaces/createpagestream) temsilcisiyle ilişkili yöntem tarafından örneklenen akışı serbest bırakır. |
| [ReleaseResourceStream](./releaseresourcestream) | [`CreateResourceStream`](../groupdocs.viewer.interfaces/createresourcestream) temsilcisiyle ilişkili yöntem tarafından örneklenen akışı serbest bırakır. |
## Arayüzler

| Arayüz | Açıklama |
| --- | --- |
| [IFileStreamFactory](./ifilestreamfactory) | Çıktı dosya akışını örneklemek ve serbest bırakmak için gereken yöntemleri tanımlar. |
| [IPageStreamFactory](./ipagestreamfactory) | Çıktı sayfa akışını örneklemek ve serbest bırakmak için gereken yöntemleri tanımlar. |
| [IResourceStreamFactory](./iresourcestreamfactory) | Kaynak URL'si oluşturmak, çıktı HTML kaynağı akışını örneklemek ve serbest bırakmak için gereken yöntemleri tanımlar. |

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
