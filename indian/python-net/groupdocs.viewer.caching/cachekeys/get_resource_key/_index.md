---
title: "get_resource_key मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Resource ऑब्जेक्ट का प्रतिनिधित्व करने वाले कैश एंट्री के लिए अनन्य पहचानकर्ता लौटाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

`[`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)` ऑब्जेक्ट का प्रतिनिधित्व करने वाले कैश एंट्री के लिए अद्वितीय पहचानकर्ता लौटाता है।

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| page_number | `int` | पृष्ठ की संख्या। |
| resource | `Resource` | HTML संसाधन। |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `page_number` शून्य या उससे कम है, या यदि `resource` None है। |

### साथ में देखें
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
