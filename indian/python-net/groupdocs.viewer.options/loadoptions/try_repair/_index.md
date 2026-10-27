---
title: "try_repair गुण"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "यह गुण GroupDocs.Viewer को PDF दस्तावेज़ों में संरचनात्मक भ्रष्टाचार की मरम्मत का प्रयास करने में सक्षम बनाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

यह प्रॉपर्टी GroupDocs.Viewer को PDF दस्तावेज़ों में संरचनात्मक भ्रष्टाचार की मरम्मत का प्रयास करने में सक्षम बनाती है। डिफ़ॉल्ट रूप से False है।

यह सुविधा PDF दस्तावेज़ में निम्नलिखित समस्याओं को संबोधित करती है:

- Broken references within the document (incorrect object offsets in the Cross-reference list).
- Missing critical elements like root object, page object, or page content.
- Circular references (Form X-object referencing itself).

### Definition:
```python
@property
def try_repair(self):
    ...
@try_repair.setter
def try_repair(self, value):
    ...
```

### साथ में देखें
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
