---
title: "rotate_page मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "पृष्ठ पर घड़ी की दिशा में घुमाव लागू करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

पृष्ठ पर घड़ी की दिशा में घुमाव लागू करता है।

विवरण के लिए, https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/ पर दस्तावेज़ देखें।

```python
def rotate_page(self, page_number, rotation):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| page_number | `int` | पृष्ठ संख्या, 0 से सख्ती से अधिक होनी चाहिए। |
| rotation | `Rotation` | घुमाव मान। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि पृष्ठ संख्या `page_number` के लिए घुमाव पहले ही जोड़ दिया गया था। |

### साथ में देखें
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
