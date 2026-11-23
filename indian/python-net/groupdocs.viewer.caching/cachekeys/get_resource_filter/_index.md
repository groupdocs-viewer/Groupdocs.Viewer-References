---
title: "get_resource_filter मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Resource ऑब्जेक्ट्स का प्रतिनिधित्व करने वाले कैश एंट्रीज़ को खोजने के लिए एक फ़िल्टर स्ट्रिंग लौटाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

`[`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)` ऑब्जेक्ट्स का प्रतिनिधित्व करने वाले कैश एंट्री को खोजने के लिए एक फ़िल्टर स्ट्रिंग लौटाता है।

```python
def get_resource_filter(cls, page_number):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| page_number | `int` | पृष्ठ की संख्या। |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `page_number` शून्य या उससे कम हो। |

### साथ में देखें
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
