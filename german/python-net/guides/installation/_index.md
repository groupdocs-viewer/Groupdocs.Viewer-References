---
title: "Installation"
linkTitle: "Installation"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Installieren Sie GroupDocs.Viewer for Python über .NET unter Windows, Linux oder macOS — von PyPI oder aus einem vorab heruntergeladenen Wheel, einschließlich Intel- und Apple‑Silicon‑Builds."
type: docs
url: /de/python-net/guides/installation/
is_root: false
weight: 10
---


Überprüfen Sie vor der Installation die [System Requirements](), um unterstützte Python‑Versionen und Plattformabhängigkeiten zu sehen.

## Install Package from PyPI

Die Bibliothek wird auf [PyPI](https://pypi.org/project/groupdocs-viewer-net/) als **`groupdocs-viewer-net`** veröffentlicht. `pip` wählt automatisch das passende plattformspezifische Wheel für Ihr System aus.

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

Sie sollten eine Ausgabe ähnlich der folgenden sehen:

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

Der genaue Wheel-Name hängt von Ihrem Betriebssystem und Ihrer CPU‑Architektur ab — siehe die [wheel-suffix table]() in den System Requirements für die vollständige Liste.

## Add the Package to `requirements.txt`

Fügen Sie die Abhängigkeit zu Ihrer `requirements.txt`‑Datei des Projekts hinzu:

```text
groupdocs-viewer-net
```

Installieren Sie dann aus der Datei:

```bash
pip install -r requirements.txt
```

Fixieren Sie eine bestimmte Version, wenn Sie reproduzierbare Builds benötigen — zum Beispiel `groupdocs-viewer-net==26.9.0`.

## Install from a Pre-Downloaded Wheel

Für luftisolierte oder kontrollierte Umgebungen laden Sie das Wheel von der [GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) Seite oder der [PyPI release page](https://pypi.org/project/groupdocs-viewer-net/#files) herunter und installieren es direkt. Pro Release werden vier plattformspezifische Wheels veröffentlicht; wählen Sie dasjenige, das zu Ihrem Host passt:

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux_2_27_x86_64.whl` (glibc 2.27 or newer)
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_arm64.whl` (macOS 12 or newer)
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_x86_64.whl` (macOS 12 or newer)

Seit Version 26.9 geben die Dateinamen das älteste System an, auf dem jedes Wheel läuft, sodass pip 20.3 oder neuer ein älteres Wheel sofort ablehnt, anstatt eine Laufzeit zu installieren, die nicht starten kann. Wheels bis Version 26.5 waren mit `manylinux1_x86_64`, `macosx_10_14_x86_64` und `macosx_11_0_arm64` gekennzeichnet.

Kopieren Sie das heruntergeladene Wheel in Ihren Projektordner und installieren Sie es mit `pip`:

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

Benennen Sie die Wheel-Datei explizit: PowerShell erweitert ein `*`‑Wildcard für einen nativen Befehl nicht, sodass `pip install groupdocs_viewer_net-*.whl` dort fehlschlägt.

Erwartete Ausgabe:

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
