# 1. část - Datový model (ERD) a model případů užití

## ZADÁNÍ
- Datový model (ER diagram) zachycující strukturu dat, resp. požadavky na data v databázi, vyjádřený v notaci UML diagramu tříd (jako na přednáškách) nebo jako ER diagram např. v tzv. Crow's Foot notaci a model případů užití vyjádřený jako diagram případů užití v notaci UML reprezentující požadavky na poskytovanou funkcionalitu aplikace používající databázi navrženého datového modelu. Datový model musí obsahovat alespoň jeden vztah generalizace/specializace (tedy nějakou entitu/třídu a nějakou její specializovanou entitu/podtřídu spojené vztahem generalizace/specializace; vč. použití správné notace vztahu generalizace/specializace v diagramu).

- Odevzdává se dokument obsahující výše uvedené modely včetně stručného popisu datového modelu. Z popisu musí být zřejmý význam jednotlivých entitních a vztahových množin.

## ŘEŠENÍ

### Volba tématu

IUS 2. projekt témata

#### 56. Cech zlodějů

Cech zlodějů chce zefektivnit svoji práci a zadal výběrové řízení na vytvoření informačního systému pro evidence krádeží a loupeží. Zloději udávají své reálné jméno (někteří jsou však bezejmenní), úředně potvrzenou přezdívku (např. Vilda Dlouhoprsťák), věk, stav (mrtvý, živý), vypsanou odměnu, a navíc vlastní řadu vybavení, které jsou různých typů (zbraně, náčiní, pasti,.), pro které musí být důkladně proškolení. Školení se rovněž vztahuje na typy zločinů, přičemž u každého typu nás zajímají detaily, míry obtížnosti provedení/proškolení. Vybavení se může dědit a předávat dál (např. v případě smrti), přičemž evidujeme od kdy do kdy zloděj dané vybavení vlastnil. Z důvodu regulace zločinu ve městě se vydávají povolení (či poukázky) na provedení zločinu určitého typu. Tyto poukázky se uplatňují na konkrétní zločin, u kterého navíc evidujeme, ve kterém rajónu byl proveden a jakou kořist poskytl. Daný zločin pak mohlo provést více zločinců. Každý zloděj eviduje své rajóny, ve kterých se pohybuje, přičemž může mít více rajónů. Evidujte rovněž základní informace o rajónech, jako je pozice, počet lidí, kapacita zlodějů (tzn. kolik se jich tam uživí), celkově dostupné bohatství a pod. Systém pravidelně tiskne žebříček nejlepší zlodějů, podle míry provedených zločinů během měsíce, i podle absolutního počtu kořistí.
