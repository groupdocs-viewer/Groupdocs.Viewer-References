---
title: "Méthode for_external_resources"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de la classe HtmlViewOptions pour le rendu en HTML avec des ressources externes."
type: docs
url: /fr/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

Initialise une instance de la classe [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) pour le rendu en HTML avec des ressources externes.

Pour l'exemple de code, consultez la documentation.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | La méthode qui instancie le flux utilisé pour écrire les données de la page de sortie. |
| create_resource_stream | `CreateResourceStream` | La méthode qui libère le flux créé par la méthode `create_page_stream`. |
| create_resource_url | `CreateResourceUrl` | La méthode qui crée l'URL pour la ressource HTML. |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `create_resource_url` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("sample.docx") as viewer:
    options = HtmlViewOptions.for_external_resources(
        "page_{0}.html",
        "page_{0}/resource_{0}_{1}",
        "page_{0}/resource_{0}_{1}"
    )
    viewer.view(options)
```

## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url-release_page_stream-release_resource_stream}

Initialise une instance de la classe HtmlViewOptions pour le rendu en HTML avec des ressources externes.

Pour des exemples d'utilisation supplémentaires, consultez la documentation de GroupDocs Viewer.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | La méthode qui instancie un flux utilisé pour écrire les données de page de sortie. |
| create_resource_stream | `CreateResourceStream` | La méthode qui instancie un flux utilisé pour écrire les données de la ressource HTML de sortie. |
| create_resource_url | `CreateResourceUrl` | La méthode qui crée une URL pour une ressource HTML. |
| release_page_stream | `ReleasePageStream` | La méthode qui libère le flux créé par le délégué passé à `create_page_stream`. |
| release_resource_stream | `ReleaseResourceStream` | La méthode qui libère le flux créé par le délégué passé à `create_resource_stream`. |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `release_resource_stream` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # Charger la feuille de calcul Excel
    with Viewer("invoice.xlsx") as viewer:
        # Convertir la feuille de calcul en HTML avec des ressources externes.
        # {0} et {1} sont remplacés respectivement par le numéro de page actuel et le nom de la ressource.
        view_options = HtmlViewOptions.for_external_resources(
            "render_excel_to_html_external/pdf_page_{0}.html",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}"
        )
        viewer.view(view_options)

if __name__ == "__main__":
    render_excel_to_html_external()
```

## for_external_resources {#page_stream_factory-resource_stream_factory}

Initialise une instance de HtmlViewOptions pour le rendu en HTML avec des ressources externes.

Pour plus de détails, consultez la documentation en ligne.

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | La fabrique qui implémente les méthodes de création et de libération du flux de page de sortie. |
| resource_stream_factory | `IResourceStreamFactory` | La fabrique qui implémente les méthodes requises pour créer les URL de ressources, instancier et libérer les flux de ressources HTML de sortie. |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `resource_stream_factory` est None. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Créez un fichier HTML pour chaque page et stockez les ressources externes séparément.
    # {0} et {1} sont remplacés respectivement par le numéro de page actuel et le nom de la ressource.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

## for_external_resources

Initialise une instance de HtmlViewOptions configurée pour générer des fichiers HTML avec des ressources externes.

L'instance utilise les chaînes de format fournies :
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

Les fichiers de sortie sont placés dans le répertoire de travail actuel de l'application.

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html_external():
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html_external()
```

## for_external_resources {#file_path_format-resource_file_path_format-resource_url_format}

Initialise une instance de la classe [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/).

Pour l'exemple de code, consultez la documentation.

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path_format | `str` | Le format du chemin de fichier, par ex. `'page_{0}.html'`. |
| resource_file_path_format | `str` | Le format du chemin du fichier de ressources, par ex. `'page_{0}/resource_{1}'`. |
| resource_url_format | `str` | Le format de l'URL de ressource, par ex. `'page_{0}/resource_{1}'`. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `resource_url_format` est None ou vide. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Chargez un document et rendez chaque page dans un fichier HTML avec des ressources externes.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

### Voir aussi
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
