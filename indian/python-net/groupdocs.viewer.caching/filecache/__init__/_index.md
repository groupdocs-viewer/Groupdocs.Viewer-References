---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक नया FileCache उदाहरण प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

एक नया FileCache उदाहरण प्रारंभ करता है।

```python
def __init__(self, cache_path):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| cache_path | `str` | दस्तावेज़ कैश जहाँ संग्रहीत होगा, उसके लिए सापेक्ष या पूर्ण पथ। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `cache_path` None है। |

## __init__ {#cache_path-cache_sub_folder}

FileCache क्लास का एक नया उदाहरण प्रारंभ करता है।

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| cache_path | `str` | दस्तावेज़ कैश जहाँ संग्रहीत होगा, उसके लिए सापेक्ष या पूर्ण पथ। |
| cache_sub_folder | `str` | `cache_path` में जोड़ने के लिए उप-फ़ोल्डर। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `cache_sub_folder` None है। |

### साथ में देखें
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
