# Enervit Category Planner – Build Checklist

> Referenčný súbor: `html-mockups/royalbay-reference-planner.html`
> Cieľ: Vybudovať rovnaký interaktívny HTML planner pre Enervit, prispôsobený na športovú výživu.

---

## Čo Royal Bay planner obsahuje (a Enervit musí mať rovnako)

### 1. Interaktívny HTML planner (single-file, self-contained)
- [ ] Sidebar s kategóriami (Shopify collections) — drag & drop priradenie
- [ ] Product grid s kartami — každý produkt zobrazuje parametre, farby, ceny
- [ ] Tabs: All Products, Unassigned, Category Tree, Variant Strategy, Filter Preview, Shopify Setup, SEO & LLM Guide
- [ ] Search a filter podľa produktovej rady
- [ ] Export: JSON, CSV, Markdown, Download All

### 2. Dátová štruktúra (v `<script>`)
- [ ] `CATEGORIES` — Shopify collections s SEO title, description, H1, handle (URL)
  - Podľa typu produktu (gely, elektrolyty, tyčinky, proteíny, nápoje...)
  - Podľa aktivity (beh, cyklistika, fitness, trail, triatlon...)
  - Podľa fázy (pred/počas/po tréningu)
  - Podľa produktovej rady (Enervit / C2:1 / Pure Pro)
  - Špeciálne (outlet, novinky)
- [ ] `FILTER_SCHEMA` — parametrické filtre pre Shopify metafieldy
  - `custom.product_line` (Enervit, C2:1, Pure Pro)
  - `custom.product_type` (Gél, Tyčinka, Prášok, Tableta, Hotový nápoj)
  - `custom.activity` (Beh, Cyklistika, Fitness, Trail, Triatlon)
  - `custom.training_phase` (Pred, Počas, Po, Medzi tréningami)
  - `custom.flavor` (Pomaranč, Citron, Čokoláda, Vanilka...)
  - `option.size` (variant option — jednorazové, multipack, veľké balenie)
  - `option.flavor` (variant option)
  - `custom.features` (Doping-free, Vegan, Gluten-free, Lactose-free...)
- [ ] `PRODUCTS` — kompletný katalóg s:
  - `sku` — kód z aktuálneho e-shopu
  - `name` — pôvodný názov
  - `shopifyName` — optimalizovaný názov pre Shopify
  - `seoTitle` — SEO title tag
  - `llmDesc` — LLM-optimized description (pre AI search)
  - `categories` — priradené kolekcie
  - `params` — všetky metafieldy
  - `price`, `priceOld` — ceny
- [ ] `PRODUCT_RELATIONS` — cross-sell (related) a upsell (alternatives)
  - Cross-sell: komplementárne podľa fázy tréningu
  - Upsell: Enervit → C2:1 upgrade, single → multipack

### 3. UI features
- [ ] Stats bar (celkový počet produktov, priradené, nepriradené)
- [ ] Drag & drop produktov medzi kategóriami
- [ ] Product card: parametre, príchute, ceny, cross-sell/upsell vzťahy
- [ ] Category tree vizualizácia
- [ ] Shopify Setup tab — menu štruktúra, kolekcie, metafieldy
- [ ] SEO & LLM Guide tab — best practices

### 4. Vizuálny štýl
- [ ] Svetlý minimalistický theme (rovnaký ako Royal Bay)
- [ ] Color-coded produktové rady (Enervit = modrá, C2:1 = červená, Pure Pro = zelená)
- [ ] Responsive (mobile-friendly)

---

## Rozdiely oproti Royal Bay

| Aspect | Royal Bay | Enervit |
|--------|-----------|---------|
| Produkt | Kompresné oblečenie | Športová výživa |
| Variant | Farba + Veľkosť | Príchuť + Veľkosť balenia |
| Rady | Energy, Air, Extreme, Therapy... | Enervit, C2:1, Pure Pro |
| Filtre | Kompresia, Materiál, Medical | Fáza tréningu, Príchuť, Doping-free |
| Cross-sell | Podkolenky → Ponožky | Gél → Elektrolyt (tréningový set) |
| B2B | Nie | Áno (7 cenových úrovní) |
| Kolekcie | Na míru | Outlet (pred expiráciou) |

---

## Zdroje dát

- `seo/category-analysis.md` — navrhované kategórie a filtre
- `products/categories.md` — produktové rady a typy
- `b2b/pricing-tiers.md` — B2B cenové úrovne
- Aktuálny e-shop: enervit.cz (scrape produkty ak treba)
- Royal Bay referencia: `html-mockups/royalbay-reference-planner.html`
