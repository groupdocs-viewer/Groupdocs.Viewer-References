---
title: "Installazione"
linkTitle: "Installation"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Installa GroupDocs.Viewer per Python via .NET su Windows, Linux o macOS — da PyPI o da un wheel pre‑scaricato, includendo build per Intel e Apple Silicon."
type: docs
url: /it/python-net/guides/installation/
is_root: false
weight: 10
---


Prima dell'installazione, controlla i [System Requirements]() per le versioni Python supportate e le dipendenze della piattaforma.

## Install Package from PyPI

La libreria è pubblicata su [PyPI](https://pypi.org/project/groupdocs-viewer-net/) come **`groupdocs-viewer-net`**. `pip` seleziona automaticamente il wheel specifico per la piattaforma corretto per il tuo sistema.

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

Dovresti vedere un output simile a:

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

Il nome esatto del wheel dipende dal tuo OS e dall'architettura CPU — consulta la [wheel-suffix table]() in System Requirements per l'elenco completo.

## Add the Package to `requirements.txt`

Aggiungi la dipendenza al `requirements.txt` del tuo progetto:

```text
groupdocs-viewer-net
```

Quindi installa dal file:

```bash
pip install -r requirements.txt
```

Fissa a una versione specifica se hai bisogno di build riproducibili — ad esempio, `groupdocs-viewer-net==26.9.0`.

## Install from a Pre-Downloaded Wheel

Per ambienti isolati o controllati, scarica il wheel dal sito [GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) o dalla [pagina di rilascio di PyPI](https://pypi.org/project/groupdocs-viewer-net/#files) e installalo direttamente. Sono pubblicati quattro wheel specifici per piattaforma per ogni rilascio; scegli quello che corrisponde al tuo host:

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux_2_27_x86_64.whl` (glibc 2.27 or newer)
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_arm64.whl` (macOS 12 or newer)
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_x86_64.whl` (macOS 12 or newer)

A partire dalla 26.9 i nomi dei file indicano il sistema più vecchio su cui ogni wheel può essere eseguito, quindi pip 20.3 o versioni successive rifiuta in anticipo un wheel più vecchio invece di installare un runtime che non può avviarsi. I wheel fino alla 26.5 erano etichettati `manylinux1_x86_64`, `macosx_10_14_x86_64` e `macosx_11_0_arm64`.

Copia il wheel scaricato nella cartella del tuo progetto e installalo con `pip`:

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

Specifica esplicitamente il nome del file wheel: PowerShell non espande il carattere jolly `*` per un comando nativo, quindi `pip install groupdocs_viewer_net-*.whl` fallisce.

Output previsto:

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
