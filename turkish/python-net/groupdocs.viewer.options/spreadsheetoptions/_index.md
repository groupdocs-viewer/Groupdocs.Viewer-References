---
title: "SpreadsheetOptions sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Elektronik tabloları renderlemek için seçenekler."
type: docs
url: /tr/python-net/groupdocs.viewer.options/spreadsheetoptions/
is_root: false
weight: 280
---


## SpreadsheetOptions class

Elektronik tabloları renderlemek için seçenekler.

Ayrıntılar için Render spreadsheet files konusunun alt başlıklarına bakın.

SpreadsheetOptions türü aşağıdaki üyeleri ortaya çıkarır:

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [for_one_page_per_sheet](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/) | Tam bir sayfada tüm sayfayı render etmek için bir [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) örneği başlatır. |
| [for_rendering_by_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/) | Sayfa sonlarına göre çalışma sayfalarını sayfalara bölmek için yapılandırılmış bir [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) örneği başlatır. |
| [for_rendering_print_area](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/) | Yalnızca yazdırma alanlarını render etmek için [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) sınıfının bir örneğini başlatır. |
| [for_rendering_print_area_and_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/) | Yazdırma alanlarını ve sayfa sonlarını render etmek için [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) sınıfının bir örneğini başlatır. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page) | Bir sayfayı sayfalara render etmek için bir SpreadsheetOptions örneği başlatır. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page-count_columns_per_page) | Bir sayfayı sayfalara render etmek için bir SpreadsheetOptions örneği başlatır. |
| [for_split_sheet_into_pages_int32](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages_int32/) |  |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/bottom_margin/) | PDF'ye dönüştürürken bir sayfanın alt kenar boşluğu. |
| [count_columns_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_columns_per_page/) | Çalışma sayfasını sayfalara bölerken her sayfada dahil edilecek sütun sayısı. |
| [count_rows_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_rows_per_page/) | Çalışma sayfasını sayfalara bölerken her sayfada dahil edilecek satır sayısı. |
| [detect_separator](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/detect_separator/) | Bu özellik, CSV/TSV dosyaları için bir ayırıcı tespit etmeyi etkinleştirir. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/) | Oluşturulan görüntüler için inç başına nokta cinsinden yatay çözünürlük. Bu seçenek yalnızca elektronik tabloları PNG veya JPEG formatlarına render ederken kullanılır. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/left_margin/) | PDF'ye dönüştürürken bir sayfanın sol kenar boşluğu. |
| [render_grid_lines](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_grid_lines/) | Bu özellik, ızgara çizgilerinin render edilmesini etkinleştirir. |
| [render_headings](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_headings/) | Bu özellik, başlıkların render edilmesini etkinleştirir. |
| [render_hidden_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_columns/) | Bu özellik, gizli sütunların render edilmesini etkinleştirir. |
| [render_hidden_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_rows/) | Bu özellik gizli satırların işlenmesini etkinleştirir. |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/right_margin/) | PDF'ye dönüştürürken bir sayfanın sağ kenar boşluğu. |
| [skip_empty_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_columns/) | Bu özellik boş sütunların işlenmesini devre dışı bırakır. |
| [skip_empty_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_rows/) | Bu özellik boş satırların işlenmesini devre dışı bırakır. |
| [text_overflow_mode](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/text_overflow_mode/) | Elektronik tablo belgelerinin HTML'ye işlenmesi için metin taşması modu. Varsayılan değer `TextOverflowMode.OverlayIfNextIsEmpty` olup, varsayılan MS Excel davranışını taklit eder. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/top_margin/) | PDF'ye dönüştürürken bir sayfanın üst kenar boşluğu. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/) | Oluşturulan görüntüler için inç başına nokta cinsinden dikey çözünürlük. Bu seçenek yalnızca elektronik tablolar PNG veya JPEG formatına işlenirken kullanılır. |

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Elektronik tabloda ızgara çizgilerinin işlenmesini etkinleştir.
    view_options.spreadsheet_options.render_grid_lines = True
    viewer.view(view_options)
```

### Ayrıca Bakınız
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
