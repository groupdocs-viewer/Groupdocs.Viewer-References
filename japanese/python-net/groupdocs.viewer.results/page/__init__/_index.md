---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Page の新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.results/page/__init__/
is_root: false
weight: 10
---


## __init__

新しい [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) インスタンスを初期化します。

```python
def __init__(self):
    ...
```

## __init__ {#number-visible}

新しい [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) インスタンスを初期化します。

```python
def __init__(self, number, visible):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| number | `int` | ページ番号です。 |
| visible | `bool` | ページの可視性インジケータ。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `number` が 0 以下のとき。 |

## __init__ {#number-name-visible}

新しい Page インスタンスを初期化します。

```python
def __init__(self, number, name, visible):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| number | `int` | ページ番号です。 |
| name | `str` | ワークシートまたはページ名です。 |
| visible | `bool` | ページの可視性インジケータ。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `number` が 0 以下のとき。 |

## __init__ {#number-visible-width-height}

新しい [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) インスタンスを初期化します。

```python
def __init__(self, number, visible, width, height):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| number | `int` | ページ番号です。 |
| visible | `bool` | ページの可視性インジケータ。 |
| width | `int` | JPG または PNG として表示する場合のページの幅（ピクセル単位）。 |
| height | `int` | JPG または PNG として表示する際のページの高さ（ピクセル）です。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `height` が 0 以下のとき。 |

## __init__ {#number-name-visible-width-height}

新しい [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) インスタンスを初期化します。

```python
def __init__(self, number, name, visible, width, height):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| number | `int` | ページ番号です。 |
| name | `str` | ワークシートまたはページ名です。 |
| visible | `bool` | ページの可視性インジケータ。 |
| width | `int` | JPG または PNG として表示する場合のページの幅（ピクセル単位）。 |
| height | `int` | JPG または PNG として表示する際のページの高さ（ピクセル）です。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `height` が 0 以下のとき。 |

## __init__ {#number-visible-width-height-lines}

新しい [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) インスタンスを初期化します。

```python
def __init__(self, number, visible, width, height, lines):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| number | `int` | ページ番号です。 |
| visible | `bool` | ページの可視性インジケータ。 |
| width | `int` | JPG または PNG として表示する場合のページの幅（ピクセル単位）。 |
| height | `int` | JPG または PNG として表示する際のページの高さ（ピクセル）です。 |
| lines | `List[Line]` | テキスト抽出が有効な状態で JPG または PNG として表示する際のページに含まれる行です。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `lines` が None の場合。 |

## __init__ {#number-name-visible-width-height-lines}

新しい [`Page`](/viewer/python-net/groupdocs.viewer.results/page/) インスタンスを初期化します。

```python
def __init__(self, number, name, visible, width, height, lines):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| number | `int` | ページ番号です。 |
| name | `str` | ワークシートまたはページ名です。 |
| visible | `bool` | ページの可視性インジケータ。 |
| width | `int` | JPG または PNG として表示する場合のページの幅（ピクセル単位）。 |
| height | `int` | JPG または PNG として表示する際のページの高さ（ピクセル）です。 |
| lines | `List[Line]` | テキスト抽出が有効な状態で JPG または PNG として表示する際のページに含まれる行です。 |

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `lines` が None のとき。 |

### 参照
* class [`Page`](/viewer/python-net/groupdocs.viewer.results/page/)
