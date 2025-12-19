---
title: for_split_sheet_into_pages method
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 60
---

## for_split_sheet_into_pages {#int}

Initializes an instance of the [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions) class for rendering sheet into pages.


### Returns 


New instance of the [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions) class for rendering sheet into pages.


```python
def for_split_sheet_into_pages(self, count_rows_per_page):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| count_rows_per_page | int | Count of rows to include into each page. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `count_rows_per_page` is equals or less than zero. |




## for_split_sheet_into_pages {#int-int}

Initializes an instance of the [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions) class for rendering sheet into pages.


### Returns 


New instance of the [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions) class for rendering sheet into pages.


```python
def for_split_sheet_into_pages(self, count_rows_per_page, count_columns_per_page):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| count_rows_per_page | int | Count of rows to include into each page. |
| count_columns_per_page | int | Count of columns to include into each page. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentException | Thrown when `count_rows_per_page` is equals or less than zero. |
| ArgumentException | Thrown when `count_columns_per_page` is equals or less than zero. |





### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions)
