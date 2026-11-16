# Organic Chemistry Reaction Mechanisms — LLM Wiki Index

> This wiki is a structured knowledge base covering the four core organic chemistry reaction mechanisms used in nucleophilic substitution and elimination reactions: **SN1**, **SN2**, **E1**, and **E2**. Each entry is written at a Clayden/McMurry/Wade textbook level and includes mechanism steps, stereochemistry, controlling factors, and cross-references. Use this index to navigate between mechanisms, compare them side-by-side, and decide which one applies to a given substrate/reagent combination.

---

## Quick Navigation

| Mechanism | Type | Link |
|-----------|------|------|
| SN1 | Unimolecular Nucleophilic Substitution | [SN1 — Unimolecular Nucleophilic Substitution](sn1.md) |
| SN2 | Bimolecular Nucleophilic Substitution | [SN2 — Bimolecular Nucleophilic Substitution](sn2.md) |
| E1 | Unimolecular Elimination | [E1 — Unimolecular Elimination](e1.md) |
| E2 | Bimolecular Elimination | [E2 — Bimolecular Elimination](e2.md) |

---

## Mechanism Summaries

### SN1 — Unimolecular Nucleophilic Substitution

SN1 is a two-step reaction: the leaving group first departs to form a planar carbocation intermediate, then the nucleophile attacks from either face. Because the rate depends only on the substrate concentration (`Rate = k[substrate]`), it is first-order and strongly favors tertiary substrates in polar protic solvents. The planar carbocation leads to **racemization** at the stereocenter.

### SN2 — Bimolecular Nucleophilic Substitution

SN2 is a single concerted step in which a strong nucleophile attacks the back face of the electrophilic carbon while the leaving group departs simultaneously. The rate is second-order (`Rate = k[substrate][nucleophile]`), and the reaction is fastest on methyl and primary substrates where steric hindrance is minimal. The backside attack geometry enforces **complete inversion of configuration** (Walden inversion) at the stereocenter.

### E1 — Unimolecular Elimination

E1 is a two-step elimination: ionization of the leaving group forms a carbocation intermediate (identical first step to SN1), followed by loss of a β-proton to a base, generating an alkene. The rate depends only on substrate concentration (`Rate = k[substrate]`), and the reaction favors tertiary substrates, weak bases, polar protic solvents, and high temperatures. Products follow **Zaitsev's rule** (more substituted alkene predominates).

### E2 — Bimolecular Elimination

E2 is a single concerted step in which a strong base abstracts a β-hydrogen while the leaving group departs simultaneously, forming an alkene directly. The rate is second-order (`Rate = k[substrate][base]`), and the reaction requires a strict **anti-periplanar geometry** between the β-H and the leaving group. It operates on all substrate classes with a strong base and high temperature; bulky bases can override Zaitsev selectivity to give the **Hofmann product**.

---

## Comparison Table

| Property | SN1 | SN2 | E1 | E2 |
|----------|-----|-----|----|----|
| **Molecularity** | Unimolecular | Bimolecular | Unimolecular | Bimolecular |
| **Rate Law** | Rate = k[substrate] | Rate = k[substrate][Nu] | Rate = k[substrate] | Rate = k[substrate][base] |
| **Steps** | 2 (ionization → attack) | 1 (concerted) | 2 (ionization → deprotonation) | 1 (concerted) |
| **Carbocation Intermediate** | Yes | No | Yes | No |
| **Stereochemistry** | Racemization (± inversion) | Complete inversion (Walden) | Mixture / Zaitsev alkene | Anti-periplanar; E/Z determined by geometry |
| **Best Substrate** | 3° (benzylic/allylic 2° ok) | Methyl > 1° > 2° (not 3°) | 3° >> 2° | 3° > 2° > 1° |
| **Nucleophile/Base Needed** | Weak Nu (H₂O, ROH) | Strong, polarizable Nu (I⁻, CN⁻, RS⁻, RO⁻) | Weak base (H₂O, ROH) | Strong base (NaOH, NaOEt, NaOtBu, DBU) |
| **Best Solvent** | Polar protic (H₂O, ROH) | Polar aprotic (DMSO, DMF, acetone) | Polar protic (H₂O, ROH) | Polar aprotic or protic (high conc. base) |
| **Temperature** | Low–moderate | Low–moderate | High favors E1 over SN1 | High favors E2 over SN2 |

---

## Decision Guide

Use the following flowchart of questions to determine which mechanism applies. Work through the questions in order.

```
START
  │
  ▼
Q1. What is the substrate class?
  ├─ Methyl (CH₃-X) ──────────────────────────────► SN2 only
  │
  ├─ Primary (1°, RCH₂-X)
  │     │
  │     ▼
  │   Q2. Is the nucleophile/base strong?
  │     ├─ Strong Nu, polar aprotic solvent ────────► SN2
  │     ├─ Strong, bulky base + high temp ──────────► E2
  │     └─ Weak Nu, polar protic ─────────────────── SN2 (slow) or SN1 (rare)
  │
  ├─ Secondary (2°, R₂CH-X)
  │     │
  │     ▼
  │   Q2. Is the nucleophile/base strong?
  │     ├─ Strong Nu, polar aprotic ──────────────── SN2 (or E2 competes)
  │     ├─ Strong, bulky base + high temp ──────────► E2
  │     ├─ Weak Nu, polar protic, low temp ─────────► SN1
  │     └─ Weak base, polar protic, high temp ──────► E1
  │
  └─ Tertiary (3°, R₃C-X)
        │
        ▼
      Q2. Is the nucleophile/base strong?
        ├─ Strong, bulky base + high temp ──────────► E2
        ├─ Strong base, low/mod temp ────────────────► E2 (SN2 blocked by steric)
        ├─ Weak Nu, polar protic, low temp ─────────► SN1
        └─ Weak base, polar protic, high temp ───────► E1
```

### Quick Rules of Thumb

1. **Methyl or 1° + strong Nu + polar aprotic** → **SN2**
2. **3° + weak Nu + polar protic + low temp** → **SN1**
3. **3° + weak base + polar protic + high temp** → **E1**
4. **Any substrate + strong base + high temp** → **E2** (3° and 2° especially)
5. **Bulky base (tBuOK)** → **E2 Hofmann product** (less substituted alkene)
6. **SN2 is blocked at 3°** — if you see 3° + strong Nu, expect **E2** instead
7. **SN1 and E1 always compete** (same carbocation intermediate); temperature tips the balance

---

## Key Vocabulary

**Carbocation**
: A carbon atom bearing a formal positive charge with only three bonds and an empty p orbital. It is sp² hybridized and planar. Stability order: 3° > 2° > 1° > methyl. Resonance-stabilized (benzylic, allylic) carbocations are especially stable. Carbocations are the key intermediate in SN1 and E1 reactions.

**Leaving Group (LG)**
: An atom or group that departs with the bonding electron pair during substitution or elimination. Good leaving groups are stable as anions (weak conjugate bases of strong acids). Reactivity order: I⁻ > Br⁻ > Cl⁻ >> F⁻; also OTs⁻ (tosylate) and OTf⁻ (triflate) are excellent LGs. Poor leaving groups: OH⁻, OR⁻, NH₂⁻ (must be activated, e.g., OH protonated to OH₂⁺).

**Nucleophile (Nu)**
: An electron-rich species that donates an electron pair to an electrophile. Nucleophiles attack electrophilic carbon centers. Strong nucleophiles (I⁻, CN⁻, RS⁻, RO⁻) are essential for SN2. Nucleophilicity correlates with polarizability (larger atoms are better nucleophiles in protic solvents) and charge (anions > neutral species).

**Electrophile**
: An electron-poor species that accepts an electron pair from a nucleophile. In SN1/SN2/E1/E2 chemistry, the α-carbon bearing the leaving group is the electrophilic center. Carbocations are strong electrophiles.

**Walden Inversion**
: The complete inversion of stereochemical configuration at a tetrahedral carbon center that occurs during an SN2 reaction. The backside attack of the nucleophile inverts all three substituents like an umbrella flipping in the wind. An (R)-configured substrate becomes an (S)-configured product, and vice versa.

**Anti-Periplanar**
: A geometric arrangement in which two atoms or groups on adjacent carbons have a dihedral angle of exactly 180°, placing them in the same plane on opposite sides. In E2 elimination, the β-hydrogen and the leaving group must be anti-periplanar for the concerted mechanism to occur. In cyclohexane rings, this requires both groups to be in the diaxial conformation.

**Zaitsev's Rule**
: The empirical rule (formulated by Alexander Zaitsev) that predicts the major alkene product of an elimination reaction is the **more substituted** (more stable, more highly substituted double bond) alkene. Applies when a small, non-bulky base is used in E2 or in E1 reactions. Example: 2-bromobutane + KOH → 2-butene (major, Zaitsev) + 1-butene (minor).

**Hofmann Product**
: The **less substituted** alkene formed as the major product when a **bulky base** (e.g., potassium tert-butoxide, KOtBu) is used in an E2 elimination. Steric hindrance prevents the bulky base from accessing the more hindered β-hydrogen, so it abstracts the less hindered β-H to give the less substituted alkene. This is the opposite of Zaitsev selectivity.

**Polar Protic Solvent**
: A solvent that is both polar (has a significant dipole moment) and contains O–H or N–H bonds capable of hydrogen bonding. Examples: water (H₂O), methanol (MeOH), ethanol (EtOH), isopropanol (iPrOH), acetic acid (AcOH). Polar protic solvents stabilize ions through hydrogen bonding and solvation, favoring SN1 and E1 by stabilizing the carbocation intermediate and the departing anion. They **slow SN2** by solvating (caging) the nucleophile.

**Polar Aprotic Solvent**
: A polar solvent that lacks O–H or N–H bonds and therefore cannot donate hydrogen bonds. Examples: DMSO (dimethyl sulfoxide), DMF (dimethylformamide), acetone, acetonitrile (MeCN), HMPA. These solvents dissolve ionic reagents (allowing dissociation) but do not solvate anions strongly, leaving nucleophiles "naked" and highly reactive. Ideal for **SN2** reactions; also used in **E2**.

---

## See Also — Individual Mechanism Pages

- [SN1 — Unimolecular Nucleophilic Substitution](sn1.md)
- [SN2 — Bimolecular Nucleophilic Substitution](sn2.md)
- [E1 — Unimolecular Elimination](e1.md)
- [E2 — Bimolecular Elimination](e2.md)

---

*Wiki maintained as part of the Organic Chemistry LLM Wiki & Learning Hub project. All content is grounded in standard Clayden/McMurry/Wade-level organic chemistry pedagogy.*
