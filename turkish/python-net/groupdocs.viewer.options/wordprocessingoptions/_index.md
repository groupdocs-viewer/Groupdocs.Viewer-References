---
title: "WordProcessingOptions sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Word belgelerinin oluşturulması için seçenekleri içerir."
type: docs
url: /tr/python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

Word belgelerinin oluşturulması için seçenekleri içerir.

Ayrıntılar için https://docs.groupdocs.com/viewer/net/render-word-documents/ adresindeki belgeleri inceleyin.

WordProcessingOptions türü aşağıdaki üyeleri ortaya çıkarır:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | Kelime işleme belgelerini render etmek için seçenekleri başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | Bu seçeneklerin tam bir derin kopyasını oluşturur ve döndürür. |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | Belirtilen [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/) örneğinin bu örnek ile eşit olup olmadığını belirler. |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | Bir sayfanın alt kenar boşluğu. |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | Bu seçenek, Arapça, İbranice, Hint Latin temelli veya Kiril temelli betikler render edilirken kerning ve diğer OpenType özelliklerini etkinleştirir. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | Oluşturulan görüntüler için inç başına nokta cinsinden yatay çözünürlük. Bu seçenek yalnızca WordProcessing belgelerini PNG veya JPEG formatlarına render ederken kullanılır. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | Bir sayfanın sol kenar boşluğu. |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | Yüklenen WordProcessing belgesi için sayfa numaralandırma konumu; sayfa numaralandırmayı zorla uygulayabilir; varsayılan olarak `WordsPageNumberLocation.not_apply` olup belge değişmeden kalır. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | Çıktı sayfasının boyutu. |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | Bu özellik, izlenen değişikliklerin (revizyonların) render edilmesini etkinleştirir. |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | Bir sayfanın sağ kenar boşluğu. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | Bir sayfanın puan cinsinden üst kenar boşluğu. |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | Bu seçenek, HTML veya PDF render edilmesi için True olarak ayarlandığında içindekiler tablosundan gezinmeyi devre dışı bırakır. |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | Bu özellik, WordProcessing belgesini HTML, PDF, PNG veya JPEG formatlarına kaydetmeden önce belirli tipteki alanların güncellenip güncellenmeyeceğini belirler. Varsayılan değer True olup, alanların güncellendiği anlamına gelir. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | Oluşturulan görüntüler için inç başına nokta cinsinden dikey çözünürlük; yalnızca WordProcessing belgelerini PNG veya JPEG formatlarına render ederken kullanılır. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
