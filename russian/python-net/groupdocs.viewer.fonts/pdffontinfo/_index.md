---
title: "Класс PdfFontInfo"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инкапсулирует метаданные и бинарные данные PDF‑шрифта, загруженного в экземпляр Viewer, который может быть встроен в документ или установлен в операционной системе, где работает GroupDocs.Viewer."
type: docs
url: /ru/python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

Инкапсулирует метаданные и бинарные данные PDF‑шрифта, загруженного в экземпляр [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/), который может быть встроен в документ или установлен в операционной системе, где работает GroupDocs.Viewer.

Тип PdfFontInfo раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### Методы
| Метод | Описание |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | Сериализует эту информацию о шрифте как правило @font-face и записывает её в указанный текстовый писатель. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | Содержимое этого шрифта в виде массива байтов, или None, если доступны только метаданные и бинарное содержимое недоступно. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | Семейное имя шрифта без стиля; никогда не None и не пустая строка. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | Формат этого шрифта. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | Свойство указывает, встроен ли шрифт в PDF‑документ и загружен в экземпляр Viewer (`True`), или нет. |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | Свойство указывает, присутствует ли этот шрифт (установлен) в операционной системе, где запущен GroupDocs.Viewer. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | Стиль шрифта; может быть Regular, Bold, Italic или Bold Italic. |

### См. также
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
