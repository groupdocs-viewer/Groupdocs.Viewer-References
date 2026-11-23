---
title: "FontStyles"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Representa 4 estilos posibles de la fuente utilizados en el documento Regular Bold Italic o Bold Italic"
type: docs
weight: 810
url: /es/net/groupdocs.viewer.fonts/fontstyles/
---

## FontStyles structure

Representa 4 estilos posibles de la fuente, utilizados en el documento: Regular, Negrita, Cursiva o Negrita Cursiva.

```csharp
public struct FontStyles : IEquatable<FontStyles>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FontStyles](fontstyles)(bool, bool) | Crea una instancia de [`FontStyles`](../fontstyles) a partir de los indicadores de negrita y cursiva especificados |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsBold](../../groupdocs.viewer.fonts/fontstyles/isbold) { get; } | Indica si esta instancia de [`FontStyles`](../fontstyles) tiene la bandera **bold** activada (`true`) o desactivada (`false`) |
| [IsItalic](../../groupdocs.viewer.fonts/fontstyles/isitalic) { get; } | Indica si esta instancia de [`FontStyles`](../fontstyles) tiene la bandera **italic** activada (`true`) o desactivada (`false`) |
| [Name](../../groupdocs.viewer.fonts/fontstyles/name) { get; } | Nombre de este estilo de fuente |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals)(FontStyles) | Indica si esta instancia de [`FontStyles`](../fontstyles) es igual a la especificada |
| override [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals_1)(object) | Indica si esta instancia de [`FontStyles`](../fontstyles) es igual a la especificada sin conversión |
| override [GetHashCode](../../groupdocs.viewer.fonts/fontstyles/gethashcode)() | Devuelve un código hash de esta instancia |
| override [ToString](../../groupdocs.viewer.fonts/fontstyles/tostring)() | Devuelve el nombre de este estilo de fuente, igual que [`Name`](./name) |
| static [TryParse](../../groupdocs.viewer.fonts/fontstyles/tryparse)(string, out FontStyles) | Intenta analizar la cadena cruda especificada como un nombre de estilo de fuente |
| [operator +](../../groupdocs.viewer.fonts/fontstyles/op_addition) | Combina (fusiona) dos estilos de fuente especificados y produce un nuevo estilo de fuente resultante, donde las banderas se combinan (unión) |
| [operator ==](../../groupdocs.viewer.fonts/fontstyles/op_equality) | Comprueba si dos valores de [`FontStyles`](../fontstyles) son iguales |
| [explicit operator](../../groupdocs.viewer.fonts/fontstyles/op_explicit) | Convierte la instancia de [`FontStyles`](../fontstyles) especificada al octeto equivalente (campo de bits de 8 bits) en el rango decimal [0..3] |
| [operator !=](../../groupdocs.viewer.fonts/fontstyles/op_inequality) | Comprueba si dos valores de [`FontStyles`](../fontstyles) no son iguales |
| [operator -](../../groupdocs.viewer.fonts/fontstyles/op_subtraction) | Resta el segundo estilo de fuente especificado (sustraendo) del primer estilo de fuente especificado (minuendo) y produce un nuevo estilo de fuente resultante, donde solo están presentes aquellas banderas del primer operando que no se encuentran en el segundo operando (diferencia) |

## Campos

| Nombre | Descripción |
| --- | --- |
| static readonly [Bold](../../groupdocs.viewer.fonts/fontstyles/bold) | Estilo de fuente negrita (solo negrita, sin cursiva) |
| static readonly [BoldItalic](../../groupdocs.viewer.fonts/fontstyles/bolditalic) | Estilo de fuente negrita cursiva (negrita y cursiva juntas) |
| static readonly [Italic](../../groupdocs.viewer.fonts/fontstyles/italic) | Estilo de fuente cursiva (solo cursiva, sin negrita) |
| static readonly [Regular](../../groupdocs.viewer.fonts/fontstyles/regular) | Estilo de fuente regular, valor predeterminado (sin negrita ni cursiva) |

### Observaciones

Estructura inmutable con API conveniente y operaciones de combinación

### Ver también

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
