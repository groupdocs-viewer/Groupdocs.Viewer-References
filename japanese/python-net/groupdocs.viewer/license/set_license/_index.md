---
title: "set_license メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "現在のプロセスにライセンスを適用します。"
type: docs
url: /ja/python-net/groupdocs.viewer/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

現在のプロセスにライセンスを適用します。

```python
def set_license(self, license_source):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| license_source |  | ``.lic`` ファイルへの文字列パス、またはライセンスバイトを提供する読み取り可能なファイルライクオブジェクトのいずれかです。ファイルライク入力はブリッジに渡す前に一時ファイルに書き込まれます。 |

| 例外 | 説明 |
| :- | :- |
| `TypeError` | ``license_source`` が文字列パスでも読み取り可能なファイルライクオブジェクトでもない場合。 |

### 参照
* class [`License`](/viewer/python-net/groupdocs.viewer/license/)
