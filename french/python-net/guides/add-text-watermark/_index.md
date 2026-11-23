---
title: "Ajouter des filigranes texte"
linkTitle: "Add text watermarks"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Ajoutez des filigranes texte aux documents rendus en utilisant GroupDocs.Viewer dans vos applications Python."
type: docs
url: /fr/python-net/guides/add-text-watermark/
is_root: false
weight: 80
---


Pour ajouter un filigrane à la sortie HTML/JPG/PNG/PDF, suivez ces étapes :

1. Créez une instance de la classe [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) (ou [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/), ou [JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/), ou [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/));
2. Créez un objet [Watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/watermark/) et remplissez ses propriétés ;
3. Appelez la méthode [watermark](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/viewoptions/#properties) de la classe [HtmlViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) (ou [PngViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pngviewoptions/), ou [JpgViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/), ou [PdfViewOptions](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)) et spécifiez l'objet créé à l'étape 2 ;
4. Appelez la méthode [Viewer.view()](https://reference.groupdocs.com/viewer/python-net/groupdocs.viewer/viewer/#methods).

L'extrait de code suivant montre comment appliquer le filigrane aux pages de sortie.

{{< tabs \"example1\">}}
{{< tab \"Python\" >}}
```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # Charger le document
    with Viewer("sample.docx") as viewer:
        # Créer un fichier HTML.
        viewOptions = HtmlViewOptions.for_embedded_resources("add_text_watermark/output-watermark.html")
        # Ajouter un filigrane.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```
{{< /tab >}}
{{< tab \"sample.docx\" >}}

`sample.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/viewer/python-net/_sample_files/developer-guide/rendering-documents/add-text-watermark/sample.docx) pour le télécharger.

{{< /tab >}}
{{< tab "output-watermark.html" >}}
```text
<!DOCTYPE html><html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8" /><meta name="generator" content="Aspose.Words for .NET 26.4.0" /><title>Sample Document ver.1</title><style type="text/css">@font-face { font-family:'Calibri'; font-style:normal; font-weight:normal; src:local('☺'), url('data:application/x-font-woff;base64,d09GRgABAAAAAGlIAA0AAAAA09gAAQAAAAAAAAAAAAAAAAAAAAAAAAAAAABPUy8yAAABMAAAAGAAAABgncM96GNtYXAAAAGQAAACswAABrCp8yKHY3Z0IAAABEQAAAKEAAAFvLlw2DVmcGdtAAAGy
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/viewer/python-net/_output_files/developer-guide/rendering-documents/add-text-watermark/add_text_watermark/output-watermark.html)
{{< /tab >}}
{{< /tabs >}}
