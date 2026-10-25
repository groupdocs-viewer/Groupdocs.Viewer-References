---
title: "com.groupdocs.viewer.interfaces"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Paket, çıktı belgesini ve kaynaklarını oluşturmak ve serbest bırakmak için arabirimler sağlar."
type: docs
weight: 17
url: /tr/java/com.groupdocs.viewer.interfaces/
---

Paket, çıktı belgesini ve kaynaklarını oluşturmak ve serbest bırakmak için arabirimler sağlar.


Bu arabirimler, çıktı dosyası, sayfalar ve HTML kaynaklarıyla ilişkili akışların ve URL'lerin oluşturulmasını ve serbest bırakılmasını yönetmek için kullanılır.

Bu paketteki ana arabirimler şunlardır:

* [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
* [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
* [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.


Bu arabirimlerle çalışma ve GroupDocs.Viewer'da çıktı belgesi ve kaynak yönetimini özelleştirme hakkında daha fazla ayrıntı için,
Lütfen [GroupDocs.Viewer Documentation](../https://docs.groupdocs.com/viewer/java/) adresine bakın.



## Arabirimler

| Arabirim | Açıklama |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | Çıktı dosyası verilerini yazmak için kullanılan bir akışı başlatan bir arabirimi temsil eder. |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | Çıktı sayfa verilerini yazmak için kullanılan bir akışı başlatan bir arabirimi temsil eder. |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | Çıktı HTML kaynağı verilerini yazmak için kullanılan bir akışı başlatan bir arabirimi temsil eder. |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | Bir HTML kaynağı için URL oluşturan bir arabirimi temsil eder. |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | Bir dosya akışını okumak için bir arabirim bildirir. |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | Çıktı dosyası akışını başlatmak ve serbest bırakmak için gerekli yöntemleri tanımlar. |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | Çıktı sayfa akışını başlatmak ve serbest bırakmak için gerekli yöntemleri tanımlar. |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | CreateFileStream arabirimiyle ilişkili yöntem tarafından başlatılan bir arabirimi serbest bırakır. |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | CreatePageStream arabirimiyle ilişkili yöntem tarafından başlatılan bir akışı serbest bırakır. |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | CreateResourceStream arabirimiyle ilişkili yöntem tarafından başlatılan bir akışı serbest bırakır. |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Bir kaynak URL'si oluşturmak, bir çıktı HTML kaynağı akışını başlatmak ve serbest bırakmak için gerekli yöntemleri tanımlar. |
