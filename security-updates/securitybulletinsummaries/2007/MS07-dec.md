---
TOCTitle: 'MS07-DEC'
Title: 'Microsoft biztonsági közlemény - összefoglalás, december 2007'
ms:assetid: 'ms07-dec'
ms:contentKeyID: 61227706
ms:mtpsurl: 'https://technet.microsoft.com/hu-HU/library/ms07-dec(v=Security.10)'
author: SharonSears
ms.author: SharonSears
---

Security Bulletin Summary

Microsoft biztonsági közlemény - összefoglalás, december 2007
=============================================================

Közzétéve: 2007. december 11. | Frissítve: 2008. július 16.

**Verzió:** 2.0

Az összefoglaló a 2007 decemberében kiadott biztonsági közleményeket összegzi.

A 2007. decemberi közlemények kiadása folytán az összefoglaló a 2007. december 6-án kiadott előzetes értesítés helyébe lép. További információk a biztonsági közlemények kiadásáról szóló előzetes értesítés szolgáltatásról lásd: [Előzetes értesítés a Microsoft biztonsági közleményeinek kiadásáról](http://technet.microsoft.com/security/bulletin/advance).

Ha automatikus értesítést szeretne kapni a Microsoft biztonsági közleményeinek megjelenéséről, fizessen elő a [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) szolgáltatásra.

A közleményekkel kapcsolatos kérdések megválaszolására a Microsoft 2007. december 12-én, csendes-óceáni idő szerint 11 órakor webes szemináriumot tart. [Jelentkezzen most a decemberi közleményeket bemutató webes szemináriumra](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344696&eventcategory=4&culture=en-us&countrycode=us). Ezt követően a webes szeminárium igény szerint kerül megrendezésre. További információkért látogasson el a [Microsoft biztonsági közleményeit és a webes szemináriumokat](http://technet.microsoft.com/security/bulletin/summary)bemutató oldalra.

A Microsoft abban is segítséget nyújt felhasználóinak, hogy a havi biztonsági közleményekkel azonos napon kiadott, nem biztonsági jellegű, de fontos frissítéseket megfelelően rangsorolhassák. Lásd az **Egyéb információ című részt**.

### A közleménnyel kapcsolatos információk

#### Összefoglalások

Az e havi biztonsági közlemények súlyossági sorrendben:

Kritikus (3)
------------

<span></span>

| Közlemény azonosítója                          | A Microsoft MS07-064 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**A DirectX távolról történő programkódfuttatást lehetővé tévő biztonsági rései (941568)**](http://go.microsoft.com/fwlink/?linkid=104988)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Összefoglalás**                              | Ez a kritikus besorolású frissítés a Microsoft DirectX két közvetlenül jelzett biztonsági rését szüntet meg. A biztonsági rések kódfuttatást tesznek lehetővé, ha a felhasználó a DirectX médiafolyamához használt, speciálisan létrehozott fájlt nyit meg. Ha valamely felhasználó felügyeleti jogosultságokkal bejelentkezett a rendszerbe, akkor a biztonsági rést kihasználó támadó teljes mértékben átveheti az irányítást a számítógép felett, Ezt követően a támadó programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén |
| **Súlyosság maximális foka**                   | [Kritikus](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **A biztonsági rés hatása**                    | Távoli kódfuttatás                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. A frissítés különleges eseteket kivéve nem teszi szükségessé a rendszer újraindítását.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Érintett szoftverek**                        | **Windows, DirectX, DirectShow.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |

| Közlemény azonosítója                          | A Microsoft MS07-068 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                                                                        |
|------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**A Windows Media fájlformátum távoli kódfuttatást lehetővé tévő biztonsági rése (941569 és 944275)**](http://go.microsoft.com/fwlink/?linkid=99075)                                                                                                                                                                                                                                                                                                   |
| **Összefoglalás**                              | A kritikus besorolású biztonsági frissítés a Windows Media Format közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rés távoli kódvégrehajtást tehet lehetővé, amennyiben a felhasználó egy különlegesen kialakított Microsoft Media Format Runtime fájlt tekintett meg. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén |
| **Súlyosság maximális foka**                   | [Kritikus](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                |
| **A biztonsági rés hatása**                    | Távoli kódfuttatás                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. A frissítés különleges eseteket kivéve nem teszi szükségessé a rendszer újraindítását.                                                                                                                                                                                                                                                           |
| **Érintett szoftverek**                        | **Windows, Windows Media Format Runtime.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                                          |

| Közlemény azonosítója                          | A Microsoft MS07-069 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                                                                                      |
|------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**Összesítő biztonsági frissítés az Internet Explorerhez (942615)**](http://go.microsoft.com/fwlink/?linkid=101160)                                                                                                                                                                                                                                                                                                                                                  |
| **Összefoglalás**                              | Ez a kritikus besorolású frissítés négy közvetlenül jelzett biztonsági rést szüntet meg. A biztonsági szempontból legsúlyosabb következmény a távoli kódfuttatás lehet, mely akkor következik be, ha a felhasználó megtekint egy speciálisan létrehozott weboldalt az Internet Explorer alkalmazásban. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén |
| **Súlyosság maximális foka**                   | [Kritikus](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                              |
| **A biztonsági rés hatása**                    | Távoli kódfuttatás                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. A frissítés a rendszer újraindítását igényli.                                                                                                                                                                                                                                                                                                                  |
| **Érintett szoftverek**                        | **Windows, Internet Explorer.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                                                                   |

Fontos (4)
----------

<span></span>

| Közlemény azonosítója                          | A Microsoft MS07-063 számú biztonsági közleménye                                                                                                                                                                                                                                                                                          |
|------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**Az SMBv2 távoli kódfuttatást lehetővé tévő biztonsági rése (942624)**](http://go.microsoft.com/fwlink/?linkid=104920)                                                                                                                                                                                                                  |
| **Összefoglalás**                              | A fontos besorolású biztonsági frissítés a kiszolgáló üzenetblokk 2. verziója (SMBv2) közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rés miatt a támadók hozzáférhetnek az SMBv2-n keresztül átvitt adatokhoz, ezáltal távoli kódfuttatásra nyílik alkalmuk az SMBv2-n keresztül kommunikáló tartománykonfigurációkon. |
| **Súlyosság maximális foka**                   | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                    |
| **A biztonsági rés hatása**                    | Távoli kódfuttatás                                                                                                                                                                                                                                                                                                                        |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. A frissítés a rendszer újraindítását igényli.                                                                                                                                                                                      |
| **Érintett szoftverek**                        | **Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                          |

| Közlemény azonosítója                          | A Microsoft MS07-065 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**Az Üzenetsor-kezelés szolgáltatás távoli kódfuttatást lehetővé tévő biztonsági rése (937894)**](http://go.microsoft.com/fwlink/?linkid=94666)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Összefoglalás**                              | Ez a fontos besorolású biztonsági frissítés az Üzenetsor-kezelés (MSMQ) szolgáltatás közvetlenül jelentett, a Microsoft Windows 2000 rendszeren távoli kódfuttatást, Microsoft Windows 2000 Professional és Windows XP rendszeren pedig jogok kiterjesztését okozó biztonsági rését szünteti meg. Microsoft Windows 2000 Professional és Windows XP rendszeren a támadónak a jogok kiterjesztését lehetővé tévő biztonsági rés kihasználásához érvényes bejelentkezési adatokkal kell rendelkeznie. Ezt követően programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de új fiókokat is létrehozhat. |
| **Súlyosság maximális foka**                   | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **A biztonsági rés hatása**                    | Távoli kódfuttatás                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. A frissítés a rendszer újraindítását igényli.                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Érintett szoftverek**                        | **Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |

| Közlemény azonosítója                          | A Microsoft MS07-066 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                     |
|------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**A Windows kernel jogok kiterjesztését lehetővé tévő biztonsági rése (943078)**](http://go.microsoft.com/fwlink/?linkid=104898)                                                                                                                                                                                                                                                                    |
| **Összefoglalás**                              | Ez a fontos besorolású biztonsági frissítés a Windows kernel közvetlenül jelentett biztonsági rését szünteti meg. Ha egy támadó kihasználja a biztonsági rést, teljes mértékben átveheti a rendszer irányítását. Ezt követően a támadó programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. |
| **Súlyosság maximális foka**                   | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                               |
| **A biztonsági rés hatása**                    | Jogok kiterjesztése                                                                                                                                                                                                                                                                                                                                                                                  |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. A frissítés a rendszer újraindítását igényli.                                                                                                                                                                                                                                                 |
| **Érintett szoftverek**                        | **Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                     |

| Közlemény azonosítója                          | A Microsoft MS07-067 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**A Macrovision illesztőprogramnak a helyi jogok illetéktelen kiterjesztését okozó biztonsági rése (944653)**](http://go.microsoft.com/fwlink/?linkid=104987)                                                                                                                                                                                                                                                                                                                                                                 |
| **Összefoglalás**                              | Ez a fontos besorolású frissítés egy nyilvánosan jelentett biztonsági rést szüntet meg. A helyi jogok illetéktelen kiterjesztését okozó biztonsági rést a konfigurációs paraméterek hibás kezelése okozza a Macrovision illesztőprogramban. A biztonsági rést sikeresen kihasználó helyi támadó átveheti az érintett rendszer irányítását. Ezt követően a támadó programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. |
| **Súlyosság maximális foka**                   | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **A biztonsági rés hatása**                    | Jogok helyi kiterjesztése                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. A frissítés a rendszer újraindítását igényli.                                                                                                                                                                                                                                                                                                                                                                           |
| **Érintett szoftverek**                        | **Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                                                                                                                                               |

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
[**MS07-063**](http://go.microsoft.com/fwlink/?linkid=104920)
</td>
<td style="border:1px solid black;">
[**MS07-064**](http://go.microsoft.com/fwlink/?linkid=104988)
</td>
<td style="border:1px solid black;">
[**MS07-065**](http://go.microsoft.com/fwlink/?linkid=94666)
</td>
<td style="border:1px solid black;">
[**MS07-066**](http://go.microsoft.com/fwlink/?linkid=104898)
</td>
<td style="border:1px solid black;">
[**MS07-067**](http://go.microsoft.com/fwlink/?linkid=104987)
</td>
<td style="border:1px solid black;">
[**MS07-068**](http://go.microsoft.com/fwlink/?linkid=99075)
</td>
<td style="border:1px solid black;">
[**MS07-069**](http://go.microsoft.com/fwlink/?linkid=101160)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Súlyosság maximális foka**
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
<td style="border:1px solid black;">
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<th colspan="8">
Windows operációs rendszer:
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Server Service Pack 4 és Microsoft Windows 2000 Professional Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=bda9d0b4-f7cb-4d9d-b030-043d7437734b)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Mérsékelt.](http://www.microsoft.com/downloads/details.aspx?familyid=09d4e6ae-5d19-4f11-bb7e-60cee8263bc8)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=c7d368d0-f7bf-4946-a4a6-3e88315e5317)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=5f4fa8e9-fcf2-4daf-93c0-8bb267da69aa)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=5f4fa8e9-fcf2-4daf-93c0-8bb267da69aa)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=0f84f5e2-1dd8-4882-b796-444ab70b6b02)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=0f84f5e2-1dd8-4882-b796-444ab70b6b02)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=1f416b71-783f-4cbc-9b85-9a9be7daa0d7)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=1f416b71-783f-4cbc-9b85-9a9be7daa0d7)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=9d22a9ee-cc08-4b2d-af4e-55d326f82761)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=9787619f-1297-411e-8b9c-3ad3e6a99797)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=05a9501c-4da3-4fa1-901e-99cb262e5e36)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=5f382050-8df6-43aa-82e9-8fad5ff8ecec)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<th colspan="8">
A Windows operációs rendszer érintett összetevői
</th>
</tr>
<tr>
<td style="border:1px solid black;">
DirectX 7.0 Microsoft Windows 2000 Service Pack 4 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=06196774-5a11-4525-b53c-8cb000738949)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
DirectX 8.1 Microsoft Windows 2000 Service Pack 4 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=ccb872bd-fc06-4a3f-ac70-3c9a42d57b37)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
DirectX 9.0\* Microsoft Windows 2000 Service Pack 4 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=03b14ce0-5189-4803-8151-6ac5cb6a9179)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
DirectX 9.0\* Windows XP Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=04a8f8d3-69f9-4445-baab-f45616a6b9b7)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
DirectX 9.0\* alkalmazás Windows XP Professional x64 Edition és Windows XP Professional x64 Edition Service Pack 2 rendszereken
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=f096c500-e765-4e75-8443-7ffec4ddf149)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
DirectX 9.0\* Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=d80a295a-baf9-4981-8a28-1b4207ecc5f7)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
DirectX 9.0\* Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=378086ea-60b8-409f-970a-fcfd62025150)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
DirectX 9.0\* Windows Server 2003 SP1 szervizcsomaggal ellátott Itanium alapú rendszeren és Windows Server 2003 SP2 csomaggal ellátott Itanium alapú rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=2e6ea4bb-9f4f-46fb-9d51-e20b15e61a89)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
DirectX 10.0 Windows Vista rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=bfa571bc-e43f-45e3-bc98-4086985c99aa)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
DirectX 10.0 Windows Vista x64 Edition rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=3d8803da-108b-4b9d-a039-84932dce8e42)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 5.01 Service Pack 4 alkalmazás Microsoft Windows 2000 Service Pack 4 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=b3bd16ea-5d69-4ae3-84b3-ab773052ceeb)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 6 Service Pack 1, Microsoft Windows 2000 Service Pack 4 rendszerre telepítve
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=bc8edf05-262a-4d1d-b196-4fc1a844970c)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 6 Windows XP Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=6e4ebafc-34c3-4dc7-b712-152c611d3f0a)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 6 alkalmazás Windows XP Professional x64 Edition és Windows XP Professional x64 Edition Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=f5a5af23-30fb-4e47-94bd-3b05b55c92f2)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 6 alkalmazás Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2 rendszerhez:
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Mérsékelt.](http://www.microsoft.com/downloads/details.aspx?familyid=bf466060-a585-4c2e-a48d-70e080c3bbe7)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 6 Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Mérsékelt.](http://www.microsoft.com/downloads/details.aspx?familyid=074697f2-18c8-4521-bbf7-1d0e7395d27d)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 6 Windows Server 2003 SP1 javítócsomaggal ellátott Itanium-alapú rendszerekhez és Windows Server 2003 SP2 csomaggal ellátott Itanium-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Mérsékelt.](http://www.microsoft.com/downloads/details.aspx?familyid=b3f390a6-0361-4553-b627-5e7ad6bf5055)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 Windows XP Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=b15a6506-02dd-43c2-aef4-e10c1c76ee97)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 7 alkalmazás Windows XP Professional x64 Edition és Windows XP Professional x64 Edition Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=c092a6bb-8e62-4d90-bdb1-5f3a15968f75)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 alkalmazás Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Mérsékelt.](http://www.microsoft.com/downloads/details.aspx?familyid=34759c10-16a5-42a2-974d-9d532fb5a0a7)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 7 Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Mérsékelt.](http://www.microsoft.com/downloads/details.aspx?familyid=7dccce5a-7562-448b-a345-cf1cc758e35c)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 Windows Server 2003 SP1 javítócsomaggal ellátott Itanium-alapú rendszerekhez és Windows Server 2003 SP2 csomaggal ellátott Itanium-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Mérsékelt.](http://www.microsoft.com/downloads/details.aspx?familyid=8414f3fb-216a-4d46-b590-4c1f304dff91)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 7 alkalmazás a Windows Vista rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=26d303da-bb2e-4555-96f1-becb0e277341)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 alkalmazás Windows Vista x64 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=c5e88e0b-a4c2-4690-91d9-326800030a16)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 rendszerre telepített Windows Media Format Runtime 7.1 esetén (KB941569)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=eecdf2ce-9aa7-4f0c-b62b-2fa7a32f369e)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4 rendszerre telepített Windows Media Format Runtime 9 esetén (KB941569)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=eecdf2ce-9aa7-4f0c-b62b-2fa7a32f369e)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 2 rendszerre telepített Windows Media Format Runtime 9 esetén (KB941569)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=bece702a-6e61-433e-8275-20f4e84f2c92)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 rendszerre telepített Windows Media Format Runtime 9.5 esetén (KB941569)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=bece702a-6e61-433e-8275-20f4e84f2c92)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition és Windows XP Professional x64 Edition Service Pack 2 rendszerre telepített Windows Media Format Runtime 9.5 esetén (KB941569)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=81f20b45-dfc7-4ddf-a4b4-6c0e9476ed51)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2 rendszerre telepített Windows Media Format Runtime 9.5 esetén (KB941569)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=8fea7da8-a7f3-4786-97c2-fb5ea7018159)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2 rendszerre telepített Windows Media Format Runtime 9.5 esetén (KB941569)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=ffc69c76-02f1-4b15-8ec1-dab8c7e33bd4)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2 rendszerre telepített Windows Media Format Runtime 9.5 x64 Edition esetén (KB941569)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=ffc69c76-02f1-4b15-8ec1-dab8c7e33bd4)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition és Windows XP Professional x64 Edition Service Pack 2 rendszerre telepített Windows Media Format Runtime 9.5 x64 Edition esetén (KB941569)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=72d2ca0e-da81-45ee-9321-4970b80f4a5a)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 rendszerre telepített Windows Media Format Runtime 11 esetén (KB941569)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=bece702a-6e61-433e-8275-20f4e84f2c92)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition és Windows XP Professional x64 Edition Service Pack 2 rendszerre telepített Windows Media Format Runtime 11 esetén (KB941569)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=1037b224-ac89-4efd-b189-6f3da77a88e6)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista rendszerre telepített Windows Media Format Runtime 11 esetén (KB941569)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=9a98ef96-bc2e-42b7-9a24-c82c8fb379db)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition rendszerre telepített Windows Media Format Runtime 11 esetén (KB941569)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=3ce02c95-d695-4f14-9fb3-30c83a9cfb9c)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2 rendszerre telepített Windows Media Services 9.1 esetén (KB944275)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=096711d4-ce01-45d0-9c2d-ebfa5c671b9f)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2 rendszerre telepített Windows Media Services 9.1 x64 Edition esetén (KB944275)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=23c23800-5aaa-455b-96bf-4ead4dfdd95d)
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>
 
**Megjegyzések:**

**<sup>[1]</sup>** Ehhez az operációs rendszerhez rendelkezésre áll egy biztonsági frissítés. További információt a táblázat érintett szoftverre vagy összetevőre vonatkozó részében illetve az ide vonatkozó biztonsági közleményben talál.

\* A DirectX 9.0a, DirectX 9.0b és DirectX 9.0c verziót is tartalmazza

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

**Megjegyzés** 2007. október 9. óta az MBSA 1.2.1 által felhasznált MSSecure.XML fájl már nem frissül. Ezután az MBSA 1.2.1 által felhasznált MSSecure.XML fájlhoz nem adódnak hozzá új biztonsági frissítések, és nem bocsátanak ki új verziót az Enterprise Scan Tool eszközből. Ez nincs hatással a Security Update Inventory Tool (SUIT) vagy az Extended Security Update Inventory Tool (ESUIT) for SMS 2.0 és SMS 2003 eszközökre. További információt a [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) webhelyen talál.

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

-   A Microsoft három **nem biztonsági jellegű**, kiemelt fontosságú frissítést, valamint egy 2007 Microsoft Office Service Pack 1 szervizcsomagot adott ki a Microsoft Update (MU) és Windows Server Update Services (WSUS) szolgáltatáson keresztül.
-   A Microsoft három **nem biztonsági jellegű**, kiemelt fontosságú frissítést adott ki a Windows és a Windows SharePoint Services 3.0 Service Pack 1 rendszerhez a Windows Update (WU) és WSUS-szolgáltatáson keresztül.

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

-   Jun Mao, [VeriSign iDefense Labs](http://labs.idefense.com/), az MS07-064 közleményben ismertetett probléma megoldásában való közreműködésért
-   Peter Winter Smith, [NGSSoftware](http://www.ngssoftware.com/), az MS07-064 közleményben ismertetett probléma megoldásában való közreműködésért
-   Jung-hyung Lee, [AhnLab](http://global.ahnlab.com/), az MS07-064 közleményben ismertetett, a DirectX alkalmazásra vonatkozó, lényeges biztonsági módosítások kidolgozásában való közreműködésért
-   [Zero Day Initiative](http://www.zerodayinitiative.com/), az MS07-065 közleményben ismertetett probléma megoldásában való közreműködésért
-   Venustech, [ADLABS](http://www.venustech.com.cn/), az MS07-065 közleményben ismertetett probléma megoldásában való közreműködésért
-   Thomas Garnier, [SkyRecon](http://www.skyrecon.com/), az MS07-066 közleményben ismertetett probléma jelentéséért
-   Ryan Smith, [ISS X-Force](http://xforce.iss.net/), az MS07-068 közleményben ismertetett probléma megoldásában való közreműködésért
-   Alex Wheeler, [ISS X-Force](http://xforce.iss.net/), az MS07-068 közleményben ismertetett probléma megoldásában való közreműködésért
-   Peter Vreugdenhil, [iDefense VCP,](http://idefense.com/) az MS07-069 közleményben ismertetett probléma jelentéséért
-   A [TippingPoint](http://www.tippingpoint.com/) és [Zero Day Initiative](http://www.zerodayinitiative.com/) cégekkel együttműködő anonim kutató, az MS07-069 közleményben leírt probléma jelentéséért
-   Sam Thomas, a [TippingPoint](http://www.tippingpoint.com/) és [Zero Day Initiative](http://www.zerodayinitiative.com/) munkatársa, az MS07-069 közleményben leírt probléma jelentéséért
-   Peter Vreugdenhil, a [TippingPoint](http://www.tippingpoint.com/) és [Zero Day Initiative](http://www.zerodayinitiative.com/) munkatársa, az MS07-069 közleményben leírt probléma jelentéséért

#### Terméktámogatás

-   Teszteléssel állapították meg a felsorolt szoftverek egyes verzióinak érintettségét. A többi verzió támogatási életciklusa végére ért. Az egyes szoftververziók támogatási életciklusáról a [Microsoft termékek terméktámogatási életciklusát ismertető webhelyen](http://go.microsoft.com/fwlink/?linkid=21742) talál felvilágosítást.
-   Az Amerikai Egyesült Államokban és Kanadában technikai segítség igényelhető a [Microsoft terméktámogatási szolgáltatásától](http://go.microsoft.com/fwlink/?linkid=21131), amelynek telefonszáma 1-866-PCSAFETY. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek.
-   Más országokban a helyi Microsoft-képviseletek nyújtanak támogatást. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. A [nemzetközi támogatási webhely](http://go.microsoft.com/fwlink/?linkid=21155) felvilágosítást nyújt arról, támogatási kérdéseivel hogyan fordulhat a Microsofthoz.

#### Felelősséget kizáró nyilatkozat

A Microsoft Tudásbázisban leírtak előzetes bejelentés nélkül változhatnak, és a cikkek tartalmáért a Microsoft nem vállal garanciát. A Microsoft egyben elhárít minden kifejezett és értelemszerű garanciát, beleértve az eladhatóságra és az adott célra való alkalmasságra vonatkozó garanciát is. A Microsoft Corporation vagy annak szállítói semmilyen körülmények között nem tehetők felelőssé közvetlen, közvetett, eseti, ok-okozati vagy különleges kárért (beleértve az elmaradt hasznot is), még akkor sem, ha a Microsoft Corporation vagy szállítói tudatában voltak a kár lehetséges voltának. Egyes államok törvényi szabályozása nem teszi lehetővé a véletlen vagy ok-okozati károkért vállalt felelősség korlátozását vagy kizárását, így ezekben az államokban az ez a felelősségkizárás nincs érvényben.

#### Verziók

-   1.0 verzió (2007. december 11.): Összefoglaló közlemény közzététele.
-   1.1 verzió (2007. december 12.): A frissített közlemény tartalmazza az MS07-065 és MS-07-067 összesítő közleményeiben eszközölt módosításokat.
-   1.2 verzió (2008. január 23.): A frissített közlemény tartalmazza az MS07-064 közlemény érintett szoftverének módosításait.
-   2.0 verzió (2008. július 16.): A frissített közlemény tartalmazza az MS07-064 közlemény érintett szoftverének módosításait.

*Built at 2014-04-18T01:50:00Z-07:00*
