+++
date = '2026-01-26'
draft = false
title = 'Part 2: The Gospel — Automating Structural Destruction'
summary = 'How Habsora generates 100+ building targets daily, transforming Gaza into an algorithmically-designated kill zone'
description = 'Analysis of the Israeli military AI system Habsora (The Gospel), which automates the identification of buildings, homes, and infrastructure for destruction at industrial scale—generating targets faster than the military can bomb them.'
toc = true
series = ['The Algorithmic Kill Chain']
series_order = 2
+++

**The numbers that define automated urbicide:**

| Metric | Value | Source |
|:-------|------:|:-------|
| Manual target generation (pre-AI) | ~50/year | IDF historical baseline |
| Habsora target generation (2021) | 100/day | Former IDF Chief Aviv Kohavi |
| Habsora target generation (post-Oct 7) | 100-250+/day | Intelligence sources |
| Targets struck in first 35 days | ~15,000 | IDF reporting |
| Buildings destroyed across Gaza | 50%+ | UN/satellite analysis |

Before AI, identifying 50 targets took Israeli intelligence analysts a full year. Habsora now generates that volume before lunch.

---

## What Habsora Does

While [Lavender](/research/algorithmic-kill-chain/lavender/) marks individuals for assassination, Habsora marks structures for demolition. The Gospel is the IDF's AI system for automating the identification of buildings, infrastructure, tunnels, and homes deemed "significant" by algorithmic analysis.

Developed by the IDF's Targets Administration Division (established 2019), the system processes surveillance data—drone footage, intercepted communications, cell phone tracking, geospatial intelligence—and outputs coordinates for bombing.

The critical insight: Habsora doesn't merely *find* targets. It algorithmically *constructs* them. The system operates through pattern-matching, comparing new data against characteristics of structures previously designated as "militant-affiliated." A building showing sufficient statistical correlation gets flagged for destruction.

This is probabilistic inference, not causal evidence. As AI researchers consistently warn, such systems recommend targets based on correlations in training data—data gathered through decades of occupation surveillance, framed entirely by Israeli security paradigms. The algorithm inherits the colonial gaze that views Palestinian infrastructure as inherently suspect.

---

## The Target Categories

Habsora generates recommendations across Gaza's entire built environment:

### "Operatives' Homes"

The private residences of individuals suspected of militant affiliation—extended under post-October 7 policies to include junior operatives previously considered off-limits. One source described the practice bluntly: "So they mark the home and bomb the house and kill everyone there."

The system reportedly calculates expected civilian casualties for each target. These calculations feed into "proportionality" decisions made under rules of engagement that were drastically loosened after October 7.

### "Power Targets"

This category reveals the underlying doctrine most clearly. "Power targets" include:

- High-rise apartment buildings
- Residential towers
- Universities
- Banks
- Government ministry buildings
- Mosques

Intelligence sources explicitly state the purpose: not immediate military advantage, but to inflict harm on Palestinian civil society, create "shock," and exert "civil pressure" on Hamas. This is the [Dahiya Doctrine](https://en.wikipedia.org/wiki/Dahiya_doctrine) encoded into software—disproportionate force against civilian infrastructure as deliberate strategy.

The bombing of the Babel Building, Al-Taj tower, Al-Mohandseen tower, and the Islamic University of Gaza all fall within this category.

### Tactical and Underground Targets

Alleged command posts, weapons storage, rocket launch sites, and tunnel infrastructure. These categories are presented as legitimate military objectives, though the speed of Habsora's generation and the minimal review process raise serious questions about verification.

---

## The Integration: How Lavender and Habsora Work Together

The systems don't operate in isolation. They create a synergistic kill chain:

1. **Habsora** identifies a residential building as a potential target based on algorithmic analysis
2. **Lavender** flags an individual on its kill list as present in that building
3. **"Where's Daddy?"** tracks the individual until they return home—preferably at night, when family is gathered
4. The home becomes the strike coordinates

This convergence transforms Palestinian homes from potential sanctuaries into preferred kill zones. The operational logic appears calibrated not merely to eliminate the targeted individual, but to do so when and where family casualties are maximized.

The integration is deliberate. The systems were designed to work together. The "Where's Daddy?" nickname—chosen by IDF personnel—indicates awareness of what the system does: it waits for fathers to come home to their children before triggering the strike.

---

## The Velocity Problem

Former IDF Chief of Staff Aviv Kohavi publicly celebrated the transformation: where analysts once identified 50 targets across an entire year, Habsora generates 100 per day.

**What this velocity enables:**

- First 35 days post-October 7: approximately 15,000 targets struck
- Comparison: 51-day 2014 assault struck 5,263 targets total
- The system produces recommendations faster than the Air Force can act on them

Target scarcity is no longer a limiting factor. The pipeline is infinite.

**What this velocity destroys:**

The sheer volume creates "infobesity"—one source estimated that "tens of thousands of intelligence officers could not process" the data feeding the system. Human review becomes mathematically impossible at meaningful depth.

This is not a bug. Speed itself is weaponized. The acceleration of the targeting cycle inherently degrades the conditions necessary for careful deliberation, thorough vetting, and implementation of legal precautions. When you generate targets faster than humans can think about them, you've designed a system where thinking is structurally excluded.

---

## The "Human in the Loop" Fiction

The IDF maintains that human oversight remains central—analysts review, commanders approve, international law is followed.

The testimonies say otherwise:

> "The emphasis is on quantity and not on quality."

> "No time to delve deep into the target."

Sources describe human review as a "rubber stamp" on machine recommendations. The operational tempo since October 7 leaves no time for independent verification. For Lavender targets, review reportedly consists of confirming the target's gender—a process taking approximately 20 seconds. For Habsora's structural targets, the pressure is similar: approve the queue, maintain the tempo.

This is automation bias at institutional scale. When operators face an overwhelming queue of machine-generated recommendations under intense time pressure, they're incentivized to trust the algorithm rather than engage in time-consuming critical assessment.

The "human in the loop" becomes a legal fig leaf—a way to claim compliance while the system's design ensures meaningful judgment is impossible.

---

## What 50% Destruction Looks Like

Over half of all buildings in Gaza have been destroyed. The sites include:

- Hospitals
- Schools
- Mosques
- Bakeries
- Water treatment facilities
- Refugee camps
- UN facilities

While attributing each individual strike to Habsora is impossible given operational secrecy, the system's capacity for generating targets at industrial scale is undeniably what *enables* this destruction. No human analytical process could identify structures for demolition at the rate required to level a city.

Achille Mbembe's concept of "necropolitics" applies precisely: sovereign power asserting itself by creating "death-worlds"—environments rendered fundamentally unlivable. The transformation of Gaza into vast expanses of rubble is not collateral damage but active political strategy.

Habsora automates urbicide.

---

## Legal Analysis: The Three Violations

### Distinction

International humanitarian law requires distinguishing between civilian objects and military objectives. The explicit targeting of "power targets" to create "civil pressure" directly violates this principle—it involves intentional destruction of civilian objects for psychological or political effect, not military advantage.

The mass targeting of homes based on tenuous algorithmic connections stretches "military objective" beyond credible limits.

### Proportionality

IHL prohibits attacks expected to cause civilian harm excessive to the anticipated military advantage. The evidence suggests systematic violation:

- The system calculates expected civilian casualties
- Post-October 7 rules permit strikes anticipated to kill dozens or hundreds of civilians to eliminate single targets (sometimes junior operatives)
- The scale of civilian death demonstrates that anticipated military gains routinely "outweigh" devastating, foreseeable harm

This is not risk tolerance. This is policy.

### Precautions

Parties must take feasible precautions to minimize civilian harm. Habsora's operational tempo directly undermines this obligation:

- Rapid target generation leaves insufficient time for verifying civilian absence
- Reports indicate residential buildings struck without prior warning
- The system's velocity is structurally incompatible with meaningful precautionary measures

---

## The Accountability Void

When destruction is mediated through opaque algorithms, rapid queues, and perfunctory review, who bears responsibility for unlawful strikes?

The algorithm's designers? The commanders who approve policies? The operators who rubber-stamp recommendations? The political leadership that deployed the system?

Habsora's architecture distributes responsibility across so many nodes that no single point becomes accountable. This diffusion is not incidental—it's a feature that enables the commission of potential atrocity crimes while providing plausible deniability at every level.

---

## The Broader Framework

Habsora cannot be understood solely through international humanitarian law. It functions within structures of:

**Settler Colonialism:** Mass destruction of homes (domicide) and urban landscapes (urbicide) directly facilitates displacement of indigenous population and seizure of land.

**Apartheid:** The system is part of a technologically advanced apparatus of surveillance, control, and violence deployed overwhelmingly against one racialized group—reinforcing segregation, domination, and differential rights.

**Potential Genocide:** Given inflammatory rhetoric from Israeli officials, the catastrophic civilian death toll, and systematic destruction of infrastructure essential for sustaining life, Habsora's role in facilitating these outcomes is deeply concerning. The system enables what the Genocide Convention prohibits: "deliberately inflicting on the group conditions of life calculated to bring about its physical destruction."

AI in this context is not a neutral force multiplier. It accelerates and scales state violence, making the commission of potential atrocity crimes technologically feasible and bureaucratically streamlined.

---

## Challenging the Official Narrative

The IDF emphasizes precision, adherence to international law, robust human control, minimization of civilian harm.

The evidence reveals: mass target generation, loosened casualty constraints, perfunctory review, and deliberate targeting of civilian infrastructure for "civil pressure."

Attempts to downplay AI's role—characterizing systems as mere "databases" or claiming AI *improves* accuracy—appear as strategic efforts to maintain plausible deniability. The deliberate opacity surrounding Habsora's algorithms, data inputs, and operational parameters serves a clear purpose: hinder independent scrutiny and deflect accountability while leveraging the perception of technological sophistication.

---

## Sources and Evidence Assessment

This analysis draws primarily on:

- **+972 Magazine and Local Call investigations** based on interviews with current and former Israeli intelligence personnel
- **The Guardian's** independent corroboration of AI targeting systems
- **Public statements by IDF leadership**, including former Chief of Staff Aviv Kohavi's explicit acknowledgment of AI-driven target generation rates
- **Palestinian testimonies** documenting the scale of home and infrastructure destruction
- **Human Rights Watch, Amnesty International, and Access Now** documentation and analysis
- **UN reporting** on destruction levels and potential IHL violations

The insider accounts are weighted heavily because they provide operational detail unavailable through official channels. Their consistency across multiple sources, corroboration by observable destruction patterns, and alignment with public official statements (like Kohavi's) support their credibility.

Official IDF denials are noted but assessed skeptically given the documented gap between public claims and insider testimony.

---

## What Comes Next

Habsora marks structures. [Lavender](/research/algorithmic-kill-chain/lavender/) marks people. The next section examines how ["Where's Daddy?"](/research/algorithmic-kill-chain/wheres-daddy/) tracks individuals to their homes for precisely-timed strikes designed to maximize family casualties.

---

**[← Back to Series Index](/research/algorithmic-kill-chain/)**

---

*This investigation is part of [The Algorithmic Kill Chain](/research/algorithmic-kill-chain/) series documenting AI-enabled targeting systems. For questions or additional documentation, contact joshuaphilipdunlap@gmail.com.*