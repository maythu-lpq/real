# SN1 — Unimolecular Nucleophilic Substitution

> **Source file:** `wiki/sn1.md` | Part of the [Organic Chemistry Reaction Mechanism Wiki](index.md)

---

## Overview

**SN1** (Substitution, Nucleophilic, **Unimolecular**) is a two-step reaction mechanism in which a leaving group departs first to generate a carbocation intermediate, which is then captured by a nucleophile. Because the rate-determining step involves only one species (the substrate), the reaction is classified as unimolecular.

**General Equation:**

```
R–LG  →  R⁺  +  LG⁻   (slow, rate-determining)
R⁺  +  Nu⁻  →  R–Nu   (fast)
```

**Key characteristics at a glance:**

| Feature | SN1 |
|---|---|
| Steps | 2 (ionization → capture) |
| Rate order | 1st order (unimolecular) |
| Intermediate | Carbocation (sp² hybridized) |
| Stereochemical outcome | Racemization (± slight inversion) |
| Preferred substrate | Tertiary (3°) >> Secondary (2°) |
| Nucleophile strength | Not required (weak Nu acceptable) |
| Solvent preference | Polar protic (H₂O, ROH) |

---

## Kinetics & Rate Law

The SN1 reaction is **first-order overall**, depending only on the concentration of the substrate. The nucleophile does not appear in the rate law because it attacks *after* the rate-determining step.

**Rate Law:**

$$\text{Rate} = k[\text{substrate}]$$

or equivalently:

```
Rate = k[R–LG]
```

> **Key Rule:** Because the nucleophile is not involved in the rate-determining step, changing the nucleophile's concentration or identity has **no effect** on the reaction rate.

**Energy Profile:**

The reaction coordinate shows two steps separated by two transition states and one energy minimum (the carbocation intermediate):

```
Energy
  |         TS1              TS2
  |          *               *
  |         / \             / \
  |        /   \           /   \
  |       /     \         /     \
  |  SM  /       [R⁺·LG⁻]       \  Product
  |_____/                         \________
                Reaction Coordinate →
```

- **TS1** (highest energy point): C–LG bond stretching to full heterolytic cleavage → rate-determining
- **Intermediate**: Planar, sp²-hybridized carbocation (or intimate ion pair)
- **TS2**: Nucleophile approaching carbocation → fast step

**Temperature & Solvent Effects on Rate:**

- Increased temperature raises k (Arrhenius behavior); SN1 has a relatively large activation energy for ionization.
- Polar protic solvents dramatically lower ΔG‡ by stabilizing developing charges in TS1, increasing rate.

---

## Step-by-Step Mechanism

### Step 1: Ionization (Rate-Determining Step)

The C–LG bond undergoes **heterolytic cleavage**: both electrons of the bond move with the leaving group, generating a carbocation and the leaving group anion.

```
       LG                            ⊕          ⊖
  R₃C–LG  ──────→   R₃C    +    LG
            slow
         (rate-determining)
```

- The bond breaks heterolytically; the leaving group departs with the bonding electron pair.
- The central carbon rehybridizes from **sp³ → sp²**, becoming planar with an empty p orbital.
- This step is strongly endothermic; it requires a stable carbocation to form.
- An **ion pair** (R₃C⁺ ‖ LG⁻) may persist transiently before full separation.

### Step 2: Nucleophilic Attack (Fast Step)

The nucleophile (Nu) attacks the electron-deficient carbocation. Because the carbocation is **planar** (sp²), the nucleophile can approach from either face — the top or the bottom — with roughly equal probability.

```
       Nu⁻             ⊕                      Nu⁻
        ↓          R₃C                         ↑
       [from top]    |     → products      [from bottom]
                   (empty p orbital)
```

- If the nucleophile attacks from the **same face** the leaving group departed → **retention** of configuration.
- If the nucleophile attacks from the **opposite face** → **inversion** of configuration.
- In practice, both pathways occur, leading to racemization (see Stereochemistry).

### Optional Step: Carbocation Rearrangements

If the initially formed carbocation is not maximally stable, **1,2-hydride shifts** or **1,2-methyl shifts** can occur to generate a more stable (higher-order) carbocation *before* nucleophilic capture.

```
  2° carbocation  →  1,2-hydride shift  →  3° carbocation  →  product
```

> **Watch out:** Rearrangements are a diagnostic hallmark of SN1 (and E1) pathways. If the product carbon skeleton differs from the starting material, a rearrangement has occurred.

---

## Stereochemistry

### Racemization as the Expected Outcome

Because the planar sp² carbocation intermediate has **no top/bottom distinction** (both faces are equivalent in an achiral environment), nucleophilic attack occurs from both faces with equal probability, yielding a **50:50 mixture of enantiomers (racemate)**.

```
Starting material:          Carbocation:         Products:
  (R)-R₃C–LG    →      [planar R₃C⁺]    →   (R)-R₃C–Nu   (50%)
                                          →   (S)-R₃C–Nu   (50%)
```

**Result:** Complete loss of optical activity (optical rotation → 0 for the racemate).

### Slight Excess of Inversion (Ion-Pair Effect)

In reality, the leaving group does not immediately diffuse away. It remains briefly as an **intimate ion pair** or **solvent-separated ion pair**, partially shielding the face from which it departed. This means the nucleophile preferentially attacks from the opposite face, giving a **slight excess of the inverted product**.

```
Observed ratio ≈ 55–70% inversion / 30–45% retention (varies with conditions)
```

> **Key Rule:** SN1 gives racemization as the *theoretical* outcome but partial inversion in *practice* due to ion-pair shielding. This contrasts sharply with SN2, which gives **complete inversion** (Walden inversion).

### Summary Table

| Mechanism | Stereochemical Outcome |
|---|---|
| SN1 | Racemization (± slight excess of inversion) |
| SN2 | 100% inversion (Walden inversion) |
| E1 | No new stereocenters formed; Zaitsev product |
| E2 | Anti-periplanar; stereospecific |

---

## Controlling Factors

### Substrate

Substrate structure is the **most critical** factor for SN1. The reaction requires a stable carbocation intermediate, so only substrates that can generate reasonably stable carbocations will react via SN1.

**Reactivity order:**

```
Methyl (0°) << Primary (1°) < Secondary (2°) << Tertiary (3°) ≈ Allylic/Benzylic
```

| Substrate Type | Carbocation Stability | SN1 Feasibility |
|---|---|---|
| Methyl (CH₃–LG) | Methyl cation (extremely unstable) | Never |
| Primary (1°) | Primary carbocation (very unstable) | Essentially never* |
| Secondary (2°) | Secondary carbocation (moderate) | Possible (slow) |
| Tertiary (3°) | Tertiary carbocation (stable) | Yes (fast) |
| Allylic / Benzylic | Resonance-stabilized cation | Yes (fast) |

*\*Exception: allylic and benzylic primary substrates can react via SN1 due to resonance stabilization.*

**Carbocation stability — why tertiary is favored:**

- **Hyperconjugation**: Adjacent C–H σ bonds donate electron density into the empty p orbital.
- **Inductive effect**: Alkyl groups are electron-donating (+I), stabilizing adjacent positive charge.
- More alkyl substituents → more hyperconjugation and inductive stabilization → more stable carbocation.

> **Key Rule:** Never expect SN1 at a methyl or unactivated primary carbon. The carbocation would be too high in energy to form under normal conditions.

### Nucleophile/Base

Unlike SN2, the nucleophile does **not** participate in the rate-determining step of SN1. Therefore:

- **Nucleophile strength is irrelevant to rate.**
- Weak, non-basic nucleophiles (H₂O, ROH, RCOOH) are perfectly acceptable and are the typical nucleophiles in SN1.
- Strong nucleophiles are not required and may even shift the mechanism toward SN2 (if the substrate allows) or E2.

**Common SN1 nucleophiles:**

| Nucleophile | Example | Comment |
|---|---|---|
| Water (H₂O) | Solvolysis → alcohol | Most common in aqueous media |
| Alcohols (ROH) | Solvolysis → ether | Common in alcohol solvents |
| Carboxylates (RCOO⁻) | → ester | Weak nucleophile, good for SN1 |
| Halide ions (Cl⁻, Br⁻) | → alkyl halide | In polar protic media |

> **Key Rule:** The rate of SN1 is independent of [Nu]. Doubling [Nu] does *not* double the rate.

### Leaving Group

A **good leaving group** is essential for SN1 because the entire reaction depends on the first step — ionization — which requires C–LG bond cleavage to be favorable.

**Leaving group ability (best → worst):**

```
TfO⁻ > TsO⁻ > I⁻ > Br⁻ > Cl⁻ >> F⁻ >> HO⁻, RO⁻, NH₂⁻
```

| Leaving Group | pKa of conjugate acid (H–LG) | LG Ability |
|---|---|---|
| Triflate (TfO⁻) | ~ −14 | Excellent |
| Tosylate (TsO⁻) | ~ −1 | Excellent |
| Iodide (I⁻) | ~ −10 | Very good |
| Bromide (Br⁻) | ~ −9 | Good |
| Chloride (Cl⁻) | ~ −7 | Moderate |
| Fluoride (F⁻) | +3.2 | Poor |
| Hydroxide (HO⁻) | +15.7 | Will not leave (without activation) |
| Alkoxide (RO⁻) | ~16–18 | Will not leave |

**General rule:** A good leaving group is the conjugate base of a **strong acid** (low pKa). It must be stable as an anion after departure.

> **Key Rule:** Hydroxyl groups (–OH) are poor leaving groups in their natural form. They must be **protonated** (to give –OH₂⁺, which then leaves as water) or **activated** as a tosylate/triflate before SN1 can proceed.

**Effect on rate:** Unlike the nucleophile, **the leaving group does appear in the rate-determining step** (TS1). Better leaving groups lower the activation energy for ionization and increase the rate of SN1.

### Solvent Effects

Solvent choice has a **dramatic effect** on SN1 reactions. Polar protic solvents strongly favor SN1 because they stabilize both the developing cationic and anionic charges in the transition state and in the intermediate.

**Why polar protic solvents favor SN1:**

1. **Solvation of carbocation**: The solvent's lone pairs (from O–H groups) coordinate to the empty p orbital of R⁺, lowering its energy.
2. **Solvation of leaving group anion**: Hydrogen bonding from the solvent stabilizes LG⁻ after departure.
3. **Lower activation energy**: Both effects lower ΔG‡ for ionization (TS1), accelerating the rate.

**Solvent classification:**

| Solvent Type | Examples | SN1 Favorability |
|---|---|---|
| Polar protic | H₂O, MeOH, EtOH, AcOH, HCOOH | **Strongly favored** |
| Polar aprotic | DMSO, DMF, acetone, MeCN | Moderate / disfavored |
| Nonpolar | hexane, diethyl ether, CCl₄ | Strongly disfavored |

> **Key Rule:** SN1 is strongly promoted by **polar protic** solvents. Polar aprotic solvents favor SN2 instead by solvating the cation but leaving the nucleophile "naked" and highly reactive.

**Dielectric constant (ε) matters:**

Higher ε → better solvation of ions → faster SN1

```
H₂O (ε ≈ 80) > MeOH (ε ≈ 33) > EtOH (ε ≈ 25) > acetone (ε ≈ 21) > Et₂O (ε ≈ 4)
```

---

## SN1 vs. SN2 — Quick Decision Guide

Use this table to decide which mechanism is operating:

| Factor | Favors SN1 | Favors SN2 |
|---|---|---|
| Substrate | 3°, allylic, benzylic | Methyl, 1°, (some 2°) |
| Nucleophile | Weak (H₂O, ROH) | Strong (OH⁻, CN⁻, RS⁻) |
| Solvent | Polar protic | Polar aprotic |
| Leaving group | Good (I⁻, OTs⁻) | Good (same) |
| Stereochemistry | Racemization | Inversion |
| Rate law | Rate = k[substrate] | Rate = k[substrate][Nu] |
| Rearrangements | Possible | Never |

---

## Related Mechanisms

- [SN2 Mechanism](sn2.md) — Bimolecular nucleophilic substitution; one-step, back-side attack, complete inversion; favored by strong nucleophiles and unhindered (methyl/primary) substrates.
- [E1 Mechanism](e1.md) — Unimolecular elimination; shares the carbocation intermediate with SN1; competes with SN1 at the same substrates; favored at higher temperatures.
- [E2 Mechanism](e2.md) — Bimolecular elimination; concerted, anti-periplanar geometry required; favored by strong bases and hindered substrates; competes with SN2.

> **Competition note:** SN1 and E1 always compete because they share the same carbocation intermediate. Raising temperature or using a bulky base shifts selectivity toward elimination (E1). Lowering temperature and using a good nucleophile (but not too strong) favors substitution (SN1).

---

*Last updated: 2026-11-16 | See [Wiki Index](index.md) for all entries.*
