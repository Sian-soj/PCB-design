# Your badge name

> Space Carnival 2026 — PCB Badge Design Competition entry.
> Competition guide: https://space-carnival-psi.vercel.app/badge/

**Designer(s):** your name(s), city, and a link to you (GitHub / Instagram / LinkedIn)

![Render or photo of the badge](images/render.png)

## The idea

What is your badge, and what does it do? One or two short paragraphs.

## Theme

How does it represent local maker culture: Kerala, Kochi, our communities, our language, our stories?

## How it works

- **Power:** 3 V coin cell / USB / other
- **Main parts:** e.g. 2 × RGB LED, CH552, 555 timer…
- **What happens when you power it:**

## Soldering experience

What does a first-timer solder, and roughly how long does it take? (Target: 15–20 minutes, through-hole recommended.)

## Checklist

- [ ] Board fits within 40 × 40 mm
- [ ] Total BOM under ₹50 per badge, including the PCB and battery (see `bom.csv`)
- [ ] Every BOM row has quantity, unit price at 300 units and a source link
- [ ] Manufacturable by Lion Circuits (checked against their capabilities)
- [ ] Schematic in `schematic/` (PDF + source files)
- [ ] Gerbers zipped in `gerber/`
- [ ] Render or photo in `images/`

**BOM total per badge:** ₹__

## Files

| Folder / file | What goes in it |
| --- | --- |
| `schematic/` | Schematic as PDF, plus the source files from your EDA tool (EasyEDA / KiCad / Fusion) |
| `gerber/` | A single zip of your Gerber and drill files, ready for Lion Circuits |
| `bom.csv` | One row per part: quantity, unit price at 300 units (₹) and a source link |
| `images/` | A 3D render or photo of the badge, front and back if you can |

## Submit

Push everything to this repo, keep it **public**, and submit the repo link on the TinkerHub app before **21 November 2026**.

Need an example? Last year's badge is laid out the same way: https://github.com/salmanfarisvp/space-carnival-badge-2025

## License

Pick an open license for your design (MIT, CERN-OHL or CC BY-SA are common for hardware) and add a `LICENSE` file.
