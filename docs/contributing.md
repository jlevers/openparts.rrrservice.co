# Contributing to OpenParts

OpenParts is built by people who actually work on machines. If you've got parts knowledge — OEM numbers, cross-references, dimensions, rebuild tips — this is the place to share it.

## How to Contribute

### The GitHub Workflow

1. **Fork** the [OpenParts repo](https://github.com/triple-r-service/openparts)
2. **Create or edit** pages in the `docs/` folder
3. **Submit a pull request** — we'll review and merge

That's it. No special tooling required. The site is built with [MkDocs](https://www.mkdocs.org/) and all content is plain Markdown.

### Don't Want to Use Git?

No problem. Open an [issue](https://github.com/triple-r-service/openparts/issues) on the repo with your parts data and someone will format and add it. The knowledge is what matters.

---

## What Makes a Good Parts Entry

A useful parts entry includes as much of the following as you can provide:

### Required

- **OEM part number** — the manufacturer's original number
- **Component name** — what the part is, in plain language
- **Machine application** — what it fits (model, year range, serial number range if relevant)

### Strongly Recommended

- **Cross-reference numbers** — aftermarket equivalents (Sparex, ICP, etc.)
- **Dimensions** — OD, ID, thickness, thread sizes. Measured, not guessed.
- **Quantity needed** — per side, per machine, total
- **Material** — steel, sintered, brass, rubber, etc.

### Nice to Have

- **Rebuild vs. replace guidance** — can it be rebuilt? What's the seal kit number?
- **Cost estimates** — rough pricing so people can budget
- **Gotchas** — serial number break points, 2WD/4WD differences, common mistakes
- **Cross-application** — other models that use the same part

!!! tip "Measure it"
    If you've got the part in your hand, measure it. OD, ID, thickness, thread pitch. Dimensions are the most valuable data for sourcing alternates — they're what let someone find a replacement when the OEM number is discontinued.

---

## Page Structure

Follow this directory structure:

```
docs/machines/{type}/{manufacturer}/{model}/{system}.md
```

**Examples:**

- `docs/machines/tractors/massey-ferguson/362/brakes.md`
- `docs/machines/tractors/john-deere/4020/hydraulics.md`
- `docs/machines/skid-steers/bobcat/s250/engine.md`

Each model should have an `index.md` overview page listing what systems are documented.

---

## Formatting Guidelines

### Use Tables for Parts Data

```markdown
| Specification | Value |
|---|---|
| **OEM Part Number** | 1860964M2 |
| **Alternate OEM** | 1669474M1 |
| **Outside Diameter** | 223mm (8.779") |
```

### Use Admonitions for Warnings and Tips

```markdown
!!! warning "Check your serial number"
    Disc count changed at S/N B33001.

!!! tip "Rebuild first"
    The actuator housing rarely fails. Replace balls and springs only.
```

### Include Both Metric and Imperial

Most older machines mix metric and imperial hardware. Include both where possible:

```
223mm (8.779")
```

### Cross-Reference Tables

When a part has equivalents across manufacturers, use a cross-reference table:

```markdown
| Component | MF OEM | Sparex | Case/DB | Leyland | Valmet |
|---|---|---|---|---|---|
| Friction disc | 1860964M2 | S.40486 | — | — | — |
```

---

## Data Accuracy

- **Only submit data you can verify.** Don't copy-paste from random forums without checking.
- **Note your source** if it's from a parts book, manual, or catalog — it helps others verify.
- **Flag uncertainty.** If you're not 100% sure, say so: "Believed to interchange — verify dimensions before ordering."
- **Measure when possible.** Calipers beat catalogs.

---

## License

All contributions are licensed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). By submitting, you agree that your contribution can be freely used, shared, and built upon — with attribution and under the same license.

This keeps the knowledge free and open. That's the whole point.
