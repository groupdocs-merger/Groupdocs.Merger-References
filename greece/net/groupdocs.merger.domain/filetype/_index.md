---
title: "FileType"
second_title: "GroupDocs.Merger για .NET API Reference"
description: "Αντιπροσωπεύει τον τύπο αρχείου. Παρέχει μεθόδους για την απόκτηση λίστας όλων των τύπων αρχείων που υποστηρίζονται από το GroupDocs.Merger, ανίχνευση τύπου αρχείου με βάση την επέκταση κ.λπ."
type: docs
weight: 110
url: /el/net/groupdocs.merger.domain/filetype/
---
## FileType class

Αντιπροσωπεύει τύπο αρχείου. Παρέχει μεθόδους για την απόκτηση λίστας όλων των τύπων αρχείων που υποστηρίζονται από **GroupDocs.Merger**, ανίχνευση τύπου αρχείου με βάση την επέκταση κ.λπ.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | Κατάληξη ονόματος αρχείου (συμπεριλαμβανομένου του σημείου ".") π.χ. ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | Όνομα τύπου αρχείου π.χ. "Microsoft Word Document". |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | Αντιστοιχίζει την επέκταση αρχείου στον τύπο αρχείου. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | Καθορίζει εάν το τρέχον [`FileType`](../filetype) είναι το ίδιο με το καθορισμένο αντικείμενο [`FileType`](../filetype). |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | Καθορίζει εάν το τρέχον [`FileType`](../filetype) είναι το ίδιο με το καθορισμένο αντικείμενο. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | Επιστρέφει τον κωδικό κατακερματισμού για το τρέχον αντικείμενο [`FileType`](../filetype). |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | Ανακτά τους υποστηριζόμενους τύπους αρχείων |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | Καθορίζει εάν η είσοδος [`FileType`](../filetype) είναι μορφή αρχείου αρχειοθήκης. |
| static [IsAudio](../../groupdocs.merger.domain/filetype/isaudio)(FileType) | Καθορίζει εάν η είσοδος [`FileType`](../filetype) είναι μορφή ήχου. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | Καθορίζει εάν η είσοδος [`FileType`](../filetype) είναι μορφή εικόνας. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | Καθορίζει εάν η είσοδος [`FileType`](../filetype) είναι μορφή πρωτόγονου κειμένου. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | Καθορίζει εάν δύο αντικείμενα [`FileType`](../filetype) είναι τα ίδια. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | Καθορίζει εάν δύο αντικείμενα [`FileType`](../filetype) δεν είναι τα ίδια. |

## Πεδία

| Όνομα | Περιγραφή |
| --- | --- |
| static readonly [BMP](../../groupdocs.merger.domain/filetype/bmp) | Bitmap Image File (.bmp) αντιπροσωπεύει αρχεία που χρησιμοποιούνται για την αποθήκευση ψηφιακών bitmap εικόνων. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/image/bmp). |
| static readonly [BZ2](../../groupdocs.merger.domain/filetype/bz2) | Αρχείο Συμπίεσης Bzip2 (.bz2) |
| static readonly [CSV](../../groupdocs.merger.domain/filetype/csv) | Comma Separated Values File (.csv) αντιπροσωπεύει αρχεία απλού κειμένου που περιέχουν εγγραφές δεδομένων με τιμές διαχωρισμένες με κόμμα. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/spreadsheet/csv). |
| static readonly [DOC](../../groupdocs.merger.domain/filetype/doc) | Microsoft Word Document (.doc) αντιπροσωπεύει έγγραφα που δημιουργούνται από το Microsoft Word ή άλλα προγράμματα επεξεργασίας κειμένου σε δυαδική μορφή αρχείου. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/word-processing/doc). |
| static readonly [DOCM](../../groupdocs.merger.domain/filetype/docm) | Τα αρχεία Word Open XML Macro-Enabled Document (.docm) είναι έγγραφα που δημιουργούνται από το Microsoft Word 2007 ή νεότερο, με δυνατότητα εκτέλεσης μακροεντολών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/word-processing/docm). |
| static readonly [DOCX](../../groupdocs.merger.domain/filetype/docx) | Το Microsoft Word Open XML Document (.docx) είναι μια γνωστή μορφή για έγγραφα Microsoft Word. Εισήχθη το 2007 με την κυκλοφορία του Microsoft Office 2007, η δομή αυτής της νέας μορφής εγγράφου άλλαξε από απλό δυαδικό σε συνδυασμό αρχείων XML και δυαδικών. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/word-processing/docx). |
| static readonly [DOT](../../groupdocs.merger.domain/filetype/dot) | Τα αρχεία Word Document Template (.dot) είναι αρχεία προτύπων που δημιουργούνται από το Microsoft Word για να έχουν προ-μορφοποιημένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOC ή DOCX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/word-processing/dot). |
| static readonly [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Το Word Open XML Macro-Enabled Document Template (.dotm) αντιπροσωπεύει ένα αρχείο προτύπου που δημιουργήθηκε με το Microsoft Word 2007 ή νεότερο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/word-processing/dotm). |
| static readonly [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Τα Word Open XML Document Template (.dotx) είναι αρχεία προτύπων που δημιουργούνται από το Microsoft Word για να έχουν προ-μορφοποιημένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOCX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/word-processing/dotx). |
| static readonly [EMF](../../groupdocs.merger.domain/filetype/emf) | Windows Enhanced Metafile (.emf) |
| static readonly [EMZ](../../groupdocs.merger.domain/filetype/emz) | Windows Compressed Enhanced Metafile (.emz) |
| static readonly [EPUB](../../groupdocs.merger.domain/filetype/epub) | Το Open eBook File (.epub) είναι μια μορφή αρχείου ηλεκτρονικού βιβλίου που παρέχει ένα τυποποιημένο ψηφιακό φορμά δημοσίευσης για εκδότες και καταναλωτές. Η μορφή αυτή είναι πλέον τόσο διαδεδομένη που υποστηρίζεται από πολλούς αναγνώστες e‑book και λογισμικές εφαρμογές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/ebook/epub). |
| static readonly [ERR](../../groupdocs.merger.domain/filetype/err) | Το Error Log File (.err) είναι ένα αρχείο κειμένου που περιέχει μηνύματα σφάλματος που δημιουργήθηκαν από ένα πρόγραμμα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://fileinfo.com/extension/err). |
| static readonly [GIF](../../groupdocs.merger.domain/filetype/gif) | Αρχείο Graphical Interchange Format (.gif) |
| static readonly [GZ](../../groupdocs.merger.domain/filetype/gz) | Συμπιεσμένο αρχείο G‑Zip (.gz) |
| static readonly [HTML](../../groupdocs.merger.domain/filetype/html) | Το Hypertext Markup Language File (.html) είναι η επέκταση για ιστοσελίδες που δημιουργούνται για προβολή σε προγράμματα περιήγησης. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/web/html). |
| static readonly [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | Η JPEG Image (.jpeg) είναι ένας τύπος μορφής εικόνας που αποθηκεύεται χρησιμοποιώντας τη μέθοδο της απώλειας συμπίεσης. Η τελική εικόνα, ως αποτέλεσμα της συμπίεσης, αποτελεί μια ισορροπία μεταξύ μεγέθους αποθήκευσης και ποιότητας εικόνας. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/image/jpeg). |
| static readonly [JPG](../../groupdocs.merger.domain/filetype/jpg) | Εικόνα JPEG (.jpg) |
| static readonly [MHT](../../groupdocs.merger.domain/filetype/mht) | Το MHTML Web Archive (.mht) είναι μια μορφή αρχειοθέτησης ιστοσελίδων που μπορεί να δημιουργηθεί από διάφορες εφαρμογές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/web/mhtml). |
| static readonly [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | Το MIME HTML File (.mhtml) είναι μια μορφή αρχειοθέτησης ιστοσελίδων που μπορεί να δημιουργηθεί από διάφορες εφαρμογές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/web/mhtml). |
| static readonly [MP3](../../groupdocs.merger.domain/filetype/mp3) | Τα αρχεία με επέκταση .mp3 είναι ψηφιακά κωδικοποιημένες μορφές αρχείων ήχου που βασίζονται επίσημα στο MPEG‑1 Audio Layer III ή MPEG‑2 Audio Layer III. Αναπτύχθηκαν από το Moving Picture Experts Group (MPEG) που χρησιμοποιεί τη συμπίεση ήχου Layer 3. Η συμπίεση που επιτυγχάνεται από τη μορφή αρχείου MP3 είναι το 1/10 του μεγέθους των αρχείων .WAV ή .AIF. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/audio/mp3). |
| static readonly [ODP](../../groupdocs.merger.domain/filetype/odp) | Το OpenDocument Presentation (.odp) αντιπροσωπεύει τη μορφή αρχείου παρουσίασης που χρησιμοποιείται από το OpenOffice.org στο πρότυπο OASISOpen. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/presentation/odp). |
| static readonly [ODS](../../groupdocs.merger.domain/filetype/ods) | OpenDocument Spreadsheet (.ods) Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/spreadsheet/ods). |
| static readonly [ODT](../../groupdocs.merger.domain/filetype/odt) | Τα αρχεία OpenDocument Text Document (.odt) είναι τύπος εγγράφων που δημιουργούνται με εφαρμογές επεξεργασίας κειμένου και βασίζονται στη μορφή OpenDocument Text File. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/word-processing/odt). |
| static readonly [ONE](../../groupdocs.merger.domain/filetype/one) | Τα αρχεία OneNote Document (.one) δημιουργούνται από την εφαρμογή Microsoft OneNote. Το OneNote σας επιτρέπει να συγκεντρώνετε πληροφορίες χρησιμοποιώντας την εφαρμογή σαν να χρησιμοποιείτε το σημειωματάριό σας για λήψη σημειώσεων. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/note-taking/one). |
| static readonly [OTP](../../groupdocs.merger.domain/filetype/otp) | Το OpenDocument Presentation Template (.otp) αντιπροσωπεύει αρχεία προτύπων παρουσιάσεων που δημιουργούνται από εφαρμογές σε μορφή προτύπου OASIS OpenDocument. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/presentation/otp). |
| static readonly [OTT](../../groupdocs.merger.domain/filetype/ott) | Το OpenDocument Document Template (.ott) αντιπροσωπεύει έγγραφα προτύπων που δημιουργούνται από εφαρμογές σύμφωνα με το πρότυπο μορφότυπο OASIS OpenDocument. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/word-processing/ott). |
| static readonly [PDF](../../groupdocs.merger.domain/filetype/pdf) | Το Portable Document Format File (.pdf) είναι ένα μορφότυπο αρχείου που εισήχθη ως πρότυπο για την αναπαράσταση εγγράφων και άλλου αναφορικού υλικού σε μορφή ανεξάρτητη από λογισμικό εφαρμογών, υλικό καθώς και λειτουργικό σύστημα. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/view/pdf). |
| static readonly [PNG](../../groupdocs.merger.domain/filetype/png) | Το Portable Network Graphic (.png) είναι ένας τύπος μορφότυπου αρχείου raster εικόνας που χρησιμοποιεί χωρίς απώλειες συμπίεση. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/image/png). |
| static readonly [POTM](../../groupdocs.merger.domain/filetype/potm) | PowerPoint Open XML Macro-Enabled Presentation Template (.potm) |
| static readonly [POTX](../../groupdocs.merger.domain/filetype/potx) | PowerPoint Open XML Presentation Template (.potx) |
| static readonly [PPS](../../groupdocs.merger.domain/filetype/pps) | Το PowerPoint Slide Show (.pps) είναι ένα αρχείο που δημιουργείται με τη χρήση του Microsoft PowerPoint για σκοπό παρουσίασης διαφανειών. Η ανάγνωση και δημιουργία αρχείων PPS υποστηρίζεται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/presentation/pps). |
| static readonly [PPSM](../../groupdocs.merger.domain/filetype/ppsm) | PowerPoint Open XML Macro-Enabled Slide (.ppsm) |
| static readonly [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | Το PowerPoint Open XML Slide Show (.ppsx) είναι ένα αρχείο που δημιουργείται με τη χρήση του Microsoft PowerPoint 2007 και μεταγενέστερων εκδόσεων για σκοπό παρουσίασης διαφανειών. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/presentation/ppsx). |
| static readonly [PPT](../../groupdocs.merger.domain/filetype/ppt) | Το PowerPoint Presentation (.ppt) αντιπροσωπεύει αρχείο PowerPoint που αποτελείται από μια συλλογή διαφανειών για προβολή ως SlideShow. Καθορίζει το Binary File Format που χρησιμοποιείται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/presentation/ppt). |
| static readonly [PPTM](../../groupdocs.merger.domain/filetype/pptm) | PowerPoint Open XML Macro-Enabled Presentation |
| static readonly [PPTX](../../groupdocs.merger.domain/filetype/pptx) | Το PowerPoint Open XML Presentation (.pptx) είναι ένα αρχείο παρουσίασης που δημιουργείται με τη δημοφιλή εφαρμογή Microsoft PowerPoint. Σε αντίθεση με την προηγούμενη έκδοση του μορφότυπου αρχείου παρουσίασης PPT που ήταν δυαδική, το μορφότυπο PPTX βασίζεται στο ανοιχτό XML μορφότυπο παρουσίασης του Microsoft PowerPoint. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/presentation/pptx). |
| static readonly [PS](../../groupdocs.merger.domain/filetype/ps) | PostScript File (.ps) |
| static readonly [RAR](../../groupdocs.merger.domain/filetype/rar) | Roshal ARchive Compressed File (.rar) |
| static readonly [RTF](../../groupdocs.merger.domain/filetype/rtf) | Το Rich Text Format File (.rtf) εισήχθη και τεκμηριώθηκε από τη Microsoft, το Rich Text Format (RTF) αντιπροσωπεύει μια μέθοδο κωδικοποίησης μορφοποιημένου κειμένου και γραφικών για χρήση σε εφαρμογές. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/word-processing/rtf). |
| static readonly [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | 7-Zip Compressed File (.7z) |
| static readonly [SVG](../../groupdocs.merger.domain/filetype/svg) | Scalable Vector Graphics File (.svg) |
| static readonly [SVGZ](../../groupdocs.merger.domain/filetype/svgz) | Scalable Vector Graphics Compressed File (.svgz) |
| static readonly [TAR](../../groupdocs.merger.domain/filetype/tar) | Consolidated Unix File Archive (.tar) |
| static readonly [TEX](../../groupdocs.merger.domain/filetype/tex) | Το LaTeX Source Document (.tex) είναι μια γλώσσα που περιλαμβάνει προγραμματιστικά καθώς και χαρακτηριστικά σήμανσης, χρησιμοποιείται για τη σύνθεση εγγράφων. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/page-description-language/tex). |
| static readonly [TIF](../../groupdocs.merger.domain/filetype/tif) | Tagged Image File (.tif) |
| static readonly [TIFF](../../groupdocs.merger.domain/filetype/tiff) | Tagged Image File Format (.tiff) |
| static readonly [TSV](../../groupdocs.merger.domain/filetype/tsv) | Το Tab Separated Values File (.tsv) αντιπροσωπεύει δεδομένα που διαχωρίζονται με καρτέλες σε μορφή απλού κειμένου. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/spreadsheet/tsv). |
| static readonly [TXT](../../groupdocs.merger.domain/filetype/txt) | Το Plain Text File (.txt) αντιπροσωπεύει ένα έγγραφο κειμένου που περιέχει απλό κείμενο με μορφή γραμμών. Μάθετε περισσότερα για αυτό το μορφότυπο αρχείου [εδώ](https://docs.fileformat.com/word-processing/txt). |
| static readonly [Unknown](../../groupdocs.merger.domain/filetype/unknown) | Αντιπροσωπεύει άγνωστο τύπο αρχείου. |
| static readonly [VDX](../../groupdocs.merger.domain/filetype/vdx) | Το αρχείο Visio Drawing XML (.vdx) είναι ένα σχέδιο ή διάγραμμα που δημιουργείται στο Microsoft Visio, αλλά αποθηκεύεται σε μορφή XML με επέκταση .VDX. Ένα αρχείο Visio drawing XML δημιουργείται στο λογισμικό Visio, το οποίο αναπτύσσεται από τη Microsoft. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/image/vdx). |
| static readonly [VSD](../../groupdocs.merger.domain/filetype/vsd) | Αρχείο Visio Drawing (.vsd) |
| static readonly [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Τα αρχεία Visio Macro-Enabled Drawing (.vsdm) είναι αρχεία σχεδίων που δημιουργούνται με την εφαρμογή Microsoft Visio και υποστηρίζουν μακροεντολές. Τα αρχεία VSDM είναι σχέδια OPC/XML που είναι παρόμοια με τα VSDX, αλλά παρέχουν επίσης τη δυνατότητα εκτέλεσης μακροεντολών όταν ανοίγεται το αρχείο. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/image/vsdm). |
| static readonly [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Το Visio Drawing (.vsdx) αντιπροσωπεύει τη μορφή αρχείου Microsoft Visio που εισήχθη από το Microsoft Office 2013 και μετά. Αναπτύχθηκε για να αντικαταστήσει τη δυαδική μορφή αρχείου .VSD, η οποία υποστηρίζεται από παλαιότερες εκδόσεις του Microsoft Visio. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/image/vsdx). |
| static readonly [VSS](../../groupdocs.merger.domain/filetype/vss) | Αρχείο Visio Stencil (.vss) |
| static readonly [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Τα αρχεία Visio Macro-Enabled Stencil (.vssm) είναι αρχεία Stencil του Microsoft Visio που παρέχουν υποστήριξη για μακροεντολές. Ένα αρχείο VSSM όταν ανοίγεται επιτρέπει την εκτέλεση των μακροεντολών για την επίτευξη της επιθυμητής μορφοποίησης και τοποθέτησης των σχημάτων σε ένα διάγραμμα. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/image/vssm). |
| static readonly [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Τα αρχεία Visio Stencil (.vssx) είναι πρότυπα σχεδίων που δημιουργούνται με το Microsoft Visio 2013 και μεταγενέστερες εκδόσεις. Η μορφή αρχείου VSSX μπορεί να ανοιχτεί με το Visio 2013 και μεταγενέστερες εκδόσεις. Τα αρχεία Visio είναι γνωστά για την αναπαράσταση μιας ποικιλίας στοιχείων σχεδίασης όπως συλλογή σχημάτων, συνδέσμων, διαγραμμάτων ροής, διατάξεων δικτύου, διαγραμμάτων UML. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/image/vssx). |
| static readonly [VST](../../groupdocs.merger.domain/filetype/vst) | Πρότυπο Visio Drawing (.vst) |
| static readonly [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Τα αρχεία Visio Macro-Enabled Drawing Template (.vstm) είναι πρότυπα που δημιουργούνται με το Microsoft Visio και υποστηρίζουν μακροεντολές. Σε αντίθεση με τα αρχεία VSDX, τα αρχεία που δημιουργούνται από πρότυπα VSTM μπορούν να εκτελούν μακροεντολές που έχουν αναπτυχθεί σε κώδικα Visual Basic for Applications (VBA). Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/image/vstm). |
| static readonly [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Τα αρχεία Visio Drawing Template (.vstx) είναι πρότυπα σχεδίων που δημιουργούνται με το Microsoft Visio 2013 και μεταγενέστερες εκδόσεις. Αυτά τα αρχεία VSTX παρέχουν ένα σημείο εκκίνησης για τη δημιουργία σχεδίων Visio, αποθηκευμένα ως αρχεία .VSDX, με προεπιλεγμένη διάταξη και ρυθμίσεις. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/image/vstx). |
| static readonly [VSX](../../groupdocs.merger.domain/filetype/vsx) | Το αρχείο Visio Stencil XML (.vsx) αναφέρεται σε πρότυπα που αποτελούνται από σχέδια και σχήματα που χρησιμοποιούνται για τη δημιουργία διαγραμμάτων στο Microsoft Visio. Τα αρχεία VSX αποθηκεύονται σε μορφή XML και υποστηρίζονταν μέχρι το Visio 2013. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/image/vsx). |
| static readonly [VTX](../../groupdocs.merger.domain/filetype/vtx) | Το αρχείο Visio Template XML (.vtx) είναι ένα πρότυπο σχεδίου Microsoft Visio που αποθηκεύεται στο δίσκο σε μορφή XML. Το πρότυπο αποσκοπεί στην παροχή ενός αρχείου με βασικές ρυθμίσεις που μπορούν να χρησιμοποιηθούν για τη δημιουργία πολλαπλών αρχείων Visio με τις ίδιες ρυθμίσεις. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/image/vtx). |
| static readonly [WAV](../../groupdocs.merger.domain/filetype/wav) | Το WAV, γνωστό για το WAVE (Waveform Audio File Format), είναι ένα υποσύνολο της προδιαγραφής Resource Interchange File Format (RIFF) της Microsoft για την αποθήκευση ψηφιακών αρχείων ήχου. Η μορφή δεν εφαρμόζει καμία συμπίεση στο bitstream και αποθηκεύει τις ηχογραφήσεις με διαφορετικούς ρυθμούς δειγματοληψίας και bitrate. Είναι και ήταν ένα από τα πρότυπα μορφές για CD ήχου. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/audio/wav). |
| static readonly [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Πρόσθετο Excel Macro-Enabled Add-In (.xlam) |
| static readonly [XLS](../../groupdocs.merger.domain/filetype/xls) | Το Excel Spreadsheet (.xls) είναι ένα αρχείο που μπορεί να δημιουργηθεί από το Microsoft Excel καθώς και από άλλα παρόμοια προγράμματα λογιστικών φύλλων όπως το OpenOffice Calc ή το Apple Numbers. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/spreadsheet/xls). |
| static readonly [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Η μορφή αρχείου Excel Binary Spreadsheet (.xlsb) καθορίζει το Excel Binary File Format, το οποίο είναι μια συλλογή εγγραφών και δομών που καθορίζουν το περιεχόμενο του βιβλίου εργασίας Excel. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/spreadsheet/xlsb). |
| static readonly [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Excel Open XML Macro-Enabled Spreadsheet (.xlsm) είναι ένας τύπος αρχείων λογιστικού φύλλου που υποστηρίζουν μακροεντολές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/spreadsheet/xlsm). |
| static readonly [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Microsoft Excel Open XML Spreadsheet (.xlsx) είναι μια γνωστή μορφή για έγγραφα Microsoft Excel που εισήχθη από τη Microsoft με την κυκλοφορία του Microsoft Office 2007. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/spreadsheet/xlsx). |
| static readonly [XLT](../../groupdocs.merger.domain/filetype/xlt) | Excel Template File (.xlt) είναι αρχεία προτύπων που δημιουργούνται με το Microsoft Excel, το οποίο είναι μια εφαρμογή λογιστικού φύλλου που αποτελεί μέρος της σουίτας Microsoft Office. Το Microsoft Office 97-2003 υποστήριζε τη δημιουργία νέων αρχείων XLT καθώς και το άνοιγμά τους. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/spreadsheet/xlt). |
| static readonly [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Excel Open XML Macro-Enabled Spreadsheet Template (.xltm) αντιπροσωπεύει αρχεία που δημιουργούνται από το Microsoft Excel ως αρχεία προτύπου με υποστήριξη μακροεντολών. Τα αρχεία XLTM είναι παρόμοια με τα XLTX στη δομή, εκτός από το ότι τα τελευταία δεν υποστηρίζουν τη δημιουργία αρχείων προτύπου με μακροεντολές. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/spreadsheet/xltm). |
| static readonly [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Excel Open XML Spreadsheet Template (.xltx) αρχεία βασίζονται στις προδιαγραφές μορφής αρχείων Office OpenXML. Χρησιμοποιούνται για τη δημιουργία ενός τυπικού αρχείου προτύπου που μπορεί να χρησιμοποιηθεί για τη δημιουργία αρχείων XLSX που εμφανίζουν τις ίδιες ρυθμίσεις όπως ορίζονται στο αρχείο XLTX. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/spreadsheet/xltx). |
| static readonly [XPS](../../groupdocs.merger.domain/filetype/xps) | XML Paper Specification File (.xps) αντιπροσωπεύει αρχεία διάταξης σελίδας που βασίζονται στις XML Paper Specifications που δημιουργήθηκαν από τη Microsoft. Μάθετε περισσότερα για αυτή τη μορφή αρχείου [εδώ](https://docs.fileformat.com/page-description-language/xps). |
| static readonly [ZIP](../../groupdocs.merger.domain/filetype/zip) | Συμπιεσμένο αρχείο (.zip) |

### Παρατηρήσεις

**Learn more**

* Learn more about file formats supported by GroupDocs.Merger: [Full list of supported document formats](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Learn more about getting supported file types in code: [How to get supported file formats in code](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### Δείτε επίσης

* namespace [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* assembly [GroupDocs.Merger](../../)

<!-- ΜΗΝ ΕΠΕΞΕΡΓΑΣΕΤΕ: δημιουργήθηκε από xmldocmd για GroupDocs.merger.dll -->
