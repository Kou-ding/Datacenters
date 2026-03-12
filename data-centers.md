---
marp: true
size: 16:9
paginate: true
theme: rose-pine
footer: Post AI Era Datacenters Deepdive
style: |
    .fa-twitter { color: aqua; }
    .fa-mastodon { color: purple; }
    .fa-linkedin { color: blue; }
    .fa-window-maximize { color: skyblue; }
    .columns {
        display: grid;
        grid-template-columns: repeat(2, minmax(0, 1fr));
        gap: 1rem;
    }
    @import 'https://use.fontawesome.com/releases/v7.2.0/css/all.css';
---

![bg opacity:10%](media/ai-data-center.jpg)

# <center> Post AI Era Datacenters Deepdive </center>

Papadakis Konstantinos Fotios
AEM: 10371

---

## Contents <i class="fa-solid fa-list"></i>

1. [Status quo](#status-quo)
2. [Datacenters Pillars](#new-datacenters)
3. [Energy Requirements](#energy-requirements)
4. [Network topology](#network--topology)
5. [Environmental Impact](#environmental-impact)
7. [Health](#health-effects)
8. [Finance](#finance)
9. [Sociopolitical Aspect](#sociopolitical--aspect)

![bg w:400 right:50%](media/stack-of-books.png)

---

# Status Quo <i class="fa-solid fa-bomb"></i>

What's the driving force of datacenter construction and expansions?

---

## Artificial Intelligence <i class="fa-brands fa-openai"></i>

- There always were Datacenters
- Many ambitious datacenter projects
- Focus on new facilities and expansions post AI era
- Push towards AGI
- Technology replacing humans in most fields
- note-to-self: why does the AI crisis seem to be different than technology not creating that many new jobs?

![bg w:350 right:35%](media/AI-stock-img.png)

---

# New Datacenters <i class="fa-solid fa-server"></i>

The datacenters that are responsible for running and training the worlds most advanced LLMs.

---

## Map

![bg right:70% w:850](media/datacenter-map.jpg)

Most Activity

|<i class="fa-solid fa-ranking-star"></i>  | State |
|-|-|
| 1 |Virginia |
| 2 |Texas |
| 3 |California |
| 4 |Illinois |
| 5 |Ohio |

---

## LLM Facilities <i class="fa-solid fa-industry"></i>

| Datacenter | Location | Company | LLM |
| ---------- | -------- | ------- | --- |
| Canton Facility | Mississipi | Amazon | - |
| Monterey Park Data Center | California | California | - |
| Stargate Project | Saline Township, Michigan | OpenAI, Oracle | - |
| Colossus | Memphis | xAI | |

---


## <center> Stargate </center> 


![bg left:65%](media/stargate.jpg)


---

## Specifications <i class="fa-solid fa-file-pen"></i>

<div class="columns">
<!-- Column 1 -->
<div>

| Specs      | Value          |
|------------|----------------|
| Investment | $500 billion   |
| Location   | Abilene, Texas |
| Company    | OpenAI & Oracle|
| IT Capacity | 4.5 GW |

based on <sup>[10][10]</sup>

</div>

<!-- Column 2 -->
<div>

5 new sites
- Shackelford County, Texas
- Milam County, Texas
- Doña Ana County, New Mexico
- Lordstown, Ohio
- a mystery site located somewhere in America's Midwest.

End goal being 10GW of combined capacity.

</div>
</div>

---

## Chips

- Nvidia GB200 racks

---

## Monterey Park Datacenter

![bg left:60%](media/monterey_park_datacenter_project_site.png)

---

## Specifications <i class="fa-solid fa-file-pen"></i>

<div class="columns">
<!-- Column 1 -->
<div>

| Specs      | Value          |
|------------|----------------|
| Investment |  |
| Location   |  |
| Company    |  |
| IT Capacity |  |


</div>

<!-- Column 2 -->
<div>



</div>
</div>

---

## Canton Amazon

![bg left:70%](media/canton-amazon-facility-ai-upscale.jpeg)

---

## Specifications <i class="fa-solid fa-file-pen"></i>

<div class="columns">
<!-- Column 1 -->
<div>

| Specs      | Value          |
|------------|----------------|
| Investment | $10 billion   |
| Location   | Canton, Mississipi |
| Company    | Amazon |
| IT Capacity |  |

---

## Colossus

![bg h:800 left:70%](media/xAI-Colossus-ai-upscale.jpeg)

---

## Specifications <i class="fa-solid fa-file-pen"></i>

<div class="columns">
<!-- Column 1 -->
<div>

| Specs      | Value          |
|------------|----------------|
| Investment |   |
| Location   |  |
| Company    | xAI |
| IT Capacity |  |

---

# Energy Requirements <i class="fa-solid fa-bolt"></i>

Ways to fullfil the insatiable hunger of datacenters for electricity.

---

## Energy source candidates 

City main line isn't enough.

Use of backup turbines
- Diesel
- Gas 
- Methane

---

## Diesel Engine Turbines <i class="fa-solid fa-gas-pump"></i>


Monterey Park Data Center , Canton Mississippi 

---

## Methane Gas Turbines <i class="fa-solid fa-gas-pump"></i>

<div class="columns">
<div>

- Output
- 

</div>
<div>

Elon Musk's xAI data center Methane gas turbines, Colossus. <sup>[24][24]</sup>
7 Titan-350 <sup>[22][22]</sup>
12 SMT-130 <sup>[23][23]</sup>

XAI Colossus 2’s is targeting ~1 Gigawatt as soon as possible. They have natural gas turbines for primary generation, batteries for stability, and grid for long-term scalability.

XAI Colossus 2 has power from seven installed SMT-360/Titan-350 Natural Gas Turbines. The seven turbines in question are deployed at the Southaven, Mississippi site 6 miles from Colossus 2’s core Memphis facility and were acquired in late July/early August 2025. SemiAnalysis and Patel report the Titan-350 models from Solar Turbines (a Caterpillar subsidiary) were chosen for their mobile, high-efficiency design (up to 40% thermal efficiency) and rapid deployment (weeks vs. months for grid upgrades). Each Titan-350 can generate 35-38 Megawatts of power.

This power Colossus 2 via medium-voltage (MV) interconnect lines, providing primary baseload power for ~110,000 NVIDIA GB200 NVL72 GPUs (targeting 1.1 PFlops FP8 compute).

xAI’s joint venture (JV) with Solaris Energy Infrastructure (50.1% Solaris, 49.9% xAI) has already deployed $112 million in Q2 2025 CapEx for turbines, with Q4 2025-Q1 2026 ramping to enable over 1.1 GW total by Q2 2027 (and options for 1.5+ GW). This is fueled by temporary permitting loopholes (e.g., 12-month approvals without full environmental review) and land acquisitions like the former Duke Energy plant in Southaven.

The mobile turbines can reach 1.1 gigawatts with about 30+ Titan-350 turbines.

Grid Power (Substation) for 300 MW in 45-90 days

There is current minimal power (~0.5 MW initial from Memphis Light, Gas & Water/MLGW), as turbines handle 90%+ load. No full tie-in yet due to TVA delays.

A second dedicated substation (150-300 MW) is under construction and is directly funded by xAI ($50M+ upfront).

They target getting it online by October 2025, relegating turbines to peaker/backup.

The status is the foundations are complete and energization is imminent (60-90 days from September permits). Patel notes xAI’s direct funding (paying TVA $50M+) model accelerates this 2-3x faster than hyperscalers like Meta.

Dylan Patel, SemiAnalysis warns of over $10 Billion of capital spending is needed total CapEx.

Tesla Megapacks will provide power backup and resilience for outages, demand-response, and turbine ramping. they can provide 4 hours of power. They are planing to deploy 200 megapack for about 1 gigawatt hour of buffering.

There is ~150-200 MWh of megapacks deployed at Colossus 2. They will have more batteries than Colossus 1’s 156 units/ ~600 MWh and connecting via MV (medium voltage) lines to Southaven.

Tesla megapack revenue for Colossus 1 and Colossus 2 could combine to hit $500 million.

Musk envisions solar and battery at 100 GW-1 TW scale but near-term it is Megapacks and gas turbines as a bridge. 

![w:600](media/gas-turbines-grok.jpg)

</div>
</div>

---

## Sustainable Pledges <i class="fa-solid fa-solar-panel"></i>

---

# Network $\quad$ topology <i class="fa-solid fa-network-wired"></i>

Network topology optimization

---

How are the cables routed 

---

# Environmental Impact <i class="fa-solid fa-leaf"></i>

- diesel generators spike local NOx levels

---

## Water Shortage <i class="fa-solid fa-droplet"></i>

---

## Energy sources and emissions <i class="fa-solid fa-smog"></i>

Electricity-generating turbines were exempt from requirements for air quality permits. <sup>[14][14]</sup>

loophole allowing the operation of generators without permits so long as the machines did not sit in one place for more than 364

xAI eventually received permits for 15 turbines at Colossus 1 and is now operating 12 permitted machines at the site.

- Net annual nitrogen oxide emission reductions of up to 296 tons by 2032,” <sup>[4][4]</sup>

---

# Health Effects <i class="fa-solid fa-heart-pulse"></i>

---

## Canton

Residents reported:
- lung irritation, 
- breathing difficulties, and 
- construction dust that settled over homes and playgrounds. 
- Cooling towers pull millions of gallons of water daily from the already-stressed Big Black River system, 
- while weekly tests of backup diesel generators spike local NOx levels and worsen the area’s elevated childhood asthma rates. <sup>[6][6]</sup>

---

## Infrasound <i class="fa-solid fa-wave-square"></i>

<div class="columns">
<!-- Column 1 -->
<div>

- Sound below <sup>[1][1]</sup>

</div>
<!-- Column 2 -->
<div>

### Known Health Effects <sup>[13][13]</sup>

- Spike in cortisol levels (stress, hyppertension) <sup>[14][14],</sup> <sup>[15][15]</sup>
- Nausea, Dizziness<sup>[12][12]</sup>
- Vibroacoustic disease <sup>[16][16]</sup>
- High frequency hearing loss <sup>[17][17]</sup>
- Shortness of breath <sup>[18][18]</sup>
- Anxiety, Depression <sup>[19][19]</sup>

</div>

---

## Sustained audible noise pollution <i class="fa-solid fa-ear-listen"></i>

---

## Methane gas

- Methane gas turbines pump harmful nitrogen oxides into the air, which are known to cause:
    - cancer, 
    - asthma and 
    - other upper respiratory diseases.<sup>[4][4]</sup>


---

# Finance <i class="fa-solid fa-money-bill"></i>

---

- Monopolizing goods for consumers leading to cost skyrocketting
    - Ram & Hard disk prices
- shift towards subscription based models and away from owning based logic


---

# Sociopolitical $\quad$ Aspect <i class="fa-solid fa-scale-balanced"></i>

---

## Job Creation <i class="fa-solid fa-briefcase"></i>

- Stargate
- **100,000–200,000** construction and operations jobs <sup>[9][9]</sup>
- **~25,000** onsite jobs <sup>[11][11]</sup>
- But large automated data centers often need *only dozens* of permanent staff once built. 
- Abilene’s first facility may only employ **~57** ongoing workers, despite promises of thousands <sup>[12][12]</sup>

---

## Strategic Placement <i class="fa-solid fa-republican"></i>

- On democrat states
- Low backlash from the community
-   

---

## Worries about ownership

- Shift towards cloud computing
- Subscription based models
- 


<!-- ################# Sources ################# -->

[1]: https://youtu.be/_bP80DEAbuo "Datacenters Behaving Like Acoustic Weapons - Benn Jordan 2026"

[2]: https://sustainabilitydialogue.uchicago.edu/news/data-centers-pollution-and-the-communities-left-behind/ "Data Centers, Pollution, and the Communities Left Behind - The University of Chicago"

[3]: https://doi.org/10.1016/j.rser.2015.12.283 "Optimizing energy consumption for data centers"

[4]: https://www.theguardian.com/technology/2026/jan/15/elon-musk-xai-datacenter-memphis "Elon Musk’s xAI datacenter generating extra electricity illegally, regulator rules - TheGuardian"

[5]: https://sustainabilitydialogue.uchicago.edu/news/data-centers-pollution-and-the-communities-left-behind/ "Data Centers, Pollution, and the Communities Left Behind"

[6]: https://www.mississippifreepress.org/amazons-canton-data-center-promises-prosperity-for-neighbors-its-bringing-dust-noise-and-pollution-fears/ "Amazon’s Canton Data Center Promises Prosperity. For Neighbors, It’s Bringing Dust, Noise and Pollution Fears."

[7]: https://www.theguardian.com/us-news/2026/feb/07/california-monterey-park-stop-datacenter-construction "Rage against the machine: a California community rallied against a datacenter and won - TheGuardian"

[8]: https://www.theguardian.com/us-news/2025/dec/18/michigan-data-center-fight "‘Uniquely evil’: Michigan residents fight against huge datacenter backed by top tycoons - TheGuardian"

[9]: https://intuitionlabs.ai/articles/openai-stargate-datacenter-details "OpenAI’s Stargate Project: A Guide to the AI Infrastructure - Intuition Labs"

[10]: https://www.blackridgeresearch.com/blog/upcoming-largest-data-center-projects-in-united-states-usa "Blackridge Research - K.Vaishnavi Srivalli"

[11]: https://www.theregister.com/2025/09/24/openai_oracle_softbank_datacenters/#:~:text=While%20OpenAI%20claims%20the%20new,%C2%AE "OpenAI's Stargate project to pave the world with AI datacenters announces five new US locations - The Register"

[12]: https://www.cnbc.com/2025/02/06/openai-looking-at-16-states-for-data-center-campuses-tied-to-stargate.html#:~:text=The%20company%20also%20said%20it,jobs%2C%20according%20to%20recent%20reports "OpenAI considering 16 states for data center campuses as part of Trump’s Stargate project - CNBC"

[13]: https://doi.org/10.3390/ijerph20053916 "Low-Frequency Noise: Experiences from a Low-Frequency Noise Perceiving Population - PubMed"

[14]: https://doi.org/10.1016/j.neuroscience.2010.02.060 "Involvement of microglial cells in infrasonic noise-induced stress via upregulated expression of corticotrophin releasing hormone type 1 receptor - PubMed"

[15]: https://doi.org/10.1016/s0024-3205(01)01450-3 "Low frequency noise enhances cortisol among noise sensitive subjects during work performance - Science Direct" 

[16]: https://doi.org/10.1016/j.pbiomolbio.2006.07.011 "Vibroacoustic disease: Biological effects of infrasound and low-frequency noise explained by mechanotransduction cellular signalling - Science Direct"

[17]: https://doi.org/10.1016/j.heares.2007.01.016 "Effect of infrasound on cochlear damage from exposure to a 4-kHz octave band of noise - NIH"

[18]: https://pubmed.ncbi.nlm.nih.gov/15703146/ "Effects of low frequency noise on man, a case study - NIH"

[19]: https://doi.org/10.1038/s41598-021-82203-6 "A longitudinal, randomized experimental pilot study to investigate the effects of airborne infrasound on human mental health, cognition, and brain structure - NIH"

[20]: https://openai.com/index/five-new-stargate-sites/ "OpenAI, Oracle, and SoftBank expand Stargate with five new AI data center sites - OpenAI"

[21]: https://openai.com/index/stargate-advances-with-partnership-with-oracle/ "Stargate advances with 4.5 GW partnership with Oracle - OpenAI"

[22]: https://s7d2.scene7.com/is/content/Caterpillar/CM20220318-18bf4-966d4 "Titan 350, Gas Turbine Compressor Set - Solar Turbines"

[23]: https://s7d2.scene7.com/is/content/Caterpillar/CM20201215-9943b-379e0 "SMT130, SOLAR MOBILE TURBOMACHINERY, Solar Turbines"

[24]: https://www.nextbigfuture.com/2025/09/xai-colossus-2-first-gigawatt-ai-data-center.html "XAI Colossus 2 First Gigawatt AI Data Center - nextBIGFUTURE"

[25]: https://www.sgvtribune.com/2025/12/04/monterey-park-pauses-vote-on-massive-proposed-data-center-as-questions-linger-over-impact/ "Monterey Park pauses vote on massive proposed data center, as questions linger over impact - San Gabriel Valley Tribune"