# Enervit – Shopify E-shop (B2C + B2B)

> Nový e-shop pre značku Enervit (športová výživa). Agentura: Mime Digital. Platforma: Shopify (pending final rozhodnutie).

## Stav projektu

| Oblast | Status |
|--------|--------|
| Predimplementačná analýza | ⏳ Prebieha (Mime Digital) |
| Rozhodnutie Shopify vs Shoptet | ⏳ Čaká na analýzu |
| SEO analýza + kategórie | ⏳ TODO |
| Royal Bay separácia | ✅ Rozhodnuté (separátny e-shop) |
| B2B cenové úrovne | ⏳ Definovať |
| ERP integrácia (Pohoda) | ⏳ Middleware stratégia |

## Produktové rady

| Rada | Cieľovka | Kategória |
|------|----------|-----------|
| **Enervit** (klasik) | Bežný športovec | Gely, elektrolyty, tyčinky |
| **C2:1** (pro) | Profesionáli, závodníci | Glukóza:fruktóza, profi výživa |
| **Pure Pro** | Hybrid (atletika + fitness) | Proteíny, BCAčka, elektrolyty |

## Štruktúra repo

```
enervit-shopify/
├── README.md              ← tento súbor
├── TODO.md                ← mobilný task list (GitHub app)
├── seo/                   ← SEO analýzy, URL štruktúra, redirecty
├── products/              ← kategórie, cross-sell, produktové dáta
│   └── data/              ← CSV/JSON exporty
├── design/
│   └── html-mockups/      ← HTML makety kategórií
├── b2b/                   ← B2B špecifiká (cenníky, registrácia)
└── docs/
    └── meeting-summaries/ ← stručné zhrnutia z meetingov
```

## PACT kontext (lokálne v Cursor)

Strategické rozhodnutia, plné meeting transcripty, zmluvy a knowledge base sú v:
```
VitarSport2026/Projects/enervit-eshop/
```

Toto repo obsahuje len **pracovné artefakty** — veci na ktorých pracuje Claude Code a ktoré sú dostupné na mobile.
