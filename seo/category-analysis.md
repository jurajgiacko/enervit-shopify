# Enervit CZ — Kategórie, navigácia & SEO

> **Primárna navigácia: Product Type** (gely, tyčinky, nápoje…) — validované analýzou 8 konkurenčných značiek
> Sekundárna: tréningová fáza | Terciárna: brand
> Produkt žije vo viacerých kolekciách súčasne (typ + fáza + brand)

---

## Strategické rozhodnutia

- **Navigačná hierarchia (12.3.2026):** Product Type (primárna) → Training Phase (sekundárna) → Brand (terciárna)
  - Validované: Nutrend, Nduranz, SiS, MyProtein, GU Energy Labs, Maurten, enervit.com — všetky používajú Product Type ako primárnu navigáciu
- **3 produktové rady** vizuálne oddelené: Enervit Sport / C2:1 PRO / Pure-PRO
- **Obsahový web sa zlúči s e-shopom** → enervit.cz = e-shop
- **B2C + B2B na jednej platforme**, rovnaký sortiment, odlišný ceník
- **Multi-collection:** Produkt žije v kategórii podľa typu (gely) AJ v kolekcii podľa rady (C2:1 PRO) AJ vo fázovej kolekcii (během tréninku)

---

## Navigačná štruktúra (Shopify menu)

### Hlavné menu (mega menu)

```
PODLE TYPU (primární)        PODLE FÁZE (sekundární)    ZNAČKY (terciární)
├── Energetické gely         ├── Před tréninkem         ├── Enervit Sport
├── Energetické tyčinky      ├── Během tréninku         ├── C2:1 PRO
├── Nápoje & elektrolyty     ├── Po tréninku            └── Pure-PRO
├── Aminokyseliny & BCAA     └── Mezi tréninky
├── Proteíny                                            SPECIÁLNÍ
├── Regenerace                                          ├── Novinky
└── Doplňky & příslušenství                             ├── Outlet / Výpredaj
                                                        ├── Variety Kity
                                                        └── Doping-free
```

### Footer menu
```
O značce Enervit | Kontakt | Doprava a platba | Obchodní podmínky | GDPR | B2B registrace | Blog
```

---

## Kompletná štruktúra kolekcií (Shopify collections)

### A) Podľa typu produktu (hlavná navigácia)

| Collection | Handle (URL) | Produkty | SEO Title | Meta Description |
|---|---|---|---|---|
| Energetické gely | `/collections/gely` | Enervit Gel, Liquid Gel, Competition Gel, Carbo Gel C2:1, Carbo Jelly, Carbo Chews | Energetické gely \| Enervit — Sportovní výživa | Energetické gely od Enervit a C2:1 PRO. Rychlá energie pro běžce a cyklisty. 10% sleva pro registrované. |
| Energetické tyčinky | `/collections/tycinky` | Competition Bar, Performance Bar, Carbo Bar C2:1 | Energetické tyčinky \| Enervit | Sportovní tyčinky Enervit a C2:1 PRO. Energie na trénink i závod. |
| Nápoje & elektrolyty | `/collections/napoje` | Instant Sport Drink, Isocarb, Carbo Flow C2:1, Carbo Tablets | Sportovní nápoje a elektrolyty \| Enervit | Izotoniké nápoje a elektrolyty pro hydrataci při sportu. |
| Aminokyseliny & BCAA | `/collections/aminokyseliny` | BCAA 2:1:1, BCAA 4:1:1, Creatine, Glutamine, Instant Drink BCAA | Aminokyseliny a BCAA \| Enervit | BCAA, kreatin a glutamin pro sportovce. |
| Proteíny | `/collections/proteiny` | 100% Whey Isolate, Whey Protein, Plant Protein | Proteíny \| Pure-PRO by Enervit | Prémiové proteíny Pure-PRO. Syrovátkový i rostlinný protein. |
| Regenerace | `/collections/regenerace` | Recovery produkty, Magic Cherry | Regenerace po tréninku \| Enervit | Produkty pro zotavení po sportu. Recovery drinky a antioxidanty. |
| Doplňky & příslušenství | `/collections/doplnky` | Fľaše, shakery, imunitná podpora | Sportovní doplňky \| Enervit | Sportovní lahve, šejkry a doplňky výživy. |

### B) Podľa produktovej rady (brand kolekcie)

| Collection | Handle | Popis | Produkty |
|---|---|---|---|
| **Enervit Sport** | `/collections/enervit-sport` | Kompletná rada klasickej športovej výživy | Všetky Enervit Sport produkty (#8–#23) |
| **C2:1 PRO** | `/collections/c2-1-pro` | Premium endurance — 2:1 sacharidový pomer | Carbo Gel, Carbo Bar, Carbo Jelly, Carbo Chews, Carbo Tablets, Carbo Flow, Kit (#1–#7) |
| **Pure-PRO** | `/collections/pure-pro` | Proteíny a aminokyseliny pre fitness | Whey Isolate, Whey, Plant Protein, BCAA Drink (#24–#28) |
| **The Protein Deal** | `/collections/protein-deal` | Proteínové tyčinky — snack s vysokým obsahom bielkovín | Protein Deal (5 príchutí + mix) |

### C) Podľa fázy tréningu (occasion kolekcie)

| Collection | Handle | Produkty |
|---|---|---|
| Před tréninkem | `/collections/pred-treninkem` | Pre Sport, Carbo Flow, tyčinky, gely |
| Během tréninku | `/collections/behem-treninku` | Gely, Carbo Gel C2:1, elektrolyty, Carbo Chews |
| Po tréninku | `/collections/po-treninku` | Recovery, proteíny, BCAA, Magic Cherry |
| Mezi tréninky | `/collections/mezi-treninky` | Proteíny, BCAA, Creatine, Glutamine |

### D) Špeciálne kolekcie

| Collection | Handle | Pravidlá |
|---|---|---|
| Novinky | `/collections/novinky` | Tag: `new`, automaticky po 60 dní |
| Outlet / Výpredaj | `/collections/outlet` | Produkty 60 dní pred expiráciou, staré balenia |
| Doping-free | `/collections/doping-free` | Produkty s WADA certifikátom |
| Variety Kity | `/collections/variety-kity` | Všetky variety packs a kity |
| Bestsellery | `/collections/bestsellery` | Top 10 podľa predaja (manuálne) |

---

## Shopify Metafield schema (filtre)

| Filter | Metafield Key | Typ | Hodnoty | Zobrazenie |
|--------|---------------|-----|---------|------------|
| Produktová rada | `custom.product_line` | `single_line_text` | Enervit Sport, C2:1 PRO, Pure-PRO, The Protein Deal | Checkboxy |
| Typ produktu | `custom.product_type` | `single_line_text` | Gél, Tyčinka, Prášok, Tableta, Hotový nápoj, Želé, Shot, Kapsle | Checkboxy |
| Aktivita | `custom.activity` | `list.single_line_text` | Běh, Cyklistika, Fitness, Trail, Triatlon, Plavání | Checkboxy |
| Fáza tréningu | `custom.training_phase` | `list.single_line_text` | Před, Během, Po, Mezi tréninky | Checkboxy |
| Príchuť | `option.flavor` | variant option | Mango, Lime, Orange, Lemon, Cola, Tropical, Cocoa, Vanilla, Cranberry... | Swatche (farebné) |
| Veľkosť balenia | `option.size` | variant option | 1ks, 3ks, 6ks, 12ks, 24ks, Dóza, Kit | Dropdown |
| Vlastnosti | `custom.features` | `list.single_line_text` | Doping-free, Vegan, Gluten-free, Lactose-free, S kofeínom, Bez kofeínu | Checkboxy |
| Cena | `filter.price` | range | — | Range slider |
| Dostupnosť | `filter.availability` | boolean | — | Toggle |

### Indexovanie pravidlá

| Typ stránky | INDEX? | Canonical |
|---|---|---|
| Hlavná kategória (`/collections/gely`) | ✅ INDEX | self |
| Brand kolekcia (`/collections/c2-1-pro`) | ✅ INDEX | self |
| Fázová kolekcia (`/collections/pred-treninkem`) | ✅ INDEX | self |
| Filtrovaná URL (s parametrami) | ❌ NOINDEX | parent kolekcia |
| Paginácia (`?page=2`) | ❌ NOINDEX | page 1 |
| Variant URL | ❌ NOINDEX | master produkt |
| Outlet | ✅ INDEX | self |

---

## URL štruktúra

### Produkty
```
enervit.cz/products/{handle}
```
Príklady:
- `enervit.cz/products/carbo-gel-c2-1-pro` (C2:1 gél)
- `enervit.cz/products/competition-bar` (Enervit tyčinka)
- `enervit.cz/products/100-whey-protein-isolate` (Pure-PRO proteín)

### Kolekcie
```
enervit.cz/collections/{handle}
```

### 301 Redirecty
| Stará URL (aktuálny e-shop) | Nová URL (Shopify) |
|-----|-----|
| TODO — exportovať z aktuálneho e-shopu | TODO — namapovať |

---

## SEO kľúčové slová (CZ trh)

### Hlavné (vysoký objem)
- sportovní výživa
- energetické gely
- enervit gely
- enervit eshop / enervit obchod
- izotoniký nápoj
- proteinový prášek

### Long-tail (nižší konkurencia, vysoký intent)
- energetické gely na běh
- sportovní výživa pro cyklisty
- C2:1 gel enervit
- enervit gel mango
- BCAA pro sportovce
- protein po tréninku
- enervit cena / enervit akce / enervit sleva

### Brand
- enervit sport
- enervit c2:1 pro
- pure pro protein
- enervit competition bar

---

## Meta tagy — šablóny

### Kolekcie
```
Title: {Kategória} | Enervit — Sportovní výživa pro váš výkon
Description: {Kategória} od Enervit. Sportovní výživa pro běžce, cyklisty a fitness nadšence. Registrujte se a získejte 10% slevu. Doprava zdarma od {X} Kč.
H1: {Kategória}
```

### Produkty
```
Title: {Produkt} | {Rada} — Enervit (max 60 znakov)
Description: {Produkt} od {Rada}. {Hlavný benefit}. {Cena} Kč. Doprava zdarma od {X} Kč.
H1: {Produkt}
```

### LLM Description (pre AI search / GEO)
Každý produkt bude mať `llmDesc` — popis v prirodzenom jazyku:
```
"Carbo Gel C2:1 PRO je prémiový energetický gel od Enervit s patentovaným poměrem sacharidů 2:1
(maltodextrin:fruktóza) pro maximální absorpci energie během závodu. Ideální pro běh, cyklistiku
a triatlon. Dostupný v příchutích Mango, Lime, Orange. Doping-free certifikace."
```

---

## Cross-sell & Upsell mapa

> **Kompletná mapa (per-product):** viď `products/categories.md` — cross-sell a upsell pre všetkých ~49 produktov

### Princípy cross-sell

1. **Fázový flow:** Před → Během → Po → Mezi (zákazník vždy potrebuje ďalšiu fázu)
2. **Rovnaká rada:** C2:1 zákazníkovi ponúkaj C2:1, Enervit zákazníkovi Enervit
3. **Komplementárny typ:** Gél + nápoj + tyčinka + príslušenstvo
4. **Max 3–4 cross-sell produkty** na PDP

### Upsell sumár (Enervit → C2:1 PRO)

| Z (Enervit) | Na (C2:1 PRO) | Argument |
|---|---|---|
| Enervit Gel | Carbo Gel C2:1 | 2:1 sacharidový pomer, rýchlejšia absorpcia |
| Isotonic Drink | Isocarb C2:1 | Vyšší obsah sacharidov, pro formula |
| Competition Bar | Carbo Bar C2:1 | Premium endurance tyčinka |
| Enervit Láhev | Láhev C2:1 Elite | Pro-level fľaša |
| BCAA 2:1:1 | BCAA 4:1:1 | Vyšší pomer leucínu |
| Protein Bar 26% | Protein Bar 50% | Dvojnásobný obsah proteínu |
| 1ks | Multi-pack (24ks) | Lepšia cena za kus |

### Tréningové sety (Shopify Bundles / content)

| Set | Produkty | Pre koho |
|---|---|---|
| **Běžecký balíček** | Carbo Gel C2:1 + Isocarb C2:1 + R2 Recovery | Maratónci, trail |
| **Cyklo balíček** | Carbo Bar C2:1 + Carbo Gel C2:1 + Isocarb + C2:1 láhev | Dlhé výjazdy |
| **Fitness balíček** | Whey Protein + BCAA + Creatine + Shaker | Svalová hmota |
| **Závodní balíček** | C2:1 celá řada (sada) | Pro závodníci |
| **Protein snack balíček** | Protein Deal Mix + Protein Bar 50% + Protein Bar 26% | Snack lovers |
