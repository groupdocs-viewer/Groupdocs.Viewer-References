---
title: LoadOptions
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: 
type: docs
weight: 100
url: /viewer/python-net/groupdocs.viewer.options/loadoptions/
---

## LoadOptions class

Contains options that used to open the file. For details, see this

The LoadOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|LoadOptions()|Initializes an instance of the [LoadOptions](/viewer/python-net/groupdocs.viewer.options/loadoptions/) class.|
|LoadOptions(file_type)|Initializes a new instance of the LoadOptions class|
## Properties
| Name | Description |
| :- | :- |
|file_type|Sets the type of the file to open.|
|password|Sets the password to open encrypted file.|
|encoding|Sets the encoding used when opening text-based files or email messages such as<br/>            [None](/viewer/python-net/groupdocs.viewer/filetype/),<br/>            [None](/viewer/python-net/groupdocs.viewer/filetype/),<br/>            and [None](/viewer/python-net/groupdocs.viewer/filetype/).<br/>            Default value is .|
|detect_encoding|Enables the encoding detection for the [None](/viewer/python-net/groupdocs.viewer/filetype/), [None](/viewer/python-net/groupdocs.viewer/filetype/), and [None](/viewer/python-net/groupdocs.viewer/filetype/) files.|
|resource_loading_timeout|Sets the timeout to load external resources.|
|skip_external_resources|Disables loading of all external resource such as images except [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/).|
|whitelisted_resources|The list of URL fragments corresponding to external resources that should be loaded<br/>            when [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/) is set to|

### See Also

* namespace [groupdocs.viewer.options](/viewer/python-net/groupdocs.viewer.options/)
* assembly [GroupDocs.Viewer](/viewer/python-net/)

