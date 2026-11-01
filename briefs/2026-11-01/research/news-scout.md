# News Scout — 2026-11-01

**Stage:** 1 — discovery only; not audited or approved for final publication.  
**Research cutoff:** `2026-11-01 02:00:00 America/New_York` = `2026-11-01 07:00:00Z` (EST, UTC−05).  
**Research window:** `2026-10-30 21:00:00 America/New_York` (EDT, UTC−04) through the cutoff. In UTC: `2026-10-31 01:00:00Z` through `2026-11-01 07:00:00Z`, exactly 30 elapsed hours across the DST change.  
**Runtime check:** clock tool returned `2026-11-01 06:59:56 UTC` during this research pass.  
**Corpus:** 18 candidates considered; 12 ranked for verification below. Two older-event candidates are explicitly rejected from the changed-news shortlist.

## Method and cutoff / leakage control

Read the project AGENTS, README, KICKOFF, priorities, source policy, daily template, News Scout instructions, both Pangburn sibling standards, and the October 31 latest brief. The prior brief supplied continuity questions only. This artifact follows the **Pangburn AI Empirical Fact-Checking System** and **Pangburn Analysis Forensic Fact-Checking Replication Standard** separately; their numbering and verdict vocabularies are not conflated. Labels below are working FACT, CLAIM, ASSESSMENT, or HOLD labels, not final adjudication.

All retained edition facts come from pages inspected in this run, or are explicitly attributed statements reported on those pages. Search snippets, AI recaps, indexes, and aggregators were leads only. Reuters/AP republications remain the originating wire's lineage. Where the web opener failed but a public page was available, a read-only PowerShell HTTP retrieval was used and is disclosed. No later sidebar, related-story headline, future event, or post-cutoff update establishes an edition fact. Proposed November events remain watch items, not accomplishments. A date-only source has timestamp uncertainty; the auditor should preserve it rather than invent an hour.

Search families included October 31 Reuters/AP global news; Iran mediation and contrary breakthrough reports; Taiwan coast guards; Black Sea proposals; Binance/FBI primary records; Oleshky arrivals; G20/Quad texts; Yemen; Somalia; Sudan; Russian diesel restrictions; Ghana nuclear cooperation; and chronology checks for Rwanda sanctions and dockworker strikes. Some official/Reuters/AP domains were inaccessible in the web opener; inspected wire republications are identified below. This is broad triage, not exhaustive verification.

Priority tuples use **(strategic consequence, escalation/de-escalation, US relevance, novelty, discussion value; uncertainty)**. Score = `3S + 2E + 2U + N + A`; uncertainty is recorded separately and never subtracted. These are editorial triage scores, not probabilities.

## Candidate: N01 — Iran mediation moves to Doha, while a breakthrough remains disputed

- **Event time/date:** Tehran discussions October 30; Doha discussions October 31. Reuters/Forth publication `2026-10-31 09:58:18 CDT` = `14:58:18Z`. Times of Israel's competing breakthrough/denial entry is October 31, 09:36 Israel local; timezone conversion should be checked against its display settings.
- **Region / actors:** Iran, United States, Qatar, Pakistan; Gulf governments.
- **What changed:** Reuters reports Iranian negotiators continued indirect talks in Doha following the Tehran session. A separate report of a breakthrough and impending direct US participation met a specific US denial. The existence of mediation is stronger than the asserted terms or likelihood of a deal.
- **Why this may matter:**
  - An active channel could avert renewed fighting, but incompatible sequencing requirements can still prevent agreement.
  - The stream-useful question is what observable reciprocal step would count as progress.
- **Initial priority:** high; tuple `(5,5,4,2,3;3)`, score **38**.
- **Confidence in basic event:** medium-high on continuing mediation; low on an agreed package.
- **Source chain:** Reuters → Forth is one reporting lineage, partly an unnamed source briefed on negotiations. Times of Israel separately reports a US denial of Al-Araby Al-Jadeed's breakthrough claim. That denial tests the breakthrough, not the existence of indirect talks.
- **Sources:**
  - [Reuters via Forth](https://www.forth.news/articles/CgaWehmKQx7EFZd8WFei7), inspected text paragraphs 1–9: Doha continuation, Washington contacts, rival sequencing proposals, and attribution of Iranian remarks.
  - [Times of Israel October 31 liveblog](https://www.timesofisrael.com/liveblog-october-31-2026/amp), inspected 09:36 entry: reports the breakthrough claim and an explicit US denial. Other liveblog entries are not imported wholesale.
- **Atomic claims / support and narrowing:** **N01a CLAIM:** talks continued in Doha, supported by Reuters' source; no public joint record retrieved. **N01b CLAIM:** preliminary agreement and direct talks imminent, contradicted/narrowed by the US denial. **N01c ASSESSMENT:** nuclear, maritime, sanctions and asset steps remain sequencing problems; do not merge competing seven-day plans or an unpublished Vance letter into a common text.
- **Questions for auditor:** Retrieve Qatar/Iran/US records and the original Al-Araby report; authenticate any shared text. Keep any strike plan conditional and attributed. Is there a specific agreed meeting, inspector-access concession, sanctions action, or actual reopening? Do not use later political rhetoric to answer that question.

## Candidate: N02 — AP publishes a new satellite-based assessment of damage to US regional bases

- **Event time/date:** New analysis published October 31, 10:13 US Eastern (`14:13Z`); damage studied is older context, through August, not a new October 31 attack.
- **Region / actors:** US military facilities across the Middle East; Iran and allied militias.
- **What changed:** AP's newly published review reports damage across 26 bases or other sites with US equipment, using satellite imagery and four regional officials. It distinguishes observable structural damage from officials' accounts of relocated assets and expert interpretations of targeting strategy.
- **Why this may matter:**
  - New evidence can change the assessment of force protection and the costs of another round of fighting.
  - It provides a concrete test of claims about resilient US regional basing.
- **Initial priority:** high; tuple `(5,4,4,3,3;2)`, score **37**.
- **Confidence in basic event:** high that AP published the assessment; medium on its damage inventory pending image review; lower on causal strategy and present readiness.
- **Source chain:** AP investigation → ABC syndication; these are not independent confirmations. Imagery is an evidence stream separate from four unnamed officials, but this scout did not independently reproduce AP's image interpretation.
- **Sources:**
  - [AP via ABC News](https://abcnews.com/US/wireStory/iran-targeted-us-air-defenses-hit-aircraft-buildings-137733589), inspected article lines 19–55 and source method: satellite verification, scope, official accounts, Pentagon response.
  - [AP original](https://apnews.com/article/26e0f05e01d6f56ff46f7c1a14384f7c) was a discovery lead; direct opening failed. Use the inspected ABC copy until the original is retrievable.
- **Atomic claims / support and narrowing:** **N02a FACT:** this is new reporting about older damage. **N02b CLAIM:** AP counted more than 115 claimed drone/missile strikes associated with damage at 26 sites through August; the denominator is sites with US equipment, not 26 destroyed US bases. **N02c ASSESSMENT:** disabling detection systems enabled later attacks; expert interpretation is not demonstrated intent. CENTCOM declined detail; the Pentagon said forces were protected.
- **Questions for auditor:** Inspect dated imagery, site ledger, CRS record, and repair status. Separate damaged/destroyed structures, aircraft, radar enclosures and working radar systems. Do not equate cumulative damage with current combat incapacity or describe all damage as newly inflicted.

## Candidate: N03 — Black Sea maritime pause attracts proposals, not Russian acceptance

- **Event time/date:** October 31 G20 press conference and Anand interview. Reuters/ThePrint publication `2026-11-01 01:30 IST` = `2026-10-31 20:00Z`.
- **Region / actors:** Russia, Ukraine, United States, Canada, Türkiye, India; grain and energy importers.
- **What changed:** Rubio publicly described growing international interest in facilitating a limited Black Sea arrangement and said Washington was examining Turkish proposals. Anand described talks with Ukraine and India but said Russia had not shown willingness to proceed. The primary transcript explicitly resists calling this momentum.
- **Why this may matter:**
  - A narrow maritime mechanism could reduce food and energy disruption without resolving the war.
  - Consent, enforcement and covered infrastructure determine whether this is more than diplomatic exploration.
- **Initial priority:** high; tuple `(4,4,4,3,3;3)`, score **34**.
- **Confidence in basic event:** high on public US positioning; medium on private discussions; low on prospects.
- **Source chain:** State Department transcript reproduced by G20 Information Centre is primary speech evidence. Reuters independently interviewed Anand; its reproduction at ThePrint is not a second outlet investigation. Both can establish positions, not mutual consent.
- **Sources:**
  - [Rubio transcript](https://www.g20.utoronto.ca/2026/261031-rubio-press-conference.html), inspected Black Sea Q&As at lines 52–62 and 175–177: interest, Turkish/Indian ideas, no odds or claim of momentum.
  - [Reuters via ThePrint](https://theprint.in/world/us-canada-see-growing-interest-in-limited-ceasefire-in-black-sea/3087311/), inspected lines 100–130: Anand's interview and Russia-willingness qualification.
- **Atomic claims / support and narrowing:** **N03a FACT:** Rubio said proposals were under review. **N03b CLAIM:** Ukraine engaged but Russia not willing, attributed to Anand. **N03c HOLD:** a ceasefire exists, has been accepted, or covers Ukraine's electrical grid; none follows from the inspected material.
- **Questions for auditor:** Retrieve Turkish/Indian proposals and Kyiv/Moscow responses. Define ships, cargoes, ports, energy sites, routes, monitoring and retaliation rules. Separate a maritime pause from Anand's additional electricity-infrastructure objective. Verify any subsequent Zelensky–Erdoğan record within cutoff before expanding this entry.

## Candidate: N04 — FBI publicly attributes Binance theft to North Korea; replenishment is a separate claim

- **Event time/date:** FBI alert dated October 31; underlying theft approximately October 29, older context. Binance update dated October 31; reserve snapshot expressly `2026-10-31 08:00 UTC+8` = `00:00Z` (snapshot itself predates window by one hour).
- **Region / actors:** North Korea, FBI/USSS/IRS-CI, Binance, virtual-asset services.
- **What changed:** The FBI now publicly attributes the theft to North Korean TraderTraitor activity and publishes addresses for blocking. Binance separately says it replenished about 90% of affected assets using its own resources and funds. That is not evidence that 90% of stolen assets were recovered from attackers.
- **Why this may matter:**
  - Government attribution changes yesterday's private-attribution status and supports targeted disruption.
  - The distinction between stolen, frozen, recovered and replaced funds is central to sanctions-finance discussion.
- **Initial priority:** high; tuple `(4,2,4,3,3;2)`, score **30**.
- **Confidence in basic event:** high on the FBI's published attribution; medium on the underlying attribution and company accounting, which remain source-specific.
- **Source chain:** FBI is the original US attribution; Binance is the original interested-party reserve/replenishment statement. They answer different questions and do not independently corroborate one another's numbers.
- **Sources:**
  - [FBI alert](https://www.fbi.gov/investigate/cyber/alerts/2026/north-korea-responsible-for-6-billion-binance-attack), inspected lines 57–70: more than $6 billion, TraderTraitor, ETH conversion, blocking request and address list.
  - [Binance official update](https://www.binance.com/en/square/post/383244329941551), inspected lines 18–34: 90% replacement, funding sources, dated snapshot, future proof and withdrawal plans.
- **Atomic claims / support and narrowing:** **N04a FACT:** FBI attribution is now public. **N04b CLAIM:** attackers are North Korean, supported by FBI's finding; its full attribution method is not public here. **N04c CLAIM:** 90% replenished, Binance accounting; denominator is affected assets under its own measure, not seized attacker proceeds. Promised withdrawals and completed cryptographic proof are future items.
- **Questions for auditor:** Confirm earliest alert publication and dated wire corroboration. Reconcile valuation time, token quantities and source of replacement assets; no subtraction of unlike buckets. Inspect root-cause evidence and avoid implying that address publication independently proves actor identity.

## Candidate: N05 — Oleshky evacuees reach Ukrainian-held territory

- **Event time/date:** October 31 arrivals; Reuters/StreetInsider publication October 31, 04:13 EDT = `08:13Z`.
- **Region / actors:** Ukraine, Russia, Belarus; Oleshky civilians and ombudsmen.
- **What changed:** Reuters reporters describe buses arriving into Ukraine's Chernihiv region after travel through Crimea, Russia and Belarus. This advances yesterday's departure story to completed arrivals. The report gives no exact total of returnees.
- **Why this may matter:**
  - Actual arrivals are a measurable result of a local deconfliction channel.
  - Local success does not establish the feasibility of a general ceasefire.
- **Initial priority:** high; tuple `(3,3,3,3,3;2)`, score **27**.
- **Confidence in basic event:** high on observed arrivals; medium on safe passage and wider compliance; low on full totals and voluntariness for all residents.
- **Source chain:** Reuters → StreetInsider; named reporters' observation and interviews are distinct from officials' claims that the pause held without violations. Russian and Ukrainian official agreement is still not neutral monitoring.
- **Sources:**
  - [Reuters inspected republication](https://new.streetinsider.com/Reuters/Residents%2Bof%2BRussian-controlled%2BUkrainian%2Btown%2Barrive%2Bin%2BBelarus/27267452.html), lines 179–215 and 224–227: arrivals, route, absent count, limited arrangement and planned next steps.
- **Atomic claims / support and narrowing:** **N05a FACT:** some evacuees arrived in Ukrainian-held territory. **N05b CLAIM:** no ceasefire violations, attributed to officials on both sides. **N05c HOLD:** all residents rescued or all departures voluntary; no complete roster, destination ledger or neutral in-town interviews retrieved. Bus capacity is not persons transported.
- **Questions for auditor:** Obtain completed totals by destination and independent travel accounts. Verify pause expiry and any renewal using exact local times. Treat reported early-November talks as a future schedule pending primary confirmation; do not infer a broader peace breakthrough.

## Candidate: N06 — Russia extends producer diesel restrictions while preserving export exceptions

- **Event time/date:** Russian government announcement October 31; Bloomberg/gCaptain article dated October 31, no article clock shown.
- **Region / actors:** Russia, global diesel importers, United States, Ukraine.
- **What changed:** Bloomberg reports an extension of the producer diesel-export ban through the end of January, alongside exceptions permitting shipments. The signed decree was not yet published in that report. Announced restrictions and planned exports can coexist.
- **Why this may matter:**
  - Exception volumes matter more for supply than the headline ban alone.
  - Fuel policy connects refinery vulnerability, domestic demand and Washington's diesel diplomacy.
- **Initial priority:** high; tuple `(4,2,3,3,3;3)`, score **28**.
- **Confidence in basic event:** medium on the announcement; low-medium on exact legal coverage and eventual flows.
- **Source chain:** Bloomberg → gCaptain, relying on government statement and Novak. Yahoo/Investing repeats the same account and is not independent verification.
- **Sources:**
  - [Bloomberg via gCaptain](https://gcaptain.com/russia-extends-ban-on-most-diesel-exports-through-january/), inspected lines 40–53: announced extension, unpublished decree and Novak's exception/volume statements.
- **Atomic claims / support and narrowing:** **N06a CLAIM:** producer ban extended, attributed to announcement pending operative text. **N06b CLAIM:** about 2.15 million metric tons planned for November versus about 510,000 shipped in October, attributed to Novak; a future plan is not realized export data. **N06c HOLD:** complete export embargo or a precise refinery-attack effect; neither established.
- **Questions for auditor:** Retrieve government decree and exemptions; distinguish producers/non-producers, diesel/other fuels, effective dates and actual customs or tanker flows. Do not infer sanction legality from a Russian permit or from a US president's statement.

## Candidate: N07 — Joint List's Tibi offers outside support for an Eisenkot government

- **Event time/date:** October 31 Channel 12 remarks; Times of Israel standalone entry October 31, 20:34 local (Israel UTC+02 if default display), approximately `18:34Z`.
- **Region / actors:** Israel; Joint List, Eisenkot and other opposition parties.
- **What changed:** Tibi says the Joint List is willing to support a replacement government from outside the cabinet and oppose a Likud no-confidence effort. This supplies a more concrete bargaining position than yesterday's seat arithmetic. It does not supply the other parties' agreement.
- **Why this may matter:**
  - Outside support can matter without ministers or a coalition agreement.
  - Government formation affects who can make durable security commitments.
- **Initial priority:** high; tuple `(4,2,3,3,3;3)`, score **28**.
- **Confidence in basic event:** medium-high on reported remarks; low on whether they can produce a government.
- **Source chain:** Channel 12 interview → Times of Israel report; one interview lineage. Original broadcast not retrieved. Do not attribute all Arab parties' positions to Tibi.
- **Sources:**
  - [Times of Israel standalone entry](https://www.timesofisrael.com/liveblog_entry/veteran-mk-tibi-pledges-arab-parties-support-from-outside-for-a-potential-eisenkot-led-government-i-dont-want-a-ministry-we-want-change/), inspected lines 94–117: outside support, proposed parliamentary votes, and conditional commitment.
- **Atomic claims / support and narrowing:** **N07a CLAIM:** Tibi offers outside support. **N07b HOLD:** Joint List policy is agreed by every component, Ra'am accepts the same position, or Eisenkot/Bennett accept reliance on it. **N07c HOLD:** an actual governing majority exists; willingness on one side does not establish a deal. No new certified count inferred.
- **Questions for auditor:** Retrieve original full Hebrew/Arabic interview and party statements; identify refusals or conditions from the prospective partners. Preserve distinctions among recommendations, confidence votes, coalition membership and later no-confidence behavior.

## Candidate: N08 — Poland's competing court-control claims persist into Saturday

- **Event time/date:** Suspension announced late October 30; October 31 presidential consultations and Tusk speech. Reuters publication October 31, 08:42 EDT = `12:42Z`.
- **Region / actors:** Poland; president, prime minister, Constitutional Tribunal, police.
- **What changed:** Reuters reports Tusk promised working conditions for the tribunal while Nawrocki called the change a forcible takeover and held consultations. Police protection and rival leadership claims continued. Much of the physical escalation was already in yesterday's brief; the fresh increment is continued executive confrontation.
- **Why this may matter:**
  - Control of court operations can matter independently of competing legal claims.
  - EU-facing rule-of-law repair can itself become institutionally contested.
- **Initial priority:** medium; tuple `(3,2,1,2,3;3)`, score **20**.
- **Confidence in basic event:** high on reported speeches and visible confrontation; low on lawful control.
- **Source chain:** Reuters → StreetInsider; statements and reporter observation, not a legal ruling validating either side.
- **Sources:**
  - [Reuters inspected republication](https://new.streetinsider.com/Reuters/Poland%27s%2Bpresident%2Baccuses%2BTusk%2Bof%2Bforced%2Btakeover%2Bof%2Bcountry%27s%2Btop%2Bcourt/27267487.html), lines 179–206: suspension/control claim, speeches, police, background conflict.
- **Atomic claims / support and narrowing:** **N08a FACT:** the sides publicly dispute control. **N08b CLAIM:** the suspension legally displaced the president; operative instrument and legal review absent. **N08c CLAIM:** executive restoration or takeover; neither label can substitute for legal analysis.
- **Questions for auditor:** Obtain the suspension instrument, statutory basis, registry/control evidence and any court review. What changed after yesterday's cutoff? If no operational change, reduce to rapid fire or omit. Do not use a political speech to decide legality.

## Candidate: N09 — G20 ends with a chair's statement rather than a joint settlement

- **Event time/date:** October 31 closing session; primary reproduced statement dated October 31. Reuters/ThePrint final-meeting account published by `20:00Z` October 31.
- **Region / actors:** G20, United States, Russia, European and other delegations.
- **What changed:** The meeting now has a published US chair's statement emphasizing energy, supply chains and maritime routes. Reuters reports no joint statement or agreement. This converts yesterday's predicted split into an observed procedural outcome, not an agreed G20 security settlement.
- **Why this may matter:**
  - A chair can describe an agenda without establishing consensus.
  - Specific bilateral proposals can matter despite failure of the full forum.
- **Initial priority:** medium; tuple `(3,2,3,2,2;1)`, score **23**.
- **Confidence in basic event:** high on the chair's text; medium-high on lack of joint consensus from reporting.
- **Source chain:** State Department text → G20 Information Centre reproduction is primary institutional wording; Reuters reports the meeting outcome. The chair's account is not a negotiated communiqué.
- **Sources:**
  - [Chair's statement](https://www.g20.utoronto.ca/2026/261031-foreign.html), inspected opening and energy sections: what the chair issued and subjects discussed.
  - [Reuters final-meeting account](https://theprint.in/world/us-canada-see-growing-interest-in-limited-ceasefire-in-black-sea/3087311/), inspected lines 104–109: absence of joint statement/agreement. Shared with N03, not an extra reporting lineage.
- **Atomic claims / support and narrowing:** **N09a FACT:** a chair's statement exists. **N09b CLAIM:** no joint agreement, Reuters outcome reporting. **N09c HOLD:** G20 collectively endorsed every US formulation or made binding commitments. Treat the primary text's pronouns and consensus implications cautiously.
- **Questions for auditor:** Retrieve original State Department release and delegation objections. Consolidate with N03/N10 if final space is tight; do not count one meeting as several major breakthroughs. Separate consensus failure from failure of all bilateral diplomacy.

## Candidate: N10 — Quad announces semiconductor / AI supply-chain mapping

- **Event time/date:** Atlanta meeting October 31. State Department reproduction says distributed `2026-10-31 18:51 UTC`; its site-header clock differs, so use explicit UTC footer.
- **Region / actors:** United States, Australia, India, Japan; Indo-Pacific partners.
- **What changed:** A joint release says the Quad will start identifying semiconductor and advanced AI hardware supply-chain chokepoints. It also sets future maritime awareness and humanitarian exercises. These are new workstreams and plans, not delivered supply or a defense guarantee.
- **Why this may matter:**
  - Shared vulnerability mapping can precede export, investment and procurement choices.
  - Implementation indicators will distinguish coordination from summit language.
- **Initial priority:** medium; tuple `(3,1,4,2,2;2)`, score **23**.
- **Confidence in basic event:** high on published commitments; low on future effectiveness.
- **Source chain:** Joint ministerial text released by State Department → unedited Public Technologies reproduction; a primary-origin text, no independent outcome assessment.
- **Sources:**
  - [Joint press release reproduced by Public Technologies](https://www.pubt.io/view/CCA13FDFC9D4684BD11F526EBB96532F67062CAA), inspected technology and logistics paragraphs and provenance footer at lines 268–287.
- **Atomic claims / support and narrowing:** **N10a FACT:** ministers announced a new mapping effort. **N10b HOLD:** identified chokepoints have already been removed or the release constitutes an anti-China defense alliance. **N10c FUTURE WATCH:** maritime symposium early 2027 and exercise participation remain scheduled intentions. The text itself explains its unusual SI terminology; do not silently translate it into a distinct agreed technical standard.
- **Questions for auditor:** Find parallel Japanese/Australian/Indian releases and full original text. Identify budget, output date, responsible agencies, actual projects and measures. If no concrete machinery beyond mapping, rapid fire is enough.

## Candidate: N11 — Yemeni military reports strikes on Aden airport and presidential palace

- **Event time/date:** Reported attacks Friday October 30, precise event time absent; Saudi Gazette publication October 31, 05:31, timezone not stated on page.
- **Region / actors:** Yemen government, Houthis, Aden airport and Maashiq palace.
- **What changed:** Yemen's military spokesman said ballistic missiles targeted both facilities after the airport had reopened following an earlier attack. The fresh target pattern may be significant, but the inspected article relies on the government's account and does not establish impacts or damage independently.
- **Why this may matter:**
  - Attacks on a government center and transport hub can deepen a wider front.
  - Attribution and effect must be checked separately from a launch claim.
- **Initial priority:** medium-high, conditional; tuple `(4,4,2,2,2;3)`, score **28**.
- **Confidence in basic event:** medium that the military made the report; low-medium on physical details.
- **Source chain:** Yemeni military statement → agency text → Saudi Gazette. One claimant lineage; Saudi interest in the war requires explicit attribution.
- **Sources:**
  - [Saudi Gazette inspected article](https://saudigazette.com.sa/article/665870/world/houthis-target-aden-airport-presidential-palace-with-ballistic-missiles), lines 44–50: named spokesman and target claim.
- **Atomic claims / support and narrowing:** **N11a CLAIM:** missiles targeted the palace and airport. **N11b HOLD:** missiles hit both, particular people were targeted, or casualties occurred in the Friday incident. Earlier Wednesday damage/casualties are context and cannot be relabeled Friday's toll.
- **Questions for auditor:** Event timing may precede the window; retrieve the originating statement, independent airport status, geolocated imagery, Houthi position and local reporting. Confirm launch versus interception versus impact. Downgrade if no new in-window effect.

## Candidate: N12 — UN political mission in Somalia reaches its closure date

- **Event time/date:** Operations close October 31; UN News article dated October 31, hour absent.
- **Region / actors:** Somalia, UNTMIS, Somali institutions and UN agencies.
- **What changed:** The UN News account says UNTMIS wraps up on Saturday after its transition. The change is the scheduled closure becoming operative, rather than a newly announced surprise withdrawal. Humanitarian and development agencies remain.
- **Why this may matter:**
  - Political mediation and state-building functions move to different institutions.
  - What succeeds the mission matters more than ceremonial closure.
- **Initial priority:** medium; tuple `(3,2,2,2,2;2)`, score **21**.
- **Confidence in basic event:** high on the UN's closure account; lower on smooth transfer of every function.
- **Source chain:** UN News → Global Issues republication; one official-origin lineage, not independent evaluation of Somali capacity.
- **Sources:**
  - [UN News inspected republication](https://www.globalissues.org/news/2026/10/31/44484), lines 30–57: closure and continued agency presence.
- **Atomic claims / support and narrowing:** **N12a FACT:** UN says political mission closes. **N12b HOLD:** the entire UN or all international security assistance left Somalia. **N12c ASSESSMENT:** national institutions can absorb functions; official optimism is not an independent capacity finding.
- **Questions for auditor:** Retrieve final UNTMIS order and function-transfer matrix; distinguish UNTMIS, UNSOS, UN country agencies and AU security mandates. Was closure completed by cutoff and what unresolved electoral/constitutional support remains? Do not re-present yesterday's announced date as a surprise.

## Candidate: N13 — Sudan accuses Ukraine of assisting RSF and says it filed with the UN

- **Event time/date:** October 31 report of foreign minister remarks in Moscow; exact interview and submission times absent.
- **Region / actors:** Sudanese government, Ukraine, RSF, Russia, UN Security Council.
- **What changed:** Sudan's foreign minister told Sputnik Afrika that Ukrainian personnel train RSF fighters and that Sudan submitted material through its UN representative. The source does not publish the evidence, captured identities, or a UN document number. This is a consequential allegation, not established Ukrainian support for RSF.
- **Why this may matter:**
  - A documented foreign-support channel could change the war's external dimensions.
  - A weak allegation could also be used to attack Western arms accountability.
- **Initial priority:** medium, **HOLD on underlying accusation**; tuple `(3,2,2,3,3;3)`, score **23**.
- **Confidence in basic event:** medium on the reported accusation; low on its truth and submission status.
- **Source chain:** Sudan minister → Russian state outlet Sputnik Afrika → Sudan Tribune. One interested-party allegation chain; Reuters photograph in the article adds no corroboration.
- **Sources:**
  - [Sudan Tribune inspected article](https://sudantribune.com/article/320714), lines 20–27: accusation, asserted captures and purported UN filing.
- **Atomic claims / support and narrowing:** **N13a CLAIM:** minister alleges training. **N13b HOLD:** Ukrainians served RSF, were captured, or diverted US weapons; no evidentiary packet retrieved. **N13c HOLD:** formal UN submission exists; no registry record identified. Lack of a response is not confirmation.
- **Questions for auditor:** Locate Security Council document, Sputnik interview, identities and Ukrainian response. Seek dates, units, geolocation and chain of custody. Consider misidentified foreign personnel or recycled material. Omit unless evidence or a consequential official response warrants inclusion.

## Candidate: N14 — Ghana announces Russian cooperation on a 2,000 MW nuclear project

- **Event time/date:** October 31 announcement; Reuters/MarketScreener first published 15:42 EDT (`19:42Z`), modified 15:45 EDT (`19:45Z`).
- **Region / actors:** Ghana, Russia, Rosatom.
- **What changed:** Ghana's foreign minister says Russia agreed to cooperate on developing a 2,000 MW nuclear plant, with defense and other cooperation also discussed. The account follows Rosatom's statement of talks with African states. No financed construction contract is established.
- **Why this may matter:**
  - Nuclear supply agreements can create long relationships in fuel, skills and finance.
  - Announced capacity is far from operating capacity.
- **Initial priority:** medium; tuple `(3,1,1,3,2;3)`, score **18**.
- **Confidence in basic event:** medium-high on minister's announcement; low on project delivery.
- **Source chain:** Ghana minister's X statement and Rosatom remarks → Reuters → MarketScreener. The two state-linked statements are not independent proof of financing or execution.
- **Sources:**
  - [Reuters inspected republication](https://www.marketscreener.com/news/ghana-says-russia-to-back-2-000-mw-nuclear-plant-deepen-ties-ce785fd8db80f224), article lines 724–747: capacity and source of announcement.
- **Atomic claims / support and narrowing:** **N14a CLAIM:** Russia agreed to cooperate. **N14b HOLD:** a plant has been financed, contracted, licensed or begun construction. **N14c QUANTITY:** 2,000 MW is proposed generating capacity, not generation, delivery or money. Reported bar on Ghanaian recruitment is also a minister-attributed commitment, not compliance evidence.
- **Questions for auditor:** Retrieve statement and signed instruments; identify reactor type, site, ownership, finance, regulator and schedule. Compare prior Ghana nuclear agreements to assess novelty. Rapid fire unless a binding contract or material policy shift emerges.

## Candidate: N15 — UN discloses a staff member's earlier death in Houthi custody

- **Event time/date:** New disclosure October 31; death reportedly more than a month earlier. Reuters publication October 31, 15:37 EDT = `19:37Z`.
- **Region / actors:** Yemen, OHCHR, Houthis, detained aid personnel.
- **What changed:** Reuters reports Volker Türk disclosed the death of OHCHR staff member Mohammad el Shami and called for an independent investigation. His family had only recently been informed. The new fact is disclosure, not a death on October 31.
- **Why this may matter:**
  - Continued staff detention can constrain humanitarian access and UN presence.
  - The unanswered cause of death makes independent records essential.
- **Initial priority:** medium; tuple `(2,2,1,3,2;3)`, score **17**.
- **Confidence in basic event:** high on reported UN disclosure; medium on underlying custody chronology; low on cause.
- **Source chain:** OHCHR statement/family account → Reuters → StreetInsider. One disclosure lineage; a separate condemnation is not independent forensic evidence.
- **Sources:**
  - [Reuters inspected republication](https://new.streetinsider.com/Reuters/UN%2Bsays%2BYemeni%2Bstaff%2Bmember%2Bdies%2Bin%2BHouthi%2Bcustody%2C%2Bdemands%2Binvestigation/27267559.html), lines 174–181: identity, timing, inquiry request and absent Houthi response. Direct OHCHR/UN News openings failed.
- **Atomic claims / support and narrowing:** **N15a FACT:** the UN disclosed the death and sought an inquiry. **N15b CLAIM:** he died in custody after detention since June 6, 2024, attributed to Türk/family. **N15c HOLD:** cause, responsibility mechanism or exact death date; no medical/detention records retrieved. Do not confuse OHCHR with UNHCR based on a mislabeled secondary headline found in discovery.
- **Questions for auditor:** Retrieve the original OHCHR statement and medical/detention records if available; keep cause unknown. Confirm the current detained-personnel total with a dated denominator before using it. Consider folding into Yemen coverage rather than a separate major item.

## Candidate: N16 — Taiwan contests a new Chinese coast-guard patrol east of the island

- **Event time/date:** Patrol and Taiwanese response late October 31 local. Reuters first publication visible on syndications `2026-11-01 01:19Z`; AOL update `01:21Z`, both before cutoff.
- **Region / actors:** Taiwan, China Coast Guard; east-coast shipping, Pratas.
- **What changed:** Reuters reports Taiwan said two Chinese coast-guard ships operated east of the island and it sent ships to monitor. Chinese state footage showed a law-enforcement radio message. Taiwanese claims of harassment and blockade practice remain attributed interpretations, not proof that a blockade began.
- **Why this may matter:**
  - Repeated asserted jurisdiction can pressure shipping without military combat.
  - Radio enforcement, boarding, exclusion and blockade are different observable thresholds.
- **Initial priority:** high; tuple `(4,4,4,3,3;3)`, score **34**.
- **Confidence in basic event:** medium-high on reported patrol/response; low on precise geography, operational effect and intent.
- **Source chain:** Chinese state-media footage and Taiwan Coast Guard statements → Reuters → AOL/Yahoo/StreetInsider. Syndications are one wire lineage; governmental accounts establish positions, not the legality of competing claims.
- **Sources:**
  - [Reuters via AOL](https://www.aol.com/articles/taiwan-says-china-harassing-shipping-011905000.html), full article inspected by read-only PowerShell `Invoke-WebRequest` after the web opener failed. It contains the update timestamp, two-ship account, described radio footage, and Taiwan's response.
- **Atomic claims / support and narrowing:** **N16a CLAIM:** two Chinese ships patrolled and Taiwan monitored. **N16b CLAIM:** radio harassment, attributed to Taiwan; the recipient and fishing vessel identity are unspecified. **N16c ASSESSMENT:** blockade rehearsal, attributed to Taiwanese officials. **N16d HOLD:** merchant traffic was blocked, boarded or diverted; no such evidence retrieved.
- **Questions for auditor:** Retrieve both coast-guard statements, dated footage, hull numbers, coordinates and AIS/merchant accounts. Separate Pratas from east-coast patrol geography. Verify legal claims against jurisdiction and actual locations; do not infer a territorial-sea incursion from an EEZ dispute.

## Candidate: N17 — Global port action is significant but mostly outside this edition's window

- **Event time/date:** Strikes and protests October 30; Reuters first publication October 30, 14:16Z, **before the window**. Reuters Connect partner asset dated October 30, clock absent.
- **Region / actors:** Port unions, shipping operators, military cargo routes across Europe and beyond.
- **What changed:** Discovery surfaced coordinated port actions and large claims of disruption. Chronology checking shows the central report predates this edition. No inspected new post-01:00Z operational effect justifies treating it as today's fresh major development.
- **Why this may matter:**
  - Sustained refusal to handle military cargo could affect logistics if measured.
  - Organizers' projected cargo value is not realized economic loss.
- **Initial priority:** low for this edition; **REJECT as fresh news pending new effect**. Tuple `(3,1,2,0,2;3)`, score **17**.
- **Confidence in basic event:** medium on actions; low on global disruption totals.
- **Source chain:** Latin America News Agency → Reuters Connect. The platform explicitly says Reuters did not produce, verify or endorse this partner asset. Do not call it Reuters reporting or independent verification of organizer totals.
- **Sources:**
  - [Inspected Reuters Connect partner asset](https://www.reutersconnect.com/item/greek-port-workers-join-a-global-protest-across-more-than-100-ports-against-arms-shipments/dGFnOnJldXRlcnMuY29tLDIwMjY6bmV3c21sX09XTFRBQ0FOU1ZNNTBLUzZPOFFFNk9KUzZRRU5ONTA), lines 47–55 and 61–91: Piraeus shotlist, organizer claims, unverified scale and explicit source disclaimer.
  - [Reuters/AOL discovery lead](https://www.aol.com/articles/dockworkers-strike-europe-beyond-against-141621000.html): timestamp indicated older report; not used as inspected evidence here.
- **Atomic claims / support and narrowing:** **N17a CLAIM:** organizers planned action at 113 terminals; participation and duration vary. **N17b HOLD:** more than $2 billion lost or 40% of Mediterranean traffic actually stopped; asset calls these possible impacts and says extent unconfirmed. **N17c FACT:** core event chronology is older context.
- **Questions for auditor:** Only revive if in-window port-authority data, shipping delays or a sustained military-cargo refusal changes the story. Find actual operations, not projected value. Distinguish terminals, ports, countries and unions.

## Candidate: N18 — Rwanda sanctions headline is new coverage of an October 28 action

- **Event time/date:** Operative Treasury announcement `2026-10-28 10:32 EDT` = `14:32Z`, **outside window**; later October 31 coverage prompted discovery.
- **Region / actors:** United States, Rwanda, DRC, M23, Rwandan defense ministry and Zigama.
- **What changed:** Treasury sanctioned Rwanda's defense ministry and Zigama on October 28. No new in-window sanctions act was retrieved. This is a useful chronology exclusion and background for Congo coverage, not a fresh October 31 action.
- **Why this may matter:**
  - The action may pressure Rwanda's state-linked financial channels.
  - Newly published journalism does not reset the policy's event date.
- **Initial priority:** low for this edition; **REJECT as fresh news**. Tuple `(4,2,3,0,2;2)`, score **24** reflects substantive significance but not freshness.
- **Confidence in basic event:** high on Treasury's dated designation announcement; underlying support allegations remain attributed findings.
- **Source chain:** Treasury original bulletin, primary evidence of the act and US rationale. Later coverage repeating Treasury is not independent proof of each conflict allegation.
- **Sources:**
  - [Treasury original bulletin](https://content.govdelivery.com/accounts/USTREAS/bulletins/430c4a3), inspected timestamp and paragraphs describing designated entities and action.
- **Atomic claims / support and narrowing:** **N18a FACT:** Treasury announced designations October 28. **N18b CLAIM:** designated entities support M23, Treasury attribution. **N18c HOLD:** action occurred within this 30-hour window or already changed Rwandan behavior; neither supported.
- **Questions for auditor:** Include only as clearly labeled context for a newly changed Congo development. Retrieve designation notices/legal instruments for legal specifics; do not upgrade allegations or infer compliance effects without new evidence.

# Scout shortlist

1. **N01 — Iran Doha channel:** highest immediate escalation stakes; audit the alleged breakthrough and denied direct participation.
2. **N02 — AP US-base damage analysis:** major new evidence about older events; preserve methodology and current-readiness limits.
3. **N03 — Black Sea proposals:** public US interest plus Canadian contacts; no Russian consent or ceasefire yet.
4. **N16 — Taiwan coast-guard patrol:** new in-window friction near strategic access routes; no demonstrated blockade.
5. **N04 — FBI/Binance:** government attribution is a clear change; company replenishment is a separate accounting claim.
6. **N05 — Oleshky arrivals:** observed completion advances yesterday's departure story; total and voluntariness remain open.
7. **N06 — Russian diesel extension:** retrieve decree and exemptions; supply effects depend on actual volumes.
8. **N07 — Tibi outside-support offer:** a concrete bargaining position, not an agreed government.
9. **N11 — Aden targets:** strategically serious but event time, impact and independent confirmation need work.
10. **N08 — Poland court control:** continued institutional confrontation; include only the fresh increment.
11. **N10 — Quad supply-chain mapping:** practical new workstream, likely rapid fire unless implementation detail emerges.
12. **N12 — Somalia mission closure:** scheduled transition realized; distinguish political mission from continuing UN/AU presence.

N09 can support N03/N10 or become rapid fire; avoid three major entries about the same G20 meeting. N14/N15 are secondary options. N13 is a serious-allegation HOLD. N17/N18 fail freshness absent an in-window development. No regional quota was applied.

## Retrieval and QA handoff

- **High-impact holds:** shared Iran text and original denial context; AP imagery/ledger and repaired-capability status; Black Sea belligerent consent; FBI attribution method and same-time crypto accounting; Russian decree/exemptions; Taiwan primary footage/coordinates; Aden event clock/physical confirmation; Polish operative court order.
- **Access limits:** direct AP and some Reuters/OHCHR pages failed. AP was read at ABC; Reuters at Forth, ThePrint, StreetInsider, MarketScreener and AOL as labeled. The AOL Taiwan article was retrieved directly in PowerShell and read in full. Failed searches and sidebars are not evidence. None of these republications creates an independent second lineage.
- **Count check:** 18 distinct candidate records; 12 shortlist entries. N17/N18 are excluded chronology controls, not filler for the final brief. Every candidate has all News Scout role fields plus atomic claims, narrowing evidence and uncertainty. Scores are triage aids only.
- **Scope check:** no asserted post-cutoff outcome, no fabricated exact quote, no current-event fact sourced to yesterday's brief, no casualty/impact percentage inferred from mismatched denominators. All quantitative claims retain their source population and time basis. Timestamp ambiguities remain visible.
- **Audit status:** discovery complete; source, entailment, primary-record, adversarial and final publication checks remain the auditor's work. The narrative must not outrun the narrower claim records above.
