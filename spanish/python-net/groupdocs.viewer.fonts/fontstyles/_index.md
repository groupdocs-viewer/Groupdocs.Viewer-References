---
title: "Clase FontStyles"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa 4 estilos posibles de la fuente, utilizados en el documento: Regular, Negrita, Cursiva o Negrita Cursiva."
type: docs
url: /es/python-net/groupdocs.viewer.fonts/fontstyles/
is_root: false
weight: 40
---


## FontStyles class

Representa 4 estilos posibles de la fuente, utilizados en el documento: Regular, Negrita, Cursiva o Negrita Cursiva.

Estructura inmutable con API conveniente y operaciones de combinación.

El tipo FontStyles expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/__init__/#is_bold-is_italic) | Inicializa una instancia de FontStyles a partir de los indicadores de negrita y cursiva especificados. |

### Métodos
| Método | Descripción |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals/#other) | Indica si esta instancia de FontStyles es igual a la instancia especificada. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals/#other) | Indica si esta instancia de [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) es igual al objeto no convertido especificado. |
| [equals_font_styles](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals_font_styles/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/get_hash_code/) | Devuelve un código hash de esta instancia. |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/to_string/) | Devuelve el nombre de este estilo de fuente, igual que [`FontStyles.name`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/name/). |
| [try_parse](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/try_parse/#style-parsed) | Intenta analizar la cadena cruda especificada como un nombre de estilo de fuente. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [is_bold](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/is_bold/) | La propiedad indica si esta instancia de [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) tiene la bandera de negrita habilitada (`True`) o deshabilitada (`False`). |
| [is_italic](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/is_italic/) | El estado de la bandera cursiva de esta instancia de [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/); `True` si está habilitada, `False` si está deshabilitada. |
| [name](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/name/) | El nombre de este estilo de fuente. |

### Campos
| Campo | Descripción |
| :- | :- |
| [REGULAR](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/) | Estilo de fuente regular, valor predeterminado (sin negrita ni cursiva) |
| [BOLD](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/bold/) | Estilo de fuente negrita (solo negrita, sin cursiva) |
| [ITALIC](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/italic/) | Estilo de fuente cursiva (solo cursiva, sin negrita) |
| [BOLD_ITALIC](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/bold_italic/) | Estilo de fuente BoldItalic (negrita y cursiva juntos) |

### Ver también
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
