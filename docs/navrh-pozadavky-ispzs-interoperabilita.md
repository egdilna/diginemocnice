Následující tabulka obsahuje dekomponované konkrétní požadavky na [[Informační systém poskytovatele zdravotních služeb|ISPZS]], které souvisejí s elektronizací zdravotnictví. Jde zejména o požadavky implementující povinnosti a předpoklady zákona [[predpis:325/2021]] a zákona [[372/2011]].
| ID | Type | Name | Documentation | Specialization |
|---|---|---|---|---|
| ehispreq01 | Requirement | Přijímat elektronickou identitu IDRR REIZP |  | Požadavek souladu |
| ehispreq02 | Requirement | Ověřit identitu zdravotnického pracovníka při vstupu do poskytovatele |  | Požadavek souladu |
| ehispreq03 | Requirement | Ověřit identitu zdravotnického pracovníka při výstupu od poskytovatele |  | Požadavek souladu |
| ehispreq04 | Requirement | Ověřit identitu zdravotnického pracovníka dle potřeby |  | Požadavek souladu |
| ehispreq05 | Requirement | Autentifikovat zdravotnického pracovníka dle jeho identity v IDRR REIZP |  | Požadavek souladu |
| ehispreq06 | Requirement | Zajistit přístup identifikovaného zdravotnického pracovníka do informačního systému |  | Požadavek souladu |
| ehispreq07 | Requirement | Autorizovat zdravotnického pracovníka v jeho aktuální roli |  | Požadavek souladu |
| ehispreq08 | Requirement | Autorizovat přístup zdravotnického pracovníka v jeho roli do informačního systému |  | Požadavek souladu |
| ehispreq09 | Requirement | Ověřit validaci dle certifikátu zdravotnického pracovníka v IDRR REIZP |  | Požadavek souladu |
| ehispreq10 | Requirement | Ověřit validaci poskytovatele dle jeho resortního certifikátu z IDRR REIZP |  | Požadavek souladu |
| ehispreq11 | Requirement | Zapsat údaje o zaměstnaneckém vztahu zdravotnického pracovníka a poskytovatele |  | Požadavek souladu |
| ehispreq12 | Requirement | Zapsat údaje o ukončení zaměstnaneckého vztahu zdravotnického pracovníka s poskytovatelem |  | Požadavek souladu |
| ehispreq13 | Requirement | Zapsat údaje o příslušnosti zdravotnického pracovníka k pracovišti poskytovatele |  | Požadavek souladu |
| ehispreq14 | Requirement | Vedení záznamů zdravotnické dokumentace v elektronické podobě |  | Požadavek souladu |
| ehispreq15 | Requirement | Vedení záznamů o exportu či výstupu záznamů zdravotnické dokumentace ze systému |  | Požadavek souladu |
| ehispreq16 | Requirement | Export výstupu zdravotnické dokumentace do listinné podoby a záznam o tom |  | Požadavek souladu |
| ehispreq17 | Requirement | Export výstupu zdravotnické dokumentace do autorizovaného záznamu či autorizovaného dokumentu |  | Požadavek souladu |
| ehispreq18 | Requirement | Autorizování dokumentu či záznamu zdravotnické dokumentaci při předání mimo poskytovatele |  | Požadavek souladu |
| ehispreq19 | Requirement | Vedení auditního transakčního protokolu k záznamům a dokumentům zdravotnické dokumentace v informačním systému |  | Požadavek souladu |
| ehispreq21 | Requirement | Nezměnitelnost a důvěryhodnost vedení záznamů ve zdravotnické dokumentaci |  | Požadavek souladu |
| ehispreq22 | Requirement | Důvěryhodné svázání jakékoliv akce s konkrétním zdravotnickým pracovníkem |  | Požadavek souladu |
| ehispreq23 | Requirement | Přístup ke službám elektronického zdravotnictví prostřednictvím svého informačního systému poskytovatele |  | Požadavek souladu |
| ehispreq24 | Requirement | Přidělení jednoznačného identifikátoru každému záznamu zdravotnické dokumentace dle standardu |  | Požadavek souladu |
| ehispreq25 | Requirement | Přidělení jednoznačného identifikátoru záznamu o záznamu zdravotnické dokumentace dle standardu |  | Požadavek souladu |
| ehispreq51 | Requirement | Pro identifikaci pacienta využívání výhradně identifikátoru pacienta |  | Požadavek souladu |
| ehispreq52 | Requirement | Vazba identifikátoru pacienta na číslo pojištěnce či rodné číslo |  | Požadavek souladu |
| ehispreq53 | Requirement | Ztotožnění pacienta přes jeho identitu ve Kmenovém registru pacientů |  | Požadavek souladu |
| ehispreq54 | Requirement | Reklamace neexistence či nesprávných údajů o pacientovi v KRP |  | Požadavek souladu |
| ehispreq55 | Requirement | Přebírání údajů o pojištění pacienta přes kmenové registry |  | Požadavek souladu |
| ehispreq56 | Requirement | Vedení a výstup transakčního auditního logu k jednomu pacientovi |  | Požadavek souladu |
| ehispreq57 | Requirement | Předávání údajů o zdravotní péči a službách do NZIS |  | Požadavek souladu |
| ehispreq58 | Requirement | Předávání údajů o vybraných diagnózách a službách do specifických registrů v rámci NZIS |  | Požadavek souladu |
| ehispreq81 | Requirement | Převod účetnických a ekonomických informací dle Metodiky evidence zdrojů zdravotnického zařízení dle CZ-DRG |  | Požadavek souladu |
| ehispreq82 | Requirement | Předávání údajů pro sledování akutní ´lůžkové péče dle datového rozhraní a ve struktuře klasifikace CZ-DRG |  | Požadavek souladu |
| ehispreq20 | Requirement | Vedení auditního protokolu o přístupu ke zdravotnické dokumentaci a nahlížení do ní | Informační systém musí vést informace o přístupu kohokoli v jakékoliv roli k jednotlivým záznamům zdravotnické dokumentace a to včetně ověřené identity konkrétního zdravotnického pracovníka, jeho roli a důvodu přístupu. Je vhodné toto vést také jako součást auditního transakčního protokolu ke zdravotnické dokumentaci. | Požadavek souladu |
| ehispreq26 | Requirement | Autorizování záznamů zdravotnické dokumentace v informačním systému | Poskytovatel záznamy ve zdravotnické dokumentaci vedené v elektronické podobě nebo její části vedené v elektronické podobě, které nepředává jiné osobě, autorizuje způsobem určeným tímto poskytovatelem, který zajišťuje, že z autorizace lze určit, která osoba potvrdila jeho správnost, a to s uvedením data a času provedení tohoto záznamu. K tomu se přidávají technické požadavky na důvěryhodnost vedení zdravotnické dokumentace v informačním systému poskytovatele, jak stanoví prováděcí vyhláška a příslušné standardy NCEZ. | Požadavek souladu |
| ehispreq27 | Requirement | Autorizování záznamu zdravotnické dokumentace v informačním systému pokud není předáván | Poskytovatel záznamy ve zdravotnické dokumentaci vedené v elektronické podobě nebo její části vedené v elektronické podobě, které nepředává jiné osobě, autorizuje způsobem určeným tímto poskytovatelem, který zajišťuje, že z autorizace lze určit, která osoba potvrdila jeho správnost, a to s uvedením data a času provedení tohoto záznamu. | Požadavek souladu |
| ehispreq28 | Requirement | Záznam o autorizaci zdravotnické dokumentace při předávání | Do transakčního auditního logu se pochopitelně jako jedna událost zaznamená také informace o autorizaci záznamu zdravotnické dokumentace v elektronické podobě a výstupu v elektronické podobě s využitím správných validačních prvků podle § 55a odst. 4 ZZS | Požadavek souladu |
| ehispreq29 | Requirement | Opravy a doplnění existujícího záznamu novým svázaným záznamem | Opravy a doplnění autorizovaného záznamu se provádí novým záznamem a musí se provádět tak, aby bylo možné zjistit obsah záznamu před opravou. To se zajistí vazbou záznamů na sebe a provazbou v rámci transaločního auditního logu. | Požadavek souladu |
| ehispreq30 | Requirement | Záznam o opravě či doplnění již jednou autorizovaného záznamu zdravotnické dokumentace | Z auditního logu musí být jasné, že došlo k opravě jednou autorizovaného dřívejšího záznamu, to musí splňovat všechny věcné a technické náležitosti a musí být jasné, která verze záznamu je platná a vazba na předchozí záznam, oba pochopitelně autorizované. To platí i u autorizovaných výstupů předávaných ven. | Požadavek souladu |</datatables>

  * Tabulka se seznamem požadavků se postupně doplňuje a upravuje, jak si v rámci národní úrovně vyjasňujeme jednotlivé povinnosti a jejich dopad na [[Informační systém poskytovatele zdravotních služeb|ISPZS]], je vhodné ji průběžně sledovat.
  * Požadavky jsou vždy součástí aktuální verze architektonického modelu [[ArchiMate model ehealthuposkytovatele]].
