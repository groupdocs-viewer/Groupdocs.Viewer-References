---
title: "Page"
second_title: "GroupDocs.Viewer per .NET API Reference"
description: "Inizializza una nuova istanza della classe Pagegroupdocs.viewer.results/page."
type: docs
weight: 10
url: /it/net/groupdocs.viewer.results/page/page/
---

## Page() {#constructor}

Inizializza una nuova istanza della classe [`Page`](../../page).

```csharp
public Page()
```

### Vedi anche

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

Inizializza una nuova istanza della classe [`Page`](../../page).

```csharp
public Page(int number, bool visible)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| numero | Int32 | Il numero della pagina. |
| visibile | Boolean | L'indicatore di visibilità della pagina. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato quando *number* è minore o uguale a zero. |

### Vedi anche

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

Inizializza una nuova istanza della classe [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| numero | Int32 | Il numero della pagina. |
| nome | Stringa | Il nome del foglio di lavoro o della pagina. |
| visibile | Boolean | L'indicatore di visibilità della pagina. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato quando *number* è minore o uguale a zero. |

### Vedi anche

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

Inizializza una nuova istanza della classe [`Page`](../../page).

```csharp
public Page(int number, bool visible, int width, int height)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| numero | Int32 | Il numero della pagina. |
| visibile | Boolean | L'indicatore di visibilità della pagina. |
| larghezza | Int32 | La larghezza della pagina in pixel quando visualizzata come JPG o PNG. |
| altezza | Int32 | L'altezza della pagina in pixel quando visualizzata come JPG o PNG. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato quando *number* è minore o uguale a zero. |
| ArgumentException | Generato quando *larghezza* è minore o uguale a zero. |
| ArgumentException | Generato quando *altezza* è minore o uguale a zero. |

### Vedi anche

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

Inizializza una nuova istanza della classe [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| numero | Int32 | Il numero della pagina. |
| nome | Stringa | Il nome del foglio di lavoro o della pagina. |
| visibile | Boolean | L'indicatore di visibilità della pagina. |
| larghezza | Int32 | La larghezza della pagina in pixel quando visualizzata come JPG o PNG. |
| altezza | Int32 | L'altezza della pagina in pixel quando visualizzata come JPG o PNG. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato quando *number* è minore o uguale a zero. |
| ArgumentException | Generato quando *larghezza* è minore o uguale a zero. |
| ArgumentException | Generato quando *altezza* è minore o uguale a zero. |

### Vedi anche

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

Inizializza una nuova istanza della classe [`Page`](../../page).

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| numero | Int32 | Il numero della pagina. |
| visibile | Boolean | L'indicatore di visibilità della pagina. |
| larghezza | Int32 | La larghezza della pagina in pixel quando visualizzata come JPG o PNG. |
| altezza | Int32 | L'altezza della pagina in pixel quando visualizzata come JPG o PNG. |
| righe | List`1 | Le linee contenute nella pagina quando visualizzata come JPG o PNG con estrazione del testo abilitata. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato quando *number* è minore o uguale a zero. |
| ArgumentException | Generato quando *larghezza* è minore o uguale a zero. |
| ArgumentException | Generato quando *altezza* è minore o uguale a zero. |
| ArgumentNullException | Generato quando *lines* è null. |

### Vedi anche

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

Inizializza una nuova istanza della classe [`Page`](../../page).

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| numero | Int32 | Il numero della pagina. |
| nome | Stringa | Il nome del foglio di lavoro o della pagina. |
| visibile | Boolean | L'indicatore di visibilità della pagina. |
| larghezza | Int32 | La larghezza della pagina in pixel quando visualizzata come JPG o PNG. |
| altezza | Int32 | L'altezza della pagina in pixel quando visualizzata come JPG o PNG. |
| righe | List`1 | Le linee contenute nella pagina quando visualizzata come JPG o PNG con estrazione del testo abilitata. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato quando *number* è minore o uguale a zero. |
| ArgumentException | Generato quando *larghezza* è minore o uguale a zero. |
| ArgumentException | Generato quando *altezza* è minore o uguale a zero. |
| ArgumentNullException | Generato quando *lines* è null. |

### Vedi anche

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
