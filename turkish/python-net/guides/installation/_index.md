---
title: "Kurulum"
linkTitle: "Installation"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Windows, Linux veya macOS üzerinde .NET aracılığıyla GroupDocs.Viewer for Python'ı kurun — PyPI'dan veya önceden indirilmiş bir wheel'dan, Intel ve Apple Silicon sürümleri dahil."
type: docs
url: /tr/python-net/guides/installation/
is_root: false
weight: 10
---


Kurulumdan önce, desteklenen Python sürümleri ve platform bağımlılıkları için [System Requirements]() kontrol edin.

## Install Package from PyPI

Kütüphane, [PyPI](https://pypi.org/project/groupdocs-viewer-net/) üzerinde **`groupdocs-viewer-net`** olarak yayınlanmıştır. `pip` sisteminiz için doğru platforma özgü tekerleği otomatik olarak seçer.

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

Şu benzeri bir çıktı görmelisiniz:

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

Tam tekerlek adı, işletim sisteminiz ve CPU mimarinizine bağlıdır — tam liste için Sistem Gereksinimleri'ndeki [wheel-suffix table]() sayfasına bakın.

## Add the Package to `requirements.txt`

Bağımlılığı projenizin `requirements.txt` dosyasına ekleyin:

```text
groupdocs-viewer-net
```

Ardından dosyadan kurun:

```bash
pip install -r requirements.txt
```

Tekrarlanabilir derlemeler için belirli bir sürüme sabitleyin — örneğin, `groupdocs-viewer-net==26.9.0`.

## Install from a Pre-Downloaded Wheel

Havadan izole veya kontrol edilen ortamlar için, tekerleği [GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) sitesinden veya [PyPI release page](https://pypi.org/project/groupdocs-viewer-net/#files) sayfasından indirip doğrudan kurun. Her sürümde dört platforma özgü tekerlek yayınlanır; ana bilgisayarınıza uyanı seçin:

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux_2_27_x86_64.whl` (glibc 2.27 or newer)
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_arm64.whl` (macOS 12 or newer)
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_x86_64.whl` (macOS 12 or newer)

26.9 sürümünden itibaren dosya adları, her tekerleğin çalıştığı en eski sistemi belirtir, bu yüzden pip 20.3 veya daha yeni sürümler, baştan bir eski tekerleği reddeder ve başlatılamayan bir çalışma zamanını kurmaz. 26.5'e kadar olan tekerlekler `manylinux1_x86_64`, `macosx_10_14_x86_64` ve `macosx_11_0_arm64` olarak etiketlenmişti.

İndirilen tekerleği proje klasörünüze kopyalayın ve `pip` ile kurun:

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

Tekerlek dosyasını açıkça adlandırın: PowerShell, yerel bir komut için `*` joker karakterini genişletmez, bu yüzden `pip install groupdocs_viewer_net-*.whl` burada başarısız olur.

Beklenen çıktı:

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
