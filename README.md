# GVSU Civic Engagement Ecosystem Map & Inventory
**Project Type:** Public Affairs & Institutional Research Audit Prototype  
**Audience:** Division of Public Affairs and Communication, Grand Valley State University  
**Live Interactive Map:** [View Interactive Kumu Relationship Map][(https://kumu.io/<your-kumu-username>/gvsu-community-engagement-map](https://embed.kumu.io/a825dc713b5dc4e46f33ac83c12b7275))

---

## 📌 Executive Summary
This research prototype establishes a baseline current-state inventory and interactive stakeholder map of Grand Valley State University’s publicized external civic partnerships across the Grand Rapids and Allendale ecosystems. Built to mirror the core methodology of the **GVSU University-Wide Community Engagement Audit**, the project standardizes disparate institutional records into a relational entity database, analyzes network clustering, and identifies cross-departmental coordination patterns.

![GVSU Community Engagement Network Map](GVSU-Civic-Engagement-Map.pdf)

---

## 🎯 Key Audit Findings
- **High Operational Clustering:** Strong concentration of high-intensity partnerships situated along the Medical Mile (Kirkhof College of Nursing $\leftrightarrow$ Corewell Health, Trinity Health, Mary Free Bed) and downtown Grand Rapids (Seidman College $\leftrightarrow$ Regional Economic Development).
- **Cross-Departmental Overlaps:** Multiple academic units maintain concurrent, uncoordinated touchpoints with high-density regional partners (e.g., both the Padnos College of Engineering and Seidman College engaging *The Right Place*; Education and Enrollment units engaging *Grand Rapids Public Schools*), demonstrating the strategic need for a centralized community engagement inventory.
- **Geographic Opportunity Gaps:** High density in the Grand Rapids metropolitan core relative to fewer cataloged institutional touchpoints across rural Ottawa County municipal jurisdictions.

---

## 🛠️ Data Architecture & Methodology
- **Data Model:** Relational two-tier graph structure composed of **32 Elements** (7 Central GVSU Academic Units + 25 Regional Community Partners) and **26 Connections**.
- **Taxonomy:** Community partners categorized across 6 primary sectors: *Healthcare*, *K-12 Education*, *Municipal & Civic*, *Economic Development*, *Tech & Innovation*, and *Non-Profit*.
- **Intensity Tiers:** Connections weighted by formal engagement depth:
  - **High:** Contractual, accredited clinical/residency placements, formal host programs.
  - **Medium:** Applied field research, grant partnerships, advisory boards.
  - **Low:** Student volunteer projects, annual service activities.

---

## 📂 Repository Contents
- `gvsu_elements.csv` — Entity catalog containing entity labels, types, sectors, campus anchors, and descriptions.
- `gvsu_connections.csv` — Edge mapping file linking GVSU colleges to external partners with relationship classifications and intensity weights.
- `GVSU-Civic-Engagement-Map.pdf` — High-resolution network graph render.
