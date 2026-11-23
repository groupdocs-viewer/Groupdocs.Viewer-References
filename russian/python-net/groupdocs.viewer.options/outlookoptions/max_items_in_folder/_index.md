---
title: "Свойство max_items_in_folder"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Максимальное количество сообщений или элементов, которые могут быть отображены из одной папки."
type: docs
url: /ru/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/
is_root: false
weight: 2030
---


## max_items_in_folder property

Максимальное количество сообщений или элементов, которые могут быть отображены из одной папки.

Файлы данных Outlook могут быть большими, и получение всех сообщений может занять значительное время. Это свойство ограничивает максимальное количество сообщений или элементов, которые отображаются. Значение по умолчанию — `50`. Чтобы отобразить все сообщения, установите значение `0`.

Для примера кода см. документацию.

### Definition:
```python
@property
def max_items_in_folder(self):
    ...
@max_items_in_folder.setter
def max_items_in_folder(self, value):
    ...
```

### См. также
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions/)
