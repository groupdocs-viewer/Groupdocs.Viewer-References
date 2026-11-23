---
title: "свойство render_header_footer_placeholders"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Свойство включает отображение заполнителей в заголовке и нижнем колонтитуле слайда."
type: docs
url: /ru/python-net/groupdocs.viewer.options/presentationoptions/render_header_footer_placeholders/
is_root: false
weight: 2010
---


## render_header_footer_placeholders property

Свойство включает отображение заполнителей в заголовке и нижнем колонтитуле слайда.

По умолчанию отключено (`False`). Эта опция применяется ко всем четырём режимам рендеринга презентаций: HTML, PDF, PNG и JPEG. Она не применяется при рендеринге презентации в чистый HTML/CSS с использованием [`PresentationOptions.render_to_pure_html`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/render_to_pure_html/).

### Definition:
```python
@property
def render_header_footer_placeholders(self):
    ...
@render_header_footer_placeholders.setter
def render_header_footer_placeholders(self, value):
    ...
```

### См. также
* class [`PresentationOptions`](/viewer/python-net/groupdocs.viewer.options/presentationoptions/)
