# Česká konkurence – aktualizovaný konkurenční deep dive

**Projekt:** Endpaper / tendry  
**Aktualizováno:** 9. 10. 2026  
**Účel:** podklad pro validaci enterprise tender intelligence layer pro větší dodavatele; nikoliv hotová GTM strategie.  
**Metodika:** veřejné produktové weby, oficiální ceníky a FAQ; žádný placený demo účet, mystery shopping ani nezávislé benchmarky kvality. Veřejně deklarovaná funkce ≠ prokázaná kvalitní implementace.

> Toto je aktualizace původní analýzy z počátku října. Nahrazuje zastaralé závěry, že v ČR nikdo nenabízí AI matching, analýzu dokumentace, končící smlouvy či bid workflow. Původní text je dostupný v Git historii.

## 1. Hlavní zjištění

1. **Monitoring zakázek a základní AI matching jsou již cenově komoditizované.** Existují bezplatné a velmi levné alternativy.
2. **TenderLab** už nabízí monitoring, skóre shody, AI rozbor zadání, kvalifikační gap analysis, bid pipeline, AI asistenta nad firmou a návrh nabídky v DOCX. Nelze vůči němu diferencovat jen pomocí „AI bid assistant“.
3. **QCM** má distribuci a přístup k české zadávací infrastruktuře. Na 20. 10. 2026 avizuje nový Portál Dodavatele včetně analytiky a balíčku Business; přesné funkce je třeba potvrdit na webináři/demu.
4. **NENDE** už má radar dobíhajících smluv a AI shrnutí dokumentace; **dZakazky** má konkurenty, Kanban a webhooky; **Veritra** má multicountry data, API a AI beta.
5. Příležitost pro Endpaper se musí dokazovat **hloubkou enterprise procesu** (bid/no-bid v kontextu kapacit a profitability, schvalování, právní compliance, role, audit, interní data, pre-RFP signály), nikoliv absencí základních funkcí u konkurence.
6. Negativní zjištění z veřejného webu se zapisuje „**není veřejně doloženo**“, nikoliv „produkt to nemá“.

## 2. Segmentace konkurence

| Kategorie | Hráči | Vztah k Endpaperu |
|---|---|---|
| Dodavatelská intelligence + bidding | TenderLab, QCM Portál Dodavatele, NENDE, dZakazky, Veritra, TenderSignal, Hello Tender, NajdiVZ | Přímá či částečná konkurence |
| Oficiální discovery a veřejná data | Zakázky GOV, VVZ, TED, NEN, Hlídač státu | Bezplatná konkurence v základní datové vrstvě; možné datové zdroje |
| Elektronické zadávací nástroje | E-ZAK, JOSEPHINE, Tender arena, PVÚ, TENDERBOX | Primárně workflow zadavatele a podání, ne totéž co interní bid management dodavatele |

## 3. Ceníkový benchmark (9. 10. 2026)

| Produkt | Veřejná cena | Model / poznámky | Zdroj |
|---|---|---|---|
| TenderLab Software | **6 490 Kč/měsíc / 5 uživatelů**; **5 490 Kč/měsíc** při roční fakturaci | 14 dní zdarma, servis individuálně | https://tenderlab.cz/ ; https://tenderlab.cz/terms |
| NENDE | **Free**; **2 900 Kč/rok Basic**; **9 900 Kč/rok Premium** | bez DPH, AI analýza v Premium, radar končících smluv od Basic | https://nende.cz/cs/cenik |
| dZakazky | akčně **420 Kč/měs.**, **4 200 Kč/rok** (na webu i běžné ceny 890 Kč/měs., 8 900 Kč/rok) | Self-service, 5 dní trial; změny akce možné | https://dzakazky.cz/ |
| Veritra | pro ČR **11 €/země/měs.** nebo **120 €/země/rok** dle vícejazyčného ceníku; český web může zobrazovat Kč | Sleva podle počtu zemí; AI analýza beta, podle spotřeby | https://veritra.io/pricing ; https://www.veritra.io/nl/pricing |
| TenderSignal | **29 €/měsíc**, 14 dní zdarma | IT zakázky v CZ/SK/PL | https://tendersignal.eu/cz |
| Hello Tender | **Free**, **19 €/měs. Plus**, **69 €/měs. Pro Unlimited** | Uvedené ceny při roční fakturaci; cena bez DPH | https://www.hellotender.eu/en/pricing |
| NajdiVZ | od **990 Kč/měs.** rozšířené hledání; **1 190 Kč/měs.** s monitoringem; **4 990 Kč/měs.** na míru | Bez DPH; XML/Excel export u tarifu na míru, API deklaruje v produktu | https://www.najdivz.cz/balicky-sluzeb |
| Zakázky GOV | **Zdarma** | Státní projekt; dostupnost podání závisí na podpoře konkrétního zadávacího nástroje | https://zakazky.gov.cz/ |
| Hlídač státu | veřejné použití zdarma; komerční API **12 000 Kč / 6 měsíců pouze zakázky**; **250 000 Kč/rok kompletní** | Důležité pro datové náklady a licenční strategii | https://www.hlidacstatu.cz/cenik |
| QCM Portál Dodavatele | **Aktuální veřejný ceník spolehlivě neověřen** | Tarify + chystaný balíček Business; nebrat historických 2 500 Kč/rok jako nynější cenu | https://www.portaldodavatele.cz/ |

Pozn.: nejde o skutečné zaplacené ceny enterprise kontraktů; tarify se liší počtem uživatelů, zdroji, workflow, daty i fakturací. Akční ceny nelze mechanicky extrapolovat na celý trh.

## 4. Hloubkové profily

### 4.1 TenderLab — nejbližší funkční rival

**Fungování:** (a) firemní profil s referencemi, certifikacemi a kapacitami, (b) agregace a deduplikace NEN/E-ZAK/PVÚ/ISVZ/TED, (c) AI fit skóre 0–100, (d) AI čtení dokumentace a kvalifikační gap analýza, (e) pipeline/checklisty/dokumenty, (f) návrh nabídky v DOCX, (g) odborný servis s lidskou přípravou kompletní nabídky.

**Dobře:** silný end-to-end příběh; propojení kvalifikace firmy s příležitostí; transparentní software pricing; možnost upsellu na službu.

**Neověřené mezery:** enterprise SSO, práva v rámci divizí, víceúrovňová interní schvalování, automatická identifikace změn na úrovni požadavků, deep CRM/SharePoint integrace, audit AI rozhodnutí; žádná z absencí nebyla prokázána. Pro software se v podmínkách liší závazek od lidské služby; prověřit právní odpovědnost za výstupy.

**Threat:** vysoká produktová. Nutné demo na reálné komplikované zakázce a písemná nabídka enterprise.

**Zdroje:** https://tenderlab.cz/ ; https://tenderlab.cz/terms

### 4.2 QCM / Portál Dodavatele — největší infrastrukturní a distribuční rival

**Fungování:** rozhraní nad více e-nástroji, relevantní filtry a hlídače, upozornění, historie zakázek, návaznost na E-ZAK a podání nabídky, je-li u konkrétního řízení podporováno. Skupina QCM provozuje E-ZAK a další zadávací produkty.

**Novinka:** QCM na **20. října 2026 10:00–10:45** výslovně ohlašuje představení nové generace Portálu Dodavatele a Business analytiky; předvedení zatím **není důkaz**, že je celé řešení nasazené a dostupné dnes.

**Dobře:** distribuce u veřejných zadavatelů a dodavatelů, české procesy a legislativa, přímé workflow do zadávacích systémů.

**Neověřené mezery:** intrafiremní enterprise schvalování, práce s neveřejnou znalostní bází dodavatele, prediktivní obchodní rozhodování na úrovni portfolia příležitostí.

**Threat:** vysoká strategická. Priorita: webinář a požadavek na nabídku se scénářem 10+ uživatelů / více divizí.

**Zdroje:** https://www.portaldodavatele.cz/ ; https://skoleni.qcm.cz/predstaveni-portalu-dodavatele-1026/

### 4.3 NENDE — levný AI monitoring

**Fungování:** filtrování podle CPV/NUTS/zadavatele, e-mail alerty, CSV a 30–60denní historie, radar končících smluv; Premium sumarizuje zadávací dokumentaci, kvalifikaci a termíny.

**Dobře:** nízká jasná roční cena, rychlý onboarding, silný value for money.

**Neověřené mezery:** dlouhá retrospektiva, komplexní týmová pipeline, rozsáhlé integrace, příprava nabídky a kalibrovaný model pravděpodobnosti úspěchu.

**Threat:** vysoká cenová pro „AI shrnutí + renewal radar“, nižší pro skutečný enterprise tým.

**Zdroj:** https://nende.cz/cs/cenik

### 4.4 dZakazky.cz — specialista na VZMR

**Fungování:** sběr ze strojově čitelných profilů, čištění nerelevantních zakázek, ranní monitoring, historické výsledky/konkurenti, Kanban pipeline, webhooky do CRM a Slacku. Provozovatel uvádí >25 000 monitorovaných účtů a 80% pokrytí VZMR; **jde o tvrzení dodavatele**.

**Dobře:** konkrétní ICP a cena, praktické integrace, filtrování přehnaně velkých řízení pro malé dodavatele.

**Neověřené mezery:** velké komplexní zakázky, víceúrovňové schvalování, právní kontrola rozpracované nabídky.

**Threat:** spíše nepřímá pro enterprise, důležitá pro přehodnocení unikátnosti Kanbanu/webhooků.

**Zdroj:** https://dzakazky.cz/

### 4.5 NajdiVZ — agregace a datové integrace

**Fungování:** vyhledávání/monitoring, vlastní filtry, datové exporty a API pro interní zpracování.

**Dobře:** zákazník může využívat data v existujících interních systémech; jasné cenové hladiny.

**Neověřené mezery:** AI kvalifikační kontrola, kvalitní bid/no-bid nad interní ekonomikou a reference-based proposal drafting.

**Threat:** střední pro samotný „intelligence feed“.

**Zdroje:** https://www.najdivz.cz/ ; https://www.najdivz.cz/balicky-sluzeb

### 4.6 Veritra — multicountry data a integrační vrstva

**Fungování:** jednotlivé sledované země, alerty, REST API, webhooky a AI beta pro relevanci a některé dokumenty.

**Dobře:** EU rozsah, cena za zemi, integrace.

**Neověřené mezery:** hluboká česká kvalifikační logika, proposal governance a řízení větších týmů.

**Threat:** střední, zejména pro geografickou expanzi.

**Zdroje:** https://www.veritra.io/nl/pricing ; https://www.veritra.io/vop

### 4.7 TenderSignal — specializace IT v CEE

**Fungování:** IT zakázky CZ/SK/PL, relevance vůči profilu, shortlist a podklady k bid/no-bid, odkazy k originálům.

**Dobře:** vertikální focus, vysvětlitelnost shortlistu, jednoduché rozhodnutí o dalším průzkumu.

**Neověřené mezery:** multi-department enterprise workflow a generování plně validované nabídky.

**Threat:** relevantní při vstupu do IT enterprise segmentu.

**Zdroj:** https://tendersignal.eu/cz

### 4.8 Hello Tender — evropské AI discovery a příprava

**Fungování:** firemní profil, evropské vyhledávání, AI insights, dokumenty a vedené checklisty; Pro umožňuje max. 5 přípravných workflow denně pro podporované dokumentace.

**Dobře:** freemium, celoevropská nabídka, nízký práh vstupu.

**Neověřené mezery:** lokální česká přesnost, enterprise role, detailní integrace a právní garance.

**Threat:** částečná konkurence přeshraničnímu AI tender SaaS.

**Zdroj:** https://www.hellotender.eu/en/pricing

### 4.9 Bezplatná a infrastrukturní konkurence

- **Zakázky GOV:** státní vyhledávač se sémantickým hledáním, alerty a podporovaným elektronickým podáním v části zadávacích nástrojů; není to univerzální náhrada všech e-nástrojů. https://zakazky.gov.cz/
- **Hlídač státu:** historická data, smlouvy, zakázky, veřejná analytika a API. Komerční licenční náklady mohou být relevantní pro datový stack. https://www.hlidacstatu.cz/ ; https://www.hlidacstatu.cz/cenik
- **JOSEPHINE, E-ZAK, Tender arena, PVÚ, TENDERBOX:** většinou nástroje zadavatelské administrace, komunikace a podání. Neklasifikovat je automaticky jako přímou náhradu interního capture/bid managementu dodavatele.

## 5. Feature matrix (deklarováno / částečně / veřejně neověřeno)

| Produkt | AI matching | AI rozbor dokumentů | Konkurenční historie | Interní bid pipeline | API/webhook |
|---|---|---|---|---|---|
| TenderLab | Ano | Ano | Ano | Ano | ? |
| QCM Portál Dodavatele | Částečně / připravovaná analytika | ? | Ano / Business | Část (vazba na podání) | ? |
| NENDE | Filtry | Ano (Premium) | ? | ? | Export CSV |
| dZakazky | AI priority/filtr | ? | Ano | Kanban | Ano |
| NajdiVZ | Filtry | ? | ? | ? | Ano |
| Veritra | Beta | Beta | ? | ? | Ano |
| TenderSignal | Ano | Shortlist/summary | Historie | Shortlist | ? |
| Hello Tender | Ano | Ano | Část | Checklist | ? |
| Zakázky GOV | Sémantické hledání | Rozvoj AI | Část | Elektronické podání části zakázek | ? |
| Hlídač státu | Fulltext/filtry | ? | Ano | ? | Ano |

„?“ není důkaz, že funkcionalita neexistuje. Marketingové „šance na výhru“ neznamenají kalibrovanou P(win).

## 6. Potenciální enterprise mezery — hypotézy k testování, ne potvrzená whitespace

1. **Strategické bid/no-bid:** explicitní vyhodnocení profitability, kapacit, referencí a governance; odlišit fit skóre od odhadované P(win).
2. **Týmový capture workflow:** role, gate reviews, vlastní schvalovací matice, divize, externí partneři, audit.
3. **Interní knowledge layer:** RFP požadavek -> interní důkaz -> schválený response snippet -> citace -> verze; ověřit bezpečnost.
4. **Sledování změn dokumentace:** automatický diff požadavků, určení dopadu na pracovní dokumenty, vlastník a potvrzení.
5. **Pre-RFP intelligence:** plány zadavatelů, rozpočtové signály, nákupní cykly a končící rámce; data s pravděpodobností, proveniencí a právním režimem.
6. **Návaznost na existující CRM / Teams / SharePoint:** nebudovat další izolovaný portál, pokud zákazník chce integrovanou vrstvu.
7. **Post-award learning:** evidence výsledku, důvodů výhry/prohry, lessons learned a feedback do dalšího bid/no-bid.

Pro všechny body je potřeba prokázat bolest, dostupnost dat a ochotu platit; konkurent některé může mít ve svém neveřejném enterprise tarifu.

## 7. Doporučený battle-test / validace

**Testovací sada:** 30–100 identických skutečných zakázek z několika oborů včetně náročných příloh, zrušených řízení a dodatků. Metriky: recall relevancí, precision, latence zveřejnění -> alert, chybně přehlédnuté kvalifikační podmínky, kvalita zdrojových citací, čas na připravený go/no-go podklad, reálné náklady/tendr.

**Prioritní demoverze:**
1. TenderLab: 100stránková dokumentace; reference a certifikace; kvalifikační gap; schválení; revize podkladů; SSO/integrace.
2. QCM: účastnit se webináře 20. 10.; ověřit dostupnost Business analytiky, kontrakty/uhrazené ceny, multi-team workflow, pricing.
3. NajdiVZ/Veritra: API specifikace, inkrementální aktualizace, licenční omezení, dostupnost historických polí.
4. NENDE: kvalita radarů a coverage, prověřit falešné renewaly.
5. Design partneři: požádat vedoucího tender týmu, aby popsal **poslední tři skutečná** go/no-go rozhodnutí, interní předávání a časové ztráty; nedotazovat se jen „chtěl byste AI“.

## 8. Pracovní positioning a protiargument

Možné positioningové tvrzení (k ověření): „Endpaper propojuje veřejnou procurement intelligence s interními daty a procesy velkého dodavatele a dává týmu auditovatelný podklad pro výběr, přípravu a vyhodnocení zakázek.“

**Protiargument:** Zákazník může proces již dostatečně pokrývat kombinací QCM/TenderLab, Salesforce/Teams/SharePoint a interních specialistů. Pokud nepřidáme měřitelnou hodnotu, jde jen o další UI / další seat licenci.

## 9. Doporučené další kroky

- [ ] Demoverze TenderLab, QCM a alespoň jednoho API-first poskytovatele.
- [ ] Vyžádat reálnou enterprise cenu a detail bezpečnostních/integr. podmínek.
- [ ] Dokumentovat v benchmarku „marketing claim vs. test evidence vs. unknown“.
- [ ] Ověřit prioritní pain points s velkými českými dodavatelskými týmy, ne jen s mikrofirmami.
- [ ] Následovat globální konkurencí zejména v USA (GovWin, HigherGov, GovDash, GovTribe, Govly, Awarded AI), UK (Tussell, Stotles) a Evropě (Mercell, Tendium).

---
*Poznámka k výzkumu: fakta jsou podložena oficiálními produktovými stránkami uvedenými u každé firmy; dostupná literatura nepostačuje k nezávislému ověření výkonnosti, cen enterprise smluv ani zákaznické retence.*
