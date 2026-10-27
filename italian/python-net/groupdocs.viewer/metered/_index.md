---
title: "Classe Metered"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Gestisce la licenza a consumo (pay-per-use)."
type: docs
url: /it/python-net/groupdocs.viewer/metered/
is_root: false
weight: 80
---


## Metered class

Gestisce la licenza a consumo (pay-per-use).

Le licenze Metered fatturano in base al consumo reale (tipicamente pagine o
documenti elaborati). Imposta la coppia di chiavi pubblica/privata una sola volta al
avvio dell'applicazione; il wrapper segnala l'utilizzo al GroupDocs
server di licenza in background.

Il tipo Metered espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [get_consumption_credit](/viewer/python-net/groupdocs.viewer/metered/get_consumption_credit/) | Restituisce il credito residuo metered per la chiave corrente. |
| [get_consumption_quantity](/viewer/python-net/groupdocs.viewer/metered/get_consumption_quantity/) | Restituisce la quantità totale metered consumata finora. |
| [set_metered_key](/viewer/python-net/groupdocs.viewer/metered/set_metered_key/#public_key-private_key) | Attiva la fatturazione metered con la coppia di chiavi pubblica/privata fornita. |

### Vedi anche
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
