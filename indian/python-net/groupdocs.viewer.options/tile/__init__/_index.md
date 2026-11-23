---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Tile class का एक उदाहरण प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

[`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) क्लास का एक उदाहरण प्रारंभ करता है।

विवरण के लिए, दस्तावेज़ देखें।

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| start_point_x | `int` | टाइल के शुरू होने वाले चित्र में सबसे निचला बायाँ बिंदु का X निर्देशांक। |
| start_point_y | `int` | टाइल के शुरू होने वाले चित्र में सबसे निचला बायाँ बिंदु का Y निर्देशांक। |
| width | `int` | पिक्सेल में टाइल की चौड़ाई। |
| height | `int` | पिक्सेल में टाइल की ऊँचाई। |

### उदाहरण

```python
from groupdocs.viewer.options import Tile

# टाइल पैरामीटर परिभाषित करें
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# ड्राइंग के एक भाग का प्रतिनिधित्व करने वाला टाइल बनाएं।
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### साथ में देखें
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
