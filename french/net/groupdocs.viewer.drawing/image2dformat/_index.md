---
title: "Image2DFormat"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Représente les formats d'image 2D les plus courants, prenant en charge les formats raster et vectoriels"
type: docs
weight: 960
url: /fr/net/groupdocs.viewer.drawing/image2dformat/
---

## Image2DFormat structure

Représente les formats d'image 2D les plus courants, prend en charge les formats raster et vectoriel.

```csharp
public struct Image2DFormat : IEquatable<Image2DFormat>
```

## Propriétés

| Nom | Description |
| --- | --- |
| static [Bmp](../../groupdocs.viewer.drawing/image2dformat/bmp) { get; } | Type d'image BMP |
| static [Emf](../../groupdocs.viewer.drawing/image2dformat/emf) { get; } | Type d'image vectorielle EMF (Enhanced MetaFile) |
| static [Gif](../../groupdocs.viewer.drawing/image2dformat/gif) { get; } | Type d'image GIF |
| static [Icon](../../groupdocs.viewer.drawing/image2dformat/icon) { get; } | Type d'image ICON |
| static [Jpeg](../../groupdocs.viewer.drawing/image2dformat/jpeg) { get; } | Type d'image JPEG |
| static [Png](../../groupdocs.viewer.drawing/image2dformat/png) { get; } | Type d'image PNG |
| static [Svg](../../groupdocs.viewer.drawing/image2dformat/svg) { get; } | Type d'image vectorielle SVG |
| static [Tiff](../../groupdocs.viewer.drawing/image2dformat/tiff) { get; } | Type d'image raster TIFF (Tagged Image File Format) |
| static [Undefined](../../groupdocs.viewer.drawing/image2dformat/undefined) { get; } | Type d'image indéfini - valeur spéciale qui ne devrait normalement pas se produire |
| static [Wmf](../../groupdocs.viewer.drawing/image2dformat/wmf) { get; } | Type d'image vectorielle WMF (Windows MetaFile) |
| [FileExtension](../../groupdocs.viewer.drawing/image2dformat/fileextension) { get; } | Extension de fichier (sans le caractère point initial) d'un type d'image particulier en minuscules. Pour la valeur [`Undefined`](./undefined) retourne la chaîne 'undefined'. |
| [IsVector](../../groupdocs.viewer.drawing/image2dformat/isvector) { get; } | Indique si ce format particulier est vectoriel (`true`) ou raster (`false`) |
| [MimeCode](../../groupdocs.viewer.drawing/image2dformat/mimecode) { get; } | Code MIME d'un type d'image particulier sous forme de chaîne. Pour le type Undefined, renvoie la chaîne 'unsefined'. |
| [Name](../../groupdocs.viewer.drawing/image2dformat/name) { get; } | Renvoie un nom officiel de ce format d'image. Ne renvoie jamais NULL. Si l'instance n'est pas corrompue, ne lève jamais d'exception. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [ParseFromFilenameWithExtension](../../groupdocs.viewer.drawing/image2dformat/parsefromfilenamewithextension)(string) | Renvoie la valeur ImageFormat, qui équivaut à l'extension de nom de fichier, extraite du nom de fichier spécifié |
| static [ParseFromMime](../../groupdocs.viewer.drawing/image2dformat/parsefrommime)(string) | Renvoie la valeur [`Image2DFormat`](../image2dformat), qui équivaut au code MIME spécifié |
| [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals)(Image2DFormat) | Détermine si cette instance est égale à l'instance spécifiée \"[`Image2DFormat`](../image2dformat)\" |
| override [Equals](../../groupdocs.viewer.drawing/image2dformat/equals#equals_1)(object) | Détermine si cette instance est égale à l'objet non converti spécifié, qui est probablement une autre instance \"[`Image2DFormat`](../image2dformat)\" |
| override [GetHashCode](../../groupdocs.viewer.drawing/image2dformat/gethashcode)() | Renvoie un code de hachage, qui est un nombre immuable pour cette instance spécifique |
| override [ToString](../../groupdocs.viewer.drawing/image2dformat/tostring)() | Renvoie la propriété [`Name`](./name) |
| [operator ==](../../groupdocs.viewer.drawing/image2dformat/op_equality) | Définit si deux instances spécifiques de [`Image2DFormat`](../image2dformat) sont égales |
| [operator !=](../../groupdocs.viewer.drawing/image2dformat/op_inequality) | Définit si deux instances spécifiques de [`Image2DFormat`](../image2dformat) ne sont pas égales |

### Voir aussi

* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
