# Projekt 1. část: Datový model (ERD), model případů užití 
## Zadání
### 10: Distribuce tisku
Vaše SW firma dostala zakázku na systém "Doručování periodického tisku". Tento
informační systém musí být schopen evidovat zákazníky a jimi odebírané noviny a časopisy,
připravovat účty a evidovat platby, evidovat termíny, kdy zákazník dočasně neodebírá
tiskoviny (např. po dobu dovolené ) a pro každého doručovatele připravit vhodně uspořádaný
denní seznam doručovaných tiskovin.

## Datový model - ER diagram
![ER-Diagram + use case IDS 2025 - Page 1 (1)](https://github.com/user-attachments/assets/5602ef4c-2672-49a0-9bd7-f326fd1d6aef)

### Popis datového modelu a jeho entitních množibn a vztahů
Každá tiskovina je popsaná unikátním identifikátorem a obsahuje název, rok vydání, nakladatelství, ročník, číslo, její typ (noviny, časopis) a periodicitu vydání. Princip plateb funguje na způsob předplatného, tedy zákazník při objednávce tiskoviny rovnou tiskovinu na danou dobu doručování platí. Zákazník o tiskovinu může tedy žádat konkrétně skrz vytvoření platby, která specifikuje o jaké tiskoviny se jedná. Platba obsahuje své unikátní číslo, variabilní symbol a datum provedení. Platbu přijímá doručovatel s unikátním IČO a uvedeným názvem společnosti. Každá platba (přijatá i odeslaná) je evidovaná k uživatelům, ke kterým se vztahuje. Uživatel je zákazník, doručovatel či správce. Úlohou správce je správa účtů a samotného informačního systému. Doručovatel dostává denní seznam tiskovin, který obsahuje svoje unikátní ID, datum vytvoření, seznam a celkovou kvantitu potřebných tiskovin. Zákazník si také může evidovat dobu neodebírání tiskovin, v které pozastavuje odběr všech svých předplatných.


## Diagram případů užití 
![ER-Diagram + use case IDS 2025 - Page 2](https://github.com/user-attachments/assets/e1377647-4f23-4a20-a9da-1471b57f78b9)

