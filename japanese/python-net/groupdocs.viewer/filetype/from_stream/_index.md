---
title: "from_stream メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ファイルシグネチャを読み取ってファイルタイプを検出します。"
type: docs
url: /ja/python-net/groupdocs.viewer/filetype/from_stream/
is_root: false
weight: 1120
---


## from_stream {#stream}

ファイルシグネチャを読み取ってファイルタイプを検出します。

```python
def from_stream(cls, stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | `io.RawIOBase` | ファイルストリームです。 |

## from_stream {#stream-password}

ファイルシグネチャを読み取ってファイルタイプを検出します。

```python
def from_stream(cls, stream, password):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | `io.RawIOBase` | ファイルストリームです。 |
| password | `str` | ファイルを開くためのパスワードです。 |

## from_stream {#stream-logger}

ファイルシグネチャを読み取ってファイルタイプを検出します。

```python
def from_stream(cls, stream, logger):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | `io.RawIOBase` | ファイルストリームです。 |
| logger | `ILogger` | ロガー。 |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

## from_stream {#stream-password-logger}

ファイルシグネチャを読み取ってファイルタイプを検出します。

```python
def from_stream(cls, stream, password, logger):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | `io.RawIOBase` | ファイルストリームです。 |
| password | `str` | ファイルを開くためのパスワードです。 |
| logger | `ILogger` | ロガー。 |

**Returns:** FileType: The detected file type, or `FileType.unknown` if detection fails.

### 参照
* class [`FileType`](/viewer/python-net/groupdocs.viewer/filetype/)
