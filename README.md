# Awesome Reactor [Awesome](https://awesome.re/badge.svg)

> A curated list of nuclear reactor databases, interactive visualizations, simulators, technical software, and monitoring tools. Built for systems engineers, researchers, and anyone exploring the global nuclear fleet.

**Last Updated: 2026-10-04**

[![Databases](https://img.shields.io/badge/Databases-8-blue?style=for-the-badge)](#-official-databases--statistics)
[![Maps](https://img.shields.io/badge/Maps-4-green?style=for-the-badge)](#-interactive-maps--visualizations)
[![Simulators](https://img.shields.io/badge/Simulators-8-orange?style=for-the-badge)](#-simulators--learning-tools)
[![SMR](https://img.shields.io/badge/SMR%20%2F%20Advanced-4-purple?style=for-the-badge)](#-smr--advanced-reactor-trackers)
[![Technical](https://img.shields.io/badge/Technical%20Software-6-red?style=for-the-badge)](#-technical-software--simulation)

---

## Table of Contents

1. [Reactor Type Reference](#1-reactor-type-reference)
2. [Official Databases & Statistics](#2-official-databases--statistics)
3. [Interactive Maps & Visualizations](#3-interactive-maps--visualizations)
4. [SMR & Advanced Reactor Trackers](#4-smr--advanced-reactor-trackers)
5. [Simulators & Learning Tools](#5-simulators--learning-tools)
6. [Technical Software & Simulation](#6-technical-software--simulation)
7. [Monitoring & Instrumentation](#7-monitoring--instrumentation)
8. [Video Documentaries & Lectures](#8-video-documentaries--lectures)
9. [Communities & News](#9-communities--news)

---

## 1. Reactor Type Reference

*The fundamental classification of nuclear reactors by coolant, moderator, and neutron spectrum.*

### Commercial Power Reactor Types

| Type | Full Name | Coolant | Moderator | Fuel | Countries | Notes |
|---|---|---|---|---|---|---|
| **PWR** | Pressurized Water Reactor | Light Water (H₂O) | Light Water | Enriched UO₂ | US, France, Japan, Russia, China, Korea | ~304 reactors. The global standard. Coolant does not boil in the reactor vessel. |
| **BWR** | Boiling Water Reactor | Light Water | Light Water | Enriched UO₂ | US, Japan, Sweden | ~94 reactors. Coolant boils directly in the core, producing steam for the turbine. |
| **PHWR / CANDU** | Pressurized Heavy Water Reactor | Heavy Water (D₂O) | Heavy Water | Natural UO₂ | Canada, India | ~40 reactors. Uses natural uranium, reducing enrichment needs. |
| **AGR** | Advanced Gas-cooled Reactor | CO₂ | Graphite | Enriched UO₂ | UK | ~8 reactors. UK-specific design. |
| **RBMK** | Light Water Graphite Reactor | Light Water | Graphite | Enriched UO₂ | Russia | ~11 reactors. The Chernobyl design. Positive void coefficient. |
| **FBR** | Fast Breeder Reactor | Liquid Sodium (Na) | None | Mixed Oxide (MOX) | Russia, India, Japan, France | ~4 reactors. Uses fast neutrons for breeding. Sodium has high boiling point (~883°C) and high thermal conductivity. |

### Generation IV Reactor Concepts

An international task force is developing six nuclear reactor technologies for deployment between 2020 and 2030. Four are fast neutron reactors.

| System | Full Name | Coolant | Spectrum | Notes |
|---|---|---|---|---|
| **VHTR** | Very High Temperature Reactor | Helium | Thermal | High outlet temp (>900°C). Hydrogen production, process heat. |
| **SFR** | Sodium-cooled Fast Reactor | Liquid Sodium | Fast | The most mature Gen IV concept. High power density. |
| **SCWR** | Supercritical Water-cooled Reactor | Supercritical Water | Thermal/Fast | High thermal efficiency. |
| **GFR** | Gas-cooled Fast Reactor | Helium | Fast | High outlet temp. Closed fuel cycle. |
| **LFR** | Lead-cooled Fast Reactor | Liquid Lead or LBE | Fast | High boiling point. Passive safety features. |
| **MSR** | Molten Salt Reactor | Molten Fluoride/Chloride Salts | Thermal/Fast | Liquid fuel. Thorium fuel cycle. Near atmospheric pressure operation. |

### Molten Salt Reactor (MSR) Deep Dive

Molten salt reactors use molten fluoride salts as primary coolant at low pressure. The MSR is most commonly associated with the ²³³U/thorium fuel cycle. The Molten Salt Breeder Reactor (MSBR) was a Th-U cycle thermal breeder applying continuous chemical processing of fuel in situ.

| Concept | Description | Notes |
|---|---|---|
| **MSBR** | Molten Salt Breeder Reactor | Oak Ridge concept. Th-U cycle. Continuous fuel processing. |
| **LFTR** | Liquid Fluoride Thorium Reactor | Thermal-spectrum breeder. ²³³U/thorium fuel cycle. |
| **FUJI** | Simplified MSR | Designed for closed Th-U fuel cycle. Japan/International. |
| **TMSR-500** | ThorCon MSR | Being designed for the Indonesian market by ThorCon. |

---

## 2. Official Databases & Statistics

*The authoritative sources for global reactor data.*

| Resource | Description | URL | Type | Notes |
|---|---|---|---|---|
| **IAEA PRIS** | Power Reactor Information System — the world's authoritative source on nuclear power reactors since 1969. | [pris.iaea.org](https://pris.iaea.org) | Database | 417 reactors in operation, 62 under construction. Data updated continuously. |
| **IAEA ARIS** | Advanced Reactor Information System — design descriptions of evolutionary and innovative nuclear reactors. | [aris.iaea.org](https://aris.iaea.org) | Database | 126+ designs. Standardized, impartial data on reactor designs. |
| **World Nuclear Association Reactor Database** | Information on nuclear reactors from around the globe. | [world-nuclear.org](https://world-nuclear.org/information-library/nuclear-power-reactors) | Database | Built on IAEA PRIS data + WNA updates. |
| **World Nuclear Association SMR Database** | Comprehensive record of SMR designs at various stages of development. | [world-nuclear.org](https://world-nuclear.org/information-library/nuclear-power-reactors/small-modular-reactors/small-modular-reactor-smr-design-database) | Database | 133+ reactors listed. Search by design, developer, country, technical parameters. |
| **NEA SMR Dashboard** | OECD Nuclear Energy Agency's interactive dashboard. | [oecd-nea.org](https://www.oecd-nea.org/jcms/pl_107879/nea-small-modular-reactor-digital-dashboard) | Dashboard | Tracks 129 SMR designs worldwide, 79 included in the digital dashboard. |
| **NucNet SMR Database** | Small Modular and Advanced Reactor Database. | [smr.nucnet.org](https://smr.nucnet.org) | Database | 112+ results. Distribution by country, size, output, fuel class. |
| **IAEA Research Reactors Database** | Research Reactor Database (RRDB). | [nucleus.iaea.org](https://nucleus.iaea.org) | Database | Global research reactor inventory. |

### IAEA PRIS Statistics (As of 2026-06-30)

| Region | Reactors in Operation | Net Electrical Capacity [MW] |
|---|---|---|
| **Total Worldwide** | **417** | **379,700** |
| United States | 94 | 96,952 |
| France | 57 | 63,000 |
| China | 60 | 58,812 |
| Russia | 34 | 27,969 |
| Korea, Republic of | 26 | 25,609 |
| Canada | 17 | 12,714 |
| Ukraine | 15 | 13,107 |
| India | 23 | 7,730 |

**Suspended Operation:** India (2), Japan (19) — Total 21 reactors, 19,387 MW.

---

## 3. Interactive Maps & Visualizations

*Geospatial tools for exploring the world's nuclear fleet.*

| Resource | Description | URL | Type | Notes |
|---|---|---|---|---|
| **WNISR DataViz** | Interactive data-visualization covering 828 power reactors (1951–2026). | [dv.worldnuclearreport.org](https://dv.worldnuclearreport.org/) | Visualization | Cross-filter by fleet, power ratings, age, construction, status. |
| **Nuclearplanet** | Interactive world map showing all civil nuclear power plants and radioactive waste repositories. | [app.nuclearplanet.ch](https://app.nuclearplanet.ch/nuclearplanet/) | Map | English, French, German. Data from IAEA PRIS. |
| **ReactorMap** | Interactive 3D globe tracking 811+ reactors worldwide. | [reactormap.com](https://reactormap.com) | Map | Built with Three.js and WebGL. Free and open. |
| **World Nuclear Map (NucNet)** | Nuclearplanet integration on NucNet. | [nucnet.org](https://www.nucnet.org/world-nuclear-map) | Map | Search by site name and facility type. |

---

## 4. SMR & Advanced Reactor Trackers

*Focused databases for small modular reactors and next-generation designs.*

| Resource | Description | URL | Type | Notes |
|---|---|---|---|---|
| **NEA SMR Digital Dashboard** | Real-time evidence-based analysis of global SMR development. | [oecd-nea.org](https://www.oecd-nea.org/jcms/pl_107879/nea-small-modular-reactor-digital-dashboard) | Dashboard | 129 designs tracked, 79 included. Edition 3.2 released. |
| **World Nuclear Association SMR Database** | Design database for SMRs at various development stages. | [world-nuclear.org](https://world-nuclear.org/information-library/nuclear-power-reactors/small-modular-reactors/small-modular-reactor-smr-design-database) | Database | 133 reactors. Filters by design, developer, country, fuel, capacity. |
| **World Nuclear Association SMR Global Tracker** | Interactive map of SMR projects under development. | [world-nuclear.org](https://world-nuclear.org/information-library/nuclear-power-reactors/small-modular-reactors/small-modular-reactor-smr-global-tracker) | Map | 70+ projects, 50+ pre-project agreements. |
| **NucNet SMR Database** | Distribution by country, size, electric/thermal output, fuel class. | [smr.nucnet.org](https://smr.nucnet.org) | Database | 112+ results. |
| **IAEA ARIS** | Advanced Reactor Information System — 126+ designs including SMRs and microreactors. | [aris.iaea.org](https://aris.iaea.org) | Database | Standardized design descriptions. |

---

## 5. Simulators & Learning Tools

*Interactive tools for understanding reactor physics and operations.*

| Resource | Description | URL | Type | Notes |
|---|---|---|---|---|
| **Reactor Sim (Djobleezy)** | Browser-based nuclear reactor control room simulator. | [GitHub](https://github.com/Djobleezy/reactor-sim) | Simulator | Neutronics, thermal-hydraulics, control rods, xenon transients. Gamified challenge mode. |
| **RBMK-1000 Simulator** | Interactive, browser-based RBMK-1000 reactor simulation. | [GitHub](https://github.com/natozenbilek/rbmk) | Simulator | Physics behind Chernobyl: positive void coefficient, xenon-135, AZ-5/SCRAM. Four modes. |
| **Dalton Nuclear Simulator** | Educational web-based simulator for reactor operations. | [Manchester](https://research-it.manchester.ac.uk) | Simulator | Modernised. Interactive gameplay for exploring reactor operations. |
| **NuRRES** | Web-based Nuclear Research Reactor Educational Simulator. | [IAEA INIS](https://inis.iaea.org) | Simulator | LabVIEW-based. Interactive GUI. |
| **CANDU Simulator** | Java applet to simulate a CANDU reactor. | [IAEA INIS](https://inis.iaea.org) | Simulator | Directly available on a web page. |
| **TRIGA Simulator** | Digital simulation for education and training in TRIGA-type research reactors. | [IAEA INIS](https://inis.iaea.org) | Simulator | Moodle-based online format. |
| **IAEA HOPS** | Hub for On-line Nuclear Power Plant Part-Task Simulators. | [nucleus.iaea.org](https://nucleus.iaea.org) | Simulator | Requires Nucleus login. Free for Member States. |
| **Singularity Reactor Dashboard** | High-fidelity nuclear reactor simulation and audio-visual synthesis platform. | [Hugging Face](https://huggingface.co) | Simulator | GPU-accelerated canvas for particle effects. |

---

## 6. Technical Software & Simulation

*Engineering-grade software for neutronics, thermal-hydraulics, and safety analysis.*

| Software | Description | Type | Notes |
|---|---|---|---|
| **SAM** | System Analysis Module — plant-level system analysis tool for advanced reactors. | Thermal-hydraulics | Developed at Argonne National Laboratory under DOE-NE NEAMS Program. Modern system thermal-hydraulics code. |
| **OpenPronghorn** | Simulation tool for thermal-hydraulic phenomena in advanced nuclear reactors. | Thermal-hydraulics | Built on MOOSE (Multiphysics Object-Oriented Simulation Environment). Open source. |
| **JUPITER** | Detailed thermal-hydraulics analysis code. | Thermal-hydraulics | JAEA Utility Program for Interdisciplinary Thermal-hydraulics Engineering and Research. Gas-liquid two-phase flow, severe accident conditions. |
| **SCENES** | Extensible integrated thermal–hydraulic system analysis code. | Safety analysis | Advanced reactor safety design and multi-physics coupling analysis. |
| **Nek5000 / NekRS / Cardinal** | Computational fluid dynamics for nuclear applications. | CFD | Part of NEAMS thermal-fluid area. |
| **Sockeye** | Nuclear fuel performance code. | Fuel performance | Part of NEAMS. |
| **MOOSE** | Multiphysics Object-Oriented Simulation Environment. | Framework | Open-source platform for high-performance scientific computing applications. |

---

## 7. Monitoring & Instrumentation

*Systems for reactor core monitoring, radiation detection, and control.*

| Resource | Description | Type | Notes |
|---|---|---|---|
| **Westinghouse BEACON** | Online core monitoring system. | Monitoring | Prominent industry example. |
| **Global Nuclear Fuel ACUMEN** | Online core monitoring system. | Monitoring | — |
| **Framatome POWERTRAX / POWERPLEX** | Online core monitoring systems. | Monitoring | — |
| **Studsvik Scandpower GARDEL** | Online core monitoring system. | Monitoring | — |
| **Mirion Connect** | Instrumentation and control, radiation monitoring, neutron flux monitoring. | Monitoring | Covers ~70% of reactors worldwide. |
| **OpenReactor** | Open-source IEC nuclear fusion reactor control, monitoring, and data logging system. | Monitoring | InfluxDB + Grafana. |

---

## 8. Video Documentaries & Lectures

*Visual resources for understanding reactor engineering and history.*

| Resource | Description | URL | Type | Notes |
|---|---|---|---|---|
| **Inside Nuclear (Heysham 2)** | Access-all-areas documentary into nuclear power generation. | [EDF Energy](https://www.edfenergy.com) | Documentary | 30-minute film. YouTube. |
| **The Nuclear Option (CNA)** | Documentary series exploring next-generation reactors, fusion research, and fuel security. | [CNA Insider YouTube](https://www.youtube.com) | Documentary | Episode 4 features Brian Wirth (UTK). |
| **Molten-Salt Reactor Experiment** | ORNL documentary on the first Molten Salts Thorium reactor. | [Oak Ridge National Laboratory](https://www.youtube.com) | Documentary | 1960s. Exquisite detail. |
| **Microreactors: Looking to the Past to Power the Future** | Idaho National Laboratory documentary-style video. | [YouTube](https://www.youtube.com/watch?v=e9KnqSU64Zc) | Documentary | 16 minutes. |
| **Why Thorium rocks** | Short animated video explaining molten salt reactors. | [YouTube](https://www.youtube.com) | Animation | How MSRs operate, why liquid fuel changes safety fundamentals. |
| **Building PFR** | 1974 film celebrating the commissioning of the Prototype Fast Reactor at Dounreay. | [YouTube](https://www.youtube.com) | Historical | UKAEA. Extensive footage from Risley, Windscale, Dounreay. |
| **Shippingport Atomic Power Station** | Film about the first U.S. commercial nuclear power plant. | [Yale Library](https://search.library.yale.edu) | Historical | Reactor Operation (3:03), Power Station Design (4:28), Nuclear Reactor Design (5:02). |
| **Engineering Test Reactor** | USAF film on the design, construction, operations of the large engineering test reactor in Idaho. | [IAEA Encore](https://libenc-ext.iaea.org) | Historical | USAEC production. |
| **Reactor Safety (CANDU)** | In-depth study of CANDU reactors: safety programme, physical barriers, shutdown systems. | [IAEA Archives](https://archives-catalogue.iaea.org) | Educational | 1982. AVN 0671. |
| **Fukushima Daiichi PCV Investigations** | Inside investigation videos of Unit 2 Primary Containment Vessel. | [JAEA Archive](https://f-archive.jaea.go.jp) | Documentary | Multiple dates (2011–2013). |

---

## 9. Communities & News

*Where to follow nuclear industry developments.*

| Resource | Description | URL |
|---|---|---|
| **NucNet** | Independent nuclear news. | [nucnet.org](https://www.nucnet.org) |
| **World Nuclear News** | Industry news from the World Nuclear Association. | [world-nuclear-news.org](https://www.world-nuclear-news.org) |
| **IAEA News** | Official IAEA updates and publications. | [iaea.org/newscenter](https://www.iaea.org/newscenter) |
| **Nuclear Engineering International** | Serving the nuclear industry since 1956. | [neimagazine.com](https://www.neimagazine.com) |
| **World Nuclear Report** | Annual WNISR report and DataViz. | [worldnuclearreport.org](https://www.worldnuclearreport.org) |

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or PR with:
- Resource name and URL
- One-line description
- Category (Database, Map, Simulator, etc.)
- Why it belongs

