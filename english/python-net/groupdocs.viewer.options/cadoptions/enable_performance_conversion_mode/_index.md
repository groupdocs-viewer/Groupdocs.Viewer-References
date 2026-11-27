---
title: enable_performance_conversion_mode property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The flag that enables a special performance-oriented conversion mode for all CAD formats."
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/
is_root: false
weight: 2030
---


## enable_performance_conversion_mode property

The flag that enables a special performance-oriented conversion mode for all CAD formats.

When set to True, conversion speed is much faster but the quality of the resultant documents is significantly lower. When False (default), the highest possible quality is used at the expense of performance.

### Definition:
```python
@property
def enable_performance_conversion_mode(self):
    ...
@enable_performance_conversion_mode.setter
def enable_performance_conversion_mode(self, value):
    ...
```

### See Also
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
