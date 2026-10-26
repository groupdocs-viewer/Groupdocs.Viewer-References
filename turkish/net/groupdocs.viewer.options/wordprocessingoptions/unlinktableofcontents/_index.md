---
title: "UnlinkTableOfContents"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "HTML veya PDF'ye render ederken bu seçeneği true olarak ayarlayarak içindekiler tablosundan gezinmeyi devre dışı bırakabilirsiniz. HTML renderında, göreli bağlantılı a etiketleri span etiketleriyle değiştirilir; işlevsellik kaldırılır ancak görsel görünüm korunur. PDF renderında ise içindekiler tablosu, belge bölümlerine bağlantı olmadan düz metin olarak render edilir."
type: docs
weight: 110
url: /tr/net/groupdocs.viewer.options/wordprocessingoptions/unlinktableofcontents/
---

## WordProcessingOptions.UnlinkTableOfContents property

HTML veya PDF'ye işlenirken, bu seçeneği `true` olarak ayarlayarak içindekiler tablosundan gezinmeyi devre dışı bırakabilirsiniz. HTML işlenmesi için, göreli bağlantılara sahip `a` etiketleri `span` etiketleriyle değiştirilecek, işlevsellik kaldırılacak ancak görsel görünüm korunacaktır. PDF işlenmesi için, içindekiler tablosu belge bölümlerine bağlantı olmadan düz metin olarak işlenecektir.

```csharp
public bool UnlinkTableOfContents { get; set; }
```

### Açıklamalar

Varsayılan değer `false`tır.

Ayrıntılar için, [belgelere](https://docs.groupdocs.com/viewer/net/render-word-documents/#unlink-table-of-contents) bakın.

### Ayrıca Bakınız

* class [WordProcessingOptions](../../wordprocessingoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
