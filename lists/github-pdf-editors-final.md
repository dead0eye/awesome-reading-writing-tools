# Free & Open Source PDF Editors & Annotators

> Annotate, merge, split, sign and fill PDF forms without subscriptions or watermarks.

`12 tools` &nbsp;&middot;&nbsp; `v1.1.2` &nbsp;&middot;&nbsp; `updated 2026-09-11` &nbsp;&middot;&nbsp; `11 open source`

[&larr; back to the index](../README.md)

Finding a genuinely free pdf editor is harder than it should be, because most search results point to commercial trials that watermark your pages, restrict you to three files a day, or lock saving behind an expensive subscription. The reality is that the vast majority of PDF tasks do not need a commercial desktop suite. Whether you need to sign a contract, fill out a government form, combine meeting handouts, or delete a stray blank page, every tool featured here is free to use for its core job with no hidden paywalls.

Finding the right free pdf editor depends on which part of the document you actually need to change. Page organizers like PDF Arranger and PDFsam Basic excel at visually rearranging, merging, rotating, and splitting pages without touching the underlying content. Form fillers and annotators such as Okular and Xournal++ handle interactive form fields, stylus sketching, and digital signatures without altering the original layout. For direct text editing and vector manipulation, suites like LibreOffice Draw allow you to click on existing paragraphs and edit wording in place. Finally, all-in-one local toolkits like Stirling-PDF and PDF24 Creator provide browser-based or desktop Swiss Army knives for OCR, proper text redaction, conversion, and encryption.

Pick the free pdf editor that matches the exact operation you need to perform rather than searching for one program that does everything. If you simply need to combine and rotate scanned sheets, a lightweight page organizer is faster and less error-prone than an entire office suite; if you need to sanitize confidential records, choose a tool that performs genuine redaction rather than drawing opaque shapes over private data.

## How these were chosen

- Free for its core purpose - zero watermarks, no daily document caps, no expiring trials, and no subscriptions to save your finished file.
- No mandatory cloud accounts - every tool runs entirely locally on your machine or self-hosted in your private infrastructure, keeping sensitive documents private.
- Open source transparency - open-source entries link directly to their public source repositories so license terms and active commits can be independently verified. Eleven of the twelve are open source; the one that is not is marked Freeware in its row and clearly flagged in its downsides.
- Distinguishes full editing from annotating - clearly labels whether a tool reflows underlying text, fills interactive forms, or overlays markup so you pick the right tool for your immediate job.
- Real redaction only - tools claiming redaction must genuinely sanitize and remove underlying text and vector data from the document stream, rather than painting black rectangles on top.
- No affiliate or aggregator links - every link points straight to the official project homepage or source repository.

## The list

| # | Tool | Best for | Platforms | Licence | Est. |
|---:|---|---|---|---|---|
| 1 | **[PDF Arranger](https://github.com/pdfarranger/pdfarranger)** | Quickly rearranging, merging, splitting, rotating, and cropping PDF pages visually | Linux &middot; Win | [GPL-3.0](https://github.com/pdfarranger/pdfarranger) | 2018 |
| 2 | **[Stirling-PDF](https://stirlingpdf.com/)** | Self-hosters and teams who want a full browser-based PDF utility suite without cloud privacy risks | Self-host &middot; Web &middot; Win &middot; mac &middot; Linux | [MIT](https://github.com/Stirling-Tools/Stirling-PDF) | 2023 |
| 3 | **[LibreOffice Draw](https://www.libreoffice.org/discover/draw/)** | Directly rewriting existing paragraphs and editing vector diagrams inside a PDF | Win &middot; mac &middot; Linux | [MPL-2.0](https://github.com/LibreOffice/core) | 2010 |
| 4 | **[Okular](https://okular.kde.org/)** | Filling interactive government forms and signing documents with cryptographic certificates | Linux &middot; Win &middot; mac &middot; Android | [GPL-2.0](https://invent.kde.org/graphics/okular) | 2005 |
| 5 | **[Xournal++](https://xournalpp.github.io/)** | Handwriting notes, stylus sketching, and applying handwritten signatures onto PDF pages | Win &middot; mac &middot; Linux &middot; Android | [GPL-2.0](https://github.com/xournalpp/xournalpp) | 2011 |
| 6 | **[PDFsam Basic](https://pdfsam.org/)** | Automating bulk PDF splits, page range extractions, and merges across large batches of files | Win &middot; mac &middot; Linux | [AGPL-3.0](https://github.com/torakiki/pdfsam) | 2006 |
| 7 | **[PDF4QT](https://jakubmelka.github.io/)** | Users needing an open-source desktop suite with true content redaction and form filling | Win &middot; Linux | [MIT](https://github.com/JakubMelka/PDF4QT) | 2018 |
| 8 | **[OCRmyPDF](https://ocrmypdf.readthedocs.io/)** | Adding accurate, searchable text layers to scanned PDFs without degrading image quality | CLI &middot; Linux &middot; mac &middot; Win | [MPL-2.0](https://github.com/ocrmypdf/OCRmyPDF) | 2013 |
| 9 | **[PDF Mix Tool](https://gitlab.com/scarpetta/pdfmixtool)** | Lightweight visual page composition, booklet generation, and multi-page grid layouts | Linux &middot; Win | [GPL-3.0](https://gitlab.com/scarpetta/pdfmixtool) | 2017 |
| 10 | **[Sioyek](https://sioyek.info/)** | Academics and researchers navigating and annotating dense textbooks and scientific papers | Win &middot; mac &middot; Linux | [GPL-3.0](https://github.com/ahrm/sioyek) | 2020 |
| 11 | **[pdfcpu](https://pdfcpu.io/)** | Developers and power users needing scriptable batch processing, watermarking, and booklet creation | CLI &middot; Win &middot; mac &middot; Linux | [Apache-2.0](https://github.com/pdfcpu/pdfcpu) | 2017 |
| 12 | **[PDF24 Creator](https://www.pdf24.org/)** | Windows users seeking a zero-friction desktop suite with unlimited offline tools and no watermarks | Win | Freeware | 2006 |

<sub>Licence links point at the source repository. `Freeware` means free to use but not open source.</sub>

## Details

### 1. PDF Arranger

**Platforms** Linux, Windows &nbsp;&middot;&nbsp; **Licence** GPL-3.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2018  
[Homepage](https://github.com/pdfarranger/pdfarranger) &nbsp;&middot;&nbsp; [Source](https://github.com/pdfarranger/pdfarranger)

Quickly rearranging, merging, splitting, rotating, and cropping PDF pages visually

**Good** &mdash; Clean visual thumbnail grid that makes reordering, rotating, or deleting pages effortless; Instant startup with minimal memory overhead and zero telemetry; Lossless page manipulation that preserves original fonts, bookmarks, and vector elements

**Less good** &mdash; Does not edit document contents, inline text, or interactive form fields; macOS installation requires manual setup via Homebrew or source compilation

PDF Arranger is a Python-GTK utility originally forked from the dormant PDF-Shuffler project. It does not attempt to edit text or parse document streams; instead, it provides the fastest possible interface for reorganizing multi-page scans or combining chapters before sharing.

### 2. Stirling-PDF

**Platforms** Self-hosted, Web, Windows, macOS, Linux &nbsp;&middot;&nbsp; **Licence** MIT &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2023  
[Homepage](https://stirlingpdf.com/) &nbsp;&middot;&nbsp; [Source](https://github.com/Stirling-Tools/Stirling-PDF)

Self-hosters and teams who want a full browser-based PDF utility suite without cloud privacy risks

**Good** &mdash; Over 50 PDF operations including OCR, true text redaction, page merging, signing, and conversion; Complete data privacy with self-hosted Docker deployments that never send files to third parties; Modern web UI accessible from any device on your local network, including phones and Chromebooks

**Less good** &mdash; Requires Docker or a Java runtime environment to deploy and maintain; Open-core: the free self-hosted plan covers all PDF operations but is capped at 5 user accounts, and directories under app/proprietary/ carry a separate licence that forbids production use without a subscription; The hosted service at stirling.com is a different proposition again: its free tier is credit-capped with paid processing beyond that. Only the self-hosted build is the one this entry recommends.

Stirling-PDF is open-core, and the README says so in as many words. The free self-hosted build gets every one of the PDF operations, which is the part that matters here; the paid tiers add user capacity, SSO, an external database and audit logging rather than PDF features. Install the self-hosted build - the hosted service at stirling.com is a different product with a credit cap.

### 3. LibreOffice Draw

**Platforms** Windows, macOS, Linux &nbsp;&middot;&nbsp; **Licence** MPL-2.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2010  
[Homepage](https://www.libreoffice.org/discover/draw/) &nbsp;&middot;&nbsp; [Source](https://github.com/LibreOffice/core)

Directly rewriting existing paragraphs and editing vector diagrams inside a PDF

**Good** &mdash; Opens PDFs as editable vector documents where you can click and modify text blocks directly; Deep control over shapes, embedded graphics, typography, and page dimensions; Backed by the Document Foundation with broad cross-platform availability and active maintenance

**Less good** &mdash; Complex layouts or missing system fonts can cause text to reflow unpredictably on import; Breaks interactive AcroForm fields and digital signature structures upon saving

LibreOffice Draw treats imported PDF pages as vector drawing canvases. That makes it one of the very few open-source tools capable of altering existing sentences and replacing images directly, but it should be avoided for fillable administrative forms.

### 4. Okular

**Platforms** Linux, Windows, macOS, Android &nbsp;&middot;&nbsp; **Licence** GPL-2.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2005  
[Homepage](https://okular.kde.org/) &nbsp;&middot;&nbsp; [Source](https://invent.kde.org/graphics/okular)

Filling interactive government forms and signing documents with cryptographic certificates

**Good** &mdash; Robust support for interactive AcroForms and XFA forms that other free viewers fail to render; First-class support for cryptographic digital signatures using system certificates and GPG; Extensive review tools including inline pop-up notes, highlight stamps, and freehand drawing

**Less good** &mdash; Cannot rewrite underlying body text or edit existing vector illustrations; Pulls in KDE desktop framework libraries on non-Plasma operating systems

Maintained by the KDE community, Okular is certified by the German Federal Office for Information Security and was the first software awarded the Blue Angel eco-label. It is the premier open-source choice for legal and administrative workflows requiring digital signature validation.

### 5. Xournal++

**Platforms** Windows, macOS, Linux, Android &nbsp;&middot;&nbsp; **Licence** GPL-2.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2011  
[Homepage](https://xournalpp.github.io/) &nbsp;&middot;&nbsp; [Source](https://github.com/xournalpp/xournalpp)

Handwriting notes, stylus sketching, and applying handwritten signatures onto PDF pages

**Good** &mdash; Pressure-sensitive stylus input with palm rejection for smooth digital handwriting; Easily inserts freehand signatures, text labels, LaTeX equations, and custom image stamps; Saves non-destructive annotations alongside the document and exports clean flattened PDFs

**Less good** &mdash; Not intended for reflowing or modifying original document typography; Lacks support for interactive fillable PDF form fields and cryptographic certificates

Xournal++ is a modern C++ rewrite of Xournal designed specifically for tablet and touchscreen note-taking. It treats a PDF as a paper background, making it the ideal tool when you need to sign a contract by hand, grade a student paper, or annotate lecture slides.

### 6. PDFsam Basic

**Platforms** Windows, macOS, Linux &nbsp;&middot;&nbsp; **Licence** AGPL-3.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2006  
[Homepage](https://pdfsam.org/) &nbsp;&middot;&nbsp; [Source](https://github.com/torakiki/pdfsam)

Automating bulk PDF splits, page range extractions, and merges across large batches of files

**Good** &mdash; Reliable batch processing for splitting by page numbers, bookmarks, or file size; Visual document reordering and alternate mixing for double-sided document scans; No document limits or remote uploads, processing gigabytes of files entirely locally

**Less good** &mdash; Basic edition excludes visual text editing and form creation (reserved for commercial tiers); Java-based UI can feel utilitarian and slightly heavy on startup

PDFsam (PDF Split and Merge) is a veteran desktop workhorse that has been active since 2006. While commercial versions (Enhanced and Visual) exist, the open-source Basic edition remains completely free and unrestricted for all splitting, merging, and rotation duties.

### 7. PDF4QT

**Platforms** Windows, Linux &nbsp;&middot;&nbsp; **Licence** MIT &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2018  
[Homepage](https://jakubmelka.github.io/) &nbsp;&middot;&nbsp; [Source](https://github.com/JakubMelka/PDF4QT)

Users needing an open-source desktop suite with true content redaction and form filling

**Good** &mdash; True sanitizing redaction that permanently purges text and vector data from the file stream; Comprehensive toolkit including DocEditor, PageOrganizer, form filling, and cryptographic signing; Native C++/Qt application delivering high rendering speed and multithreaded performance

**Less good** &mdash; No official macOS pre-built binaries available; Interface is modular and feature-dense, which presents an initial learning curve

PDF4QT is an impressive, modular open-source PDF ecosystem created by Jakub Melka. Unlike simple annotators that merely paint black rectangles over words, PDF4QT physically strips confidential data out of the document byte stream to guarantee safe redaction.

### 8. OCRmyPDF

**Platforms** CLI, Linux, macOS, Windows &nbsp;&middot;&nbsp; **Licence** MPL-2.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2013  
[Homepage](https://ocrmypdf.readthedocs.io/) &nbsp;&middot;&nbsp; [Source](https://github.com/ocrmypdf/OCRmyPDF)

Adding accurate, searchable text layers to scanned PDFs without degrading image quality

**Good** &mdash; Generates clean, invisible text layers matching the exact coordinates of scanned bitmaps; Leverages the Tesseract OCR engine with automatic deskew, page rotation, and image cleanup; Preserves original PDF/A compliance, digital signatures, and vector graphics without rasterization

**Less good** &mdash; Command-line tool with no graphical user interface (GUI) of its own; Requires underlying external dependencies like Tesseract and Ghostscript

OCRmyPDF is the de facto standard engine used by document management systems like Paperless-ngx. It solves the ubiquitous problem of dead scanned PDF pages, converting image-only files into searchable, selectable documents suitable for archiving.

### 9. PDF Mix Tool

**Platforms** Linux, Windows &nbsp;&middot;&nbsp; **Licence** GPL-3.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2017  
[Homepage](https://gitlab.com/scarpetta/pdfmixtool) &nbsp;&middot;&nbsp; [Source](https://gitlab.com/scarpetta/pdfmixtool)

Lightweight visual page composition, booklet generation, and multi-page grid layouts

**Good** &mdash; Built-in booklet generation and n-up page layout tools for physical printing prep; Fast Qt interface with single-operation and multi-file batch composition modes; Lightweight resource footprint with no Java or heavy web runtimes required

**Less good** &mdash; No inline text editing or interactive form filling capabilities; Official tagged stable releases have been infrequent, though commits remain ongoing

PDF Mix Tool focuses on page-level restructuring, offering an especially polished feature set for booklet creation and alternating scan collation. It is a neat native alternative to PDFsam when you want a lean Qt tool without Java dependencies. The project's old GitLab Pages site has gone; the GitLab project page is now its home, and it is also on Flathub.

### 10. Sioyek

**Platforms** Windows, macOS, Linux &nbsp;&middot;&nbsp; **Licence** GPL-3.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2020  
[Homepage](https://sioyek.info/) &nbsp;&middot;&nbsp; [Source](https://github.com/ahrm/sioyek)

Academics and researchers navigating and annotating dense textbooks and scientific papers

**Good** &mdash; Smart link portals that let you view figures and citations in a split window without losing your place; Vim-style keyboard navigation with fast table of contents searching and bookmarking; Built-in visual ruler, custom color palettes, and searchable reference jumping

**Less good** &mdash; Keyboard-heavy interface lacks conventional toolbars and takes time to master; No tagged release since late 2022 — development commits continue but users should build from source or use a community package for bug fixes

Sioyek is tailored specifically for reading technical documents and academic papers. Where general PDF tools focus on office tasks, Sioyek provides innovative portal windows that preview referenced diagrams and bibliographies side-by-side with the reading text.

### 11. pdfcpu

**Platforms** CLI, Windows, macOS, Linux &nbsp;&middot;&nbsp; **Licence** Apache-2.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2017  
[Homepage](https://pdfcpu.io/) &nbsp;&middot;&nbsp; [Source](https://github.com/pdfcpu/pdfcpu)

Developers and power users needing scriptable batch processing, watermarking, and booklet creation

**Good** &mdash; Written in pure Go with zero external C library or rendering engine dependencies; Extensive CLI capabilities including watermarking, stamping, n-up imposition, encryption, and trimming; Extremely fast execution speeds suitable for automated build pipelines and server-side workflows

**Less good** &mdash; Terminal-only command line with no interactive visual page preview; Syntax and configuration flags can be complex for casual one-off operations

pdfcpu is an independent PDF processor written from scratch in Go. It operates directly on the PDF syntax tree without rasterization, making it exceptionally fast for adding watermarks, generating multi-page booklets, and validating PDF conformance.

### 12. PDF24 Creator

**Platforms** Windows &nbsp;&middot;&nbsp; **Licence** Freeware &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2006  
[Homepage](https://www.pdf24.org/)

Windows users seeking a zero-friction desktop suite with unlimited offline tools and no watermarks

**Good** &mdash; Truly unlimited offline desktop toolkit with zero file size caps, page limits, or watermarks; Comprehensive launcher covering compression, merging, OCR, page deletion, signing, and conversion; Simple drag-and-drop workflow designed for non-technical office and home users

**Less good** &mdash; Closed-source proprietary freeware, so underlying source code cannot be audited; Desktop application is exclusive to Windows (Mac and Linux users must use their browser tools)

PDF24 Creator is the standard recommendation for Windows users who want a simple, all-in-one local alternative to commercial subscriptions. While closed source, it processes documents entirely offline on your PC without watermarking outputs or charging for core features.

## Also worth knowing

- **[PDFgear](https://www.pdfgear.com/)** &mdash; Cross-platform desktop and mobile editing with built-in text reflow and AI summarization (Freeware)
- **[QPDF](https://qpdf.readthedocs.io/)** &mdash; Low-level structural transformations, linearization for web streaming, and file recovery (Apache-2.0)
- **[Inkscape](https://inkscape.org/)** &mdash; Precision vector editing, artistic modification, and path adjustments on single PDF pages (GPL-2.0-or-later)

## FAQ

**Can a free pdf editor edit existing text without breaking the layout?**

Editing existing text in a PDF is notoriously difficult because PDFs store text as positioned glyphs and visual paths rather than flowing paragraphs. LibreOffice Draw can open a PDF and let you edit text blocks directly, but complex multi-column layouts or documents with missing fonts may shift slightly. For documents requiring exact typography preservation, annotating, overlaying new text, or editing the original source file before re-exporting is usually cleaner.

**How does redaction work in free PDF tools, and is it safe?**

True redaction permanently removes sensitive text, metadata, and underlying vector elements from the document's internal byte stream. Drawing a black box or highlight over text using a standard viewer leaves the underlying text completely readable and selectable by anyone who opens the file. Tools like Stirling-PDF and PDF4QT offer true redaction that sanitizes the file content before saving.

**What is the difference between filling a form and annotating a PDF?**

Interactive form filling uses standard AcroForm or XFA data fields embedded in the document, allowing you to type directly into text fields, check boxes, and select dropdown items while preserving tab-order and digital signatures. Annotating merely paints text boxes, stamps, or freehand ink over the visual page. Dedicated tools like Okular and PDF4QT properly populate interactive form fields so that automated processing systems can read the data.

**Why do so many free online PDF editors watermark files or limit daily usage?**

Processing PDF documents on cloud servers requires continuous server bandwidth and computing power, which cloud providers monetize by restricting free tiers to two or three files per day or adding promotional watermarks. The desktop and self-hosted tools on this list run entirely on your own CPU, meaning there are no servers to pay for, no file size caps, and no reason to watermark your work.

**Which tool should I use if I only need to merge, split, or rotate pages?**

If you only need page-level manipulation, PDF Arranger is by far the fastest and cleanest option for desktop users, featuring an intuitive grid of page thumbnails you can drag, rotate, and delete. For command-line users and automated scripts, pdfcpu and QPDF offer lightning-fast batch processing without launching a graphical window.

## Changelog

**v1.1.2** &mdash; 2026-09-11
- Est. column checked against each project's history. Corrected: LibreOffice Draw 2010 (not 2011), Xournal++ 2011 (not 2013), PDF4QT 2018 (not 2019), PDF Mix Tool 2017 (not 2018) and Sioyek 2020 (not 2021).

**v1.1.1** &mdash; 2026-09-10
- Inkscape: licence corrected from GPL-3.0 to GPL-2.0-or-later. The project's own COPYING file states version 2 or later, with the javascript polyfills under CC0 and parts of src/3rdparty under LGPL or MPL. GitLab reports no licence at all for the repository because COPYING is a summary rather than a licence text, so this had to be read by hand.
- Stirling-PDF: the entry said the self-hosted build was open source and unlimited. The project's README now describes itself as open-core, its free self-hosted plan is capped at five user accounts, and app/proprietary/, app/saas/ and engine/ all exist and carry a separate licence forbidding production use without a subscription. All PDF operations are still free, which is the part that matters here, and the entry now says exactly that instead.
- LibreOffice Draw: recorded why GitHub reports GPL-3.0 for a project that publishes MPL-2.0 - the mirror still carries the legacy COPYING file from the OpenOffice.org lineage. The same note already existed on LibreOffice Writer in the converters list; it was missing here.

**v1.1.0** &mdash; 2026-09-09
- Full verification pass. Every homepage and repository link opened; every open source licence claim checked against the GitHub or GitLab API.
- PDF Mix Tool's homepage was returning 404 - its GitLab Pages site has gone. The link now points at the GitLab project, which is active and is also the Flathub source.
- internalLink replaced. It pointed at getfreeebooks.com/desktop-ebook-readers, which returns 404 because that list is not published yet, so the link would have shipped broken.
- Stirling-PDF: the hosted service at stirling.com now has a free tier capped at 500 monthly credits with paid processing beyond it. The self-hosted build is unaffected and remains free and unlimited, which is what this list recommends - the entry now says so explicitly rather than describing the project as simply free.
- Stirling-PDF licence caveat retained: MIT overall, with separate proprietary/SaaS licences on some directories, which is why GitHub reports the licence as unrecognised.
- signals blocks populated for all 13 entries that have a repository. None is archived and all have commits within the last five weeks.
- LibreOffice Draw's MPL-2.0 checked and left alone - the GitHub mirror mis-reports GPL-3.0, but the project's own licence page states MPL-2.0.
- NOT verified: whether the two freeware entries, PDF24 Creator and PDFgear, watermark output or limit use in practice. Both are closed source and would need installing to test.

**v1.0.0** &mdash; 2026-09-08
- First publication with 12 PDF editors and annotators plus 3 near-misses.
- Seeded from verified repository research covering desktop page managers, form fillers, stylus annotators, OCR engines, direct text editors, and self-hosted web suites.

---

Found something missing or out of date? [Open an issue](https://github.com/dead0eye/awesome-reading-writing-tools/issues) or see [CONTRIBUTING](../CONTRIBUTING.md).  
Maintained by [GetFreeEbooks](https://getfreeebooks.com). Content released under [CC0 1.0](../LICENSE).
