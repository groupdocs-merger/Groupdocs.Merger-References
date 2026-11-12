---
title: "ISplitOptions"
second_title: "L'espace de noms com.groupdocs.merger.domain.builders fournit des constructeurs."
description: "Interface pour les options de fractionnement."
type: docs
weight: 33
url: /fr/java/com.groupdocs.merger.domain.options.interfaces/isplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IPageOptions](../../com.groupdocs.merger.domain.options.interfaces/ipageoptions)
```
public interface ISplitOptions extends IPageOptions
```

Interface pour les options de fractionnement.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getMode()](#getMode--) | Obtient le mode de division des pages. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valide les options de division. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Obtient le chemin complet du fichier du document divisé par index avec l'extension définie. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Délégué qui définit la méthode pour créer le flux de sortie de division. |
### getMode() {#getMode--}
```
public abstract int getMode()
```


Obtient le mode de division des pages.

**Returns:**
int
### validate(FileType fileType) {#validate-com.groupdocs.merger.domain.FileType-}
```
public abstract void validate(FileType fileType)
```


Valide les options de division.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Le type de fichier de la classe [FileType](../../com.groupdocs.merger.domain/filetype). |

### getPathByIndex(int index, String extension) {#getPathByIndex-int-java.lang.String-}
```
public abstract String getPathByIndex(int index, String extension)
```


Obtient le chemin complet du fichier du document divisé par index avec l'extension définie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int | Index du document divisé. |
| extension | java.lang.String | Extension du fichier. |

**Returns:**
java.lang.String - Le chemin complet du fichier.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public abstract SplitStreamFactory getSplitStreamFactory()
```


Délégué qui définit la méthode pour créer le flux de sortie de division.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
