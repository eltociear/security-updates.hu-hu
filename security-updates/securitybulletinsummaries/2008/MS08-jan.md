---
TOCTitle: 'MS08-JAN'
Title: 'Microsoft biztonsági közlemény - összefoglalás, január 2008'
ms:assetid: 'ms08-jan'
ms:contentKeyID: 61227720
ms:mtpsurl: 'https://technet.microsoft.com/hu-HU/library/ms08-jan(v=Security.10)'
author: SharonSears
ms.author: SharonSears
---

Security Bulletin Summary

Microsoft biztonsági közlemény - összefoglalás, január 2008
===========================================================

Közzétéve: 2008. január 8. | Frissítve: 2008. január 25.

**Verzió:** 1.2

Az összefoglaló a 2008 januárjában kiadott biztonsági közleményeket összegzi.

A 2008. januári közlemények kiadása folytán az összefoglaló a 2008. január 3-án kiadott előzetes értesítés helyébe lép. A biztonsági közlemények kiadásáról szóló előzetes értesítés szolgáltatásról itt olvashat bővebben: [Előzetes értesítés a Microsoft biztonsági közleményeinek kiadásáról](http://technet.microsoft.com/security/bulletin/advance).

Ha automatikus értesítést szeretne kapni a Microsoft biztonsági közleményeinek megjelenéséről, fizessen elő a [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) szolgáltatásra.

A közleményekkel kapcsolatos kérdések megválaszolására a Microsoft 2008. január 9-én, csendes-óceáni idő szerint 11 órakor webes szemináriumot tart. [Jelentkezzen most a januári közleményeket bemutató webes szemináriumra](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357213&eventcategory=4&culture=en-us&countrycode=us). Ezt követően a webes szeminárium igény szerint kerül megrendezésre. További információkért látogasson el a [Microsoft biztonsági közleményeit és a webes szemináriumokat](http://technet.microsoft.com/security/bulletin/summary)bemutató oldalra.

A Microsoft abban is segítséget nyújt felhasználóinak, hogy a havi biztonsági közleményekkel azonos napon kiadott, nem biztonsági jellegű, de fontos frissítéseket megfelelően rangsorolhassák. Lásd az **Egyéb információ című részt**.

### A közleménnyel kapcsolatos információk

#### Összefoglalások

Az e havi biztonsági közlemények súlyossági sorrendben:

Kritikus (1)
------------

<span></span>
| Közlemény azonosítója                          | A Microsoft MS08-001 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                                                                                        |
|------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**A Windows TCP/IP protokolljának biztonsági rései távoli programkódfuttatásra adhatnak lehetőséget (941644)**](http://go.microsoft.com/fwlink/?linkid=104919)                                                                                                                                                                                                                                                                                                         |
| **Összefoglalás**                              | Ez a kritikus besorolású biztonsági frissítés két közvetlenül jelentett biztonsági rés hibáját szünteti meg az átvitelvezérlő protokoll/internetprotokoll (TCP/IP) feldolgozási folyamatában. Ha egy támadó kihasználja a biztonsági rést, teljes mértékben átveheti a rendszer irányítását. Ezt követően programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. |
| **Súlyosság maximális foka**                   | [Kritikus](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                |
| **A biztonsági rés hatása**                    | Távoli kódfuttatás                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. A frissítés a rendszer újraindítását igényli.                                                                                                                                                                                                                                                                                                                    |
| **Érintett szoftverek**                        | **Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                                                                                        |

Fontos (1)
----------

<span></span>
| Közlemény azonosítója                          | A Microsoft MS08-002 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**Az LSASS helyi jogok kiterjesztését okozó biztonsági rése (943485)**](http://go.microsoft.com/fwlink/?linkid=104921)                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Összefoglalás**                              | Ez a fontos besorolású frissítés a Microsoft Windows LSASS (Local Security Authority Subsystem Service) szolgáltatás közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rést kihasználó támadó magasabb szintű rendszerjogosultságokkal tetszőleges kódot futtathat az érintett rendszeren. Ha egy támadó kihasználja a biztonsági rést, teljes mértékben átveheti a rendszer irányítását. Ezt követően programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. |
| **Súlyosság maximális foka**                   | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **A biztonsági rés hatása**                    | Jogok helyi kiterjesztése                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. A frissítés a rendszer újraindítását igényli.                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Érintett szoftverek**                        | **Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |

Érintett szoftverek és letöltési helyek
---------------------------------------

<span></span>
**A táblázat használata**

A táblázat segítségével megtudhatja a szükséges információt a telepítendő biztonsági frissítésekről. Nézzen meg minden felsorolt szoftvert vagy összetevőt annak megállapításához, hogy van-e telepítendő biztonsági frissítés. Ha egy szoftver vagy összetevő szerepel a felsorolásban, akkor a biztonsági rés hatását is tartalmazza a táblázat az elérhető szoftverfrissítésre mutató hivatkozással együtt.

**Megjegyzés:** Előfordulhat, hogy egy biztonsági rés megszüntetéséhez több biztonsági frissítést kell telepíteni. Nézze át az egyes közleményazonosítókhoz tartozó teljes oszlopot, és ellenőrizze a telepítendő frissítéseket a rendszerre telepített programok vagy összetevők alapján.

**Érintett szoftverek és letöltési helyek**

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
Részletek        
</th>
<th style="border:1px solid black;" >
Részletek        
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-001**](http://go.microsoft.com/fwlink/?linkid=104919)
</td>
<td style="border:1px solid black;">
[**MS08-002**](http://go.microsoft.com/fwlink/?linkid=104921)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Súlyosság maximális foka**
</td>
<td style="border:1px solid black;">
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<th colspan="3">
Windows operációs rendszer:
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Mérsékelt.](http://www.microsoft.com/downloads/details.aspx?familyid=980f5457-c7b5-421c-8643-0e57429ec156)
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=7956632e-17d9-4876-8340-84fe3e43e5cc)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=0a766242-2342-4fa0-9b66-8953c54a2211)
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=6a4cf182-8e36-490e-aefe-edb7b3a0df9c)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition és Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=2e8bc7d5-fe81-4ed5-9efa-360738d160ee)
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=51fc657b-2b4a-4725-a744-d279e027c4a5)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2 rendszerhez
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=fda060a5-9a1e-4036-9899-13eb61fdd8be)
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=12397b47-b18f-4d4d-b8d7-adec8ff310d5)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2 rendszerhez
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=19d993f9-06dd-4dc4-b0cc-c59e822eb8fa)
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=f19fd790-a4e6-4a8a-8077-d1bbfe37ecca)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1 Itanium alapú rendszerekhez és Windows Server 2003 SP2 Itanium alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=2c2264f7-ebbb-40ab-9dbf-9b4e313665a7)
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=0382a195-aa3d-409b-8a79-9fe61588d8a9)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Small Business Server 2003 Service Pack 1, Windows Small Business Server 2003 R2, Windows Small Business Server 2003 R2 Service Pack 2 és Windows Home Server
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=fda060a5-9a1e-4036-9899-13eb61fdd8be)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=23c0e03a-db66-4618-bce0-af55e5c1b067)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=5f6a37b1-c604-47c9-932f-485db2eda133)
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>
 

Észlelési és telepítési eszközök, útmutatás
-------------------------------------------

<span></span>
**Biztonsági központ**

A szoftveres és biztonsági frissítések kezeléséhez azokat a szervezet asztali és hordozható számítógépeire, valamint kiszolgálóira is telepíteni kell. További tájékoztatásért látogasson el a [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) weboldalára. A [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) bővebb tájékoztatással szolgál a Microsoft-termékek biztonsági funkcióival kapcsolatban. A [Biztonság otthon](http://go.microsoft.com/fwlink/?linkid=85102) weboldalon a megfelelő hivatkozásra kattintva elérhetőek a legújabb biztonsági frissítések.

A biztonsági frissítések a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) és az [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) weboldalakról tölthetőek le. A biztonsági frissítések a [Microsoft letöltőközpontjában](http://go.microsoft.com/fwlink/?linkid=21129) is elérhetőek. Legegyszerűbben a „security update” kifejezésre irányuló kulcsszavas kereséssel találhatja meg ezeket.

A biztonsági frissítések a [Microsoft Update katalógusából](http://go.microsoft.com/fwlink/?linkid=96155) is letölthetőek. A Microsoft Update katalógus a Windows Update és Microsoft Update szolgáltatáson keresztül elérhető tartalom kereshető adatbázisa; ide tartoznak a biztonsági frissítések, illesztőprogramok és szervizcsomagok. A biztonsági közlemény számára (pl. „MS07-036”) történő kereséssel hozzáadhatja az összes vonatkozó frissítést a kosárhoz (beleértve a frissítés különböző nyelvi változatait), és letöltheti azokat a megadott mappába. A Microsoft Update katalógus részletes leírását lásd a vonatkozó [GYIK](http://go.microsoft.com/fwlink/?linkid=97900)részben.

**Útmutató az észleléshez és a telepítéshez**

A Microsoft az e havi biztonsági frissítésekhez észlelési és telepítési útmutatót adott ki. Az útmutató a számítógépes szakembereknek is ötleteket adhat ahhoz, hogyan használják a különböző eszközöket, pl. Windows Update, Microsoft Update, Office Update, Microsoft Baseline Security Analyzer (MBSA), Office Detection Tool, Microsoft Systems Management Server (SMS) és Extended Security Update Inventory Tool (ESUIT) a biztonsági frissítések telepítéséhez. További információt a [Microsoft Tudásbázis 910723. számú cikkében](http://support.microsoft.com/kb/910723) talál.

**Microsoft Baseline Security Analyzer**

A Microsoft Baseline Security Analyzer (MBSA) segítségével a rendszergazda mind a helyi, mind a távoli számítógépeken ellenőrizheti, hogy mely biztonsági frissítések hiányoznak, illetve hogy mely biztonsági beállítások vannak helytelenül megadva. Ha többet szeretne tudni az MBSA -eszközről, látogasson el a [Microsoft Baseline Security Analyzer webhelyre](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

A Microsoft Software Update Services (WSUS) szolgáltatással a rendszergazdák gyorsan és megbízható módon telepíthetik központilag a legújabb fontos és biztonsági frissítéseket Windows 2000 és újabb operációs rendszerekhez, Office XP és újabb operációs rendszerekhez, Exchange Server 2003 és SQL Server 2000 Windows 2000 és újabb operációs rendszerekre.

A biztonsági frissítésnek Windows Server Update Services szolgáltatással történő központi telepítéséről a [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) webhelyen tudhat meg többet.

**Systems Management Server**

A Microsoft Systems Management Server (SMS) rendszer egy sokoldalúan beállítható vállalati megoldás, amely a frissítések kezelésére szolgál. Az SMS segítségével a rendszergazda megállapíthatja, hogy melyik Windows alapú számítógép szorul biztonsági frissítésre, és ezeket a frissítéseket szabályozott módon, a felhasználók minimális zavarásával központilag telepítheti a vállalat teljes informatikai környezetében. Az SMS, vagyis a System Center Configuration Manager 2007 újabb kiadása immáron elérhető, lásd még: [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860,aspx). Arról, hogy a rendszergazdák hogyan használhatják a biztonsági frissítések telepítéséhez az SMS 2003 alkalmazást, az [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939) részben olvashat. Az SMS 2.0 verzióját használók a [Software Updates Services Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) szolgáltatásait is segítségül hívhatják a biztonsági frissítések központi telepítéséhez. Az SMS-szolgáltatásról bővebben a [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) oldalán olvashat.

**Megjegyzés:** Az SMS a Microsoft Baseline Security Analyzer és a Microsoft Office Detection Tool program segítségével széles körű támogatást nyújt a frissítések biztonsági értesítők segítségével történő észleléséhez és telepítéséhez. Előfordulhat, hogy egyes szoftverfrissítéseket ezek az eszközök nem észlelnek. Az SMS alkalmazás leltározási szolgáltatásai segítségével a rendszergazdák adott rendszereken hajthatják végre a frissítést. Az eljárással kapcsolatban olvassa el a [szoftverfrissítések telepítése az SMS szoftverelosztó ügynök segítségével](http://go.microsoft.com/fwlink/?linkid=33341) című tájékoztatót. Egyes biztonsági frissítésekhez rendszergazdai jogosultságokra van szükség a számítógép újraindítása után. A rendszergazdák az [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) és az [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) csomag részét képező Elevated Rights Deployment Tool nevű eszközzel telepíthetik ezeket a frissítéseket.

### Egyéb információ

#### A Microsoft Windows rosszindulatú szoftvereket eltávolító eszköze

A Microsoft a Windows Update, Microsoft Update, Windows Server Update Services és Letöltőközpont szolgáltatásán keresztül elérhetővé tette a Microsoft Windows rosszindulatú szoftvereket eltávolító eszközének frissített változatát.

#### Nem biztonsági jellegű, kiemelt fontosságú frissítések a MU, WU és WSUS-szolgáltatásokban

Ebben a hónapban:

-   A Microsoft a Microsoft Update (MU) és a Windows Server Update Services (WSUS) szolgáltatáson keresztül öt **nem biztonsági jellegű**, kiemelt fontosságú frissítést adott ki.
-   A Microsoft a Windows Update (WU) és a WSUS szolgáltatáson keresztül két **nem biztonsági jellegű**, kiemelt fontosságú Windows-frissítést adott ki.

Felhívjuk figyelmét, hogy a tájékoztatás **kizárólag** a biztonsági frissítéseket összegző kiadvánnyal azonos napon kiadott, **nem biztonsági jellegű**, a Microsoft Update, Windows Update, Windows Server Update Services szolgáltatásokon keresztül elérhető, kiemelt fontosságú frissítésekre vonatkozik. A más napokon kiadott, **nem biztonsági jellegű** frissítésekről tájékoztatást **nem** nyújtunk.

#### Biztonsági stratégiák és közösségek

**Frissítésekkel kapcsolatos stratégiák**

[A javítások telepítésére vonatkozó útmutatás](http://go.microsoft.com/fwlink/?linkid=21168) a Microsoft által a biztonsági frissítések telepítéséhez ajánlott legjobban bevált eljárást ismerteti.

**Egyéb biztonsági frissítések beszerzése**

Az alábbi helyekről más típusú biztonsági problémákhoz szerezhetők be frissítések.

-   A biztonsági frissítések a [Microsoft letöltőközpontban](http://go.microsoft.com/fwlink/?linkid=21129) érhetők el. Legegyszerűbben a „security update” kifejezésre irányuló kulcsszavas kereséssel találhatja meg ezeket.
-   Az ügyfélrendszerek frissítései a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) oldalról elérhetőek.
-   A Windows Update szolgáltatáson keresztül terjesztett havi aktuális biztonsági frissítések a letöltőközpontból a biztonsági és kritikus frissítéseket tartalmazó ISO CD-képfájlként is letölthetőek. További információt a [Microsoft Tudásbázis 913086](http://support.microsoft.com/kb/913086) számú cikkében talál.

**IT Pro Security közösség**

Az [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) közösségben hasznos információt találhat a biztonság javításáról és az informatikai infrastruktúrák optimalizálásáról, továbbá eszmecserét folytathat a biztonsági kérdésekről más informatikai szakemberekkel.

#### Köszönetnyilvánítás

A Microsoft [köszönetét](http://go.microsoft.com/fwlink/?linkid=21127) fejezi ki a vásárlók védelmének biztosításában nyújtott segítségért az alábbi szervezet(ek)nek és szakember(ek)nek:

-   [IBM Internet Security Systems X-Force](http://www.iss.net/), Alex Wheeler és Ryan Smith, az [MS08-001](http://go.microsoft.com/fwlink/?linkid=104919) közleményben ismertetett probléma jelentéséért
-   [IBM Internet Security Systems X-Force](http://www.iss.net/), Alex Wheeler és Ryan Smith, az [MS08-001](http://go.microsoft.com/fwlink/?linkid=104919) közleményben ismertetett probléma jelentéséért
-   Thomas Garnier, [SkyRecon](http://www.skyrecon.com/), az [MS08-002](http://go.microsoft.com/fwlink/?linkid=104921) közleményben ismertetett probléma jelentéséért

#### Terméktámogatás

-   Teszteléssel állapították meg a felsorolt szoftverek egyes verzióinak érintettségét. A többi verzió támogatási életciklusa végére ért. Az egyes szoftververziók támogatási életciklusáról a [Microsoft termékek terméktámogatási életciklusát ismertető webhelyen](http://go.microsoft.com/fwlink/?linkid=21742) talál felvilágosítást.
-   Az Amerikai Egyesült Államokban és Kanadában technikai segítség igényelhető a [Microsoft terméktámogatási szolgáltatásától](http://go.microsoft.com/fwlink/?linkid=21131), amelynek telefonszáma 1-866-PCSAFETY. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek.
-   Más országokban a helyi Microsoft-képviseletek nyújtanak támogatást. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. A [nemzetközi támogatási webhely](http://go.microsoft.com/fwlink/?linkid=21155) felvilágosítást nyújt arról, támogatási kérdéseivel hogyan fordulhat a Microsofthoz.

#### Felelősséget kizáró nyilatkozat

A Microsoft Tudásbázisban leírtak előzetes bejelentés nélkül változhatnak, és a cikkek tartalmáért a Microsoft nem vállal garanciát. A Microsoft egyben elhárít minden kifejezett és értelemszerű garanciát, beleértve az eladhatóságra és az adott célra való alkalmasságra vonatkozó garanciát is. A Microsoft Corporation vagy annak szállítói semmilyen körülmények között nem tehetők felelőssé közvetlen, közvetett, eseti, ok-okozati vagy különleges kárért (beleértve az elmaradt hasznot is), még akkor sem, ha a Microsoft Corporation vagy szállítói tudatában voltak a kár lehetséges voltának. Egyes államok törvényi szabályozása nem teszi lehetővé a véletlen vagy ok-okozati károkért vállalt felelősség korlátozását vagy kizárását, így ezekben az államokban az ez a felelősségkizárás nincs érvényben.

#### Verziók

-   1.0 verzió (2008. január 8.): Összefoglaló közlemény közzététele.
-   1.1 verzió (2008. január 23.): A frissített összesítő közlemény az MS08-001 közleménynél már érintettként jelöli a Windows Small Business Server 2003 Service Pack 2 rendszert.
-   1.2 verzió (2008. január 25.): A frissített összesítő közleményben a Windows Small Business Server 2003 Service Pack 1, Windows Small Business Server 2003 R2, Windows Small Business Server 2003 R2 Service Pack 2 és Windows Home Server alkalmazás az MS08-001 közlemény vonatkozásában már érintett szoftverként szerepel.

*Built at 2014-04-18T01:50:00Z-07:00*
