---
title: "インストール"
linkTitle: "Installation"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Windows、Linux、macOS 上で .NET 経由で Python 用 GroupDocs.Viewer をインストールします — PyPI から、または事前にダウンロードしたホイールから、Intel と Apple Silicon ビルドを含みます。"
type: docs
url: /ja/python-net/guides/installation/
is_root: false
weight: 10
---


インストールする前に、サポートされている Python バージョンとプラットフォームの依存関係について、[System Requirements]() を確認してください。

## Install Package from PyPI

このライブラリは [PyPI](https://pypi.org/project/groupdocs-viewer-net/) で **`groupdocs-viewer-net`** として公開されています。`pip` はシステムに適したプラットフォーム固有のホイールを自動的に選択します。

### Install the Latest Version

{{< tabs \"install-pypi\">}}
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

以下のような出力が表示されます:

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

正確なホイール名は OS と CPU アーキテクチャに依存します — 完全な一覧は System Requirements の [wheel-suffix table]() を参照してください。

## Add the Package to `requirements.txt`

プロジェクトの `requirements.txt` に依存関係を追加します:

```text
groupdocs-viewer-net
```

次に、ファイルからインストールします:

```bash
pip install -r requirements.txt
```

再現性のあるビルドが必要な場合は特定のバージョンに固定します — 例: `groupdocs-viewer-net==26.9.0`。

## Install from a Pre-Downloaded Wheel

ネットワークが遮断された環境や制御された環境では、[GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) サイトまたは [PyPI release page](https://pypi.org/project/groupdocs-viewer-net/#files) からホイールをダウンロードし、直接インストールしてください。各リリースごとに 4 つのプラットフォーム固有のホイールが公開されており、ホストに合致するものを選択します:

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux_2_27_x86_64.whl` (glibc 2.27 or newer)
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_arm64.whl` (macOS 12 or newer)
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_x86_64.whl` (macOS 12 or newer)

バージョン 26.9 以降、ファイル名には各ホイールが対応する最古のシステムが示されるようになり、pip 20.3 以降は起動できないランタイムをインストールしないよう、古いホイールを事前に拒否します。26.5 までのホイールは `manylinux1_x86_64`、`macosx_10_14_x86_64`、`macosx_11_0_arm64` とタグ付けされていました。

ダウンロードしたホイールをプロジェクトフォルダーにコピーし、`pip` でインストールします:

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

ホイールファイル名を明示的に指定してください: PowerShell はネイティブコマンドに対して `*` ワイルドカードを展開しないため、`pip install groupdocs_viewer_net-*.whl` は失敗します。

期待される出力:

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
