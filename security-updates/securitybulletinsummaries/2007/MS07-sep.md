---
TOCTitle: 'MS07-SEP'
Title: 'Microsoft biztonsági közlemény - összefoglalás, szeptember 2007'
ms:assetid: 'ms07-sep'
ms:contentKeyID: 61227715
ms:mtpsurl: 'https://technet.microsoft.com/hu-HU/library/ms07-sep(v=Security.10)'
author: SharonSears
ms.author: SharonSears
---

Security Bulletin Summary

Microsoft biztonsági közlemény - összefoglalás, szeptember 2007
===============================================================

Közzétéve: 2007. szeptember 11. | Frissítve: 2007. szeptember 12.

**Verzió:** 1.1

Az összefoglaló a 2007 szeptemberében kiadott biztonsági közleményeket összegzi.

A 2007. szeptemberi közlemények kiadása folytán az összefoglaló a 2007. szeptember 6-án kiadott előzetes értesítés helyébe lép. További információk a biztonsági közlemények kiadásáról szóló előzetes értesítés szolgáltatásról lásd: [Előzetes értesítés a Microsoft biztonsági közleményeinek kiadásáról](http://technet.microsoft.com/security/bulletin/advance).

Ha automatikus értesítést szeretne kapni a Microsoft biztonsági közleményeinek megjelenéséről, fizessen elő a [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) szolgáltatásra.

A közleményekkel kapcsolatos kérdések megválaszolására a Microsoft 2007. szeptember 12-én, csendes-óceáni idő szerint 11 órakor webszemináriumot tart. [Jelentkezzen most a szeptemberi közleményeket bemutató webes szemináriumra](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344690&eventcategory=4&culture=en-us&countrycode=us). Ezt követően a webszeminárium igény szerint kerül megrendezésre. További információkért látogasson el a [Microsoft biztonsági közleményeit és a webes szemináriumokat](http://technet.microsoft.com/security/bulletin/summary)bemutató oldalra.

A Microsoft abban is segítséget nyújt felhasználóinak, hogy a havi biztonsági közleményekkel azonos napon kiadott, nem biztonsági jellegű, de fontos frissítéseket megfelelően rangsorolhassák. Lásd az **Egyéb információ című részt**.

### A közleménnyel kapcsolatos információk

#### Összefoglalások

Az e havi biztonsági közlemények súlyossági sorrendben:

Kritikus (1)
------------

<span></span>
| Közlemény azonosítója                          | A Microsoft MS07-051 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**A Microsoft Agent biztonsági rése távolról történő programkódfuttatást tehet lehetővé (938827)**](http://go.microsoft.com/fwlink/?linkid=94667)                                                                                                                                                                                                                                                                                                                                                    |
| **Összefoglalás**                              | Ez a kritikus besorolású frissítés egy közvetlenül jelzett biztonsági rést szüntet meg. A Microsoft Agent programban bizonyos különlegesen kialakított URL-címek kezelési módja miatt távoli kódfuttatást lehetővé tevő biztonsági rés keletkezhet. A biztonsági rés az érintett rendszerben távoli programkódfuttatást tesz lehetővé. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén |
| **Súlyosság maximális foka**                   | [Kritikus](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **A biztonsági rés hatása**                    | Távoli kódfuttatás                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. A frissítés a rendszer újraindítását igényli.                                                                                                                                                                                                                                                                                                                                                  |
| **Érintett szoftverek**                        | **Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                                                                                                                      |

Fontos (3)
----------

<span></span>
| Közlemény azonosítója                          | A Microsoft MS07-052 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                              |
|------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**A Crystal Reports for Visual Studio alkalmazás biztonsági rése programkód távoli futtatását teheti lehetővé (941522)**](http://go.microsoft.com/fwlink/?linkid=98460)                                                                                                                                                                                                                      |
| **Összefoglalás**                              | Ez a fontos besorolású frissítés egy nyilvánosan jelentett biztonsági rést szüntet meg. A biztonsági rések távoli kódvégrehajtást tehetnek lehetővé, amennyiben a felhasználó egy különlegesen kialakított RPT-fájlt nyit meg. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén |
| **Súlyosság maximális foka**                   | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                        |
| **A biztonsági rés hatása**                    | Távoli kódfuttatás                                                                                                                                                                                                                                                                                                                                                                            |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer és az Enterprise Update Scan Tool észleli, szükség van-e a számítógépen az adott frissítésre. Előfordulhat, hogy a frissítés a rendszer újraindítását igényli.                                                                                                                                                                                         |
| **Érintett szoftverek**                        | **Visual Studio.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                        |

| Közlemény azonosítója                          | A Microsoft MS07-053 számú biztonsági közleménye                                                                                                                                                                                                                                                                                             |
|------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**A Windows Services for UNIX alkalmazás biztonsági rése jogok kiterjesztését teheti lehetővé (939778)**](http://go.microsoft.com/fwlink/?linkid=94467)                                                                                                                                                                                     |
| **Összefoglalás**                              | Ez a fontos besorolású frissítés egy nyilvánosan jelzett biztonsági rést szüntet meg. A Windows Services for UNIX 3.0, Windows Services for UNIX 3.5, és Subsystem for UNIX-based Applications alkalmazásokban biztonsági rés található, amely miatt bizonyos bináris setuid fájlok futtatásakor a támadó jogok kiterjesztését végezheti el. |
| **Súlyosság maximális foka**                   | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                       |
| **A biztonsági rés hatása**                    | Jogok kiterjesztése                                                                                                                                                                                                                                                                                                                          |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer és az Enterprise Update Scan Tool észleli, szükség van-e a számítógépen az adott frissítésre. A frissítés a rendszer újraindítását igényli.                                                                                                                                                           |
| **Érintett szoftverek**                        | **A Windows Services for UNIX, Subsystem for UNIX alapú alkalmazások.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                  |

| Közlemény azonosítója                          | A Microsoft MS07-054 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**Az MSN Messenger és a Windows Live Messenger alkalmazás biztonsági rése programkód távoli futtatását teheti lehetővé (942099)**](http://go.microsoft.com/fwlink/?linkid=100148)                                                                                                                                                                                                                                                                                                                                                                                               |
| **Összefoglalás**                              | A biztonsági frissítés feladata az MSN Messenger és a Windows Live Messenger alkalmazás nyilvánosan közzétett biztonsági résének megszüntetése. A támadótól érkező, videobeszélgetésre vagy webkamerás beszélgetésre felkérő meghívó felhasználó általi elfogadása programkód távoli futtatását teheti lehetővé. A biztonsági rést kihasználó támadó teljes mértékben átveheti a megtámadott rendszer vezérlését. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén |
| **Súlyosság maximális foka**                   | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **A biztonsági rés hatása**                    | Távoli kódfuttatás                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **A szoftver észlelésével kapcsolatos adatok** | Ezek a termékek a frissítések telepítéséhez és automatikus észleléséhez beépített mechanizmusokkal rendelkeznek. Előfordulhat, hogy a frissítés a rendszer újraindítását igényli.                                                                                                                                                                                                                                                                                                                                                                                                |
| **Érintett szoftverek**                        | **MSN Messenger, Windows Live Messenger.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

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
[**MS07-051**](http://go.microsoft.com/fwlink/?linkid=94667)
</td>
<td style="border:1px solid black;">
[**MS07-052**](http://go.microsoft.com/fwlink/?linkid=98460)
</td>
<td style="border:1px solid black;">
[**MS07-053**](http://go.microsoft.com/fwlink/?linkid=94467)
</td>
<td style="border:1px solid black;">
[**MS07-054**](http://go.microsoft.com/fwlink/?linkid=100148)
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
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<th colspan="5">
Windows operációs rendszer:
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=7cd248ed-d154-4dce-89ef-ceefd2700965)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5">
A Windows operációs rendszer érintett összetevői
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Services for UNIX 3.0 alkalmazás Windows 2000 Service Pack 4 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Services for UNIX 3.5 alkalmazás Windows 2000 Service Pack 4 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Services for UNIX 3.0 alkalmazás Windows XP Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Services for UNIX 3.5 alkalmazás Windows XP Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Services for UNIX 3.0 alkalmazás Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Services for UNIX 3.5 alkalmazás Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Subsystem for UNIX-based Applications alkalmazás Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=8ab5cc43-0b9c-45eb-aa51-47568ab6ce3f)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Subsystem for UNIX-based Applications alkalmazás Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=1d21e3e8-b5f6-4044-9db6-054af836492b)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Subsystem for UNIX-based Applications alkalmazás Windows Vista rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=4d52e4f4-2888-42df-8163-85c648e65b29)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Subsystem for UNIX-based Applications alkalmazás Windows Vista x64 Edition rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=4be667cc-c239-480b-a9a0-939bcd27f0de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5">
Fejlesztői eszközök és rendszerek
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio .NET 2002 Service Pack 1  
(KB937057)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=2608c83b-e1b2-4449-9a0e-1e566aac3d76)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visual Studio .NET 2003:  
(KB937058)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=d612ad41-5a0d-4e13-99ea-d6a5589786d6)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio .NET 2003 Service Pack 1  
(KB937059)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=0b10b04b-932c-4bff-9cbc-b3eeb15064b1)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Visual Studio 2005  
(KB937060)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=21073cc2-919c-40df-8ebb-aa3db06050d2)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Visual Studio 2005 Service Pack 1  
(KB937061)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=967d43c8-efba-4221-beb0-981e7deef33a)**<sup>[2]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5">
Más érintett szoftverek
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
MSN Messenger 6.2 alkalmazás Microsoft Windows 2000 Service Pack 4 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=cf49c56c-8b3e-4eae-9904-9505f47bed45&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
MSN Messenger 7.0 alkalmazás Microsoft Windows 2000 Service Pack 4 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=cf49c56c-8b3e-4eae-9904-9505f47bed45&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
MSN Messenger 6.2 alkalmazás Windows XP Service Pack 2, Windows XP Professional x64 Edition, Windows XP Professional x64 Edition Service Pack 2, Windows Server 2003 Service Pack 1, Windows Server 2003 Service Pack 2, Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition Service Pack 2, Windows Vista és Windows Vista x64 Edition rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
MSN Messenger 7.0 alkalmazás Windows XP Service Pack 2, Windows XP Professional x64 Edition, Windows XP Professional x64 Edition Service Pack 2, Windows Server 2003 Service Pack 1, Windows Server 2003 Service Pack 2, Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition Service Pack 2, Windows Vista és Windows Vista x64 Edition rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
MSN Messenger 7.5 alkalmazás Windows XP Service Pack 2, Windows XP Professional x64 Edition, Windows XP Professional x64 Edition Service Pack 2, Windows Server 2003 Service Pack 1, Windows Server 2003 Service Pack 2, Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition Service Pack 2, Windows Vista és Windows Vista x64 Edition rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Live Messenger 8.0 alkalmazás Windows XP Service Pack 2, Windows XP Professional x64 Edition, Windows XP Professional x64 Edition Service Pack 2, Windows Server 2003 Service Pack 1, Windows Server 2003 Service Pack 2, Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition Service Pack 2, Windows Vista és Windows Vista x64 Edition rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&displaylang=en)**<sup>[3]</sup>**
</td>
</tr>
</table>
 
**Megjegyzések:**

**<sup>[1]</sup>** Ehhez az operációs rendszerhez rendelkezésre áll egy biztonsági frissítés. További információt a táblázat érintett szoftverre vagy összetevőre vonatkozó részében illetve az ide vonatkozó biztonsági közleményben talál.** **

**<sup>[2]</sup>** Nem minden Visual Studio-verzió érintett. Az érintett verziókkal kapcsolatban tekintse meg a vonatkozó közleményt.** **

**<sup>[3]</sup>** A szoftverhez elérhető az MSN Messenger és a Windows Live Messenger szolgáltatás on-line frissítését lehetővé tévő opció is. További információért olvassa el a megfelelő biztonsági közleményt.

Észlelési és telepítési eszközök, útmutatás
-------------------------------------------

<span></span>
**Biztonsági központ**

A szoftveres és biztonsági frissítések kezeléséhez azokat a szervezet asztali és hordozható számítógépeire, valamint kiszolgálóira is telepíteni kell. További tájékoztatásért látogasson el a [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) weboldalára. A [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) bővebb tájékoztatással szolgál a Microsoft-termékek biztonsági funkcióival kapcsolatban. A [Biztonság otthon](http://go.microsoft.com/fwlink/?linkid=85102) weboldalon a megfelelő hivatkozásra kattintva elérhetőek a legújabb biztonsági frissítések.

A biztonsági frissítések a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) és az [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) weboldalakról tölthetőek le. A biztonsági frissítések a [Microsoft letöltőközpontjában](http://go.microsoft.com/fwlink/?linkid=21129) is elérhetőek. legegyszerűbben a „biztonsági javítás” kifejezésre irányuló kulcsszavas kereséssel találhatja meg őket. A biztonsági frissítések a Windows Update katalógusából is letölthetőek. A Windows Update katalógusról a [Microsoft Tudásbázis 323166](http://support.microsoft.com/kb/323166) számú cikkében talál információkat.

**Útmutató az észleléshez és a telepítéshez**

A Microsoft az e havi biztonsági frissítésekhez észlelési és telepítési útmutatót adott ki. Az útmutató a számítógépes szakembereknek is ötleteket adhat ahhoz, hogyan használják a különböző eszközöket, pl. Windows Update, Microsoft Update, Office Update, Microsoft Baseline Security Analyzer (MBSA), Office Detection Tool, Microsoft Systems Management Server (SMS), Extended Security Update Inventory Tool vagy Enterprise Update Scan Tool (EST) a biztonsági frissítések telepítéséhez. További információt a [Microsoft Tudásbázis 910723. számú cikkében](http://support.microsoft.com/kb/910723) talál.

**Microsoft Baseline Security Analyzer és** **Enterprise** **Update Scan Tool**

A Microsoft Baseline Security Analyzer (MBSA) segítségével a rendszergazda mind a helyi, mind a távoli számítógépeken ellenőrizheti, hogy mely biztonsági frissítések hiányoznak, illetve hogy mely biztonsági beállítások vannak helytelenül megadva. Ha többet szeretne tudni az MBSA -eszközről, látogasson el a [Microsoft Baseline Security Analyzer webhelyre](http://go.microsoft.com/fwlink/?linkid=21134).

Ha a MBSA 1.2.1 nem támogatja a különleges biztonsági frissítés észlelését, a Microsoft kiad egy külön Enterprise Update Scan Tool (EST) verziót az adott frissítéshez. Az EST-eszközről további információkat az [Enterprise UPdate Scan Tool](http://support.microsoft.com/default.aspx?id=894193) webhelyén talál.

**Megjegyzés** 2007. október 9. óta az MBSA 1.2.1 által felhasznált MSSecure.XML fájl már nem frissül. Ezután az MBSA 1.2.1 által felhasznált MSSecure.XML fájlhoz nem adódnak hozzá új biztonsági frissítések, és nem bocsátanak ki új verziót az Enterprise Scan Tool eszközből. Ha többet szeretne megtudni, látogasson el a [Microsoft Baseline Security Analyzer webhelyre](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

A Microsoft Software Update Services (WSUS) szolgáltatással a rendszergazdák gyorsan és megbízható módon telepíthetik központilag a legújabb fontos és biztonsági frissítéseket Windows 2000 és újabb operációs rendszerekhez, Office XP és újabb operációs rendszerekhez, Exchange Server 2003 és SQL Server 2000 Windows 2000 és újabb operációs rendszerekre.

A biztonsági frissítésnek Windows Server Update Services szolgáltatással történő központi telepítéséről a [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) webhelyen tudhat meg többet.

**Systems Management Server**

A Microsoft Systems Management Server (SMS) rendszer egy sokoldalúan beállítható vállalati megoldás, amely a frissítések kezelésére szolgál. Az SMS segítségével a rendszergazda megállapíthatja, hogy melyik Windows alapú számítógép szorul biztonsági frissítésre, és ezeket a frissítéseket szabályozott módon, a felhasználók minimális zavarásával központilag telepítheti a vállalat teljes informatikai környezetében. Ha többet szeretne tudni arról, hogy a rendszergazdák miként telepíthetik a biztonsági frissítéseket az SMS 2003 alkalmazással, látogasson el az [SMS 2003 Security Patch Management webhelyre](http://go.microsoft.com/fwlink/?linkid=22939). Az SMS 2.0 verzióját használók a [Software Updates Services Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) szolgáltatásait is segítségül hívhatják a biztonsági frissítések központi telepítéséhez. Az SMS-szolgáltatásról bővebben a [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158) oldalán olvashat.

**Megjegyzés:** Az SMS a Microsoft Baseline Security Analyzer és a Microsoft Office Detection Tool program segítségével széles körű támogatást nyújt a frissítések biztonsági értesítők segítségével történő észleléséhez és telepítéséhez. Előfordulhat, hogy egyes szoftverfrissítéseket ezek az eszközök nem észlelnek. Az SMS alkalmazás leltározási szolgáltatásai segítségével a rendszergazdák adott rendszereken hajthatják végre a frissítést. Az eljárással kapcsolatban olvassa el a [szoftverfrissítések telepítése az SMS szoftverelosztó ügynök segítségével](http://go.microsoft.com/fwlink/?linkid=33341) című tájékoztatót. Egyes biztonsági frissítésekhez rendszergazdai jogosultságokra van szükség a számítógép újraindítása után. A rendszergazdák az [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) és az [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) csomag részét képező Elevated Rights Deployment Tool nevű eszközzel telepíthetik ezeket a frissítéseket.

### Egyéb információ

#### A Microsoft Windows rosszindulatú szoftvereket eltávolító eszköze

A Microsoft a Windows Update, Microsoft Update, Windows Server Update Services és Letöltőközpont szolgáltatásán keresztül elérhetővé tette a Microsoft Windows rosszindulatú szoftvereket eltávolító eszközének frissített változatát.

#### Nem biztonsági jellegű, kiemelt fontosságú frissítések a MU, WU és WSUS-szolgáltatásokban

Ebben a hónapban:

-   A Microsoft a Windows Update (WU) szolgáltatáson keresztül nem adott ki **nem biztonsági jellegű**, kiemelt fontosságú Windows-frissítéseket.
-   A Microsoft a Windows Update (WU) szolgáltatáson keresztül nem adott ki **nem biztonsági jellegű**, kiemelt fontosságú Windows-frissítéseket.

Felhívjuk figyelmét, hogy a tájékoztatás **kizárólag** a biztonsági frissítéseket összegző kiadvánnyal azonos napon kiadott, **nem biztonsági jellegű**, a Microsoft Update, Windows Update, Windows Server Update Services szolgáltatásokon keresztül elérhető, kiemelt fontosságú frissítésekre vonatkozik. A más napokon kiadott, **nem biztonsági jellegű** frissítésekről tájékoztatást **nem** nyújtunk.

#### Biztonsági stratégiák és közösségek

**Frissítésekkel kapcsolatos stratégiák**

[A javítások telepítésére vonatkozó útmutatás](http://go.microsoft.com/fwlink/?linkid=21168) a Microsoft által a biztonsági frissítések telepítéséhez ajánlott legjobban bevált eljárást ismerteti.

**Egyéb biztonsági frissítések beszerzése**

Az alábbi helyekről más típusú biztonsági problémákhoz szerezhetők be frissítések.

-   A biztonsági frissítések a [Microsoft letöltőközpontban](http://go.microsoft.com/fwlink/?linkid=21129) érhetők el. legegyszerűbben a „biztonsági javítás” kifejezésre irányuló kulcsszavas kereséssel találhatja meg őket.
-   Az ügyfélrendszerek frissítései a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) oldalról elérhetőek.
-   A Windows Update szolgáltatáson keresztül terjesztett havi aktuális biztonsági frissítések a letöltőközpontból a biztonsági és kritikus frissítéseket tartalmazó ISO CD-képfájlként is letölthetőek. További információt a [Microsoft Tudásbázis 913086](http://support.microsoft.com/kb/913086) számú cikkében talál.

**IT Pro Security közösség**

Az [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) közösségben hasznos információt találhat a biztonság javításáról és az informatikai infrastruktúrák optimalizálásáról, továbbá eszmecserét folytathat a biztonsági kérdésekről más informatikai szakemberekkel.

#### Köszönetnyilvánítás

A Microsoft [köszönetét](http://go.microsoft.com/fwlink/?linkid=21127) fejezi ki a vásárlók védelmének biztosításában nyújtott segítségért az alábbi szervezet(ek)nek és szakember(ek)nek:

-   Vulnerability Research csapat, [Assurent Secure Technologies](http://www.assurent.com/) az [MS07-051](http://go.microsoft.com/fwlink/?linkid=94667) közleményben bemutatott probléma jelentéséért.
-   Yamata Li, [Palo Alto Networks](http://www.paloaltonetworks.com/), az [MS07-051](http://go.microsoft.com/fwlink/?linkid=94667) közleményben bemutatott probléma jelentéséért.
-   Az [iDefense VCP](http://labs.idefense.com/) anonim kutatója, az [MS07-051](http://go.microsoft.com/fwlink/?linkid=94667) közleményben ismertetett probléma jelentéséért.
-   Brian A. Reiter, WolfeReiter, az [MS07-053](http://go.microsoft.com/fwlink/?linkid=94467) közleményben ismertetett probléma megoldásában való közös munkavégzéséért.
-   Woo Shi, [team 509](http://www.team509.com/), az [MS07-054](http://go.microsoft.com/fwlink/?linkid=100148) közleményben ismertetett probléma jelentéséért.

#### Terméktámogatás

-   Teszteléssel állapították meg a felsorolt szoftverek egyes verzióinak érintettségét. A többi verzió támogatási életciklusa végére ért. Az egyes szoftververziók támogatási életciklusáról a [Microsoft termékek terméktámogatási életciklusát ismertető webhelyen](http://go.microsoft.com/fwlink/?linkid=21742) talál felvilágosítást.
-   Az Amerikai Egyesült Államokban és Kanadában technikai segítség igényelhető a [Microsoft terméktámogatási szolgáltatásától](http://go.microsoft.com/fwlink/?linkid=21131), amelynek telefonszáma 1-866-PCSAFETY. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek.
-   Más országokban a helyi Microsoft-képviseletek nyújtanak támogatást. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. A [nemzetközi támogatási webhely](http://go.microsoft.com/fwlink/?linkid=21155) felvilágosítást nyújt arról, támogatási kérdéseivel hogyan fordulhat a Microsofthoz.

#### Felelősséget kizáró nyilatkozat

A Microsoft Tudásbázisban leírtak előzetes bejelentés nélkül változhatnak, és a cikkek tartalmáért a Microsoft nem vállal garanciát. A Microsoft egyben elhárít minden kifejezett és értelemszerű garanciát, beleértve az eladhatóságra és az adott célra való alkalmasságra vonatkozó garanciát is. A Microsoft Corporation vagy annak szállítói semmilyen körülmények között nem tehetők felelőssé közvetlen, közvetett, eseti, ok-okozati vagy különleges kárért (beleértve az elmaradt hasznot is), még akkor sem, ha a Microsoft Corporation vagy szállítói tudatában voltak a kár lehetséges voltának. Egyes államok törvényi szabályozása nem teszi lehetővé a véletlen vagy ok-okozati károkért vállalt felelősség korlátozását vagy kizárását, így ezekben az államokban az ez a felelősségkizárás nincs érvényben.

#### Verziók

-   1.0 verzió (2007. szeptember 11.): Összefoglaló közlemény közzététele.
-   1.1 verzió (2007. szeptember 12.): Az MS07-054 közlemény vonatkozásában módosultak az újraindítási követelmények, valamint letöltési hivatkozások hozzáadására is sor került.

*Built at 2014-04-18T01:50:00Z-07:00*
