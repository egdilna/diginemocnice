Prezentace pro workshop [[26.2.2026: Workshop diginemocnice.cz - Funkce a požadavky na ISPZS [7 - Proběhlo]]]

Michal Rada a kolektiv

Určeno nejen pro nemocnice, ale pro všechny zainteresované do rozvoje EZ a ISPZS

[[Akce a workshopy Diginemocnice.cz]]

## O čem to dneska bude

1. Co je ISPZS, co je NIS a co všechno vlastně v nemocnicích řešíme za zdravotnické systémy
2. Typizovaný ISPZS, co dělá a jak to dělá a jak by to měl dělat v rámci eZdravotnictví
3. Jaké jsou povinnosti poskytovatelů realizované jejich informačními systémy
4. Typické integrace s okolím a především se systémy EZ a jak na ně
5. Aplikační architektura a integrace ve státní nemocnici
6. Typické požadavky na dodavatele a co znamenají

## Důležité je i to, o čem to dneska nebude

Dnes to nebude o **elektronické zdravotnické dokumentaci**, protože k tomu **dva Michalové** připravují pak samostatný workshop, protože je to docela složitá problematika.

* Trochu to zmíníme, ale ryze z technického hlediska
* Bude jedno z témat konference [[2026-03-18-19-konference-senohraby]]
* A my speciálně pro nemocnice budeme mít letos jeden workshop jen k tématům kolem EZD

## Co nás eČeká?

Rámcový přehled získáme třeba z [[Legislativní rámec EZ]]

* Plnění [[Centrální služby elektronického zdravotnictví|centrálních služeb]]
* Musíme zajistit [[Seznam povinností z eZdravotnictví pro poskytovatele|Seznam poviností z eZdravotnictví pro poskytovatele]]
* A zejména [[Výměna dat v rámci eZdravotnictví]]

## Jaké systémy jsou v typické nemocnici

* Nemocniční IS, tedy systém s údaji k pacientům a co děláme a službám a vykazování a tak
* Lékárenský IS: výdej lidem z chodníku i výdej v rámci nemocnice
* Laboratorní IS: zpracování surových dat, výsledky, interpretace a vazba na EZD
* PAX a další zobrazovací data: a to včetně jejich zpracování a vázání na EZD a pacienta

## ISPZS co to je a proč

Jde o informační systém, ve kterém se zejména uchovává a vede [Elektronická zdravotnická dokumentace](https://egdwiki.info/diginemocnice:elektronicka-zdravotnicka-dokumentace) a [Poskytovatel zdravotních služeb](https://egdwiki.info/diginemocnice:poskytovatel-zdravotnich-sluzeb) s jeho pomocí vykonává zdravotní služby.

Požadavky na tento informační systém stanovuje zejména [325/2021 Sb. (zákon o eZdravotnictví)](https://egdwiki.info/predpis:325-2021) a [372/2011 Sb. (zákon o zdravotních službách)](https://egdwiki.info/predpis:372-2011) a také i [Standardy elektronického zdravotnictví](https://egdwiki.info/diginemocnice:standardy-ez).

Zásadními oblastmi, na které se při rozvoji tohoto informačního systému musí klást důraz, jsou zejména [Výměna dat v rámci eZdravotnictví](https://egdwiki.info/diginemocnice:vymena-dat-v-ramci-ezdravotnictvi), [vedení zdravotnické dokumentace v ISPZS](https://egdwiki.info/drafts:vedeni-zdravotnicke-dokumentace-v-ispzs), nebo [Autorizace zdravotnické dokumentace](https://egdwiki.info/diginemocnice:autorizace-zdravotnicke-dokumentace). Postupně se kupříkladu pro praktickou pomoc dodavatelům i poskytovatelům vytváří [Rámcové požadavky pro ISPZS týkající se služeb EZ a interoperability](https://egdwiki.info/diginemocnice:navrh-pozadavky-ispzs-interoperabilita).

Jde o informační systém, který se musí propojit s některými systémy elektronického zdravotnictvó, aby poskytovatel splnil příslušné povinnosti. Tedy poskytovatel zajistí tyto [Typické integrace ISPZS na informační systémy elektronického zdravotnictví](https://egdwiki.info/diginemocnice:typicke-integrace-ispzs-na-is-ez).

## Takový typizovaný ISPZS...

Co má ISPZS dělat? K čemu slouží a co od něj z pohledu aplikační architektury čekáme?

...tady nebudeme teoretizovat, ale podíváme se do živé referenční architektury na model [[ArchiMate model ehealthuposkytovatele]]

## Kam a proč se ISPZS musí a má integrovat

Vnitřní integrace: na ekonimiku, na lékárnu, na sklady, na stravování, na výkaznictví

Vnější: na služby EZ přes IDRR, na eRecept, na eŽádanky, na úložiště EP, na NZIS, na ISIN a na ostatní ISPZS přes výměnnou síť

Souhrn je také na [[Typické integrace ISPZS na IS EZ|Typické integrace ISPZS na informační systémy elektronického zdravotnictví]]

...Ale my se zase mrkneme i do architektury

## A u nemocnic pak máme více druhů výměny dat

Nemocnice má defacto tři dost oddělené důvody a formy výměny dat ve zdravotnictví:

1. Nemocnice a jiní poskytovatelé (třeba propouštěcí zpráva)
2. Nemocnice a záchranka (záznam výjezdu a akutní ZZS)
3. Nemocnice jako realizátor vyřešení (vlastně eŽádanky)

1 a 3 řeší povinné služby EZ a to zejména Výměnná síť a eŽádanka a vrácení výsledku výměnnou sítí

2 přímou regulaci nemá, existují základní standardy, ale ne pro vše a teprve se zabýváme technickými požadavky, ale máme úkol ve strategii (SC 3.4)

## Konkrétní požadavky na ISPZS

A jak do toho?

Co takhle znáte nějaké připravené požadavky na ISPZS, resp na dodavatele?

...a zase se mrkněme do architektury...
