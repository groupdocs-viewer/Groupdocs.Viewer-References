---
title: "WordProcessingOptions 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "包含用于渲染 Word 文档的选项。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

包含用于渲染 Word 文档的选项。

有关详细信息，请参阅位于 https://docs.groupdocs.com/viewer/net/render-word-documents/ 的文档。

WordProcessingOptions 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | 初始化用于渲染文字处理文档的选项。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | 创建并返回这些选项的完整深拷贝。 |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | 确定指定的 [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/) 实例是否等于此实例。 |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### 属性
| 属性 | 描述 |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | 页面的底部边距。 |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | 此选项在渲染阿拉伯语、希伯来语、印度拉丁系或西里尔系脚本时启用字距调整和其他 OpenType 功能。 |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | 生成图像的水平分辨率（每英寸点数）。此选项仅在将 WordProcessing 文档渲染为 PNG 或 JPEG 格式时使用。 |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | 页面的左侧边距。 |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | 已加载的 WordProcessing 文档的页码位置，可强制应用页码；默认情况下为 `WordsPageNumberLocation.not_apply`，保持文档不变。 |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | 输出页面的尺寸。 |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | 此属性启用已跟踪更改（修订）的渲染。 |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | 页面的右侧边距。 |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | 页面的顶部边距（以点为单位）。 |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | 当此选项在 HTML 或 PDF 渲染时设置为 True 时，将禁用目录的导航功能。 |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | 此属性决定在将 WordProcessing 文档保存为 HTML、PDF、PNG 或 JPEG 格式之前，是否更新某些类型的字段。默认值为 True，表示会更新字段。 |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | 生成图像的垂直分辨率（每英寸点数），仅在将 WordProcessing 文档渲染为 PNG 或 JPEG 格式时使用。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
