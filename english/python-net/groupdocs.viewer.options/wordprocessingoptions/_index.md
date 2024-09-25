---
title: WordProcessingOptions
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: 
type: docs
weight: 300
url: /python-net/groupdocs.viewer.options/wordprocessingoptions/
---

## WordProcessingOptions class

Contains options for rendering Word documents. For details, see the

The WordProcessingOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|WordProcessingOptions()|Contains options for rendering word processing documents. For details, see the|
## Properties
| Name | Description |
| :- | :- |
|page_size|The size of the output page.<br/>            The default value is [UNSPECIFIED](/viewer/python-net/groupdocs.viewer.options/pagesize/) which means that a page size is set in a page settings (Page Setup) is used.|
|render_tracked_changes|Enables tracked changes (revisions) rendering.|
|left_margin|Sets the left margin of a page.|
|right_margin|Sets the right margin of a page.|
|top_margin|Sets the top margin of a page.|
|bottom_margin|Sets the bottom margin of a page.|
|enable_open_type_features|This option enables kerning and other OpenType Features when rendering Arabic, Hebrew, Indian Latin-based, or Cyrillic-based scripts.|
|unlink_table_of_contents|When rendering to HTML or PDF, you can set this option to `true` to disable navigation from the table of contents.<br/>            For HTML rendering, `a` tags with relative links will be replaced with `span` tags, removing functionality but preserving visual appearance.<br/>            For PDF rendering, the table of contents will be rendered as plain text without links to document sections.|

### See Also

* namespace [groupdocs.viewer.options](/viewer/python-net/groupdocs.viewer.options/)
* assembly [GroupDocs.Viewer](/viewer/python-net/)

