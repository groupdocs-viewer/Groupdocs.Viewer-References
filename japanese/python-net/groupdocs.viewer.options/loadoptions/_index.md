---
title: "LoadOptions クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ファイルを開く際に使用されるオプション。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

ファイルを開く際に使用されるオプション。

LoadOptions 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/) クラスのインスタンスを初期化します。 |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | 新しい LoadOptions インスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | このプロパティは、[`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/)、[`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/)、および [`FileType.tsv`](/viewer/python-net/groupdocs.viewer/filetype/tsv/) ファイルのエンコーディング検出を有効にします。 |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | テキストベースのファイルやメールメッセージ（[`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/)、[`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/)、[`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/)）を開く際に使用されるエンコーディングです。デフォルト値は `utf-8` です。 |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | 開くファイルのタイプ。 |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | 暗号化されたファイルを開くためのパスワード。 |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | 外部リソースをロードするタイムアウト。 |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | このプロパティは、画像などのすべての外部リソースのロードを無効にしますが、[`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) にリストされているものは除外されます。 |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | このプロパティは、GroupDocs.Viewer が PDF ドキュメントの構造的破損の修復を試みることを可能にします。デフォルトは False です。 |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | このリストは、[`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) が `True` に設定されている場合にロードすべき外部リソースに対応する URL フラグメントです。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
