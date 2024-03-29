---
title: FixedLayout
second_title: .NET API Başvurusu için GroupDocs.Viewer
description: PDF sabit bir biçimdir bu nedenle tüm öğelerin sayfada belirli bir yeri vardır. Çıktı HTMLsinin kaynak PDF ile aynı görünmesini sağlamak için belgeler varsayılan olarak sabit bir düzenle HTMLye işlenir. ile oluştururken sabit düzen çıktı HTMLsinin boyutu sabittir böylece öğeler pencere boyutundan bağımsız olarak aynı yerde kalır. Değişken mizanpajlı HTMLye dönüştürmek için bu özelliği şu şekilde ayarlayınYANLIŞ .
type: docs
weight: 50
url: /tr/net/groupdocs.viewer.options/pdfoptions/fixedlayout/
---
## PdfOptions.FixedLayout property

PDF sabit bir biçimdir, bu nedenle tüm öğelerin sayfada belirli bir yeri vardır. Çıktı HTML'sinin kaynak PDF ile aynı görünmesini sağlamak için belgeler varsayılan olarak sabit bir düzenle HTML'ye işlenir. ile oluştururken sabit düzen çıktı HTML'sinin boyutu sabittir, böylece öğeler pencere boyutundan bağımsız olarak aynı yerde kalır. Değişken mizanpajlı HTML'ye dönüştürmek için bu özelliği şu şekilde ayarlayın:`YANLIŞ` .

```csharp
public bool FixedLayout { get; set; }
```

### Notlar

Varsayılan değer:`doğru` .

Bu seçenek, HTML'ye dönüştürülürken desteklenir.

Değişken mizanpaja dönüştürülürken görüntüler atlanır. Metin içeriğine sahip PDF belgelerini işlerken değişken mizanpaj kullanın.

### Örnekler

Bu örnek, PDF belgesinin akıcı mizanpajla HTML'ye nasıl dönüştürüleceğini gösterir.

```csharp
using GroupDocs.Viewer;
using GroupDocs.Viewer.Options;
//..

using (var viewer = new Viewer("resume.pdf"))
{
   var viewOptions = HtmlViewOptions.ForEmbeddedResources("page_{0}.html");
   viewOptions.FixedLayout = false;
   viewer.View(viewOptions);
}        
```

### Ayrıca bakınız

* class [PdfOptions](../../pdfoptions)
* ad alanı [GroupDocs.Viewer.Options](../../pdfoptions)
* toplantı [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
