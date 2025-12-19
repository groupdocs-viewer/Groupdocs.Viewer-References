---
title: WordProcessingOptions class
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 300
---

## WordProcessingOptions class

Contains options for rendering Word documents. For details, see the [documentation](https://docs.groupdocs.com/viewer/net/render-word-documents/).



The WordProcessingOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/#) | Contains options for rendering word processing documents. For details, see the [documentation](https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes). |


### Properties
| Property | Description |
| :- | :- |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size) | The size of the output page.<br/>The default value is [`PageSize.UNSPECIFIED`](/viewer/python-net/groupdocs.viewer.options/pagesize#UNSPECIFIED) which means that a page size is set in a page settings (Page Setup) is used.<br/><br/>When rendering HTM and HTML files the default page size is set to Letter 792 x 612 points.<br/>As a result, some of the content may not fit into the page frame.<br/>Set a larger page size e.g. [`PageSize.A3`](/viewer/python-net/groupdocs.viewer.options/pagesize#A3) to fit the contents. |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes) | Enables tracked changes (revisions) rendering. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin) | Sets the left margin of a page. |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin) | Sets the right margin of a page. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin) | Sets the top margin of a page. |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin) | Sets the bottom margin of a page. |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features) | This option enables kerning and other OpenType Features when rendering Arabic, Hebrew, Indian Latin-based, or Cyrillic-based scripts. |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents) | When rendering to HTML or PDF, you can set this option to `true` to disable navigation from the table of contents.<br/>For HTML rendering, `a` tags with relative links will be replaced with `span` tags, removing functionality but preserving visual appearance.<br/>For PDF rendering, the table of contents will be rendered as plain text without links to document sections. |



### See Also
* module [`groupdocs.viewer.options`](..)
