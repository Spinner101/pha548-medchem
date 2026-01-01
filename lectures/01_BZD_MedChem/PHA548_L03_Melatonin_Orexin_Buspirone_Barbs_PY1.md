---
marp: true
theme: uncover
paginate: true
backgroundColor: #ffffff
style: |
  section {
    font-family: 'Helvetica', sans-serif;
    text-align: left;
    font-size: 22px;
    padding: 40px;
  }
  h1 { font-size: 40px; }
  h2 { font-size: 32px; }
  h3 { font-size: 26px; }
  footer { font-size: 14px; color: #7f8c8d; }
  .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
  }

title: Melatonin Agonists, Orexin Antagonists, Buspirone, and Barbiturates – Medicinal Chemistry
footer: "PHA 548 | Hampton University | PY1 PharmD"
---

# 🌗 Alternative Hypnotic Pathways: Melatonin, Orexin, Buspirone & Barbiturates

**Course:** PHA 548 Pharmacology & Medicinal Chemistry  

---

## 🎯 Learning Objectives (PY1 – MedChem Focus)

By the end of this lecture, you should be able to:

1. **Describe** the structural pharmacophores of **melatonin receptor agonists** (ramelteon, tasimelteon) and relate them to MT1/MT2 selectivity. :contentReference[oaicite:3]{index=3}  
   - *Bloom:* Understand / Apply  

2. **Compare** the **duAL orexin receptor antagonists** (suvorexant, lemborexant, daridorexant) in terms of structure, lipophilicity, and half-life. :contentReference[oaicite:4]{index=4}  
   - *Bloom:* Analyze  

3. **Explain** how **buspirone** differs mechanistically and structurally from $GABA_A$-modulating sedative-hypnotics.  
   - *Bloom:* Understand / Analyze  

4. **Relate** barbiturate SAR to CNS depressant spectrum, potency, and duration of action.  
   - *Bloom:* Analyze / Evaluate  

5. **Apply** structure → PK/PD logic across classes to select safer options in insomnia / anxiety case vignettes.  
   - *Bloom:* Apply / Evaluate  

---

## Section 1 – Melatonin Receptor Agonists

### Endogenous Template: Melatonin

- **Target:** MT1 and MT2 GPCRs in the **suprachiasmatic nucleus**  
- **Core motif:** **Indole** (or indane-like) + amide side chain  
- Rapid first-pass metabolism → short $t_{1/2}$, limited as a regulated drug

> Medicinal chemistry goal: build more **selective**, **stable**, and **orally effective** analogues.

---

## Ramelteon – MT1/MT2 Agonist:contentReference[oaicite:5]{index=5}

<div class="columns">
<div>

**Key Structural Points**

- **Non-indole** scaffold (indane-like bicyclic core)  
- Amide side chain mimics melatonin’s acylamido motif  
- Additional lipophilic/aromatic regions → **↑ MT1/MT2 affinity**  
- Deliberate design to **avoid BZD site** on $GABA_A$ receptors:contentReference[oaicite:6]{index=6}  

**PK / Metabolism**

- Rapid absorption; **extensive first-pass metabolism**  
- **CYP1A2** (major), 2C, 3A4; $t_{1/2}\approx 2$ h:contentReference[oaicite:7]{index=7}  
- Active metabolite (M-II) retains MT1/MT2 agonism, may prolong effect:contentReference[oaicite:8]{index=8}  

**Clinical design win**

- Effective in **transient & chronic insomnia** with **no tolerance** over months of use and minimal next-day effects:contentReference[oaicite:9]{index=9}  
- Not a controlled substance; no evidence of abuse liability:contentReference[oaicite:10]{index=10}  

</div>
<div>

![Ramelteon structure](figures/ramelteon_structure.jpg)

</div>
</div>

---

## Tasimelteon – MT1/MT2 Agonist:contentReference[oaicite:11]{index=11}

- **Selective MT1/MT2 agonist**  
- Designed for **non–24-hour sleep–wake disorder**, particularly in totally blind patients  
- FDA ultimately approved use in both **blind and non-blind** individuals:contentReference[oaicite:12]{index=12}  

**MedChem Themes**

- Similar melatonin-mimetic topology (aryl–alkyl–amide motif)  
- Structural tailoring to improve:
  - Oral bioavailability  
  - Circadian rhythm entrainment  
- High receptor selectivity → **low off-target sedation** and **no BZD-type amnesia**

---

## Section 2 – Orexin Receptor Antagonists (“DORAs”)

**Physiology**

- Orexin A/B (hypocretins): neuropeptides promoting **wakefulness**  
- **OX1R / OX2R** activation → arousal, increased monoamine tone  
- Antagonists → **“switch off wake drive”** → sleep

---

## Suvorexant & Lemborexant – Dual Orexin Receptor Antagonists

<div class="columns">
<div>

### Shared MedChem Traits

- Highly **lipophilic, polyaryl cores**  
- Amide / urea or related polar handles (H-bonding to receptor)  
- **Dual OX1/OX2 antagonism** → sleep promotion without $GABA_A$ modulation  
- Schedule IV; main adverse effect: **somnolence**

### Lemborexant Key Data:contentReference[oaicite:13]{index=13}  

- FDA-approved 2019  
- Doses 2.5–10 mg effective for insomnia  
- $t_{1/2}$ ≈ 17–19 h (long but designed for **night-time** action)  
- Minimal next-morning drowsiness in most patients  
- Does *not* produce BZD/Z-drug-like **anterograde amnesia**:contentReference[oaicite:14]{index=14}  

</div>
<div>

![Orexin antagonist structures](figures/orexin_DORA_panel.jpg)

</div>
</div>

---

## Daridorexant (Quviviq) – Newer DORA (MedChem Angle)

- Dual OX1/OX2 antagonist (like suvorexant/lemborexant)  
- Designed with:
  - **Moderate lipophilicity**  
  - Shorter effective half-life than suvorexant  
- Clinical goal: maintain sleep benefits while **reducing next-day impairment**

**Conceptual MedChem Theme**

- Fine-tune:
  - Lipophilicity  
  - Volume of distribution  
  - Clearance (CYP3A4-mediated)  
to optimize **sleep maintenance** vs **residual sedation**.

---

## MedChem Compare – BZD/Z vs Orexin vs Melatonin

| Class                   | Primary Target      | Core Scaffold          | Memory Effects      | Abuse Potential |
| :---------------------- | :------------------ | :--------------------- | :------------------ | :-------------- |
| Classic BZDs            | $GABA_A$ BZD site   | Benzodiazepine         | ↑ Amnesia           | Yes (C-IV)      |
| Z-drugs                 | $GABA_A$ BZD site   | Heteroaromatic         | ↑ Amnesia / behaviors | Yes (C-IV)   |
| Melatonin agonists      | MT1/MT2 GPCRs       | Melatonin-mimetic      | Minimal             | None (non-CS)   |
| Orexin antagonists      | OX1/OX2 GPCRs       | Polyaryl amide/urea    | Minimal amnesia     | Yes (C-IV)      |

> Case teaching hook: “Which scaffold would you choose for a patient with history of BZD misuse and sleep-related eating?”

---

## Section 3 – Buspirone (Non-sedating Anxiolytic)

<div class="columns">
<div>

**Mechanism**

- **Partial agonist at 5-HT1A receptors**  
- Minor D2 receptor actions  
- No direct action at:
  - $GABA_A$  
  - Melatonin  
  - Orexin receptors  

**Structure**

- **Azaspirodecanedione** core  
- Aryl-piperazine side chain  
- Polar, bulky scaffold → **poor CNS penetration compared with lipophilic BZDs**

**Clinical Consequences**

- **Non-sedating anxiolytic**  
- No significant hypnosis, no anticonvulsant or muscle relaxant activity  
- Delayed onset (weeks) → not for acute panic  

</div>
<div>

![Buspirone structure](figures/buspirone_structure.jpg)

</div>
</div>

---

## Section 4 – Barbiturates: “Old School” Sedative-Hypnotics

### Core MedChem

- Parent: **barbituric acid** (ureide of malonic acid + urea)  
- Active drugs: **5,5-disubstituted barbiturates**

**Key SAR Rules**

1. **Substitution at C5** (two side chains) is required for activity  
2. ↑ **Carbon chain length** (up to a limit) → ↑ lipophilicity → ↑ potency & onset  
3. **Branching** at C5 increases lipophilicity and potency  
4. Introduction of **sulfur at C2** (thiobarbiturates) → ↑ lipophilicity → faster onset & shorter duration (e.g., thiopental)  
5. Polarity (e.g., N-substitution, hydroxyl groups) → shorter duration by ↑ renal clearance

---

## Barbiturates – Structure → PK/PD

<div class="columns">
<div>

**Onset & Duration**

- **Ultra-short acting** (thiopental, thiamylal):  
  - High lipophilicity → rapid CNS entry  
  - Rapid redistribution → short hypnosis  

- **Intermediate/long-acting** (secobarbital, phenobarbital):  
  - Less lipophilic; more ionized at physiologic pH  
  - Slower redistribution, more dependence on hepatic metabolism

**Mechanism vs BZDs**

- Enhance $GABA_A$ function and, at high concentrations:  
  - Directly **open $Cl^-$ channel without GABA**  
  - Inhibit excitatory AMPA receptors  
- Explains **narrow therapeutic index** vs BZDs.

</div>
<div>

![Barbiturate SAR](figures/barbiturate_SAR_panel.jpg)

</div>
</div>

---

## MedChem Safety Contrast – BZDs vs Barbiturates

| Feature                   | BZDs                           | Barbiturates                      |
| :------------------------ | :---------------------------- | :-------------------------------- |
| Require GABA to act?      | Yes (modulators)              | No at high doses (direct agonists)|
| Overdose lethality        | Much lower (alone)            | High                              |
| Anesthesia production     | Not reliable                  | Yes (thiopental, etc.)            |
| Abuse/dependence          | Moderate                      | High                              |
| Design trend              | Still used                    | Largely replaced in insomnia      |

---

## PY1 Active Learning – Case/SAR Board

**Small-group prompt:**

1. *Which class (melatonin agonist vs orexin antagonist vs Z-drug) would you pick for:*
   - A patient with **substance use disorder** and chronic insomnia?  
   - An elderly patient needing **sleep maintenance** but already on multiple CNS depressants?  

2. *For barbiturates,* predict what happens if:
   - You **lengthen** both C5 side chains and add branching.  
   - You replace O at C2 with S.  

Students justify answers using **lipophilicity, metabolism, receptor mechanism, and safety**.

---

## Assessment Blueprint Ideas (L03)

You can store stems in `assessments/L03_AltHypnotics_bank.md` for later ExamSoft/Canvas export.

1. **Melatonin vs Orexin MCQ**  
   - Stem: Which statement best explains why ramelteon lacks abuse liability compared with BZDs and Z-drugs?  
   - Correct: It selectively activates **MT1/MT2 receptors** without modulating $GABA_A$ BZD sites and does not produce euphoria or reinforcing effects.  
   - Distractors should incorrectly attribute effects to “orexin blockade” or “lack of CNS penetration”.  
   - Bloom: *Understand/Analyze*  

2. **Orexin antagonist SAR item**  
   - Focus on high lipophilicity and dual OX1/OX2 antagonism as drivers of sleep promotion vs amnesia.  

3. **Barbiturate SAR item**  
   - Ask which structural change would **increase** onset speed but **decrease** duration (→ thiobarbiturate with bulky, lipophilic C5 substituents).  
   - Bloom: *Analyze/Evaluate*  

---

## Wrap-Up / Integrative Take-Home

- **Multiple structural strategies** can achieve hypnosis:
  - Allosteric $GABA_A$ modulation (BZDs, Z-drugs)  
  - **MT1/MT2 agonism** (ramelteon, tasimelteon):contentReference[oaicite:15]{index=15}  
  - **Orexin antagonism** (suvorexant, lemborexant, daridorexant):contentReference[oaicite:16]{index=16}  
  - Deep CNS depression (barbiturates)  

- **MedChem levers** (scaffold choice, lipophilicity, polar groups, “soft” metabolic handles) shape:  
  - Onset & duration  
  - Tolerance/abuse potential  
  - Cognitive and respiratory safety  

- For NAPLEX/ACPE-style questions, prioritize **pattern recognition**:  
  - Structure → target → PK → clinical use → safety.

---

