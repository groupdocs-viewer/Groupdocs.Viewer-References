---
title: "Instalación"
linkTitle: "Installation"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Instale GroupDocs.Viewer para Python a través de .NET en Windows, Linux o macOS — desde PyPI o desde una rueda predescargada, incluidas versiones para Intel y Apple Silicon."
type: docs
url: /es/python-net/guides/installation/
is_root: false
weight: 10
---


Antes de instalar, consulte los [Requisitos del sistema]() para las versiones de Python compatibles y las dependencias de la plataforma.

## Install Package from PyPI

La biblioteca se publica en [PyPI](https://pypi.org/project/groupdocs-viewer-net/) como **`groupdocs-viewer-net`**. `pip` selecciona automáticamente la rueda específica de la plataforma adecuada para su sistema.

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

Debería ver una salida similar a:

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

El nombre exacto de la rueda depende de su SO y arquitectura de CPU — consulte la [tabla de sufijos de rueda]() en Requisitos del sistema para la lista completa.

## Add the Package to `requirements.txt`

Agregue la dependencia al `requirements.txt` de su proyecto:

```text
groupdocs-viewer-net
```

Luego instale desde el archivo:

```bash
pip install -r requirements.txt
```

Fije una versión específica si necesita compilaciones reproducibles — por ejemplo, `groupdocs-viewer-net==26.9.0`.

## Install from a Pre-Downloaded Wheel

Para entornos aislados o controlados, descargue la rueda del sitio [GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) o de la [página de lanzamiento de PyPI](https://pypi.org/project/groupdocs-viewer-net/#files) e instálela directamente. Se publican cuatro ruedas específicas por plataforma por cada versión; elija la que coincida con su host:

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux_2_27_x86_64.whl` (glibc 2.27 or newer)
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_arm64.whl` (macOS 12 or newer)
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_x86_64.whl` (macOS 12 or newer)

Desde la 26.9, los nombres de archivo indican el sistema más antiguo en el que cada rueda funciona, por lo que pip 20.3 o superior rechaza una más antigua de inmediato en lugar de instalar un tiempo de ejecución que no puede iniciarse. Las ruedas hasta la 26.5 estaban etiquetadas `manylinux1_x86_64`, `macosx_10_14_x86_64` y `macosx_11_0_arm64`.

Copie la rueda descargada en la carpeta de su proyecto y instálela con `pip`:

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

Nombre el archivo de la rueda explícitamente: PowerShell no expande un comodín `*` para un comando nativo, por lo que `pip install groupdocs_viewer_net-*.whl` falla allí.

Salida esperada:

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
