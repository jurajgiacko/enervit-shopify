# Workflow: Ako pracovat s Enervit projektom

> Rovnaky princip ako Royal Bay — PACT drzi strategiu, Git repo drzi pracovne artefakty.

---

## Kde co zije

```
PACT (Cursor, lokalny disk)                 Git repo (GitHub → Claude Code + mobil)
─────────────────────────                    ─────────────────────────────────────────
VitarSport2026/Projects/                     github.com/jurajgiacko/enervit-shopify
  enervit-eshop/
  ├── ENERVIT-ESHOP.md   ←── projekt brief  ├── TODO.md  ←── mobilne tasky
  ├── 2026-02-24-*.md    ←── meetingy       ├── seo/     ←── SEO analyzy
  └── (buduci obsah)                        ├── products/ ←── kategorie, data
                                             ├── b2b/     ←── B2B ceniky, workflow
                                             ├── design/  ←── HTML makety
                                             └── docs/    ←── meeting summaries
```

**Pravidlo:** Citlive veci (zmluvy, plne transcripty, financie, B2B ceniky detail) → PACT. Pracovne artefakty (SEO, produkty, makety, tasky) → Git.

---

## Ked pride nahravka z PLAUD

1. Nahraj transkript do Cursora → meeting-coach spracuje → zapis do PACT
2. Povedz agentovi: "sync meeting do enervit git repo"
3. Agent vytvori summary v `docs/meeting-summaries/` + aktualizuje `TODO.md`
4. Na mobile vidis nove tasky v GitHub app

---

## Claude Code

Napoj na `jurajgiacko/enervit-shopify`. Moze robit:
- SEO keyword research pre sportovu vyzivu
- Navrh URL struktury
- HTML makety kategorii (rovnaky pristup ako Royal Bay planner)
- Produktovy katalog — mapovanie SKU, parametre
- Cross-sell/upsell strom

Nema pristup k: meeting transcriptom, zmluvam, B2B cenovym detailom v PACT.

---

## Suvisiace projekty

- **Royal Bay Shopify:** github.com/jurajgiacko/royalbay-shopify
- Rovnaka agentura (Mime Digital), zdielany Shopify developer
- Royal Bay = priorita #1, Enervit nasleduje
