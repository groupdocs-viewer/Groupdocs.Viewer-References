---
title: "Installation"
linkTitle: "Installation"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Installera GroupDocs.Viewer for Python via .NET på Windows, Linux eller macOS — från PyPI eller från ett förhandsnedladdat wheel, inklusive Intel‑ och Apple Silicon‑byggnader."
type: docs
url: /sv/python-net/guides/installation/
is_root: false
weight: 10
---


Innan du installerar, kontrollera [Systemkrav]() för stödda Python‑versioner och plattformsberoenden.

## Install Package from PyPI

Biblioteket publiceras på [PyPI](https://pypi.org/project/groupdocs-viewer-net/) som **`groupdocs-viewer-net`**. `pip` väljer automatiskt rätt plattforms‑specifika wheel för ditt system.

### Install the Latest Version

{{< tabs "install-pypi">}}
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

Du bör se utdata liknande:

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

Det exakta wheel‑namnet beror på ditt OS och CPU‑arkitektur — se [wheel‑suffix‑tabell]() i Systemkrav för den kompletta listan.

## Add the Package to `requirements.txt`

Lägg till beroendet i ditt projekts `requirements.txt`:

```text
groupdocs-viewer-net
```

Installera sedan från filen:

```bash
pip install -r requirements.txt
```

Fäst en specifik version om du behöver reproducerbara byggen — till exempel, `groupdocs-viewer-net==26.9.0`.

## Install from a Pre-Downloaded Wheel

För luftisolerade eller kontrollerade miljöer, ladda ner wheel från [GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) webbplatsen eller [PyPI release page](https://pypi.org/project/groupdocs-viewer-net/#files) och installera den direkt. Fyra plattforms‑specifika wheels publiceras per utgivning; välj den som matchar din värd:

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux_2_27_x86_64.whl` (glibc 2.27 or newer)
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_arm64.whl` (macOS 12 or newer)
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_x86_64.whl` (macOS 12 or newer)

Sedan 26.9 anger filnamnen det äldsta systemet som varje wheel kan köras på, så pip 20.3 eller nyare avvisar en äldre direkt istället för att installera en runtime som inte kan starta. Wheels upp till 26.5 var märkta `manylinux1_x86_64`, `macosx_10_14_x86_64` och `macosx_11_0_arm64`.

Kopiera den nedladdade wheelen till din projektmapp och installera den med `pip`:

{{< tabs "install-wheel">}}
{{< tab "Windows (64-bit)" >}}
```ps
py -m pip install groupdocs_viewer_net-26.9.0-py3-none-win_amd64.whl
```
{{< /tab >}}
{{< tab "Linux (glibc)" >}}
```bash
python3 -m pip install ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
```
{{< /tab >}}
{{< tab "macOS (Apple Silicon)" >}}
```bash
python3 -m pip install ./groupdocs_viewer_net-26.9.0-py3-none-macosx_12_0_arm64.whl
```
{{< /tab >}}
{{< tab "macOS (Intel)" >}}
```bash
python3 -m pip install ./groupdocs_viewer_net-26.9.0-py3-none-macosx_12_0_x86_64.whl
```
{{< /tab >}}
{{< /tabs >}}

Ange wheel-filen explicit: PowerShell expanderar inte ett `*` wildcard för ett inbyggt kommando, så `pip install groupdocs_viewer_net-*.whl` misslyckas där.

Förväntad utdata:

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
