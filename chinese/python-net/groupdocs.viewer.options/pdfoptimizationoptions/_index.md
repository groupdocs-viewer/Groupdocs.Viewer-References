---
title: "PdfOptimizationOptions 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示要应用于输出 PDF 文件的 PDF 优化选项."
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

表示要应用于输出 PDF 文件的 PDF 优化选项.

有关详细信息和代码示例，请参阅文档页面。

PdfOptimizationOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | 将 MaxResolution 选项的默认值初始化为 300，将 ImageQuality 选项的默认值初始化为 100。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | 该属性启用对输出 PDF 文件中图像的压缩。 |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | 该属性启用将输出 PDF 文件转换为灰度。 |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | 输出 PDF 文件中的图像质量，以百分比表示。 |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | 该属性启用针对使用网页浏览器在线查看的输出 PDF 文件的优化。 |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | 输出 PDF 文件的最大分辨率。 |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | 该属性启用对 PDF 文件中电子表格的优化。 |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | 该属性启用从输出 PDF 文件中移除注释。 |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | 该属性启用从 PDF 文件中移除表单字段。 |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | 该属性移除 PDF 文件中未使用（孤立）的对象。 |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | 该属性移除 PDF 文件中未使用（孤立）的流，这些流在页面资源字典中被引用但在页面内容中从未使用。默认情况下已禁用（`False`）；将其设置为 `True` 可减小输出 PDF 的大小。 |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | 此属性可设置输出 PDF 文件的最大分辨率。 |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | 此属性在输出 PDF 文件中对字体进行子集化。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # 启用线性化以加快网页预览速度
        view_options.pdf_optimization_options.lineriaze = True
        # 删除批注和表单字段以减小文件大小
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
