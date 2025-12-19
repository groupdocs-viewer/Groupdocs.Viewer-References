---
title: for_rendering_by_scale_factor method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 30
---

## for_rendering_by_scale_factor {#float}

Initializes an instance of the [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions) class for rendering by scale factor.


### Returns 


New instance of the [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions) class for rendering by scale factor.


```python
def for_rendering_by_scale_factor(self, scale_factor):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| scale_factor | float | Value higher than 1 enlarges output result; value between 0 and 1 reduces output result. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `scale_factor` is less or equal to zero. |





### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions)
