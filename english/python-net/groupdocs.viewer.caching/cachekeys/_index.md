---
title: CacheKeys
second_title: GroupDocs.Viewer for Python via .NET API Reference
description: 
type: docs
weight: 10
url: /python-net/groupdocs.viewer.caching/cachekeys/
---

## CacheKeys class

Provides methods to retrieve unique identifier for the cache entry.

The CacheKeys type exposes the following members:
## Methods
| Name | Description |
| :- | :- |
|get_attachments_key()|Returns unique identifier for the cache entry that represents collection of [Attachment](/viewer/python-net/groupdocs.viewer.results/attachment/) objects.|
|get_attachment_key(attachment_id)|Returns unique identifier for the cache entry that represents attachment file.|
|get_view_info_key()|Returns unique identifier for the cache entry that represents [ViewInfo](/viewer/python-net/groupdocs.viewer.results/viewinfo/) object.|
|get_file_info_key()|Returns unique identifier for the cache entry that represents [ViewInfo](/viewer/python-net/groupdocs.viewer.results/viewinfo/) object.|
|get_file_key(extension)|Returns unique identifier for the cache entry that represents file.|
|get_page_key(page_number, extension)|Returns unique identifier for the cache entry that represents page file.|
|get_resource_key(page_number, resource)|Returns unique identifier for the cache entry that represents [Resource](/viewer/python-net/groupdocs.viewer.results/resource/) object.|
|get_resource_filter(page_number)|Returns filter string to search for cache entries that represents [Resource](/viewer/python-net/groupdocs.viewer.results/resource/) objects.|

### See Also

* namespace [groupdocs.viewer.caching](/viewer/python-net/groupdocs.viewer.caching/)
* assembly [GroupDocs.Viewer](/viewer/python-net/)

