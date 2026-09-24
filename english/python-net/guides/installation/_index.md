---
title: Installation
linkTitle: "Installation"
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Install GroupDocs.Viewer for Python via .NET on Windows, Linux, or macOS — from PyPI or from a pre-downloaded wheel, including Intel and Apple Silicon builds."
type: docs
url: /python-net/guides/installation/
is_root: false
weight: 10
---


Before installing, check the [System Requirements]() for supported Python versions and platform dependencies.

## Install Package from PyPI

The library is published on [PyPI](https://pypi.org/project/groupdocs-viewer-net/) as **`groupdocs-viewer-net`**. `pip` automatically selects the right platform-specific wheel for your system.

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

You should see output similar to:

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

The exact wheel name depends on your OS and CPU architecture — see the [wheel-suffix table]() in System Requirements for the complete list.

## Add the Package to `requirements.txt`

Add the dependency to your project's `requirements.txt`:

```text
groupdocs-viewer-net
```

Then install from the file:

```bash
pip install -r requirements.txt
```

Pin to a specific version if you need reproducible builds — for example, `groupdocs-viewer-net==26.9.0`.

## Install from a Pre-Downloaded Wheel

For air-gapped or controlled environments, download the wheel from the [GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) site or the [PyPI release page](https://pypi.org/project/groupdocs-viewer-net/#files) and install it directly. Four platform-specific wheels are published per release; pick the one that matches your host:

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux1_x86_64.whl`
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_11_0_arm64.whl`
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_10_14_x86_64.whl`

Copy the downloaded wheel into your project folder and install it with `pip`:

{{< tabs "install-wheel">}}
{{< tab "Windows (64-bit)" >}}
```ps
py -m pip install groupdocs_viewer_net-26.9.0-py3-none-win_amd64.whl
```
{{< /tab >}}
{{< tab "Linux (glibc)" >}}
```bash
python3 -m pip install ./groupdocs_viewer_net-26.9.0-py3-none-manylinux1_x86_64.whl
```
{{< /tab >}}
{{< tab "macOS (Apple Silicon)" >}}
```bash
python3 -m pip install ./groupdocs_viewer_net-26.9.0-py3-none-macosx_11_0_arm64.whl
```
{{< /tab >}}
{{< tab "macOS (Intel)" >}}
```bash
python3 -m pip install ./groupdocs_viewer_net-26.9.0-py3-none-macosx_10_14_x86_64.whl
```
{{< /tab >}}
{{< /tabs >}}

Name the wheel file explicitly: PowerShell does not expand a `*` wildcard for a native command, so `pip install groupdocs_viewer_net-*.whl` fails there.

Expected output:

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux1_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
