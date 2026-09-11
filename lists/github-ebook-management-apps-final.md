# Free & Open Source Ebook Management Apps

> Organise, tag, convert and sync a personal ebook library without paying anyone.

`11 tools` &nbsp;&middot;&nbsp; `v1.1.1` &nbsp;&middot;&nbsp; `updated 2026-09-11` &nbsp;&middot;&nbsp; `10 open source`

[&larr; back to the index](../README.md)

Good free ebook management software solves a problem that only gets worse with time: a folder of a few hundred files with names like `book_final_2.epub`, no covers, no series order, and no idea which ones you have actually read. The tools below all fix that, and every one of them is free to use for its core job.

They split into three groups. Desktop managers keep the library on one machine and give you the deepest editing and conversion tools. Self-hosted servers put the same library behind a web page so a phone, a tablet and an e-reader can all reach it. Collection catalogues track the books themselves rather than the files, which is what you want if most of your shelf is physical.

Pick based on where you want the library to live, not on the feature list. Almost every tool here can import from the others, so the decision is reversible.

## How these were chosen

- Free for its core purpose - no expiring trial, and no tier so limited it cannot manage a real library.
- Actively maintained, or clearly labelled when maintenance has stalled.
- Open source entries link to their own repository, so the licence claim can be checked in one click. Eleven of the twelve are open source; the one that is not is marked Freeware in its row and says so in its downsides.
- Listed where its primary job is - a tool that mainly reads books belongs in our desktop readers list and is cross-referenced from here, not duplicated.
- Handles at least EPUB and PDF; format-specific tools are noted as such.
- No affiliate links - every link goes to the project's own homepage.

## The list

| # | Tool | Best for | Platforms | Licence | Est. |
|---:|---|---|---|---|---|
| 1 | **[Calibre](https://calibre-ebook.com/)** | The default answer for anyone with a large local library | Win &middot; mac &middot; Linux | [GPL-3.0](https://github.com/kovidgoyal/calibre) | 2006 |
| 2 | **[Calibre-Web](https://github.com/janeczku/calibre-web)** | Putting a friendly web front end on a library Calibre already manages | Self-host &middot; Web | [GPL-3.0](https://github.com/janeczku/calibre-web) | 2015 |
| 3 | **[Kavita](https://www.kavitareader.com/)** | A mixed library of ebooks, comics and manga in one server | Self-host &middot; Web | [GPL-3.0](https://github.com/Kareadita/Kavita) | 2020 |
| 4 | **[Komga](https://komga.org/)** | Comic and manga collections where series metadata matters most | Self-host &middot; Web | [MIT](https://github.com/gotson/komga) | 2019 |
| 5 | **[Koodo Reader](https://koodo.960960.xyz/)** | Someone who wants library management and a good reading experience in the same window | Win &middot; mac &middot; Linux &middot; Web | [AGPL-3.0](https://github.com/koodo-reader/koodo-reader) | 2020 |
| 6 | **[Thorium Reader](https://www.edrlab.org/software/thorium-reader/)** | Accessible reading and standards-correct EPUB 3 rendering | Win &middot; mac &middot; Linux | [BSD-3-Clause](https://github.com/edrlab/thorium-reader) | 2017 |
| 7 | **[Foliate](https://johnfactotum.github.io/foliate/)** | Linux desktops that want something native and quiet | Linux | [GPL-3.0](https://github.com/johnfactotum/foliate) | 2019 |
| 8 | **[Audiobookshelf](https://www.audiobookshelf.org/)** | Libraries where audiobooks are as important as ebooks | Self-host &middot; Web &middot; Android &middot; iOS | [GPL-3.0](https://github.com/advplyr/audiobookshelf) | 2021 |
| 9 | **[Tellico](https://tellico-project.org/)** | Cataloguing what you own rather than managing files | Linux | [GPL-2.0](https://invent.kde.org/office/tellico) | 2001 |
| 10 | **[GCstar](https://gitlab.com/GCstar/GCstar)** | A single catalogue covering books alongside other collections | Win &middot; Linux | [GPL-2.0](https://gitlab.com/GCstar/GCstar) | 2006 |
| 11 | **[Ubooquity](https://vaemendis.net/ubooquity/)** | A zero-configuration server for a folder you do not want reorganised | Self-host &middot; Web | Freeware | 2013 |

<sub>Licence links point at the source repository. `Freeware` means free to use but not open source.</sub>

## Details

### 1. Calibre

**Platforms** Windows, macOS, Linux &nbsp;&middot;&nbsp; **Licence** GPL-3.0 &nbsp;&middot;&nbsp; **Cost** Free, donation-supported &nbsp;&middot;&nbsp; **Established** 2006  
[Homepage](https://calibre-ebook.com/) &nbsp;&middot;&nbsp; [Source](https://github.com/kovidgoyal/calibre)

The default answer for anyone with a large local library

**Good** &mdash; Converts between virtually every ebook format, in bulk; Deep metadata editing, custom columns and saved searches; A very large plugin ecosystem covering almost every edge case

**Less good** &mdash; The interface is dense and dated, and there is a real learning curve; Wants to own and reorganise your file structure, which is hard to undo

Calibre is the reference implementation of this entire category - most of the other tools here either build on its library format or exist because someone wanted a lighter version of it. If you only install one thing from this list, install this, then decide later whether you want a nicer front end on top.

### 2. Calibre-Web

**Platforms** Self-hosted, Web &nbsp;&middot;&nbsp; **Licence** GPL-3.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2015  
[Homepage](https://github.com/janeczku/calibre-web) &nbsp;&middot;&nbsp; [Source](https://github.com/janeczku/calibre-web)

Putting a friendly web front end on a library Calibre already manages

**Good** &mdash; Clean, modern browsing UI that non-technical household members will actually use; Built-in OPDS feed and send-to-Kindle, plus per-user accounts and permissions

**Less good** &mdash; Reads an existing Calibre database rather than replacing it, so you still need Calibre for heavy editing; Requires you to run and update a server yourself

The usual pairing is Calibre on a desktop for imports and metadata cleanup, and Calibre-Web pointed at the same library folder for everyday reading and lending.

### 3. Kavita

**Platforms** Self-hosted, Web &nbsp;&middot;&nbsp; **Licence** GPL-3.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2020  
[Homepage](https://www.kavitareader.com/) &nbsp;&middot;&nbsp; [Source](https://github.com/Kareadita/Kavita)

A mixed library of ebooks, comics and manga in one server

**Good** &mdash; Handles EPUB, PDF and comic archives equally well rather than treating comics as second class; Fast built-in web reader with per-user progress tracking and reading lists

**Less good** &mdash; No format conversion - it serves what you give it; Metadata matching for prose books is weaker than Calibre's

The strongest option if your shelf is genuinely mixed. Where Calibre-Web assumes a Calibre database underneath, Kavita scans plain folders, so it suits people who want to keep their own file structure.

### 4. Komga

**Platforms** Self-hosted, Web &nbsp;&middot;&nbsp; **Licence** MIT &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2019  
[Homepage](https://komga.org/) &nbsp;&middot;&nbsp; [Source](https://github.com/gotson/komga)

Comic and manga collections where series metadata matters most

**Good** &mdash; Excellent series, volume and read-status handling for CBZ/CBR collections; Solid OPDS support, so third-party reader apps work well against it

**Less good** &mdash; Comics first - EPUB support exists but is not the focus; Needs a Java runtime or Docker, which is a higher setup bar than a desktop app

Komga and Kavita cover overlapping ground; the short version is that Komga is stronger on comic series metadata and Kavita is more even-handed across formats.

### 5. Koodo Reader

**Platforms** Windows, macOS, Linux, Web &nbsp;&middot;&nbsp; **Licence** AGPL-3.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2020  
[Homepage](https://koodo.960960.xyz/) &nbsp;&middot;&nbsp; [Source](https://github.com/koodo-reader/koodo-reader)

Someone who wants library management and a good reading experience in the same window

**Good** &mdash; Reads a wide range of formats including EPUB, PDF, MOBI, AZW3, CBZ and TXT; Highlights, notes and per-book progress sync through your own cloud storage

**Less good** &mdash; Library organisation is shallower than Calibre's - no custom columns or saved searches; Sync depends on you wiring up a storage provider yourself

The best fit for a few hundred books rather than a few thousand. Most people who bounce off Calibre for being too heavy land here.

### 6. Thorium Reader

**Platforms** Windows, macOS, Linux &nbsp;&middot;&nbsp; **Licence** BSD-3-Clause &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2017  
[Homepage](https://www.edrlab.org/software/thorium-reader/) &nbsp;&middot;&nbsp; [Source](https://github.com/edrlab/thorium-reader)

Accessible reading and standards-correct EPUB 3 rendering

**Good** &mdash; Built by EDRLab, the organisation behind the Readium standard, so EPUB 3 rendering is unusually faithful; Strong accessibility support including screen readers and dyslexia-friendly settings

**Less good** &mdash; Library features are basic - it is a reader with a shelf, not a cataloguing tool; No format conversion

Worth knowing about specifically for its accessibility work and its handling of library-loan formats, which most tools on this list ignore entirely.

### 7. Foliate

**Platforms** Linux &nbsp;&middot;&nbsp; **Licence** GPL-3.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2019  
[Homepage](https://johnfactotum.github.io/foliate/) &nbsp;&middot;&nbsp; [Source](https://github.com/johnfactotum/foliate)

Linux desktops that want something native and quiet

**Good** &mdash; Genuinely pleasant, native GTK reading experience with good typography controls; Built-in dictionary, translation and text-to-speech lookups

**Less good** &mdash; Linux only; Library view is a simple shelf, not a manager

Pairs well with Calibre doing the heavy library work in the background.

### 8. Audiobookshelf

**Platforms** Self-hosted, Web, Android, iOS &nbsp;&middot;&nbsp; **Licence** GPL-3.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2021  
[Homepage](https://www.audiobookshelf.org/) &nbsp;&middot;&nbsp; [Source](https://github.com/advplyr/audiobookshelf)

Libraries where audiobooks are as important as ebooks

**Good** &mdash; Best-in-class audiobook handling - chapters, playback speed, sleep timer and progress sync; Official Android and iOS apps, which most self-hosted book servers lack

**Less good** &mdash; Ebook support is secondary to audio and podcasts; Self-hosting required

Included here because a lot of people's reading is actually listening, and no desktop ebook manager handles that well.

### 9. Tellico

**Platforms** Linux &nbsp;&middot;&nbsp; **Licence** GPL-2.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2001  
[Homepage](https://tellico-project.org/) &nbsp;&middot;&nbsp; [Source](https://invent.kde.org/office/tellico)

Cataloguing what you own rather than managing files

**Good** &mdash; Tracks physical and digital books side by side, plus loans to friends; Pulls metadata automatically from online sources by ISBN

**Less good** &mdash; Linux and KDE oriented; Does nothing with the ebook files themselves - no reading, no conversion

A different category of tool to everything above it: this is a collection database, not a file manager. If most of your shelf is paper, start here.

### 10. GCstar

**Platforms** Windows, Linux &nbsp;&middot;&nbsp; **Licence** GPL-2.0 &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2006  
[Homepage](https://gitlab.com/GCstar/GCstar) &nbsp;&middot;&nbsp; [Source](https://gitlab.com/GCstar/GCstar)

A single catalogue covering books alongside other collections

**Good** &mdash; Handles books, films, games and more in one database with custom fields; Lending tracker and import from a long list of other collection tools

**Less good** &mdash; Interface is dated and development is slow; Book-specific features are shallower than a dedicated ebook manager

Worth checking the repository's recent activity before committing a large collection to it.

### 11. Ubooquity

**Platforms** Self-hosted, Web &nbsp;&middot;&nbsp; **Licence** Freeware &nbsp;&middot;&nbsp; **Cost** Free &nbsp;&middot;&nbsp; **Established** 2013  
[Homepage](https://vaemendis.net/ubooquity/)

A zero-configuration server for a folder you do not want reorganised

**Good** &mdash; Points at an existing folder tree and just works, with no database import step; Single Java file - genuinely the fastest thing here to get running

**Less good** &mdash; Closed source, so the licence and privacy claims cannot be independently verified; Sparse metadata handling compared with Kavita or Komga

The one non-open-source entry on this list, included because nothing open source is quite as effortless to start. Flagged clearly so you can rule it out if that matters to you.

## Also worth knowing

- **[Sigil](https://sigil-ebook.com/)** &mdash; Editing EPUB files rather than managing them (GPL-3.0)
- **[Readarr](https://github.com/Readarr/Readarr)** &mdash; Automating library organisation the way Sonarr does for TV (GPL-3.0)
- **[Zotero](https://www.zotero.org/)** &mdash; PDF-heavy research libraries rather than ebooks (AGPL-3.0)
- **[BicBucStriim](https://github.com/rvolz/BicBucStriim)** &mdash; Serving a Calibre library from ordinary shared web hosting (MIT)

## FAQ

**Is Calibre still the best free ebook management software?**

For a large local library, yes - nothing else comes close on conversion and metadata editing. The common pattern now is to keep Calibre as the engine and put a nicer front end such as Calibre-Web or Kavita on top of it, so you get the power without the interface.

**What is OPDS, and why does it keep coming up?**

OPDS is an open catalogue format - effectively RSS for book libraries. If a server publishes an OPDS feed, any compatible reader app on your phone or e-reader can browse and download from it directly, without a proprietary app in between. Every self-hosted option on this list supports it.

**Do any of these remove DRM from books I bought?**

No, and that is deliberate. Stripping DRM is illegal in many countries regardless of whether you paid for the book, so nothing on this list is recommended for that purpose. All of these tools work on files you already have the right to open.

**Which one should I pick if the library lives on one laptop?**

Calibre if you want full control and conversion, Koodo Reader if Calibre feels like too much machinery for a few hundred books. Both import from a plain folder, so trying one does not lock you out of the other.

## Changelog

**v1.1.1** &mdash; 2026-09-11
- Filled the Est. column - the year each project was established - which was blank on ten of eleven rows, from each project's repository history or its own release notes.
- Three research-supplied years were corrected: Thorium Reader 2017, not 2019 (its repository dates from March 2017); GCstar 2006, not 2005 (its earliest record is its 2006 website and Debian packaging request); and Ubooquity 2013, not 2014 (its own release notes date version 1.2.0 to October 2013).
- Tellico is recorded as 2001, when it shipped as Bookcase 0.1. It was renamed in 2004.

**v1.1.0** &mdash; 2026-09-09
- Full verification pass. Every homepage and every repository link opened and returning 200; every open source licence claim checked against the GitHub or GitLab API, and against the licence file itself where the API reported NOASSERTION.
- BicBucStriim moved to Also consider: archived by its maintainer in July 2023, who directs users to community forks. It had been a main-table entry telling the reader to go and check the commit history themselves.
- Readarr's downsides now state that the project is archived rather than asking the reader to check its status.
- Koodo Reader's repository URL updated - the project moved to koodo-reader/koodo-reader and the old address only worked via a redirect.
- signals blocks populated for all 14 entries that have a repository, from the hosting platform's API rather than by estimate.
- Two claims checked and left alone: Zotero really is AGPL-3.0 (GitHub cannot detect a licence in a file named COPYING), and LibreOffice really is MPL-2.0 (its GitHub mirror mis-reports GPL-3.0).
- externalLink set to the OPDS 1.2 specification and internalLink to an existing getfreeebooks.com post; both confirmed reachable.
- Entry count corrected in the meta fields after the move to Also consider - they still claimed 12.
- NOT verified: whether each application installs and runs, and whether any has changed its commercial terms while keeping its licence. That needs a person and a trial.

**v1.0.0** &mdash; 2026-08-31
- First publication with 12 tools plus 3 near-misses.
- Seeded from internal research - every link, licence and release year still needs human verification before publishing.

---

Found something missing or out of date? [Open an issue](https://github.com/dead0eye/awesome-reading-writing-tools/issues) or see [CONTRIBUTING](../CONTRIBUTING.md).  
Maintained by [GetFreeEbooks](https://getfreeebooks.com). Content released under [CC0 1.0](../LICENSE).
