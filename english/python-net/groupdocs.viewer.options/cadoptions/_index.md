---
title: CadOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---

## CadOptions class

Contains options for rendering CAD drawings. For more information and code examples, see the [Render CAD drawings and models as HTML, PDF, and image files](https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) and [Specify rendering options for CAD files](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/).



The CadOptions type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor) | Value higher than 1 enlarges output result; value between 0 and 1 reduces output result. |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width) | The width of the output result (in pixels). |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height) | The height of the output result (in pixels). |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color) | Image background color. |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles) | The drawing regions to render. |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts) | Flag if layouts from CAD document should be rendered. |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name) | The name of the specific layout to render. Layout name is case-sensitive. |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers) | The CAD drawing layers to render. |
| [pc_3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc_3_file) | PC3 - plotter configuration file |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode) | Setting this flag to `true` enables a special performance-oriented  conversion mode for all formats within CAD family — in this mode the conversion speed is much faster, but the quality of the resultant documents is signifiantly worser. By default is disabled (`false`) — the quality of the resultant documents is the best possible at the expense of performance. |


### Methods
| Method | Description |
| :- | :- |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#float) | Initializes an instance of the [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions) class for rendering by scale factor. |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#int) | Initializes an instance of the [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions) class for rendering by width. |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#int) | Initializes an instance of the [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions) class for rendering by height. |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#int-int) | Initializes an instance of the [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions) class for rendering by width and height. |



### See Also
* module [`groupdocs.viewer.options`](..)
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions)
