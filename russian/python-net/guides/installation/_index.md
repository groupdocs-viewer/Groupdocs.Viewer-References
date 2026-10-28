---
title: "Установка"
linkTitle: "Installation"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Установите GroupDocs.Viewer для Python через .NET на Windows, Linux или macOS — из PyPI или из предварительно загруженного wheel, включая сборки для Intel и Apple Silicon."
type: docs
url: /ru/python-net/guides/installation/
is_root: false
weight: 10
---


Перед установкой проверьте [System Requirements]() на поддерживаемые версии Python и зависимости платформы.

## Install Package from PyPI

Библиотека опубликована на [PyPI](https://pypi.org/project/groupdocs-viewer-net/) как **`groupdocs-viewer-net`**. `pip` автоматически выбирает подходящий платформенно-специфичный wheel для вашей системы.

### Install the Latest Version

{{< tabs \"install-pypi\">}}
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

Вы должны увидеть вывод, похожий на:

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

Точное название wheel зависит от вашей ОС и архитектуры CPU — см. [wheel-suffix table]() в System Requirements для полного списка.

## Add the Package to `requirements.txt`

Добавьте зависимость в файл `requirements.txt` вашего проекта:

```text
groupdocs-viewer-net
```

Затем установите из файла:

```bash
pip install -r requirements.txt
```

Зафиксируйте конкретную версию, если вам нужны воспроизводимые сборки — например, `groupdocs-viewer-net==26.9.0`.

## Install from a Pre-Downloaded Wheel

Для изолированных или контролируемых сред скачайте wheel с сайта [GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) или со [страницы релиза PyPI](https://pypi.org/project/groupdocs-viewer-net/#files) и установите его напрямую. На каждый релиз публикуются четыре платформенно-специфичных wheel; выберите тот, который соответствует вашему хосту:

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux_2_27_x86_64.whl` (glibc 2.27 or newer)
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_arm64.whl` (macOS 12 or newer)
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_x86_64.whl` (macOS 12 or newer)

Начиная с версии 26.9 в названиях файлов указывается самая старая система, на которой каждый wheel может работать, поэтому pip 20.3 и новее отклоняют более старый wheel сразу, вместо установки среды выполнения, которая не может запуститься. Wheel до версии 26.5 имели теги `manylinux1_x86_64`, `macosx_10_14_x86_64` и `macosx_11_0_arm64`.

Скопируйте загруженный wheel в папку вашего проекта и установите его с помощью `pip`:

{{< tabs \"install-wheel\">}}
{{< tab \"Windows (64-bit)\" >}}
```ps
py -m pip install groupdocs_viewer_net-26.9.0-py3-none-win_amd64.whl
```
{{< /tab >}}
{{< tab \"Linux (glibc)\" >}}
```bash
python3 -m pip install ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
```
{{< /tab >}}
{{< tab \"macOS (Apple Silicon)\" >}}
```bash
python3 -m pip install ./groupdocs_viewer_net-26.9.0-py3-none-macosx_12_0_arm64.whl
```
{{< /tab >}}
{{< tab \"macOS (Intel)\" >}}
```bash
python3 -m pip install ./groupdocs_viewer_net-26.9.0-py3-none-macosx_12_0_x86_64.whl
```
{{< /tab >}}
{{< /tabs >}}

Укажите имя файла wheel явно: PowerShell не расширяет подстановочный символ `*` для нативной команды, поэтому `pip install groupdocs_viewer_net-*.whl` там не работает.

Ожидаемый вывод:

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
