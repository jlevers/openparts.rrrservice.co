# F10 528i (N20) — Exhaust Cam Failure & Oil Starvation

## Overview

The N20 2.0T has a well-documented failure mode: plastic timing chain guides degrade, drop chunks into the oil pan, clog the oil pickup screen, and starve the engine of oil. The exhaust camshaft is the first casualty — it's the farthest point from the oil pump in the oiling circuit and starves first.

**Symptoms:**

- Misfire codes on multiple cylinders
- Exhaust cam/crank correlation faults (BMW fault 130E20)
- Valvetronic faults (BMW fault 120408)
- Scored exhaust cam lobes and journals
- Exhaust rocker arms walking out of position or falling out entirely
- Rough idle, loss of power

!!! warning "Oil Change Intervals"
    BMW's original 15,000-mile oil change interval accelerated guide degradation on these engines. Use quality 5W-30 LL-01 spec oil and change every **5,000–7,000 miles**. This is the single most important preventive measure for the N20.

---

## How It Fails

The failure chain:

1. **Plastic timing chain guides degrade** — heat, age, and extended oil change intervals break down the guide material
2. **Chunks fall into the oil pan** — plastic debris settles to the bottom
3. **Oil pickup screen clogs** — even 30–50% blockage reduces oil flow enough to cause problems
4. **Oil pressure drops** — but not uniformly. Oil enters the head and reaches the intake cam first
5. **Exhaust cam starves** — it's the last component in the oiling circuit, highest in the head, farthest from the pump
6. **Cam journals score, lobes wear** — metal-on-metal contact destroys the bearing surfaces
7. **Rocker arms lose oil film** — they start walking, eventually pop out of position
8. **Misfire** — valves stop opening properly, you get codes and rough running

The fact that the exhaust cam is destroyed while the intake cam looks relatively OK is the signature of oil starvation from below — not a lubrication defect in the head.

---

## Investigation Checklist

Before ordering parts beyond the obvious, **drop the oil pan and see what's in there.** What you find determines how deep this job goes.

### Oil Pan & Pickup

- [ ] Drop oil pan — look for plastic guide debris and metal shavings
- [ ] Pull oil pickup tube and inspect screen for blockage
- [ ] Replace pickup tube O-ring regardless
- [ ] Clean pan spotless before reinstalling

### Cylinder Head — Exhaust Side

- [ ] Remove and inspect all exhaust rocker arms — check roller surfaces for flat spots and scoring
- [ ] Inspect all exhaust cam bearing journals (5 positions)
- [ ] Inspect exhaust cam bearing cap surfaces
- [ ] Inspect cam saddles in the head — if scored, head replacement or line boring required
- [ ] Check exhaust VANOS actuator for debris and sticking

### Cylinder Head — Intake Side

- [ ] Inspect intake cam journals — these should look better than exhaust
- [ ] If intake journals show scoring → starvation was severe, suspect bottom end damage
- [ ] Check intake rocker arms for wear

### Timing System

- [ ] Inspect chain guides — are they updated metal-backed or original plastic?
- [ ] Check chain tension/stretch
- [ ] Look for guide material in timing cover area

### Oil System & Bottom End

- [ ] Cut open oil filter — inspect for metal particles
- [ ] Check turbo shaft play (radial play > 0.05mm = bad)
- [ ] Measure oil pressure after reassembly: want 15+ PSI at hot idle, 40+ PSI at 3000 RPM

!!! tip "Document everything"
    Take photos of all findings — debris in pan, blocked pickup, scored journals. Save debris in a bag. If the car recently had timing chain or oil pan work done by another shop, this documentation may be needed to establish negligence.

---

## Parts

!!! warning "Verify all part numbers with your VIN"
    The N20 had multiple part number supersessions, especially for camshafts and VANOS components. Always verify against your specific VIN at [RealOEM.com](https://www.realoem.com/bmw/) before ordering.

### Must Replace

| Part | BMW Part # | Qty | Est. Price | Notes |
|---|---|---|---|---|
| Exhaust camshaft | Verify with VIN on RealOEM | 1 | $250–400 | See warning below about part number confusion |
| Exhaust rocker arms | 11337631589 / INA 4220226100 | 8 | $15–25 ea ($120–200) | Replace ALL exhaust rockers, not just failed ones |
| Oil pan gasket | 11137627512 | 1 | $25–40 | |
| Oil pickup tube O-ring | Source with pan gasket or separately | 1 | $5–10 | |
| Valve cover gasket | 11127588412 (verify) | 1 | $30–50 | |
| Oil filter | 11427953129 / Mann HU816x | 1 | $8–12 | Fresh filter after debris cleanup |

!!! warning "Exhaust Cam Part Number Confusion"
    ECS Tuning lists 11377630747 as "N20 Camshaft" — but that's the **Valvetronic eccentric shaft**, NOT the exhaust cam. These are completely different parts. Always verify the correct exhaust cam part number against your specific VIN on RealOEM.com, or call FCP Euro with your VIN.

### Strongly Recommended

| Part | BMW Part # | Qty | Est. Price | Notes |
|---|---|---|---|---|
| VANOS solenoid (exhaust) | 11367593719 | 1 | $60–90 | Same part for intake and exhaust. Cheap insurance. |
| Exhaust VANOS actuator | 11367583820 (verify) | 1 | $150–250 | If cam was starved, this probably was too |
| Oil filter housing gasket | 11427537293 | 1 | $15–25 | Common N20 leak point, and you're right there |
| Cam position sensor (exhaust) | 13627588095 (verify) | 1 | $30–50 | If contaminated by debris |

### Inspect and Decide

| Part | Est. Price | When to Replace |
|---|---|---|
| Timing chain kit (chain + guides + tensioner) | $300–500 | If you don't trust the previous shop's work, or guides are original plastic |
| Intake rocker arms (×8) | $120–200 | Only if intake cam shows scoring |
| Intake camshaft | $250–400 | Only if intake journals are scored |
| Turbo oil feed/return lines | $40–80 | If starvation was prolonged — check turbo shaft play first |
| Cam bearing caps | Varies (dealer) | If cap bearing surfaces are scored |
| Cylinder head | $800–2,000+ (used) | Nuclear option — only if cam saddles in head are scored beyond saving |

---

## Cross-Application

These part numbers apply across all N20/N26 engines:

- F10 528i / 528i xDrive
- F30 320i / 328i / 328i xDrive
- F31/F32/F33/F34/F36 28i variants
- F22/F23 228i
- E84 X1 sDrive28i / xDrive28i
- F25 X3 sDrive28i / xDrive28i
- F26 X4 xDrive28i
- E89 Z4 sDrive28i

---

## Suppliers

| Supplier | Location | Why |
|---|---|---|
| **FCP Euro** | Milford, CT | **Lifetime replacement guarantee on all parts.** Free shipping over $49. Best choice for a job this size. |
| ECS Tuning | Wadsworth, OH | Good N20-specific kits, large inventory |
| Turner Motorsport | Amesbury, MA | Quality OEM/Genuine BMW parts |
| RealOEM.com | — | Free BMW parts catalog. **Always verify part numbers here with your VIN.** |

---

## Cost Estimate

| Scenario | Est. Cost |
|---|---|
| Minimum (cam + rockers + gaskets + oil) | $440–710 |
| Recommended (+ VANOS + sensors) | $700–1,125 |
| Full (+ timing chain kit) | $1,000–1,625 |
| Worst case (head replacement) | $1,800–3,600+ |

!!! tip "FCP Euro lifetime guarantee"
    FCP Euro's lifetime replacement guarantee means if any of these parts fail later, you get a free replacement. Worth the slightly higher price over eBay or Amazon for a job this expensive.
