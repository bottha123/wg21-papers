# Concept Manifest - A Young Delegate's Notebook

Binding contract for every writing agent. Read this before drafting any chapter.

## How to use this manifest

- Each chapter OWNS the terms listed under it. A term is defined once (bolded, in plain language) in its owning section.
- Never use a term formally before its owning section. If you need a concept owned by a later chapter, paraphrase it in plain words and do not claim the formal definition.
- When you use a term first defined in an earlier chapter, restate its meaning in a short parenthetical on first use in your chapter.
- Section numbers are decimal. Chapter headings are `## N. Title`, sections `### N.M Title`, subsections `#### N.M.K Title`. Headings carry the number, no section symbol. In prose, references use the symbol (§5.2).

## The anatomy bridge (important)

The chapter order introduces papers (Ch 3) and remote participation (Ch 4) before the full structural map (Ch 5). To avoid forward references, Chapter 2 introduces the committee's basic anatomy at a shallow level: WG21, National Body, convener, plenary, subgroup. Chapter 5 owns the deep structural treatment (the specific rooms, study groups, the Direction Group, chair power) and restates each shared term with a parenthetical. Writers in Ch 3-4 use only the shallow Ch 2 meanings.

## Cross-cutting psychological awareness

Woven in, never its own topic, never jargon. Advice TO the reader about their own judgment. Placed in: Ch 1 (responsibility, not a game), Ch 6 (realistic expectations), Ch 7 (don't get addicted; stay skeptical), Ch 8 (consensus is social pressure; demand evidence), Ch 9 (evidence over enthusiasm), Ch 11 (burnout; boundaries), Ch 13 (participation is not impact).

---

## Chapter 1 - The C++ Standard

Arc: enters curious about "what is this thing," leaves feeling the weight and seriousness of it.

Subheading order:
- 1.1 Standardization Is a Responsibility (not a hobby, resume item, or game)
- 1.2 The Delegate's Oath (told as delegate lore; the pull of your employer, in plain words, with no national-body talk yet)
- 1.3 Every Feature Is Forever (the standard only grows; std::regex; ABI locks mistakes; nothing can be removed)
- 1.4 The People Who Inherit Your Work (roughly sixteen million users, per SlashData's 2025 estimate of 16.3 million; every compiler team must build every feature; small is not free)
- 1.5 The Standard Is Not the Language (the document vs compilers vs what people write)
- 1.6 What "The Standard" Actually Is (the working draft; IS, TS, white paper, TR; no level-4 subsections; C++26 finished technical work March 2026 and is in its final approval vote)
- 1.7 How to Read the Standard (clauses, normative text vs notes, stable section labels)
- 1.8 From Standard to Compiler (the path to implementation; the three implementers)

Owns:
- **the standard** (§1.5) - the official ISO document that defines what C++ means; not the compilers, not the code people write.
- **the Delegate's Oath** (§1.2) - the vow: do what's best for the language, make no unnecessary proposals, put users first.
- **the working draft** (§1.6) - the living, in-progress text that becomes the next official version of C++.
- **International Standard (IS)** (§1.6) - the finished, published version of C++, like C++23; the binding standard.
- **Technical Specification (TS)** (§1.6) - an optional, experimental document for trying a feature before it enters the standard.
- **white paper** (§1.6) - a lighter twin of the TS with far less ISO paperwork, recommended by ISO and SC22 since 2023. In ch 1 it is described in plain words ("the standards bodies") and the source is linked as "the committee's practices guide" (SD-4, defined formally in Ch 3).
- **Technical Report (TR)** (§1.6) - an older informational document type, now mostly replaced by the TS and the white paper.
- **normative text** (§1.7) - the parts that state real requirements, as opposed to notes and examples.
- **stable section labels** (§1.7) - bracketed names like [container.requirements] that stay fixed across drafts, unlike section numbers.
- **the three implementers** (§1.8) - GCC, Clang, and MSVC, the three main compiler teams who turn the standard into something usable.

Prerequisites: none (first chapter). Uses "WG21" plainly (from the intro).
Links: isocpp.org, eel.is/c++draft, github.com/cplusplus/draft, SlashData's 2025 developer report, Herb Sutter's March 2026 trip report (the C++26 status), SD-4 (as "the committee's practices guide"). Defer the formal wg21.link explanation to Ch 3. Defer "feature-test macro" to Ch 9.

---

## Chapter 2 - Meet the Committee

Arc: enters intimidated ("can I even join?"), leaves seeing the way in wide open.

Subheading order (as written):
- 2.1 You Don't Need Permission (the barrier is lower than you think; non-technical help is valued)
- 2.2 The Nesting: ISO, JTC1, SC22, WG21
- 2.3 How the Committee Meets (plenary and subgroups; anatomy bridge; the June 2026 Brno meeting: about two hundred people, twenty-eight nations, a little over half on site, twenty-five first-time guests)
- 2.4 What a National Body Is (the national body appoints the experts; its mirror committee is the group you actually join, decides who represents the country and what it thinks of a draft; inside WG21 experts vote as individuals at plenary; one country, one vote only on the formal ballots)
- 2.5 The Easiest Start: Attending as a Guest (email the convener; ISO strongly encourages a week's notice; guest status covers the first meeting only, then join a national body or get sponsored by a member organization)
- 2.6 Getting Further In: INCITS and the Beman Project (INCITS open to anyone, individuals included; 2026 fees $510 academic to $2,703 standard, per committee, cycle December 1 to November 30; Beman Project free alternate seats, join INCITS at no cost, travel on you; before you join, check who holds the seat: you in some countries, whoever pays the fee in the United States, so a seat your employer pays for may not follow you to your next job; author's call: the Beman Project is the only sponsor named, do not mention the C++ Alliance or the Boost Foundation)
- 2.7 Getting a Vote: The ISO Global Directory (accreditation; the trap is never getting your name into the directory; to avoid it, email the national body chairs via the isocpp.org meetings page; a guest needs a week's notice, a vote needs months; a seat asks two things, read the proposals before you vote and stay active in your mirror committee; you vote as yourself, but you're there on your national body's word)
- 2.8 The Roles You Can Play (note-taker, also called the scribe; reviewer, author, implementer, champion)
- 2.9 Your First Day: Orientation and Introductions (6 p.m. Sunday orientation, usually from the main hotel lobby; first-timer welcome)
- 2.10 Showing Up Is the Secret (eighty percent of success is showing up)
- 2.11 Where Ideas Start (everyday problems; C++Now refines ideas, CppCon is where ideas meet the wider community; ACCU, Meeting C++, and the isocpp.org conference list)

Owns:
- **ISO** (§2.2) - the International Organization for Standardization, the global body that publishes technical standards.
- **IEC** (§2.2) - the International Electrotechnical Commission, ISO's sister body; the two run information technology together, hence ISO/IEC.
- **JTC1** (§2.2) - the joint ISO/IEC committee for information technology.
- **SC22** (§2.2) - the subcommittee under JTC1 for programming languages.
- **WG21** (§2.2) - Working Group 21, the group inside SC22 that writes the C++ standard (formal nesting; used plainly before this).
- **subgroup** (§2.3, shallow) - one of the smaller groups WG21 splits into to do its work. Ch 5 owns the specific rooms.
- **plenary** (§2.3, shallow) - the session where the whole committee meets and makes final decisions. Ch 7 and Ch 8 deepen.
- **national body (NB)** (§2.4) - a country's standards organization and the official member; it appoints the experts who attend. Experts vote as individuals at plenary. The national body votes for the country only on the formal ballots. Lowercase in running text.
- **guest** (§2.5) - someone who attends without joining a national body; can take part but can't vote at plenary. Guest status covers the first meeting only.
- **convener** (§2.5, shallow) - the person who runs WG21 and whom you email to attend. Ch 5 deepens.
- **INCITS** (§2.6) - the US national body, open to anyone, individuals included; yearly fee from $510 (academic) to $2,703 (standard) in the 2026 cycle.
- **mirror committee** (§2.4) - the small group inside a national body that shadows WG21 at home; the group you actually join. Lowercase in running text.
- **global directory** (§2.7) - the ISO roster your name must reach to cast a counting vote at plenary. SD-4 calls it the "ISO LiveLink global directory." Lowercase in running text.
- **champion** (§2.8, shallow) - someone who presents and pushes a proposal. Ch 11 deepens.

Prerequisites: the standard (§1.5); WG21 (intro).
Links: isocpp.org committee page, ISO, IEC, JTC1 (jtc1info.org), SC22 (open-std.org/jtc1/sc22), the Brno June 2026 trip report, isocpp.org meetings and participation page, INCITS, the Beman Project, C++Now, CppCon, ACCU, Meeting C++, the isocpp.org worldwide conference list.

---

## Chapter 3 - How Papers Work

Arc: enters confused about how work happens, leaves understanding the paper is the unit and how to find and read one.

Subheading order:
- 3.1 Nothing Happens Without a Paper (SD-4's rule, run into the prose with the rulebook linked; hallway talk matters but decides nothing until it's in a paper)
- 3.2 What a Paper Is and Its Types (ask-paper and inform-paper, flagged as informal labels; design and wording papers; standing documents)
- 3.3 The P-Number System (P, N, D; N-numbers are official ISO document numbers, used for the working draft, agendas, minutes, and editors' reports, and for every paper before 2015; revisions R0 and up)
- 3.4 Finding Any Paper (open-std.org, wg21.org as unofficial, wg21.link run by Mara Bos)
- 3.5 The Mailing System and Deadlines (mailings roughly monthly, nine in 2025, biggest before and after each meeting; eight hundred or more papers a year counting revisions; pre-meeting deadline weeks ahead)
- 3.6 The Paper Lifecycle (idea to International Standard; seven steps, with the national-body comment round, C++26 drew 411, and the approval vote in plain words; links the isocpp.org stage-by-stage page)
- 3.7 Design Review versus Wording Review (and the handoff between them)
- 3.8 Defect Reports and the Issues Lists (core and library lists, linked; the wording groups work them and plenary-approved fixes go into the working draft)
- 3.9 Reading a Paper Critically (what to look for, red flags, compare against the prior revision; if a paper leaves a gap, tell the author)
- 3.10 The Documents Everyone Should Read: SD-4 and P2000 (SD-4 covers polls, consensus, deadlines, ballots, and escalation, not guests; P2000R5 "Direction for ISO C++")

Owns:
- **paper** (§3.1) - a written proposal or report; the unit of all committee work.
- **P-number / N-number / D-number** (§3.3) - a paper's ID: P is a numbered proposal, D is an unpublished draft, N is an official ISO document number (the working draft, agendas, minutes, editors' reports, and every paper before 2015).
- **ask-paper / inform-paper** (§3.2) - informal labels for a paper that asks for a poll and one that only puts facts on the record.
- **revision (R0, R1, ...)** (§3.3) - the version of a paper; R0 is first, higher is later.
- **open-std.org** (§3.4, shallow) - the official archive where every paper lives. Ch 4 deepens.
- **wg21.org** (§3.4, shallow) - a friendlier, searchable view of the same papers. Ch 4 deepens.
- **wg21.link** (§3.4) - an unofficial shortcut that redirects a paper number to its open-std.org copy, like wg21.link/p2300r10. Named, never linked.
- **the mailing** (§3.5) - a batch of papers, published roughly monthly; the biggest land just before and just after each meeting.
- **pre-meeting mailing deadline** (§3.5) - the cutoff, weeks before a meeting, after which papers aren't actionable.
- **the paper lifecycle** (§3.6) - the path a paper takes from idea to International Standard.
- **design review** (§3.7) - deciding whether C++ wants the change at all, and how it should work.
- **wording review** (§3.7) - checking that the exact standard text says the approved design precisely, with no gaps.
- **defect report** (§3.8) - a reported bug in the standard itself (an issue) whose fix the full committee has accepted.
- **issues lists** (§3.8) - the core language and library issues lists that track standard defects; the wording groups work through them.
- **standing document (SD)** (§3.2) - a numbered document holding the committee's own rules and practices.
- **SD-4** (§3.10) - the standing document describing how WG21 works in practice; everyone is expected to know it.
- **Direction Group / P2000** (§3.10, shallow) - a small group of experienced members that recommends direction, and its paper P2000, "Direction for ISO C++." Ch 5 deepens.

Prerequisites: the standard, IS (§1.5, §1.6); WG21, plenary, subgroup (Ch 2).
Links: open-std.org, wg21.org, SD-4 on isocpp.org, P2000.

---

## Chapter 4 - How to Participate Remotely

Arc: enters thinking you must travel to matter, leaves empowered to contribute today from your desk.

Subheading order:
- 4.1 You Can Take Part from Your Desk (reading, reviewing, discussing; taking minutes for an online meeting; the free-login review)
- 4.2 The Reflector (any meeting attended, in person or online, qualifies you; many topic lists are publicly readable and a topic group's chair can add an expert; the quoting rule; courtesy, "costs you a reader for a decade")
- 4.3 The Official Sites, and One Unofficial One (isocpp.org and open-std.org official; wg21.org unofficial, volunteer-built; do not name the C++ Alliance)
- 4.4 The Wiki (agendas, schedules, video-call links, poll pages; don't edit unless told; access once you're a participant)
- 4.5 Real-Time Chat: Mattermost and Discord (Mattermost is for committee participants; the #include <C++> Discord is public; the courtesy rule holds in chat; no C++ Slack, per the author's call on the C++ Alliance)
- 4.6 Floating Ideas: std-proposals
- 4.7 Telecons Between Meetings (subgroup telecons, about thirty a month per isocpp.org; the shared calendar)
- 4.8 Voting from Afar: Electronic Polls (rules in P2195R2; each round is a paper, P3712R0, with outcomes in another, P3713R0)
- 4.9 Following a Live Meeting (hybrid; hallway talk is hard to join remotely; trip reports; official minutes as an N-paper, N5040 for March 2026; time zones)
- 4.10 Open-Source Help: The Beman Project and Tools (Beman builds open-source implementations of proposed library features; wg21.link; no npaperbot)

Owns:
- **the reflector** (§4.2) - the committee's email mailing lists, where most discussion happens between meetings.
- **isocpp.org** (§4.3) - the public-facing C++ site, with standing documents and the committee page.
- **open-std.org** (§4.3, deep) - the official archive of papers and drafts (introduced in Ch 3).
- **wg21.org** (§4.3, deep) - the enhanced mailing and paper-discovery site (introduced in Ch 3).
- **the wiki** (§4.4) - the committee's internal hub for agendas, schedules, Zoom links, and poll pages.
- **Mattermost** (§4.5) - the committee's real-time chat at chat.isocpp.org, for committee participants.
- **std-proposals** (§4.6) - the public mailing list on lists.isocpp.org for floating an idea before writing a paper.
- **telecon** (§4.7) - an online meeting a subgroup holds between the big in-person meetings.
- **the Beman Project** (§4.10) - builds open-source implementations of proposed standard library features so people can try them before the vote.

Prerequisites: paper, the mailing (Ch 3); subgroup, plenary (Ch 2).
Note: "straw poll" appears here in plain words only ("quick online votes"). The formal definition is owned by §8.2.
Links: isocpp.org, open-std.org, wg21.org, the public lists index on lists.isocpp.org, chat.isocpp.org, std-proposals, #include <C++> Discord, the isocpp.org meetings page (telecon count), P2195R2, P3712R0, P3713R0, herbsutter.com, N5040, the Beman Project. wg21.link is named, never linked.

---

## Chapter 5 - How WG21 Is Structured

Arc: enters seeing a blur of acronyms, leaves with a clear map of the rooms and who decides what.

Subheading order (as written):
- 5.1 One Committee, Many Rooms (the rooms and the schedule grid)
- 5.2 The Evolution Rooms: EWG and LEWG
- 5.3 The Wording Rooms: CWG and LWG
- 5.4 Study Groups (incubation; subgroup specialties; numbered SG1 through SG23, fifteen active as of 2026, the rest dormant; links the committee page instead of a table)
- 5.5 How a Paper Moves Between Groups (joint sessions)
- 5.6 The Train Model (ships every three years; C++14 onward, not C++11; Sutter proposed it in 2011, N3316; the model since 2012 per P1000R7, January 2026; contracts pulled from C++20 in 2019, P1823R0)
- 5.7 How Features Get Removed (pulling versus removing)
- 5.8 The People Who Run It (the convener appoints chairs, creates study groups, sets the schedule, and judges consensus; SC22 appoints the convener for three-year terms; two vice-conveners and a secretary; two project editors; chair; session staff)
- 5.9 Who Sets Priorities: The Direction Group (membership by invitation; rotating chair)
- 5.10 Chair Power (discretion, paper queues, scheduling as a silent veto; SD-4's rule for what chairs take first; every paper has a public GitHub tracking issue)
- 5.11 The Rules: Standing Documents (eight current, gaps from retired numbers; new ones need full-committee agreement)
- 5.12 The Limits of Power: Volunteers and the Implementer Veto (a veto over what you can use, not over what gets adopted; P3962R0, "Implementation reality of WG21 standardization," January 2026)

Owns:
- **the rooms** (§5.1) - the nickname for WG21's main working groups.
- **the schedule grid** (§5.1) - the timetable of parallel sessions across the week.
- **EWG (Evolution Working Group)** (§5.2) - the room that decides language design direction.
- **LEWG (Library Evolution Working Group)** (§5.2) - the room that decides library design direction.
- **CWG (Core Working Group)** (§5.3) - the room that reviews and polishes the exact language wording.
- **LWG (Library Working Group)** (§5.3) - the room that reviews and polishes the exact library wording.
- **study group (SG)** (§5.4) - a focused group that incubates ideas in one area before they move on to the main rooms.
- **the train model** (§5.6) - the rule that C++ ships on a fixed schedule, every three years, with whatever is ready.
- **convener** (§5.8, deep) - the officer who runs WG21: appoints chairs, creates study groups, sets the schedule, judges consensus; appointed by SC22 for three-year terms (introduced in Ch 2).
- **project editor** (§5.8) - one of the two people who maintain the working draft text.
- **chair** (§5.8) - the person who runs a room: sets its agenda, words its polls, and calls consensus.
- **the Direction Group** (§5.9, deep) - the small senior group that sets priorities. Long-term direction in P2000 (introduced in Ch 3), next-standard priorities in P5000.
- **the implementer veto** (§5.12) - the reality that if GCC, Clang, and MSVC won't implement something, the standard can't force them. A veto over what you can use, not over what gets adopted.

Prerequisites: convener, plenary, subgroup (Ch 2, restate with parenthetical); design review, wording review (Ch 3); IS (Ch 1).
Links: the committee page on isocpp.org, N3316, P1000R7, P1823R0, SC22, P2000, P5000, SD-4, the cplusplus/papers GitHub tracker, the standing documents page, P3962R0.

---

## Chapter 6 - Getting There

Arc: enters anxious about the practical leap, leaves prepared and braced.

Subheading order:
- 6.1 What a Meeting Week Looks Like (three per year, dates on the isocpp.org upcoming meetings page; Monday-Saturday, roughly 8 a.m. to 5 p.m. on weekdays per SD-5, Saturday wrapping up by 2 p.m., plus evenings; a short plenary Monday morning; the closing plenary Saturday, where adopted wording enters the working draft)
- 6.2 Preparing Before You Go (read the mailing, choose subgroups, read SD-4, check the wiki)
- 6.3 The Cost and How to Pay for It (no registration fee; travel, lodging, meals on you, can run into the thousands; each meeting's logistics paper, like N5057 for spring 2027, and SD-5; the week away from home; many sponsored by employers, others self-fund; the free guest and Boost paths remove the membership fee, not the trip)
- 6.4 What to Bring (packing is quick; laptop, charger, power adapter for the host country; patience)
- 6.5 Bracing for Your First Meeting (it will be overwhelming, and that's normal)

Owns:
- **meeting week** (§6.1) - the six-day Monday-to-Saturday gathering, held three times a year.

Prerequisites: the mailing, SD-4 (Ch 3); subgroup, the wiki (Ch 2, Ch 4); the rooms (Ch 5).
Psychological note: your first meeting is orientation, not production. Set expectations low and steady.
Links: the isocpp.org upcoming meetings page, SD-4, N5057, SD-5.

---

## Chapter 7 - In the Room

Arc: enters nervous about how to behave, leaves confident in the room's rhythm and norms.

Subheading order:
- 7.1 The Opening Plenary (officers, new members introduce themselves, agenda and updated working drafts approved, per SD-4 and the N4916 minutes)
- 7.2 Cycling Between Rooms (follow the paper schedule, not one room)
- 7.3 Meeting Etiquette (queue behavior, laptop etiquette; listen more than you talk at first)
- 7.4 How to Speak (small rooms usually raise hands, big rooms queue at a microphone; two minutes; state your name; use the microphone)
- 7.5 Confidentiality and the Code of Conduct (no blogging, tweeting, photos, or recording, because people need to speak freely, per N4916; what you can and cannot quote; the ISO Code of Ethics and Conduct plus the IEC Code of Conduct; the meeting slide; SD-4 points to ISO's reporting process)
- 7.6 Note-Taking (how minutes work, how to volunteer; SD-4: everyone present "should be prepared to take minutes"; why scribing teaches you the room)
- 7.7 Where Relationships Form (evening sessions, meals are networking)
- 7.8 Get Out of Your Lane (P2000: "try to spend at least one day each meeting in a WG that isn't 'your own'"; serve before you push; ask how the IETF or W3C does it)

Owns:
- **opening plenary** (§7.1) - the Monday session that introduces officers, welcomes new members, approves the agenda and the updated working drafts, then sends everyone to the rooms.
- **the Code of Conduct** (§7.5) - the ISO Code of Ethics and Conduct and the IEC Code of Conduct, which WG21 follows together; they cover behavior in meetings and on social media.
- **confidentiality rule** (§7.5) - the norm against blogging, recording, or quoting people by name without consent.

Prerequisites: plenary (Ch 2), the rooms, chair (Ch 5), paper schedule (Ch 3, Ch 5).
Psychological note: the meeting cadence is seductive; don't let attendance become the reward. Go into every discussion skeptical and question the room's priors.
Links: the ISO Code of Ethics and Conduct (iso.org PUB100011) and the IEC Code of Conduct (iec.ch basecamp page), both behind bot protection, so verified by search only; SD-4; P2000R5; the IETF; W3C.

---

## Chapter 8 - How Decisions Get Made

Arc: enters puzzled by how votes work, leaves able to read the room and vote with conviction.

Subheading order (as written):
- 8.1 The Culture of Consensus (not unanimity, absence of sustained opposition; ISO's definition, quoted in SD-4; consensus as social pressure)
- 8.2 Straw Polls and the Five-Point Scale (the chair may instead ask whether anyone objects; everyone in the room votes, guests included; the poll steers whether a paper moves on, goes back, or stops)
- 8.3 Reading Poll Results (the 2:1 guideline, applied after discussing the against votes and maybe a re-poll; neutrals stay out of the ratio, a neutral majority is a warning sign; strong opposition outweighs the count, the January 2022 poll at 37 to 17, P2459R0)
- 8.4 Straw Poll versus Formal Vote (formal votes in two places: the plenary poll, where the convener judges consensus, and the national ballots, one country, one vote)
- 8.5 When to Vote and When to Abstain (vote sincerely; be ready to explain an against vote, per SD-4; people who didn't read the paper "typically do not vote on that poll"; voting with the room is noise; P2000: not reading an on-time paper is no reason to oppose; demand evidence)
- 8.6 Two Gates: Direction versus Design (and "encouragement is not approval"; expansion statements, P1306R1, approved by EWG for C++20 in 2019, adopted for C++26 in 2025)
- 8.7 A Small Minority Can Block (but SD-4: consensus is not a tyranny of the majority or of the minority; the three-step escalation path with the 5 p.m. deadline the evening before the closing plenary; bring at least a draft paper; the convener asks national body chairs whether an objection is personal or national, and nothing counts as national until the delegation has talked it through)
- 8.8 The Plenary: Where Features Enter the Draft (closing plenary Saturday; unanimous consent, then a three-way poll; only the global directory votes; std::byte failed 24 to 15 in November 2016, N4623, and passed 44 to 2 with the same name in March 2017, N4654)
- 8.9 Processing Issues (CWG and LWG work the issues lists and move ready fixes at plenary in one batch, N5015)
- 8.10 The Countries Vote (countries usually see the draft twice: the committee draft for comments, the round meant for changing the text, which drew 411 comments for C++26, then the DIS for approval; a country with concerns votes yes with comments, and a no means "not at all," per SD-4; a good comment works like a small paper with a fix, and drafting one needs no seniority; C++26's DIS ballot ran July 31 to October 9, 2026; two-thirds of voting member countries approve and no more than a quarter of votes cast negative; FDIS only after technical changes, otherwise straight to publication; SD-4 wants near-unanimous support for design changes after the DIS)

Owns:
- **consensus** (§8.1) - general agreement shown by the absence of sustained opposition; not a majority and not unanimity.
- **straw poll** (§8.2) - a subgroup poll, usually on a five-point scale (strongly favor, weakly favor, neutral, weakly against, strongly against), that shows the room's sense and steers the work but puts nothing into the standard.
- **the 2:1 guideline** (§8.3) - the rough rule that a proposal normally advances with more than twice as many in favor as against.
- **formal vote** (§8.4) - a binding vote, distinct from a straw poll: the plenary poll on a motion, where the convener judges consensus, or a national ballot.
- **abstain** (§8.5) - choosing not to vote because you aren't familiar with the issue.
- **direction approval** (§8.6) - an early "we want this" gate.
- **design approval** (§8.6) - a later "this specific design is right" gate.
- **escalation path** (§8.7) - SD-4's three steps for a "cannot live with" objection: tell the EWG and LEWG chairs, post on the subgroup's reflector by 5 p.m. the evening before the closing plenary, and raise it in your national body, with at least a draft paper.
- **closing plenary** (§8.8) - the Saturday session where subgroups report and the committee polls to adopt wording into the working draft.
- **committee draft** (§8.10) - the comment ballot, the round meant for changing the text. Chapter 3 describes the comment round in plain words. Lowercase in running text, and the book doesn't use the acronym CD.
- **DIS / FDIS** (§8.10) - the Draft and Final Draft International Standard ballot stages where national bodies vote, one country, one vote. The FDIS happens only when the text changes technically after the DIS.

Prerequisites: plenary, national body, guest, global directory (Ch 2); paper, SD-4, issues lists, Direction Group / P2000 (Ch 3); the reflector (Ch 4); the rooms, EWG, LEWG, CWG, LWG, chair, convener (Ch 5).
Psychological note: consensus is social pressure with a polite name. Keep your wits about you, vote your conviction not the room's momentum, and demand evidence.
Links: SD-4, P2459R0, P2000R5, P1306R1, N4623 (Issaquah 2016 minutes), N4654 (Kona 2017 minutes), the core and library issues lists, N5015 (the June 2025 editors' report).

---

## Chapter 9 - What Goes Into a Proposal

Arc: enters with an idea, leaves knowing the bar a proposal must clear.

Subheading order:
- 9.1 What Belongs in a Paper (motivation, design, alternatives, implementation experience; cite earlier papers on the same ground; thank reviewers by name, and P4024R0 says a single author citing diverse reviewers is equally valid)
- 9.2 The Three Pillars (example-based, principle-based, shows alternatives; SD-4's own three, the difference between "someone's cool idea" and "a real proposal")
- 9.3 The Abstract as Elevator Pitch
- 9.4 Tony Tables (named for Tony Van Eerd, who came up with the format; his C++17 tables on GitHub)
- 9.5 Show the Alternatives: The Steel Man (two steel men; P2000: showing only your design's advantages and only a rival's disadvantages "is not acceptable"; the best answer is that it already works)
- 9.6 Implementation Experience (and feature-test macros, with the rules in SD-FeatureTest, kept by SG10)
- 9.7 Writing Standard Wording (shall versus should; stable labels, not section numbers; SD-4 expects you to find a wording expert before the wording groups see your text)
- 9.8 A Short Tutorial (P2000 asks for one during design, to keep features for "ordinary programmers" out of expert-only territory)
- 9.9 Scope and Dependencies (split large papers, ship in stages)
- 9.10 The High Bar (burden on the proposer, default no; core language is hard mode; most papers don't make it: the Networking TS, 2018, still not in the standard, and the Transactional Memory TS never merged)

Owns:
- **the three pillars** (§9.2) - the habit that a strong paper is example-based, principle-based, and shows alternatives. SD-4 asks for all three. A coined label, so lowercase.
- **Tony Table** (§9.4) - a side-by-side before/after table that makes a proposal's value visible, named for Tony Van Eerd.
- **steel man** (§9.5) - the strongest version of the argument against your proposal, which you then answer with evidence. A coined label, so lowercase.
- **implementation experience** (§9.6) - proof your proposal has been built and used, ideally in more than one place.
- **feature-test macro** (§9.6) - a predefined symbol that lets code check whether a compiler supports a feature. The rules are in SD-FeatureTest.
- **shall / should** (§9.7) - standard-wording verbs: "shall" is a requirement, "should" is advice.

Prerequisites: paper, design review, wording review, SD-4, P2000, the Direction Group (Ch 3); the standard, stable labels (Ch 1); study group, CWG, LWG, chair (Ch 5); consensus, design approval (Ch 8).
Psychological note: be convinced by overwhelming evidence and nothing else. Go into your own paper skeptical.
Links: P4024R0, SD-4, Tony Van Eerd's cpp17_in_TTs on GitHub, P2000R5, SD-FeatureTest, the Networking TS and the Transactional Memory TS on iso.org (bot-protected, so verified by search only).

---

## Chapter 10 - Producing and Submitting Your Paper

Arc: enters ready to write, leaves equipped with the tools and the submission path.

Subheading order:
- 10.1 Float the Idea First (std-proposals; P4024R0's "no surprise competitors" rule: check for papers on the same problem, talk to their authors before the working group, aim for one unified paper)
- 10.2 Writing the Paper: Tools and Template (mpark/wg21, Bikeshed, COWEL, LaTeX; the official template is the "Template for Library Proposals" at the bottom of the submit-a-proposal page)
- 10.3 The Formatting Standard: SD-7 (paper number, format, submission; the pre-meeting deadline is the Monday four weeks before the meeting, per SD-7; each paper in a mailing gets a GitHub tracker issue)
- 10.4 Make It Accessible (contrast, monospace code, logical headings)
- 10.5 Prototyping: Compiler Explorer and GitHub
- 10.6 Coauthoring and Revision History
- 10.7 Patent Disclosure
- 10.8 Getting on the Agenda (email the chair, and asking isn't pushy; no presenter means no discussion)
- 10.9 The Other 80% (design approval is a start, not the finish; the life-of-a-proposal page's "other 80%" line)

Owns:
- **SD-7** (§10.3) - the standing document with the paper formatting rules, how to get a paper number, and the mailing deadlines.
- **the official template** (§10.2) - the "Template for Library Proposals" on isocpp.org's submit-a-proposal page, plus the tools' own versions in mpark/wg21 and Bikeshed.
- **Compiler Explorer** (§10.5) - the online tool (godbolt.org) for showing code run across compilers.

Prerequisites: std-proposals (Ch 4); paper, P-number, the mailing, the deadline (Ch 3); chair, the GitHub paper tracker, the Direction Group (Ch 5); design approval (Ch 8); implementation experience (Ch 9).
Links: std-proposals, the isocpp.org submit-a-proposal page, P4024R0, mpark/wg21, Bikeshed, COWEL, SD-7, godbolt.org, the ISO patent policy (iso.org, verified by search only), the cplusplus/papers GitHub tracker, the isocpp.org life-of-a-proposal page.

---

## Chapter 11 - Championing Your Paper

Arc: enters hopeful about your paper, leaves resilient for the long social campaign.

Subheading order (as written):
- 11.1 Before the Room: Presocialization (the five minutes before a poll; earn supporters over years by reviewing other people's papers first)
- 11.2 Finding and Being a Champion (finding one when you can't attend)
- 11.3 The First Gate: "Do We Want It at All?" (frame it in the Direction Group's priorities, P5000R1)
- 11.4 When the Poll Goes Against You (sent back is not rejection; re-litigation)
- 11.5 Negotiating: Back-Pocket and Max-Min
- 11.6 Disagreement versus Opposition, and When to Withdraw
- 11.7 How Reputation Works (start small, claim a territory, pick your battles)
- 11.8 The Presenter Is Judged Too (don't cause needless delay; SD-4 warns that escalating topic after topic erodes credibility; procedural momentum)
- 11.9 The Long Game (years not months; famous long-running proposals; stackful coroutines' P0876 at revision 24 as of July 2026)
- 11.10 The Structural Headwinds (the Bandwidth Gap; the expert bubble; corporate resource asymmetry)
- 11.11 The Emotional Side (don't take it personally; burnout is real; the 2020 pulse poll in P2260R0: over 60 percent often exhausted by meetings and other demands)

Owns:
- **presocialization** (§11.1) - talking to people about your idea in the hallways before you present it.
- **champion** (§11.2, deep) - the person who presents and advocates for a paper, author or not (introduced in Ch 2).
- **back-pocket alternative** (§11.5) - a fallback design you keep ready if your first choice is rejected. Hyphenated, per AGENTS.md.
- **max-min solution** (§11.5) - the smallest version of a proposal that everyone can accept.
- **re-litigation** (§11.4) - re-debating a question the committee already settled.
- **procedural momentum** (§11.8) - the benefit of the doubt a paper earns from many revisions and prior favorable polls.
- **the Bandwidth Gap** (§11.10) - there are far more papers than reviewers and time to handle them.
- **the expert bubble** (§11.10) - the tendency for papers to be written by experts for experts.

Prerequisites: paper, design and wording review (Ch 3); the rooms, the Direction Group, chair (Ch 5); consensus, straw poll, direction and design approval (Ch 8); most papers don't make it (Ch 9).
Psychological note: burnout is real, the Bandwidth Gap is structural, and knowing when to stop is a skill. Set boundaries.
Links: P5000R1, SD-4, P2300R10, P0876R24, P2260R0.

---

## Chapter 12 - C++ Design Principles

Arc: enters wondering why good ideas die, leaves respecting the deep constraints.

Subheading order:
- Intro (the rules come from Stroustrup's The Design and Evolution of C++, 1994, called D&E; read it before a language proposal)
- 12.1 Standardize Existing Practice (the committee's safest path; bless what already works; fmt and range-v3, linked)
- 12.2 Backward Compatibility (the weight of decades of code; the committee is reluctant to ship two versions of a type; C++20 added std::jthread beside std::thread rather than change the old one)
- 12.3 The Zero-Overhead Principle
- 12.4 ABI: The Invisible Constraint (the constraint you're least likely to see coming; std::regex locked by layout, std::unordered_map also by its interface; the Prague ABI vote of 2020, on Titus Winters's P1863R1 and P2028R0; the ABI Review Group advises on particular proposals)
- 12.5 Freestanding versus Hosted

Owns:
- **standardize existing practice** (§12.1) - the preference for blessing tools that already work over inventing new ones.
- **backward compatibility** (§12.2) - the rule that old code keeps working with new standards.
- **the zero-overhead principle** (§12.3) - you don't pay for what you don't use, and what you use you couldn't hand-code better.
- **ABI (application binary interface)** (§12.4) - the binary contract between compiled pieces of a program; breaking it breaks existing programs.
- **the Prague ABI vote** (§12.4) - the February 2020 decision not to break ABI across the library for C++23, while refusing to promise stability forever. In effect, existing binaries stayed safe and the frozen types stayed frozen.
- **freestanding vs hosted** (§12.5) - two environments: freestanding (no operating system, limited library) and hosted (full library).

Prerequisites: the standard, the three implementers (Ch 1); the implementer veto, the Direction Group (Ch 5).
Links: The Design and Evolution of C++ (stroustrup.com), fmt and range-v3 on GitHub, P1863R1, P2028R0.

---

## Chapter 13 - Common Mistakes

Arc: enters confident, leaves humble and careful, able to step around the traps.

Subheading order (one mistake per section, each a recap with the correct behavior):
- 13.1 Showing Up Without Announcing (and guest status covers your first meeting only, so talk to a national body before your second)
- 13.2 Proposing Core Language Features Too Early
- 13.3 Writing an Idea-Only Paper
- 13.4 Skipping the Search for Competing Papers (P4024R0's "no surprise competitors" rule, from chapter 10)
- 13.5 Voting on Things You Haven't Followed
- 13.6 Quoting Reflectors or Notes Publicly (share only poll questions and numbers; no live-posting, even in paraphrase)
- 13.7 Raising Concerns Too Late (tell your national body; the 5 p.m. deadline the evening before plenary)
- 13.8 Expecting Majority Rule (consensus works both ways: a minority can stall a paper, but being heard isn't a veto)
- 13.9 Talking Too Much Too Soon
- 13.10 Misreading Encouragement as Approval
- 13.11 Ignoring Subgroup Direction
- 13.12 Declaring Victory at Design Approval
- Closing (the rules keep changing, so don't treat the notebook as scripture: read each new SD-4 and trip report and trust them over it; then participation is not impact; farewell)

Owns: no new terms. Restate each referenced term with a short parenthetical.

Prerequisites: draws on every prior chapter.
Psychological note: don't confuse committee participation with impact. A proposal that never ships helped nobody.
Links: P4024R0, SD-4.
