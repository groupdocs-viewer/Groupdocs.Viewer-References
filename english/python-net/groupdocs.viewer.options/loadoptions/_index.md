---
title: LoadOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 100
---

## LoadOptions class

Contains options that used to open the file. For details, see this [page](https://docs.groupdocs.com/viewer/net/loading/) and its children.



The LoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#) | Initializes an instance of the [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions) class. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#groupdocs.viewer.FileType) | Initializes an instance of the [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions) class. |


### Properties
| Property | Description |
| :- | :- |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type) | Sets the type of the file to open. |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password) | Sets the password to open encrypted file. |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding) | Sets the encoding used when opening text-based files or email messages such as<br/>[`FileType.CSV`](/viewer/python-net/groupdocs.viewer/filetype),<br/>[`FileType.TXT`](/viewer/python-net/groupdocs.viewer/filetype),<br/>and [`FileType.MSG`](/viewer/python-net/groupdocs.viewer/filetype).<br/>Default value is UTF8. |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding) | Enables the encoding detection for the [`FileType.TXT`](/viewer/python-net/groupdocs.viewer/filetype), [`FileType.CSV`](/viewer/python-net/groupdocs.viewer/filetype), and [`FileType.TSV`](/viewer/python-net/groupdocs.viewer/filetype) files. |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout) | Sets the timeout to load external resources. |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources) | Disables loading of all external resource such as images except [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions#whitelisted_resources). |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources) | The list of URL fragments corresponding to external resources that should be loaded<br/>when [`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions#skip_external_resources) is set to `true`. |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair) | When enabled GroupDocs.Viewer tries to repair structural corruption in PDF documents.<br/>Default value is `false`. |



### See Also
* module [`groupdocs.viewer.options`](..)
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions)
