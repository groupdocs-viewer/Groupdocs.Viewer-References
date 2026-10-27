---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "एक नया Attachment उदाहरण प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.results/attachment/__init__/
is_root: false
weight: 10
---


## __init__

एक नया [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/) उदाहरण प्रारंभ करता है।

```python
def __init__(self):
    ...
```

## __init__ {#file_name-file_path}

एक नया Attachment उदाहरण प्रारंभ करता है।

```python
def __init__(self, file_name, file_path):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| file_name | `str` | संलग्नक फ़ाइल नाम। |
| file_path | `str` | संलग्नक का सापेक्ष पथ, उदाहरण के लिए \"folder/file.docx\" या फ़ाइलनाम जब फ़ाइल आर्काइव की रूट में स्थित हो, ई‑मेल संदेश या डेटा फ़ाइल में। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `file_path` None या खाली है। |

## __init__ {#id-file_name-file_path-size}

Attachment क्लास का एक नया उदाहरण प्रारंभ करता है।

```python
def __init__(self, id, file_name, file_path, size):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| id | `str` | एकल फ़ाइल के संदर्भ में अनन्य पहचानकर्ता अटैचमेंट का। |
| file_name | `str` | संलग्नक फ़ाइल नाम। |
| file_path | `str` | संलग्नक का सापेक्ष पथ, उदाहरण के लिए `folder/file.docx` या फ़ाइलनाम जब फ़ाइल आर्काइव की रूट में स्थित हो, ई‑मेल संदेश या डेटा फ़ाइल में। |
| size | `int` | संलग्न फ़ाइल का आकार बाइट्स में। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | यदि `file_path` शून्य या खाली है। |

## __init__ {#id-file_name-file_path-file_type-size}

Attachment क्लास का एक नया उदाहरण प्रारंभ करता है।

```python
def __init__(self, id, file_name, file_path, file_type, size):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| id | `str` | एकल फ़ाइल के संदर्भ में अनन्य पहचानकर्ता अटैचमेंट का। |
| file_name | `str` | संलग्नक फ़ाइल नाम। |
| file_path | `str` | संलग्नक का सापेक्ष पथ, उदाहरण के लिए `folder/file.docx` या फ़ाइलनाम जब फ़ाइल आर्काइव की रूट में स्थित हो, ई‑मेल संदेश या डेटा फ़ाइल में। |
| file_type | `FileType` | संलग्न फ़ाइल प्रकार। |
| size | `int` | संलग्न फ़ाइल का आकार बाइट्स में। |

| उत्पन्न करता है | विवरण |
| :- | :- |
| `ValueError` | जब `file_type` शून्य है। |

### साथ में देखें
* class [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/)
