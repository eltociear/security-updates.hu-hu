---
TOCTitle: 'MS09-DEC'
Title: 'Microsoft biztonsági közlemény - összefoglalás, december 2009'
ms:assetid: 'ms09-dec'
ms:contentKeyID: 61227728
ms:mtpsurl: 'https://technet.microsoft.com/hu-HU/library/ms09-dec(v=Security.10)'
author: SharonSears
ms.author: SharonSears
---

Security Bulletin Summary

Microsoft biztonsági közlemény - összefoglalás, december 2009
=============================================================

Közzétéve: 2009. december 8. | Frissítve: 2010. január 13.

**Verzió:** 2.0

Az összefoglaló a 2009 decemberében kiadott biztonsági közleményeket összegzi.

A 2009. decemberi közlemények kiadása folytán az összefoglaló a 2009. december 3-án kiadott előzetes értesítés helyébe lép. További információk a biztonsági közlemények kiadásáról szóló előzetes értesítés szolgáltatásról lásd: [Előzetes értesítés a Microsoft biztonsági közleményeinek kiadásáról](http://technet.microsoft.com/security/bulletin/advance).

Ha automatikus értesítést szeretne kapni a Microsoft biztonsági közleményeinek megjelenéséről, fizessen elő a [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) szolgáltatásra.

A közleményekkel kapcsolatos kérdések megválaszolására a Microsoft 2009. december 9-én, csendes-óceáni idő szerint 11 órakor webszemináriumot tart. [Jelentkezzen most a decemberi közleményeket bemutató webes szemináriumra](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032407802&culture=en-us). Ezt követően a webes szeminárium igény szerint kerül megrendezésre. További információkért látogasson el a [Microsoft biztonsági közleményeit és a webes szemináriumokat](http://technet.microsoft.com/security/bulletin/summary)bemutató oldalra.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=177727">MS09-071</a></td>
<td style="border:1px solid black;"><strong>Az internetes hitelesítési szolgáltatás biztonsági rései távoli kódfuttatást okozhatnak (974318)</strong><br />
<br />
Ez a biztonsági frissítés a Microsoft Windows két közvetlenül jelzett biztonsági rését szünteti meg. A súlyosabb biztonsági rés távoli kódfuttatást tehet lehetővé, ha az internetes hitelesítési szolgáltatás kiszolgálójától kapott üzenetek helytelenül lettek a memóriába másolva a PEAP hitelesítési próbálkozások kezelése közben. Windows Server 2008 rendszerben hálózati házirend-kiszolgáló (NPS) váltja fel az internetes hitelesítési szolgáltatást (IAS). A biztonsági rések valamelyikét kiaknázó támadó teljes mértékben átveheti az érintett rendszer vezérlését. Az internetes hitelesítési szolgáltatást illetve hálózati házirend-kiszolgálót alkalmazó kiszolgálók csak akkor érintettek, ha a PEAP és az MS-CHAP v2 hitelesítést együtt használják.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141642">MS09-074</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Office Project biztonsági rése távoli kódfuttatást tehet lehetővé (967183)</strong><br />
<br />
A biztonsági frissítés a Microsoft Office Project közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rés távoli kódvégrehajtást tehet lehetővé, ha a felhasználó megnyit egy speciálisan kialakított Project fájlt. Ha egy támadó kihasználja a biztonsági rést, teljes mértékben átveheti a rendszer irányítását. Ezt követően a támadó programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=169404">MS09-072</a></td>
<td style="border:1px solid black;"><strong>Összesítő biztonsági frissítés az Internet Explorer programhoz (976325)</strong><br />
<br />
A biztonsági frissítés négy közvetlenül és egy nyilvánosan jelentett biztonsági rést szüntet meg az Internet Explorer programban. A biztonsági rések mindegyike távoli kódvégrehajtást tehet lehetővé, amennyiben a felhasználó egy különlegesen kialakított weboldalt tekint meg az Internet Explorer alkalmazás segítségével. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén A Microsoft Active Template Library (ATL) alapon létrehozott ActiveX vezérlő fejlécei is távoli kódfuttatást okozhatnak: az ezzel kapcsolatos biztonsági rést a Microsoft 973882 sz. biztonsági tanácsadója és a MS09-035 Microsoft biztonsági közlemény ismerteti.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=177555">MS09-069</a></td>
<td style="border:1px solid black;"><strong>Az LSASS biztonsági rése szolgáltatásmegtagadást okozhat (974392)</strong><br />
<br />
A biztonsági frissítés a Microsoft Windows közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rés szolgáltatásmegtagadást tehet lehetővé, amennyiben a távoli, hitelesített támadó az IPsec funkción keresztül kommunikálva egy különlegesen kialakított ISAKMP üzenetet küld az LSASS-szolgáltatásnak.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Szolgáltatásmegtagadás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163844">MS09-070</a></td>
<td style="border:1px solid black;"><strong>Az Active Directory szövetségi szolgáltatások biztonsági rései távoli kódfuttatást okozhatnak (971726)</strong><br />
<br />
Ez a biztonsági frissítés a Microsoft Windows két közvetlenül jelzett biztonsági rését szünteti meg. E biztonsági rések súlyosabbjai távoli kódfuttatást tesznek lehetővé, ha a támadó speciálisan kialakított HTTP kérelmeket küld valamelyik ADFS-képes webkiszolgálóra. A biztonsági rések bármelyikének kihasználásához a támadónak hitelesített felhasználónak kell lenni.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163833">MS09-073</a></td>
<td style="border:1px solid black;"><strong>A WordPad és az Office szövegkonverterekben található biztonsági rés távolról történő kódfuttatást tesz lehetővé (975539)</strong><br />
<br />
A biztonsági frissítés a Microsoft Virtual WordPad és a Microsoft Office szövegkonverterek közvetlenül jelzett biztonsági rését szünteti meg. A biztonsági rés a WordPad és a Microsoft Office Word alkalmazásnál távoli kódfuttatást tehet lehetővé, amennyiben ezekben az alkalmazásokban a felhasználó különlegesen kialakított Word 97 fájlt nyit meg. A biztonsági rést kihasználó támadó a felhasználóéval azonos jogosultságokhoz juthat. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
</tr>
</tbody>
</table>
  
Kihasználhatósági információk  
-----------------------------
  
<span></span>
A következő táblázat az adott hónapban megoldott biztonsági rések kihasználhatósági jellemzőit ismerteti. A biztonsági rések a közlemény azonosítója és súlyossági besorolás azonosítója szerint vannak felsorolva.
  
**A táblázat használata**
  
A táblázat segítségével meghatározható annak valószínűsége, hogy a biztonsági közlemény kiadását követő 30 napon belül a telepíteni szükséges biztonsági frissítésekre működő rosszindulatú programkódot jelentetnek meg. A telepítés fontossági sorrendjének megállapításához az adott konfigurációnak megfelelően tekintse át az alábbi értékeléseket. A minősítések jelentéséről és meghatározásuk módjáról a [Microsoft biztonsági rések jegyzéke](http://technet.microsoft.com/en-us/security/cc998259.aspx) tartalmaz bővebb információt.
  
| Közlemény azonosítója                                     | A biztonsági rés címe                                                                    | CVE-azonosító                                                                    | Kihasználhatósági információk értékelése                                                                                 | Fontos megjegyzések                                                                                                                                                                                                                                                                                    |  
|-----------------------------------------------------------|------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-069](http://go.microsoft.com/fwlink/?linkid=177555) | A Local Security Authority Subsystem szolgáltatási erőforráshiányt okozó biztonsági rése | [CVE-2009-3675](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3675) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nem valószínű működő rosszindulatú programkód       | A biztonsági rés távoli kódfuttatást nem tesz lehetővé, a távoli, hitelesített támadó mindössze szolgáltatásmegtagadást okozhat.                                                                                                                                                                       |  
| [MS09-070](http://go.microsoft.com/fwlink/?linkid=163844) | Az ADFS egyszeri bejelentkezéssel tartalomhamisítást okozó biztonsági rése               | [CVE-2009-2508](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2508) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nem valószínű működő rosszindulatú programkód       | A biztonsági rés távoli kódfuttatást nem, csak tartalomhamisítást tesz lehetővé.                                                                                                                                                                                                                       |  
| [MS09-070](http://go.microsoft.com/fwlink/?linkid=163844) | Az ADFS távoli kódfuttatást okozó biztonsági rése                                        | [CVE-2009-2509](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2509) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | A biztonsági rést kizárólag hitelesített támadó használhatja ki.                                                                                                                                                                                                                                       |  
| [MS09-071](http://go.microsoft.com/fwlink/?linkid=177727) | Internetes hitelesítő szolgáltatás memóriameghibásodási biztonsági rése                  | [CVE-2009-2505](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2505) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | Távoli kódfuttatás korlátozott lehetősége. A legvalószínűbb tünet a szolgáltatásmegtagadás.                                                                                                                                                                                                            |  
| [MS09-071](http://go.microsoft.com/fwlink/?linkid=177727) | Az MS-CHAP hitelesítést megkerülő biztonsági rés                                         | [CVE-2009-3677](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3677) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nem valószínű működő rosszindulatú programkód       | A biztonsági rés távoli kódfuttatást nem tesz lehetővé, azonban a hálózati hitelesítés megkerülése miatt jogok kiterjesztését eredményezheti.                                                                                                                                                          |  
| [MS09-072](http://go.microsoft.com/fwlink/?linkid=169404) | ATL COM inicializálás biztonsági rése                                                    | [CVE-2009-2493](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | Nincsenek                                                                                                                | (Ezt a biztonsági rést a [júliusi közleményösszesítő](http://technet.microsoft.com/security/bulletin/ms09-jul) a kihasználhatóság szempontjából már besorolta. Ennek oka az, hogy a biztonsági rést első alkalommal az [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131) közlemény orvosolta.) |  
| [MS09-072](http://go.microsoft.com/fwlink/?linkid=169404) | Inicializálás hiánya miatti memóriameghibásodás okozta biztonsági rés                    | [CVE-2009-3671](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3671) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                                                                                                                                                                                                                |  
| [MS09-072](http://go.microsoft.com/fwlink/?linkid=169404) | HTML-objektumok okozta memóriameghibásodás biztonsági rése                               | [CVE-2009-3672](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3672) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                                                                                                                                                                                                                |  
| [MS09-072](http://go.microsoft.com/fwlink/?linkid=169404) | Inicializálás hiánya miatti memóriameghibásodás okozta biztonsági rés                    | [CVE-2009-3673](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3673) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                                                                                                                                                                                                                |  
| [MS09-072](http://go.microsoft.com/fwlink/?linkid=169404) | Inicializálás hiánya miatti memóriameghibásodás okozta biztonsági rés                    | [CVE-2009-3674](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3674) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                                                                                                                                                                                                                |  
| [MS09-073](http://go.microsoft.com/fwlink/?linkid=163833) | A WordPad és Office szövegkonverter memóriameghibásodási biztonsági rése                 | [CVE-2009-2506](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2506) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                                                                                                                                                                                                                                                                |  
| [MS09-074](http://go.microsoft.com/fwlink/?linkid=141642) | A Project alkalmazás memóriakezelés biztonsági rése                                      | [CVE-2009-0102](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0102) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                                                                                                                                                                                                                                                                |
  
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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="6">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://go.microsoft.com/fwlink/?linkid=177727)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://go.microsoft.com/fwlink/?linkid=169404)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://go.microsoft.com/fwlink/?linkid=177555)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://go.microsoft.com/fwlink/?linkid=163844)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=5b02d10d-1abd-4d68-826b-71dad543657a)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=0cf37247-505a-4dc2-aad7-c8cb1a63b57a)  
(Kritikus)  
[Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7fb6261c-6895-4f79-be2c-bb110874a19c)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=560e01db-5f59-4ef1-9406-f5d7e0fd4128)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=50936f51-b0a9-4e94-85bf-93f9ad74fdd1)  
(KB973904)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="6">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://go.microsoft.com/fwlink/?linkid=177727)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://go.microsoft.com/fwlink/?linkid=169404)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://go.microsoft.com/fwlink/?linkid=177555)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://go.microsoft.com/fwlink/?linkid=163844)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
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
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 és Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 és Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=4d294be6-19d1-43b5-9c75-f9d30699a2e7)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=facab13f-ea31-4c71-be4c-24e44ded174f)  
(Kritikus)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=def2c038-3b03-4162-a563-a6ebec756f37)  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=6c003629-77bf-4735-bd4a-c37c4386f869)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 és Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=5448b168-6bf7-4bae-9627-b88d76c4d5c5)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 és Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c090c4c2-c277-4d8c-91e1-28286bc5443e)  
(KB973904)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=17b5206d-61e9-4663-afc7-80e98bf4d618)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=a253c19a-c808-4115-8bd0-cf312d396abd)  
(Kritikus)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=98a56425-4f88-4f0f-963b-dada8dc0d8f8)  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0c9af3b5-d015-4025-bbb4-1a5113e9113f)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c2bbf515-f81a-436b-947b-cbf2db85fdd9)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4b9bf156-cd34-460f-b4ad-571e37f54659)  
(KB973904)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://go.microsoft.com/fwlink/?linkid=177727)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://go.microsoft.com/fwlink/?linkid=169404)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://go.microsoft.com/fwlink/?linkid=177555)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://go.microsoft.com/fwlink/?linkid=163844)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3d49b386-133a-4d51-b6f0-cec0c70ef93e)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=6659fc40-71ee-44a9-9656-8d3ee02b5bc0)  
(Kritikus)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7bdba030-e2c6-44ac-bb5f-24ae8ec372a2)  
(Mérsékelt)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0dd50357-64f2-4286-86ba-c512e65eed2a)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a779aae1-7724-4458-94fb-a2343356ecae)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=31351b9e-b5bb-4618-990b-1089ea5a3bc2)<sup>[1]</sup>
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b9678229-2473-4aae-a814-eca9ea556d17)  
(KB973904)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5a273b47-8a18-4778-9b60-8b560a1ce089)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=287e7921-8aab-42a6-b647-551d0a9adc15)  
(Kritikus)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4de4bbcd-b1b8-4482-8ef7-0d9b4a730e0c)  
(Mérsékelt)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=e62aba15-5eeb-46a2-a142-bfca94016c55)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a8a9bf12-4ad6-49fd-b2b7-f379dc3309d2)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b6eb9d9b-1a43-4b30-a033-19a1db786244)<sup>[2]</sup>
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=257facf3-20a1-49e2-ab4c-c1ae67fe05a0)  
(KB973904)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 javítócsomaggal Itanium alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=498f5eeb-d03e-42ee-ad6a-9d6f98c66acb)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=9ce1a721-0c6a-4775-9407-9633d817d716)  
(Kritikus)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=72d44de7-dfc5-4667-a59f-2ee73d0e3708)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 javítócsomaggal Itanium alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=f5b003ad-af25-488a-91fb-98835a0bfeac)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 javítócsomaggal Itanium alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=1a7784ef-5d25-4de1-a293-f742b5a3473d)  
(KB973904)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://go.microsoft.com/fwlink/?linkid=177727)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://go.microsoft.com/fwlink/?linkid=169404)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://go.microsoft.com/fwlink/?linkid=177555)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://go.microsoft.com/fwlink/?linkid=163844)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista Service Pack 1 és Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista és Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3e4ae4d0-1060-4867-82c5-7e20ea93c2c6)  
(Mérsékelt)  
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3e4ae4d0-1060-4867-82c5-7e20ea93c2c6)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=40d26d40-4203-4013-b3f9-912a5b209fbd)  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=47d5ada1-1d60-4233-bdd3-64918b5e1245)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 és Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition és Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2ca62ea8-67cb-40da-8a65-db6f3607bbab)  
(Mérsékelt)  
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2ca62ea8-67cb-40da-8a65-db6f3607bbab)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3140527a-aa33-462b-b3a6-bfcd78b5aa0c)  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=1e466b48-422f-4c80-8fdf-ba61111942b1)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://go.microsoft.com/fwlink/?linkid=177727)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://go.microsoft.com/fwlink/?linkid=169404)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://go.microsoft.com/fwlink/?linkid=177555)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://go.microsoft.com/fwlink/?linkid=163844)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
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
[**Mérsékelt**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 32 bites rendszerekhez és Windows Server 2008 32 bites rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=582a1b15-214e-4f5e-bb5b-95677f4d5968)\*  
(Fontos)  
[Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=582a1b15-214e-4f5e-bb5b-95677f4d5968)\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d0570536-756e-4fda-883d-f2a3c4ac5bbd)\*  
(Mérsékelt)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=43660133-43e1-41f3-8a82-98c4a739914f)\*  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez és Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f6715abb-fd93-44ba-9854-2ecc672622da)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 x64 alapú rendszerekhez és Windows Server 2008 x64 alapú rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=77e774b4-ec0c-481c-9e93-eee9f44ec71b)\*  
(Fontos)  
[Windows Server 2008 x64 alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=77e774b4-ec0c-481c-9e93-eee9f44ec71b)\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0e72d0f1-2ce7-4650-b72c-bb303351aafc)\*  
(Mérsékelt)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=22972970-740f-4c50-93ec-f6d49dd1b360)\*  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64 alapú rendszerekhez és Windows Server 2008 x64 alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7d1f5e9e-a7de-4f96-89c8-510fd51f16e7)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Itanium alapú rendszerekhez és Windows Server 2008 Itanium alapú rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 Itanium alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=89defe77-7e82-4bfa-9693-66c93b930da1)  
(Mérsékelt)  
[Windows Server 2008 Itanium alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=89defe77-7e82-4bfa-9693-66c93b930da1)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2c7765a2-3117-4dd8-94b4-0060ca16871b)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="6">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://go.microsoft.com/fwlink/?linkid=177727)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://go.microsoft.com/fwlink/?linkid=169404)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://go.microsoft.com/fwlink/?linkid=177555)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://go.microsoft.com/fwlink/?linkid=163844)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
<td style="border:1px solid black;">
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 32 bites rendszerekhez
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5af3be0b-2dd2-4039-90e1-2278e9c5aee5)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 alapú rendszerekhez
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9d9a04c8-a019-4943-8e93-c6bfd77c8960)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://go.microsoft.com/fwlink/?linkid=177727)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://go.microsoft.com/fwlink/?linkid=169404)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://go.microsoft.com/fwlink/?linkid=177555)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://go.microsoft.com/fwlink/?linkid=163844)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
<td style="border:1px solid black;">
[**Mérsékelt**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 alapú rendszerekhez
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=bcb38127-787f-49b0-b3fb-62f6a8628d89)\*  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium alapú rendszerekhez
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2c1b96f2-b3c3-4711-a9ad-b2133ea7bf81)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
</table>
 
**Megjegyzések a Windows Server 2008 és Windows Server 2008 R2 rendszerhez**

**\*A kiszolgálómag-telepítés nem érintett.** A frissítésben tárgyalt biztonsági rések nem érintik a jelzett módon a Windows Server 2008 és a Windows Server 2008 R2 támogatott kiadásait, amennyiben a telepítés a kiszolgálómag-telepítési opció használatával történt. Erről a telepítési opcióról bővebben a [Kiszolgálómag](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) és a [Kiszolgálómag a Windows Server 2008 R2 rendszerhez](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) MSDN-cikkekben olvashat. A kiszolgálómag-telepítési opció nem vonatkozik a Windows Server 2008 és a Windows Server 2008 R2 bizonyos kiadásaira; lásd: [A kiszolgálómag-telepítési opciók összehasonlítása](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Megjegyzések az MS09-070 közleménnyel kapcsolatban**

<sup>[1]</sup>A rendszer csak akkor érintett, ha Windows Server 2003 R2 verzióra frissíti Active Directory szövetségi szolgáltatások használatával.

<sup>[2]</sup>A rendszer csak akkor érintett, ha Windows Server 2003 R2 x64 Edition verzióra frissíti Active Directory szövetségi szolgáltatások használatával.

**Megjegyzés az MS09-073 közleménnyel kapcsolatban**

Az ugyanezen a közlemény azonosító alatt található, további frissített fájlokat illetően lásd még az egyéb szoftverkategóriák részt ebben a fejezetben, **Érintett szoftverek és letöltési helyek**. Ez a közlemény több szoftverkategóriát ölel fel.

#### Microsoft Office programcsomagok és szoftverek

 
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
Microsoft Office programcsomagok, rendszerek és összetevők
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-074**](http://go.microsoft.com/fwlink/?linkid=141642)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=bc3ec3ba-2cec-43ab-b184-c222794231f2)  
(KB975008)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b4a4126c-b0b3-4db2-b6f5-0e67519c2a5f)  
(KB975051)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="3">
Egyéb Microsoft Office szoftver
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-074**](http://go.microsoft.com/fwlink/?linkid=141642)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
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
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Project 2000
</td>
<td style="border:1px solid black;">
[Microsoft Project 2000 Service Release 1](http://www.microsoft.com/downloads/details.aspx?familyid=135c010a-55f4-4385-b67d-96ea06ef881a)  
(KB961083)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Project 2002
</td>
<td style="border:1px solid black;">
[Microsoft Project 2002 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c55ef8fe-8f66-42fc-a298-de6f8886b3e4)  
(KB961079)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Project 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2ea8ca39-f130-439a-92d5-77e9ef050105)  
(KB961082)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works 8.5
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Works 8.5](http://www.microsoft.com/downloads/details.aspx?familyid=807426a1-8b78-4681-a606-dc39f4d7b64a)  
(KB977304)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Converter Pack
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Converter Pack](http://www.microsoft.com/downloads/details.aspx?familyid=f3ff8bb6-d047-42f1-9331-b6df85fff9fd)  
(KB974882)  
(Fontos)
</td>
</tr>
</table>
 
**Megjegyzés az MS09-073 közleménnyel kapcsolatban**

Az ugyanezen a közlemény azonosító alatt található, további frissített fájlokat illetően lásd még az egyéb szoftverkategóriák részt ebben a fejezetben, **Érintett szoftverek és letöltési helyek**. Ez a közlemény több szoftverkategóriát ölel fel.

Észlelési és telepítési eszközök, útmutatás
-------------------------------------------

<span></span>
**Biztonsági központ**

A szoftveres és biztonsági frissítések kezeléséhez azokat a szervezet asztali és hordozható számítógépeire, valamint kiszolgálóira is telepíteni kell. További tájékoztatásért látogasson el a [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) weboldalára. A [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) bővebb tájékoztatással szolgál a Microsoft-termékek biztonsági funkcióival kapcsolatban. A [Biztonság otthon](http://go.microsoft.com/fwlink/?linkid=85102) weboldalon a megfelelő hivatkozásra kattintva elérhetőek a legújabb biztonsági frissítések.

A biztonsági frissítések a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) és a [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) weboldalról tölthetők le. A biztonsági frissítések a [Microsoft letöltőközpontjában](http://go.microsoft.com/fwlink/?linkid=21129) is elérhetőek. Legegyszerűbben a „security update” kifejezésre irányuló kulcsszavas kereséssel találhatja meg ezeket.

A biztonsági frissítések a [Microsoft Update katalógusából](http://go.microsoft.com/fwlink/?linkid=96155) is letölthetőek. A Microsoft Update katalógus a Windows Update és Microsoft Update szolgáltatáson keresztül elérhető tartalom kereshető adatbázisa; ide tartoznak a biztonsági frissítések, illesztőprogramok és szervizcsomagok. A biztonsági közlemény azonosítójára (pl. „MS07-036”) történő kereséssel hozzáadhatja az összes vonatkozó frissítést a kosárhoz (beleértve a frissítés különböző nyelvi változatait), és letöltheti azokat a megadott mappába. A Microsoft Update katalógus részletes leírását lásd a vonatkozó [GYIK](http://go.microsoft.com/fwlink/?linkid=97900)részben.

**Megjegyzés** 2009. augusztus 1-től a Microsoft megszünteti az Office Update és az Office Update Inventory Tool támogatását. A Microsoft Office termékeihez készült legújabb frissítéseket a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) segítségével érheti el. A további tudnivalókat lásd [Az Office Update bemutatása: Gyakran ismételt kérdések című témakört.](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx)

**Útmutató az észleléshez és a telepítéshez**

A biztonsági frissítésekkel kapcsolatban a Microsoft észlelési és telepítési segítséget nyújt. Ez az útmutató olyan javaslatokat és tudnivalókat tartalmaz, amelyeket segítséget nyújthatnak az informatikusoknak a biztonsági frissítések észlelési és telepítési eszközeinek használatához. További tudnivalókat a [Microsoft Tudásbázis 961747. számú cikkében](http://support.microsoft.com/kb/961747) talál.

**Microsoft Baseline Security Analyzer**

A Microsoft Baseline Security Analyzer (MBSA) segítségével a rendszergazda mind a helyi, mind a távoli számítógépeken ellenőrizheti, hogy mely biztonsági frissítések hiányoznak, illetve hogy mely biztonsági beállítások vannak helytelenül megadva. Ha többet szeretne tudni az MBSA -eszközről, látogasson el a [Microsoft Baseline Security Analyzer webhelyre](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

A Microsoft Software Update Services (WSUS) szolgáltatással a rendszergazdák gyorsan és megbízható módon telepíthetik központilag a legújabb fontos és biztonsági frissítéseket Windows 2000 és újabb operációs rendszerekhez, Office XP és újabb operációs rendszerekhez, Exchange Server 2003 és SQL Server 2000 Windows 2000 és újabb operációs rendszerekre.

A biztonsági frissítésnek Windows Server Update Services szolgáltatással történő központi telepítéséről a [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) webhelyen tudhat meg többet.

**Systems Management Server**

A Microsoft Systems Management Server (SMS) rendszer egy sokoldalúan beállítható vállalati megoldás, amely a frissítések kezelésére szolgál. Az SMS segítségével a rendszergazda megállapíthatja, hogy melyik Windows alapú számítógép szorul biztonsági frissítésre, és ezeket a frissítéseket szabályozott módon, a felhasználók minimális zavarásával központilag telepítheti a vállalat teljes informatikai környezetében. Az SMS, vagyis a System Center Configuration Manager 2007 újabb kiadása immáron elérhető, lásd még: [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Arról, hogy a rendszergazdák hogyan használhatják a biztonsági frissítések telepítéséhez az SMS 2003 alkalmazást, az [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939) részben olvashat. A biztonsági frissítések felderítéséhez az SMS 2.0 felhasználók a Security Update Inventory Tool (SUIT) eszközt is használhatják. Az SMS-szolgáltatásról bővebben a [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) oldalán olvashat.

**Megjegyzés** Az SMS a Microsoft Baseline Security Analyzer eszközön keresztül széles körű támogatást nyújt a biztonsági közlemények frissítéseinek észleléséhez, valamint a frissítések telepítéséhez. Előfordulhat, hogy egyes szoftverfrissítéseket ezek az eszközök nem észlelnek. Az SMS-alkalmazás leltározási szolgáltatásai segítségével a rendszergazdák adott rendszereken hajthatják végre a frissítést. Az eljárással kapcsolatban olvassa el a [szoftverfrissítések telepítése az SMS szoftverelosztó ügynök segítségével](http://go.microsoft.com/fwlink/?linkid=33341) című tájékoztatót. Egyes biztonsági frissítésekhez rendszergazdai jogosultságokra van szükség a számítógép újraindítása után. A rendszergazdák az [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) és az [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) csomag részét képező Elevated Rights Deployment Tool nevű eszközzel telepíthetik ezeket a frissítéseket.

**Az Update Compatibility Evaluator (a frissítéskompatibilitás kiértékelője) és az Application Compatibility Toolkit (alkalmazáskompatibilitási eszközkészlet)**

Az alkalmazások működése érdekében a frissítések gyakran írnak ugyanazokba a fájlokba, illetve regisztrációs bejegyzésekbe. Ez inkompatibilitást okozhat, és növelheti a biztonsági frissítések központi telepítésére használt időt. A Windows frissítések és az alkalmazásoknak való megfelelőség tesztelése és ellenőrzése egyszerűsíthető az [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) eszközeivel, ami része az [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=hu) alkalmazáskompatibilitási eszközkészletnek.

Az Application Compatibility Toolkit (ACT) tartalmazza a Microsoft Windows Vista, a Windows Update, a Microsoft Security Update vagy a Windows Internet Explorer új verziójának központi telepítése előtt az alkalmazáskompatibilitási problémák kiértékeléséhez és enyhítéséhez szükséges eszközöket és dokumentációt.

### Egyéb információ

#### A Microsoft Windows rosszindulatú szoftvereket eltávolító eszköze

A Microsoft a Windows Update, Microsoft Update, Windows Server Update Services és Letöltőközpont szolgáltatásán keresztül elérhetővé tette a Microsoft Windows rosszindulatú szoftvereket eltávolító eszközének frissített változatát.

#### Nem biztonsági jellegű, kiemelt fontosságú frissítések a MU, WU és WSUS-szolgáltatásokban

A Windows Update és a Microsoft Update helyen elérhető, nem biztonsági jellegű frissítésekről tájékozódjon itt:

-   [Microsoft Tudásbázis 894199. cikke](http://support.microsoft.com/kb/894199): Tartalommódosítás a Software Update Services és Windows Server Update Services rendszerek leírásában. Az összes Windows-tartalmat érinti.
-   [Az elmúlt hónapok frissítései Windows Server Frissítési szolgáltatások esetén](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Microsoft termékek új, módosított és újra kiadott frissítései, a Microsoft Windows rendszert kivéve.

#### Microsoft Active Protections Program (MAPP)

Az ügyfelek védelmének növelése érdekében a biztonsági szoftverekkel foglalkozó nagyobb gyártók a Microsoft a havi biztonsági közlemények megjelenése előtt ellátja biztonsági résekkel kapcsolatos információkkal. Így a biztonságiszoftver-gyártók a kapott biztonsági résekkel kapcsolatos információt felhasználhatják ügyfeleik hatásosabb védelmére az olyan biztonsági szoftverek vagy eszközök (például víruskeresők, hálózati behatolásérzékelő rendszerek vagy kiszolgálóalapú behatolásvédelmi rendszerek) frissítése által. A biztonságiszoftver-gyártók által kiadott aktív védelem elérhetőségéről a [Microsoft Active Protections Program (MAPP) Partners](http://www.microsoft.com/security/msrc/mapp/partners.mspx) webhelyén található listán szereplő és a programban részt vevő gyártók aktív védelmi webhelyein tájékozódhat.

#### Biztonsági stratégiák és közösségek

**Frissítésekkel kapcsolatos stratégiák**

[A frissítések kezelésére vonatkozó útmutatás](http://go.microsoft.com/fwlink/?linkid=21168) a Microsoft által a biztonsági frissítések telepítéséhez ajánlott legjobban bevált eljárást ismerteti.

**Egyéb biztonsági frissítések beszerzése**

Az alábbi helyekről más típusú biztonsági problémákhoz szerezhetők be frissítések:

-   A biztonsági frissítések a [Microsoft letöltőközpontban](http://go.microsoft.com/fwlink/?linkid=21129) érhetők el. Legegyszerűbben a „security update” kifejezésre irányuló kulcsszavas kereséssel találhatja meg ezeket.
-   Az ügyfélrendszerek frissítései a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) oldalról elérhetőek.
-   A Windows Update szolgáltatáson keresztül terjesztett havi aktuális biztonsági frissítések a letöltőközpontból a biztonsági és kritikus frissítéseket tartalmazó ISO CD-képfájlként is letölthetőek. További információt a [Microsoft Tudásbázis 913086](http://support.microsoft.com/kb/913086) számú cikkében talál.

**IT Pro Security közösség**

Az [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) közösségben hasznos információt találhat a biztonság javításáról és az informatikai infrastruktúrák optimalizálásáról, továbbá eszmecserét folytathat a biztonsági kérdésekről más informatikai szakemberekkel.

#### Köszönetnyilvánítás

A Microsoft [köszönetét](http://go.microsoft.com/fwlink/?linkid=21127) fejezi ki a vásárlók védelmének biztosításában nyújtott segítségért az alábbi szervezet(ek)nek és szakember(ek)nek:

-   Ryan Smith, [VeriSign iDefense Labs](http://labs.idefense.com/), az MS09-072 közleményben bemutatott egyik probléma jelentéséért
-   Sam Thomas, eshu.co.uk, a [TippingPoint](http://www.tippingpoint.com/) és a [Zero Day Initiative](http://www.zerodayinitiative.com/) munkatársa, az MS09-072 számú közleményben bemutatott egyik probléma jelentéséért
-   [team509](http://www.team509.com/), a [VeriSign iDefense Labs](http://labs.idefense.com/) munkatársa, az MS09-072 közleményben bemutatott egyik probléma jelentéséért
-   A [Tipping Point](http://www.tippingpoint.com/) és [Zero Day Initiative](http://www.zerodayinitiative.com/) cégekkel együttműködő anonim kutató, az MS09-072 közleményben leírt egyik probléma jelentéséért
-   A [Tipping Point](http://www.tippingpoint.com/) és [Zero Day Initiative](http://www.zerodayinitiative.com/) cégekkel együttműködő anonim kutató, az MS09-072 közleményben leírt egyik probléma jelentéséért
-   Sean Larsson és Jun Mao, [VeriSign iDefense Labs](http://labs.idefense.com/), az MS09-073 közleményben bemutatott egyik probléma jelentéséért
-   Bing Liu, [Fortinet FortiGuard Labs](http://www.fortiguard.com/), az MS09-074 számú közleményben ismertetett egyik probléma jelentéséért

#### Terméktámogatás

-   Teszteléssel állapították meg a felsorolt szoftverek egyes verzióinak érintettségét. A többi verzió támogatási életciklusa végére ért. Az egyes szoftververziók támogatási életciklusáról a [Microsoft termékek terméktámogatási életciklusát ismertető webhelyen](http://go.microsoft.com/fwlink/?linkid=21742) talál felvilágosítást.
-   Az Amerikai Egyesült Államokban és Kanada területén élő ügyfelek technikai támogatást kérhetnek a [biztonsági támogatás szolgáltatójától](http://go.microsoft.com/fwlink/?linkid=21131) vagy az 1-866-PCSAFETY telefonszámon. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. Az elérhető támogatási lehetőségekről további információt talál a [Microsoft segítségnyújtással és támogatással foglalkozó webhelyén](http://support.microsoft.com/).
-   Más országokban a helyi Microsoft-képviseletek nyújtanak támogatást. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. A [nemzetközi támogatási webhely](http://go.microsoft.com/fwlink/?linkid=21155) felvilágosítást nyújt arról, támogatási kérdéseivel hogyan fordulhat a Microsofthoz.

#### Felelősséget kizáró nyilatkozat

A Microsoft Tudásbázisban leírtak előzetes bejelentés nélkül változhatnak, és a cikkek tartalmáért a Microsoft nem vállal garanciát. A Microsoft egyben elhárít minden kifejezett és értelemszerű garanciát, beleértve az eladhatóságra és az adott célra való alkalmasságra vonatkozó garanciát is. A Microsoft Corporation vagy annak szállítói semmilyen körülmények között nem tehetők felelőssé közvetlen, közvetett, eseti, ok-okozati vagy különleges kárért (beleértve az elmaradt hasznot is), még akkor sem, ha a Microsoft Corporation vagy szállítói tudatában voltak a kár lehetséges voltának. Egyes államok törvényi szabályozása nem teszi lehetővé a véletlen vagy ok-okozati károkért vállalt felelősség korlátozását vagy kizárását, így ezekben az államokban az ez a felelősségkizárás nincs érvényben.

#### Verziók

-   1.0 verzió (2009. december 8.): Összefoglaló közlemény közzététele.
-   1.1 verzió (2009. december 9.): Javítottuk az MS09-071 közlemény leírását az Összefoglalások táblázatban. Javítottuk az MS09-073 közlemény által kiváltott újraindításra vonatkozó információt.
-   2.0 verzió (2010. január 13.): Az MS09-073 közlemény vonatkozásában átnevezésre kerültek a korábban **Microsoft Office Word 2002 Service Pack 3 (KB975008)** és **Microsoft Office Word 2003 Service Pack 3 (KB975051)** névvel illetett frissítőcsomagok **Microsoft Office XP Service Pack 3 (KB975008)** és **Microsoft Office 2003 Service Pack 3 (KB975051)** névre.

*Built at 2014-04-18T01:50:00Z-07:00*
