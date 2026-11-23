---
title: "disable_font_license_verifications özelliği"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Bu özellik, geçerli XPS/OXPS belgesindeki tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/
is_root: false
weight: 2030
---


## disable_font_license_verifications property

Bu özellik, geçerli XPS/OXPS belgesindeki tüm yazı tipleri için lisans kısıtlamalarını devre dışı bırakır.

Yazı tipleriyle ilgili birçok işlem, yazı tipinin lisansı tarafından yasaklanmışsa gerçekleştirilemez. Örneğin, bazı yazı tipleri, lisans kuralları bu yazı tipinin gömülmesini engelliyorsa bir PDF belgesine yerleştirilemez. Bu seçenek, bu kuralların doğrulamasını atlamanızı sağlar.

Bu bayrağı kullanırken dikkatli olun. Ayarlandığında, bu bayrağı ayarlayan kişinin olası lisans veya yasa ihlallerinden tamamen sorumlu olduğu anlamına gelir. Bu bayrağı yalnızca telif hakkı yasasını ihlal etmediğinizden tamamen emin olduğunuzda kullanmanız şiddetle önerilir. Varsayılan değer `False`dır.

Kod örneği için, belgeleri şu adreste inceleyin: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

### Definition:
```python
@property
def disable_font_license_verifications(self):
    ...
@disable_font_license_verifications.setter
def disable_font_license_verifications(self, value):
    ...
```

### Ayrıca Bakınız
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
