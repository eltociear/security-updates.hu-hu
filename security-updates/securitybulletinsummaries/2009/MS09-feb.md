---
TOCTitle: 'MS09-FEB'
Title: 'Microsoft biztonsági közlemény - összefoglalás, február 2009'
ms:assetid: 'ms09-feb'
ms:contentKeyID: 61227729
ms:mtpsurl: 'https://technet.microsoft.com/hu-HU/library/ms09-feb(v=Security.10)'
author: SharonSears
ms.author: SharonSears
---

Security Bulletin Summary

Microsoft biztonsági közlemény - összefoglalás, február 2009
============================================================

Közzétéve: 2009. február 10. | Frissítve: 2009. február 25.

**Verzió:** 2.1

Az összefoglaló a 2009 februárjában kiadott biztonsági közleményeket összegzi.

A 2009. februári közlemények kiadása folytán az összefoglaló a 2009. február 5-én kiadott előzetes értesítés helyébe lép. A biztonsági közlemények kiadásáról szóló előzetes értesítés szolgáltatásról itt olvashat bővebben: [Előzetes értesítés a Microsoft biztonsági közleményeinek kiadásáról](http://technet.microsoft.com/security/bulletin/advance).

Ha automatikus értesítést szeretne kapni a Microsoft biztonsági közleményeinek megjelenéséről, fizessen elő a [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) szolgáltatásra.

A közleményekkel kapcsolatos kérdések megválaszolására a Microsoft 2009. február 11-én, csendes-óceáni idő szerint 11 órakor webes szemináriumot tart. Jelentkezzen most a [februári közleményeket bemutató webes szemináriumra](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395122). Ezt követően a webes szeminárium igény szerint kerül megrendezésre. További információkért látogasson el a [Microsoft biztonsági közleményeit és a webes szemináriumokat](http://technet.microsoft.com/security/bulletin/summary)bemutató oldalra.

A Microsoft abban is segítséget nyújt felhasználóinak, hogy a havi biztonsági közleményekkel azonos napon kiadott, nem biztonsági jellegű, de fontos frissítéseket megfelelően rangsorolhassák. Lásd az **Egyéb információ című részt**.

### A közleménnyel kapcsolatos információk

Összefoglalások
---------------

<span></span>
A következő táblázat összegzi az e havi biztonsági közleményeket súlyossági sorrendben.

Az érintett szoftverekkel kapcsolatban további tudnivalókat a következő, az **Érintett szoftverek és letöltési helyek** című részben talál.

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Közlemény azonosítója</th>
<th style="border:1px solid black;" >Közlemény címe és összefoglalás</th>
<th style="border:1px solid black;" >Súlyosság maximális foka és a biztonsági rés hatása</th>
<th style="border:1px solid black;" >Újraindítás szükségessége</th>
<th style="border:1px solid black;" >Érintett szoftverek</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139814">MS09-002</a></td>
<td style="border:1px solid black;"><strong>Összesítő biztonsági frissítés az Internet Explorer programhoz (961260)</strong><br />
<br />
A biztonsági frissítés két közvetlenül jelzett biztonsági rést szüntet meg. A biztonsági rések mindegyike távoli kódvégrehajtást tehet lehetővé, amennyiben a felhasználó egy különlegesen kialakított weboldalt tekint meg az Internet Explorer alkalmazás segítségével. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=136636">MS09-003</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Exchange biztonsági rései távolról történő programkódfuttatást tesznek lehetővé (959239)</strong><br />
<br />
Ez a kritikus besorolású frissítés a Microsoft Exchange Server két közvetlenül jelzett biztonsági rését szünteti meg. Az első biztonsági rés programkód távoli futtatását teheti lehetővé, amennyiben különlegesen kialakított TNEF-üzenetet küldenek egy Microsoft Exchange Server alkalmazásnak. A biztonsági rést sikeresen kihasználó támadó teljesen átveheti az érintett rendszer irányítását, mindezt Exchange Server szolgáltatási fiókjogosultságokkal. A második biztonsági rés szolgáltatásmegtagadást okozhat, ha egy különlegesen kialakított MAPI-parancsot küldenek egy Microsoft Exchange Server kiszolgálóra. A biztonsági rést sikeresen kihasználó támadó a Microsoft Exchange System Attendant szolgáltatás és egyéb, az EMSMDB32 funkciót használó rendszerek válaszadásának megtagadását okozhatja.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139513">MS09-004</a></td>
<td style="border:1px solid black;"><strong>A Microsoft SQL Server biztonsági rése távoli kódfuttatást tehet lehetővé (959420)</strong><br />
<br />
A biztonsági frissítés a Microsoft SQL Server közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rés akkor ad lehetőséget távoli kódfuttatásra, ha nem megbízható felhasználók hozzáférnek az érintett rendszerhez, illetve ha azon az SQL-beszúrási biztonsági rést kihasználó támadás történik. A SQL Server 7.0 Service Pack 4, SQL Server 2005 Service Pack 3 és az SQL Server 2008 rendszereket a probléma nem érinti.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128107">MS09-005</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Office Visio biztonsági rése távolról történő programkódfuttatást tehet lehetővé (957634)</strong><br />
<br />
A kritikus biztonsági frissítés a Microsoft Office Visio három, közvetlenül a Microsoftnak jelzett biztonsági rését szünteti meg, melyek távoli kódfuttatást tesznek lehetővé, amennyiben a felhasználó megnyit egy speciálisan létrehozott Visio fájlt. Ha egy támadó kihasználja a biztonsági rést, teljes mértékben átveheti a rendszer irányítását. Ezt követően a támadó programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
Kihasználhatósági információk  
-----------------------------
  
<span></span>
A következő táblázat az adott hónapban megoldott biztonsági rések kihasználhatósági jellemzőit ismerteti. A biztonsági rések a közlemény azonosítója és súlyossági besorolás azonosítója szerint vannak felsorolva.
  
**A táblázat használata**
  
A táblázat segítségével meghatározható annak valószínűsége, hogy a biztonsági közlemény kiadását követő 30 napon belül a telepíteni szükséges biztonsági frissítésekre működő rosszindulatú programkódot jelentetnek meg. A telepítés fontossági sorrendjének megállapításához az adott konfigurációnak megfelelően tekintse át az alábbi értékeléseket. A minősítések jelentéséről és meghatározásuk módjáról a [Microsoft biztonsági rések jegyzéke](http://technet.microsoft.com/en-us/security/cc998259.aspx) tartalmaz bővebb információt.
  
| Közlemény azonosítója                                     | Közlemény címe                                                                                        | CVE-azonosító                                                                    | Kihasználhatósági információk értékelése                                                                                 | Fontos megjegyzések                                                                                                                                                      |  
|-----------------------------------------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-002](http://go.microsoft.com/fwlink/?linkid=139814) | Összesítő biztonsági frissítés az Internet Explorer programhoz (961260)                               | [CVE-2009-0075](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0075) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | A konzisztens rosszindulatú programkód könnyen kialakítható.                                                                                                             |  
| [MS09-002](http://go.microsoft.com/fwlink/?linkid=139814) | Összesítő biztonsági frissítés az Internet Explorer programhoz (961260)                               | [CVE-2009-0076](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0076) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | A konzisztens rosszindulatú programkód könnyen kialakítható.                                                                                                             |  
| [MS09-003](http://go.microsoft.com/fwlink/?linkid=136636) | A Microsoft Exchange biztonsági rései távolról történő programkódfuttatást tesznek lehetővé (959239)  | [CVE-2009-0098](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0098) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                                                                                                                                  |  
| [MS09-003](http://go.microsoft.com/fwlink/?linkid=136636) | A Microsoft Exchange biztonsági rései távolról történő programkódfuttatást tesznek lehetővé (959239)  | [CVE-2009-0099](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0099) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | Ez a biztonsági rés szolgáltatásmegtagadást okoz. A biztonsági rést kihasználó támadások valószínűleg csak szolgáltatásmegtagadáshoz vezetnek, távoli kódfuttatást nem.  |  
| [MS09-004](http://go.microsoft.com/fwlink/?linkid=139513) | A Microsoft SQL Server biztonsági rése távoli kódfuttatást tehet lehetővé (959420)                    | [CVE-2008-5416](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-5416) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | Közzétett, hitelesítés utáni, működő rosszindulatú programkód.                                                                                                           |  
| [MS09-005](http://go.microsoft.com/fwlink/?linkid=128107) | A Microsoft Office Visio biztonsági rése távolról történő programkódfuttatást tehet lehetővé (957634) | [CVE-2009-0095](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0095) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                                                                                                                                  |  
| [MS09-005](http://go.microsoft.com/fwlink/?linkid=128107) | A Microsoft Office Visio biztonsági rése távolról történő programkódfuttatást tehet lehetővé (957634) | [CVE-2009-0096](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0096) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                                                                                                                                  |  
| [MS09-005](http://go.microsoft.com/fwlink/?linkid=128107) | A Microsoft Office Visio biztonsági rése távolról történő programkódfuttatást tehet lehetővé (957634) | [CVE-2009-0097](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0097) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                                                                                                                                  |
  
Érintett szoftverek és letöltési helyek  
---------------------------------------
  
<span></span>
A következő táblázatok a közleményeket a főbb szoftverkategóriák és súlyosság szerint sorolják fel.
  
**A táblázatok használata**
  
A táblázatok segítségével megtudhatja a szükséges információt a telepítendő biztonsági frissítésekről. Nézzen meg minden felsorolt szoftvert vagy összetevőt annak megállapításához, hogy elérhető-e a rendszerhez való frissítés. Ha a szoftver vagy összetevő szerepel a listán, hiperhivatkozással kapcsolódik hozzá az elérhető szoftverfrissítés, és a frissítés besorolása is fel van tüntetve.
  
**Megjegyzés:** Előfordulhat, hogy egy biztonsági rés megszüntetéséhez több biztonsági frissítést kell telepíteni. Nézze át az egyes közleményazonosítókhoz tartozó teljes oszlopot, és ellenőrizze a telepítendő frissítéseket a rendszerre telepített programok vagy összetevők alapján.
  
#### A Windows operációs rendszer és összetevői

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="3">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://go.microsoft.com/fwlink/?linkid=139814)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://go.microsoft.com/fwlink/?linkid=139513)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2 és Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8cd902ec-e018-4b61-80f9-825d973f998e)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition és Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=dd3e2236-9cc0-478e-a46c-981ef685c0e3)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://go.microsoft.com/fwlink/?linkid=139814)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://go.microsoft.com/fwlink/?linkid=139513)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
[**Mérsékelt**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2 rendszerhez
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e52aa1fd-e694-4322-b3ff-6abc1b4a16fe)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine (WMSDE)](http://www.microsoft.com/downloads/details.aspx?familyid=218809d6-a9fb-408b-a34d-ab2ac786994c)  
(KB960082)  
(Fontos)  
[Windows Internal Database (WYukon) Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=16925be5-98d0-446b-9bbc-d9a2d335c69e)  
(KB960089)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2 rendszerhez
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=edbf1566-b96b-4c7d-98fe-b15f8e766792)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Microsoft SQL Server 2000 Desktop Engine (WMSDE)](http://www.microsoft.com/downloads/details.aspx?familyid=87183155-6770-4ea2-acca-191de4d40d27)  
(KB960082)  
(Fontos)  
[Windows Internal Database (WYukon) x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=05c5c265-cfd7-4364-b323-77650b7f1e67)  
(KB960089)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1 Itanium alapú rendszerekhez és Windows Server 2003 SP2 Itanium alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5ce78797-d1c0-40d4-84e1-1004389833be)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://go.microsoft.com/fwlink/?linkid=139814)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://go.microsoft.com/fwlink/?linkid=139513)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista és Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5f9fa4b6-85a4-43bc-b84f-6bd847799650)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition és Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e9a8c94b-b9d2-4d64-855f-b5f02ce3dfb5)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-002**](http://go.microsoft.com/fwlink/?linkid=139814)
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://go.microsoft.com/fwlink/?linkid=139513)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
[**Mérsékelt**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 32 bites rendszerekhez
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2491dbf2-7cd3-44f1-bfad-77e6f760a25c)\*\*  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Windows Internal Database (WYukon) Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=16925be5-98d0-446b-9bbc-d9a2d335c69e)\*  
(KB960089)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 x64 alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=794373cc-2dce-4ef5-af50-7804c622c230)\*\*  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Windows Internal Database (WYukon) x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=05c5c265-cfd7-4364-b323-77650b7f1e67)\*  
(KB960089)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 Itanium alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=11985325-4b33-4077-82cf-6afc7a71c510)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
</table>
 
**Megjegyzések a Windows Server 2008 rendszerhez**

**\*Érinti a Windows Server 2008 kiszolgálómag-telepítését.** A frissítés besorolása ugyanaz a Windows Server 2008 támogatott kiadásain függetlenül attól, hogy a Windows Server 2008 alkalmazást a kiszolgálómag-telepítési opcióval telepítették-e. További tudnivalókat ezzel a telepítési beállítással kapcsolatban a következő weboldalon talál:[Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). A Server Core telepítési beállítás a Windows Server 2008 egyes kiadásainál nem alkalmazható. További tudnivalók: [Server Core telepítési beállítások összehasonlítása](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Nem érinti a Windows Server 2008 kiszolgálómag-telepítését.** A frissítésben tárgyalt biztonsági rések nem érintik a Windows Server 2008 támogatott kiadásait, amennyiben a Windows Server 2008 telepítése a kiszolgálómag-telepítési opció használatával történt. További tudnivalókat ezzel a telepítési beállítással kapcsolatban a következő weboldalon talál:[Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). A Server Core telepítési beállítás a Windows Server 2008 egyes kiadásainál nem alkalmazható. További tudnivalók: [Server Core telepítési beállítások összehasonlítása](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Megjegyzés az MS09-004 közleményhez**

További frissített fájlokat a **Microsoft Server Software** című részben talál. Ez a közlemény egyszerre tárgyalja a Windows operációs rendszert és annak összetevőit, valamint a Microsoft Server szoftverelemeit.

#### Microsoft Server Software

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-003**](http://go.microsoft.com/fwlink/?linkid=136636)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange 2000 Server
</td>
<td style="border:1px solid black;">
[Microsoft Exchange 2000 Server Service Pack 3, 2004 augusztusi összegző frissítőcsomaggal](http://www.microsoft.com/downloads/details.aspx?familyid=805dc856-ea60-477d-be40-6ac535a7e7e5)  
(KB959897)  
(Kritikus)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server 2003
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1d9f0956-88bd-4e13-a86b-b1c8d4782f71)\*  
(KB959897)  
(Kritikus)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=93cb3f66-ae72-4356-bdbf-35029cff6df1)\*\*  
(KB959241)  
(Kritikus)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Exchange Server MAPI ügyfél és Collaboration Data Objects 1.2.1
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server MAPI ügyfél és Collaboration Data Objects 1.2.1](http://www.microsoft.com/downloads/details.aspx?familyid=e17e7f31-079a-43a9-bff2-0a110307611e)\*\*\*  
(Kritikus)
</td>
</tr>
</table>
 
**Megjegyzések az MS09-003 közleménnyel kapcsolatban**

\*Az Exchange Server 2003 rendszerhez tartozó Microsoft Exchange rendszerkezelő eszközöket is tartalmazza, ha a kiszolgálón az Exchange szolgáltatás aktív példánya fut.

\*\*A 32 bites és az x64 alapú verziókat is tartalmazza

\*\*\*A fenyegetett kódot a Microsoft Exchange Server MAPI ügyfele tartalmazza. Az MS09-003 közleményben ismertetett problémákkal szembeni védettség érdekében a Microsoft Exchange Server MAPI ügyfél felhasználóinak a MAPI ügyfél 6.5.8069 verziószámú változatára kell frissíteniük. 

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft SQL Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-004**](http://go.microsoft.com/fwlink/?linkid=139513)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
GDR-frissítés:  
[SQL Server 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c)  
(KB960082)  
(Fontos)  
QFE-frissítés:  
[SQL Server 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a)  
(KB960083)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2000 Itanium alapú kiadás, Service Pack 4
</td>
<td style="border:1px solid black;">
GDR-frissítés:  
[SQL Server 2000 Itanium alapú kiadás, Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c)  
(KB960082)  
(Fontos)  
QFE-frissítés:  
[SQL Server 2000 Itanium alapú kiadás, Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a)  
(KB960083)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Service Pack 2
</td>
<td style="border:1px solid black;">
GDR-frissítés:  
[SQL Server 2005 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(Fontos)  
QFE-frissítés:  
[SQL Server 2005 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
GDR-frissítés:  
[SQL Server 2005 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(Fontos)  
QFE-frissítés:  
[SQL Server 2005 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 SP2 Itanium alapú rendszerekhez
</td>
<td style="border:1px solid black;">
GDR-frissítés:  
[SQL Server 2005 SP2 Itanium alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(Fontos)  
QFE-frissítés:  
[SQL Server 2005 SP2 Itanium alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4
</td>
<td style="border:1px solid black;">
GDR-frissítés:  
[Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c)  
(KB960082)  
(Fontos)  
QFE-frissítés:  
[Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a)  
(KB960083)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
SQL Server 2005 Express Edition Service Pack 2
</td>
<td style="border:1px solid black;">
GDR-frissítés:  
[SQL Server 2005 Express Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(Fontos)  
QFE-frissítés:  
[SQL Server 2005 Express Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
SQL Server 2005 Express Edition rendszer Advanced Services Service Pack 2 csomaggal
</td>
<td style="border:1px solid black;">
GDR-frissítés:  
[SQL Server 2005 Express Edition rendszer Advanced Services Service Pack 2 csomaggal](http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e)  
(KB960089)  
(Fontos)  
QFE-frissítés:  
[SQL Server 2005 Express Edition rendszer Advanced Services Service Pack 2 csomaggal](http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a)  
(KB960090)  
(Fontos)
</td>
</tr>
</table>
 
**Megjegyzés az MS09-004 közleményhez**

További frissített fájlokat **A Windows operációs rendszer és összetevői** című részben talál. Ez a közlemény egyszerre tárgyalja a Windows operációs rendszert és annak összetevőit, valamint a Microsoft Server szoftverelemeit.

#### Microsoft Office programcsomagok és szoftverek

 
<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2">
Microsoft Office Visio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-005**](http://go.microsoft.com/fwlink/?linkid=128107)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Visio 2002
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2002 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a30cef3f-9eaf-45bd-9a25-4b65302362cb)  
(KB955654)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Visio 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c9cb589e-1a37-485d-8402-7f42bcd7a1a9)  
(KB955655)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Visio 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office Visio 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=4b711e89-8de2-4f17-8afc-691e0604ff82)  
(KB957831)  
(Fontos)
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

A Microsoft Systems Management Server (SMS) rendszer egy sokoldalúan beállítható vállalati megoldás, amely a frissítések kezelésére szolgál. Az SMS segítségével a rendszergazda megállapíthatja, hogy melyik Windows alapú számítógép szorul biztonsági frissítésre, és ezeket a frissítéseket szabályozott módon, a felhasználók minimális zavarásával központilag telepítheti a vállalat teljes informatikai környezetében. Az SMS, vagyis a System Center Configuration Manager 2007 újabb kiadása immáron elérhető, lásd még: [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Arról, hogy a rendszergazdák hogyan használhatják a biztonsági frissítések telepítéséhez az SMS 2003 alkalmazást, az [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939) részben olvashat. Az SMS 2.0 verzióját használók a [Software Updates Services Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) szolgáltatásait is segítségül hívhatják a biztonsági frissítések központi telepítéséhez. Az SMS-szolgáltatásról bővebben a [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) oldalán olvashat.

**Megjegyzés:** Az SMS a Microsoft Baseline Security Analyzer és a Microsoft Office Detection Tool program segítségével széles körű támogatást nyújt a frissítések biztonsági értesítők segítségével történő észleléséhez és telepítéséhez. Előfordulhat, hogy egyes szoftverfrissítéseket ezek az eszközök nem észlelnek. Az SMS alkalmazás leltározási szolgáltatásai segítségével a rendszergazdák adott rendszereken hajthatják végre a frissítést. Az eljárással kapcsolatban olvassa el a [szoftverfrissítések telepítése az SMS szoftverelosztó ügynök segítségével](http://go.microsoft.com/fwlink/?linkid=33341) című tájékoztatót. Egyes biztonsági frissítésekhez rendszergazdai jogosultságokra van szükség a számítógép újraindítása után. A rendszergazdák az [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) és az [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) csomag részét képező Elevated Rights Deployment Tool nevű eszközzel telepíthetik ezeket a frissítéseket.

**Az Update Compatibility Evaluator (a frissítéskompatibilitás kiértékelője) és az Application Compatibility Toolkit (alkalmazáskompatibilitási eszközkészlet)**

Az alkalmazások működése érdekében a frissítések gyakran írnak ugyanazokba a fájlokba, illetve regisztrációs bejegyzésekbe. Ez inkompatibilitást okozhat, és növelheti a biztonsági frissítések központi telepítésére használt időt. A Windows frissítések és az alkalmazásoknak való megfelelőségének tesztelése és ellenőrzése egyszerűsíthető az [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) eszközeivel, ami része az [Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=hu) csomagnak.

Az Application Compatibility Toolkit (ACT) tartalmazza a Microsoft Windows Vista, a Windows Update, a Microsoft Security Update vagy a Windows Internet Explorer új verziójának központi telepítése előtt az alkalmazáskompatibilitási problémák kiértékeléséhez és enyhítéséhez szükséges eszközöket és dokumentációt.

### Egyéb információ

#### A Microsoft Windows rosszindulatú szoftvereket eltávolító eszköze

A Microsoft a Windows Update, Microsoft Update, Windows Server Update Services és Letöltőközpont szolgáltatásán keresztül elérhetővé tette a Microsoft Windows rosszindulatú szoftvereket eltávolító eszközének frissített változatát.

#### Nem biztonsági jellegű, kiemelt fontosságú frissítések a MU, WU és WSUS-szolgáltatásokban

A Windows Update és a Microsoft Update helyen elérhető, nem biztonsági jellegű frissítésekről tájékozódjon itt:

-   [Microsoft Tudásbázis 894199. cikke](http://support.microsoft.com/kb/894199): Tartalommódosítás a Software Update Services és Windows Server Update Services rendszerek leírásában. Az összes Windows-tartalmat érinti.
-   [Microsoft-termékek új, módosított és közreadott frissítései, a Microsoft Windows rendszert kivéve](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

#### Microsoft Active Protections Program (MAPP)

Az ügyfelek védelmének növelése érdekében a biztonsági szoftverekkel foglalkozó nagyobb gyártók a Microsoft a havi biztonsági közlemények megjelenése előtt ellátja biztonsági résekkel kapcsolatos információkkal. Így a biztonságiszoftver-gyártók a kapott biztonsági résekkel kapcsolatos információt felhasználhatják ügyfeleik hatásosabb védelmére az olyan biztonsági szoftverek vagy eszközök (például víruskeresők, hálózati behatolásérzékelő rendszerek vagy kiszolgálóalapú behatolásvédelmi rendszerek) frissítése által. A biztonságiszoftver-gyártók által kiadott aktív védelem elérhetőségéről a [Microsoft Active Protections Program (MAPP) Partners](http://www.microsoft.com/security/msrc/mapp/partners.mspx) webhelyén található listán szereplő és a programban részt vevő gyártók aktív védelmi webhelyein tájékozódhat.

#### Biztonsági stratégiák és közösségek

**Frissítésekkel kapcsolatos stratégiák**

[A frissítések kezelésére vonatkozó útmutatás](http://go.microsoft.com/fwlink/?linkid=21168) a Microsoft által a biztonsági frissítések telepítéséhez ajánlott legjobban bevált eljárást ismerteti.

**Egyéb biztonsági frissítések beszerzése**

Az alábbi helyekről más típusú biztonsági problémákhoz szerezhetők be frissítések.

-   A biztonsági frissítések a [Microsoft letöltőközpontban](http://go.microsoft.com/fwlink/?linkid=21129) érhetők el. Legegyszerűbben a „security update” kifejezésre irányuló kulcsszavas kereséssel találhatja meg ezeket.
-   Az ügyfélrendszerek frissítései a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) oldalról elérhetőek.
-   A Windows Update szolgáltatáson keresztül terjesztett havi aktuális biztonsági frissítések a letöltőközpontból a biztonsági és kritikus frissítéseket tartalmazó ISO CD-képfájlként is letölthetőek. További információt a [Microsoft Tudásbázis 913086](http://support.microsoft.com/kb/913086) számú cikkében talál.

**IT Pro Security közösség**

Az [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) közösségben hasznos információt találhat a biztonság javításáról és az informatikai infrastruktúrák optimalizálásáról, továbbá eszmecserét folytathat a biztonsági kérdésekről más informatikai szakemberekkel.

#### Köszönetnyilvánítás

A Microsoft [köszönetét](http://go.microsoft.com/fwlink/?linkid=21127) fejezi ki a vásárlók védelmének biztosításában nyújtott segítségért az alábbi szervezet(ek)nek és szakember(ek)nek:

-   [TippingPoint](http://www.tippingpoint.com/) és [Zero Day Initiative](http://www.zerodayinitiative.com/), az MS09-002 számú közleményben bemutatott probléma jelentéséért
-   Sam Thomas (<http://eshu.co.uk/>), a [TippingPoint](http://www.tippingpoint.com/) és a [Zero Day Initiative](http://www.zerodayinitiative.com/) munkatárs, az MS09-002 számú közleményben bemutatott probléma jelentéséért
-   Bogdan Materna, [VoIPshield Systems](http://www.voipshield.com), az MS09-003 számú közleményben bemutatott probléma jelentéséért
-   Bernhard Mueller, [SEC Consult Vulnerability Lab](http://www.sec-consult.com/), az MS09-004 közleményben bemutatott probléma jelentéséért
-   Bing Liu, a Fortinet [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) tagja, az MS09-005 számú közleményben bemutatott probléma jelentéséért

#### Terméktámogatás

-   Teszteléssel állapították meg a felsorolt szoftverek egyes verzióinak érintettségét. A többi verzió támogatási életciklusa végére ért. Az egyes szoftververziók támogatási életciklusáról a [Microsoft termékek terméktámogatási életciklusát ismertető webhelyen](http://go.microsoft.com/fwlink/?linkid=21742) talál felvilágosítást.
-   Az Amerikai Egyesült Államokban és Kanadában technikai segítség igényelhető a [Microsoft terméktámogatási szolgáltatásától](http://go.microsoft.com/fwlink/?linkid=21131), amelynek telefonszáma 1-866-PCSAFETY. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek.
-   Más országokban a helyi Microsoft-képviseletek nyújtanak támogatást. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. A [nemzetközi támogatási webhely](http://go.microsoft.com/fwlink/?linkid=21155) felvilágosítást nyújt arról, támogatási kérdéseivel hogyan fordulhat a Microsofthoz.

#### Felelősséget kizáró nyilatkozat

A Microsoft Tudásbázisban leírtak előzetes bejelentés nélkül változhatnak, és a cikkek tartalmáért a Microsoft nem vállal garanciát. A Microsoft egyben elhárít minden kifejezett és értelemszerű garanciát, beleértve az eladhatóságra és az adott célra való alkalmasságra vonatkozó garanciát is. A Microsoft Corporation vagy annak szállítói semmilyen körülmények között nem tehetők felelőssé közvetlen, közvetett, eseti, ok-okozati vagy különleges kárért (beleértve az elmaradt hasznot is), még akkor sem, ha a Microsoft Corporation vagy szállítói tudatában voltak a kár lehetséges voltának. Egyes államok törvényi szabályozása nem teszi lehetővé a véletlen vagy ok-okozati károkért vállalt felelősség korlátozását vagy kizárását, így ezekben az államokban az ez a felelősségkizárás nincs érvényben.

#### Verziók

-   1.0 verzió (2009. február 10.): Összefoglaló közlemény kiadva.
-   2.0 verzió (2009. február 16.): A frissítésben a Microsoft Exchange Server MAPI ügyfele már érintett szoftverként szerepel az MS09-003 vonatkozásában.
-   2.1 verzió (2009. február 25.): Az MS09-003 közlemény az Exchange Server 2003 rendszerhez tartozó Exchange rendszerkezelő eszközökkel kapcsolatos megjegyzéssel bővült.

*Built at 2014-04-18T01:50:00Z-07:00*
