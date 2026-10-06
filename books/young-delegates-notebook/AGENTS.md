# Agent instructions: A Young Delegate's Notebook

This repo holds one product: A Young Delegate's Notebook. It walks a reader from "I've never heard of WG21" to "I'm attending meetings and finding my niche." Each chapter is a stable plateau, a resting point where someone could stop and still be contributing. The guide accumulates: each chapter builds on the one before it.

This file is the source of truth for voice and mechanics. Supporting files live in `planning/`:

- `planning/emotional-arc.md` - how the reader should feel entering and leaving each chapter.
- `planning/concept-manifest.md` - which chapter owns which term, and the order terms may appear in.
- `planning/source-briefs/` - verified facts for each chapter, with flags for anything unverified.

Where a planning file disagrees with this one about voice or mechanics, this file wins.

## What this book is

- A practical guide for newcomers. Dead simple, accumulative, builds like a pyramid.
- Intimate. One experienced delegate talking to one newcomer, in the second person. It should read nothing like committee papers, standing documents, or reflector mail, which are long, formal, and bureaucratic. If a sentence would fit in an SD-4 revision, rewrite it.
- Opinionated. It has a position: stability over innovation, users first, evidence over enthusiasm.
- Voiced by the Patron, an unnamed experienced delegate speaking straight to the reader. The Patron is never named in the text.

## What this book is not

- Not institutional analysis. That is the job of `my-books/wg21-bible/`.
- Not a reform manifesto. That is the job of the Reform Codex.
- Not a textbook, manual, or encyclopedia.
- It does not use coined terms from the Bible. No Consensus Ratchet, no Peerage, no Empty Seat, no Silence As Consensus.
- It does not psychoanalyze the committee. Advice is addressed to the reader about their own judgment, in plain words, not jargon.

## Voice

The whole book is one person talking to you. Everything in this section protects that.

### Who is talking

- The Patron is a patient colleague sitting next to the reader, not above the reader.
- The Patron is one person and says "I." Never "we," which sounds like the committee or an editorial board. "Let's" is fine, because it means you and me.
- No other voices. Never mention reviewers, coauthors, or what "this notebook's" anyone thinks.

### Who is listening

- Address the reader as "you," always. Never "the newcomer," "participants," or "delegates" when you mean the reader.
- Advice is about the reader's own judgment. Don't guess at why other people vote or act the way they do.
- When the evidence is thin, say so. Never present an opinion as a fact about the committee.

### How it sounds

- Contractions. Informal. Plain words.
- Conclusion first in every section. State the destination, then build toward it.
- Average sentence 15 words, hard cap 25. Paragraphs three sentences at most.
- Starting a sentence with "And," "But," or "So" is fine. So is ending one on a preposition. Chicago agrees, so don't let an edit "fix" them.
- Banned words: delve, tapestry, landscape, ecosystem, realm, robust, leverage, utilize, facilitate, navigate, streamline.
- No committee-speak: "in order to," "with respect to," "it should be noted," "stakeholders." Watch for stacked nouns like "the responsibility of participation in the standardization committee." Say the plain thing.
- A bridge sentence between sections is welcome when it adds something. Never write one that only restates the next heading.
- End each chapter where `planning/emotional-arc.md` says the reader should land: a short closing paragraph in the Patron's voice, then a pointer to what comes next.

## Mechanics

Mechanics follow *The Chicago Manual of Style* wherever this file is silent. Every rule below was picked because it keeps the text sounding like a person instead of a document. Where Chicago and this file conflict, this file wins.

### Punctuation

- No em dashes, no en dashes used as dashes, no double dashes. Prefer a period or a colon. When you truly need a dash, use a single spaced hyphen ( - ).
- No semicolons. Split the sentence.
- Lowercase after a colon, unless two or more full sentences follow it: "Here's the hard rule: the standard almost never shrinks."
- Always use the serial comma: "read, review, and discuss."
- Double quotation marks. Periods and commas go inside the closing quote.

### Capitalization

- Down style. Capitalize only true proper names: WG21, ISO, SC22, INCITS, SD-4, the Direction Group, CppCon.
- Lowercase generic terms, even when committee documents capitalize them: national body, working draft, committee draft, global directory, mirror committee, study group, plenary, convener, chair, head of delegation.
- Capitalize a title only directly before a name: "Convener Guy Davidson," but "the convener."
- "The Delegate's Oath" is a proper name. After that, it's "the oath."
- Coined labels for ideas stay lowercase: steel man, max-min solution, back-pocket alternative.

### Emphasis and terms

- No bold in running text.
- Italicize a key term once, where it's defined, then set it in roman: "Behind every release is a living document called the *working draft*."
- Italicize words used as words: "*shall* marks a hard requirement."
- Italicize a vote when the vote itself is the subject, and keep it lowercase: "a *no* vote," "vote *yes* with comments."
- Book titles go in italics: *The Prince*, *The Design and Evolution of C++*. Paper titles go in quotation marks, worded as the paper gives them.
- Code identifiers go in backticks every time: `std::regex`, `memory_order_relaxed`.

### Numbers, dates, and times

- In narrative, spell out zero through one hundred and round numbers: "twenty-eight nations," "about two hundred people," "sixteen million users."
- Use numerals for vote tallies ("57 in favor, 2 against"), ratios like 2:1, years, dates, money, paper and revision numbers, chapter and section numbers, versions like C++26, clock times, and anything in a table.
- Never start a sentence with a numeral.
- Percentages take a numeral and the word: "80 percent." A quoted phrase keeps its own form.
- Write dates month first: "October 9, 2026."
- Write times as "5 p.m.," not "5pm" or "5:00 p.m." Use words when they read naturally: "the evening before plenary."

### Abbreviations

- Spell them out in prose and headings: "for example," "that is," "also known as," "versus." No "e.g.," "i.e.," "a.k.a.," or "vs."
- Committee acronyms (EWG, NB, CD, DIS) are fine once defined in their owning chapter. See `planning/concept-manifest.md`.

### Spelling

- American spelling, following Merriam-Webster.
- Follow Merriam-Webster for hyphenation. Where it's silent, close common prefixes: coauthor, cowrite, reread, nonvoting.

### Quotations

- Run short quotes into the sentence, so the Patron is the one telling the reader: SD-4 is blunt that "if a proposal doesn't have a paper, it doesn't exist."
- Lowercase a quote's first letter when it runs into your sentence. Trim with an ellipsis (...) to keep only the point.
- No block quotes, except the Delegate's Oath and the epigraph.

### Lists

- Run short items into the sentence: "Keep three things apart: the standard is the text, the compilers try to follow it, and the living language is what real code relies on."
- Use a vertical list only for something the reader will use as a checklist or a sequence of steps.

### Headings

- Headline style: capitalize the first and last words and all major words. Lowercase articles, prepositions, and coordinating conjunctions: "You Can Take Part from Your Desk," "A Newcomer's Path into WG21."
- No abbreviations in headings.

### The epigraph

- A blockquote with no quotation marks around the passage. The source line sits beneath it in the same blockquote, with the work's title in italics.

## Structure

- `young-delegates-notebook.md` - the assembled manuscript. Generated. Do not edit by hand.
- `chapters/intro.md` - the introduction. Sets the voice for the whole book.
- `chapters/ch-01.md` through `ch-13.md` - the thirteen chapters.
- `build.py` - the assembler. Run `python build.py` from this directory to regenerate the manuscript and its table of contents.

Edit chapter files. Rebuild. Never edit the assembled manuscript directly.

## Section numbering and cross-references

- Decimal hierarchy. Chapters are `1`, `2`. Sections are `1.1`, `1.2`. Subsections are `1.2.1`.
- Chapter headings are `## 1. Title` (level 2). Section headings are `### 1.1 Title` (level 3). Subsection headings are `#### 1.1.1 Title` (level 4).
- Headings carry their full number. Headings do not use the section symbol.
- In prose, point to the idea first and the place second: "the guest path from chapter 2." Write "chapter 3" and "section 2.4" in lowercase. No section symbol in prose.
- Older chapter text still uses bold terms and `§2.4` references. Convert them when you edit a chapter.

## Linking

- No citations, footnotes, endnotes, or bibliography. Every reference is an inline hyperlink, the way a colleague points at something.
- Dense inline links. The text should read like a well-linked wiki, not an academic paper.
- Every paper number is a live link to its official copy on open-std.org: `[P4014R2](https://www.open-std.org/jtc1/sc22/wg21/docs/papers/2026/p4014r2.pdf)`. No bare paper numbers.
- Never put a wg21.link URL in the book text. It's an unofficial redirect service, not the archive. Use it only to look up a paper's address: `https://wg21.link/p4014r2` redirects to the open-std.org URL, and that resolved URL is what goes in the text. Link a specific revision, and keep the year and extension the redirect gives you, since some papers are HTML, not PDF.
- Chapter 3 teaches wg21.link as a lookup tool, so the text can name it and show the pattern in backticks (`wg21.link/p2300r10`). It is never a hyperlink, even on first mention.
- Every named document, site, or resource is linked on first mention in each chapter file. Later mentions in the same file use the plain name.

## The Delegate's Oath

Exact wording, do not paraphrase:

> I vow to do what is best for the language, to make no unnecessary proposals, and to put the needs of sixteen million users ahead of my own.

The oath belongs to chapter 1. The introduction holds its spirit ("put the users first") but does not state the formal oath.

## Reform Codex boundaries

The Notebook draws principles from the Reform Codex but never its partisan or operational content. Use Sections 1-4 (the weight of the standard, paper writing, voting, delegate behavior). Do not use Sections 5-9 (reform communication, institutional diagnosis, structural remedies, NB strategy, counter-tactics). The reader should come away thinking "good principles for responsible participation," not "recruited into a faction."
