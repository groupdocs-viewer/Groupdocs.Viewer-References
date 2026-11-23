---
title: "安装"
linkTitle: "Installation"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "通过 .NET 在 Windows、Linux 或 macOS 上安装 GroupDocs.Viewer for Python——可从 PyPI 或预先下载的 wheel 安装，包括 Intel 和 Apple Silicon 构建。"
type: docs
url: /zh/python-net/guides/installation/
is_root: false
weight: 10
---


安装前，请检查 [System Requirements]()，了解受支持的 Python 版本和平台依赖项。

## Install Package from PyPI

该库已发布在 [PyPI](https://pypi.org/project/groupdocs-viewer-net/) 上，名称为 **`groupdocs-viewer-net`**。`pip` 会自动为您的系统选择合适的平台特定 wheel。

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

您应该会看到类似以下的输出：

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

确切的 wheel 名称取决于您的操作系统和 CPU 架构——请参阅 System Requirements 中的 [wheel-suffix table]() 以获取完整列表。

## Add the Package to `requirements.txt`

将依赖添加到项目的 `requirements.txt` 中：

```text
groupdocs-viewer-net
```

然后从文件安装：

```bash
pip install -r requirements.txt
```

如果需要可复现的构建，请锁定到特定版本——例如，`groupdocs-viewer-net==26.9.0`。

## Install from a Pre-Downloaded Wheel

对于空气隔离或受控环境，请从 [GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) 网站或 [PyPI release page](https://pypi.org/project/groupdocs-viewer-net/#files) 下载 wheel 并直接安装。每个发行版会发布四个平台特定的 wheel；请选择与您的主机匹配的那个：

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux_2_27_x86_64.whl` (glibc 2.27 or newer)
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_arm64.whl` (macOS 12 or newer)
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_x86_64.whl` (macOS 12 or newer)

自 26.9 起，文件名会标明每个 wheel 可运行的最旧系统，因此 pip 20.3 或更高版本会在安装前拒绝较旧的 wheel，以免安装无法启动的运行时。26.5 之前的 wheel 使用标签 `manylinux1_x86_64`、`macosx_10_14_x86_64` 和 `macosx_11_0_arm64`。

将下载的 wheel 复制到项目文件夹中，并使用 `pip` 安装：

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

明确指定 wheel 文件名：PowerShell 不会为本机命令展开 `*` 通配符，因此 `pip install groupdocs_viewer_net-*.whl` 会失败。

预期输出：

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
