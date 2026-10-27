---
title: "टाइल क्लास"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "ड्रॉइंग क्षेत्र को दर्शाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

ड्रॉइंग क्षेत्र को दर्शाता है।

विवरण के लिए, https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles पर दस्तावेज़ देखें।

Tile प्रकार निम्नलिखित सदस्यों को उजागर करता है:

### कंस्ट्रक्टर्स
| कंस्ट्रक्टर | विवरण |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) क्लास का एक उदाहरण प्रारंभ करता है। |

### मेथड्स
| मेथड | विवरण |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | टाइल के समाप्त होने वाले चित्र में सबसे ऊँचा दायाँ बिंदु का X निर्देशांक लौटाता है। |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | टाइल के समाप्त होने वाले चित्र में सबसे ऊँचा दायाँ बिंदु का Y निर्देशांक लौटाता है। |

### प्रॉपर्टीज़
| प्रॉपर्टी | विवरण |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | पिक्सेल में टाइल की ऊँचाई। |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | टाइल के शुरू होने वाले चित्र में सबसे निचला बायाँ बिंदु का X निर्देशांक। |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | टाइल के शुरू होने वाले चित्र में सबसे निचला बायाँ बिंदु का Y निर्देशांक। |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | पिक्सेल में टाइल की चौड़ाई। |

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions, Tile

with Viewer("sample.dwg") as viewer:
    view_info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    width = view_info.pages[0].width
    height = view_info.pages[0].height

    columns, rows = 2, 2
    tile_width = width / columns
    tile_height = height / rows

    view_options = HtmlViewOptions.for_embedded_resources(
        "output/drawing_tile_{0}.html"
    )
    for i in range(columns):
        for j in range(rows):
            tile = Tile(i * tile_width, j * tile_height, tile_width, tile_height)
            view_options.cad_options.tiles.append(tile)
```

### साथ में देखें
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
