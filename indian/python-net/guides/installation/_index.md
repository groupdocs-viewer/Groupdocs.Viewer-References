---
title: "स्थापना"
linkTitle: "Installation"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "Windows, Linux, या macOS पर .NET के माध्यम से GroupDocs.Viewer for Python स्थापित करें — PyPI से या पूर्व‑डाउनलोडेड व्हील से, जिसमें Intel और Apple Silicon बिल्ड्स शामिल हैं।"
type: docs
url: /hi/python-net/guides/installation/
is_root: false
weight: 10
---


इंस्टॉल करने से पहले, समर्थित Python संस्करणों और प्लेटफ़ॉर्म निर्भरताओं के लिए [System Requirements]() देखें।

## Install Package from PyPI

लाइब्रेरी [PyPI](https://pypi.org/project/groupdocs-viewer-net/) पर **`groupdocs-viewer-net`** के रूप में प्रकाशित की गई है। `pip` स्वचालित रूप से आपके सिस्टम के लिए सही प्लेटफ़ॉर्म-विशिष्ट व्हील चुनता है।

### Install the Latest Version

{{< tabs \"install-pypi\">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< /tabs >}}

आपको इस तरह का आउटपुट दिखना चाहिए:

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

सटीक व्हील नाम आपके OS और CPU आर्किटेक्चर पर निर्भर करता है — पूर्ण सूची के लिए System Requirements में [wheel-suffix table]() देखें।

## Add the Package to `requirements.txt`

अपने प्रोजेक्ट की `requirements.txt` में निर्भरता जोड़ें:

```text
groupdocs-viewer-net
```

फिर फ़ाइल से इंस्टॉल करें:

```bash
pip install -r requirements.txt
```

यदि आपको पुनरुत्पादक बिल्ड्स चाहिए तो एक विशिष्ट संस्करण को पिन करें — उदाहरण के लिए, `groupdocs-viewer-net==26.9.0`।

## Install from a Pre-Downloaded Wheel

एयर-गैप्ड या नियंत्रित वातावरणों के लिए, व्हील को [GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) साइट या [PyPI रिलीज़ पेज](https://pypi.org/project/groupdocs-viewer-net/#files) से डाउनलोड करें और सीधे इंस्टॉल करें। प्रत्येक रिलीज़ में चार प्लेटफ़ॉर्म-विशिष्ट व्हील प्रकाशित होते हैं; वह चुनें जो आपके होस्ट से मेल खाता हो:

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux_2_27_x86_64.whl` (glibc 2.27 or newer)
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_arm64.whl` (macOS 12 or newer)
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_x86_64.whl` (macOS 12 or newer)

संस्करण 26.9 से फ़ाइल नाम यह दर्शाते हैं कि प्रत्येक व्हील किस सबसे पुराने सिस्टम पर चलता है, इसलिए pip 20.3 या उससे नया पहले ही पुराने व्हील को अस्वीकार कर देता है बजाय ऐसे रनटाइम को इंस्टॉल करने के जो शुरू नहीं हो सकता। 26.5 तक के व्हील को `manylinux1_x86_64`, `macosx_10_14_x86_64` और `macosx_11_0_arm64` टैग किया गया था।

डाउनलोड किया गया व्हील अपने प्रोजेक्ट फ़ोल्डर में कॉपी करें और `pip` के साथ इंस्टॉल करें:

{{< tabs \"install-wheel\">}}
{{< tab \"Windows (64-bit)\" >}}
```ps
py -m pip install groupdocs_viewer_net-26.9.0-py3-none-win_amd64.whl
```
{{< /tab >}}
{{< tab \"Linux (glibc)\" >}}
```bash
python3 -m pip install ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
```
{{< /tab >}}
{{< tab \"macOS (Apple Silicon)\" >}}
```bash
python3 -m pip install ./groupdocs_viewer_net-26.9.0-py3-none-macosx_12_0_arm64.whl
```
{{< /tab >}}
{{< tab \"macOS (Intel)\" >}}
```bash
python3 -m pip install ./groupdocs_viewer_net-26.9.0-py3-none-macosx_12_0_x86_64.whl
```
{{< /tab >}}
{{< /tabs >}}

व्हील फ़ाइल का नाम स्पष्ट रूप से दें: PowerShell मूल कमांड के लिए `*` वाइल्डकार्ड का विस्तार नहीं करता, इसलिए `pip install groupdocs_viewer_net-*.whl` वहाँ विफल हो जाता है।

अपेक्षित आउटपुट:

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
