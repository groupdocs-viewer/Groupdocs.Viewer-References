---
title: "Εγκατάσταση"
linkTitle: "Installation"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Εγκαταστήστε το GroupDocs.Viewer for Python μέσω .NET σε Windows, Linux ή macOS — από το PyPI ή από προ-κατεβασμένο wheel, συμπεριλαμβανομένων των εκδόσεων για Intel και Apple Silicon."
type: docs
url: /el/python-net/guides/installation/
is_root: false
weight: 10
---


Πριν από την εγκατάσταση, ελέγξτε τις [System Requirements]() για τις υποστηριζόμενες εκδόσεις Python και τις εξαρτήσεις πλατφόρμας.

## Install Package from PyPI

Η βιβλιοθήκη δημοσιεύεται στο [PyPI](https://pypi.org/project/groupdocs-viewer-net/) ως **`groupdocs-viewer-net`**. Το `pip` επιλέγει αυτόματα το σωστό wheel ειδικό για την πλατφόρμα του συστήματός σας.

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

Θα πρέπει να δείτε έξοδο παρόμοια με:

```text
Collecting groupdocs-viewer-net
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl.metadata (6.8 kB)
  Downloading groupdocs_viewer_net-<version>-py3-none-win_amd64.whl (193 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 193/193 MB 2.8 MB/s
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-<version>
```

Το ακριβές όνομα του wheel εξαρτάται από το λειτουργικό σας σύστημα και την αρχιτεκτονική CPU — δείτε τον πίνακα [wheel-suffix table]() στις System Requirements για την πλήρη λίστα.

## Add the Package to `requirements.txt`

Προσθέστε την εξάρτηση στο `requirements.txt` του έργου σας:

```text
groupdocs-viewer-net
```

Στη συνέχεια, εγκαταστήστε από το αρχείο:

```bash
pip install -r requirements.txt
```

Καθορίστε μια συγκεκριμένη έκδοση εάν χρειάζεστε επαναλήψιμες κατασκευές — για παράδειγμα, `groupdocs-viewer-net==26.9.0`.

## Install from a Pre-Downloaded Wheel

Για περιβάλλοντα χωρίς πρόσβαση στο διαδίκτυο ή ελεγχόμενα περιβάλλοντα, κατεβάστε το wheel από τον ιστότοπο [GroupDocs Releases](https://releases.groupdocs.com/viewer/python-net/) ή τη [σελίδα κυκλοφορίας του PyPI](https://pypi.org/project/groupdocs-viewer-net/#files) και εγκαταστήστε το απευθείας. Τέσσερα wheels ειδικά για πλατφόρμες δημοσιεύονται ανά κυκλοφορία· επιλέξτε αυτό που ταιριάζει στον κεντρικό σας υπολογιστή:

- **Windows x86-64** — `groupdocs_viewer_net-<version>-py3-none-win_amd64.whl`
- **Linux x86-64** — `groupdocs_viewer_net-<version>-py3-none-manylinux_2_27_x86_64.whl` (glibc 2.27 or newer)
- **macOS Apple Silicon (ARM64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_arm64.whl` (macOS 12 or newer)
- **macOS Intel (x86-64)** — `groupdocs_viewer_net-<version>-py3-none-macosx_12_0_x86_64.whl` (macOS 12 or newer)

Από την έκδοση 26.9 τα ονόματα των αρχείων δηλώνουν το παλαιότερο σύστημα στο οποίο τρέχει κάθε wheel, έτσι το pip 20.3 ή νεότερο απορρίπτει εκ των προτέρων ένα παλαιότερο wheel αντί να εγκαταστήσει ένα runtime που δεν μπορεί να ξεκινήσει. Τα wheels μέχρι την έκδοση 26.5 είχαν ετικέτες `manylinux1_x86_64`, `macosx_10_14_x86_64` και `macosx_11_0_arm64`.

Αντιγράψτε το ληφθέν wheel στον φάκελο του έργου σας και εγκαταστήστε το με το `pip`:

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

Ονομάστε το αρχείο wheel ρητά: το PowerShell δεν επεκτείνει το σύμβολο μπαλαντέρ `*` για μια εγγενή εντολή, επομένως το `pip install groupdocs_viewer_net-*.whl` αποτυγχάνει εκεί.

Αναμενόμενη έξοδος:

```text
Processing ./groupdocs_viewer_net-26.9.0-py3-none-manylinux_2_27_x86_64.whl
Installing collected packages: groupdocs-viewer-net
Successfully installed groupdocs-viewer-net-26.9.0
```

## Next Steps

- [Quick Start Guide]() — render your first document in five minutes.
- [How to Run Examples]() — clone the runnable examples repository and execute every documented scenario.
- [Agents and LLMs]() — use GroupDocs.Viewer with AI coding assistants through the MCP server and the package-bundled `AGENTS.md`.
