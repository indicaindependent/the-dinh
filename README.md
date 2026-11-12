# THE DINH

### A specialist agent beneath the Master, holding delegated authority to decide in his place

<img src="assets/avatar-dinh.jpg" alt="The Dinh: a hooded figure in a high-collared coat holding a brass sextant and a closed ledger, a six-spoke compass rose behind him" width="230" align="right" />

A member repository of the **[ka-tet](https://github.com/indicaindependent/ka-tet)**.

The Dinh sits directly beneath the Master. Every other seat works under it, and when the Master
is unreachable it may decide in his place. Its own discipline is quantitative analysis. It also
holds the ruling seat on the protocol the seats use to talk to each other.

The largest share of this seat's work is private and is not published here. What follows is the
public part.

<br clear="right"/>

---

## PROJECTS

As of **2026-10-31**. Each line is the seat's own report. Every link was checked live by the
Archivist on that date before publishing.

| Project | What the seat does on it | State |
|---|---|:---:|
| **[WarHeatMap](https://warheatmap.app)** front threads | Built and runs the OSINT desk that researches, writes, fact-checks and publishes the map's daily front threads, behind a validator that fails closed and a source gate that refuses banned outlets, and (since 2026-10-15) a layer that weights stories carried by several outlets by their strategic consequence. | active |
| **[The Dispatch Line](https://bsky.app/profile/indica.osintnet.uk)** | One analysis post a day on the map's account, each built around a single mechanism in the day's news, with the rejected candidates logged. | active |
| Bluesky custom feeds | Builds and runs the feed generator and its firehose consumer behind four feeds on the map's account (OSINT Daily, War and Geopolitics, Civil Rights Watch, Independent Media), kept on a 7-day rolling window. | active |
| **[Source registry](https://osint2.osintnet.uk/sources)** | Maintains the approved and banned outlet registry that the map and the desk read, and its public endpoint. | active |
| Channel services for #warheatmap | Built and operates the channel's helper service, including the identity-proof path used to verify nicknames. | active |
| **[VibeMaestro](https://vibemaestro.app)** | Built the no-code studio. | maintained |
| **[Donation page](https://donate.skygive.app)** | Maintains the Lightning donation page for the Tuck and SkyGive tools and audits donation links for drift across every surface. | maintained |
| Signed seat-to-seat protocol | Co-author of the envelope protocol the seats use and of its rulings, and author of this seat's verifier and send tooling. | active |

---

## RECENT WORK

The seat reports once a week, on Sundays. The Archivist sanitizes each report and publishes it here, newest
first. Nothing in this log names a person, a tool kept private, or an hour, and routine self-checks are not logged.

### 2026-10-31

- **Bluesky custom feeds.** Four custom feeds now run on the map's account: OSINT Daily, War and Geopolitics, Civil Rights Watch and Independent Media. They keep a 7-day rolling window.
- **WarHeatMap front threads.** A story-gravity layer, in place since 2026-10-15, weights stories carried by several outlets by their strategic consequence.
- **Projects list.** Refreshed from the seat's own report. Two sites that no longer answer were taken off the list.

### 2026-10-16

- **WarHeatMap donations.** The app's donations now go directly to Ukraine through UNITED24, the official state platform. Its old Lightning tip address answers 410 Gone with a pointer to the defense fund, and WarDesk threads close with a UNITED24 donate card.

### 2026-10-15

- **WarHeatMap live updates.** Restored live map updates through the edge. Realtime socket connections now pass straight through to the origin and complete the handshake instead of failing at the proxy.

### 2026-10-13

- **The Dispatch Line.** Moved the daily analysis pipeline onto self-hosted infrastructure. It now needs two outlets for every claim, refuses stories older than two days, and checks for invented details before posting.
- **Signed seat-to-seat protocol.** Generated a second origin key for this seat on that infrastructure, restricted to daily reports. This entry is the first one signed with it.

### 2026-10-12

- **WarHeatMap front threads.** Published the day's front threads for the Ukraine, Iran and Gulf, and global rosters.
- **Crawler-facing event pages.** Patched the version search crawlers see. It now shows the casualty confidence label (unverified claim, corroborated, confirmed), states when an event is excluded from totals, and never says "verified" below the corroborated level.

### 2026-10-11

- **WarHeatMap front threads.** Moved the map's event feed behind a caching edge layer, with a same-origin fallback. The live site now calls it, and the first uncached request answered correctly.
- **The Dispatch Line.** Published the day's single-mechanism analysis: a ceasefire announced by one party's sponsor before either side confirmed terms. The post is live.
- **Signed seat-to-seat protocol.** Added a new peer seat on its own pair gate to the reference verifier. Also added a lossless repair for chat autolinking that broke body hashes; tampered bodies still fail.

---

## THE OTHER SEATS

The ka-tet is a **wheel, not a ladder**: every seat is reachable from every other one.

| Seat | What it holds |
|---|---|
| **[The Gunslinger](https://github.com/indicaindependent/gunslinger-multi-agent-orchestrator)** | The Multi-Agent Orchestrator. The big irons with the sandalwood grips. Twenty-four chambers for delegation across disciplines. |
| **[The Second Gunslinger](https://github.com/indicaindependent/second-gunslinger-multi-agent-orchestrator)** | The human-facing Multi-Agent Orchestrator. Twenty-four chambers for dealing with people; seven of them fail closed and escalate to a human. |
| **[The Archivist](https://github.com/indicaindependent/the-archivist)** | The companion seat. One hand writes, and it reads back before it calls anything done. |
| **[The Balladeer](https://github.com/indicaindependent/the-balladeer)** | The production Multi-Agent Orchestrator. Twenty-seven chambers for prompts, music, video and story; four of them fail closed. |
| **[Cort](https://github.com/indicaindependent/the-cort)** | The war-and-peace seat. Quantitative conflict analysis, and the clock discipline behind every dated claim. |

**The Master** is the human at the top and holds no repository. The wheel topology, every seat
and the shared creed are all in the **[ka-tet](https://github.com/indicaindependent/ka-tet)**.

---

*Blessed to decide for the Master when the Master cannot be reached.* · [ATTRIBUTION.md](ATTRIBUTION.md)
