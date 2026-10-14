---
title: "ITextSplitOptions"
second_title: "Référence API de GroupDocs.Merger pour Node.js via Java"
description: "Interface pour les options de division du texte."
type: docs
weight: 35
url: /fr/nodejs-java/com.groupdocs.merger.domain.options.interfaces/itextsplitoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.merger.domain.options.interfaces.IOptions](../../com.groupdocs.merger.domain.options.interfaces/ioptions)
```
public interface ITextSplitOptions extends IOptions
```

Interface pour les options de division du texte.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getLineNumbers()](#getLineNumbers--) | Numéros de ligne pour la division du texte. |
| [getMode()](#getMode--) | Mode de division du texte. |
| [validate(FileType fileType)](#validate-com.groupdocs.merger.domain.FileType-) | Valide les options de division. |
| [getPathByIndex(int index, String extension)](#getPathByIndex-int-java.lang.String-) | Obtient le chemin complet du fichier du document fractionné par index avec l'extension définie. |
| [getSplitStreamFactory()](#getSplitStreamFactory--) | Délégué qui définit la méthode pour créer le flux de division de sortie. |
### getLineNumbers() {#getLineNumbers--}
```
public abstract int[] getLineNumbers()
```


Numéros de ligne pour la division du texte.

**Returns:**
int[]
### getMode() {#getMode--}
```
public abstract int getMode()
```


Mode de division du texte.

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


Obtient le chemin complet du fichier du document fractionné par index avec l'extension définie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| indice | int | Index du document découpé. |
| extension | java.lang.String | Extension du fichier. |

**Returns:**
java.lang.String - Le chemin complet du fichier.
### getSplitStreamFactory() {#getSplitStreamFactory--}
```
public abstract SplitStreamFactory getSplitStreamFactory()
```


Délégué qui définit la méthode pour créer le flux de division de sortie.

**Returns:**
[SplitStreamFactory](../../com.groupdocs.merger.domain.common/splitstreamfactory)
