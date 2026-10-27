---
title: "Metered 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "管理计量（按使用付费）授权。"
type: docs
url: /zh/python-net/groupdocs.viewer/metered/
is_root: false
weight: 80
---


## Metered class

管理计量（按使用付费）授权。

Metered 许可证根据实际消耗计费（通常是页面或
已处理的文档）。在一次性设置公私钥对
应用启动时；包装器将使用情况报告回 GroupDocs
后台的许可证服务器。

Metered 类型公开以下成员：

### 方法
| 方法 | 描述 |
| :- | :- |
| [get_consumption_credit](/viewer/python-net/groupdocs.viewer/metered/get_consumption_credit/) | 返回当前密钥剩余的计量信用额度。 |
| [get_consumption_quantity](/viewer/python-net/groupdocs.viewer/metered/get_consumption_quantity/) | 返回迄今为止已消耗的计量总量。 |
| [set_metered_key](/viewer/python-net/groupdocs.viewer/metered/set_metered_key/#public_key-private_key) | 使用给定的公私钥对激活计量计费。 |

### 另见
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
