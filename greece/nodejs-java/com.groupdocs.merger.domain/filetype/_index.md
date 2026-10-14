---
title: "FileType"
second_title: "GroupDocs.Merger για Node.js μέσω Java API Reference"
description: "Αναπαριστά τύπο αρχείου."
type: docs
weight: 10
url: /el/nodejs-java/com.groupdocs.merger.domain/filetype/
---
**Inheritance:**
java.lang.Object
```
public final class FileType
```

Αντιπροσωπεύει τον τύπο αρχείου. Παρέχει μεθόδους για την λήψη λίστας όλων των τύπων αρχείων που υποστηρίζονται από **GroupDocs.Merger**, ανίχνευση τύπου αρχείου με βάση την επέκταση κ.ά.

--------------------

**Learn more**

 *  Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats][]
 *  Learn more about getting supported file types in code: [How to get supported file formats in code][]


[Full list of supported document formats]: https://docs.groupdocs.com/display/mergernet/Supported+Document+Types
[How to get supported file formats in code]: https://docs.groupdocs.com/display/mergernet/Get+supported+file+types
## Fields

| Field | Περιγραφή |
| --- | --- |
| [Unknown](#Unknown) | Αντιπροσωπεύει άγνωστο τύπο αρχείου. |
| [ZIP](#ZIP) | Συμπιεσμένο αρχείο (.zip) |
| [SevenZ](#SevenZ) | Αρχείο συμπιεσμένο με 7-Zip (.7z) |
| [TAR](#TAR) | Συγκεντρωτικό αρχείο Unix (.tar) |
| [RAR](#RAR) | Συμπιεσμένο αρχείο Roshal Archive (.rar) |
| [VSSX](#VSSX) | Visio Stencil File (.vssx) είναι στένσιλ σχεδίασης που δημιουργήθηκαν με το Microsoft Visio 2013 και νεότερες εκδόσεις. |
| [VSDX](#VSDX) | Visio Drawing (.vsdx) αντιπροσωπεύει τη μορφή αρχείου Microsoft Visio που εισήχθη από το Microsoft Office 2013 και μετά. |
| [VSDM](#VSDM) | Visio Macro-Enabled Drawing (.vsdm) είναι αρχεία σχεδίασης που δημιουργήθηκαν με την εφαρμογή Microsoft Visio που υποστηρίζει μακροεντολές. |
| [VSTX](#VSTX) | Visio Drawing Template (.vstx) είναι αρχεία προτύπων σχεδίασης που δημιουργήθηκαν με το Microsoft Visio 2013 και νεότερες εκδόσεις. |
| [VSTM](#VSTM) | Visio Macro-Enabled Drawing Template (.vstm) είναι αρχεία προτύπων που δημιουργήθηκαν με το Microsoft Visio και υποστηρίζουν μακροεντολές. |
| [VSSM](#VSSM) | Visio Macro-Enabled Stencil File (.vssm) είναι αρχεία Stencil του Microsoft Visio που παρέχουν υποστήριξη για μακροεντολές. |
| [VSX](#VSX) | Visio Stencil XML File (.vsx) αναφέρεται σε στένσιλ που αποτελούνται από σχέδια και σχήματα που χρησιμοποιούνται για τη δημιουργία διαγραμμάτων στο Microsoft Visio. |
| [VTX](#VTX) | Visio Template XML File (.vtx) είναι ένα πρότυπο σχεδίασης Microsoft Visio που αποθηκεύεται στο δίσκο σε μορφή αρχείου XML. |
| [VDX](#VDX) | Visio Drawing XML File (.vdx) είναι ένα σχέδιο ή διάγραμμα που δημιουργήθηκε στο Microsoft Visio, αλλά αποθηκεύεται σε μορφή XML με επέκταση .VDX. |
| [EPUB](#EPUB) | Open eBook File (.epub) είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυποποιημένο ψηφιακό φορμά δημοσίευσης για εκδότες και καταναλωτές. |
| [BMP](#BMP) | Bitmap Image File (.bmp) αντιπροσωπεύει αρχεία που χρησιμοποιούνται για την αποθήκευση ψηφιακών bitmap εικόνων. |
| [JPG](#JPG) | JPEG Εικόνα (.jpg) |
| [JPEG](#JPEG) | JPEG Image (.jpeg) είναι ένας τύπος μορφής εικόνας που αποθηκεύεται χρησιμοποιώντας τη μέθοδο της απώλειας συμπίεσης. |
| [PNG](#PNG) | Portable Network Graphic (.png) είναι ένας τύπος μορφής αρχείου raster εικόνας που χρησιμοποιεί συμπίεση χωρίς απώλειες. |
| [PS](#PS) | PostScript Αρχείο (.ps) |
| [TIF](#TIF) | Αρχείο Tagged Image (.tif) |
| [TIFF](#TIFF) | Μορφή αρχείου Tagged Image (.tiff) |
| [GIF](#GIF) | Αρχείο Graphical Interchange Format (.gif) |
| [SVG](#SVG) | Αρχείο Scalable Vector Graphics (.svg) |
| [SVGZ](#SVGZ) | Συμπιεσμένο αρχείο Scalable Vector Graphics (.svgz) |
| [EMF](#EMF) | Αναβαθμισμένο Μετααρχείο Windows (.emf) |
| [EMZ](#EMZ) | Συμπιεσμένο Αναβαθμισμένο Μετααρχείο Windows (.emz) |
| [HTML](#HTML) | Αρχείο Hypertext Markup Language (.html) είναι η επέκταση για ιστοσελίδες που δημιουργούνται για εμφάνιση σε προγράμματα περιήγησης. |
| [MHT](#MHT) | Το MHTML Web Archive (.mht) είναι μορφή αρχείου ιστοσελίδας που μπορεί να δημιουργηθεί από έναν αριθμό διαφορετικών εφαρμογών. |
| [MHTML](#MHTML) | Το MIME HTML File (.mhtml) είναι μορφή αρχείου ιστοσελίδας που μπορεί να δημιουργηθεί από έναν αριθμό διαφορετικών εφαρμογών. |
| [ONE](#ONE) | Αρχεία OneNote Document (.one) δημιουργούνται από την εφαρμογή Microsoft OneNote. |
| [PDF](#PDF) | Το Portable Document Format File (.pdf) είναι μορφή αρχείου που εισήχθη ως πρότυπο για την αναπαράσταση εγγράφων και άλλου αναφοράς υλικού σε μορφή ανεξάρτητη από λογισμικό εφαρμογών, υλικό καθώς και λειτουργικό σύστημα. |
| [XPS](#XPS) | Το XML Paper Specification File (.xps) αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. |
| [TEX](#TEX) | Το LaTeX Source Document (.tex) είναι μια γλώσσα που περιλαμβάνει προγραμματισμό καθώς και δυνατότητες σήμανσης, χρησιμοποιείται για τη στοιχειοθέτηση εγγράφων. |
| [PPT](#PPT) | Το PowerPoint Presentation (.ppt) αντιπροσωπεύει αρχείο PowerPoint που αποτελείται από μια συλλογή διαφανειών για προβολή ως παρουσίαση (SlideShow). |
| [PPTX](#PPTX) | Το PowerPoint Open XML Presentation (.pptx) είναι αρχείο παρουσίασης που δημιουργήθηκε με τη δημοφιλή εφαρμογή Microsoft PowerPoint. |
| [PPS](#PPS) | Το PowerPoint Slide Show (.pps) είναι αρχείο που δημιουργήθηκε με τη Microsoft PowerPoint για σκοπό παρουσίασης (Slide Show). |
| [PPSX](#PPSX) | Το PowerPoint Open XML Slide Show (.ppsx) είναι αρχείο που δημιουργήθηκε με τη Microsoft PowerPoint 2007 και νεότερες εκδόσεις για σκοπό παρουσίασης (Slide Show). |
| [ODP](#ODP) | Το OpenDocument Presentation (.odp) αντιπροσωπεύει μορφή αρχείου παρουσίασης που χρησιμοποιείται από το OpenOffice.org στο πρότυπο OASISOpen. |
| [OTP](#OTP) | Το OpenDocument Presentation Template (.otp) αντιπροσωπεύει αρχεία προτύπων παρουσίασης που δημιουργούνται από εφαρμογές στη μορφή προτύπου OASIS OpenDocument. |
| [XLS](#XLS) | Το Excel Spreadsheet (.xls) είναι αρχείο που μπορεί να δημιουργηθεί από το Microsoft Excel καθώς και από άλλα παρόμοια προγράμματα λογιστικών φύλλων όπως το OpenOffice Calc ή το Apple Numbers. |
| [XLSX](#XLSX) | Το Microsoft Excel Open XML Spreadsheet (.xlsx) είναι μια γνωστή μορφή για έγγραφα Microsoft Excel που εισήχθη από τη Microsoft με την κυκλοφορία του Microsoft Office 2007. |
| [XLSM](#XLSM) | Το Excel Open XML Macro-Enabled Spreadsheet (.xlsm) είναι ένας τύπος αρχείων λογιστικού φύλλου που υποστηρίζουν μακροεντολές. |
| [XLSB](#XLSB) | Η μορφή αρχείου Excel Binary Spreadsheet (.xlsb) καθορίζει το Excel Binary File Format, το οποίο είναι μια συλλογή εγγραφών και δομών που καθορίζουν το περιεχόμενο του βιβλίου εργασίας Excel. |
| [CSV](#CSV) | Το Comma Separated Values File (.csv) αντιπροσωπεύει αρχεία απλού κειμένου που περιέχουν εγγραφές δεδομένων με τιμές διαχωρισμένες με κόμμα. |
| [TSV](#TSV) | Το Tab Separated Values File (.tsv) αντιπροσωπεύει δεδομένα διαχωρισμένα με καρτέλες σε μορφή απλού κειμένου. |
| [ODS](#ODS) | OpenDocument Spreadsheet (.ods). |
| [XLTM](#XLTM) | Το Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) αντιπροσωπεύει αρχεία που δημιουργούνται από το Microsoft Excel ως αρχεία προτύπου με ενεργοποιημένες μακροεντολές. |
| [XLTX](#XLTX) | Τα Excel Open XML Spreadsheet Template (.xltx) αρχεία βασίζονται στις προδιαγραφές μορφής αρχείου Office OpenXML. |
| [XLT](#XLT) | Τα Excel Template File (.xlt) είναι αρχεία προτύπου που δημιουργούνται με το Microsoft Excel, το οποίο είναι μια εφαρμογή λογιστικών φύλλων που περιλαμβάνεται στο πακέτο Microsoft Office. |
| [XLAM](#XLAM) | Πρόσθετο Excel με δυνατότητα μακροεντολών (.xlam). |
| [DOC](#DOC) | Το έγγραφο Microsoft Word (.doc) αντιπροσωπεύει έγγραφα που δημιουργούνται από το Microsoft Word ή άλλα προγράμματα επεξεργασίας κειμένου σε δυαδική μορφή αρχείου. |
| [DOCX](#DOCX) | Το έγγραφο Microsoft Word Open XML (.docx) είναι μια γνωστή μορφή για έγγραφα Microsoft Word. |
| [DOCM](#DOCM) | Τα αρχεία Word Open XML με δυνατότητα μακροεντολών (.docm) είναι έγγραφα που δημιουργήθηκαν από το Microsoft Word 2007 ή νεότερο, με δυνατότητα εκτέλεσης μακροεντολών. |
| [DOT](#DOT) | Τα αρχεία προτύπου εγγράφου Word (.dot) είναι αρχεία προτύπου που δημιουργήθηκαν από το Microsoft Word για να έχουν προ-μορφοποιημένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOC ή DOCX. |
| [DOTX](#DOTX) | Το πρότυπο εγγράφου Word Open XML (.dotx) είναι αρχεία προτύπου που δημιουργήθηκαν από το Microsoft Word για να έχουν προ-μορφοποιημένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOCX. |
| [DOTM](#DOTM) | Το πρότυπο εγγράφου Word Open XML με δυνατότητα μακροεντολών (.dotm) αντιπροσωπεύει αρχείο προτύπου που δημιουργήθηκε με το Microsoft Word 2007 ή νεότερο. |
| [RTF](#RTF) | Το αρχείο Rich Text Format (.rtf), που εισήχθη και τεκμηριώθηκε από τη Microsoft, το Rich Text Format (RTF) αντιπροσωπεύει μια μέθοδο κωδικοποίησης μορφοποιημένου κειμένου και γραφικών για χρήση σε εφαρμογές. |
| [TXT](#TXT) | Το αρχείο απλού κειμένου (.txt) αντιπροσωπεύει ένα έγγραφο κειμένου που περιέχει απλό κείμενο με μορφή γραμμών. |
| [ERR](#ERR) | Το αρχείο καταγραφής σφαλμάτων (.err) είναι ένα αρχείο κειμένου που περιέχει μηνύματα σφάλματος που δημιουργήθηκαν από ένα πρόγραμμα. |
| [ODT](#ODT) | Τα αρχεία OpenDocument Text Document (.odt) είναι τύπος εγγράφων που δημιουργούνται με εφαρμογές επεξεργασίας κειμένου που βασίζονται στη μορφή αρχείου OpenDocument Text. |
| [OTT](#OTT) | Τα πρότυπα εγγράφων OpenDocument (.ott) αντιπροσωπεύουν έγγραφα προτύπου που δημιουργούνται από εφαρμογές σύμφωνα με το πρότυπο μορφής OpenDocument του OASIS. |
| [WAV](#WAV) | Το WAV, γνωστό για το WAVE (Waveform Audio File Format), είναι ένα υποσύνολο της προδιαγραφής Resource Interchange File Format (RIFF) της Microsoft\\u2019s για την αποθήκευση ψηφιακών αρχείων ήχου. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Όνομα τύπου αρχείου π.χ. |
| [getExtension()](#getExtension--) | Κατάληξη ονόματος αρχείου (συμπεριλαμβανομένου του σημείου \".\") π.χ. |
| [fromExtension(String extension)](#fromExtension-java.lang.String-) | Αντιστοιχίζει την επέκταση αρχείου με τον τύπο αρχείου. |
| [getSupportedFileTypes()](#getSupportedFileTypes--) | Ανακτά τους υποστηριζόμενους τύπους αρχείων |
| [equals(FileType other)](#equals-com.groupdocs.merger.domain.FileType-) | Καθορίζει εάν το τρέχον [FileType](../../com.groupdocs.merger.domain/filetype) είναι το ίδιο με το καθορισμένο αντικείμενο [FileType](../../com.groupdocs.merger.domain/filetype). |
| [equals(Object obj)](#equals-java.lang.Object-) | Καθορίζει εάν το τρέχον [FileType](../../com.groupdocs.merger.domain/filetype) είναι το ίδιο με το καθορισμένο αντικείμενο. |
| [hashCode()](#hashCode--) | Επιστρέφει τον κωδικό κατακερματισμού για το τρέχον αντικείμενο [FileType](../../com.groupdocs.merger.domain/filetype). |
| [op_Equality(FileType left, FileType right)](#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Καθορίζει εάν δύο αντικείμενα [FileType](../../com.groupdocs.merger.domain/filetype) είναι τα ίδια. |
| [op_Inequality(FileType left, FileType right)](#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-) | Καθορίζει εάν δύο αντικείμενα [FileType](../../com.groupdocs.merger.domain/filetype) δεν είναι τα ίδια. |
| [toString()](#toString--) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |
| [isText(FileType fileType)](#isText-com.groupdocs.merger.domain.FileType-) | Καθορίζει εάν η είσοδος [FileType](../../com.groupdocs.merger.domain/filetype) είναι πρωτότυπη μορφή κειμένου. |
| [isArchive(FileType fileType)](#isArchive-com.groupdocs.merger.domain.FileType-) | Καθορίζει εάν η είσοδος [FileType](../../com.groupdocs.merger.domain/filetype) είναι μορφή αρχείου αρχειοθήκης. |
| [isImage(FileType fileType)](#isImage-com.groupdocs.merger.domain.FileType-) | Καθορίζει εάν η είσοδος [FileType](../../com.groupdocs.merger.domain/filetype) είναι πρωτότυπη μορφή κειμένου. |
| [isAudio(FileType fileType)](#isAudio-com.groupdocs.merger.domain.FileType-) | Καθορίζει εάν η είσοδος [FileType](../../com.groupdocs.merger.domain/filetype) είναι μορφή ήχου. |
| [getBase(FileType fileType)](#getBase-com.groupdocs.merger.domain.FileType-) |  |
### Unknown {#Unknown}
```
public static final FileType Unknown
```


Αντιπροσωπεύει άγνωστο τύπο αρχείου.

### ZIP {#ZIP}
```
public static FileType ZIP
```


Συμπιεσμένο αρχείο (.zip)

### SevenZ {#SevenZ}
```
public static final FileType SevenZ
```


Αρχείο συμπιεσμένο με 7-Zip (.7z)

### TAR {#TAR}
```
public static final FileType TAR
```


Συγκεντρωτικό αρχείο Unix (.tar)

### RAR {#RAR}
```
public static final FileType RAR
```


Συμπιεσμένο αρχείο Roshal Archive (.rar)

### VSSX {#VSSX}
```
public static final FileType VSSX
```


Το Visio Stencil File (.vssx) είναι πρότυπα σχεδίασης που δημιουργήθηκαν με το Microsoft Visio 2013 και μεταγενέστερες εκδόσεις. Η μορφή αρχείου VSSX μπορεί να ανοιχθεί με το Visio 2013 και μεταγενέστερες εκδόσεις. Τα αρχεία Visio είναι γνωστά για την αναπαράσταση μιας ποικιλίας στοιχείων σχεδίασης όπως συλλογή σχημάτων, συνδέσμων, διαγραμμάτων ροής, διάταξης δικτύου, διαγραμμάτων UML. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/image/vssx

### VSDX {#VSDX}
```
public static final FileType VSDX
```


Το Visio Drawing (.vsdx) αντιπροσωπεύει τη μορφή αρχείου Microsoft Visio που εισήχθη από το Microsoft Office 2013 και μετά. Αναπτύχθηκε για να αντικαταστήσει τη δυαδική μορφή αρχείου, .VSD, η οποία υποστηρίζεται από παλαιότερες εκδόσεις του Microsoft Visio. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/image/vsdx

### VSDM {#VSDM}
```
public static final FileType VSDM
```


Το Visio Macro-Enabled Drawing (.vsdm) είναι αρχεία σχεδίασης που δημιουργήθηκαν με την εφαρμογή Microsoft Visio που υποστηρίζει μακροεντολές. Τα αρχεία VSDM είναι σχεδιαγράμματα OPC/XML που είναι παρόμοια με τα VSDX, αλλά παρέχουν επίσης τη δυνατότητα εκτέλεσης μακροεντολών όταν ανοίγει το αρχείο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/image/vsdm

### VSTX {#VSTX}
```
public static final FileType VSTX
```


Το Visio Drawing Template (.vstx) είναι αρχεία προτύπων σχεδίασης που δημιουργήθηκαν με το Microsoft Visio 2013 και μεταγενέστερες εκδόσεις. Αυτά τα αρχεία VSTX παρέχουν σημείο εκκίνησης για τη δημιουργία σχεδίων Visio, αποθηκευμένα ως αρχεία .VSDX, με προεπιλεγμένη διάταξη και ρυθμίσεις. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/image/vstx

### VSTM {#VSTM}
```
public static final FileType VSTM
```


Το Visio Macro-Enabled Drawing Template (.vstm) είναι αρχεία προτύπων που δημιουργήθηκαν με το Microsoft Visio και υποστηρίζουν μακροεντολές. Σε αντίθεση με τα αρχεία VSDX, τα αρχεία που δημιουργούνται από πρότυπα VSTM μπορούν να εκτελούν μακροεντολές που έχουν αναπτυχθεί σε κώδικα Visual Basic for Applications (VBA). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/image/vstm

### VSSM {#VSSM}
```
public static final FileType VSSM
```


Το Visio Macro-Enabled Stencil File (.vssm) είναι αρχεία Stencil του Microsoft Visio που παρέχουν υποστήριξη για μακροεντολές. Ένα αρχείο VSSM όταν ανοίγεται επιτρέπει την εκτέλεση των μακροεντολών για την επίτευξη της επιθυμητής μορφοποίησης και τοποθέτησης των σχημάτων σε ένα διάγραμμα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/image/vssm

### VSX {#VSX}
```
public static final FileType VSX
```


Το Visio Stencil XML File (.vsx) αναφέρεται σε πρότυπα που αποτελούνται από σχέδια και σχήματα που χρησιμοποιούνται για τη δημιουργία διαγραμμάτων στο Microsoft Visio. Τα αρχεία VSX αποθηκεύονται σε μορφή XML και υποστηρίζονταν μέχρι το Visio 2013. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/image/vsx

### VTX {#VTX}
```
public static final FileType VTX
```


Το Visio Template XML File (.vtx) είναι ένα πρότυπο σχεδίασης Microsoft Visio που αποθηκεύεται σε δίσκο σε μορφή αρχείου XML. Το πρότυπο στοχεύει να παρέχει ένα αρχείο με βασικές ρυθμίσεις που μπορούν να χρησιμοποιηθούν για τη δημιουργία πολλαπλών αρχείων Visio με τις ίδιες ρυθμίσεις. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/image/vtx

### VDX {#VDX}
```
public static final FileType VDX
```


Το Visio Drawing XML File (.vdx) είναι ένα σχέδιο ή διάγραμμα που δημιουργήθηκε στο Microsoft Visio, αλλά αποθηκεύεται σε μορφή XML με επέκταση .VDX. Ένα αρχείο Visio drawing XML δημιουργείται στο λογισμικό Visio, το οποίο αναπτύχθηκε από τη Microsoft. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/image/vdx

### EPUB {#EPUB}
```
public static final FileType EPUB
```


Το Open eBook File (.epub) είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυποποιημένο ψηφιακό μορφότυπο δημοσίευσης για εκδότες και καταναλωτές. Η μορφή αυτή είναι πλέον τόσο κοινή που υποστηρίζεται από πολλούς αναγνώστες ηλεκτρονικών βιβλίων και λογισμικά εφαρμογές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/ebook/epub

### BMP {#BMP}
```
public static final FileType BMP
```


Το Bitmap Image File (.bmp) αντιπροσωπεύει αρχεία που χρησιμοποιούνται για την αποθήκευση ψηφιακών bitmap εικόνων. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/image/bmp

### JPG {#JPG}
```
public static final FileType JPG
```


JPEG Εικόνα (.jpg)

### JPEG {#JPEG}
```
public static final FileType JPEG
```


Η JPEG Image (.jpeg) είναι ένας τύπος μορφής εικόνας που αποθηκεύεται με τη μέθοδο της απώλειας συμπίεσης. Η τελική εικόνα, ως αποτέλεσμα της συμπίεσης, αποτελεί μια ισορροπία μεταξύ μεγέθους αποθήκευσης και ποιότητας εικόνας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/image/jpeg

### PNG {#PNG}
```
public static final FileType PNG
```


Το Portable Network Graphic (.png) είναι ένας τύπος μορφής αρχείου raster εικόνας που χρησιμοποιεί χωρίς απώλειες συμπίεση. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/image/png

### PS {#PS}
```
public static final FileType PS
```


PostScript Αρχείο (.ps)

### TIF {#TIF}
```
public static FileType TIF
```


Αρχείο Tagged Image (.tif)

### TIFF {#TIFF}
```
public static FileType TIFF
```


Μορφή αρχείου Tagged Image (.tiff)

### GIF {#GIF}
```
public static FileType GIF
```


Αρχείο Graphical Interchange Format (.gif)

### SVG {#SVG}
```
public static FileType SVG
```


Αρχείο Scalable Vector Graphics (.svg)

### SVGZ {#SVGZ}
```
public static FileType SVGZ
```


Συμπιεσμένο αρχείο Scalable Vector Graphics (.svgz)

### EMF {#EMF}
```
public static final FileType EMF
```


Αναβαθμισμένο Μετααρχείο Windows (.emf)

### EMZ {#EMZ}
```
public static final FileType EMZ
```


Συμπιεσμένο Αναβαθμισμένο Μετααρχείο Windows (.emz)

### HTML {#HTML}
```
public static final FileType HTML
```


Το Hypertext Markup Language File (.html) είναι η επέκταση για ιστοσελίδες που δημιουργούνται για εμφάνιση σε προγράμματα περιήγησης. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/web/html

### MHT {#MHT}
```
public static final FileType MHT
```


Το MHTML Web Archive (.mht) είναι μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που μπορεί να δημιουργηθεί από διάφορες εφαρμογές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/web/mhtml

### MHTML {#MHTML}
```
public static final FileType MHTML
```


Το MIME HTML File (.mhtml) είναι μια μορφή αρχείου αρχειοθέτησης ιστοσελίδων που μπορεί να δημιουργηθεί από διάφορες εφαρμογές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/web/mhtml

### ONE {#ONE}
```
public static final FileType ONE
```


Τα αρχεία OneNote Document (.one) δημιουργούνται από την εφαρμογή Microsoft OneNote. Το OneNote σας επιτρέπει να συλλέγετε πληροφορίες χρησιμοποιώντας την εφαρμογή σαν να χρησιμοποιείτε το σημειωματάριό σας για λήψη σημειώσεων. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/note-taking/one

### PDF {#PDF}
```
public static final FileType PDF
```


Το αρχείο Portable Document Format (.pdf) είναι ένα μορφότυπο αρχείου που εισήχθη ως πρότυπο για την αναπαράσταση εγγράφων και άλλου υλικού αναφοράς σε μορφή ανεξάρτητη από λογισμικό εφαρμογών, υλικό καθώς και λειτουργικό σύστημα. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/view/pdf

### XPS {#XPS}
```
public static final FileType XPS
```


Το αρχείο XML Paper Specification (.xps) αντιπροσωπεύει αρχεία διάταξης σελίδων που βασίζονται στις προδιαγραφές XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/page-description-language/xps

### TEX {#TEX}
```
public static final FileType TEX
```


Το LaTeX Source Document (.tex) είναι μια γλώσσα που περιλαμβάνει προγραμματισμό καθώς και χαρακτηριστικά σήμανσης, που χρησιμοποιείται για τη στοιχειοθέτηση εγγράφων. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/page-description-language/tex

### PPT {#PPT}
```
public static final FileType PPT
```


Η PowerPoint Presentation (.ppt) αντιπροσωπεύει αρχείο PowerPoint που αποτελείται από μια συλλογή διαφανειών για προβολή ως SlideShow. Καθορίζει το Binary File Format που χρησιμοποιείται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/presentation/ppt

### PPTX {#PPTX}
```
public static final FileType PPTX
```


Το PowerPoint Open XML Presentation (.pptx) είναι ένα αρχείο παρουσίασης που δημιουργείται με τη δημοφιλή εφαρμογή Microsoft PowerPoint. Σε αντίθεση με την προηγούμενη έκδοση του μορφότυπου αρχείου παρουσίασης PPT που ήταν δυαδικό, ο μορφότυπος PPTX βασίζεται στο ανοιχτό XML μορφότυπο παρουσίασης του Microsoft PowerPoint. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/presentation/pptx

### PPS {#PPS}
```
public static final FileType PPS
```


Το PowerPoint Slide Show (.pps) είναι ένα αρχείο που δημιουργείται με το Microsoft PowerPoint για σκοπό Slide Show. Η ανάγνωση και δημιουργία αρχείων PPS υποστηρίζεται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/presentation/pps

### PPSX {#PPSX}
```
public static final FileType PPSX
```


Το PowerPoint Open XML Slide Show (.ppsx) είναι ένα αρχείο που δημιουργείται με το Microsoft PowerPoint 2007 και νεότερες εκδόσεις για σκοπό Slide Show. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/presentation/ppsx

### ODP {#ODP}
```
public static final FileType ODP
```


Το OpenDocument Presentation (.odp) αντιπροσωπεύει το μορφότυπο αρχείου παρουσίασης που χρησιμοποιείται από το OpenOffice.org στο πρότυπο OASIS Open. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/presentation/odp

### OTP {#OTP}
```
public static final FileType OTP
```


Το OpenDocument Presentation Template (.otp) αντιπροσωπεύει αρχεία προτύπων παρουσίασης που δημιουργούνται από εφαρμογές στο πρότυπο μορφότυπο OASIS OpenDocument. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/presentation/otp

### XLS {#XLS}
```
public static final FileType XLS
```


Το Excel Spreadsheet (.xls) είναι ένα αρχείο που μπορεί να δημιουργηθεί από το Microsoft Excel καθώς και από άλλα παρόμοια προγράμματα λογιστικών φύλλων όπως το OpenOffice Calc ή το Apple Numbers. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/spreadsheet/xls

### XLSX {#XLSX}
```
public static final FileType XLSX
```


Το Microsoft Excel Open XML Spreadsheet (.xlsx) είναι ένας γνωστός μορφότυπος για έγγραφα Microsoft Excel που εισήχθη από τη Microsoft με την κυκλοφορία του Microsoft Office 2007. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsx

### XLSM {#XLSM}
```
public static final FileType XLSM
```


Το Excel Open XML Macro-Enabled Spreadsheet (.xlsm) είναι ένας τύπος αρχείων λογιστικού φύλλου που υποστηρίζουν μακροεντολές. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsm

### XLSB {#XLSB}
```
public static final FileType XLSB
```


Ο μορφότυπος αρχείου Excel Binary Spreadsheet (.xlsb) καθορίζει το Excel Binary File Format, το οποίο είναι μια συλλογή εγγραφών και δομών που ορίζουν το περιεχόμενο του βιβλίου εργασίας Excel. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlsb

### CSV {#CSV}
```
public static final FileType CSV
```


Το αρχείο Comma Separated Values (.csv) αντιπροσωπεύει αρχεία απλού κειμένου που περιέχουν εγγραφές δεδομένων με τιμές χωρισμένες με κόμμα. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/spreadsheet/csv

### TSV {#TSV}
```
public static final FileType TSV
```


Το αρχείο Tab Separated Values (.tsv) αντιπροσωπεύει δεδομένα διαχωρισμένα με καρτέλες σε μορφή απλού κειμένου. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/spreadsheet/tsv

### ODS {#ODS}
```
public static final FileType ODS
```


OpenDocument Spreadsheet (.ods).

### XLTM {#XLTM}
```
public static final FileType XLTM
```


Το Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) αντιπροσωπεύει αρχεία που δημιουργούνται από το Microsoft Excel ως πρότυπα αρχείων με ενεργοποιημένες μακροεντολές. Τα αρχεία XLTM είναι παρόμοια με τα XLTX στη δομή, εκτός από το ότι τα δεύτερα δεν υποστηρίζουν τη δημιουργία προτύπων αρχείων με μακροεντολές. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltm

### XLTX {#XLTX}
```
public static final FileType XLTX
```


Τα αρχεία Excel Open XML Spreadsheet Template (.xltx) βασίζονται στις προδιαγραφές του μορφότυπου αρχείου Office OpenXML. Χρησιμοποιούνται για τη δημιουργία ενός τυπικού αρχείου προτύπου που μπορεί να αξιοποιηθεί για τη δημιουργία αρχείων XLSX που εμφανίζουν τις ίδιες ρυθμίσεις όπως ορίζονται στο αρχείο XLTX. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [here][].


[here]: https://docs.fileformat.com/spreadsheet/xltx

### XLT {#XLT}
```
public static final FileType XLT
```


Τα αρχεία προτύπου Excel (.xlt) είναι αρχεία προτύπου που δημιουργούνται με το Microsoft Excel, το οποίο είναι μια εφαρμογή λογιστικού φύλλου που αποτελεί μέρος της σουίτας Microsoft Office. Το Microsoft Office 97-2003 υποστήριζε τη δημιουργία νέων αρχείων XLT καθώς και το άνοιγμά τους. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/spreadsheet/xlt

### XLAM {#XLAM}
```
public static final FileType XLAM
```


Πρόσθετο Excel με δυνατότητα μακροεντολών (.xlam).

### DOC {#DOC}
```
public static final FileType DOC
```


Τα έγγραφα Microsoft Word (.doc) αντιπροσωπεύουν έγγραφα που δημιουργούνται από το Microsoft Word ή άλλα προγράμματα επεξεργασίας κειμένου σε δυαδική μορφή αρχείου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/word-processing/doc

### DOCX {#DOCX}
```
public static final FileType DOCX
```


Το Microsoft Word Open XML Document (.docx) είναι μια γνωστή μορφή για έγγραφα Microsoft Word. Εισήχθη το 2007 με την κυκλοφορία του Microsoft Office 2007, η δομή αυτής της νέας μορφής εγγράφου άλλαξε από απλό δυαδικό σε συνδυασμό αρχείων XML και δυαδικών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/word-processing/docx

### DOCM {#DOCM}
```
public static final FileType DOCM
```


Τα αρχεία Word Open XML Macro-Enabled Document (.docm) είναι έγγραφα που δημιουργούνται από το Microsoft Word 2007 ή νεότερο, με δυνατότητα εκτέλεσης μακροεντολών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/word-processing/docm

### DOT {#DOT}
```
public static final FileType DOT
```


Τα αρχεία Word Document Template (.dot) είναι αρχεία προτύπου που δημιουργούνται από το Microsoft Word για να έχουν προδιαμορφωμένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOC ή DOCX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/word-processing/dot

### DOTX {#DOTX}
```
public static final FileType DOTX
```


Τα Word Open XML Document Template (.dotx) είναι αρχεία προτύπου που δημιουργούνται από το Microsoft Word για να έχουν προδιαμορφωμένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOCX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/word-processing/dotx

### DOTM {#DOTM}
```
public static final FileType DOTM
```


Το Word Open XML Macro-Enabled Document Template (.dotm) αντιπροσωπεύει αρχείο προτύπου που δημιουργήθηκε με το Microsoft Word 2007 ή νεότερο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/word-processing/dotm

### RTF {#RTF}
```
public static final FileType RTF
```


Το αρχείο Rich Text Format (.rtf), που εισήχθη και τεκμηριώθηκε από τη Microsoft, το Rich Text Format (RTF) αντιπροσωπεύει μια μέθοδο κωδικοποίησης μορφοποιημένου κειμένου και γραφικών για χρήση σε εφαρμογές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/word-processing/rtf

### TXT {#TXT}
```
public static final FileType TXT
```


Το αρχείο Plain Text (.txt) αντιπροσωπεύει ένα έγγραφο κειμένου που περιέχει απλό κείμενο με μορφή γραμμών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/word-processing/txt

### ERR {#ERR}
```
public static final FileType ERR
```


Το αρχείο Error Log (.err) είναι ένα αρχείο κειμένου που περιέχει μηνύματα σφάλματος που δημιουργήθηκαν από ένα πρόγραμμα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://fileinfo.com/extension/err

### ODT {#ODT}
```
public static final FileType ODT
```


Τα αρχεία OpenDocument Text Document (.odt) είναι τύπος εγγράφων που δημιουργούνται με εφαρμογές επεξεργασίας κειμένου που βασίζονται στη μορφή OpenDocument Text File. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/word-processing/odt

### OTT {#OTT}
```
public static final FileType OTT
```


Τα OpenDocument Document Template (.ott) αντιπροσωπεύουν έγγραφα προτύπου που δημιουργούνται από εφαρμογές σε συμμόρφωση με το πρότυπο μορφής OpenDocument του OASIS. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [here][].


[here]: https://docs.fileformat.com/word-processing/ott

### WAV {#WAV}
```
public static FileType WAV
```


Το WAV, γνωστό για το WAVE (Waveform Audio File Format), είναι ένα υποσύνολο της προδιαγραφής Resource Interchange File Format (RIFF) της Microsoft\\u2019s για την αποθήκευση ψηφιακών αρχείων ήχου. Η μορφή δεν εφαρμόζει καμία συμπίεση στο bitstream και αποθηκεύει τις ηχογραφήσεις με διαφορετικούς ρυθμούς δειγματοληψίας και bitrate. Είναι και παραμένει μία από τις τυπικές μορφές για CD ήχου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου  [here][] .


[here]: https://docs.fileformat.com/audio/wav

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Όνομα τύπου αρχείου π.χ. "Microsoft Word Document".

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Κατάληξη ονόματος αρχείου (συμπεριλαμβανομένου του σημείου ".") π.χ. ".doc".

**Returns:**
java.lang.String
### fromExtension(String extension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String extension)
```


Αντιστοιχίζει την επέκταση αρχείου με τον τύπο αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| επέκταση | java.lang.String | Επέκταση αρχείου (συμπεριλαμβανομένου του σημείου "."). |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype) - When file type is supported returns it, otherwise returns default \#Unknown.Unknown file type.
### getSupportedFileTypes() {#getSupportedFileTypes--}
```
public static List<FileType> getSupportedFileTypes()
```


Ανακτά τους υποστηριζόμενους τύπους αρχείων

**Returns:**
java.util.List<com.groupdocs.merger.domain.FileType> - Επιστρέφει τη σειρά των υποστηριζόμενων τύπων αρχείων
### equals(FileType other) {#equals-com.groupdocs.merger.domain.FileType-}
```
public final boolean equals(FileType other)
```


Καθορίζει εάν το τρέχον [FileType](../../com.groupdocs.merger.domain/filetype) είναι το ίδιο με το καθορισμένο αντικείμενο [FileType](../../com.groupdocs.merger.domain/filetype).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [FileType](../../com.groupdocs.merger.domain/filetype) | Το αντικείμενο προς σύγκριση με το τρέχον αντικείμενο [FileType](../../com.groupdocs.merger.domain/filetype). |

**Returns:**
boolean - ```
true
```

if both [FileType](../../com.groupdocs.merger.domain/filetype) objects are the same; otherwise,

```
false
```
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the current [FileType](../../com.groupdocs.merger.domain/filetype) is the same as specified object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with the current [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

if

```
obj
```

η παράμετρος είναι [FileType](../../com.groupdocs.merger.domain/filetype) και είναι η ίδια με το τρέχον αντικείμενο [FileType](../../com.groupdocs.merger.domain/filetype); διαφορετικά,

```
false
```
### hashCode() {#hashCode--}
```
public int hashCode()
```


Επιστρέφει τον κωδικό κατακερματισμού για το τρέχον αντικείμενο [FileType](../../com.groupdocs.merger.domain/filetype).

**Returns:**
int - Ένας κωδικός κατακερματισμού για το τρέχον αντικείμενο [FileType](../../com.groupdocs.merger.domain/filetype).
### op_Equality(FileType left, FileType right) {#op-Equality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Equality(FileType left, FileType right)
```


Καθορίζει εάν δύο αντικείμενα [FileType](../../com.groupdocs.merger.domain/filetype) είναι τα ίδια.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | Αριστερό [FileType](../../com.groupdocs.merger.domain/filetype) αντικείμενο. |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | Δεξιό [FileType](../../com.groupdocs.merger.domain/filetype) αντικείμενο. |

**Returns:**
boolean - ```
true
```

if both [FileType](../../com.groupdocs.merger.domain/filetype) objects are the same; otherwise,

```
false
```
### op_Inequality(FileType left, FileType right) {#op-Inequality-com.groupdocs.merger.domain.FileType-com.groupdocs.merger.domain.FileType-}
```
public static boolean op_Inequality(FileType left, FileType right)
```


Determines whether two [FileType](../../com.groupdocs.merger.domain/filetype) objects are not the same.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [FileType](../../com.groupdocs.merger.domain/filetype) | Left [FileType](../../com.groupdocs.merger.domain/filetype) object. |
| right | [FileType](../../com.groupdocs.merger.domain/filetype) | Right [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

εάν και τα δύο [FileType](../../com.groupdocs.merger.domain/filetype) αντικείμενα δεν είναι τα ίδια· διαφορετικά,

```
false
```
### toString() {#toString--}
```
public String toString()
```


Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο.

**Returns:**
java.lang.String - Μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο.
### isText(FileType fileType) {#isText-com.groupdocs.merger.domain.FileType-}
```
public static boolean isText(FileType fileType)
```


Καθορίζει εάν η είσοδος [FileType](../../com.groupdocs.merger.domain/filetype) είναι πρωτότυπη μορφή κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Το [FileType](../../com.groupdocs.merger.domain/filetype) αντικείμενο. |

**Returns:**
boolean - ```
true
```

if input [FileType](../../com.groupdocs.merger.domain/filetype) is primitive text format; otherwise,

```
false
```
### isArchive(FileType fileType) {#isArchive-com.groupdocs.merger.domain.FileType-}
```
public static boolean isArchive(FileType fileType)
```


Determines whether input [FileType](../../com.groupdocs.merger.domain/filetype) is archive format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

εάν η είσοδος [FileType](../../com.groupdocs.merger.domain/filetype) είναι μορφή αρχείου αρχειοθέτησης· διαφορετικά,

```
false
```
### isImage(FileType fileType) {#isImage-com.groupdocs.merger.domain.FileType-}
```
public static boolean isImage(FileType fileType)
```


Καθορίζει εάν η είσοδος [FileType](../../com.groupdocs.merger.domain/filetype) είναι πρωτότυπη μορφή κειμένου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | Το [FileType](../../com.groupdocs.merger.domain/filetype) αντικείμενο. |

**Returns:**
boolean - ```
true
```

if input [FileType](../../com.groupdocs.merger.domain/filetype) is primitive image format; otherwise,

```
false
```
### isAudio(FileType fileType) {#isAudio-com.groupdocs.merger.domain.FileType-}
```
public static boolean isAudio(FileType fileType)
```


Determines whether input [FileType](../../com.groupdocs.merger.domain/filetype) is audio format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) | The [FileType](../../com.groupdocs.merger.domain/filetype) object. |

**Returns:**
boolean - ```
true
```

εάν η είσοδος [FileType](../../com.groupdocs.merger.domain/filetype) είναι μορφή ήχου· διαφορετικά,

```
false
```
### getBase(FileType fileType) {#getBase-com.groupdocs.merger.domain.FileType-}
```
public static FileType getBase(FileType fileType)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.merger.domain/filetype) |  |

**Returns:**
[FileType](../../com.groupdocs.merger.domain/filetype)
