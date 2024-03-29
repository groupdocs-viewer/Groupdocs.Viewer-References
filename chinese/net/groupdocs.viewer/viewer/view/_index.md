---
title: View
second_title: GroupDocs.Viewer for .NET API 参考
description: 创建所有文档页面的视图
type: docs
weight: 70
url: /zh/net/groupdocs.viewer/viewer/view/
---
## View(ViewOptions) {#view}

创建所有文档页面的视图。

```csharp
public void View(ViewOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| options | ViewOptions | 视图选项。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*options*一片空白。 |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | 当打开文档需要密码时抛出。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 当指定的密码不正确时抛出。 |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 找不到附件时抛出。 |

### 评论

**了解更多**

* 更多关于遵循本指南的不同查看选项： [如何使用 GroupDocs.Viewer 自定义文档查看输出](https://docs.groupdocs.com/display/viewernet/Viewing)

### 也可以看看

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

创建所有文档页面的视图。

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| options | ViewOptions | 视图选项。 |
| cancellationToken | CancellationToken | 取消令牌发送取消当前查看进程的请求。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*options*一片空白。 |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | 当打开文档需要密码时抛出。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 当指定的密码不正确时抛出。 |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 找不到附件时抛出。 |

### 评论

**了解更多**

* 更多关于遵循本指南的不同查看选项： [如何使用 GroupDocs.Viewer 自定义文档查看输出](https://docs.groupdocs.com/display/viewernet/Viewing)

### 也可以看看

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

创建特定文档页面的视图。

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| options | ViewOptions | 视图选项。 |
| pageNumbers | Int32[] | 要查看的页码。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*options*一片空白。 |
| ArgumentNullException | 抛出时*pageNumbers*一片空白。 |
| ArgumentException | 抛出时*pageNumbers*是空的。 |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | 当打开文档需要密码时抛出。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 当指定的密码不正确时抛出。 |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 找不到附件时抛出。 |

### 评论

**了解更多**

* 更多关于遵循本指南的不同查看选项： [如何使用 GroupDocs.Viewer 自定义文档查看输出](https://docs.groupdocs.com/display/viewernet/Viewing)

### 也可以看看

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

创建特定文档页面的视图。

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| options | ViewOptions | 视图选项。 |
| pageNumbers | CancellationToken | 要查看的页码。 |
| cancellationToken | Int32[] | 用于取消处理的取消令牌。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 抛出时*options*一片空白。 |
| ArgumentNullException | 抛出时*pageNumbers*一片空白。 |
| ArgumentException | 抛出时*pageNumbers*是空的。 |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | 当打开文档需要密码时抛出。 |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | 当指定的密码不正确时抛出。 |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | 找不到附件时抛出。 |

### 评论

**了解更多**

* 更多关于遵循本指南的不同查看选项： [如何使用 GroupDocs.Viewer 自定义文档查看输出](https://docs.groupdocs.com/display/viewernet/Viewing)

### 也可以看看

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* 命名空间 [GroupDocs.Viewer](../../viewer)
* 部件 [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
