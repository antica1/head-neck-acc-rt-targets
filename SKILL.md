---
name: adenoid-cystic-carcinoma-rt-targets
description: "Postoperative radiotherapy target volume delineation for adenoid cystic carcinoma of the head and neck, emphasizing sensory nerve pathway coverage and individualized neck node irradiation strategies."
version: 1.0.0
author: Zhu Guopei / Shanghai Ninth People's Hospital
license: MIT
---

# 头颈部腺样囊性癌术后放疗靶区勾画指南

## Overview

Adenoid cystic carcinoma (ACC) of the head and neck is a rare salivary gland malignancy characterized by slow growth, high rates of perineural invasion, and low rates of lymphatic metastasis. Standard postoperative radiotherapy principles derived from squamous cell carcinoma do not adequately address ACC's unique biological behavior. 

This guide is based on clinical experience at Shanghai Ninth People's Hospital and published work in *Radiotherapy & Oncology* and *Chinese Journal of Radiation Oncology*, combined with general consensus guidelines (ICRU 83/91, QUANTEC, RTOG/EORTC contouring atlases).

## Core Principle: ACC Postoperative RT is NOT SCC PORT

| Feature | Squamous Cell Carcinoma | Adenoid Cystic Carcinoma |
|---------|------------------------|-------------------------|
| Growth rate | Rapid | Slow, indolent |
| Perineural invasion (PNI) | 5-20% | **40-60%** (hallmark feature) |
| Preferred nerve route | Mixed motor/sensory | **Strongly favors SENSORY nerves** (trigeminal branches) over motor nerves |
| Lymphatic metastasis | Common (15-40%) | **Uncommon (5-15%)** |
| Hematogenous metastasis | Late | Late (lung, bone, liver) |
| Surgical margins | Negative margins critical | **"Skip lesions" along nerves make clear margins unreliable** |
| Radiation sensitivity | Moderate | Moderate-high |

---

## Section 1 — Neural Pathway Coverage: The Ninth Hospital Approach

### 1.1 The Sensory Nerve Principle

ACC demonstrates a strong predilection for **sensory nerves** (particularly branches of the trigeminal nerve, CN V) rather than **motor nerves** (such as the facial nerve, CN VII). This is a critical departure from the conventional assumption that ACC follows "any nerve."

**Clinical example — Parotid gland ACC:**

| Nerve | Branch of | Likelihood of ACC involvement |
|-------|-----------|------------------------------|
| Auriculotemporal nerve | CN V3 (sensory) | **High** |
| Lingual nerve | CN V3 (sensory) | **High** |
| Inferior alveolar nerve | CN V3 (sensory) | **High** |
| Facial nerve (CN VII) | Motor | **Low** (despite passing through the parotid) |

This means the target volume for a parotid ACC should follow the **trigeminal nerve pathway to the skull base**, NOT the facial nerve pathway through the temporal bone.

### 1.2 The Three-Tier System for Neural Pathway Coverage

Based on postoperative pathology, ACC falls into one of three tiers dictating how aggressively the neural pathway should be irradiated:

```
┌─────────────────────────────────────────────────────┐
│   Post-op Pathology                  RT Coverage    │
├─────────────────────────────────────────────────────┤
│                                                     │
│  TIER 1: NAMED NERVE INVASION                       │
│  ┌─────────────────────────────────────────────┐   │
│  │ Pathology explicitly names an involved      │   │
│  │ nerve (e.g. "inferior alveolar nerve",     │   │
│  │ "lingual nerve", "V3 branch")              │   │
│  └─────────────────────────────────────────────┘   │
│                                                     │
│  → Cover the ENTIRE ipsilateral                    │
│    CAVERNOUS SINUS                                  │
│    (to the Meckel's cave level)                     │
│    60 Gy / 30 fx                                    │
│                                                     │
├─────────────────────────────────────────────────────┤
│                                                     │
│  TIER 2: SMALL/TERMINAL NERVE INVASION ONLY         │
│  ┌─────────────────────────────────────────────┐   │
│  │ Pathology mentions "perineural invasion",   │   │
│  │ "nerve twig involvement", or "small nerve   │   │
│  │ branch involvement" WITHOUT naming a        │   │
│  │ specific major nerve                        │   │
│  └─────────────────────────────────────────────┘   │
│                                                     │
│  → Cover to the INFERIOR BORDER of the             │
│    IPSILATERAL CAVERNOUS SINUS                     │
│    54-56 Gy / 30 fx                                 │
│                                                     │
├─────────────────────────────────────────────────────┤
│                                                     │
│  TIER 3: NO NEURAL INVASION                         │
│  ┌─────────────────────────────────────────────┐   │
│  │ No PNI detected on pathology                │   │
│  └─────────────────────────────────────────────┘   │
│                                                     │
│  → Prophylactic coverage to the SKULL BASE          │
│    following the trigeminal nerve pathway           │
│    50-54 Gy / 30 fx                                 │
│                                                     │
└─────────────────────────────────────────────────────┘
```

### 1.3 Anatomical Implementation: The Trigeminal Nerve Pathway

The CTV should follow the course of the relevant trigeminal branches from the primary site to the target level (cavernous sinus / skull base). Key anatomical reference points:

| Segment | Anatomical Landmarks to Cover |
|---------|------------------------------|
| **Primary site → Infratemporal fossa** | Pterygopalatine fossa, foramen rotundum (V2), foramen ovale (V3) |
| **Skull base foramina** | Foramen ovale (V3), foramen rotundum (V2), superior orbital fissure (V1) |
| **Cavernous sinus** | Lateral wall of the cavernous sinus, Meckel's cave |
| **Mandibular branch (V3)** | Foramen ovale → medial to lateral pterygoid plate → mandibular foramen → inferior alveolar canal |
| **Maxillary branch (V2)** | Foramen rotundum → pterygopalatine fossa → infraorbital canal |
| **Auriculotemporal nerve** | V3 → behind TMJ → upward along superficial temporal artery |

**Practical contouring technique:**
- Use a CTV of 5-8mm around the expected nerve pathway
- Narrow to 3-5mm within bony canals
- The pathway should logically connect the primary site to the cavernous sinus

---

## Section 2 — Neck Node Management in ACC

### 2.1 The Low Lymphatic Metastasis Principle

ACC has significantly lower rates of lymph node metastasis compared to SCC. Routine prophylactic neck irradiation is NOT indicated for the majority of ACC patients. Neck dissections are often not performed electively in ACC surgery.

### 2.2 When to Irradiate the Neck

The following situations warrant prophylactic ipsilateral neck irradiation (Ib + II + III):

| Indication | Rationale |
|-----------|-----------|
| **Solid-type ACC histology** | Solid subtype has higher aggression and metastatic potential |
| **Primary site BELOW the oral fissure** (tongue, floor of mouth, submandibular gland, sublingual gland) | These sites have richer lymphatic drainage |
| **Known pathological lymph node involvement** | Standard surgical bed coverage |

### 2.3 When NOT to Irradiate the Neck

Do NOT perform prophylactic neck irradiation when:

| Condition | Rationale |
|-----------|-----------|
| **Primary site ABOVE the oral fissure** (hard palate, soft palate, nasal cavity, paranasal sinuses, upper gingiva) AND **non-solid histology** | Lymphatic drainage from these sites is minimal |
| **Cribriform or tubular ACC subtype** without nodal involvement | Very low metastatic risk |

### 2.4 Neck Coverage Decision Algorithm

```
ACC Post-Op Neck Irradiation Decision
              │
    ┌─────────┴─────────┐
    │                   │
  Solid histology    Non-solid histology
    │                   │
    │              ┌────┴────┐
    │              │         │
    │         Below oral  Above oral
    │          fissure     fissure
    │              │         │
    │              │         │
    └──────┬───────┘         │
           │                 │
    Irradiate          DO NOT irradiate
    ipsilateral        prophylactic neck
    Ib + II + III
```

### 2.5 Salivary Gland-Specific Considerations

| Primary Site | Typical Neck Management | Rationale |
|-------------|------------------------|-----------|
| **Parotid gland** | No prophylactic neck RT (unless solid type) | Lymphatic drainage from parotid is minimal |
| **Submandibular gland** | Consider prophylactic Ib + II (even non-solid) | This is at/below the oral fissure level |
| **Sublingual gland** | Prophylactic Ib + II (below oral fissure) | Rich lymphatic drainage |
| **Hard palate** | No prophylactic neck RT (unless solid type) | Above oral fissure, minimal lymphatic spread |
| **Minor salivary glands (buccal, palate)** | No prophylactic neck RT (unless solid type) | Above oral fissure |

---

## Section 3 — Dose and Fractionation for ACC

### 3.1 Postoperative Dose Levels

| Risk Category | Dose | Fractionation | Indication |
|--------------|------|---------------|------------|
| **High-risk (R1/R2 resection, Tier 1 PNI)** | 66 Gy | 2.0 Gy × 33 fx | Named nerve invasion, positive margins |
| **Intermediate risk (Tier 2 PNI)** | 60 Gy | 2.0 Gy × 30 fx | Small nerve involvement |
| **Low-risk (Tier 3, R0 with no PNI)** | 60 Gy | 2.0 Gy × 30 fx | Complete resection, no PNI |
| **Neural pathway prophylaxis (Tier 3)** | 50-54 Gy | 1.67-1.8 Gy × 30 fx | Prophylactic along nerve |
| **Neck prophylaxis (if indicated)** | 50-54 Gy | 1.67-1.8 Gy × 30 fx | Prophylactic neck |

### 3.2 Dose Considerations for ACC

- ACC is moderately radiosensitive. Cumulative doses of 60-66 Gy are generally required for microscopic residual disease.
- The cavernous sinus and skull base foramina can tolerate the prescribed doses (60 Gy at 2 Gy/fx is within tolerance of CN III, IV, V, VI).
- Special OAR attention: optic chiasm (Dmax ≤ 54 Gy), brainstem (Dmax ≤ 54 Gy), temporal lobe (Dmax ≤ 60 Gy).

---

## Section 4 — Site-Specific Contouring Guidelines

### 4.1 Parotid Gland ACC

| Component | Target |
|-----------|--------|
| **Tumor bed** | Parotid bed, including stylomastoid foramen if facial nerve was sacrificed |
| **Tier 1 (named nerve, e.g. auriculotemporal N.)** | Follow V3 → foramen ovale → **entire cavernous sinus** → 66 Gy to tumor bed, 60 Gy to cavernous sinus |
| **Tier 2 (small PNI only)** | Follow V3 pathway → to **inferior border of cavernous sinus** → 60 Gy |
| **Tier 3 (no PNI)** | Prophylactic along V3 to **skull base** → 54 Gy |
| **Neck nodes** | **No prophylactic neck RT** (unless solid type ACC) |

### 4.1B Parotid ACC — Facial Nerve (CN VII) Management

While ACC strongly favors sensory trigeminal branches over motor nerves, the facial nerve passes directly through the parotid gland and may show radiographic thickening on MRI. **Not all thickened facial nerves are tumor-involved.** The management of the facial nerve depends on the level of evidence for involvement, assessed across three domains:

| Evidence Level | Pathology | Symptoms | MRI |
|---------------|-----------|----------|-----|
| **Confirmed involvement** | Tumor in nerve on pathology | Facial palsy present | Nerve thickening on MRI |
| **Suspicious** | Not definitive | No palsy | Thickening present |

#### When facial nerve involvement IS confirmed (pathology + palsy + MRI)

The vertical (descending) segment of CN VII within the stylomastoid foramen must receive **high-dose irradiation (60-66 Gy)**:

```
Stylomastoid foramen
        │
        ▼
  Vertical segment (descending in temporal bone)
        │
        ├── Upper vertical segment (near stylomastoid foramen)
        │     → Surgically inaccessible — high risk of residual
        │     → **60-66 Gy radical dose**
        │
        └── Lower vertical segment
              → Include in high-dose CTV
```

**Rationale**: The upper vertical segment of CN VII lies within the bony stylomastoid canal immediately below the skull base. This area is extremely difficult to clear surgically during parotidectomy. Even with "nerve-sparing" techniques, microscopic tumor within the canal is likely.

#### When facial nerve involvement is NOT confirmed

| Segment | Action | Dose | Rationale |
|---------|--------|------|-----------|
| **Vertical segment (stylomastoid)** | **Prophylactic coverage** | 50-54 Gy | The proximal vertical segment is still a potential route but unconfirmed |
| **Horizontal (intratemporal) segment** | **DO NOT irradiate** | — | Irradiating the horizontal segment within the petrous temporal bone would significantly increase dose to the **cochlea and vestibular apparatus** → sensorineural hearing loss |

**Key distinction from V3 pathway**: The trigeminal pathway (V3 → foramen ovale → cavernous sinus) is the primary route of ACC perineural spread from the parotid. The facial nerve pathway (CN VII → stylomastoid foramen → internal acoustic meatus) is a secondary concern that requires rigorous evidence before escalating the CTV, because the cost of over-coverage is inner ear toxicity.

#### Contouring guidance —Stylomastoid vertical segment

| Boundary | Definition |
|----------|-----------|
| Entry point | Stylomastoid foramen (between styloid process and mastoid tip) |
| Course | Descends vertically approximately 10-15 mm within the temporal bone |
| CTV width | 5-8 mm around the nerve within the canal; 3-5 mm within the bony canal |
| OAR proximity | Cochlea lies anterior and medial — **verify cochlear Dmean ≤ 45 Gy** |

| **Neck nodes** | **No prophylactic neck RT** (unless solid type ACC) |

### 4.2 Submandibular / Sublingual Gland ACC

| Component | Target |
|-----------|--------|
| Primary → nerve | Lingual nerve (V3) → chorda tympani (CN VII, but follows V3 pathway to skull base) → foramen ovale |
| Neck nodes | **Prophylactic ipsilateral Ib + II** (at or below oral fissure) → 50-54 Gy |

### 4.3 Hard Palate / Palatal Minor Salivary Gland ACC

| Component | Target |
|-----------|--------|
| Primary → nerve | Greater and lesser palatine nerves → pterygopalatine fossa → V2 (maxillary division) → foramen rotundum → cavernous sinus |
| Neck nodes | **No prophylactic neck RT** (above oral fissure, unless solid type) |

### 4.4 Nasal Cavity / Paranasal Sinus ACC

| Component | Target |
|-----------|--------|
| Nerve pathways | Anterior ethmoidal nerve (V1) → cribriform plate; V2 via pterygopalatine fossa |
| Neck nodes | **No prophylactic neck RT** (unless solid type) |

---

## Section 5 — OAR Constraints Specific to ACC RT

Since ACC RT often extends to the skull base and cavernous sinus, special attention is required for:

| OAR | Constraint | Notes |
|-----|-----------|-------|
| **Optic chiasm** | Dmax ≤ 54 Gy | Close to cavernous sinus |
| **Brainstem** | Dmax ≤ 54 Gy | |
| **Temporal lobe** | Dmax ≤ 60 Gy | Especially for V2/V3 pathway coverage |
| **Pituitary/hypothalamus** | Dmean ≤ 45 Gy | Endocrine function |
| **Cochlea** | Dmean ≤ 45 Gy | |
| **Lacrimal gland** | Dmean ≤ 30 Gy | V1 pathway proximity |

---

## Section 6 — Key References

1. Jiang W, Xiao Y, Hu H, Li J, He Y, Han N, et al. Postoperative Intensity-Modulated radiotherapy with trigeminal nerve pathway delineation for head and neck adenoid cystic carcinoma. *Radiotherapy & Oncology*. 2025;200:111174. PMID: 41027510. DOI: 10.1016/j.radonc.2025.111174.
2. 朱国培, 等. 头颈部腺样囊性癌术后放疗靶区勾画研究. *中华放射肿瘤学杂志*. 2025;34(1):49-56.
3. ICRU Report 83: Prescribing, Recording, and Reporting Photon-Beam Intensity-Modulated Radiation Therapy (IMRT). 2010.
4. Gregoire V, et al. Delineation of the neck node levels for head and neck tumors. *Radiother Oncol*. 2014;110(1):172-181.
5. Lee NY, et al. OAR dose constraints for head and neck RT. *Int J Radiat Oncol Biol Phys*. 2018.
6. Garden AS, et al. Outcomes and patterns of care for adenoid cystic carcinoma of the head and neck. *Int J Radiat Oncol Biol Phys*. 2015.

---

## Section 7 — Future Directions & GitHub Repository

This skill is maintained as part of the Hermes Agent skills ecosystem, designed for clinical reference by radiation oncology residents and practitioners. Contributions are welcome to:

- Add site-specific nuances for rare ACC primary sites
- Refine the three-tier neural pathway coverage system with outcome data
- Incorporate emerging evidence on particle therapy (proton/carbon ion) for skull base ACC
- Develop automated scripting tools for nerve pathway contouring

**GitHub Repository**: https://github.com/NousResearch/hermes-agent (this skill is distributed under the `head-neck-target-delineation` skill family)

**To contribute**: Open a pull request or file an issue on the GitHub repository.

**Contact**: Zhu Guopei, MD — Department of Radiation Oncology, Shanghai Ninth People's Hospital, Shanghai Jiao Tong University School of Medicine. Email: antica@gmail.com

---

*This clinical framework was developed through the clinical experience and published research of the Department of Radiation Oncology, Shanghai Ninth People's Hospital, Shanghai Jiao Tong University School of Medicine. It is intended for educational and clinical reference purposes and should be used in conjunction with individual patient assessment and institutional guidelines.*
