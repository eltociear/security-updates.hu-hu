---
TOCTitle: 'MS06-FEB'
Title: 'Microsoft biztonsági közlemény - összefoglalás, február 2006'
ms:assetid: 'ms06-feb'
ms:contentKeyID: 61227695
ms:mtpsurl: 'https://technet.microsoft.com/hu-HU/library/ms06-feb(v=Security.10)'
author: SharonSears
ms.author: SharonSears
---

Security Bulletin Summary

Microsoft biztonsági közlemény - összefoglalás, február 2006
============================================================

Közzétéve: 2006. február 14.

**Verzió:** 1.0

Az információk végfelhasználók számára készült összefoglalója [ezen a webhelyen](http://www.microsoft.com/security/default.mspx) található.

**A számítógép védelme:** A Microsoft az alábbi helyeken tette közzé a számítógép védelmével kapcsolatos ajánlásait:

-   Végfelhasználók keressék fel [A számítógép védelme webhelyet](http://go.microsoft.com/fwlink/?linkid=21169).
-   Informatikai szakemberek látogassanak el a [Security Guidance Center](http://go.microsoft.com/fwlink/?linkid=21171) webhelyre.

**Frissítésekkel kapcsolatos stratégiák:** A [biztonsági javítások kezelésével, a biztonsági frissítésekkel és a letöltésekkel foglalkozó webhely](http://go.microsoft.com/fwlink/?linkid=21168) további információt nyújt a Microsoft biztonsági frissítések alkalmazásával kapcsolatos gyakorlati tanácsairól.

**IT Pro Security Zone közösség:** Az [IT Pro Security Zone webhelyen](http://go.microsoft.com/fwlink/?linkid=21164) hasznos információt találhat a biztonság fokozásáról és az informatikai infrastruktúrák optimalizálásáról, továbbá eszmecserét folytathat a biztonsági kérdésekről más informatikai szakemberekkel.

**Microsoft Security Notification Service:** Ha értesítést szeretne kapni a Microsoft Security Bulletin cikkeinek megjelenéséről, fizessen elő a Microsoft Security Notification Service szolgáltatásra a [Microsoft Security Notification Service](http://go.microsoft.com/fwlink/?linkid=21163) webhelyen.

#### Összefoglalás

Ez a dokumentum ismerteti a nemrégiben felfedezett biztonsági résekhez kiadott frissítéseket. A biztonsági rések (súlyosság szerint) az alábbiak.

Kritikus (2)
------------

<span></span>
| Közlemény azonosítója         | Microsoft biztonsági közlemény MS06-004                                                                                     |
|-------------------------------|-----------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**            | [**Összesítő biztonsági frissítés az Internet Explorer programhoz (910620)**](http://go.microsoft.com/fwlink/?linkid=57064) |
| **Összefoglalás**             | Biztonsági rés található a képmegjelenítő rendszerben, amely a lehetővé teheti programkód távoli futtatását.                |
| **Súlyosság maximális foka:** | [Kritikus](http://go.microsoft.com/fwlink/?linkid=21140)                                                                    |
| **A biztonsági rés hatása:**  | Távoli kódfuttatás                                                                                                          |
| **Érintett szoftverek**       | **Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                            |

| Közlemény azonosítója         | Microsoft biztonsági közlemény MS06-005                                                                                         |
|-------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**            | **A Windows Media Player biztonsági rése, amely távoli programkódfuttatást tehet lehetővé (911565)**                            |
| **Összefoglalás**             | A Windows Media Player bizonyos fájlok feldolgozási módjában távoli programkódfuttatást lehetővé tevő biztonsági rés található. |
| **Súlyosság maximális foka:** | [Kritikus](http://go.microsoft.com/fwlink/?linkid=21140)                                                                        |
| **A biztonsági rés hatása:**  | Távoli kódfuttatás                                                                                                              |
| **Érintett szoftverek**       | **Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                |

Fontos (5)
----------

<span></span>
| Közlemény azonosítója        | Microsoft biztonsági közlemény MS06-006                                                                                                               |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**           | **A Windows Media Player bővítmény biztonsági rése miatt a nem Microsoft gyártmányú böngészőkben lehetővé válhat a távoli kódfuttatás (911564)**      |
| **Összefoglalás**            | Távoli programkódfuttatást lehetővé tevő biztonsági rés található a Windows Media Player nem Microsoft gyártmányú böngészőkhöz készült bővítményében. |
| **Súlyosság maximális foka** | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                |
| **A biztonsági rés hatása:** | Távoli kódfuttatás                                                                                                                                    |
| **Érintett szoftverek**      | **Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                      |

| Közlemény azonosítója        | Microsoft biztonsági közlemény MS06-007                                                                                                                                   |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**           | [**Szolgáltatásmegtagadást lehetővé tévő TCP/IP biztonsági rés (913446)**](http://go.microsoft.com/fwlink/?linkid=59797)                                                  |
| **Összefoglalás**            | Egy biztonsági rés következtében a támadó olyan különlegesen kialakított IGMP üzenetet küldhet, amely az érintett rendszert a válaszadások megszakítására kényszerítheti. |
| **Súlyosság maximális foka** | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                    |
| **A biztonsági rés hatása:** | Szolgáltatásmegtagadás                                                                                                                                                    |
| **Érintett szoftverek**      | **Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                          |

| Közlemény azonosítója        | Microsoft biztonsági közlemény MS06-008                                                                                                                                                                                                                                         |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**           | [**A Web Client szolgáltatás biztonsági rése (911927) programkód távoli futtatását teheti lehetővé**](http://go.microsoft.com/fwlink/?linkid=59441)                                                                                                                             |
| **Összefoglalás**            | A Web Client szolgáltatás biztonsági réseit kihasználó támadó teljesen átveheti az irányítást a rendszer felett. A támadónak a biztonsági rés kihasználásához érvényes bejelentkezési adatokkal kell rendelkeznie, és képesnek kell lennie helyileg bejelentkezni a rendszerbe. |
| **Súlyosság maximális foka** | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                          |
| **A biztonsági rés hatása:** | Távoli kódfuttatás                                                                                                                                                                                                                                                              |
| **Érintett szoftverek**      | **Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                |

| Közlemény azonosítója        | Microsoft biztonsági közlemény MS06-009                                                                                                                                                                                                                                                                                     |
|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**           | [**A koreai írásjegy-beviteli mód a jogosultság illetéktelen megszerzésének biztonsági rését teszi lehetővé (901190)**](http://go.microsoft.com/fwlink/?linkid=49512)                                                                                                                                                       |
| **Összefoglalás**            | A Windows és az Office koreai írásjegybevivőjében található biztonsági rést kihasználva a támadó teljes mértékben átveheti az érintett rendszer irányítását. A támadónak a biztonsági rés kihasználásához érvényes bejelentkezési adatokkal kell rendelkeznie, és képesnek kell lennie helyileg bejelentkezni a rendszerbe. |
| **Súlyosság maximális foka** | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                      |
| **A biztonsági rés hatása:** | Jogosultság illetéktelen megszerzése                                                                                                                                                                                                                                                                                        |
| **Érintett szoftverek**      | **Windows és Office.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                  |

| Közlemény azonosítója        | Microsoft biztonsági közlemény MS06-010                                                                           |
|------------------------------|-------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**           | **Adatokhoz való illetéktelen hozzáférést lehetővé tévő biztonsági rés a PowerPoint 2000 alkalmazásban (889167)** |
| **Összefoglalás**            | Adatokhoz való illetéktelen hozzáférést lehetővé tévő biztonsági rés található a PowerPoint alkalmazásban.        |
| **Súlyosság maximális foka** | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                            |
| **A biztonsági rés hatása:** | Adatokhoz való illetéktelen hozzáférés                                                                            |
| **Érintett szoftverek**      | **Office.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                   |

Érintett szoftverek és letöltési helyek
---------------------------------------

<span></span>
**A táblázat használata**

A táblázat segítségével megtudhatja a szükséges információt a telepítendő biztonsági frissítésekről. Nézzen meg minden felsorolt szoftvert vagy összetevőt annak megállapításához, hogy van-e telepítendő biztonsági frissítés. Ha egy szoftver vagy összetevő szerepel a felsorolásban, akkor a biztonsági rés hatását is tartalmazza a táblázat az elérhető szoftverfrissítésre mutató hivatkozással együtt.

A táblázatban a zárójelben lévő szám \[x\] azt jelzi, hogy a problémához magyarázó megjegyzés tartozik. Ezek a megjegyzések a táblázat alatt találhatók.

**Megjegyzés:** Előfordulhat, hogy egy biztonsági rés megszüntetéséhez több biztonsági frissítést kell telepíteni. Nézze át az egyes közleményazonosítókhoz tartozó teljes oszlopot, és ellenőrizze a telepítendő frissítéseket a rendszerre telepített programok vagy összetevők alapján.

#### Érintett szoftverek és letöltési helyek az MS06-004 és MS06-007 közlemények vonatkozásában

 
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ></th>
<th style="border:1px solid black;" >Részletek        </th>
<th style="border:1px solid black;" >Részletek        </th>
<th style="border:1px solid black;" >Részletek   </th>
<th style="border:1px solid black;" >Részletek   </th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Közlemény azonosítója</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=57064"><strong>MS06-004</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=59277"><strong>MS06-005</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=59278"><strong>MS06-006</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=59797"><strong>MS06-007</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Súlyosság maximális foka:</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritikus</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritikus</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Fontos</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Fontos</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Érintett Windows-szoftverek:</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ccdd3d35-be5c-4c43-8ffa-bb8570a7321c">Fontos</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=78d7df14-6049-4318-89ca-9c8681ced8ab">Fontos</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 Service Pack 1</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ccdd3d35-be5c-4c43-8ffa-bb8570a7321c">Fontos</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=78d7df14-6049-4318-89ca-9c8681ced8ab">Fontos</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e3daab50-2ac7-49dd-8971-4f98fed9fba6">Fontos</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=12aae69e-c5c3-4e4a-9970-f5db84dd9744">Fontos</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 Itanium alapú rendszerekhez</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9ae276cf-ab46-4198-bcb3-3effdf15550e">Fontos</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 SP1 csomaggal felszerelt Itanium-alapú rendszerekhez</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9ae276cf-ab46-4198-bcb3-3effdf15550e">Fontos</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Service Pack 1</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ccdd3d35-be5c-4c43-8ffa-bb8570a7321c">Fontos</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7bb21d74-c37b-472b-bb10-71d4680680a7">Fontos</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Service Pack 2</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ccdd3d35-be5c-4c43-8ffa-bb8570a7321c">Fontos</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7bb21d74-c37b-472b-bb10-71d4680680a7">Fontos</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Professional x64 Edition</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=165916c2-037e-4edd-b64a-84838bee151c">Fontos</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e2538cc-cc90-4db7-8d0b-0b8ba4234e67">Fontos</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Service Pack 4</td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ccdd3d35-be5c-4c43-8ffa-bb8570a7321c">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Millennium Edition (Me)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 98 Second Edition (SE)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 98</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><strong>[1]</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>A Windows operációs rendszer érintett összetevői:</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Internet Explorer 5.01 Service Pack 4 Microsoft Windows 2000 Service Pack 4 rendszeren</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c0df2fc3-2075-46b5-945f-6e0bd6806151">Kritikus</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 98, 98 SE, ME és Windows 2000 Service Pack 4 rendszerekre telepített Windows Media Player 7.1</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=26a0b9e1-1242-4e55-b3d4-8377b83257c6">Fontos</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Windows XP Service Pack 1 rendszerre telepített Windows Media Player for XP</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=110054f2-244d-4036-b98c-e951cba7e9ba">Fontos</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 98, 98 SE, ME, Windows 2000 Service Pack 4 és Windows XP Service Pack 1 rendszerekre telepített Windows Media Player 9</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8f9eef16-04f7-4da8-a0ef-1797b52d0b4b">Kritikus</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Service Pack 2 vagy Windows Server 2003 rendszerekre telepített Windows Media Player 9</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8f9eef16-04f7-4da8-a0ef-1797b52d0b4b">Kritikus</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Service Pack 1 vagy Windows XP Service Pack 2 rendszerekre telepített Windows Media Player 10</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=182735e1-9382-4f2e-a624-d2316a96b411">Kritikus</a></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
</tbody>
</table>
  
#### Érintett szoftverek és letöltési helyek az MS06-008 és MS06-010 közlemények vonatkozásában

 
<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="25%" />
<col width="25%" />
<col width="25%" />
<col width="25%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" ></th>
<th style="border:1px solid black;" >Részletek   </th>
<th style="border:1px solid black;" >Részletek   </th>
<th style="border:1px solid black;" >Részletek        </th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Közlemény azonosítója</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=59441"><strong>MS06-008</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=49512"><strong>MS06-009</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=61558"><strong>MS06-010</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Súlyosság maximális foka:</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Fontos</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Fontos</strong></a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Fontos</strong></a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Érintett Windows-szoftverek:</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fa073183-0c83-4f1c-be46-a2ee8a1a1440">Mérsékelt</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a092ba0f-c753-444b-a572-492e4ecb2d3f">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fa073183-0c83-4f1c-be46-a2ee8a1a1440">Mérsékelt</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a092ba0f-c753-444b-a572-492e4ecb2d3f">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 x64 Edition</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e2f5413a-0b77-4c18-9bab-e2470d3d3f4e">Mérsékelt</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=66e495e8-cd52-4e76-b20a-4471fa941556">Fontos </a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Server 2003 Itanium alapú rendszerekhez</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e186e149-208a-4035-a0fc-e1cbde4e6fef">Mérsékelt</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8479c2eb-0fb6-4879-9c3d-b49bd864a71c">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows Server 2003 SP1 csomaggal felszerelt Itanium-alapú rendszerekhez</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e186e149-208a-4035-a0fc-e1cbde4e6fef">Mérsékelt</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8479c2eb-0fb6-4879-9c3d-b49bd864a71c">Fontos </a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Service Pack 1</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=62535040-5204-4469-b0bf-eae14567c2d5">Fontos</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=290453df-1cae-4691-b20c-5d65d92216bf">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows XP Service Pack 2</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=62535040-5204-4469-b0bf-eae14567c2d5">Fontos</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=290453df-1cae-4691-b20c-5d65d92216bf">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows XP Professional x64 Edition</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9734f634-6869-434f-aaf0-47b70f84d178">Fontos</a></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7d75bf5c-2e1d-4793-b7d1-dd372a99eca5">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 2000 Service Pack 4</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows Millennium Edition (Me)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Windows 98 Second Edition (SE)</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Windows 98</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Érintett Office-szoftverek:</strong></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Office 2003 Service Pack 1</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e6f16e9-cd73-47d5-887e-616db9b09591">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Office 2003 Service Pack 2</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e6f16e9-cd73-47d5-887e-616db9b09591">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Office 2003 Multilingual User Interface csomagok</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=986f9a8d-afe7-455a-b78d-0795cbb0e80e">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Office Project 2003 Multilingual User Interface csomagok</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=22c96d7f-f384-4678-9ac0-3a11b81a4c1d">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Office Visio 2003 Multilingual User Interface csomagok</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5a4d0a92-2dfc-4f8b-9d14-138cea57af96">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Office 2003 Proofing Tools</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=32cf9f59-ffbd-45e5-a4d2-690183462d0f">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Office Visio 2003</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e6f16e9-cd73-47d5-887e-616db9b09591">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Office OneNote 2003</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e6f16e9-cd73-47d5-887e-616db9b09591">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Office Project 2003</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/hu-HU/library///www.microsoft.com/downloads/details.aspx?familyid=8e6f16e9-cd73-47d5-887e-616db9b09591(v=Security.10)">Fontos</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PowerPoint 2000</td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"></td>
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/hu-HU/library///www.microsoft.com/downloads/details.aspx?familyid=e51b27c8-2f31-4e99-b868-ce626fed5b7d(v=Security.10)">Fontos</a></td>
</tr>
</tbody>
</table>
  
**Megjegyzés**
  
**<sup>[1]</sup>** Ehhez az operációs rendszerhez rendelkezésre áll biztonsági frissítés. További információt talál a táblázat Microsoft Internet Explorer és a Windows Media Player programra vonatkozó részében és az ide vonatkozó biztonsági közleményben.
  
Telepítés  
---------
  
<span></span>
**Software Update Services:**
  
A Microsoft Software Update Services (SUS) szolgáltatással a rendszergazdák gyorsan és megbízható módon telepíthetik központilag a legújabb fontos és biztonsági frissítéseket a Windows 2000 és a Windows Server 2003 rendszerű kiszolgálókra, valamint a Windows 2000 Professional vagy a Windows XP Professional rendszert futtató asztali rendszerekre.
  
A biztonsági frissítés Software Update Services szolgáltatással történő központi telepítéséről a [Software Update Services webhelyen](http://go.microsoft.com/fwlink/?linkid=21133) tudhat meg többet.
  
**Windows Server Update Services:**
  
A Microsoft Software Update Services (WSUS) szolgáltatással a rendszergazdák gyorsan és megbízható módon telepíthetik központilag a legújabb fontos és biztonsági frissítéseket Windows 2000 és újabb operációs rendszerekhez, Office XP és újabb operációs rendszerekhez, Exchange Server 2003 és SQL Server 2000 Windows 2000 és újabb operációs rendszerekre.
  
A biztonsági frissítésnek Windows Server Update Services szolgáltatással történő központi telepítéséről a [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) webhelyen tudhat meg többet.
  
**Systems Management Server:**
  
A Microsoft Systems Management Server (SMS) rendszer egy sokoldalúan beállítható vállalati megoldás, amely a frissítések kezelésére szolgál. Az SMS segítségével a rendszergazda megállapíthatja, hogy melyik Windows alapú számítógép szorul biztonsági frissítésre, és ezeket a frissítéseket szabályozott módon, a felhasználók minimális zavarásával központilag telepítheti a vállalat teljes informatikai környezetében. Ha többet szeretne tudni arról, hogy a rendszergazdák miként telepíthetik központilag a biztonsági frissítéseket az SMS 2003 alkalmazással, látogasson el az [SMS 2003 Security Patch Management webhelyre](http://go.microsoft.com/fwlink/?linkid=22939). Az SMS 2.0-s verzióját használók a [Software Updates Service Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) szolgáltatásait is segítségül hívhatják a biztonsági frissítések központi telepítéséhez. Az SMS rendszerről az [SMS webhelyén](http://go.microsoft.com/fwlink/?linkid=21158) talál további információt.
  
**Megjegyzés:** Az SMS a Microsoft Baseline Security Analyzer és a Microsoft Office Detection Tool program segítségével széles körű támogatást nyújt a biztonsági közlemények frissítéseinek észleléséhez és telepítéséhez. Előfordulhat, hogy egyes szoftverfrissítéseket ezek az eszközök nem észlelnek. Az SMS alkalmazás leltározási szolgáltatásai segítségével a rendszergazdák adott rendszereken hajthatják végre a frissítést. Az eljárásról további információt talál [ezen a webhelyen](http://go.microsoft.com/fwlink/?linkid=33341). Egyes biztonsági frissítésekhez rendszergazdai jogosultságokra van szükség a számítógép újraindítása után. A rendszergazdák az [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) és az [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) csomag részét képező Elevated Rights Deployment Tool nevű eszközzel telepíthetik ezeket a frissítéseket.
  
**A QChain.exe és az Update.exe használata:**
  
A Microsoft által kibocsátott QChain.exe nevű parancssori eszközzel a rendszergazda biztonságosan egybefűzheti a biztonsági frissítéseket. *Az egybefűzés* azt jelenti, hogy egymás után több frissítés is telepíthető a számítógép újraindítása nélkül. A jelen dokumentum frissítéseihez használt Update.exe beépített egybefűzési funkcióval rendelkezik. Windows 2000 Service Pack 2 vagy újabb, Windows XP vagy Windows Server 2003 operációs rendszer esetén a Qchain.exe programra nincs szükség a frissítések egybefűzéséhez. A Qchain.exe ennek ellenére támogatja e Windows rendszerek frissítéseinek egybefűzését, így a rendszergazda különböző operációs rendszerekhez egységes telepítési parancsfájlt készíthet. Ha többet szeretne tudni a QChain eszközről, látogasson el erre a [webhelyre](http://go.microsoft.com/fwlink/?linkid=21156).
  
**Microsoft Baseline Security Analyzer:**
  
A Microsoft Baseline Security Analyzer (MBSA) segítségével a rendszergazda mind a helyi, mind a távoli számítógépeken ellenőrizheti, hogy mely biztonsági frissítések hiányoznak, illetve hogy mely biztonsági beállítások vannak helytelenül megadva. Ha többet szeretne tudni az MBSA eszközről, látogasson el a [Microsoft Baseline Security Analyzer webhelyre](http://go.microsoft.com/fwlink/?linkid=21134).
  
**Útmutató az észleléshez és a telepítéshez:**
  
A Microsoft az e havi biztonsági frissítésekhez észlelési és telepítési útmutatót adott ki. Az útmutató a számítógépes szakembereknek is ötleteket adhat ahhoz, hogyan használják a különböző eszközöket, pl. Windows Update, Microsoft Update, Office Update, Microsoft Baseline Security Analyzer (MBSA), Office Detection Tool, Microsoft Systems Management Server (SMS), Extended Security Update Inventory Tool vagy Enterprise Update Scan Tool (EST) a biztonsági frissítések telepítéséhez. További információt a [Microsoft Tudásbázis 910723. számú cikkében](http://support.microsoft.com/kb/910723) talál.
  
#### Egyéb információ
  
**Köszönetnyilvánítás**
  
A Microsoft [köszönetét](http://go.microsoft.com/fwlink/?linkid=21127) fejezi ki a vásárlók védelmének biztosításában nyújtott segítségért az alábbi szervezet(ek)nek és szakember(ek)nek:
  
-   Marc Maiffret (eEye) - az [MS06-005](http://technet.microsoft.com/security/bulletin/ms06-005) számú közleményben ismertetett probléma jelentéséért.  
-   John Cobb (iDefense) - az [MS06-006](http://technet.microsoft.com/security/bulletin/ms06-006) számú közleményben ismertetett probléma jelentéséért.  
-   Douglas Nascimento (Datacom) - az [MS06-007](http://technet.microsoft.com/security/bulletin/ms06-007) számú közleményben ismertetett probléma jelentéséért.  
-   Kostya Kortchinsky ([EADS/CRC](http://www.eads.net/)) - az [MS06-008](http://technet.microsoft.com/security/bulletin/ms06-008) számú közleményben ismertetett probléma jelentéséért.  
-   [Ryan Lee](http://www.microsoft.com/technet/security/bulletin/e-mail%20cím:newrun@gmail.com) - az [MS06-009](http://technet.microsoft.com/security/bulletin/ms06-009) számú közleményben ismertetett probléma jelentéséért.  
-   Andreas Sandblad - az [MS06-010](http://technet.microsoft.com/security/bulletin/ms06-010) számú közleményben ismertetett probléma jelentéséért.  
-   Yorick Koster (ITsec Security Services) - az [MS06-010](http://technet.microsoft.com/security/bulletin/ms06-010) számú közleményben ismertetett probléma jelentéséért.  
-   **Egyéb biztonsági frissítések beszerzése:**
  
    Az alábbi helyekről más típusú biztonsági problémákhoz szerezhetők be frissítések.
  
    -   A biztonsági frissítések a [Microsoft letöltőközpontban](http://go.microsoft.com/fwlink/?linkid=21129) érhetők el: legegyszerűbben a „biztonsági javítás” kifejezésre irányuló kulcsszavas kereséssel találhatja meg őket.  
    -   A kereskedelmi forgalomban kapható operációs rendszerekhez a [Microsoft Update webhelyről](http://go.microsoft.com/fwlink/?linkid=40747) tölthetők le frissítések.  
    -   A Windows Update webhelyen ebben a hónapban kínált biztonsági frissítések ISO lemezképfájl formájában is beszerezhetők (biztonsági és kritikus kiadások), a további tudnivalókat lásd a [Microsoft Tudásbázis 913086. számú cikkében](http://support.microsoft.com/kb/913086).
  
    **Terméktámogatás:**
  
    -   Az Amerikai Egyesült Államokban és Kanadában technikai segítség igényelhető a [Microsoft terméktámogatási szolgáltatásától](http://go.microsoft.com/fwlink/?linkid=21131), amelynek telefonszáma 1-866-PCSAFETY. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek.  
    -   Más országokban a helyi Microsoft képviseletek nyújtanak támogatást. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. A [nemzetközi támogatási webhely](http://go.microsoft.com/fwlink/?linkid=21155) felvilágosítást nyújt arról, támogatási kérdéseivel hogyan fordulhat a Microsofthoz.
  
    **Egyéb adatvédelmi és biztonsági források:**
  
    -   A [Microsoft TechNet Security](http://go.microsoft.com/fwlink/?linkid=21132) biztonsággal foglalkozó webhelye további információkat tartalmaz a Microsoft termékeinek biztonsági kérdéseiről.  
    -   [Microsoft Software Update Services](http://go.microsoft.com/fwlink/?linkid=21133)  
    -   [Microsoft Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120)  
    -   [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) (MBSA)  
    -   [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)  
    -   [Microsoft Update](http://update.microsoft.com/microsoftupdate)  
    -   Windows Update katalógus: A Windows Update katalógusról a Microsoft Tudásbázis [323166](http://support.microsoft.com/default.aspx?scid=kb;en-us;323166) számú cikkében talál információkat.  
    -   [Office Update](http://go.microsoft.com/fwlink/?linkid=21135)
  
    **Felelősséget kizáró nyilatkozat:**
  
    A Microsoft Tudásbázisban leírtak előzetes bejelentés nélkül változhatnak, és a cikkek tartalmáért a Microsoft nem vállal garanciát. A Microsoft egyben elhárít minden kifejezett és értelemszerű garanciát, beleértve az eladhatóságra és az adott célra való alkalmasságra vonatkozó garanciát is. A Microsoft Corporation vagy annak szállítói semmilyen körülmények között nem tehetők felelőssé közvetlen, közvetett, eseti, ok-okozati vagy különleges kárért (beleértve az elmaradt hasznot is), még akkor sem, ha a Microsoft Corporation vagy szállítói tudatában voltak a kár lehetséges voltának. Egyes államok törvényi szabályozása nem teszi lehetővé a véletlen vagy ok-okozati károkért vállalt felelősség korlátozását vagy kizárását, így ezekben az államokban az ez a felelősségkizárás nincs érvényben.
  
    **Verziók:**
  
    -   1.0 verzió (2006. február 14.): Kiadás dátuma
  
  
*Built at 2014-04-18T01:50:00Z-07:00*
