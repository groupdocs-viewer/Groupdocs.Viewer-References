---
title: "from_stream मेथड"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।"
type: docs
url: /hi/python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।

```python
def from_stream(cls, stream):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| stream | `io.RawIOBase` | फ़ाइल स्ट्रीम। |

## from_stream {#stream-password}

फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।

```python
def from_stream(cls, stream, password):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| stream | `io.RawIOBase` | फ़ाइल स्ट्रीम। |
| password | `str` | फ़ाइल खोलने के लिए पासवर्ड। |

## from_stream {#stream-logger}

फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।

```python
def from_stream(cls, stream, logger):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| stream | `io.RawIOBase` | फ़ाइल स्ट्रीम। |
| logger | `ILogger` | लॉगर। |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

फ़ाइल सिग्नेचर पढ़कर फ़ाइल प्रकार का पता लगाता है।

```python
def from_stream(cls, stream, password, logger):
    ...
```

| पैरामीटर | टाइप | विवरण |
| :- | :- | :- |
| stream | `io.RawIOBase` | फ़ाइल स्ट्रीम। |
| password | `str` | फ़ाइल खोलने के लिए पासवर्ड। |
| logger | `ILogger` | लॉगर। |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### साथ में देखें
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
