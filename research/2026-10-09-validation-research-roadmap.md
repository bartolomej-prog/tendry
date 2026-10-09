# Endpaper — kompletní plán validace českého trhu tendrů

**9. 10. 2026 | Rozhodovací roadmap | fáze VALIDACE, nikoliv product build.**  
**Vstup:** `2026-10-09-cz-tender-market-landscape.md`, `2026-10-09-competition-voice-of-customer.md`.  
**Princip:** testovat vyvratitelné hypotézy, žádný těžký scoring firem, kvalifikované firmy oslovit všechny. Oddělovat veřejné a soukromé tendry, dodavatele a zadavatele, fakta a domněnky.

## 0. Kde jsme

Máme desk research makroobjemu veřejných zakázek, popis procesu, orientační oborové rozložení, mapu české/zahraniční konkurence a jednotlivé zahraniční VOC signály. **Nemáme:** českou reprezentativní evidenci demandu, bottom-up TAM, živý datový benchmark, skutečnou ochotu platit, product usage data, přístup k interním bid workflow, ekonomiku dat, ověřené soukromé RFP ani pilotní ROI. ICT beachhead je hypotéza.

## 1. Prioritizované workstreamy (nečekat na dokončení všech)

| Priorita | Workstream | Konkrétní výstup | Akceptační kritérium | Závislost |
|---|---|---|---|---|
| **P0** | 15–20 buyer/user discovery rozhovorů | anonymizované záznamy, workflow mapy, výčet skutečných ztrát času/peněz, používané nástroje | alespoň 10 ICP ICT + 5 cross-vertical, každý ukáže poslední konkrétní tender; oddělit uživatele/kupující | kontakty a svolení |
| **P0** | Data market census 2024–2026 | deduplikované zakázky, hodnoty, CPV, zadavatelé, vítězové, četnost, segmentace | měřit coverage, data dictionary, definice unikátní zakázky, vyznačit chybějící VZMR a private | VVZ/TED/NEN/profily, registr smluv |
| **P0** | Konkurence hands-on | 5–7 skutečných demo/trial testů včetně Zakázky GOV | společný kontrolní dataset a srovnatelné metriky, screen evidence | testovací dataset |
| **P0** | ICP universe + bottom-up SAM | seznam aktivních větších dodavatelů podle IČO, oboru, účasti, týmu a spendu | doložené počty firem, duplicity skupin odstraněny, bez pseudo scoringu | market census + rozhovory |
| **P0** | Cena a budget owner | 8–12 cenových rozhovorů + 3–5 skutečných nabídek konkurence | ACV range, buyer, rozpočet, procurement proces, placený pilot nebo konkrétní LOI | discovery |
| **P1** | Shadowing 5 bid týmů | end-to-end časový rozpad 5–10 reálných tenderů | čas, ztráty, náklady, důvody no-bid, dokumentové chyby | design partners |
| **P1** | Pre-tender intelligence data feasibility | 30–50 historických obnovení smluv, spárování buyer/winner/contract | recall a precision renewal prediction; zda lze legálně a ekonomicky provozovat | data map |
| **P1** | Private tenders parallel track | 8–10 rozhovorů s privátními dodavateli / procurement týmy | kde vznikají invitation-only RFP, přístupová práva, hodnoty a workflow | kontakty |
| **P1** | EU expandability / legislation | SK/PL/DE/AT data source map, cross-border zákazníci, compliance | odlišit CZ-only value od EU edge; smluvní práva k datům | potvrzení CZ wedge |
| **P1** | Security + integration feasibility | minimální enterprise data architecture a risk register | CRM/Teams/SharePoint, SSO, audit, GDPR, retenční doby, zákaznické dokumenty | 2 design partners |
| **P1** | Concierge pilot 2–3 design partners | Tender Decision Brief na reálných případech, před/po metriky | měřit baseline, opakované používání, explicitní pokračování | P0 discovery + data |
| **P2** | Economics / distribution / sales | CAC assumptions, sales cycle, channel map, customer support cost | konzervativní scénáře, žádné vymyšlené forecasty | WTP + pilot |
| **P2** | Decision memo a go/no-go | explicitní rozhodnutí, segment, value prop, build scope | evidence-backed, uvedené alternativy a kill conditions | P0/P1 |

## 2. Workstream A — detailní datová analýza trhu

**Zdroje:** ISVZ/VVZ a otevřená data MMR, TED API/datasets, NEN, E-ZAK/Tender arena/TENDERMARKET a profily zadavatelů, registr smluv, rozpočty, výroční zprávy zadavatelů, ČSÚ a justice pro firmografii. Zvlášť mapovat právní/technická omezení stahování. Nedeklarovat úplnost.

**Schema:** stable tender ID, source ID, event type (notice, award, correction, cancellation), timestamp, CPV primary + additional, NUTS, buyer IČO, supplier IČO, value + VAT + currency, framework/lot, documents version, submission deadline, contract links. Deduplikace podle IDs a vztahů mezi oznámeními; transparentní evidence nerozpoznaných duplicit.

**Analýzy:** 2024–2026 posledních 24 měsíců a trend; počet *unikátních* příležitostí vs. oznámení; hodnoty a mediány dle CPV a buyer segmentu; četnost obnovení a rámcových smluv; 20 největších buyerů po vertikálách; winner concentration; podíl single-bid, výskyt price-only, časy na nabídku, počet změn zadání; mapa datových mezer. Rozlišit award-only dataset (nemá neúspěšné uchazeče) od participant data.

**Klíčové otázky:** Kolik potenciálních ICT tendrů ročně? Kolik aktivních větších ICT dodavatelů? Kolik se jich účastní opakovaně? Jaký podíl příležitostí má smysl řešit mimo vztahové kanály? Jaké dokumenty jsou opravdu dostupné?

## 3. Workstream B — skutečné customer discovery

**Rozdělení 20 interview:** 10–12 ICT bid/sales leaders, 3–4 zdravotnická technika, 3–4 inženýring, 2–3 další enterprise dodavatelé (počty flexibilní). U každé firmy mluvit s user a economic buyer, pokud to jde. Nepřesvědčovat; zjišťovat minulost.

**Záznam (1 řádek/rozhovor):** segment, velikost týmu, tendry/rok, veřejné/private, hodnoty, discovery channels, nástroje a ceny, posledních 5 bidů, win/no-bid, hodiny podle kroku, přehmaty, kritické překážky, buyer/budget, WTP evidence, citace se souhlasem, protiargumenty, odkazy na ukázky.

**Základní otázky:** Jak jste objevili posledních pět tendrů? Ukažte poslední odmítnutý bid a proč. Co trvá nejdéle? Kolik vás stojí bid/no-bid? Jaké nástroje používáte, co děláte ručně navíc? Co dnes zdarma pokrývá Zakázky GOV? Kdo podepisuje licenci? Co by muselo nastat, aby tým změnil workflow? Jakou informaci byste chtěli mít 3 měsíce před vyhlášením? Ukažte minulou chybu či zmeškaný termín.

**Evidence:** „To by bylo hezké“ není purchase signal. Silnější důkaz: minulý placený workaround, konkrétní náklad, rozpočet, přístup k pilotu, LOI se závazkem, placený pilot.

## 4. Workstream C — konkurenční benchmark

**Testovat:** Zakázky GOV (free baseline), Tenderpool, Datlab, NENDE, dZakazky, Apertia + vybraný zahraniční vzor. **100–200 originálních zadání** rozdělených do ICP CPV a portálů. Zkontrolovat úplnost, latency, precision/recall relevance, zdrojové citace, false negatives, chybějící přílohy, změny a impact, práci týmu, API/SSO, skutečnou cenu a licenční podmínky. Marketingové údaje zapsat jako claims; ne jako naměřené výsledky.

**Konkurence zahraniční:** Stotles, Mercell, GovWin IQ, Loopio, Responsive. Ověřit nejen feature list, ale i monetizaci, onboarding, team adoption, data acquisition, analyst cost a reálné výsledky.

## 5. Workstream D — private RFP / hybrid enterprise

Samostatná výzkumná větev: u Publicis a dalších korporací zjistit **obě role** — jak firma nakupuje jako zadavatel a jak soutěží jako dodavatel. Zjistit podíl neveřejných RFP, zda lze na základě zákazníkova souhlasu zpracovávat pozvánky/dokumenty a jaký je proces schvalování. Nevydávat private za další veřejný scraping TAM. Možný alternativní produkt: internal RFP response copilot bez public discovery.

## 6. Workstream E — pilot a ekonomika hodnoty

**Concierge MVP:** ručně/poloautomaticky zpracovat u 2–3 design partnerů 5–10 živých zakázek/partner; pro každou dát Tender Decision Brief: relevantnost, kvalifikační check, změny, zdrojové odkazy, incumbent, další úkoly. Měřit původní baseline vs. výsledek a zaznamenat každý faktický omyl.

**Navrhované (neověřené) úspěšné prahy:** ≥95 % recall známých relevantních příležitostí na vymezeném vzorku; ≥30 % snížení času prvotní kvalifikace; 100 % zásadních tvrzení s dohledatelným zdrojem; nula kriticky přehlédnutých změn v testovacím souboru; ≥2 konkrétní závazky ke komerčnímu pokračování. U malých vzorků uvádět interval nejistoty a neslibovat absolutní bezpečnost.

**WTP:** oddělit free trial, LOI, paid pilot a podepsanou licenci. Pokud je design partner „free forever“, explicitně smluvně zajistit data, pravidelné interview, product access, benchmark, referenci, čas bid týmu a právo využít agregované výsledky; z jiných firem ověřit cenu.

## 7. Go/no-go (návrh, musí schválit tým)

**GO / pokračovat do omezeného build:** ≥10 důkazně silných interview v jednom segmentu, opakovaná ekonomická bolest a existující budget; product benchmark proti bezplatné státní nabídce; datové zdroje legální a dostatečné; 2–3 pilotní firmy, ≥2 ochotné k placenému pokračování nebo silné závazné alternativě.

**PIVOT:** pain je reálný, ale u jiného segmentu; lepší privátní RFP než public discovery; kupující chce response workflow, nikoliv intelligence; data pro predikci obnov nejsou dost kvalitní.

**NO-GO / nepouštět full build:** zákazníci preferují existující zdarma/levné produkty bez významného workaroundu; nelze dosáhnout bezpečné přesnosti/aktuálnosti; data licence prohibitivní; ekonomický buyer nechce platit; složitá implementace převyšuje očekávané ACV.

## 8. Doporučená 6týdenní sekvence (orientační, paralelní)

- **Týden 1:** 30–40 cílových firem pro oslovení (ne score), 10 rozhovorů nasmlouvat; data dictionary + zdrojový audit; trial/demo konkurence.
- **Týden 2:** prvních 8–10 interview, mapa workflow, první dataset; 20–30 benchmark zakázek; upravit ICP hypotézu.
- **Týden 3:** dalších 8–10 interview, segmentová komparace, rozpočet a cenové nabídky, rozšíření benchmarku na 100+ případů.
- **Týden 4:** bottom-up SAM, identifikace 2–3 pilotů, souhlas k práci s dokumenty, předběžná data feasibility a privacy review.
- **Týden 5:** concierge pilot na reálných tendrech, měřit baseline, evidence chyb, shadowing a integrace.
- **Týden 6:** vyhodnotit pilot, cenu, adoption, datovou ekonomiku, připravit decision memo a explicitní go/pivot/no-go.

**Upozornění:** V 6 týdnech nelze garantovat kompletní výsledek u dlouhých tender cyklů; skutečný win-rate a obnovy smluv mohou vyžadovat delší longitudinální sledování. Časový plán je pro rozhodnutí o dalším investování, nikoliv potvrzení product-market fit.

## 9. Co má být na GitHubu jako evidence

`research/data-sources-register.csv` (zdroj, coverage, licence, dostupnost, update), `research/competitor-benchmark.csv` (nástroj, test, důkaz, výsledek), `research/market-census/` (data dictionary, notebooky, dedup log), `validation/interviews/` (anonymizované zápisy, consent), `validation/hypotheses.md`, `validation/pilot-metrics.csv`, `validation/decision-memo.md`. **Neukládat interní nabídky a citlivé zákaznické dokumenty do veřejného repozitáře**; zde jsou pouze anonymizované agregace a odkazy na bezpečné úložiště.

## 10. Priority v jedné větě

**Nejdřív česká zákaznická bolest + datová realita + konkurenční benchmark + ochota platit; teprve pak plnohodnotný build.** Rozšiřování do EU a privátních RFP může běžet jako průzkum, ale nesmí rozmělňovat první wedge.
