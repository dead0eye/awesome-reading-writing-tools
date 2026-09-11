# Changelog

All notable changes to the lists in this repository. Each list also carries its own changelog section at the bottom of its page.

Versioning is per list: **MAJOR** the list is re-scoped, **MINOR** a tool is added or removed, **PATCH** copy, link or licence corrections.


## 2026-09-11

### [Free & Open Source PDF Editors & Annotators](pdf-editors.md) v1.1.2

- Est. column checked against each project's history. Corrected: LibreOffice Draw 2010 (not 2011), Xournal++ 2011 (not 2013), PDF4QT 2018 (not 2019), PDF Mix Tool 2017 (not 2018) and Sioyek 2020 (not 2021).

### [Free & Open Source Writing Software for Novelists](novel-writing-software.md) v1.3.1

- oStorybook: filled the Est. column with 2013, the year its original SourceForge project was registered. Its current Framagit history only begins in 2024.

### [Free & Open Source Ebook Management Apps](ebook-management-apps.md) v1.1.1

- Filled the Est. column - the year each project was established - which was blank on ten of eleven rows, from each project's repository history or its own release notes.
- Three research-supplied years were corrected: Thorium Reader 2017, not 2019 (its repository dates from March 2017); GCstar 2006, not 2005 (its earliest record is its 2006 website and Debian packaging request); and Ubooquity 2013, not 2014 (its own release notes date version 1.2.0 to October 2013).
- Tellico is recorded as 2001, when it shipped as Bookcase 0.1. It was renamed in 2004.

### [Free & Open Source Ebook Format Converters](ebook-format-converters.md) v1.1.1

- Est. column checked against each project's history. Corrected: VERT 2024 (not 2025), kepubify 2017 (not 2019) and LibreOffice Writer 2010 (not 2011 - LibreOffice was founded in 2010, before its first release).

### [Free & Open Source Ebook Readers for Desktop](desktop-ebook-readers.md) v1.1.1

- Est. column: Thorium Reader corrected from 2019 to 2017, the year its repository was started - it now matches the Ebook Management Apps list.


## 2026-09-10

### [Free & Open Source PDF Editors & Annotators](pdf-editors.md) v1.1.1

- Inkscape: licence corrected from GPL-3.0 to GPL-2.0-or-later. The project's own COPYING file states version 2 or later, with the javascript polyfills under CC0 and parts of src/3rdparty under LGPL or MPL. GitLab reports no licence at all for the repository because COPYING is a summary rather than a licence text, so this had to be read by hand.
- Stirling-PDF: the entry said the self-hosted build was open source and unlimited. The project's README now describes itself as open-core, its free self-hosted plan is capped at five user accounts, and app/proprietary/, app/saas/ and engine/ all exist and carry a separate licence forbidding production use without a subscription. All PDF operations are still free, which is the part that matters here, and the entry now says exactly that instead.
- LibreOffice Draw: recorded why GitHub reports GPL-3.0 for a project that publishes MPL-2.0 - the mirror still carries the legacy COPYING file from the OpenOffice.org lineage. The same note already existed on LibreOffice Writer in the converters list; it was missing here.

### [Free & Open Source Writing Software for Novelists](novel-writing-software.md) v1.3.0

- Added Ghostwriter (GPL-3.0, KDE) and novelibre (GPL-3.0), taking the main table to ten. Both were added because two existing entries currently have no working download, and a reader should not lose a quarter of the list to outages.
- Quoll Writer: corrected advice that did not work. The previous note said to download from GitHub instead of the website; all 30 GitHub releases are source tags with no attached files, so there is no build to download there either. Dated the outage against the Internet Archive - last good capture 7 June 2026.
- yWriter: removed the claim that the site was updated in August 2026, which could not be checked from any reachable source. The outage is now dated to at least 5 September 2026, corroborated by an Internet Archive capture returning the same server error.
- Ghostwriter's GitHub releases page stops at 2.1.6 in 2022 and reads as abandoned; the project moved to KDE's release cycle and shipped 26.04.3 via Flathub in July 2026. Recorded in the entry so the stale releases page does not mislead.


## 2026-09-09

### [Free & Open Source PDF Editors & Annotators](pdf-editors.md) v1.1.0

- Full verification pass. Every homepage and repository link opened; every open source licence claim checked against the GitHub or GitLab API.
- PDF Mix Tool's homepage was returning 404 - its GitLab Pages site has gone. The link now points at the GitLab project, which is active and is also the Flathub source.
- internalLink replaced. It pointed at getfreeebooks.com/desktop-ebook-readers, which returns 404 because that list is not published yet, so the link would have shipped broken.
- Stirling-PDF: the hosted service at stirling.com now has a free tier capped at 500 monthly credits with paid processing beyond it. The self-hosted build is unaffected and remains free and unlimited, which is what this list recommends - the entry now says so explicitly rather than describing the project as simply free.
- Stirling-PDF licence caveat retained: MIT overall, with separate proprietary/SaaS licences on some directories, which is why GitHub reports the licence as unrecognised.
- signals blocks populated for all 13 entries that have a repository. None is archived and all have commits within the last five weeks.
- LibreOffice Draw's MPL-2.0 checked and left alone - the GitHub mirror mis-reports GPL-3.0, but the project's own licence page states MPL-2.0.
- NOT verified: whether the two freeware entries, PDF24 Creator and PDFgear, watermark output or limit use in practice. Both are closed source and would need installing to test.

### [Free & Open Source Writing Software for Novelists](novel-writing-software.md) v1.2.0

- Full verification pass. Every homepage and repository link opened; every licence claim checked against the GitHub or GitLab API.
- Two websites were unreachable at the time of checking and both entries now say so: quollwriter.com did not respond, and spacejock.com (yWriter) returned a server error across the whole domain. Neither project is declared dead - yWriter in particular appears current - but a reader should not meet a broken link without warning.
- bibisco Community Edition: last commit September 2024. Noted, since active development has moved to the paid edition and the free one is what this list recommends.
- internalLink added - the field was empty, which is a publishing gate.
- signals blocks populated for the 7 entries with a repository.
- NOT verified: whether any of these install and run, and whether the two unreachable sites recover. Both need re-checking before publication.

### [Free & Open Source Ebook Management Apps](ebook-management-apps.md) v1.1.0

- Full verification pass. Every homepage and every repository link opened and returning 200; every open source licence claim checked against the GitHub or GitLab API, and against the licence file itself where the API reported NOASSERTION.
- BicBucStriim moved to Also consider: archived by its maintainer in July 2023, who directs users to community forks. It had been a main-table entry telling the reader to go and check the commit history themselves.
- Readarr's downsides now state that the project is archived rather than asking the reader to check its status.
- Koodo Reader's repository URL updated - the project moved to koodo-reader/koodo-reader and the old address only worked via a redirect.
- signals blocks populated for all 14 entries that have a repository, from the hosting platform's API rather than by estimate.
- Two claims checked and left alone: Zotero really is AGPL-3.0 (GitHub cannot detect a licence in a file named COPYING), and LibreOffice really is MPL-2.0 (its GitHub mirror mis-reports GPL-3.0).
- externalLink set to the OPDS 1.2 specification and internalLink to an existing getfreeebooks.com post; both confirmed reachable.
- Entry count corrected in the meta fields after the move to Also consider - they still claimed 12.
- NOT verified: whether each application installs and runs, and whether any has changed its commercial terms while keeping its licence. That needs a person and a trial.

### [Free & Open Source Ebook Format Converters](ebook-format-converters.md) v1.1.0

- Full verification pass. Every homepage and repository link opened and returning 200; every licence claim checked against the GitHub API.
- internalLink added - the field was empty, which is a publishing gate.
- signals blocks populated for the 10 entries hosted on a git platform. k2pdfopt has none by design: it has no public repository, which its row already explains.
- willus.com (k2pdfopt) returns 406 to a plain request and 200 to a browser - it blocks non-browser user agents rather than being unavailable.
- NOT verified: whether each tool installs and runs, and the real-world quality of any particular conversion.

### [Free & Open Source Ebook Format Converters](ebook-format-converters.md) v1.0.0

- First research pass. Every repository checked against the GitHub or GitLab API for licence, archive status and last commit date.
- Nine main entries rather than ten: the honest free bench for offline conversion is small, and the alternative was padding with upload sites or with wrappers around Calibre's own engine.

### [Free & Open Source Ebook Readers for Desktop](desktop-ebook-readers.md) v1.1.0

- Full verification pass. Every homepage and repository link opened and returning 200; every open source licence claim checked against the GitHub or GitLab API.
- internalLink replaced. It pointed at getfreeebooks.com/ebook-management-apps, which returns 404 - that list has not been published yet, so the link would have shipped broken. It now points at an existing post on the site.
- epy's downsides rewritten to match the evidence: the last tagged release was December 2022 and the last commit March 2024. The previous wording said releases and commits had both stalled since 2023, which understated the commits and overstated the releases.
- signals blocks populated or refreshed for all 15 entries that have a repository, from the hosting platform's API rather than by estimate.
- All twelve licence claims verified correct, including the two KDE projects, which use REUSE-style multi-licensing - the stated licence is the primary one for each.
- NOT verified: whether each application installs and runs, and whether any has changed its terms while keeping its licence. That needs a person and a trial.


## 2026-09-08

### [Free & Open Source PDF Editors & Annotators](pdf-editors.md) v1.0.0

- First publication with 12 PDF editors and annotators plus 3 near-misses.
- Seeded from verified repository research covering desktop page managers, form fillers, stylus annotators, OCR engines, direct text editors, and self-hosted web suites.

### [Free & Open Source Writing Software for Novelists](novel-writing-software.md) v1.1.0

- Verified the populated entries against current official websites and public repositories.
- Corrected the intro so the first sentence contains the exact focus keyword verbatim.
- Corrected maintenance wording for Manuskript and yWriter and updated oStorybook to its current v6 source repository.
- Removed Plume Creator because its supplied project domain currently resolves to unrelated content, and did not pad the list with an unverified alternative.

### [Free & Open Source Ebook Readers for Desktop](desktop-ebook-readers.md) v1.0.0

- First publication with 12 desktop ebook readers plus 4 near-misses.
- Seeded from verified repository research covering cross-platform, Linux-native, Windows-lightweight, comic-specialist, and CLI tools.


## 2026-08-31

### [Free & Open Source Ebook Management Apps](ebook-management-apps.md) v1.0.0

- First publication with 12 tools plus 3 near-misses.
- Seeded from internal research - every link, licence and release year still needs human verification before publishing.

