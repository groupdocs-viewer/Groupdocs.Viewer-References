---
title: "FontStyles"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Stellt 4 mögliche Stile der im Dokument verwendeten Schriftart dar: Regular, Bold, Italic oder Bold Italic"
type: docs
weight: 810
url: /de/net/groupdocs.viewer.fonts/fontstyles/
---

## FontStyles structure

Stellt 4 mögliche Schriftstile dar, die im Dokument verwendet werden: Regular, Bold, Italic oder Bold Italic

```csharp
public struct FontStyles : IEquatable<FontStyles>
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FontStyles](fontstyles)(bool, bool) | Erstellt eine [`FontStyles`](../fontstyles)‑Instanz aus den angegebenen Bold‑ und Italic‑Flags |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [IsBold](../../groupdocs.viewer.fonts/fontstyles/isbold) { get; } | Gibt an, ob diese [`FontStyles`](../fontstyles)‑Instanz ein **bold**‑Flag aktiviert (`true`) oder deaktiviert (`false`) hat |
| [IsItalic](../../groupdocs.viewer.fonts/fontstyles/isitalic) { get; } | Gibt an, ob diese [`FontStyles`](../fontstyles)‑Instanz ein **italic**‑Flag aktiviert (`true`) oder deaktiviert (`false`) hat |
| [Name](../../groupdocs.viewer.fonts/fontstyles/name) { get; } | Name dieses Schriftartstils |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals)(FontStyles) | Gibt an, ob diese [`FontStyles`](../fontstyles)‑Instanz dem angegebenen entspricht |
| override [Equals](../../groupdocs.viewer.fonts/fontstyles/equals#equals_1)(object) | Gibt an, ob diese [`FontStyles`](../fontstyles)‑Instanz dem angegebenen, nicht gecasteten Wert entspricht |
| override [GetHashCode](../../groupdocs.viewer.fonts/fontstyles/gethashcode)() | Gibt einen Hashcode dieser Instanz zurück |
| override [ToString](../../groupdocs.viewer.fonts/fontstyles/tostring)() | Gibt einen Namen dieses Schriftstils zurück, derselbe wie [`Name`](./name) |
| static [TryParse](../../groupdocs.viewer.fonts/fontstyles/tryparse)(string, out FontStyles) | Versucht, die angegebene Rohzeichenkette als Schriftstilnamen zu parsen |
| [operator +](../../groupdocs.viewer.fonts/fontstyles/op_addition) | Kombiniert (vereinigt) zwei angegebene Schriftstile und erzeugt einen neuen resultierenden Schriftstil, bei dem die Flags zusammengeführt werden (Vereinigung) |
| [operator ==](../../groupdocs.viewer.fonts/fontstyles/op_equality) | Prüft, ob zwei [`FontStyles`](../fontstyles)-Werte gleich sind |
| [explicit operator](../../groupdocs.viewer.fonts/fontstyles/op_explicit) | Wandelt die angegebene [`FontStyles`](../fontstyles)-Instanz in das entsprechende Oktett (8‑Bit‑Bitfeld) im Dezimalbereich [0..3] um |
| [operator !=](../../groupdocs.viewer.fonts/fontstyles/op_inequality) | Prüft, ob zwei [`FontStyles`](../fontstyles)-Werte ungleich sind |
| [operator -](../../groupdocs.viewer.fonts/fontstyles/op_subtraction) | Subtrahiert den zweiten (Subtrahenden) angegebenen Schriftstil vom ersten (Minuenden) angegebenen Schriftstil und erzeugt einen neuen resultierenden Schriftstil, bei dem nur jene Flags des ersten Operanden enthalten sind, die im zweiten Operanden nicht vorkommen (Differenz) |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Bold](../../groupdocs.viewer.fonts/fontstyles/bold) | Fetter Schriftstil (nur fett, ohne kursiv) |
| static readonly [BoldItalic](../../groupdocs.viewer.fonts/fontstyles/bolditalic) | BoldItalic-Schriftstil (fett und kursiv zusammen) |
| static readonly [Italic](../../groupdocs.viewer.fonts/fontstyles/italic) | Kursiv-Schriftstil (nur kursiv, ohne fett) |
| static readonly [Regular](../../groupdocs.viewer.fonts/fontstyles/regular) | Regulärer Schriftstil, Standardwert (kein fett und kein kursiv) |

### Bemerkungen

Unveränderliche Struktur mit praktischer API und Kombinationsoperationen

### Siehe auch

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
