# Česká a zahraniční konkurence, ceny, uživatelské recenze a produktové mezery

**Pro Endpaper · stav 9. 10. 2026 · desk research**  
**Doplňuje:** `2026-10-09-cz-tender-market-landscape.md`.  
**Legenda důkazů:** [F] státní/oficiální zdroj; [P] tvrzení výrobce (neznamená ověřenou funkčnost); [R] jednotlivé recenze uživatelů (selection bias); [H] naše hypotéza, čeká na přímý test.

## 1. Hlavní konkurenční závěr

Endpaper NEMŮŽE stavět USP na generickém AI vyhledávání, jednoduchých notifikacích, souhrnu dokumentace, CRM/webhook integracích ani samotné konkurentní analytice. Tyto funkce již nabízí stát nebo některý z českých hráčů. **Volná příležitost je hypoteticky v kvalitě a propojení funkcí do workflow konkrétního enterprise týmu**: kvalitní specifický bid/no-bid úsudek, předtendrové signály, firemní reference, historie incumbenta, auditovatelné doklady, kontinuální změny, reálné integrace a ROI. Bez přímých testů tvrdit „konkurence to neumí“ nelze.

## 2. Česká konkurence a pricing (ceníky k datu revize)

| Produkt | Ceny / způsob monetizace | Zveřejněná funkcionalita | Poznámka pro Endpaper |
|---|---|---|---|
| **Zakázky GOV** [F, C1] | **Zdarma** pro dodavatele i zadavatele | sémantické vyhledávání, AI shrnutí, notifikace, sledování změn u oblíbených, komunikace; elektronické podávání za určitých podmínek | Silný bezplatný benchmark; v 10/2026 zdroje NEN, Tender arena, TENDERMARKET; nenabízí automaticky úplné pokrytí všech profilů |
| **Tenderpool** [P, C2] | Business **4 850 Kč/měs.** platba měsíčně nebo **4 120 Kč/měs. při roční fakturaci** (49 440 Kč/rok), Enterprise individuálně | agregace portálů, AI dokumentace, firemní kvalifikace/matching, notifikace, evidence citací; Enterprise API/webhook, SSO, více uživatelů, SLA | Česká konkurence AI a enterprise; deklarovaná 98% spolehlivost přes 60k analýz je tvrzení výrobce, není nezávislý benchmark |
| **Datlab Tendry** [P, C3] | Neověřeno veřejným aktuálním ceníkem | monitoring profilů a VVZ, upozornění na novou/změněnou zakázku, dokumentace, historie, analýza zadavatelů a opakovaných vítězů | Velmi zkušený datový hráč; blog popisuje funkce v letech 2021/2022, current capability ověřit demem; neoznačovat ho jen za jednoduché e-maily |
| **NENDE** [P, C4] | Free 0 Kč; Basic **2 900 Kč/rok bez DPH**; Premium **9 900 Kč/rok bez DPH** | hlídače, emaily, CPV/NUTS, zadavatelé, CSV, radar dobíhajících smluv; Premium AI souhrn dokumentů. Deklaruje zdroje NEN, VVZ, slovenské ÚVO, TED | Levný nástroj; omezený počet alertů. Neověřeno, zda konkrétně a v jakém rozsahu sleduje všechny změny po vyhlášení — předchozí kategorický závěr o absenci změn není doložen |
| **dZakazky.cz** [P, C5] | aktuální akční cena **420 Kč/měs.** nebo **4 200 Kč/rok** (dle webu) | VZMR, profily, scoring „šance“, historická konkurence, integrovaná CRM Kanban nástěnka, webhooky Raynet/Pipedrive/Slack, úkoly | **Oprava starší interpretace:** obsahuje i analytiku a CRM; cílí spíše malé zakázky. Udávané `80 % VZMR` je tvrzení výrobce, ne změřená úplnost |
| **Apertia AI / Public Tenders** [P, C6] | Individuální / neveřejný ceník | NEN, TED, profily, AI analýza podmínek, matching, kontrola/checklist nabídky | Web uvádí „100 % pokrytí“ a alert do „5 min“; jde o neověřené marketingové tvrzení |
| **Publictender / verejna-soutez.cz** [P, C7] | **Aktuální cenu nelze spolehlivě potvrdit** | původně uváděný český tender portál; doména publictender.cz nyní přesměrovává na verejna-soutez.cz | Předchozí desk research zmiňoval 99 EUR/rok (ČR) / 199 EUR/rok (ČR+EU), **bez aktuálně dostupného potvrzení; nepoužívat jako platný ceník** |

**Poznámka k cenám:** Nevztahují se na jednotný rozsah služeb (někdy 1 účet, jiný počet hlídačů, enterprise SLA, data aj.), všechny nejsou srovnatelné z hlediska DPH. Enterprise ACV pro ČR je stále neznámé. Konkrétní nabídky získat přes demo/procurement.

### Detailní závěry k českým hráčům

**Zakázky GOV:** bezplatný státní portál již vyhledává s pomocí AI a upozorňuje na změny u oblíbených. FAQ specifikuje postupné připojování dalších certifikovaných systémů (dobrovolně); elektronická podání jsou omezena pravidly a datem vytvoření zakázky. Obvyklá fráze „stát neumí AI“ by byla nesprávná. [C1]

**Tenderpool:** deklaruje hodinový průchod hlavními systémy, předkvalifikovaný shortlist a zdrojové citace, u Enterprise integrace a SSO. Nemáme potvrzenou přesnost, počet skutečných klientů, SLA v praxi ani kvalitu enterprise workflow. [C2]

**Datlab:** důležitý protiargument k hypotéze, že trh nemá datovou historii a monitoring změn: sám dodavatel popisuje výhry incumbentů a dokumentové změny. Přímý test by měl zahrnovat Datlab jako benchmark. [C3]

**NENDE:** nízká veřejná cena a „radar dobíhajících smluv“ snižují diferenciaci pouhým `contract expiry`. Ověřit skutečnou datovou logiku párování smluv, návaznost na registr smluv a alerty z nepojmenovaných profilů. [C4]

**dZakazky:** veřejně udává analytiku konkurentů a webhooky, takže CRM integrace sama není tržní mezera; zjišťovat produktovou hloubku, kvalitu dat, model pro enterprise a schopnost pracovat s velkými komplexními tendry. [C5]

**Apertia:** vendor claim pokrytí nelze převzít jako fakt. Vyžádat demo a reálné případy false negatives. [C6]

## 3. Zahraniční inspirace: jakou hodnotu přidávají

| Produkt | Kategorie | Co přidává nad monitoring | Co testovat v ČR |
|---|---|---|---|
| **Stotles** [C8] | UK B2G end-to-end sales/bid intelligence | končící smlouvy 12–24 měsíců dopředu, buyer spend, incumbent, kvalifikace bid/no-bid, pipeline, AI drafty z interních dokumentů, integrace/MCP | zdroje pro spolehlivé předtendrové signály; workflow od account plánu až po bid |
| **Mercell Market Intelligence** [C9] | evropský procurement intelligence + bid workflow | historie awardů, vztahy buyer–supplier, konkurenční hustota, obnovy smluv, plánování portfolia | kvalita spárování winner–contract–buyer, market mapping |
| **Deltek GovWin IQ** [R,C10] | americký government contracting intelligence | specializovaní analytici, časné opportunity intelligence, competitor intelligence, pipeline | kde je skutečná přidaná hodnota manuálního obohacení vs. automatizace |
| **Loopio** [R,C11] | RFP response management | schválená odpovědní knihovna, vlastníci otázky, workflow, opakované využití znalostí | kvalita práce se starými odpověďmi, údržba knihovny, složité Excel/Word |
| **Responsive (dříve RFPIO)** [R,C12] | RFP response management | znalostní báze, návrhy odpovědí, CRM a spolupráce, audit | adopce specialisty, schvalování, zdrojově podložené návrhy |

**Pozor na záměnu kategorií:** produkty pro vyhledávání veřejných příležitostí, software na psaní RFP odpovědí a software pro zadavatele (procurement suites) řeší odlišný problém. Endpaper je nemá nahrazovat všechny najednou.

## 4. Voice of Customer: veřejně dohledané zkušenosti

### Evidence jednotlivých problémů — především zahraničí

| JTBD / problém | Evidence recenzí [R] | Co naopak funguje | Hypotéza k ověření v ČR |
|---|---|---|---|
| **Noise a nesprávná relevance** | GovWin IQ: filtrování může být obtížné a vracet velké množství nepřesných výsledků; Bidnet Direct: část recenzentů popisuje přemíru alertů | dobré filtry a alerty jsou základní hodnota | účet-specifické matching a „proč ne“ se zdrojovým vysvětlením |
| **Aktuálnost a úplnost příloh** | GovWin IQ: někteří uživatelé uvádějí pozdní update a chybějící/nesprávné dokumenty | centralizovaná historie příležitostí šetří práci | versioned document monitor, citace, verifikace termínů |
| **Stará/duplicitní znalostní báze** | Loopio: staré či duplicitní odpovědi a složité governance, AI vyžaduje revizi | schválená knihovna odpovědí, reuse a team workflow | automatické vypršení, vlastník, evidence změny a approval |
| **Nespolehlivý parsing/formatting** | Loopio: konkrétní recenze popisuje import Excel, kdy chyběly otázky; export/format také problematický | strukturovaný import dokumentů šetří čas | robustní parsing + completeness check + human review |
| **Týmová spolupráce a adopce** | Loopio / Responsive: zmiňovaná složitost správy SME reviews a zapojení lidí z jiných oddělení | přiřazování úkolů a CRM konektory | nechtít po týmu další dashboard, ale pracovat v Teams/CRM |

**Reprezentativnost:** G2 není výběr náhodných firem, část recenzí je incentivizovaná / pozvaná. Zjištění popisují konkrétní uživatelské zkušenosti, nikoliv procento českých firem trpících danou bolestí. Kvalitních českých nezávislých recenzí bylo k této revizi málo; vlastní rozhovory jsou nezbytné.

### Must-have již fungující jinde

- Spolehlivě relevantní discovery a hlídání nových příležitostí.
- Včasné změny a termíny; důvěra v data.
- Podmínky kvalifikace a zdrojové odkazy u každého AI tvrzení.
- Sdílení s kolegy a review/approval; přehled, kdo řeší daný bid.
- Export/integrace a historie; možnost auditu.
- U složitých RFP recyklace schválených odpovědí.

**Místa možné diferenciace (nikoliv prokázané gaps):** předtendrové signály a renewal intelligence; opravdu firemně-specifický bid/no-bid; propojení předchozích nabídek/technických referencí s konkrétním požadavkem; vysvětlená relevance/nesoulad; kontinuální „change impact“ briefing; návrh kroků v již používaném CRM/Teams. Několik zahraničních hráčů má podobné funkce.

## 5. Co NEDĚLAT — opravy oproti dřívějšímu neověřenému souhrnu

1. **Netvrdit, že NENDE určitě nesleduje dodatečné změny.** Aktuálně ověřený ceník a FAQ tuto konkrétní mezeru nedokládají; zjistit v demo/testu. Naopak Zakázky GOV i Datlab deklarují notifikace změn [C1, C3, C4].
2. **Netvrdit, že českým produktům chybí API, webhooky, CRM nebo AI analýza.** Tenderpool i dZakazky funkce veřejně uvádějí [C2, C5].
3. **Nevydávat marketingové hodnoty „100 % coverage“, „98 % reliability“, „šance na výhru“ za nezávisle měřené výsledky.**
4. **Nepoužívat starý ceník Publictender jako aktuální.** Doména přesměrovává, ceny se nepodařilo znovu ověřit [C7].
5. **Neodvozovat českou willingness to pay z recenzí amerických produktů.**
6. **Nepředpokládat, že více funkcí = lepší řešení**; vyšší relevance, přesnost, adopce a rychlost rozhodnutí mohou mít větší váhu než počet feature položek.

## 6. Benchmark: jak soutěž mezi nástroji opravdu otestovat

Jednotný dataset 100–200 **unikátních** zadání z ČR za 6–12 měsíců, stratifikace podle ICP oborů, typů a zdrojových systémů. Nezávislý anotátor a zpětně ověřené změny.

| Test | Metoda | Předem definovaný výsledek |
|---|---|---|
| Coverage/recall | stejné zakázky z originálních zdrojů; porovnat detekci | recall k danému časovému cut-off, definice chybějících |
| Freshness | originální čas vyhlášení/změny vs. doručení | median / p95 latency, % missed |
| Relevance | firemní profil + nezávisle ručně označený fit/non-fit | precision/recall, false negative náklady |
| Kvalifikace | odborník anotuje technické a formální požadavky v přílohách | factual accuracy a kritické omission rate |
| Verifiability | vytáhnout každé tvrzení AI a dohledat přesný odstavec | podíl doložených správných tvrzení |
| Change impact | zavést nové vysvětlení zadání/změnu termínu | zda systém upozorní a označí měnící se požadavky |
| Enterprise workflow | stejný bid přepracovat v existujícím CRM/Teams vs. nástroji | aktivní počet uživatelů, čas, manuální přepis |
| Competitive price | vyžádat nabídku pro 5, 20, 50 seatů + data/API/SLA | skutečná nabídka, podmínky, lock-in |

**Zakázky GOV v testu povinně jako nulový cenový baseline.** Pokud rozdíl proti bezplatnému portálu nelze prokázat, proposition přestavět.

## 7. Zdroje / evidence log

- **[C1] Zakázky GOV** oficiální informace, FAQ, pokrytí a cena: https://zakazky.gov.cz/faq/ ; https://zakazky.gov.cz/o-projektu/ ; https://zakazky.gov.cz/
- **[C2] Tenderpool** ceník, tarify, datové zdroje a produktová tvrzení: https://tenderpool.cz/faq ; https://tenderpool.cz/
- **[C3] Datlab / Tendry** produkt a popis funkcí, blog datovaný 2022: https://datlab.eu/cs/ ; https://datlab.eu/blog/stovky-zakazek-kazdy-den/
- **[C4] NENDE** oficiální aktuální ceník: https://nende.cz/cs/cenik
- **[C5] dZakazky** produkt a ceník: https://dzakazky.cz/
- **[C6] Apertia AI**: https://www.apertia.ai/verejne-zakazky
- **[C7] Publictender redirect**: https://publictender.cz/ ; https://www.verejna-soutez.cz/
- **[C8] Stotles**: https://www.stotles.com/
- **[C9] Mercell Market Intelligence**: https://info.mercell.com/en/for-suppliers/market-intelligence/
- **[C10] GovWin IQ / G2**: https://www.g2.com/products/govwin-iq/reviews
- **[C11] Loopio / G2**: https://www.g2.com/products/loopio/reviews
- **[C12] Responsive / G2**: https://www.g2.com/products/responsive-formerly-rfpio/reviews
- **[C13] Bidnet Direct / G2**: https://www.g2.com/products/bidnet-direct/reviews

**Refresh doporučení:** čtvrtletně aktualizovat veřejné ceníky a funkcionalitu; při každém rozhodnutí o feature gap doložit screen-recording, trial nebo demo.
