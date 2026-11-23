---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Page का नया उदाहरण आरंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

एक नया उदाहरण प्रारंभ करता है [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

एक नया [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) उदाहरण प्रारंभ करता है।

```python
def __init__(self, number, visible):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| number | `int` | पृष्ठ संख्या। |
| visible | `bool` | पृष्ठ दृश्यता संकेतक। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `number` शून्य से कम या बराबर हो। |

## __init__ {#number-name-visible}

एक नया Page उदाहरण प्रारंभ करता है।

```python
def __init__(self, number, name, visible):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| number | `int` | पृष्ठ संख्या। |
| name | `str` | वर्कशीट या पृष्ठ का नाम। |
| visible | `bool` | पृष्ठ दृश्यता संकेतक। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `number` शून्य से कम या बराबर हो। |

## __init__ {#number-visible-width-height}

एक नया [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) उदाहरण प्रारंभ करता है।

```python
def __init__(self, number, visible, width, height):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| number | `int` | पृष्ठ संख्या। |
| visible | `bool` | पृष्ठ दृश्यता संकेतक। |
| width | `int` | JPG या PNG के रूप में देखने पर पृष्ठ की चौड़ाई पिक्सेल में। |
| height | `int` | JPG या PNG के रूप में देखने पर पृष्ठ की ऊँचाई पिक्सेल में। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `height` शून्य से कम या बराबर हो। |

## __init__ {#number-name-visible-width-height}

एक नया उदाहरण प्रारंभ करता है [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| number | `int` | पृष्ठ संख्या। |
| name | `str` | वर्कशीट या पृष्ठ का नाम। |
| visible | `bool` | पृष्ठ दृश्यता संकेतक। |
| width | `int` | JPG या PNG के रूप में देखने पर पृष्ठ की चौड़ाई पिक्सेल में। |
| height | `int` | JPG या PNG के रूप में देखने पर पृष्ठ की ऊँचाई पिक्सेल में। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `height` शून्य से कम या बराबर हो। |

## __init__ {#number-visible-width-height-lines}

एक नया उदाहरण प्रारंभ करता है [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| number | `int` | पृष्ठ संख्या। |
| visible | `bool` | पृष्ठ दृश्यता संकेतक। |
| width | `int` | JPG या PNG के रूप में देखने पर पृष्ठ की चौड़ाई पिक्सेल में। |
| height | `int` | JPG या PNG के रूप में देखने पर पृष्ठ की ऊँचाई पिक्सेल में। |
| lines | `List[Line]` | JPG या PNG के रूप में टेक्स्ट निष्कर्षण सक्षम होने पर पृष्ठ में सम्मिलित पंक्तियाँ। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `lines` None है। |

## __init__ {#number-name-visible-width-height-lines}

एक नया उदाहरण प्रारंभ करता है [`Page`](/viewer/python-net/groupdocs.viewer.results/page/).

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| number | `int` | पृष्ठ संख्या। |
| name | `str` | वर्कशीट या पृष्ठ का नाम। |
| visible | `bool` | पृष्ठ दृश्यता संकेतक। |
| width | `int` | JPG या PNG के रूप में देखने पर पृष्ठ की चौड़ाई पिक्सेल में। |
| height | `int` | JPG या PNG के रूप में देखने पर पृष्ठ की ऊँचाई पिक्सेल में। |
| lines | `List[Line]` | JPG या PNG के रूप में टेक्स्ट निष्कर्षण सक्षम होने पर पृष्ठ में सम्मिलित पंक्तियाँ। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `lines` None है। |

### साथ में देखें
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
