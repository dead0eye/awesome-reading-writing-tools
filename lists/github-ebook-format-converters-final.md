# Free & Open Source Ebook Format Converters

> Convert EPUB, PDF, MOBI, AZW3 and more without uploading your books to anyone.

`9 tools` &nbsp;&middot;&nbsp; `v1.1.1` &nbsp;&middot;&nbsp; `updated 2026-09-11` &nbsp;&middot;&nbsp; `9 open source`

[&larr; back to the index](../README.md)

A free ebook converter should not ask you to upload your library to a stranger's server. That is the first thing to check, and it rules out most of what a search returns: the top results are almost entirely web uploaders with a daily cap, a file-size limit, a watermark, or a sign-up wall before you can download your own file back.

Everything below runs on your own machine. All nine are open source with a licence you can check in one click, and the one that looks like a web tool runs entirely inside your browser tab and never sends the file anywhere. None charges for core use, none limits how many files you convert, and none needs an account.

The honest caveat first: this bench is genuinely small. There are perhaps four tools most people will ever need, and a handful of specialists behind them. A free ebook converter list that runs to twenty entries is padding, and in this category padding means upload sites.

## How these were chosen

- Nothing that requires uploading your book to somebody else's server. This single rule removes almost the entire first page of search results, and it is the main reason this list exists.
- Free for its core purpose - no daily cap, no file-size limit, no watermark, and no account needed to download your own converted file.
- Open source, with the source linked so the licence claim can be checked. Eight of the nine link to a public git repository; k2pdfopt is the exception - it is distributed as source tarballs from the author's own site, which its row says plainly.
- Listed once, by engine. Several 'different' converters are wrappers around Calibre's ebook-convert, and listing them as independent options would be padding - the command-line route is noted against Calibre instead.
- Honest about PDF. Every converter claims PDF to EPUB; almost none does it well on a multi-column or scanned file. Where a tool is listed for that job, its downsides say what actually happens.
- The list is short on purpose. Nine tools is what genuinely exists here without resorting to upload sites, and a short accurate list is worth more than a padded one.
- DRM is out of scope entirely. These convert files you are already entitled to convert; nothing here strips protection and no such tool is named or linked.

## The list

| # | Tool | Best for | Platforms | Licence | Est. |
|---:|---|---|---|---|---|
| 1 | **[Calibre](https://calibre-ebook.com)** | The default answer for almost every conversion you will actually need | Win &middot; mac &middot; Linux | [GPL-3.0](https://github.com/kovidgoyal/calibre) | 2006 |
| 2 | **[Pandoc](https://pandoc.org)** | Producing an EPUB from something you wrote yourself - Markdown, DOCX or HTML | Win &middot; mac &middot; Linux &middot; CLI | [GPL-2.0](https://github.com/jgm/pandoc) | 2006 |
| 3 | **[VERT](https://vert.sh)** | A quick one-off conversion with nothing to install and nothing uploaded | Web &middot; Self-host | [AGPL-3.0](https://github.com/VERT-sh/VERT) | 2024 |
| 4 | **[Sigil](https://sigil-ebook.com)** | Fixing an EPUB that converted badly, rather than converting it again | Win &middot; mac &middot; Linux | [GPL-3.0](https://github.com/Sigil-Ebook/Sigil) | 2009 |
| 5 | **[k2pdfopt](https://www.willus.com/k2pdfopt/)** | Making an unreadable PDF actually readable on a small e-ink screen | Win &middot; mac &middot; Linux &middot; CLI | [AGPL-3.0](https://www.willus.com/k2pdfopt/download/) | 2011 |
| 6 | **[kepubify](https://pgaskin.net/kepubify/)** | Kobo owners who want proper page counts and working reading statistics | Win &middot; mac &middot; Linux &middot; CLI | [MIT](https://github.com/pgaskin/kepubify) | 2017 |
| 7 | **[LibreOffice Writer](https://www.libreoffice.org/discover/writer/)** | Turning a manuscript you already have in DOCX or ODT into an EPUB | Win &middot; mac &middot; Linux | [MPL-2.0](https://github.com/LibreOffice/core) | 2010 |
| 8 | **[percollate](https://github.com/danburzo/percollate)** | Turning a pile of web articles into one clean EPUB or PDF to read later | Win &middot; mac &middot; Linux &middot; CLI | [MIT](https://github.com/danburzo/percollate) | 2018 |
| 9 | **[EbookLib](https://github.com/aerkalov/ebooklib)** | Building or rewriting EPUB files programmatically, in Python | CLI | [AGPL-3.0](https://github.com/aerkalov/ebooklib) | 2013 |

<sub>Licence links point at the source repository. `Freeware` means free to use but not open source.</sub>

## Details

### 1. Calibre

**Platforms** Windows, macOS, Linux &nbsp;&middot;&nbsp; **Licence** GPL-3.0 &nbsp;&middot;&nbsp; **Cost** Free, donation-supported &nbsp;&middot;&nbsp; **Established** 2006  
[Homepage](https://calibre-ebook.com) &nbsp;&middot;&nbsp; [Source](https://github.com/kovidgoyal/calibre)

The default answer for almost every conversion you will actually need

**Good** &mdash; Converts between virtually every ebook format in both directions, and in bulk; Deep control over the output - fonts, margins, page breaks, table of contents, metadata; Ships the ebook-convert command-line tool, so the same engine scripts without the interface

**Less good** &mdash; The interface is dense and dated, and there is a real learning curve for a one-off conversion; Wants to manage your library as well, which is more than you asked for if you came to convert one file

Calibre is the engine behind a large share of the other converters you will find, including several web tools and most simple desktop converters. If a tool claims to convert everything, it is usually calling ebook-convert underneath.

### 2. Pandoc

**Platforms** Windows, macOS, Linux, CLI &nbsp;&middot;&nbsp; **Licence** GPL-2.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2006  
[Homepage](https://pandoc.org) &nbsp;&middot;&nbsp; [Source](https://github.com/jgm/pandoc)

Producing an EPUB from something you wrote yourself - Markdown, DOCX or HTML

**Good** &mdash; Converts between dozens of document formats with unusually faithful structure; The authoring direction is where it beats everything else: Markdown or DOCX in, clean EPUB out; Scriptable and reproducible, so the same source builds the same book every time

**Less good** &mdash; Command line only - there is no official graphical interface; Weak in the reader direction: it is not the tool for turning a MOBI you already own into an EPUB

The complement to Calibre rather than a competitor. Pandoc is for making books; Calibre is for converting books that already exist.

### 3. VERT

**Platforms** Web, Self-hosted &nbsp;&middot;&nbsp; **Licence** AGPL-3.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2024  
[Homepage](https://vert.sh) &nbsp;&middot;&nbsp; [Source](https://github.com/VERT-sh/VERT)

A quick one-off conversion with nothing to install and nothing uploaded

**Good** &mdash; Runs the conversion in your own browser - the file never leaves your machine, which is what separates it from every other web converter; No account, no queue, no daily limit and no watermark; Self-hostable if you would rather run your own copy

**Less good** &mdash; Document and ebook support is narrower than Calibre's - it is strongest on images and audio; Large files are limited by your own browser's memory rather than by a server

Included specifically because it breaks the pattern this list exists to warn about: it looks like the upload sites and behaves like a desktop tool. Check it handles your exact format pair before relying on it.

### 4. Sigil

**Platforms** Windows, macOS, Linux &nbsp;&middot;&nbsp; **Licence** GPL-3.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2009  
[Homepage](https://sigil-ebook.com) &nbsp;&middot;&nbsp; [Source](https://github.com/Sigil-Ebook/Sigil)

Fixing an EPUB that converted badly, rather than converting it again

**Good** &mdash; Full visual and code-level EPUB editing, with validation against the specification; The practical repair step after a messy PDF or DOCX conversion; Handles EPUB 2 and EPUB 3, including the structural parts most converters get wrong

**Less good** &mdash; Not a format converter - it edits EPUB, it does not turn a MOBI into one; Assumes you are willing to look at the underlying HTML when something is wrong

Belongs on this list because conversion output is so often nearly right. Sigil is how you close the gap without re-running the conversion and hoping.

### 5. k2pdfopt

**Platforms** Windows, macOS, Linux, CLI &nbsp;&middot;&nbsp; **Licence** AGPL-3.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2011  
[Homepage](https://www.willus.com/k2pdfopt/) &nbsp;&middot;&nbsp; [Source](https://www.willus.com/k2pdfopt/download/)

Making an unreadable PDF actually readable on a small e-ink screen

**Good** &mdash; Reflows text rather than converting it, which is the honest answer to the PDF problem; Handles multi-column academic PDFs, which defeat most converters; Includes OCR, so a scanned PDF can become selectable text

**Less good** &mdash; The output is still a PDF, sized for one device - it does not give you a reflowable EPUB; The graphical interface is Windows only; elsewhere it is a command-line tool with a lot of options; No public git repository - source is distributed as tarballs from the author's own site, so you cannot check activity the usual way

Worth knowing before you rely on it: k2pdfopt has no public git repository. The author distributes source tarballs from willus.com, and the GitHub copies are thin third-party mirrors - the one most often linked has four commits. The AGPL-3.0 licence is stated in the source and corroborated by Debian, which packages it, but the usual one-click check does not apply here. The tool itself is the best answer to an unreadable PDF on e-ink.

### 6. kepubify

**Platforms** Windows, macOS, Linux, CLI &nbsp;&middot;&nbsp; **Licence** MIT &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2017  
[Homepage](https://pgaskin.net/kepubify/) &nbsp;&middot;&nbsp; [Source](https://github.com/pgaskin/kepubify)

Kobo owners who want proper page counts and working reading statistics

**Good** &mdash; Converts EPUB to Kobo's own kepub format, which unlocks per-chapter progress and statistics on the device; Dramatically faster than doing the same job through Calibre; A single standalone binary with no runtime to install

**Less good** &mdash; Does exactly one conversion and nothing else; Command line only, though it will take a whole folder at once

Narrow, but genuinely the best tool for its one job. If you own a Kobo and have wondered why the progress bar never works properly, this is the answer.

### 7. LibreOffice Writer

**Platforms** Windows, macOS, Linux &nbsp;&middot;&nbsp; **Licence** MPL-2.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2010  
[Homepage](https://www.libreoffice.org/discover/writer/) &nbsp;&middot;&nbsp; [Source](https://github.com/LibreOffice/core)

Turning a manuscript you already have in DOCX or ODT into an EPUB

**Good** &mdash; Exports directly to EPUB from File then Export As - no separate tool to learn; Already installed for most people who have a manuscript to convert; Handles the DOCX cases that trip up converters written for ebooks rather than word processors

**Less good** &mdash; One direction only - it will not convert an existing EPUB or MOBI into anything; The EPUB it produces is plain; expect to tidy the result in Sigil for anything you intend to publish

The repository link is LibreOffice's official GitHub mirror. GitHub's licence detector reports GPL-3.0 for that mirror; the project's own licence page states MPL-2.0, which is what this row records.

### 8. percollate

**Platforms** Windows, macOS, Linux, CLI &nbsp;&middot;&nbsp; **Licence** MIT &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2018  
[Homepage](https://github.com/danburzo/percollate) &nbsp;&middot;&nbsp; [Source](https://github.com/danburzo/percollate)

Turning a pile of web articles into one clean EPUB or PDF to read later

**Good** &mdash; Strips navigation, adverts and clutter before conversion, so the result reads like a book; Bundles many URLs into a single volume with a working table of contents; Output is genuinely tidy, which is rare for web-to-ebook tools

**Less good** &mdash; Needs Node.js installed, which is a barrier if you do not already have it; No release since August 2025 - it still works, but development has slowed

A different job to the rest of this list: the source is the web rather than a file you already have. Pairs naturally with a read-it-later tool.

### 9. EbookLib

**Platforms** CLI &nbsp;&middot;&nbsp; **Licence** AGPL-3.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2013  
[Homepage](https://github.com/aerkalov/ebooklib) &nbsp;&middot;&nbsp; [Source](https://github.com/aerkalov/ebooklib)

Building or rewriting EPUB files programmatically, in Python

**Good** &mdash; Reads and writes EPUB 2 and EPUB 3 from Python, with real control over the package structure; The right foundation for a bulk or repeatable conversion nobody has written a tool for yet; Small, stable and well understood

**Less good** &mdash; A library, not an application - it is only useful if you are willing to write code; EPUB only; it will not read a MOBI or write a PDF

Listed for completeness at the technical end. If your conversion is a one-off, use Calibre; if it is a hundred files with a rule attached, this is how people usually do it.

## Also worth knowing

- **[Kindle Previewer](https://kdp.amazon.com/en_US/help/topic/G202131170)** &mdash; Seeing how an EPUB will actually look on a Kindle before you send it (Freeware)
- **[KOReader](https://koreader.rocks)** &mdash; Reading the awkward format directly instead of converting it at all (AGPL-3.0)
- **[Calibre ebook-convert](https://manual.calibre-ebook.com/generated/en/ebook-convert.html)** &mdash; Scripting Calibre's conversion engine without opening the application (GPL-3.0)

## FAQ

**What is the best free ebook converter?**

Calibre, for almost everybody. It converts between every common format in both directions, runs on Windows, macOS and Linux, and costs nothing. The main reasons to look further are wanting something lighter for a single conversion, or having a PDF - which is the one job Calibre is not especially good at.

**Why should I avoid online ebook converters?**

Because you have to upload the book. Most free web converters also cap how many files you can convert per day, limit file size, or ask you to sign up before you can download the result. Everything on this list runs on your own machine, and the one browser-based entry, VERT, does the conversion locally in the tab rather than sending the file anywhere.

**Can I convert a PDF to EPUB properly?**

Usually not, and it is worth knowing why. A PDF describes where ink sits on a fixed page; an EPUB reflows to fit any screen. Converting one to the other means guessing at the structure, and on a multi-column or scanned PDF the guess is usually wrong. If the aim is to read it on a small screen, k2pdfopt reflowing the PDF often gives a better result than converting it.

**How do I get a book onto a Kindle or a Kobo?**

For Kindle, convert to AZW3 or EPUB with Calibre - modern Kindles accept EPUB directly. For Amazon's newer KFX format you need their own Kindle Previewer. For Kobo, convert to kepub with kepubify: it is the same book, but the device then tracks progress and reading statistics properly.

**Do any of these remove DRM?**

No. Everything here converts files you are already entitled to convert. DRM-locked purchases are outside the scope of this list, and we do not link to or name tools for removing it.

---

Found something missing or out of date? [Open an issue](https://github.com/dead0eye/awesome-reading-writing-tools/issues) or see [CONTRIBUTING](../CONTRIBUTING.md).  
Maintained by [GetFreeEbooks](https://getfreeebooks.com). Content released under [CC0 1.0](../LICENSE).
