---
title: enable_performance_conversion_mode property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/
is_root: false
weight: 80
---

## enable_performance_conversion_mode property


Setting this flag to `true` enables a special performance-oriented  conversion mode for all formats within CAD family — in this mode the conversion speed is much faster, but the quality of the resultant documents is signifiantly worser. By default is disabled (`false`) — the quality of the resultant documents is the best possible at the expense of performance.
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
* module [`groupdocs.viewer.options`](../../)
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions)
