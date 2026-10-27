---
title: "Installation"
linkTitle: "Installation"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Installez GroupDocs.Viewer pour Python via .NET sur Windows, Linux ou macOS — depuis PyPI ou depuis une roue pré‑téléchargée, incluant les versions Intel et Apple Silicon."
type: docs
url: /fr/python-net/guides/installation/
is_root: false
weight: 10
---


Avant l'installation, vérifiez les [Exigences du système]() pour les versions Python prises en charge et les dépendances de la plateforme.

## Install Package from PyPI

La bibliothèque est publiée sur [PyPI](https://pypi.org/project/groupdocs-viewer-net/) sous le nom **`groupdocs-viewer-net`**. `pip` sélectionne automatiquement la bonne roue spécifique à la plateforme pour votre système.

### Install the Latest Version

{{< tabs "install-pypi">}}
{{< tab \"Windows\" >}}
```ps
py -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m pip install groupdocs-viewer-net
```
{{< /tab >}}
{{< /tabs >}}

Vous devriez voir une sortie similaire à :

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

Le nom exact de la roue dépend de votre OS et de l'architecture CPU — consultez le [tableau des suffixes de roue]() dans les Exigences du système pour la liste complète.

## Add the Package to `requirements.txt`

Ajoutez la dépendance à votre `requirements.txt` du projet :

```text
groupdocs-viewer-net
```

Installez ensuite à partir du fichier :

```bash
pip install -r requirements.txt
```

Fixez une version spécifique si vous avez besoin de builds reproductibles — par exemple, `groupdocs-viewer-net==26.9.0`.

## Install from a Pre-Downloaded Wheel

Pour les environnements isolés ou contrôlés, téléchargez la roue depuis le site [GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) ou la [page de publication PyPI](https://pypi.org/project/groupdocs-viewer-net/#files) et installez‑la directement. Quatre roues spécifiques à la plateforme sont publiées par version ; choisissez celle qui correspond à votre hôte :

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux_2_27_x86_64.whl` (glibc 2.27 or newer)
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_arm64.whl` (macOS 12 or newer)
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_x86_64.whl` (macOS 12 or newer)

Depuis la version 26.9, les noms de fichiers indiquent le système le plus ancien sur lequel chaque roue fonctionne, ainsi pip 20.3 ou supérieur refuse immédiatement une version plus ancienne au lieu d'installer un runtime qui ne peut pas démarrer. Les roues jusqu'à la version 26.5 étaient étiquetées `manylinux1_x86_64`, `macosx_10_14_x86_64` et `macosx_11_0_arm64`.

Copiez la roue téléchargée dans le dossier de votre projet et installez‑la avec `pip` :

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

Nommez explicitement le fichier de roue : PowerShell n'expande pas le caractère générique `*` pour une commande native, ainsi `pip install groupdocs_viewer_net-*.whl` échoue dans ce cas.

Sortie attendue :

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
