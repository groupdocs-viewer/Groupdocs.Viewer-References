---
title: "Instalasi"
linkTitle: "Installation"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Instal GroupDocs.Viewer untuk Python via .NET di Windows, Linux, atau macOS — dari PyPI atau dari wheel yang sudah diunduh sebelumnya, termasuk build Intel dan Apple Silicon."
type: docs
url: /id/python-net/guides/installation/
is_root: false
weight: 10
---


Sebelum menginstal, periksa [System Requirements]() untuk versi Python yang didukung dan dependensi platform.

## Install Package from PyPI

Pustaka ini dipublikasikan di [PyPI](https://pypi.org/project/groupdocs-viewer-net/) sebagai **`groupdocs-viewer-net`**. `pip` secara otomatis memilih wheel spesifik platform yang tepat untuk sistem Anda.

### Install the Latest Version

{{< tabs "install-pypi">}}
{{< tab \"Windows\" >}}
```ps
py -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< /tabs >}}

Anda akan melihat keluaran yang mirip dengan:

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

Nama wheel yang tepat tergantung pada OS dan arsitektur CPU Anda — lihat [wheel-suffix table]() di System Requirements untuk daftar lengkap.

## Add the Package to `requirements.txt`

Tambahkan dependensi ke `requirements.txt` proyek Anda:

```text
groupdocs-viewer-net
```

Kemudian instal dari file:

```bash
pip install -r requirements.txt
```

Tetapkan ke versi tertentu jika Anda memerlukan build yang dapat direproduksi — misalnya, `groupdocs-viewer-net==26.9.0`.

## Install from a Pre-Downloaded Wheel

Untuk lingkungan yang terisolasi atau terkendali, unduh wheel dari situs [GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) atau [halaman rilis PyPI](https://pypi.org/project/groupdocs-viewer-net/#files) dan instal secara langsung. Empat wheel spesifik platform dipublikasikan per rilis; pilih yang cocok dengan host Anda:

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux_2_27_x86_64.whl` (glibc 2.27 or newer)
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_arm64.whl` (macOS 12 or newer)
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_x86_64.whl` (macOS 12 or newer)

Sejak versi 26.9 nama file menunjukkan sistem tertua yang dapat menjalankan setiap wheel, sehingga pip 20.3 atau yang lebih baru menolak wheel yang lebih lama di awal alih-alih menginstal runtime yang tidak dapat dijalankan. Wheel hingga versi 26.5 ditandai `manylinux1_x86_64`, `macosx_10_14_x86_64`, dan `macosx_11_0_arm64`.

Salin wheel yang diunduh ke folder proyek Anda dan instal dengan `pip`:

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

Namai file wheel secara eksplisit: PowerShell tidak memperluas wildcard `*` untuk perintah native, sehingga `pip install groupdocs_viewer_net-*.whl` gagal di sana.

Keluaran yang diharapkan:

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
