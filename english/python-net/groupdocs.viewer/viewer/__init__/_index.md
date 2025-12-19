---
title: Viewer constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer/viewer/__init__/
is_root: false
weight: 10
---

## __init__ {#io.RawIOBase}

Initializes new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer) class.



```python
def __init__(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The file stream. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `stream` is null. |




## __init__ {#System.String}

Initializes new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer) class.



```python
def __init__(self, file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String | The path to the file to render. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `file_path` is null or empty. |




## __init__ {#io.RawIOBase-bool}

Initializes new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer) class.



```python
def __init__(self, stream, leave_open):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The file stream. |
| leave_open | bool | to leave the stream open after the Viewer object is disposed; otherwise, . |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `stream` is null. |




## __init__ {#io.RawIOBase-groupdocs.viewer.options.LoadOptions}

Initializes new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer) class.



```python
def __init__(self, stream, load_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The file stream. |
| load_options | groupdocs.viewer.options.LoadOptions | The document load options. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `stream` is null. |
| ArgumentNullException | Thrown when `load_options` is null. |




## __init__ {#io.RawIOBase-groupdocs.viewer.ViewerSettings}

Initializes new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer) class.



```python
def __init__(self, stream, settings):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The file stream. |
| settings | groupdocs.viewer.ViewerSettings | The Viewer settings. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `stream` is null. |
| ArgumentNullException | Thrown when `settings` is null. |




## __init__ {#System.String-groupdocs.viewer.ViewerSettings}

Initializes new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer) class.



```python
def __init__(self, file_path, settings):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String | The path to the file to render. |
| settings | groupdocs.viewer.ViewerSettings | The Viewer settings. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `file_path` is null or empty. |
| ArgumentNullException | Thrown when `settings` is null. |




## __init__ {#System.String-groupdocs.viewer.options.LoadOptions}

Initializes new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer) class.



```python
def __init__(self, file_path, load_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String | The path to the file to render. |
| load_options | groupdocs.viewer.options.LoadOptions | The options that used to open the file. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `file_path` is null or empty. |
| ArgumentNullException | Thrown when `load_options` is null. |




## __init__ {#io.RawIOBase-groupdocs.viewer.options.LoadOptions-bool}

Initializes new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer) class.



```python
def __init__(self, stream, load_options, leave_open):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The file stream. |
| load_options | groupdocs.viewer.options.LoadOptions | The document load options. |
| leave_open | bool | to leave the stream open after the Viewer object is disposed; otherwise, . |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `stream` is null. |
| ArgumentNullException | Thrown when `load_options` is null. |




## __init__ {#io.RawIOBase-groupdocs.viewer.ViewerSettings-bool}

Initializes new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer) class.



```python
def __init__(self, stream, settings, leave_open):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The file stream. |
| settings | groupdocs.viewer.ViewerSettings | The Viewer settings. |
| leave_open | bool | to leave the stream open after the Viewer object is disposed; otherwise, . |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `stream` is null. |
| ArgumentNullException | Thrown when `settings` is null. |




## __init__ {#io.RawIOBase-groupdocs.viewer.options.LoadOptions-groupdocs.viewer.ViewerSettings}

Initializes new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer) class.



```python
def __init__(self, stream, load_options, settings):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The file stream. |
| load_options | groupdocs.viewer.options.LoadOptions | The document load options. |
| settings | groupdocs.viewer.ViewerSettings | The Viewer settings. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `stream` is null. |
| ArgumentNullException | Thrown when `load_options` is null. |
| ArgumentNullException | Thrown when `settings` is null. |




## __init__ {#System.String-groupdocs.viewer.options.LoadOptions-groupdocs.viewer.ViewerSettings}

Initializes new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer) class.



```python
def __init__(self, file_path, load_options, settings):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String | The path to the file to render. |
| load_options | groupdocs.viewer.options.LoadOptions | The options that used to open the file. |
| settings | groupdocs.viewer.ViewerSettings | The Viewer settings. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `file_path` is null or empty. |
| ArgumentNullException | Thrown when `load_options` is null. |
| ArgumentNullException | Thrown when `settings` is null. |




## __init__ {#io.RawIOBase-groupdocs.viewer.options.LoadOptions-groupdocs.viewer.ViewerSettings-bool}

Initializes new instance of [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer) class.



```python
def __init__(self, stream, load_options, settings, leave_open):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The file stream. |
| load_options | groupdocs.viewer.options.LoadOptions | The document load options. |
| settings | groupdocs.viewer.ViewerSettings | The Viewer settings. |
| leave_open | bool | to leave the stream open after the Viewer object is disposed; otherwise, . |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `stream` is null. |
| ArgumentNullException | Thrown when `load_options` is null. |
| ArgumentNullException | Thrown when `settings` is null. |





### See Also
* module [`groupdocs.viewer`](../../)
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer)
