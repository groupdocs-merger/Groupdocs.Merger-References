---
title: FileType
second_title: GroupDocs.Merger for .NET API Reference
description: Αντιπροσωπεύει τον τύπο αρχείου. Παρέχει μεθόδους λήψης λίστας όλων των τύπων αρχείων που υποστηρίζονται απόGroupDocs.Merger  ανίχνευση τύπου αρχείου κατά επέκταση κ.λπ.
type: docs
weight: 100
url: /el/net/groupdocs.merger.domain/filetype/
---
## FileType class

Αντιπροσωπεύει τον τύπο αρχείου. Παρέχει μεθόδους λήψης λίστας όλων των τύπων αρχείων που υποστηρίζονται από**GroupDocs.Merger** , ανίχνευση τύπου αρχείου κατά επέκταση κ.λπ.

```csharp
public sealed class FileType : IEquatable<FileType>
```

## Ιδιότητες

| Ονομα | Περιγραφή |
| --- | --- |
| [Extension](../../groupdocs.merger.domain/filetype/extension) { get; } | Επίθημα ονόματος αρχείου (συμπεριλαμβανομένης της περιόδου ".") π.χ. ".doc". |
| [FileFormat](../../groupdocs.merger.domain/filetype/fileformat) { get; } | Όνομα τύπου αρχείου π.χ. "Microsoft Word Document". |

## Μέθοδοι

| Ονομα | Περιγραφή |
| --- | --- |
| static [FromExtension](../../groupdocs.merger.domain/filetype/fromextension)(string) | Επέκταση αρχείου Χαρτών στον τύπο αρχείου. |
| [Equals](../../groupdocs.merger.domain/filetype/equals#equals)(FileType) | Καθορίζει εάν το ρεύμα[`FileType`](../filetype) είναι το ίδιο με αυτό που ορίζεται[`FileType`](../filetype) αντικείμενο. |
| override [Equals](../../groupdocs.merger.domain/filetype/equals#equals_1)(object) | Καθορίζει εάν το ρεύμα[`FileType`](../filetype) είναι το ίδιο με το καθορισμένο αντικείμενο. |
| override [GetHashCode](../../groupdocs.merger.domain/filetype/gethashcode)() | Επιστρέφει τον κωδικό κατακερματισμού για το τρέχον[`FileType`](../filetype) αντικείμενο. |
| override [ToString](../../groupdocs.merger.domain/filetype/tostring)() | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |
| static [GetSupportedFileTypes](../../groupdocs.merger.domain/filetype/getsupportedfiletypes)() | Ανακτά τους υποστηριζόμενους τύπους αρχείων |
| static [IsArchive](../../groupdocs.merger.domain/filetype/isarchive)(FileType) | Καθορίζει εάν εισάγεται[`FileType`](../filetype) είναι μορφή αρχείου. |
| static [IsImage](../../groupdocs.merger.domain/filetype/isimage)(FileType) | Καθορίζει εάν εισάγεται[`FileType`](../filetype) είναι μορφή εικόνας. |
| static [IsText](../../groupdocs.merger.domain/filetype/istext)(FileType) | Καθορίζει εάν εισάγεται[`FileType`](../filetype) είναι πρωτόγονη μορφή κειμένου. |
| [operator ==](../../groupdocs.merger.domain/filetype/op_equality) | Καθορίζει αν δύο[`FileType`](../filetype) τα αντικείμενα είναι ίδια. |
| [operator !=](../../groupdocs.merger.domain/filetype/op_inequality) | Καθορίζει αν δύο[`FileType`](../filetype) τα αντικείμενα δεν είναι ίδια. |

## Πεδία

| Ονομα | Περιγραφή |
| --- | --- |
| static [BMP](../../groupdocs.merger.domain/filetype/bmp) | Το αρχείο εικόνας bitmap (.bmp) αντιπροσωπεύει αρχεία που χρησιμοποιούνται για την αποθήκευση ψηφιακών εικόνων bitmap. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/image/bmp) . |
| static [BZ2](../../groupdocs.merger.domain/filetype/bz2) | Συμπιεσμένο αρχείο Bzip2 (.bz2) |
| static [CSV](../../groupdocs.merger.domain/filetype/csv) | Το αρχείο τιμών διαχωρισμένων με κόμματα (.csv) αντιπροσωπεύει αρχεία απλού κειμένου που περιέχουν εγγραφές δεδομένων με τιμές διαχωρισμένες με κόμμα. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/spreadsheet/csv) . |
| static [DOC](../../groupdocs.merger.domain/filetype/doc) | Το Το έγγραφο Microsoft Word (.doc) αντιπροσωπεύει έγγραφα που δημιουργούνται από το Microsoft Word ή άλλα έγγραφα επεξεργασίας κειμένου σε δυαδική μορφή αρχείου. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/word-processing/doc) . |
| static [DOCM](../../groupdocs.merger.domain/filetype/docm) | Τα αρχεία εγγράφου με δυνατότητα μακροεντολής XML (.docm) του Word Open είναι έγγραφα που δημιουργούνται από το Microsoft Word 2007 ή νεότερη έκδοση με δυνατότητα εκτέλεσης μακροεντολών. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/word-processing/docm) . |
| static [DOCX](../../groupdocs.merger.domain/filetype/docx) | Το Microsoft Word Open XML Document (.docx) είναι μια πολύ γνωστή μορφή για έγγραφα του Microsoft Word. Παρουσιάστηκε από το 2007 με την κυκλοφορία του Microsoft Office 2007, η δομή αυτής της νέας μορφής Εγγράφου άλλαξε από απλό δυαδικό σε συνδυασμό XML και δυαδικών αρχείων. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/word-processing/docx) . |
| static [DOT](../../groupdocs.merger.domain/filetype/dot) | Τα αρχεία προτύπου εγγράφου του Word (.dot) είναι αρχεία προτύπων που δημιουργούνται από το Microsoft Word για να έχουν προδιαμορφωμένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOC ή DOCX. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/word-processing/dot) . |
| static [DOTM](../../groupdocs.merger.domain/filetype/dotm) | Πρότυπο εγγράφου με δυνατότητα μακροεντολής XML Open XML (.dotm) αντιπροσωπεύει το αρχείο προτύπου που δημιουργήθηκε με Microsoft Word 2007 ή νεότερη έκδοση. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/word-processing/dotm) . |
| static [DOTX](../../groupdocs.merger.domain/filetype/dotx) | Word Open XML Document Template (.dotx) είναι αρχεία προτύπων που δημιουργήθηκαν από το Microsoft Word για να έχουν προδιαμορφωμένες ρυθμίσεις για τη δημιουργία περαιτέρω αρχείων DOCX. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/word-processing/dotx) . |
| static [EPUB](../../groupdocs.merger.domain/filetype/epub) | Το Open eBook File (.epub) είναι μια μορφή αρχείου ηλεκτρονικών βιβλίων που παρέχει μια τυπική μορφή ψηφιακής δημοσίευσης για εκδότες και καταναλωτές. Η μορφή ήταν τόσο κοινή μέχρι τώρα που υποστηρίζεται από πολλούς ηλεκτρονικούς αναγνώστες και εφαρμογές λογισμικού. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/ebook/epub) . |
| static [ERR](../../groupdocs.merger.domain/filetype/err) | Το αρχείο καταγραφής σφαλμάτων (.err) είναι ένα αρχείο κειμένου που περιέχει μηνύματα σφάλματος που δημιουργούνται από ένα πρόγραμμα. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://fileinfo.com/extension/err) . |
| static [GIF](../../groupdocs.merger.domain/filetype/gif) | Αρχείο μορφής γραφικής ανταλλαγής (.gif) |
| static [GZ](../../groupdocs.merger.domain/filetype/gz) | Συμπιεσμένο αρχείο G-Zip (.gz) |
| static [HTML](../../groupdocs.merger.domain/filetype/html) | Το αρχείο Hypertext Markup Language File (.html) είναι η επέκταση για ιστοσελίδες που δημιουργούνται για εμφάνιση σε προγράμματα περιήγησης. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/web/html) . |
| static [JPEG](../../groupdocs.merger.domain/filetype/jpeg) | Η εικόνα JPEG (.jpeg) είναι ένας τύπος μορφής εικόνας που αποθηκεύεται χρησιμοποιώντας τη μέθοδο συμπίεσης με απώλειες. Η εικόνα εξόδου, ως αποτέλεσμα της συμπίεσης, είναι μια αντιστάθμιση μεταξύ του μεγέθους αποθήκευσης και της ποιότητας της εικόνας. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/image/jpeg) . |
| static [JPG](../../groupdocs.merger.domain/filetype/jpg) | Εικόνα JPEG (.jpg) |
| static [MHT](../../groupdocs.merger.domain/filetype/mht) | Το MHTML Web Archive (.mht) είναι μια μορφή αρχείου ιστοσελίδων που μπορεί να δημιουργηθεί από πολλές διαφορετικές εφαρμογές. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/web/mhtml) . |
| static [MHTML](../../groupdocs.merger.domain/filetype/mhtml) | Το αρχείο MIME HTML (.mhtml) είναι μια μορφή αρχείου ιστοσελίδων που μπορεί να δημιουργηθεί από πολλές διαφορετικές εφαρμογές. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/web/mhtml) . |
| static [ODP](../../groupdocs.merger.domain/filetype/odp) | Η OpenDocument Presentation (.odp) αντιπροσωπεύει τη μορφή αρχείου παρουσίασης που χρησιμοποιείται από το OpenOffice.org στο πρότυπο OASISOpen. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/presentation/odp) . |
| static [ODS](../../groupdocs.merger.domain/filetype/ods) | Υπολογιστικό φύλλο OpenDocument (.ods) Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/spreadsheet/ods) . |
| static [ODT](../../groupdocs.merger.domain/filetype/odt) | Τα αρχεία OpenDocument Text Document (.odt) είναι τύποι εγγράφων που δημιουργούνται με εφαρμογές επεξεργασίας κειμένου που βασίζονται σε μορφή αρχείου κειμένου OpenDocument. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/word-processing/odt) . |
| static [ONE](../../groupdocs.merger.domain/filetype/one) | Τα αρχεία OneNote Document (.one) δημιουργούνται από την εφαρμογή Microsoft OneNote. Το OneNote σάς επιτρέπει να συλλέγετε πληροφορίες χρησιμοποιώντας την εφαρμογή σαν να χρησιμοποιείτε το draftpad για τη λήψη σημειώσεων. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/note-taking/one) . |
| static [OTP](../../groupdocs.merger.domain/filetype/otp) | Το Πρότυπο παρουσίασης OpenDocument (.otp) αντιπροσωπεύει αρχεία προτύπων παρουσίασης που δημιουργούνται από εφαρμογές σε τυπική μορφή OASIS OpenDocument. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/presentation/otp) . |
| static [OTT](../../groupdocs.merger.domain/filetype/ott) | Το Πρότυπο εγγράφου OpenDocument (.ott) αντιπροσωπεύει έγγραφα προτύπου που δημιουργούνται από εφαρμογές σε συμμόρφωση με την τυπική μορφή OpenDocument του OASIS. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/word-processing/ott) . |
| static [PDF](../../groupdocs.merger.domain/filetype/pdf) | Το Portable Document Format File (.pdf) είναι μια μορφή αρχείου που επρόκειτο να εισαχθεί ως πρότυπο για την αναπαράσταση εγγράφων και άλλου υλικού αναφοράς σε μορφή που είναι ανεξάρτητη από το λογισμικό εφαρμογής, το υλικό καθώς και το λειτουργικό σύστημα. Μάθετε περισσότερα για αυτό το αρχείο μορφή[εδώ](https://docs.fileformat.com/view/pdf) . |
| static [PNG](../../groupdocs.merger.domain/filetype/png) | Το Portable Network Graphic (.png) είναι ένας τύπος μορφής αρχείου εικόνας ράστερ που χρησιμοποιεί συμπίεση χωρίς απώλειες. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/image/png) . |
| static [PPS](../../groupdocs.merger.domain/filetype/pps) | Το PowerPoint Slide Show (.pps) είναι ένα αρχείο που δημιουργήθηκε με χρήση του Microsoft PowerPoint για προβολή παρουσίασης. Η ανάγνωση και η δημιουργία αρχείων PPS υποστηρίζεται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/presentation/pps) . |
| static [PPSX](../../groupdocs.merger.domain/filetype/ppsx) | Το PowerPoint Open XML Slide Show (.ppsx) είναι ένα αρχείο που δημιουργήθηκε με χρήση του Microsoft PowerPoint 2007 και άνω για σκοπούς προβολής διαφανειών. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/presentation/ppsx) . |
| static [PPT](../../groupdocs.merger.domain/filetype/ppt) | Η Παρουσίαση PowerPoint (.ppt) αντιπροσωπεύει το αρχείο PowerPoint που αποτελείται από μια συλλογή διαφανειών για εμφάνιση ως Παρουσίαση. Καθορίζει τη μορφή δυαδικού αρχείου που χρησιμοποιείται από το Microsoft PowerPoint 97-2003. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/presentation/ppt) . |
| static [PPTX](../../groupdocs.merger.domain/filetype/pptx) | Η PowerPoint Open XML Presentation (.pptx) είναι ένα αρχείο παρουσίασης που δημιουργήθηκε με τη δημοφιλή εφαρμογή Microsoft PowerPoint. Σε αντίθεση με την προηγούμενη έκδοση της μορφής αρχείου παρουσίασης PPT που ήταν δυαδική, η μορφή PPTX βασίζεται στη μορφή αρχείου παρουσίασης ανοιχτής XML του Microsoft PowerPoint. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/presentation/pptx) . |
| static [PS](../../groupdocs.merger.domain/filetype/ps) | Αρχείο PostScript (.ps) |
| static [RAR](../../groupdocs.merger.domain/filetype/rar) | Συμπιεσμένο αρχείο Roshal ARchive (.rar) |
| static [RTF](../../groupdocs.merger.domain/filetype/rtf) | Αρχείο μορφής εμπλουτισμένου κειμένου (.rtf) που εισήχθη και τεκμηριώθηκε από τη Microsoft, η Μορφή εμπλουτισμένου κειμένου (RTF) αντιπροσωπεύει μια μέθοδο κωδικοποίησης μορφοποιημένου κειμένου και γραφικών για χρήση σε εφαρμογές. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/word-processing/rtf) . |
| static [SevenZ](../../groupdocs.merger.domain/filetype/sevenz) | Συμπιεσμένο αρχείο 7-Zip (.7z) |
| static [TAR](../../groupdocs.merger.domain/filetype/tar) | Ενοποιημένο αρχείο Unix (.tar) |
| static [TEX](../../groupdocs.merger.domain/filetype/tex) | Το LaTeX Source Document (.tex) είναι μια γλώσσα που περιλαμβάνει προγραμματισμό καθώς και χαρακτηριστικά σήμανσης, που χρησιμοποιούνται για τη στοιχειοθεσία εγγράφων. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/page-description-language/tex) . |
| static [TIF](../../groupdocs.merger.domain/filetype/tif) | Αρχείο εικόνας με ετικέτα (.tif) |
| static [TIFF](../../groupdocs.merger.domain/filetype/tiff) | Μορφή αρχείου εικόνας με ετικέτα (.tiff) |
| static [TSV](../../groupdocs.merger.domain/filetype/tsv) | Το αρχείο τιμών διαχωρισμένων με καρτέλες (.tsv) αντιπροσωπεύει δεδομένα διαχωρισμένα με καρτέλες σε μορφή απλού κειμένου. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/spreadsheet/tsv) . |
| static [TXT](../../groupdocs.merger.domain/filetype/txt) | Το αρχείο απλού κειμένου (.txt) αντιπροσωπεύει ένα έγγραφο κειμένου που περιέχει απλό κείμενο με τη μορφή γραμμών. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/word-processing/txt) . |
| static [Unknown](../../groupdocs.merger.domain/filetype/unknown) | Αντιπροσωπεύει άγνωστο τύπο αρχείου. |
| static [VDX](../../groupdocs.merger.domain/filetype/vdx) | Το Το αρχείο XML σχεδίασης του Visio (.vdx) είναι ένα σχέδιο ή γράφημα που δημιουργήθηκε στο Microsoft Visio, αλλά που είναι αποθηκευμένο σε μορφή XML έχει επέκταση .VDX. Ένα αρχείο XML σχεδίασης Visio δημιουργείται στο λογισμικό Visio, το οποίο έχει αναπτυχθεί από τη Microsoft. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/image/vdx) . |
| static [VSDM](../../groupdocs.merger.domain/filetype/vsdm) | Το Visio Macro-Enabled Drawing (.vsdm) είναι αρχεία σχεδίασης που έχουν δημιουργηθεί με την εφαρμογή Microsoft Visio που υποστηρίζει μακροεντολές. Τα αρχεία VSDM είναι σχέδια OPC/XML που είναι παρόμοια με το VSDX, αλλά παρέχουν επίσης τη δυνατότητα εκτέλεσης μακροεντολών όταν ανοίγει το αρχείο. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/image/vsdm) . |
| static [VSDX](../../groupdocs.merger.domain/filetype/vsdx) | Το Το Σχέδιο Visio (.vsdx) αντιπροσωπεύει τη μορφή αρχείου του Microsoft Visio που εισήχθη από το Microsoft Office 2013 και μετά. Αναπτύχθηκε για να αντικαταστήσει τη μορφή δυαδικού αρχείου, .VSD, η οποία υποστηρίζεται από προηγούμενες εκδόσεις του Microsoft Visio. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/image/vsdx) . |
| static [VSSM](../../groupdocs.merger.domain/filetype/vssm) | Το Visio Macro-Enabled Stencil File (.vssm) είναι αρχεία Stencil του Microsoft Visio που υποστηρίζουν την παροχή υποστήριξης για μακροεντολές. Ένα αρχείο VSSM όταν ανοίγει επιτρέπει την εκτέλεση των μακροεντολών για την επίτευξη της επιθυμητής μορφοποίησης και τοποθέτησης σχημάτων σε ένα διάγραμμα. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/image/vssm) . |
| static [VSSX](../../groupdocs.merger.domain/filetype/vssx) | Το Visio Stencil File (.vssx) είναι στένσιλ σχεδίασης που δημιουργήθηκαν με το Microsoft Visio 2013 και νεότερη έκδοση. Η μορφή αρχείου VSSX μπορεί να ανοίξει με το Visio 2013 και μεταγενέστερη έκδοση. Τα αρχεία Visio είναι γνωστά για την αναπαράσταση μιας ποικιλίας στοιχείων σχεδίασης, όπως συλλογή σχημάτων, συνδέσεις, διαγράμματα ροής, διάταξη δικτύου, διαγράμματα UML, Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/image/vssx) . |
| static [VSTM](../../groupdocs.merger.domain/filetype/vstm) | Το Πρότυπο σχεδίασης με δυνατότητα μακροεντολής του Visio (.vstm) είναι αρχεία προτύπων που δημιουργήθηκαν με το Microsoft Visio και υποστηρίζουν μακροεντολές. Σε αντίθεση με τα αρχεία VSDX, τα αρχεία που δημιουργούνται από πρότυπα VSTM μπορούν να εκτελούν μακροεντολές που έχουν αναπτυχθεί σε κώδικα Visual Basic for Applications (VBA). Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/image/vstm) . |
| static [VSTX](../../groupdocs.merger.domain/filetype/vstx) | Το Πρότυπο σχεδίασης του Visio (.vstx) είναι αρχεία προτύπων σχεδίασης που έχουν δημιουργηθεί με το Microsoft Visio 2013 και νεότερη έκδοση. Αυτά τα αρχεία VSTX παρέχουν το σημείο εκκίνησης για τη δημιουργία σχεδίων Visio, αποθηκευμένα ως αρχεία .VSDX, με προεπιλεγμένη διάταξη και ρυθμίσεις. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/image/vstx) . |
| static [VSX](../../groupdocs.merger.domain/filetype/vsx) | Το αρχείο Visio Stencil XML (.vsx) αναφέρεται σε στένσιλ που αποτελούνται από σχέδια και σχήματα που χρησιμοποιούνται για τη δημιουργία διαγραμμάτων στο Microsoft Visio. Τα αρχεία VSX αποθηκεύονται σε μορφή αρχείου XML και υποστηρίζονταν μέχρι το Visio 2013. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/image/vsx) . |
| static [VTX](../../groupdocs.merger.domain/filetype/vtx) | Το Πρότυπο Visio Αρχείο XML (.vtx) είναι ένα πρότυπο σχεδίασης του Microsoft Visio που αποθηκεύεται σε δίσκο σε μορφή αρχείου XML. Το πρότυπο έχει ως στόχο να παρέχει ένα αρχείο με βασικές ρυθμίσεις που μπορούν να χρησιμοποιηθούν για τη δημιουργία πολλών αρχείων Visio με τις ίδιες ρυθμίσεις. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/image/vtx) . |
| static [XLAM](../../groupdocs.merger.domain/filetype/xlam) | Πρόσθετο με δυνατότητα Macro-Enabled Excel (.xlam) |
| static [XLS](../../groupdocs.merger.domain/filetype/xls) | Το Excel Spreadsheet (.xls) είναι ένα αρχείο που μπορεί να δημιουργηθεί από το Microsoft Excel καθώς και από άλλα παρόμοια προγράμματα υπολογιστικών φύλλων όπως το OpenOffice Calc ή το Apple Numbers. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/spreadsheet/xls) . |
| static [XLSB](../../groupdocs.merger.domain/filetype/xlsb) | Η μορφή αρχείου του δυαδικού υπολογιστικού φύλλου του Excel (.xlsb) καθορίζει τη Μορφή δυαδικού αρχείου του Excel, η οποία είναι μια συλλογή εγγραφών και δομών που καθορίζουν το περιεχόμενο του βιβλίου εργασίας του Excel. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/spreadsheet/xlsb) . |
| static [XLSM](../../groupdocs.merger.domain/filetype/xlsm) | Το Excel Open XML Macro-Enabled Spreadsheet (.xlsm) είναι ένας τύπος αρχείων υπολογιστικού φύλλου που υποστηρίζουν μακροεντολές. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/spreadsheet/xlsm) . |
| static [XLSX](../../groupdocs.merger.domain/filetype/xlsx) | Το Microsoft Excel Open XML Spreadsheet (.xlsx) είναι μια πολύ γνωστή μορφή για έγγραφα του Microsoft Excel που εισήχθη από τη Microsoft με την κυκλοφορία του Microsoft Office 2007. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/spreadsheet/xlsx) . |
| static [XLT](../../groupdocs.merger.domain/filetype/xlt) | Το Excel Template File (.xlt) είναι αρχεία προτύπων που δημιουργούνται με το Microsoft Excel, το οποίο είναι μια εφαρμογή υπολογιστικών φύλλων που διατίθεται ως μέρος της σουίτας του Microsoft Office. Το Microsoft Office 97-2003 υποστήριξε τη δημιουργία νέων αρχείων XLT καθώς και το άνοιγμα αυτών. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/spreadsheet/xlt) . |
| static [XLTM](../../groupdocs.merger.domain/filetype/xltm) | Πρότυπο υπολογιστικού φύλλου με δυνατότητα μακροεντολής (.xltm) του Excel Open XML (.xltm) αντιπροσωπεύει αρχεία που δημιουργούνται από το Microsoft Excel ως αρχεία προτύπων με δυνατότητα μακροεντολής. Τα αρχεία XLTM είναι παρόμοια με τα XLTX σε δομή, εκτός από το ότι το τελευταίο δεν υποστηρίζει τη δημιουργία αρχείων προτύπων με μακροεντολές. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/spreadsheet/xltm) . |
| static [XLTX](../../groupdocs.merger.domain/filetype/xltx) | Τα αρχεία προτύπου υπολογιστικού φύλλου ανοιχτού XML του Excel (.xltx) βασίζονται στις προδιαγραφές μορφής αρχείου του Office OpenXML. Χρησιμοποιείται για τη δημιουργία ενός τυπικού αρχείου προτύπου που μπορεί να χρησιμοποιηθεί για τη δημιουργία αρχείων XLSX που εμφανίζουν τις ίδιες ρυθμίσεις με αυτές που καθορίζονται στο αρχείο XLTX. Μάθετε περισσότερα για αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/spreadsheet/xltx) . |
| static [XPS](../../groupdocs.merger.domain/filetype/xps) | Το XML Paper Specification File (.xps) αντιπροσωπεύει αρχεία διάταξης σελίδας που βασίζονται σε Προδιαγραφές χαρτιού XML που δημιουργήθηκαν από τη Microsoft. Μάθετε περισσότερα σχετικά με αυτήν τη μορφή αρχείου[εδώ](https://docs.fileformat.com/page-description-language/xps) . |
| static [ZIP](../../groupdocs.merger.domain/filetype/zip) | Συμπιεσμένο αρχείο (.zip) |

### Παρατηρήσεις

**Μάθε περισσότερα**

* Μάθετε περισσότερα σχετικά με τις μορφές αρχείων που υποστηρίζονται από το GroupDocs.Merger: [Πλήρης λίστα υποστηριζόμενων μορφών εγγράφων](https://docs.groupdocs.com/display/mergernet/Supported+Document+Types)
* Μάθετε περισσότερα σχετικά με τη λήψη υποστηριζόμενων τύπων αρχείων σε κώδικα: [Πώς να λάβετε υποστηριζόμενες μορφές αρχείων σε κώδικα](https://docs.groupdocs.com/display/mergernet/Get+supported+file+types)

### Δείτε επίσης

* χώρος ονομάτων [GroupDocs.Merger.Domain](../../groupdocs.merger.domain)
* συνέλευση [GroupDocs.Merger](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Merger.dll -->
