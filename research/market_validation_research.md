# Validace trhu pro tendry v ČR — Deep Research Report

*Vytvořeno: 2026-10-01*

## 1. CO FAKT FUNGUJE (osvědčené taktiky)

### Mom Test — Zlaté pravidlo rozhovorů
- **Neptej se na budoucnost** ("Líbilo by se ti...?") — každý řekne ano
- **Ptej se na minulost**: "Kdy naposledy jsi hledal zakázku? Co jsi udělal? Kolik času ti to zabralo?"
- **Hledej commitment**: Intro k dalšímu člověku, čas na demo, předplatné — ne "super nápad!"

### MVT místo MVP
- **Minimum Viable Test** = testuj jednu hypotézu, ne celý produkt
- Maven prodával kurzy za $150K+ před buildem softwaru
- **Pro tebe**: Landing page s "upozornit mě na relevantní zakázky" → měř konverze PŘED vývojem

### Constraint strategy
- **Začni úzce**: Rover = jen Seattle, Airbnb = jen vybrané města, Etsy = jen 3 kategorie
- **Pro tebe**: Vyber jeden segment (např. IT zakázky pro obce, nebo stavební zakázky nad 10M) a validuj tam

### Sean Ellis PMF test
- "Jak bys se cítil, kdybys nemohl používat [produkt]?"
- **40%+ "very disappointed" = product-market fit**
- Minimum 40 respondentů pro směrodatnost

---

## 2. CO NEFUNGUJE (časté chyby)

| Chyba | Proč nefunguje |
|-------|----------------|
| "Všichni říkají, že je to super" | Komplimenty ≠ validace. Hledej peníze/čas |
| Hypotetické otázky | "Koupil bys...?" → lži. Ptej se na minulost |
| Měsíce vývoje bez zákazníků | Build-Measure-Learn cyklus co nejkratší |
| Cílení na všechny | Fragmentace = smrt. Jdi narrow → wide |
| Měření vanity metrics | Počet registrací ≠ platící zákazníci |

### Red flags že idea nefunguje
- Po 20 rozhovorech nenajdeš vzorec
- Nedokážeš definovat jednoduchou value proposition
- Trh advisorů/dodavatelů je příliš malý
- Ty sám nemáš passion to exekutovat

---

## 3. SPECIFIKA B2G (veřejné zakázky)

### Kdo jsou hráči
1. **Zadavatelé** (24 536 v NEN) — ministerstva, obce, nemocnice, státní firmy
2. **Dodavatelé** (42 699 v NEN) — firmy soutěžící o zakázky
3. **Regulátoři** — MMR, ÚOHS

### Pain points pro validaci

| Segment | Bolesti |
|---------|---------|
| **Zadavatelé** | Administrativa, compliance, strach z korupčních nařčení, málo kvalitních nabídek |
| **Dodavatelé** | Složité najít relevantní zakázky, papírování, nejistota výsledku, dlouhé platby |

### Jak mluvit s úředníky
- **Nabídni hodnotu bez sales tlaku** — jsou konzervativní
- **Reference z jiných úřadů** — "používá to město XY"
- **Konference**: Fórum veřejných zakázek, e-government eventy
- **Cyklus**: 6-18 měsíců (procurement má 5 fází)

---

## 4. ČESKÝ TRH — Mapa

### Velikost
- **272 654 zakázek** za **2,16 bilionu Kč** (NEN)
- ~15% HDP jde přes veřejné zakázky

### Konkurence

| Platforma | Typ | Co dělá |
|-----------|-----|---------|
| **NEN** | Státní | Povinný nástroj, největší objem |
| **Věstník VZ** | Státní | Oficiální publikace |
| **Hlídač státu** | Neziskovka | 1,5M tendrů, freemium monitoring |
| **PROEBIZ** (Tenderbox, Josephine) | Komerční | CZ/SK/PL, od 2002 |
| **Tender Arena** | Komerční | E-nástroj pro zadavatele |

### Příležitosti
1. **Agregace** — fragmentace mezi platformami
2. **AI matching** — propojení zakázek s relevantními dodavateli
3. **Analytika** — predikce, benchmarking cen
4. **UX** — státní systémy mají hrozné UX

---

## 5. AKČNÍ PLÁN — Co udělat tento týden

### Fáze 1: Discovery (týden 1-2)
- [ ] **Stáhni data** z Hlídače státu a NEN — analyzuj vzorce
- [ ] **5 rozhovorů s dodavateli**: "Kdy naposledy jsi hledal zakázku? Jak? Co bylo nejtěžší?"
- [ ] **5 rozhovorů se zadavateli**: "Co je největší pain při vypisování zakázky?"

### Fáze 2: Hypotéza (týden 2-3)
- [ ] **Vyber segment**: např. "IT zakázky obcí do 50K obyvatel"
- [ ] **Definuj value prop**: jedna věta, jeden problém
- [ ] **Landing page**: "Upozorníme vás na relevantní zakázky" → sbírej e-maily

### Fáze 3: MVT (týden 3-4)
- [ ] **Manuální pilot**: Prvním 10 zájemcům posílej zakázky ručně
- [ ] **Měř engagement**: Otevírají? Odpovídají? Platili by?
- [ ] **Willingness to pay**: "Za kolik měsíčně by to mělo smysl?"

### Commitment test
> "Kdybych ti posílal relevantní zakázky každý týden, dal bys mi 500 Kč/měsíc?"
> Pokud ano → validace. Pokud "možná" → fake signal.

---

## 6. KLÍČOVÉ ZDROJE

**Knihy:**
- The Mom Test (Rob Fitzpatrick) — povinné čtení
- Running Lean (Ash Maurya) — Lean Canvas, MVT
- Lean Startup (Eric Ries) — Build-Measure-Learn

**Data:**
- nen.nipez.cz — oficiální data
- hlidacstatu.cz — 1,5M zakázek, API

**Inspirace:**
- Hlídač státu — co už existuje v ČR
- GovWin (Deltek) — US model pro B2G intelligence

---

## 7. GO-TO-MARKET STRATEGIE — Dodatečný výzkum

*Zdroje: Asana, HubSpot, ProductPlan, Lenny's Newsletter*

### Co je GTM strategie
Plán krok za krokem definující **co** prodáváš, **komu**, **kde** a **jak**. Aplikuje se při:
- Spuštění nového produktu
- Vstupu na nový trh
- Rozšíření stávající nabídky

### 9 kroků GTM strategie (Asana/HubSpot)

1. **Identifikace problému** — Jakou konkrétní potřebu řešíš?
2. **Definice cílové skupiny** — ICP (Ideal Customer Profile) + buyer personas
3. **Výzkum konkurence** — Kdo už to dělá? Jak se odlišíš?
4. **Klíčové sdělení** — Jedna věta value proposition pro každou personu
5. **Mapování cesty kupujícího** — Awareness → Consideration → Decision
6. **Volba kanálů** — Kde je tvoje cílovka? (LinkedIn, konference, cold email?)
7. **Prodejní model** — Self-service / Inside sales / Field sales / Partneři
8. **Konkrétní cíle** — SMART KPIs (CAC, LTV, konverze)
9. **Transparentní procesy** — Jasná komunikace v týmu

### 4 přístupy k GTM

| Přístup | Popis | Kdy použít |
|---------|-------|------------|
| **Sales-led** | Prodejci aktivně oslovují | B2B enterprise, vysoká cena |
| **Product-led** | Produkt se prodává sám (freemium, trial) | B2B SaaS, nízký onboarding |
| **Marketing-led** | Inbound content, SEO, ads | B2C, SMB |
| **Community-led** | Komunita jako distribuční kanál | Developer tools, niche |

### Jak získat prvních 1000 uživatelů (Lenny's Newsletter)

**7 osvědčených strategií z dat 100+ úspěšných startupů:**

1. **Fyzický přístup** — Tinder: zakladatelé chodili osobně na univerzity. DoorDash: letáky na Stanfordu
2. **Online komunity** — Dropbox: Hacker News. Buffer: 150 guest postů
3. **Pozvání přátel** — Facebook: 1500 uživatelů za 24h přes mailing list
4. **FOMO/Exkluzivita** — Clubhouse, Superhuman: invite-only čekací lista
5. **Influenceři** — Instagram: designéři s velkým Twitter following
6. **Mediální pokrytí** — Superhuman: článek přinesl 5000 signupů
7. **Předprodukční komunita** — Product Hunt začínal jako email newsletter

**Klíčové zjištění**: Nejúspěšnější startupy se zaměřily na **1-3 strategie**, ne na všechny.

### Specifika B2B GTM

- **Nákupní centrum**: 6-10 decision makerů s různými rolemi
- **Matice hodnot**: Propoj personu → její bolest → tvé řešení → zprávu
- **Delší cyklus**: Týdny až měsíce, proto vztahy > transakce
- **Retence**: 7× levnější prodávat stávajícím zákazníkům

### Časté GTM chyby

| Chyba | Důsledek |
|-------|----------|
| Neurčený ICP | Oslovuješ všechny = nikoho |
| Příliš široký launch | Rozředíš zdroje, žádná trakce |
| Ignorování konkurence | Překvapení, že trh je přesycený |
| Měření vanity metrics | Registrace ≠ platící zákazníci |
| Žádná diferenciace | "Proč ty a ne oni?" bez odpovědi |

---

## 8. APLIKACE NA TENDRY V ČR

### Tvůj GTM framework

**Problem-Market Fit otázky:**
- Kdo má největší bolest? Dodavatelé (hledání zakázek) nebo zadavatelé (administrativa)?
- Jak velká je ta bolest? Kolik času/peněz ztrácejí?
- Platí už za nějaké řešení? (Hlídač státu, PROEBIZ)

**ICP kandidáti:**

| Segment | Charakteristika | Potenciální value prop |
|---------|-----------------|------------------------|
| Malí dodavatelé IT | 1-10 zaměstnanců, soutěží o zakázky obcí | "Najdeme ti relevantní zakázky, ušetříš 5h/týden" |
| Střední stavební firmy | Soutěží o zakázky 10-50M Kč | "Predikce úspěšnosti, optimalizace nabídky" |
| Obce | Vypisují 5-20 zakázek ročně | "Compliance a administrativa na autopilotu" |

**Doporučený GTM přístup:**
1. **Product-led + Community-led hybrid**
2. Freemium monitoring jako vstupní bod
3. Premium features: AI matching, analytics, alerting
4. Komunita kolem veřejných zakázek (newsletter, webináře)

### Konkrétní první kroky

1. **Tento týden**: 5 rozhovorů s malými IT dodavateli
2. **Příští týden**: Landing page "Sledujte IT zakázky" → měř signupy
3. **Za 2 týdny**: Manuální pilot pro prvních 10 zájemců
4. **Za měsíc**: Vyhodnoť engagement a willingness to pay
