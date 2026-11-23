---
title: "التثبيت"
linkTitle: "Installation"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "قم بتثبيت GroupDocs.Viewer للبايثون عبر .NET على Windows أو Linux أو macOS — من PyPI أو من حزمة wheel تم تحميلها مسبقًا، بما في ذلك إصدارات Intel وApple Silicon."
type: docs
url: /ar/python-net/guides/installation/
is_root: false
weight: 10
---


قبل التثبيت، تحقق من [System Requirements]() للإصدارات المدعومة من Python واعتمادات المنصة.

## Install Package from PyPI

المكتبة منشورة على [PyPI](https://pypi.org/project/groupdocs-viewer-net/) باسم **`groupdocs-viewer-net`**. `pip` يختار تلقائيًا العجلة المناسبة للنظام الأساسي الخاص بك.

### Install the Latest Version

{{< tabs "install-pypi">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< /tabs >}}

يجب أن ترى مخرجات مشابهة لـ:

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

اسم العجلة الدقيق يعتمد على نظام التشغيل ومعمارية المعالج — راجع [wheel-suffix table]() في System Requirements للحصول على القائمة الكاملة.

## Add the Package to `requirements.txt`

أضف الاعتماد إلى ملف `requirements.txt` الخاص بمشروعك:

```text
groupdocs-viewer-net
```

ثم قم بالتثبيت من الملف:

```bash
pip install -r requirements.txt
```

ثبت إلى إصدار محدد إذا كنت تحتاج إلى بناء قابل لإعادة الإنتاج — على سبيل المثال، `groupdocs-viewer-net==26.9.0`.

## Install from a Pre-Downloaded Wheel

في البيئات المعزولة أو الخاضعة للرقابة، قم بتنزيل العجلة من موقع [GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) أو من [صفحة إصدار PyPI](https://pypi.org/project/groupdocs-viewer-net/#files) وقم بتثبيتها مباشرة. يتم نشر أربع عجلات خاصة بالمنصة لكل إصدار؛ اختر ما يتطابق مع مضيفك:

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux_2_27_x86_64.whl` (glibc 2.27 or newer)
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_arm64.whl` (macOS 12 or newer)
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_x86_64.whl` (macOS 12 or newer)

منذ الإصدار 26.9، تُظهر أسماء الملفات أقدم نظام يمكن لكل عجلة تشغيله، لذا يرفض `pip` 20.3 أو أحدث العجلة القديمة مسبقًا بدلاً من تثبيت بيئة تشغيل لا يمكنها البدء. العجلات حتى الإصدار 26.5 كانت مُعلمة بـ `manylinux1_x86_64`، `macosx_10_14_x86_64` و `macosx_11_0_arm64`.

انسخ العجلة التي تم تنزيلها إلى مجلد مشروعك وقم بتثبيتها باستخدام `pip`:

{{< tabs "install-wheel">}}
{{< tab "Windows (64-bit)" >}}
```ps
py -m pip install groupdocs_viewer_net-26.9.0-py3-none-win_amd64.whl
```
{{< /tab >}}
{{< tab "Linux (glibc)" >}}
```bash
python3 -m pip install ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
```
{{< /tab >}}
{{< tab "macOS (Apple Silicon)" >}}
```bash
python3 -m pip install ./groupdocs_viewer_net-26.9.0-py3-none-macosx_12_0_arm64.whl
```
{{< /tab >}}
{{< tab "macOS (Intel)" >}}
```bash
python3 -m pip install ./groupdocs_viewer_net-26.9.0-py3-none-macosx_12_0_x86_64.whl
```
{{< /tab >}}
{{< /tabs >}}

قم بتسمية ملف العجلة صراحةً: PowerShell لا يقوم بتوسيع حرف البدل `*` للأمر الأصلي، لذا فالأمر `pip install groupdocs_viewer_net-*.whl` يفشل هناك.

المخرجات المتوقعة:

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
