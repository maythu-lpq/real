# SN2 — Bimolecular Nucleophilic Substitution

## Overview

**SN2** (Substitution, Nucleophilic, Bimolecular) is a concerted, one-step nucleophilic substitution reaction in which a nucleophile displaces a leaving group from a carbon atom in a **single elementary step**. Unlike SN1, there is no discrete carbocation intermediate — bond breaking and bond forming occur simultaneously.

The reaction proceeds exclusively by **backside attack**: the nucleophile approaches the electrophilic carbon from the side directly opposite (180°) to the leaving group. This geometry is dictated by the need to overlap the nucleophile's HOMO (highest occupied molecular orbital) with the σ* (antibonding) orbital of the C–LG bond.

**General reaction:**

```
Nu:⁻  +  R–LG  →  Nu–R  +  LG⁻
```

Where:
- **Nu** = nucleophile (electron-pair donor)
- **R** = alkyl group attached to the reaction center
- **LG** = leaving group (the displaced fragment)

> **Key Concept:** SN2 is a concerted mechanism — there is exactly **one transition state** and **zero intermediates**. The reaction coordinate shows a single energy barrier.

**Prototype reaction:**

```
HO⁻  +  CH3–Br  →  HO–CH3  +  Br⁻
  (methanol synthesis from bromomethane)
```

---

## Kinetics & Rate Law

SN2 is a **second-order reaction** — first order in substrate and first order in nucleophile:

```
Rate = k [substrate][nucleophile]
```

| Variable | Effect on Rate |
|---|---|
| [Substrate] doubles | Rate doubles |
| [Nucleophile] doubles | Rate doubles |
| Both double | Rate quadruples |

Because both the substrate and nucleophile participate in the **rate-determining (and only) step**, doubling either concentration directly doubles the reaction rate. This distinguishes SN2 kinetically from SN1, where the nucleophile concentration has no effect on rate.

> **Exam Rule:** If the rate doubles when [nucleophile] doubles, the mechanism is **SN2**, not SN1.

**Energy profile:**

The reaction coordinate diagram for SN2 features:
- A single, smooth energy hill (one transition state, TS‡)
- No energy wells (no intermediates)
- Energy of TS‡ above both reactants and products

```
 Energy
   |          ‡
   |         /TS\
   |        /    \
   |       /      \
   |      /        \
   |─────/          \─────
   |  Reactants    Products
   |________________________________ Reaction Coordinate
```

The activation energy (Ea) is lowered by strong nucleophiles and good leaving groups.

---

## Step-by-Step Mechanism

SN2 proceeds in a **single concerted step**:

### Step 1 (Only Step): Concerted Backside Attack

1. The nucleophile (Nu:⁻) approaches the electrophilic carbon **from the back** — directly opposite the leaving group (180° approach angle).
2. As the nucleophile begins to form a bond with the carbon, the C–LG bond simultaneously begins to weaken and break.
3. The reaction passes through a single **trigonal bipyramidal transition state** in which the central carbon is pentacoordinate (five partial bonds):
   - The three substituents on the carbon lie in a plane (equatorial positions).
   - The partially bonded nucleophile and partially bonded leaving group occupy the two axial positions (above and below the plane).
4. The leaving group fully departs with both bonding electrons (heterolytic cleavage → LG⁻).
5. The nucleophile is now fully bonded; the product is formed.

**Transition state representation:**

```
         [δ−]           [δ−]
Nu ·····C(R₁R₂R₃)·····LG
     ↑ trigonal bipyramidal ↑
        pentacoordinate TS‡
```

Where the dashed lines (·····) indicate **partially formed / partially broken** bonds.

**Walden Inversion cartoon (wedge-dash notation):**

```
         R₃                       R₃
          |                        |
Nu⁻ ──> C──LG   →   Nu──C <── LG⁻
         |                        |
      R₁   R₂                  R₁   R₂
   (inversion: umbrella flips)
```

> **Mechanistic Fact:** The three non-leaving-group substituents (R₁, R₂, R₃) invert their configuration as the nucleophile attacks — like an umbrella turning inside out in the wind. This is the hallmark of SN2.

---

## Stereochemistry

SN2 reactions result in **complete inversion of configuration** at the stereocenter undergoing substitution. This phenomenon is known as the **Walden Inversion**.

### Why Complete Inversion?

- The backside attack geometry forces the nucleophile to bond to the carbon from the face opposite the leaving group.
- The three remaining substituents "flip" through the trigonal planar transition state — analogous to an umbrella inverting.
- Because the attack is strictly backside, there is no mixture of retention and inversion: **100% inversion** is observed.

### Stereochemical Outcome

| Starting Configuration | Product Configuration |
|---|---|
| (R) | (S) |
| (S) | (R) |
| (+) | (−) |
| (−) | (+) |

> **Important:** The assignment of (R) → (S) is not guaranteed by the inversion alone — the priority of the incoming nucleophile relative to the other substituents must be evaluated using CIP rules. However, the **spatial arrangement always inverts**, even if the R/S designation happens to remain the same (which occurs when the nucleophile and leaving group have similar CIP priorities).

**Example:**

```
(R)-2-bromobutane  +  HO⁻  →  (S)-2-butanol  +  Br⁻
```

- The hydroxyl attacks from the back face.
- The configuration at C-2 inverts from (R) to (S).
- The optical rotation of the product is opposite to that of the starting material.

### Enantiomeric Purity

Since SN2 is stereospecific (not just stereoselective), the product of a pure enantiomer starting material is a **pure enantiomer** product — there is no racemization. The enantiomeric excess (ee) of the product equals that of the starting material, with opposite sign.

> **Contrast with SN1:** SN1 gives a racemic mixture (or near-racemic with slight inversion excess); SN2 gives **complete inversion** with full retention of ee.

---

## Controlling Factors

### Substrate

Steric hindrance at the reaction center is the **single most important factor** controlling SN2 reactivity. The backside attack requires the nucleophile to approach closely to the carbon bearing the leaving group; bulky substituents physically block this approach.

**Reactivity order:**

```
Methyl (CH₃–)  >>  Primary (1°)  >  Secondary (2°)  >>  Tertiary (3°)
  fastest                                              virtually zero
```

| Substrate Type | Example | Relative Rate | Notes |
|---|---|---|---|
| Methyl | CH₃Br | ~1,000,000 | No steric hindrance |
| Primary (1°) | CH₃CH₂Br | ~1,000 | Low steric hindrance |
| Secondary (2°) | (CH₃)₂CHBr | ~1 | Moderate steric hindrance |
| Tertiary (3°) | (CH₃)₃CBr | ~0 | Severe steric hindrance; SN1 or E2 instead |

**Special case — Neopentyl (2,2-dimethyl-1-propyl):**

Neopentyl bromide [(CH₃)₃CCH₂Br] is a **primary** substrate but reacts extremely slowly in SN2. Although the carbon bearing the leaving group is primary (only one alkyl substituent), the adjacent quaternary carbon (bearing three methyl groups) creates severe steric congestion in the transition state — the approaching nucleophile is effectively blocked.

> **Rule:** Even 1° substrates can be SN2-resistant if there is a bulky β-substituent (neopentyl effect).

**Allylic and benzylic positions:**

- Allylic (C=C–CH₂–LG) and benzylic (Ar–CH₂–LG) primary substrates react readily via SN2 due to resonance stabilization in the transition state and no extra steric bulk.
- These are excellent SN2 substrates when paired with strong nucleophiles.

---

### Nucleophile/Base

Unlike SN1, **nucleophile strength directly affects the SN2 rate**. Strong, polarizable nucleophiles are required for efficient SN2.

**Key factors determining nucleophile strength for SN2:**

1. **Charge:** Anionic nucleophiles (Nu:⁻) react much faster than neutral ones (Nu:).
2. **Basicity:** Stronger bases are generally better nucleophiles (within the same period).
3. **Polarizability:** Larger, more polarizable atoms are better nucleophiles in protic media — their electron clouds are more easily distorted to interact with the carbon (soft–soft interaction).

**Common strong SN2 nucleophiles (ranked roughly by effectiveness):**

| Nucleophile | Name |
|---|---|
| I⁻ | Iodide (excellent — large, polarizable) |
| HS⁻ / RS⁻ | Sulfide / thiolate (large S atom, very polarizable) |
| CN⁻ | Cyanide |
| N₃⁻ | Azide |
| Br⁻ | Bromide |
| RO⁻ | Alkoxide (strong base) |
| HO⁻ | Hydroxide |
| Cl⁻ | Chloride |
| NH₃ | Ammonia (neutral, moderate) |

> **Trend:** Nucleophilicity down a group (e.g., F⁻ < Cl⁻ < Br⁻ < I⁻) increases with polarizability, especially in polar protic solvents. In polar aprotic solvents, the basicity/nucleophilicity correlation is cleaner: F⁻ > Cl⁻ > Br⁻ > I⁻.

**Poor SN2 nucleophiles (too weak or too sterically hindered):**

- Carboxylates (RCOO⁻) — resonance-stabilized, reduced nucleophilicity
- Weak bases/neutral molecules in absence of a polar aprotic solvent
- Bulky bases (e.g., LDA, t-BuO⁻) — promote elimination (E2) instead of substitution

> **Competition with Elimination:** Strong bases that are also poor nucleophiles (or bulky) favor **E2** over SN2. E.g., KOtBu with a secondary substrate gives predominantly alkene, not substitution product.

---

### Leaving Group

The leaving group must be able to **depart as a stable species** (anion or neutral molecule) with both electrons from the C–LG bond. The same leaving group trends apply in SN2 as in SN1.

**Reactivity order (best to worst leaving groups):**

```
I⁻  >  Br⁻  >  Cl⁻  >>  F⁻
OTs⁻ (tosylate)  >  OTf⁻ (triflate)  >>  OH⁻, OR⁻, NH₂⁻
```

| Leaving Group | Species Departed | Quality | Notes |
|---|---|---|---|
| –I | I⁻ | Excellent | Weakest C–halogen bond; most polarizable |
| –Br | Br⁻ | Very Good | Common in lab synthesis |
| –Cl | Cl⁻ | Good | Adequate for SN2 |
| –F | F⁻ | Poor | Strongest C–F bond; F⁻ is a poor LG |
| –OTs | OTs⁻ | Excellent | Tosylates = sulfonate esters; comparable to Br |
| –OTf | OTf⁻ | Excellent | Triflates = superb leaving groups |
| –OH | H₂O | Very Poor | OH⁻ is a strong base and poor LG; must protonate first |
| –OR | ROH | Poor | Same reasoning as –OH |
| –NH₂ | NH₂⁻ | Very Poor | NH₂⁻ is a strong base; will not leave |

> **Practical Note:** To substitute an alcohol via SN2, the –OH must first be converted to a tosylate (TsCl/pyridine) or activated with SOCl₂ or PBr₃. This converts the poor –OH leaving group into an excellent one while **retaining configuration** (the C–O bond is not broken in this step).

---

### Solvent Effects

Solvent choice profoundly affects SN2 rates by influencing how well the nucleophile is solvated (and therefore deactivated) before it reaches the substrate.

#### Polar Aprotic Solvents (Ideal for SN2)

Polar aprotic solvents have high polarity (ability to dissolve ions) but **lack O–H or N–H bonds** and thus cannot hydrogen-bond to the nucleophile.

**Examples:** DMSO (dimethyl sulfoxide), DMF (dimethylformamide), acetone, acetonitrile (MeCN), HMPA

**Why they favor SN2:**
- The nucleophile (anion) is **"naked"** — not wrapped in a solvation shell.
- A free, unsolvated nucleophile is far more reactive and attacks the substrate much faster.
- Rate accelerations of 10³–10⁶ × compared to protic solvents have been observed.

> **Example:** NaI in acetone reacts with alkyl chlorides via SN2 (the Finkelstein reaction) because NaI is soluble in acetone but NaCl is not — the insoluble NaCl precipitates, driving the equilibrium toward product.

#### Polar Protic Solvents (Disfavor SN2)

Polar protic solvents (water, methanol, ethanol, acetic acid) have O–H or N–H bonds and strongly hydrogen-bond to anions.

**Why they slow SN2:**
- The nucleophile becomes surrounded by a cage of solvent molecules (H-bonding), dramatically reducing its reactivity.
- More energy is required to "desolvate" the nucleophile before it can attack the carbon.
- Protic solvents also stabilize the charge-dispersed transition state less effectively than the initial reactant ions.

> **Summary Table:**

| Solvent Type | H-bonding to Nu? | SN2 Rate | SN1 Rate | Examples |
|---|---|---|---|---|
| Polar Aprotic | No | **Fast** ↑ | Moderate | DMSO, DMF, acetone, MeCN |
| Polar Protic | Yes (strongly) | **Slow** ↓ | **Fast** ↑ | H₂O, MeOH, EtOH, AcOH |

> **Rule of Thumb:** For SN2, choose **DMSO or DMF**. For SN1, choose **water or ethanol**. Matching solvent to mechanism is as important as choosing the right nucleophile.

---

## Related Mechanisms

The SN2 mechanism competes with and complements three other fundamental reactions. Understanding which pathway is favored requires evaluating substrate, nucleophile/base strength, leaving group, and solvent together.

| Mechanism | File | Key Difference from SN2 |
|---|---|---|
| SN1 | [SN1 Mechanism](sn1.md) | Two steps; carbocation intermediate; favors 3°; polar protic solvent; racemization |
| E1 | [E1 Mechanism](e1.md) | Elimination; carbocation intermediate; forms alkene; favors 3°; weak base |
| E2 | [E2 Mechanism](e2.md) | Concerted elimination; strong bulky base; anti-periplanar geometry; competes with SN2 |

**Decision guide (substrate + nucleophile/base + conditions):**

```
Strong, small nucleophile + 1° substrate + polar aprotic  →  SN2
Strong, bulky base + any substrate + polar aprotic        →  E2
Weak nucleophile + 3° substrate + polar protic            →  SN1
Weak base + 3° substrate + heat + polar protic            →  E1
```

> **Competition between SN2 and E2:** When a secondary substrate is treated with a strong base (e.g., NaOH, NaOEt), both SN2 and E2 can occur. Increasing temperature, using a bulky base (KOtBu), or switching to a 2° or 3° substrate all favor **E2** over SN2.

### Cross-References

- [SN1 Mechanism](sn1.md) — Compare unimolecular vs. bimolecular kinetics; racemization vs. inversion; carbocation stability requirements.
- [E1 Mechanism](e1.md) — Compare carbocation-based elimination with concerted elimination; role of heat.
- [E2 Mechanism](e2.md) — Understand the SN2 vs. E2 competition; role of base strength, bulkiness, and temperature.

---

*Source: Organic Chemistry LLM Wiki. For additions or corrections, update this file and the [Wiki Index](index.md).*
