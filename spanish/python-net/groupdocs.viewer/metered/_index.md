---
title: "Clase Metered"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Gestiona la licencia por consumo (pago por uso)."
type: docs
url: /es/python-net/groupdocs.viewer/metered/
is_root: false
weight: 80
---


## Metered class

Gestiona la licencia por consumo (pago por uso).

Las licencias Metered facturan según el consumo real (normalmente páginas o
documentos procesados). Establezca el par de claves pública/privada una vez en
el inicio de la aplicación; el contenedor informa del uso al
servidor de licencias en segundo plano.

El tipo Metered expone los siguientes miembros:

### Métodos
| Método | Descripción |
| :- | :- |
| [get_consumption_credit](/viewer/python-net/groupdocs.viewer/metered/get_consumption_credit/) | Devuelve el crédito restante de facturación por uso para la clave actual. |
| [get_consumption_quantity](/viewer/python-net/groupdocs.viewer/metered/get_consumption_quantity/) | Devuelve la cantidad total facturada consumida hasta ahora. |
| [set_metered_key](/viewer/python-net/groupdocs.viewer/metered/set_metered_key/#public_key-private_key) | Active la facturación por uso con el par de claves pública/privada proporcionado. |

### Ver también
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
