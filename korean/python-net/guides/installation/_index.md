---
title: "설치"
linkTitle: "Installation"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Windows, Linux 또는 macOS에서 .NET을 통해 GroupDocs.Viewer for Python을 설치합니다 — PyPI에서 또는 미리 다운로드한 휠에서, Intel 및 Apple Silicon 빌드를 포함합니다."
type: docs
url: /ko/python-net/guides/installation/
is_root: false
weight: 10
---


설치하기 전에 지원되는 Python 버전 및 플랫폼 종속성에 대한 [System Requirements]()를 확인하십시오.

## Install Package from PyPI

이 라이브러리는 [PyPI](https://pypi.org/project/groupdocs-viewer-net/)에 **`groupdocs-viewer-net`** 이름으로 게시됩니다. `pip`은 시스템에 맞는 플랫폼 전용 휠을 자동으로 선택합니다.

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

다음과 유사한 출력이 표시됩니다:

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

정확한 휠 이름은 OS와 CPU 아키텍처에 따라 달라집니다 — 전체 목록은 System Requirements에 있는 [wheel-suffix table]()를 참조하십시오.

## Add the Package to `requirements.txt`

프로젝트의 `requirements.txt`에 종속성을 추가하십시오:

```text
groupdocs-viewer-net
```

그런 다음 파일에서 설치합니다:

```bash
pip install -r requirements.txt
```

재현 가능한 빌드가 필요하면 특정 버전으로 고정하십시오 — 예: `groupdocs-viewer-net==26.9.0`.

## Install from a Pre-Downloaded Wheel

에어갭 또는 제어된 환경에서는 [GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) 사이트 또는 [PyPI release page](https://pypi.org/project/groupdocs-viewer-net/#files)에서 휠을 다운로드하고 직접 설치하십시오. 각 릴리스마다 네 개의 플랫폼 전용 휠이 게시되며, 호스트와 일치하는 것을 선택하십시오:

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux_2_27_x86_64.whl` (glibc 2.27 or newer)
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_arm64.whl` (macOS 12 or newer)
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_x86_64.whl` (macOS 12 or newer)

26.9부터 파일 이름에 각 휠이 실행될 수 있는 가장 오래된 시스템이 명시되어, pip 20.3 이상에서는 실행할 수 없는 오래된 휠을 사전에 거부합니다. 26.5까지의 휠은 `manylinux1_x86_64`, `macosx_10_14_x86_64`, `macosx_11_0_arm64` 태그가 붙어 있었습니다.

다운로드한 휠을 프로젝트 폴더에 복사하고 `pip`으로 설치하십시오:

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

휠 파일 이름을 명시적으로 지정하십시오: PowerShell은 네이티브 명령에 대해 `*` 와일드카드를 확장하지 않으므로 `pip install groupdocs_viewer_net-*.whl`이 실패합니다.

예상 출력:

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
