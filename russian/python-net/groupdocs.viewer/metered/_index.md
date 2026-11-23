---
title: "Класс Metered"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Управляет почасовым (pay-per-use) лицензированием."
type: docs
url: /ru/python-net/groupdocs.viewer/metered/
is_root: false
weight: 80
---


## Metered class

Управляет почасовым (pay-per-use) лицензированием.

Лицензии Metered выставляют счет на основе фактического потребления (обычно страниц или
обработанных документов). Установите пару публичного/приватного ключа один раз в
запуске приложения; обертка отправляет данные об использовании обратно в GroupDocs
сервер лицензий в фоновом режиме.

Тип Metered предоставляет следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [get_consumption_credit](/viewer/python-net/groupdocs.viewer/metered/get_consumption_credit/) | Возвращает оставшийся метрированный кредит для текущего ключа. |
| [get_consumption_quantity](/viewer/python-net/groupdocs.viewer/metered/get_consumption_quantity/) | Возвращает общее количество метрированных единиц, потребленных до сих пор. |
| [set_metered_key](/viewer/python-net/groupdocs.viewer/metered/set_metered_key/#public_key-private_key) | Активировать метрированную оплату с заданной парой публичного/приватного ключа. |

### См. также
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
