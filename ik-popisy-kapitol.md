
Zde jsou popisy a pokyny ke zpracování jednotlivých kapitol a podkapitol informační koncepce nemocnice podle připravené šablony.

-------


# 1. Úvod
> Úvodní kapitola, základní informace a rétorické shrnutí IK.
## 1.1. Identifikace Informační koncepce

> Základní informace o nemocnici jako takové a a o informační koncepci, včetně základních rolí a zodpovědností. Ze šablony se jen doplňují věci
## 1.2. Manažerské shrnutí Informační koncepce OVS
> Tady je klasické summary. Šablona mu dává jednotnou strukturu, aby se to lépe četlo. Takže zde jen zase dle šablony doplnit co se má, včetně odrážek. Je vhodné tady vypíchnout to nejdůležitější z celé IK a jejích záměrů. Co chcete, aby lidi četli, dejte sem.
## 1.3. Specifické postavení nemocnice a vazba na řízení IT

> Tohle je jedna ze specifických kapitol a vzhledem ke spoustě specialit a odchylek od klasického fungování jiných OVS, se toto tedy dávat už do první části. Tohle by mělo být stejné pro všechny nemocnice, ve druhé fázi by to mělo být tedy už rovnou v šabloně

# 2. Plán rozvoje informačních systémů orgánu veřejné správy
> Toto je část o ICT nástrojích pro byznys nemocnice. Je to třeba brát pro nemocnici jak z pohledu nemocnice jako nemocnice, tak i z pohledu nemocnice jako organizace. Nahrazuje část B ve velké šabloně IK, ale protože se IK nemocnice má točit především kolem informatiky a systémů (netočí se kolem výkonu veřejné správy a fungování) je přizpůsobena těmto potřebám a obsahuje i specifické věci pro nemocnice.
## 2.1. Popis stávajícího stavu architektury nemocnice

> Soupis současného stavu IT v nemocnici ve vazbě na její byznysové fungování. Pochopitelně nemá celý rozsah jako ostatní OVS, protože neřeší výkon veřejné správy jako takové. Od nemocnice se v první verzi IK neočekává detailní rozpracování architektury jako formální architektury v ArchiMate, proto postačí v první verzi jen popis a soupis dle znalostí po jednotlivých vrstvách.
### 2.1.1. Poslání nemocnice a jeho plnění (motivační architektura)
> Motivačně byznysový základ nemocnice z pohledu její role jako OVS. Opět, je u nemocnice velice specifické. Mělo by být společné z větší části pro všechny nemocnice a pokud bude zájem, může být v budoucnu součástí šablony ve druhé fázi projektu.
### 2.1.2. Fungování nemocnice (byznysová architektura)
> Čistě byznysová architektura. Tedy obecné role v nichž nemocnice je (a co z nich plyne), organizační struktura nemocnice a rozpad fungování do základních rámcových činností (/oblastí fungování). V ideálním případě pochází jako výpis prvků z architektury v ArchiMate, nicméně pro první verzi nemusí být v podrobném detailu.
### 2.1.3. Informační systémy nemocnice určené pro poskytování zdravotních služeb
> V nemocnici rozlišuje systémy na součásti NIS/ISPZS (to co potřebuje nemocnice aby nemocnicovala) a na zbytek. Zde tedy popsat NIS a další systémy a komponenty potřebné pro poskytování zdravotní péče a služeb, vykazování, integrace na IDRR a na ostatní poskytovatele, apod.
### 2.1.4. Informační systémy určené pro provoz a fungování nemocnice
> Zde popsat všechny ostatní systémy v nemocnice, tedy ty kromě NIS/ISPZS. Určitě nezapomenout na ty klíčové, jako je ekonomika, sklady, personalistika, směny, mzdy, e-mail, spisovná, systém pro sociální služby. Určitě zmínit každý systém, který má integraci ven mimo nemocnici. Ale především se zpovíme  z toho, jak systémy evidujeme, kdo za to zodpovídá a kde se to vede.
### 2.1.5. Ostatní informační systémy a aplikace
> Zde popsat další systémy, které jsou zásadní v nemocnici, ale nebereme je jako ryze klíčové. Třeba sledovací systémy, kamery, provozní systémy, IT monitoring a další provozní.
### 2.1.6. Integrace mezi systémy a na externí systémy
> Spolupráce systémů uvnitř nemocnice je důležitá pro efektivitu jak pro zdravotní péči, tak pro fungování nemocnice. Zde se tedy popisují základy vnitřní integrace (mezi systémy nemocnice) i vnější integrace (systémy integrující se ven). U vnější integrace nesmíme zapomenout na integrace na systémy služeb elektronického zdravotnictví, na systémy zdravotních pojišťoven  a další integrace plynoucí z povinností.
### 2.1.7. Zajištění technologií a infrastruktury nemocnice (technologická architektura)
> Popis technologií, datových center, serverů, úložišť, konektivity, sítí. Prostě celou vrstvu infrastruktury, připojení a technologií jež nemocnice používá a potřebuje.
## 2.2. Popis důvodu pro změny architektury nemocnice
> Tato kapitola má ukázat, že víte, co děláte a co vás ovlivňuje. Po přečtení této kapitoly by měl čtenář mít jasno, jak dobře znáte své postavení a motivace, jestli jste na něco nezapomněli a jak se ke změnám obecně stavíte. Řada z uvedených věcí pak má být součástí motivační architektury nemocnice.
### 2.2.1. Obecné důvody
> Pro změny máme různé důvody. Obecnými důvody je nepochybně rámec pro elektronizaci zdravotnictví, nové povinnosti dlouhodobého řízení plynoucí z nové role OVS a obecně legislativní potřeby a povinnosti. U jednotlivých nemocnic se mohou důvody lišit, respektive jistě přibudou důvody u fakultních nemoci oproti ostatním, apod.
### 2.2.2. Elektronizace zdravotnictví

> Popsat společný rámec elektronizace zdravotnictví (má být stejný v základu pro všechny nemocnice) a jak se k němu nemocnice staví). Podrobněji se pak rozebírá kupříkladu ve zhodnocovacích tabulkách.
### 2.2.3. Modernizace nemocnice

> Důležité jsou nejen povinnosti elektronizace zdravotnictvím ale i potřeb modernizace nemocnicfe vevnitř, ať už jde o modernizaci technologií a zařízení a nebo modernizace procesů provozu nemocnice a jejich nástrojů. I to je zásadní skupina motivace.
### 2.2.4. Další oblasti elektronizace a digitalizace

> Nemocnice má jako organizace povinnosti digitalizace nejen v rámci elektronického zdravotnictví, ale i spoustu ostatních povinností v dalších skupinách. To se týká veřejných zakázek, poskytování informacím výkonu spisové služby, digitalizace ekonomických a provozních procesů a procesů kontroly, apod. I když jsou tyto motivace často potlačovány a nezdají se být tak důležité, opak je pravdu a nesmí se na ně zapomínat.
### 2.2.5. Vnitřní motivace a potřeby změn

> Nesmí se zapomínat i na potřeby lidí uvnitř nemocnice. Kupříkladu pokud nejsou spokojeni se systémem, nebo jim dané systémy neusnadňují práci, musí se i na tyto potřeby reagovat. Nejde jen o touhy a potřeby vedení a vedoucích pracovníků, ale i všech uživatelů.
## 2.3. Navržený cílový stav architektury
> Zde se popisuje a pokud možno i výstupy z Enterprise architektury dokládá požadovaný cílový stav architektury a především cílový stav fungování nemocnice. Tato podkapitola má mít další strukturu buď dle oblastí, či dle architektonických vrstev.
## 2.4. Plán realizace změn informačních systémů nemocnice
> V předchozích podkapitolách se definoval současný a budoucí stav, v této kapitole se popisuje, jak cílového stavu dosáhnout. Rozebrat po projektové stránce, po stránce řízení a organizace, po stránce financí a procesního řízení změn. U podrobností se pak odkázat na katalog záměrů, kterými vlastně zde uvedené změny realizuje. Záměry neopisujeme, zde se vypořádáme s tím, jak jich dosáhnout.neip
# 3. Přehled řízení informatiky

> Předchozí celá kapitola byla o IT pro nemocnici jako takovou. Tato kapitola má podobnou strukturu a týká se už podrobně informatiky a jejího řízení, má tedy podrobně rozepisovat fungování a řízení a změny v ICT po odborné a provozní stránce.
## 3.1. Popis stávajícího stavu řízení informatiky


> Tato podkapitola má popsat celý současný stav řízení ICT. Protože jde o první verzi, před pilotním projektem, je zde struktura vlastně spíš jen nastíněna. Cílem je ale popsat organizaci IT útvaru, procesy a reálné řízení ICT, řízení systémů a jejich rozvoje a všechny věci kolem. Nemusíte zabývat do velkých podrobností, ale rámec musí být popsán.
### 3.1.1. Obecný popis řízení a rozvoje informatiky v nemocnici

> Popis toho, jak se ICT řídí nyní, vychází se z popisů uvedených ve vyhlášce o dlouhodobém řízení. Popíše se struktura a fungování útvaru IT, spolupráce s dalšími útvary a řízení rozvoje informačních systémů.
# 3.1.2. Soulad s procesy požadovanými dlouhodobým řízením IS
> Vyhláška 360/2023 o dlouhodobém řízení udává povinnost zavést základní procesy pro řízení ICT v nemocnici. Podrobnosti jsou uvedeny v příslušné příloze (podkapitola Datové přílohy), zde tedy pouze obecně popíšeme, že víme, že něco takového je a že víme, jak se s tím vypořádat. Neazapomenem se odkázat do kapitoly s příslušnou datovou přílohou IK.
## 3.2. Popis důvodu pro změny řízení informatiky

> Opět se po jednotlivých částech uvedou motivace a potřeby vedoucí ke změnám řízení ICT, kupříkladu právě IK, dlouhodobé řízení, organizační změny, apod.
## 3.3. Navržený cílový stav řízení informatiky

> Zde se píše cílový stav, jak má informatika fungovat a jak má fungovat rozvoj a provoz systémů a ICT prostředků. Vychází se přitom z potřeb dlouhodobého řízení, souvisejících povinností a z potřeb a motivací nemocnice.
## 3.4. Plán realizace změn pro dosažení cílového stavu řízení informatiky

> Podkapitola obsahuje informace o tom, jak nemocnice dosáhne cílového stavu a přechodu od současného k cílovému. Základem jsou záměry, na které se kapitola odkáže (do katalogu záměrů), ale popíše se i mechanismus uplatňování řídících, procesních a technických změn, nebo třeba požadavky na financování změn apod.
# 4. Dokumentace o správě informační koncepce orgánu veřejné správy
> Tato celá kapitola je o změnách a uplatňování celé IK. Mimo jiné se tady řeší její jednotlivé aktualizace, změny v aktualizacích a také procesy pro její sledování a vyhodnocování, podle kterého se pak dělají aktualizace.
## 4.1. Platnost informační koncepce orgánu veřejné správy

> V první verzi koncepce před aktualizací se uvede od kdy do kdy je platná. Obecně se má vytvořit hlavní verze jednou za 5 let, ta se musí atestovat. Dílčí aktualizace se jako hlavní verze neberou, pokud tedy nedojde k tak rozsáhlé změně obsahu IK, že se dá považovat za novou IK. Při aktualizacích pak uvádíme platnost jednotlivých aktualizací.
## 4.2. Postupy při vyhodnocování dodržování informační koncepce orgánu veřejné správy
> Zde se uvedou procesy a postupy pro zajištění jednak uplatňování IK a jednak její vyhodnocování. Vyhodnocuje se soulad skutečnosti s IK a soulad IK se skutečností. Jakékoliv podstatné změny, kupříkladu posuny v realizaci definovaných záměrů a nebo změny či náhrady informačních systémů, se musejí realizovat jen v souladu s předchozími záměry v IK a následně se musí do aktualizace IK promítnout. Uvede se také, kdo a jak je za vyhodnocení a uplatňování IK zodpovědný.
## 4.3. Postupy při provádění změn informační koncepce orgánu veřejné správy

> Při vyhodnocování se provádí změny nebo aktualizace IK. Zde se uvedou procesy a postupy, které budou dodrženy při aktualizaci, způsob jejího projednání a vyhlášení a způsob kontroly dodržení těchto procesů.
## 4.4. Změnové listy, kterými byla informační koncepce orgánu veřejné správy změněna
> Při každé aktualizace IK se vytvoří nový měnový záznam obsahující informace o nové verzi a především obsahující úplný a detailní výčet změn oproti předchozí verzi. Nová verze IK se zveřejní a u každé změny se také uvede odkaz na zveřejněnou předchozí verzi IK.
# 5. Datové přílohy informační koncepce
> Tato část koncepce obsahuje přílohová data. Jedná se o data, ze kterých se koncepce skládá. Vzhledem k důležitosti těchto primárních dat jsou přehledně na jednom místě a příslušné kapitoly z nich čerpají. Další výhodou je to, že tato data jsou součástí vyhodnocení IK a změn pro aktualizaci IK jako také a tedy se při aktualizaci primárně upraví tyto data.
## 5.1. Přehled obecných rolí nemocnice
> Seznam obecných rolí (role plynoucí ze zákona, role přinášející povinnosti a procesy), v nichž nemocnice obecně je. Je defacto stejné pro všechny nemocnice a bude součástí další verze šablony IK.
## 5.2. Tabulky zhodnocení současného stavu a změn
> Obsahuje předpřipravené tabulky a datové části zhodnocení nemocnice podle různých aspektů. Jde kupříkladu o zhodnocení souladu s principy IKČR, zásadami IKČR, adoptované cíle IKČR, principy elektronizace zdravotnictví, apod. Kromě v šabloně předpřipravených si nemocnice může přidat vlastní zhodnocovací tabulky, u kterých vždy uvede zdroj aspektů pro hodnocení.
## 5.3. Přehled informačních systémů a aplikací klíčových pro nemocnici
> Tabulka s přehledem všech informačních systémů a aplikací provozovaných v nemocnici nebo užívaných nemocnicí. Musí být výstupem ze systematické evidence systémů.
## 5.4. Přehled záměrů IK
> Obsahuje výpis ze systematické evidence Katalog záměrů IK. Zde bude tabulka s přehledem všech záměrů a pokud k nim existují podrobnosti, tak s těmito podrobnostmi. Uvede se také informace o vedení katalogu záměrů, kde jsou pak veškeré podrobnosti o záměru sledované v čase. Aktualizuje se při každé aktualizaci IK.
## 5.5. Přehled nutných součinností
> Zde se popíše seznam součinností externích subjektů. Tedy zejména těch, které ovlivní fungování ICT nemocnice a dlouhodobé řízení, dále pak těch, se kterými si nemocnice vyměňuje data apod. Základ by měl být u všech nemocnic stejný, nicméně každá nemocnice si musí především doplnit svá specifika.