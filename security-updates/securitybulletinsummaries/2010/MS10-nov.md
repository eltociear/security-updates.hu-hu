---
TOCTitle: 'MS10-NOV'
Title: Microsoft Security Bulletin Summary for november 2010
ms:assetid: 'ms10-nov'
ms:contentKeyID: 61227747
ms:mtpsurl: 'https://technet.microsoft.com/hu-HU/library/ms10-nov(v=Security.10)'
author: SharonSears
ms.author: SharonSears
---

Security Bulletin Summary

Microsoft Security Bulletin Summary for november 2010
=====================================================

Közzétéve: 2010. november 9. | Frissítve: 2010. december 15.

**Verzió:** 2.0

Az összefoglaló a 2010 novemberében kiadott biztonsági közleményeket összegzi.

A 2010. novemberi közlemények kiadása folytán az összefoglaló a 2010. november 4-én kiadott előzetes értesítés helyébe lép. A biztonsági közlemények kiadásáról szóló előzetes értesítés szolgáltatásról itt olvashat bővebben: [Előzetes értesítés a Microsoft biztonsági közleményeinek kiadásáról](http://technet.microsoft.com/security/bulletin/advance).

Ha automatikus értesítést szeretne kapni a Microsoft biztonsági közleményeinek megjelenéséről, fizessen elő a [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) szolgáltatásra.

A közleményekkel kapcsolatos kérdések megválaszolására a Microsoft 2010. november 10-én, csendes-óceáni idő szerint 11 órakor webes szemináriumot tart. [Jelentkezzen most a novemberi közleményeket bemutató webes szemináriumra](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032454441). Ezt követően a webes szeminárium igény szerint kerül megrendezésre. További információkért látogasson el a [Microsoft biztonsági közleményeit és a webes szemináriumokat](http://technet.microsoft.com/security/bulletin/summary)bemutató oldalra.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=203241">MS10-087</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Office biztonsági rései távolról történő programkódfuttatást tehetnek lehetővé (2423930)</strong><br />
<br />
Ez a biztonsági frissítés egy nyilvánosságra került és öt közvetlenül jelentett biztonsági rést szüntet meg a Microsoft Office alkalmazásban. A legsúlyosabb biztonsági rés távolról történő kódfuttatást tesz lehetővé, ha a felhasználó megnyit vagy előnézetben megnéz egy speciálisan kialakított RTF e-mail üzenetet. A biztonsági rések valamelyikét sikeresen kihasználó támadó a helyi felhasználóval egyező hozzáférést nyer a rendszerhez. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=198186">MS10-088</a></td>
<td style="border:1px solid black;"><strong>A Microsoft PowerPoint biztonsági rései távoli kódfuttatást tehetnek lehetővé (2293386)</strong><br />
<br />
A biztonsági frissítés a Microsoft Office két, közvetlenül a Microsoftnak jelzett biztonsági rését szünteti meg, amely távoli kódfuttatást tesz lehetővé, amennyiben a felhasználó megnyit egy speciálisan kialakított PowerPoint fájlt. A biztonsági rések bármelyikét kiaknázó támadó teljes mértékben átveheti az érintett rendszer vezérlését. Ezt követően a támadó programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=199536">MS10-089</a></td>
<td style="border:1px solid black;"><strong>A Forefront Unified Access Gateway (UAG) jogok kiterjesztését lehetővé tévő biztonsági rései (2316074)</strong><br />
<br />
Ez a biztonsági frissítés a Forefront Unified Access Gateway (UAG) négy, közvetlenül jelzett biztonsági rését szünteti meg. A legsúlyosabb besorolású biztonsági rések jogok kiterjesztését tehetik lehetővé, ha a felhasználó egy speciálisan kialakított URL-címen látogat el az érintett webhelyek egyikére. A támadónak ugyanakkor nincs semmilyen lehetősége arra, hogy a felhasználót egy ilyen webhely megnyitására kényszerítse. Ehelyett a támadóknak az adott webhelyre kell csábítaniuk a felhasználókat. Ezt rendszerint úgy érik el, hogy ráveszik őket arra, hogy kattintsanak rá egy e-mailben lévő hivatkozásra vagy azonnali üzenetkezelőben megjelenő kérésre.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Jogok kiterjesztése</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Forefront United Access Gateway</td>
</tr>
</tbody>
</table>
  
Kihasználhatósági információk  
-----------------------------
  
<span></span>
A következő táblázat az adott hónapban megoldott biztonsági rések kihasználhatósági jellemzőit ismerteti. A biztonsági rések a kihasználhatósági kockázat, majd a CVE azonosító szerint vannak felsorolva. Csak a kritikus és fontos besorolású biztonsági rések szerepelnek.
  
**A táblázat használata**
  
A táblázat segítségével meghatározható annak valószínűsége, hogy a biztonsági közlemény kiadását követő 30 napon belül a telepíteni szükséges biztonsági frissítésekre működő rosszindulatú programkódot jelentetnek meg. A telepítés fontossági sorrendjének megállapításához az adott konfigurációnak megfelelően tekintse át az alábbi értékeléseket. A minősítések jelentéséről és meghatározásuk módjáról a [Microsoft biztonsági rések jegyzéke](http://technet.microsoft.com/en-us/security/cc998259.aspx) tartalmaz bővebb információt.
  
| Közlemény azonosítója                                     | A biztonsági rés címe                                                                                                | CVE-azonosító                                                                    | Kihasználhatósági információk értékelése                                                                                 | Fontos megjegyzések                                                                                             |  
|-----------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|  
| [MS10-088](http://go.microsoft.com/fwlink/?linkid=198186) | PowerPoint elemzési puffertúlcsordulás okozta biztonsági rés                                                         | [CVE-2010-2572](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2572) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                         |  
| [MS10-089](http://go.microsoft.com/fwlink/?linkid=199536) | Az UAG XSS-t és jogok kiterjesztését lehetővé tévő biztonsági rése                                                   | [CVE-2010-2733](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2733) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                         |  
| [MS10-089](http://go.microsoft.com/fwlink/?linkid=199536) | A Forefront Unified Access Gateway rendszert az UAG Mobile Portal webhely XSS-problémája miatt érintő biztonsági rés | [CVE-2010-2734](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2734) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                         |  
| [MS10-087](http://go.microsoft.com/fwlink/?linkid=203241) | Az RTF-formátum kötegpuffer-túlcsordulás okozta biztonsági rése                                                      | [CVE-2010-3333](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3333) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                         |  
| [MS10-087](http://go.microsoft.com/fwlink/?linkid=203241) | Az Office Art rajzolási bejegyzései okozta biztonsági rés                                                            | [CVE-2010-3334](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3334) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                         |  
| [MS10-087](http://go.microsoft.com/fwlink/?linkid=203241) | A rajzok kivételkezelése okozta biztonsági rés                                                                       | [CVE-2010-3335](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3335) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                         |  
| [MS10-087](http://go.microsoft.com/fwlink/?linkid=203241) | A függvénytárak nem biztonságos betöltése miatti biztonsági rés                                                      | [CVE-2010-3337](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3337) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | **A biztonsági rés nyilvánosságra került**                                                                      |  
| [MS10-089](http://go.microsoft.com/fwlink/?linkid=199536) | XSS a Signurl.asp fájlban biztonsági rés                                                                             | [CVE-2010-3936](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3936) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                         |  
| [MS10-087](http://go.microsoft.com/fwlink/?linkid=203241) | A PowerPoint egészszám-alulcsordulása által okozott halommemória-sérülési biztonsági rés                             | [CVE-2010-2573](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2573) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | Az [MS10-088](http://go.microsoft.com/fwlink/?linkid=198186) közlemény szintén foglalkozik a biztonsági réssel. |  
| [MS10-088](http://go.microsoft.com/fwlink/?linkid=198186) | A PowerPoint egészszám-alulcsordulása által okozott halommemória-sérülési biztonsági rés                             | [CVE-2010-2573](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2573) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | Az [MS10-087](http://go.microsoft.com/fwlink/?linkid=203241) közlemény szintén foglalkozik a biztonsági réssel. |  
| [MS10-087](http://go.microsoft.com/fwlink/?linkid=203241) | Az MSO nagyméretű szolgáltatásiprofil-azonosítók olvasását érintő biztonsági rése                                    | [CVE-2010-3336](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3336) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                                                                         |  
| [MS10-089](http://go.microsoft.com/fwlink/?linkid=199536) | Az UAG átirányítást és tartalomhamisítást lehetővé tévő biztonsági rése                                              | [CVE-2010-2732](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2732) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nem valószínű működő rosszindulatú programkód       | Ez a biztonsági rés tartalomhamisításra ad lehetőséget.                                                         |
  
Érintett szoftverek és letöltési helyek  
---------------------------------------
  
<span></span>
A következő táblázatok a közleményeket a főbb szoftverkategóriák és súlyosság szerint sorolják fel.
  
**A táblázatok használata**
  
A táblázatok segítségével megtudhatja a szükséges információt a telepítendő biztonsági frissítésekről. Nézzen meg minden felsorolt szoftvert vagy összetevőt annak megállapításához, hogy elérhető-e a rendszerhez való frissítés. Ha a szoftver vagy összetevő szerepel a listán, hiperhivatkozással kapcsolódik hozzá az elérhető szoftverfrissítés, és a frissítés besorolása is fel van tüntetve.
  
**Megjegyzés:** Előfordulhat, hogy egy biztonsági rés megszüntetéséhez több biztonsági frissítést kell telepíteni. Nézze át az egyes közleményazonosítókhoz tartozó teljes oszlopot, és ellenőrizze a telepítendő frissítéseket a rendszerre telepített programok vagy összetevők alapján.
  
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
Microsoft Office programcsomagok és összetevők  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS10-087**](http://go.microsoft.com/fwlink/?linkid=203241)
</td>
<td style="border:1px solid black;">
[**MS10-088**](http://go.microsoft.com/fwlink/?linkid=198186)
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
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f32648e3-2fb5-472c-932f-360e5d3c0931)  
(KB2289169)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=3efbf9f6-734a-46ac-8f92-87b6ec819bfa)  
(KB2413272)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=07a6cf76-2cea-4c54-b66d-50e9eed108ac)  
(KB2289187)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=108286d4-fb68-40d6-a7b1-64b3a4eb87ee)  
(KB2413304)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=be0c5878-60c0-4700-8836-50d369b51d04)  
(KB2289158)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (32 bites kiadások)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=0b308508-0e1e-4e90-b2b8-7e32bfc5dbf4)  
(KB2289161)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 (64 bites kiadások)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (64 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=534c6a2a-e7c6-4adf-8b81-e009a2b5fff4)  
(KB2289161)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS10-087**](http://go.microsoft.com/fwlink/?linkid=203241)
</td>
<td style="border:1px solid black;">
[**MS10-088**](http://go.microsoft.com/fwlink/?linkid=198186)
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
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac<sup>[1]</sup>
(Fontos)
</td>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac<sup>[1]</sup>
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=ad1b1984-b2b2-49b3-a1dd-385b77d9248a)  
(KB2476512)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/details.aspx?familyid=8bd6ca3b-8004-4e8d-a09d-220dcbbce799)  
(KB2454823)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=b846d255-a7d4-4a2c-a084-d434c29fe676)  
(KB2476511)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="3">
További Office-szoftverek
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS10-087**](http://go.microsoft.com/fwlink/?linkid=203241)
</td>
<td style="border:1px solid black;">
[**MS10-088**](http://go.microsoft.com/fwlink/?linkid=198186)
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
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft PowerPoint megjelenítő
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft PowerPoint Viewer 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=df826b79-7398-45de-943c-6f6f0af1b4e3)  
(KB2413381)  
(Fontos)
</td>
</tr>
</table>
 
**Megjegyzés az MS10-087 közleményhez**

<sup>[1]</sup>A Microsoft Office 2004 for Mac alkalmazáshoz tartozó biztonsági frissítések jelenleg nem érhetők el.

**Megjegyzés az MS10-088 közleményhez**

<sup>[1]</sup>A Microsoft Office 2004 for Mac alkalmazáshoz tartozó biztonsági frissítések jelenleg nem érhetők el.

#### Microsoft távelérési szoftver

 
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
Microsoft Forefront Unified Access Gateway
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS10-089**](http://go.microsoft.com/fwlink/?linkid=199536)
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
Microsoft Forefront Unified Access Gateway
</td>
<td style="border:1px solid black;">
[Forefront Unified Access Gateway 2010](http://www.microsoft.com/downloads/details.aspx?familyid=5f2ee08e-e289-47db-bd3f-7b9cfc1eb985)<sup>[1]</sup>
(KB2433585)  
(Fontos)  
[Forefront Unified Access Gateway 2010 Update 1](http://www.microsoft.com/downloads/details.aspx?familyid=db0b70c8-1fa5-4d92-9888-3500c7566b19)<sup>[1]</sup>
(KB2433584)  
(Fontos)  
[Forefront Unified Access Gateway 2010 Update 2](http://www.microsoft.com/downloads/details.aspx?familyid=4e3ee07a-771c-46ee-959f-82389bab67d7)<sup>[1]</sup>
(KB2418933)  
(Fontos)
</td>
</tr>
</table>
 
**Megjegyzés az MS10-** 089 közleményhez

<sup>[1]</sup>Ez a frissítés kizárólag a Microsoft letöltőközpontból érhető el.

Észlelési és telepítési eszközök, útmutatás
-------------------------------------------

<span></span>
**Biztonsági központ**

A szoftveres és biztonsági frissítések kezeléséhez azokat a szervezet asztali és hordozható számítógépeire, valamint kiszolgálóira is telepíteni kell. További tájékoztatásért látogasson el a [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) weboldalára. A [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) bővebb tájékoztatással szolgál a Microsoft-termékek biztonsági funkcióival kapcsolatban. A [Biztonság otthon](http://go.microsoft.com/fwlink/?linkid=85102) weboldalon a megfelelő hivatkozásra kattintva elérhetőek a legújabb biztonsági frissítések.

A biztonsági frissítések a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) és a [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) weboldalról tölthetők le. A biztonsági frissítések a [Microsoft letöltőközpontjában](http://go.microsoft.com/fwlink/?linkid=21129) is elérhetőek. Legegyszerűbben a „security update” kifejezésre irányuló kulcsszavas kereséssel találhatja meg ezeket.

A biztonsági frissítések a [Microsoft Update katalógusából](http://go.microsoft.com/fwlink/?linkid=96155) is letölthetőek. A Microsoft Update katalógus a Windows Update és Microsoft Update szolgáltatáson keresztül elérhető tartalom kereshető adatbázisa; ide tartoznak a biztonsági frissítések, illesztőprogramok és szervizcsomagok. A biztonsági közlemény azonosítójára (pl. „MS07-036”) történő kereséssel hozzáadhatja az összes vonatkozó frissítést a kosárhoz (beleértve a frissítés különböző nyelvi változatait), és letöltheti azokat a megadott mappába. A Microsoft Update katalógus részletes leírását lásd a vonatkozó [GYIK](http://go.microsoft.com/fwlink/?linkid=97900)részben.

**Útmutató az észleléshez és a telepítéshez**

A biztonsági frissítésekkel kapcsolatban a Microsoft észlelési és telepítési segítséget nyújt. Ez az útmutató olyan javaslatokat és tudnivalókat tartalmaz, amelyeket segítséget nyújthatnak az informatikusoknak a biztonsági frissítések észlelési és telepítési eszközeinek használatához. További tudnivalókat a [Microsoft Tudásbázis 961747. számú cikkében](http://support.microsoft.com/kb/961747) talál.

**Microsoft Baseline Security Analyzer**

A Microsoft Baseline Security Analyzer (MBSA) segítségével a rendszergazda mind a helyi, mind a távoli számítógépeken ellenőrizheti, hogy mely biztonsági frissítések hiányoznak, illetve hogy mely biztonsági beállítások vannak helytelenül megadva. Ha többet szeretne tudni az MBSA -eszközről, látogasson el a [Microsoft Baseline Security Analyzer webhelyre](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

A Microsoft Server Update Services (WSUS) szolgáltatással a rendszergazdák gyorsan és megbízhatóan telepíthetik a legújabb fontos és biztonsági frissítéseket Microsoft Windows 2000 és újabb operációs rendszerekhez, Office XP és újabb operációs rendszerekhez, Exchange Server 2003 és SQL Server 2000 Microsoft Windows 2000 és újabb operációs rendszerekre.

A biztonsági frissítésnek Windows Server Update Services szolgáltatással történő központi telepítéséről a [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) webhelyen tudhat meg többet.

**Systems Management Server**

A Microsoft Systems Management Server (SMS) rendszer egy sokoldalúan beállítható vállalati megoldás, amely a frissítések kezelésére szolgál. Az SMS segítségével a rendszergazda megállapíthatja, hogy melyik Windows alapú számítógép szorul biztonsági frissítésre, és ezeket a frissítéseket szabályozott módon, a felhasználók minimális zavarásával központilag telepítheti a vállalat teljes informatikai környezetében. Az SMS, vagyis a System Center Configuration Manager 2007 újabb kiadása immáron elérhető, lásd még: [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Arról, hogy a rendszergazdák hogyan használhatják a biztonsági frissítések telepítéséhez az SMS 2003 alkalmazást, az [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939) részben olvashat. A biztonsági frissítések felderítéséhez az SMS 2.0 felhasználók a Security Update Inventory Tool (SUIT) eszközt is használhatják. Az SMS-szolgáltatásról bővebben a [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) oldalán olvashat.

**Megjegyzés** Az SMS a Microsoft Baseline Security Analyzer eszközön keresztül széles körű támogatást nyújt a biztonsági közlemények frissítéseinek észleléséhez, valamint a frissítések telepítéséhez. Előfordulhat, hogy egyes szoftverfrissítéseket ezek az eszközök nem észlelnek. Az SMS-alkalmazás leltározási szolgáltatásai segítségével a rendszergazdák adott rendszereken hajthatják végre a frissítést. Az eljárással kapcsolatban olvassa el a [szoftverfrissítések telepítése az SMS szoftverelosztó ügynök segítségével](http://go.microsoft.com/fwlink/?linkid=33341) című tájékoztatót. Egyes biztonsági frissítésekhez rendszergazdai jogosultságokra van szükség a számítógép újraindítása után. A rendszergazdák az Elevated Rights Deployment Tool eszközt (az [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) része) alkalmazhatják a frissítések telepítéséhez.

**Az Update Compatibility Evaluator (a frissítéskompatibilitás kiértékelője) és az Application Compatibility Toolkit (alkalmazáskompatibilitási eszközkészlet)**

Az alkalmazások működése érdekében a frissítések gyakran írnak ugyanazokba a fájlokba, illetve regisztrációs bejegyzésekbe. Ez inkompatibilitást okozhat, és növelheti a biztonsági frissítések központi telepítésére használt időt. A Windows frissítések és az alkalmazásoknak való megfelelőség tesztelése és ellenőrzése egyszerűsíthető az [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) eszközeivel, ami része az [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=hu) alkalmazáskompatibilitási eszközkészletnek.

Az Application Compatibility Toolkit (ACT) tartalmazza a Microsoft Windows Vista, a Windows Update, a Microsoft Security Update vagy a Windows Internet Explorer új verziójának központi telepítése előtt az alkalmazáskompatibilitási problémák kiértékeléséhez és enyhítéséhez szükséges eszközöket és dokumentációt.

### Egyéb információ

#### A Microsoft Windows rosszindulatú szoftvereket eltávolító eszköze

A Microsoft a Windows Update, Microsoft Update, Windows Server Update Services és Letöltőközpont szolgáltatásán keresztül elérhetővé tette a Microsoft Windows rosszindulatú szoftvereket eltávolító eszközének frissített változatát.

#### Nem biztonsági jellegű, kiemelt fontosságú frissítések a MU, WU és WSUS-szolgáltatásokban

A Windows Update és a Microsoft Update helyen elérhető, nem biztonsági jellegű frissítésekről tájékozódjon itt:

-   [Microsoft Tudásbázis 894199. cikke:](http://support.microsoft.com/kb/894199) Tartalommódosítás a Software Update Services és Windows Server Update Services rendszerek leírásában. Az összes Windows-tartalmat érinti.
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

-   A [Tipping Point](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) programjában résztvevő anonim kutató, az MS10-087 közleményben leírt egyik probléma jelentéséért
-   [team509](http://www.team509.com/), [VeriSign iDefense Labs](http://labs.idefense.com/), az MS10-087 közleményben ismertetett problémák egyikének jelentéséért
-   Dyon Balding, [Secunia](http://secunia.com/), az MS10-087 közleményben ismertetett problémák egyikének jelentéséért
-   Will Dorman, [CERT Coordination Center](http://www.cert.org/), az MS10-087 közleményben ismertetett problémák egyikének jelentéséért
-   A [TippingPoint](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/) programja, az MS10-087 közleményben ismertetett problémák egyikének jelentéséért
-   Chaouki Bekrar, [VUPEN Vulnerability Research Team](http://www.vupen.com/), az MS10-087 közleményben ismertetett problémák egyikének jelentéséért
-   Bing Liu, [Fortinet, FortiGuard Labs](http://www.fortiguard.com/), az MS10-087 közleményben ismertetett problémák egyikének jelentéséért
-   Simon Raner, [ACROS Security](http://www.acrossecurity.com), az MS10-087 közleményben ismertetett problémák egyikének jelentéséért
-   Alin Rad Pop, [Secunia Research](http://secunia.com/), az MS10-088 közleményben leírt problémák egyikének jelentéséért
-   A [Tipping Point](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) programjában résztvevő anonim kutató, az MS10-088 közleményben leírt problémák egyikének jelentéséért

#### Terméktámogatás

-   Teszteléssel állapították meg a felsorolt szoftverek egyes verzióinak érintettségét. A többi verzió támogatási életciklusa végére ért. Az egyes szoftververziók támogatási életciklusáról a [Microsoft termékek terméktámogatási életciklusát ismertető webhelyen](http://go.microsoft.com/fwlink/?linkid=21742) talál felvilágosítást.
-   Az Amerikai Egyesült Államokban és Kanada területén élő ügyfelek technikai támogatást kérhetnek a [biztonsági támogatás szolgáltatójától](http://go.microsoft.com/fwlink/?linkid=21131) vagy az 1-866-PCSAFETY telefonszámon. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. Az elérhető támogatási lehetőségekről további információt talál a [Microsoft segítségnyújtással és támogatással foglalkozó webhelyén](http://support.microsoft.com/).
-   Más országokban a helyi Microsoft-képviseletek nyújtanak támogatást. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. A [nemzetközi támogatási webhely](http://go.microsoft.com/fwlink/?linkid=21155) felvilágosítást nyújt arról, támogatási kérdéseivel hogyan fordulhat a Microsofthoz.

#### Felelősséget kizáró nyilatkozat

A Microsoft Tudásbázisban leírtak előzetes bejelentés nélkül változhatnak, és a cikkek tartalmáért a Microsoft nem vállal garanciát. A Microsoft egyben elhárít minden kifejezett és értelemszerű garanciát, beleértve az eladhatóságra és az adott célra való alkalmasságra vonatkozó garanciát is. A Microsoft Corporation vagy annak szállítói semmilyen körülmények között nem tehetők felelőssé közvetlen, közvetett, eseti, ok-okozati vagy különleges kárért (beleértve az elmaradt hasznot is), még akkor sem, ha a Microsoft Corporation vagy szállítói tudatában voltak a kár lehetséges voltának. Egyes államok törvényi szabályozása nem teszi lehetővé a véletlen vagy ok-okozati károkért vállalt felelősség korlátozását vagy kizárását, így ezekben az államokban az ez a felelősségkizárás nincs érvényben.

#### Verziók

-   1.0 verzió (2010. november 9.): Összefoglaló közlemény közzététele.
-   1.1 verzió (2010. november 9.): Az MS10-088 közleményben az érintett verzió helyesen „Microsoft PowerPoint Viewer” helyett „Microsoft PowerPoint Viewer 2007 Service Pack 2”. A módosítás csak tájékoztató jellegű. A rendszer frissítését sikeresen elvégző felhasználóknak, ideértve az automatikus frissítést alkalmazókat is, nincs tennivalójuk. A frissítést még nem telepített felhasználóknak lehetséges, hogy az érintett szoftverek javított táblázata alapján ellenőrizniük kell, hogy rendszerük frissítésre szorul-e.
-   1.2 verzió (2010. november 17.): Kiegészítettük az MS10-087 közleményben található Kihasználhatósági információkat a jelen frissítésben tárgyalt CVE-2010-2573 biztonsági réssel. A módosítás csak tájékoztató jellegű.
-   2.0 verzió (2010. december 15.): Az összefoglaló közlemény módosítása tájékoztat arról, hogy az MS10-087 közleményre vonatkozó biztonsági frissítések elérhetők a Microsoft Office 2008 for Mac (KB2476512) ls Open XML File Format Converter for Mac (KB2476511) rendszerekhez. A Microsoft javasolja, hogy az említett szoftverek felhasználói mielőbb telepítsék a frissítéseket.

*Built at 2014-04-18T01:50:00Z-07:00*
