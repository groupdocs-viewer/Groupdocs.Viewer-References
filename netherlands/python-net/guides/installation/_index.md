---
title: "Installatie"
linkTitle: "Installation"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Installeer GroupDocs.Viewer voor Python via .NET op Windows, Linux of macOS — vanaf PyPI of vanaf een vooraf gedownloade wheel, inclusief builds voor Intel en Apple Silicon."
type: docs
url: /nl/python-net/guides/installation/
is_root: false
weight: 10
---


Controleer vóór het installeren de [System Requirements]() voor ondersteunde Python‑versies en platform‑afhankelijkheden.

## Install Package from PyPI

De bibliotheek wordt gepubliceerd op [PyPI](https://pypi.org/project/groupdocs-viewer-net/) als **`groupdocs-viewer-net`**. `pip` selecteert automatisch het juiste platform‑specifieke wheel voor uw systeem.

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

U zou output moeten zien die lijkt op:

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

De exacte wheel‑naam hangt af van uw OS en CPU‑architectuur — zie de [wheel-suffix table]() in System Requirements voor de volledige lijst.

## Add the Package to `requirements.txt`

Voeg de afhankelijkheid toe aan het `requirements.txt`‑bestand van uw project:

```text
groupdocs-viewer-net
```

Installeer vervolgens vanuit het bestand:

```bash
pip install -r requirements.txt
```

Zet een specifieke versie vast als u reproduceerbare builds nodig heeft — bijvoorbeeld `groupdocs-viewer-net==26.9.0`.

## Install from a Pre-Downloaded Wheel

Voor luchtgesloten of gecontroleerde omgevingen downloadt u het wheel van de [GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) site of de [PyPI release page](https://pypi.org/project/groupdocs-viewer-net/#files) en installeert u het direct. Per release worden vier platform‑specifieke wheels gepubliceerd; kies degene die bij uw host past:

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux_2_27_x86_64.whl` (glibc 2.27 or newer)
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_arm64.whl` (macOS 12 or newer)
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_x86_64.whl` (macOS 12 or newer)

Sinds versie 26.9 geven de bestandsnamen het oudste systeem aan waarop elk wheel draait, zodat pip 20.3 of nieuwer een ouder wheel direct weigert in plaats van een runtime te installeren die niet kan starten. Wheels tot versie 26.5 waren getagd `manylinux1_x86_64`, `macosx_10_14_x86_64` en `macosx_11_0_arm64`.

Kopieer het gedownloade wheel naar uw projectmap en installeer het met `pip`:

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

Noem het wheel‑bestand expliciet: PowerShell breidt een `*`‑wildcard niet uit voor een native opdracht, waardoor `pip install groupdocs_viewer_net-*.whl` daar mislukt.

Verwachte output:

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
