---
title: "set_license 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "将许可证应用于当前进程。"
type: docs
url: /zh/python-net/groupdocs.viewer/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

将许可证应用于当前进程。

```python
def set_license(self, license_source):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| license_source |  | 可以是指向 ``.lic`` 文件的字符串路径，或可读取的类文件对象（file‑like）以提供许可证字节。类文件输入会先写入临时文件，然后再传递给桥接层。 |

| 引发 | 描述 |
| :- | :- |
| `TypeError` | 如果 ``license_source`` 既不是字符串路径，也不是可读取的类文件对象。 |

### 另见
* class [`License`](/viewer/python-net/groupdocs.viewer/license/)
