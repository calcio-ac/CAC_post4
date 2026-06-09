# CAC_post4 — Portugal: WC 2026 Squad Report

Calcio AC post #04. Complete 26-man squad analysis for Portugal at the FIFA World Cup 2026 (USA · Canada · Mexico, June–July 2026).

## The argument
- **Manager**: Roberto Martínez · **Formation**: 4-3-3
- **Recent**: UEFA Nations League 2025 Champions (Ronaldo Golden Boot at 40)
- **Verdict**: *Dark Horse → Genuine Contender*

Three story tensions:
1. **Best squad in 20 years** vs. **the Ronaldo minutes question (now 41)**
2. **PSG midfield + Mendes/Leão left flank** vs. **right-back depth question**
3. **Jota's loss as motivation** vs. **Jota's loss as tactical hole**

## Structure
```
CAC_post4/
├── data/
│   ├── Portugal_WC2026_Squad_Report.pdf   # source
│   └── squad.json                          # extracted player + meta data
├── web/
│   ├── index.html                          # interactive squad explorer
│   ├── slides.html                         # 10-slide carousel + HD export
│   └── logo.svg
├── images/                                 # exported slide PNGs go here
├── index.html                              # redirect to /web/
└── README.md
```

## Live site
Once Pages is enabled (Settings → Pages → main / root):
`https://calcio-ac.github.io/CAC_post4/`

## Interactive dashboard features
- Black ribbon banner across the top: *"IN MEMORY OF DIOGO JOTA · 1996 – 2025"*
- 4 KPI tiles (formation, NL 2025 trophy, player pool, verdict)
- **Predicted XI on a CSS pitch** — hover/tap any number for the player profile
- Strengths / Risks (green / red SWOT panels)
- **Full 26-man squad grid** — filterable by GK / DEF / MID / ATT / Predicted XI
- **Click-any-player modal** with full profile + "World Cup Impact"
- Verdict panel + standout black-bordered Jota tribute card

Player avatars are **initials in a colored circle** keyed by position (GK gold, DEF blue, MID green, ATT red).

## Slide deck (10 slides, 1080×1350)
1. COVER — "Dark Horse → Contender"
2. **THE PREDICTED XI** — pitch with all 11 names
3. **KEY STRENGTHS** — 4 stacked green boxes
4. **KEY RISKS** — 3 stacked red boxes
5. **THE LEFT SIDE** — Mendes + Leão profiles side-by-side
6. **THE MIDFIELD TRIO** — Vitinha · Bruno · Bernardo cards
7. **RONALDO AT 41** — NL Golden Boot + the minutes question
8. **IN MEMORIAM — DIOGO JOTA** — full black slide with gold accents (dedicated tribute)
9. **THE VERDICT** — "If Vitinha, Bruno, and Leão fire simultaneously…"
10. **CTA** — link to the interactive site

HD export per slide (2x/3x) + DOWNLOAD ALL.

## Palette / font (Portugal national team brand)
| Token | Hex | Pantone |
|---|---|---|
| RED   | `#E42518` | PMS 485 C |
| GREEN | `#0D6938` | PMS 349 C |
| GOLD  | `#D3C084` | PMS 616 C |
| BLACK | `#000000` | PMS Black 6 C |
| BLUE  | `#004595` | PMS 7687 C |

Font: **Courier New** (monospace) — CAC standard.

## Source
Portugal WC 2026 Squad Report (Calcio Analysis Company, June 2026). 11-page internal document covering all 26 players, predicted XI, strengths/risks, in-memoriam, and final verdict.
