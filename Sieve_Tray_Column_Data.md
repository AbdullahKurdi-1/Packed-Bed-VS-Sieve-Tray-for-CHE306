# Sieve Tray Distillation Column – HYSYS Simulation Data (T-100 / COL1)
**Fluid Package:** Basis-1 / NRTL – Ideal  
**System:** Ethanol–Water Distillation

---

## 1. Column Configuration (Design > Connections)

| Parameter | Value |
|---|---|
| Column Name | T-100 |
| Sub-Flowsheet Tag | COL1 |
| Condenser Type | Total |
| Number of Stages (n) | 19 |
| P condenser | 101.3 kPa |
| P reboiler | 101.3 kPa |
| Feed Stream | Feed → Stage 17_Main Tower |
| Condenser Energy Stream | Q-condenser |
| Reboiler Energy Stream | Q-Reboiler |
| Overhead Liquid Outlet | DISTILLATE |
| Bottoms Liquid Outlet | BOTTOMS |

---

## 2. Column Specifications (Design > Monitor)

| Specification | Specified Value | Current Value | Wt. Error | Active |
|---|---|---|---|---|
| Reflux Ratio | 2.000 | 2.000 | -0.0000 | Yes |
| Distillate Rate | 41.20 kgmole/h | 41.23 | 0.0008 | Yes |
| Reflux Rate | — | 82.46 | — | No |
| Btms Prod Rate | — | 58.77 | — | No |
| Comp Fraction | 0.9000 | 0.8344 | -1.0571 | Yes |

---

## 3. Material Streams

### Feed

| Property | Value |
|---|---|
| Vapour Fraction | 0.0000 |
| Temperature | 78.00 °C |
| Pressure | 101.3 kPa |
| Molar Flow | 100.0 kgmole/h |
| Mass Flow | 2924 kg/h |
| Std Ideal Liq Vol Flow | 3.398 m³/h |
| Molar Enthalpy | -2.764×10⁵ kJ/kgmole |
| Molar Entropy | 40.73 kJ/kgmole·°C |
| Heat Flow | -2.764×10⁷ kJ/h |

**Composition (Mole Fractions):**

| Component | Feed |
|---|---|
| H₂O | 0.6000 |
| Ethanol | 0.4000 |

---

### DISTILLATE

| Property | Value |
|---|---|
| Vapour Fraction | 0.0000 |
| Temperature | 78.17 °C |
| Pressure | 101.3 kPa |
| Molar Flow | 41.23 kgmole/h |
| Mass Flow | 1708 kg/h |
| Std Ideal Liq Vol Flow | 2.114 m³/h |
| Molar Enthalpy | -2.716×10⁵ kJ/kgmole |
| Molar Entropy | 56.52 kJ/kgmole·°C |
| Heat Flow | -1.120×10⁷ kJ/h |

**Composition (Mole Fractions – Liquid Phase):**

| Component | DISTILLATE |
|---|---|
| H₂O | 0.1656 |
| Ethanol | 0.8344 |

---

### BOTTOMS

| Property | Value |
|---|---|
| Vapour Fraction | 0.0000 |
| Temperature | 86.62 °C |
| Pressure | 101.3 kPa |
| Molar Flow | 58.77 kgmole/h |
| Mass Flow | 1216 kg/h |
| Std Ideal Liq Vol Flow | 1.284 m³/h |
| Molar Enthalpy | -2.791×10⁵ kJ/kgmole |
| Molar Entropy | 27.73 kJ/kgmole·°C |
| Heat Flow | -1.640×10⁷ kJ/h |

**Composition (Mole Fractions – Aqueous Phase):**

| Component | BOTTOMS |
|---|---|
| H₂O | 0.9048 |
| Ethanol | 0.0952 |

---

## 4. Energy Streams

| Stream | Heat Flow |
|---|---|
| Q-condenser | 4.828×10⁶ kJ/h |
| Q-Reboiler | 4.873×10⁶ kJ/h |

---

## 5. Stage Profiles (Parameters > Profiles)

| Stage | Stage Name | Pressure [kPa] | Temp [°C] | Net Liquid [kgmole/h] | Net Vapour [kgmole/h] |
|---|---|---|---|---|---|
| 0 | Condenser | 101.3 | 78.17 | 82.46 | 1.704×10⁻⁷ |
| 1 | 1_Main Tower | 101.3 | 78.21 | 82.36 | 123.7 |
| 2 | 2_Main Tower | 101.3 | 78.24 | 82.28 | 123.6 |
| 3 | 3_Main Tower | 101.3 | 78.28 | 82.20 | 123.5 |
| 4 | 4_Main Tower | 101.3 | 78.31 | 82.12 | 123.4 |
| 5 | 5_Main Tower | 101.3 | 78.35 | 82.05 | 123.3 |
| 6 | 6_Main Tower | 101.3 | 78.39 | 81.97 | 123.3 |
| 7 | 7_Main Tower | 101.3 | 78.43 | 81.90 | 123.2 |
| 8 | 8_Main Tower | 101.3 | 78.48 | 81.82 | 123.1 |
| 9 | 9_Main Tower | 101.3 | 78.53 | 81.73 | 123.1 |
| 10 | 10_Main Tower | 101.3 | 78.59 | 81.64 | 123.0 |
| 11 | 11_Main Tower | 101.3 | 78.66 | 81.54 | 122.9 |
| 12 | 12_Main Tower | 101.3 | 78.74 | 81.42 | 122.8 |
| 13 | 13_Main Tower | 101.3 | 78.85 | 81.28 | 122.6 |
| 14 | 14_Main Tower | 101.3 | 78.99 | 81.09 | 122.5 |
| 15 | 15_Main Tower | 101.3 | 79.20 | 80.85 | 122.3 |
| 16 | 16_Main Tower | 101.3 | 79.52 | 80.49 | 122.1 |
| 17 | 17_Main Tower | 101.3 | 80.10 | 181.2 | 121.7 |
| 18 | 18_Main Tower | 101.3 | 80.30 | 180.7 | 122.4 |
| 19 | 19_Main Tower | 101.3 | 81.23 | 178.8 | 122.0 |
| 20 | Reboiler | 101.3 | 86.62 | 58.77 | 120.0 |

---

## 6. Column Internals – Sieve Tray (Internals Tab)

| Parameter | Value |
|---|---|
| Active Internal | Internals-1 |
| Section | CS-1 |
| Start Stage | 1_Main Tower |
| End Stage | 19_Main Tower |
| Mode | Interactive Sizing |
| Internal Type | Trayed |
| Tray/Packing Type | Sieve |
| Number of Passes | 1 |
| Tray Spacing | 0.6096 m |
| Diameter | 0.8056 m |
| Include Static Vapor Head in Pressure Drop Calcs | Yes |
| Calculate Pressure Drop Across Sump | No |
| Liquid Residence Time | 60.00 seconds |
| Status | Internals calculations completed with errors (see hydraulic plot) |

---

## 7. Tower Sizing (Rating > Towers)

| Parameter | Value |
|---|---|
| Tower | Main Tower |
| Uniform Section | Yes |
| Internal Type | Sieve |
| Diameter | 1.500 m |
| Tray/Packed Space | 0.5500 m |
| Tray/Packed Volume | 0.9719 m³ |
| Hold Up | 8.836×10⁻² m³ |
| Weeping Factor | 1.000 |
| Tray Sizing Analysis for Costing | Internals-1@Main |

---

## 8. PF Specs (Worksheet > PF Specs)

| Parameter | Feed | DISTILLATE | BOTTOMS |
|---|---|---|---|
| Pressure Spec Active | No | No | No |
| Pressure [kPa] | 101.3 | 101.3 | 101.3 |
| Flow Spec Active | No | No | No |
| Flow Spec Basis | Molar Flow | Molar Flow | Molar Flow |
| Molar Flow [kgmole/h] | 100.0 | 41.23 | 58.77 |
| Mass Flow [kg/h] | 2924 | 1708 | 1216 |
| Std Ideal Liq Vol Flow [m³/h] | 3.398 | 2.114 | 1.284 |

---

## 9. Simulation Status

- **Converged:** Yes
- **Internals:** Calculations completed with errors (hydraulic plot required for details)
