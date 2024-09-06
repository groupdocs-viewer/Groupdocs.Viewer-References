---
title: CadOptions
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: 
type: docs
weight: 30
url: /viewer/python-net/groupdocs.viewer.options/cadoptions/
---

## CadOptions class

Contains options for rendering CAD drawings. For more information and code examples, see the

The CadOptions type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|scale_factor|Value higher than 1 enlarges output result; value between 0 and 1 reduces output result.|
|width|The width of the output result (in pixels).|
|height|The height of the output result (in pixels).|
|background_color|Image background color.|
|tiles|The drawing regions to render.|
|render_layouts|Flag if layouts from CAD document should be rendered.|
|layout_name|The name of the specific layout to render. Layout name is case-sensitive.|
|layers|The CAD drawing layers to render.|
|pc_3_file|PC3 - plotter configuration file|
## Methods
| Name | Description |
| :- | :- |
|for_rendering_by_scale_factor(scale_factor)|Initializes an instance of the [CadOptions](/viewer/python-net/groupdocs.viewer.options/cadoptions/) class for rendering by scale factor.|
|for_rendering_by_width(width)|Initializes an instance of the [CadOptions](/viewer/python-net/groupdocs.viewer.options/cadoptions/) class for rendering by width.|
|for_rendering_by_height(height)|Initializes an instance of the [CadOptions](/viewer/python-net/groupdocs.viewer.options/cadoptions/) class for rendering by height.|
|for_rendering_by_width_and_height(width, height)|Initializes an instance of the [CadOptions](/viewer/python-net/groupdocs.viewer.options/cadoptions/) class for rendering by width and height.|

### See Also

* namespace [groupdocs.viewer.options](/viewer/python-net/groupdocs.viewer.options/)
* assembly [GroupDocs.Viewer](/viewer/python-net/)

