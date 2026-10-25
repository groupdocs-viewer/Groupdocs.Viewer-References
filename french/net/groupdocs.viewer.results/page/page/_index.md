---
title: "Page"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une nouvelle instance de la classe Pagegroupdocs.viewer.results/page."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.results/page/page/
---

## Page() {#constructor}

Initialise une nouvelle instance de la classe [`Page`](../../page).

```csharp
public Page()
```

### Voir aussi

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

Initialise une nouvelle instance de la classe [`Page`](../../page).

```csharp
public Page(int number, bool visible)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nombre | Int32 | Le numéro de la page. |
| visible | Boolean | L'indicateur de visibilité de la page. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancé lorsque *number* est inférieur ou égal à zéro. |

### Voir aussi

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

Initialise une nouvelle instance de la classe [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nombre | Int32 | Le numéro de la page. |
| nom | String | Le nom de la feuille de calcul ou de la page. |
| visible | Boolean | L'indicateur de visibilité de la page. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancé lorsque *number* est inférieur ou égal à zéro. |

### Voir aussi

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

Initialise une nouvelle instance de la classe [`Page`](../../page).

```csharp
public Page(int number, bool visible, int width, int height)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nombre | Int32 | Le numéro de la page. |
| visible | Boolean | L'indicateur de visibilité de la page. |
| largeur | Int32 | La largeur de la page en pixels lors de l'affichage en JPG ou PNG. |
| hauteur | Int32 | La hauteur de la page en pixels lors de l'affichage en JPG ou PNG. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancé lorsque *number* est inférieur ou égal à zéro. |
| ArgumentException | Lancée lorsque *largeur* est inférieure ou égale à zéro. |
| ArgumentException | Lancée lorsque *hauteur* est inférieure ou égale à zéro. |

### Voir aussi

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

Initialise une nouvelle instance de la classe [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nombre | Int32 | Le numéro de la page. |
| nom | String | Le nom de la feuille de calcul ou de la page. |
| visible | Boolean | L'indicateur de visibilité de la page. |
| largeur | Int32 | La largeur de la page en pixels lors de l'affichage en JPG ou PNG. |
| hauteur | Int32 | La hauteur de la page en pixels lors de l'affichage en JPG ou PNG. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancé lorsque *number* est inférieur ou égal à zéro. |
| ArgumentException | Lancée lorsque *largeur* est inférieure ou égale à zéro. |
| ArgumentException | Lancée lorsque *hauteur* est inférieure ou égale à zéro. |

### Voir aussi

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

Initialise une nouvelle instance de la classe [`Page`](../../page).

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nombre | Int32 | Le numéro de la page. |
| visible | Boolean | L'indicateur de visibilité de la page. |
| largeur | Int32 | La largeur de la page en pixels lors de l'affichage en JPG ou PNG. |
| hauteur | Int32 | La hauteur de la page en pixels lors de l'affichage en JPG ou PNG. |
| lignes | List`1 | Les lignes contenues dans la page lors de l'affichage en JPG ou PNG avec extraction de texte activée. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancé lorsque *number* est inférieur ou égal à zéro. |
| ArgumentException | Lancée lorsque *largeur* est inférieure ou égale à zéro. |
| ArgumentException | Lancée lorsque *hauteur* est inférieure ou égale à zéro. |
| ArgumentNullException | Lancé lorsque *lines* est nul. |

### Voir aussi

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

Initialise une nouvelle instance de la classe [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| nombre | Int32 | Le numéro de la page. |
| nom | String | Le nom de la feuille de calcul ou de la page. |
| visible | Boolean | L'indicateur de visibilité de la page. |
| largeur | Int32 | La largeur de la page en pixels lors de l'affichage en JPG ou PNG. |
| hauteur | Int32 | La hauteur de la page en pixels lors de l'affichage en JPG ou PNG. |
| lignes | List`1 | Les lignes contenues dans la page lors de l'affichage en JPG ou PNG avec extraction de texte activée. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancé lorsque *number* est inférieur ou égal à zéro. |
| ArgumentException | Lancée lorsque *largeur* est inférieure ou égale à zéro. |
| ArgumentException | Lancée lorsque *hauteur* est inférieure ou égale à zéro. |
| ArgumentNullException | Lancé lorsque *lines* est nul. |

### Voir aussi

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
