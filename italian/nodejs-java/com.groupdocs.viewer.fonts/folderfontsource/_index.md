---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Rappresenta una cartella che contiene font TrueType."
type: docs
weight: 10
url: /it/nodejs-java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

Rappresenta una cartella che contiene font TrueType.

La classe FolderFontSource è usata per specificare una posizione di cartella che contiene font TrueType. Consente all'API GroupDocs.Viewer di accedere ai font memorizzati nella cartella specificata per scopi di rendering dei documenti.

Esempio di utilizzo:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | Inizializza una nuova istanza della classe FolderFontSource. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Determina se due oggetti FolderFontSource sono gli stessi. |
| [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Determina se due oggetti FolderFontSource non sono gli stessi. |
| [getFolderPath()](#getFolderPath--) | Ottiene il percorso della cartella che contiene i font TrueType. |
| [getSearchOption()](#getSearchOption--) | Ottiene l'opzione di ricerca che specifica se cercare nella cartella corrente, o nella cartella corrente e in tutte le sottocartelle. |
| [isRecursive()](#isRecursive--) | Verifica se i font verrebbero cercati ricorsivamente. |
| [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | Determina se il corrente FolderFontSource è lo stesso dell'oggetto FolderFontSource specificato. |
| [equals(Object o)](#equals-java.lang.Object-) | Determina se il corrente FolderFontSource è lo stesso dell'oggetto specificato. |
| [hashCode()](#hashCode--) | Restituisce il codice hash per l'oggetto corrente FolderFontSource. |
| [toString()](#toString--) | Restituisce una stringa che rappresenta l'oggetto corrente. |
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


Inizializza una nuova istanza della classe FolderFontSource.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderPath | java.lang.String | Percorso della cartella che contiene i font TrueType. |
| searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | Specifica se cercare nella cartella corrente, o nella cartella corrente e in tutte le sottocartelle. |

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


Determina se due oggetti FolderFontSource sono gli stessi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | L'oggetto FolderFontSource di sinistra. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | L'oggetto FolderFontSource di destra. |

**Returns:**
boolean -  true  se entrambi gli oggetti FolderFontSource sono gli stessi; altrimenti,  false .
### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


Determina se due oggetti FolderFontSource non sono gli stessi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | L'oggetto FolderFontSource di sinistra. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | L'oggetto FolderFontSource di destra. |

**Returns:**
boolean -  true  se entrambi gli oggetti FolderFontSource non sono gli stessi; altrimenti,  false .
### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


Ottiene il percorso della cartella che contiene i font TrueType.

**Returns:**
java.lang.String - il percorso della cartella che contiene i font TrueType.
### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


Ottiene l'opzione di ricerca che specifica se cercare nella cartella corrente, o nella cartella corrente e in tutte le sottocartelle.

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.
### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


Verifica se i font verrebbero cercati ricorsivamente.

**Returns:**
boolean -  true  se i font verrebbero cercati ricorsivamente,  false  altrimenti.
### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


Determina se il corrente FolderFontSource è lo stesso dell'oggetto FolderFontSource specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | L'oggetto da confrontare con l'oggetto corrente FolderFontSource. |

**Returns:**
boolean -  true  se entrambi gli oggetti FolderFontSource sono gli stessi; altrimenti,  false
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Determina se il corrente FolderFontSource è lo stesso dell'oggetto specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| o | java.lang.Object | L'oggetto da confrontare con l'oggetto corrente FolderFontSource. |

**Returns:**
boolean -  true  se il parametro  obj  è di tipo FolderFontSource e è lo stesso dell'oggetto corrente FolderFontSource; altrimenti,  false
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce il codice hash per l'oggetto corrente FolderFontSource.

**Returns:**
int - un codice hash per l'oggetto corrente FolderFontSource.
### toString() {#toString--}
```
public String toString()
```


Restituisce una stringa che rappresenta l'oggetto corrente.

**Returns:**
java.lang.String - una stringa che rappresenta l'oggetto corrente.
