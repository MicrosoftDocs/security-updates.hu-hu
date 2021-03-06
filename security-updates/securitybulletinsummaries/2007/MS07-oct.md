---
TOCTitle: 'MS07-OCT'
Title: 'Microsoft biztonsági közlemény - összefoglalás, október 2007'
ms:assetid: 'ms07-oct'
ms:contentKeyID: 61227714
ms:mtpsurl: 'https://technet.microsoft.com/hu-HU/library/ms07-oct(v=Security.10)'
author: SharonSears
ms.author: SharonSears
---

Security Bulletin Summary

Microsoft biztonsági közlemény - összefoglalás, október 2007
============================================================

Közzétéve: 2007. október 9.

**Verzió:** 1.0

Az összefoglaló a 2007 októberében kiadott biztonsági közleményeket összegzi.

A 2007. októberi közlemények kiadása folytán az összefoglaló a 2007. október 4-én kiadott előzetes értesítés helyébe lép. További információk a biztonsági közlemények kiadásáról szóló előzetes értesítés szolgáltatásról lásd: [Előzetes értesítés a Microsoft biztonsági közleményeinek kiadásáról](http://technet.microsoft.com/security/bulletin/advance).

Ha automatikus értesítést szeretne kapni a Microsoft biztonsági közleményeinek megjelenéséről, fizessen elő a [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) szolgáltatásra.

A közleményekkel kapcsolatos kérdések megválaszolására a Microsoft 2007. október 10-én, csendes-óceáni idő szerint 11 órakor webes szemináriumot tart. [Jelentkezzen most az októberi közleményeket bemutató webes szemináriumra](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344692&eventcategory=4&culture=en-us&countrycode=us). Ezt követően a webszeminárium igény szerint kerül megrendezésre. További információkért látogasson el a [Microsoft biztonsági közleményeit és a webes szemináriumokat](http://technet.microsoft.com/security/bulletin/summary)bemutató oldalra.

A Microsoft abban is segítséget nyújt felhasználóinak, hogy a havi biztonsági közleményekkel azonos napon kiadott, nem biztonsági jellegű, de fontos frissítéseket megfelelően rangsorolhassák. Lásd az **Egyéb információ című részt**.

### A közleménnyel kapcsolatos információk

#### Összefoglalások

Az e havi biztonsági közlemények súlyossági sorrendben:

Kritikus (4)
------------

<span></span>
| Közlemény azonosítója                          | A Microsoft MS07-055 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**A Kodak Image Viewer alkalmazás távoli kódfuttatatást lehetővé tévő biztonsági rése (923810)**](http://go.microsoft.com/fwlink/?linkid=94668)                                                                                                                                                                                                                                                                                                                                                                          |
| **Összefoglalás**                              | Ez a kritikus besorolású frissítés egy közvetlenül jelzett biztonsági rést szüntet meg. A Kodak Image Viewer alkalmazás (korábbi nevén Wang Image Viewer) távoli kódfuttatást lehetővé tévő biztonsági rését a speciálisan létrehozott képfájlok kezelési módja okozza. A biztonsági rés az érintett rendszerben távoli programkódfuttatást tesz lehetővé. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén |
| **Súlyosság maximális foka**                   | [Kritikus](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **A biztonsági rés hatása**                    | Távoli kódfuttatás                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. A frissítés a rendszer újraindítását igényli.                                                                                                                                                                                                                                                                                                                                                                      |
| **Érintett szoftverek**                        | **Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                                                                                                                                          |

| Közlemény azonosítója                          | A Microsoft MS07-056 számú biztonsági közleménye                                                                                                                                                                                                                                               |
|------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**Biztonsági frissítés az Outlook Express és a Windows Mail programhoz (941202)**](http://go.microsoft.com/fwlink/?linkid=96629)                                                                                                                                                              |
| **Összefoglalás**                              | Ez a kritikus besorolású biztonsági frissítés egy közvetlenül jelzett biztonsági rést szüntet meg. A biztonsági rés hibás NNTP-válasz helytelen kezelése miatt távoli kódfuttatásra ad lehetőséget. A támadó a biztonsági rés kihasználásához különlegesen kialakított weboldalt hozhat létre. |
| **Súlyosság maximális foka**                   | [Kritikus](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                       |
| **A biztonsági rés hatása**                    | Távoli kódfuttatás                                                                                                                                                                                                                                                                             |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer és az Enterprise Update Scan Tool észleli, szükség van-e a számítógépen az adott frissítésre. A frissítés különleges eseteket és a Windows Vista rendszert kivéve nem teszi szükségessé a rendszer újraindítását.                                       |
| **Érintett szoftverek**                        | **Windows, Outlook Express, Windows Mail.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                |

| Közlemény azonosítója                          | A Microsoft MS07-057 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**Összesítő biztonsági frissítés az Internet Explorerhez (939653)**](http://go.microsoft.com/fwlink/?linkid=95045)                                                                                                                                                                                                                                                                                                                                                                                        |
| **Összefoglalás**                              | Ez a kritikus besorolású biztonsági frissítés három közvetlenül jelentett, és egy nyilvánosan jelentett biztonsági rést szüntet meg. A biztonsági rés legsúlyosabb következménye a távoli kódfuttatás lehet, mely akkor következik be, ha a felhasználó megtekint egy speciálisan létrehozott weboldalt az Internet Explorer alkalmazásban. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén |
| **Súlyosság maximális foka**                   | [Kritikus](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **A biztonsági rés hatása**                    | Távoli kódfuttatás                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. A frissítés a rendszer újraindítását igényli.                                                                                                                                                                                                                                                                                                                                                       |
| **Érintett szoftverek**                        | **Windows, Internet Explorer.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                                                                                                        |

| Közlemény azonosítója                          | A Microsoft MS07-060 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                                               |
|------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**A Microsoft Word távoli kódfuttatást lehetővé tévő biztonsági rése (942695)**](http://go.microsoft.com/fwlink/?linkid=101656)                                                                                                                                                                                                                                                                                               |
| **Összefoglalás**                              | A biztonsági frissítés a Microsoft Word egy, közvetlenül a Microsoftnak jelzett biztonsági rését szünteti meg, mely távoli kódfuttatást tesz lehetővé amennyiben a felhasználó megnyit egy speciálisan létrehozott, hibás karakterláncot tartalmazó Word fájlt. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén |
| **Súlyosság maximális foka**                   | [Kritikus](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                       |
| **A biztonsági rés hatása**                    | Távoli kódfuttatás                                                                                                                                                                                                                                                                                                                                                                                                             |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. A frissítés nem teszi szükségessé a számítógép újraindítását.                                                                                                                                                                                                                                                           |
| **Érintett szoftverek**                        | **Office.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                                                |

Fontos (2)
----------

<span></span>
| Közlemény azonosítója                          | A Microsoft MS07-058 számú biztonsági közleménye                                                                                                                                                                                                                                    |
|------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**Az RPC szolgáltatásmegtagadást okozó biztonsági rése (933729)**](http://go.microsoft.com/fwlink/?linkid=91031)                                                                                                                                                                   |
| **Összefoglalás**                              | Ez a fontos besorolású frissítés egy közvetlenül jelzett biztonsági rést szüntet meg. A szolgáltatásmegtagadást lehetővé tévő biztonsági rést a távoli eljáráshívás (RPC) okozza, mivel nem képes kommunikálni az NTLM biztonsági szolgáltatóval az RPC-kérések hitelesítése során. |
| **Súlyosság maximális foka**                   | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                              |
| **A biztonsági rés hatása**                    | Szolgáltatásmegtagadás                                                                                                                                                                                                                                                              |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. A frissítés a rendszer újraindítását igényli.                                                                                                                                |
| **Érintett szoftverek**                        | **Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                    |

| Közlemény azonosítója                          | A Microsoft MS07-059 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**A Windows SharePoint Services 3.0 és a Office SharePoint Server 2007 biztonsági rése jogok kiterjesztését okozhatja a SharePoint webhelyen (942017)**](http://go.microsoft.com/fwlink/?linkid=95631)                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Összefoglalás**                              | A biztonsági közlemény a Microsoft Windows SharePoint Services 3.0 és a Microsoft Office SharePoint Server 2007 egy nyilvánosan jelentett biztonsági rését szünteti meg. A biztonsági rést sikeresen kihasználó támadó olyan tetszőleges parancsfájlt futtathat, mely jogosultság illetéktelen megszerzését okozhatja a SharePoint webhelyen (nem pedig a munkaállomáson vagy a kiszolgáló környezetében). A biztonsági rés egyben lehetőséget nyújt a támadónak olyan tetszőleges parancsfájl futtatására, mely módosítja a felhasználó gyorsítótárát, ezáltal információk kiszivárgását okozza a munkaállomásról. |
| **Súlyosság maximális foka**                   | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **A biztonsági rés hatása**                    | Jogok kiterjesztése                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. A frissítés különleges eseteket kivéve nem teszi szükségessé a rendszer újraindítását.                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Érintett szoftverek**                        | **Windows, Office.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |

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
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS07-055**](http://go.microsoft.com/fwlink/?linkid=94668)
</td>
<td style="border:1px solid black;">
[**MS07-056**](http://go.microsoft.com/fwlink/?linkid=96629)
</td>
<td style="border:1px solid black;">
[**MS07-057**](http://go.microsoft.com/fwlink/?linkid=95045)
</td>
<td style="border:1px solid black;">
[**MS07-060**](http://go.microsoft.com/fwlink/?linkid=101656)
</td>
<td style="border:1px solid black;">
[**MS07-058**](http://go.microsoft.com/fwlink/?linkid=91031)
</td>
<td style="border:1px solid black;">
[**MS07-059**](http://go.microsoft.com/fwlink/?linkid=95631)
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
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<th colspan="7">
Windows operációs rendszer:
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=29763117-c2dc-4746-b31e-0b27350118e6)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Alacsony](http://www.microsoft.com/downloads/details.aspx?familyid=6c7fb9a8-1d8d-4307-b5c6-bc6c28ee09de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=be52f740-e9c9-4228-95c0-00995213bbd0)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=1fee539c-ab86-4298-b6f4-22ce31ee7b8b)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
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
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=ac7bd100-0a03-426b-adc8-0516c602a280)
</td>
<td style="border:1px solid black;">
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=ac7bd100-0a03-426b-adc8-0516c602a280)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=9a5c9e5d-4908-48bf-9346-745b4c6f6d4e)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=011593a0-f37e-4578-bee1-a985639b521b)
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
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=9a5c9e5d-4908-48bf-9346-745b4c6f6d4e)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=011593a0-f37e-4578-bee1-a985639b521b)
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=e9bb8df5-f39e-4473-9d0c-e84430c7f859)
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=e9bb8df5-f39e-4473-9d0c-e84430c7f859)
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1 csomaggal felszerelt Itanium alapú rendszerekhez
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=492ae87c-047c-45c1-ad04-ee36352de85b)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 Itanium alapú rendszerekhez
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=492ae87c-047c-45c1-ad04-ee36352de85b)
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=ceca7f8c-7b56-48fc-8c17-87ffadf25629)
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
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=7625f5a4-2921-41ce-986d-4cc0c264135c)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="7">
A Windows operációs rendszer érintett összetevői
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Outlook Express 5.5 Service Pack 2 Micorosoft Windows 2000 Service Pack 4 rendszerhez
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=5aa009c9-4edc-4f34-989b-0493549649e8)
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
Outlook Express 6 Service Pack 1, Microsoft Windows 2000 Service Pack 4 rendszerre telepítve
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=b537115d-611c-4486-960c-08d2df450579)
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
Outlook Express 6 Windows XP Service Pack 2 rendszerhez
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=3ed7f466-78c7-4251-ba24-8ae71ad54e18)
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
Outlook Express 6 alkalmazás Windows XP Professional x64 Edition Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=6468a552-2194-4866-97d5-ff77ae205eea)
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
Outlook Express 6 alkalmazás Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=708926e4-f8af-4533-8747-22d6536ebd66)
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
Outlook Express 6 alkalmazás Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=26720f5a-d7e9-44b9-9330-2e9faa4af0d9)
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
Outlook Explorer 6 alkalmazás Windows Server 2003 SP1 javítócsomaggal ellátott Itanium-alapú rendszeren és Windows Server 2003 SP2 csomaggal ellátott Itanium-alapú rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=a8844fbb-5b2c-41f3-80f1-dce563aa7cb7)
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
Windows Vista rendszerben működő Windows Mail
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=b6ac8d93-adc3-4ec3-bad1-4990bd7d52b4)
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
Windows Vista x64 Edition rendszerben működő Windows Mail
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=34aaf9dd-4d63-43e2-b631-bbf492d56a26)
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
Internet Explorer 5.01 Service Pack 4 alkalmazás Microsoft Windows 2000 Service Pack 4 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=95827f3f-a984-4e34-a949-d16a0614121a)
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
Internet Explorer 6 Service Pack 1, Microsoft Windows 2000 Service Pack 4 rendszerre telepítve
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=df3ba596-7c5b-4151-9884-6957aa884aab)
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
Internet Explorer 6 Windows XP Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=513a8320-6d36-4fc9-a38a-867192b55b53)
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
Internet Explorer 6 alkalmazás Windows XP Professional x64 Edition és Windows XP Professional x64 Edition Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=ae8a26d8-1910-4b8c-8a73-6e2fa6b5b29f)
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
Internet Explorer 6 alkalmazás Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2 rendszerhez:
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Mérsékelt.](http://www.microsoft.com/downloads/details.aspx?familyid=4aefaa38-8757-4e6e-8924-57cabd1c2fc3)
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
Internet Explorer 6 Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Mérsékelt.](http://www.microsoft.com/downloads/details.aspx?familyid=88aba9dd-653b-4cdf-a513-cca32a7d7e41)
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
Internet Explorer 6 Windows Server 2003 SP1 javítócsomaggal ellátott Itanium-alapú rendszerekhez és Windows Server 2003 SP2 csomaggal ellátott Itanium-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Mérsékelt.](http://www.microsoft.com/downloads/details.aspx?familyid=309a8f10-c7ea-4961-a969-092b0c4d7bbc)
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
Internet Explorer 7 Windows XP Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=4ca0ac93-bf51-40fe-a1ba-cb3e0a36d8b5)
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
Internet Explorer 7 alkalmazás Windows XP Professional x64 Edition és Windows XP Professional x64 Edition Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=dbd284d0-2664-42a4-ad16-a0535244c81c)
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
Internet Explorer 7 alkalmazás Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Mérsékelt.](http://www.microsoft.com/downloads/details.aspx?familyid=0a31c451-32f4-4551-ae45-d600f8b3b11b)
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
Internet Explorer 7 Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Mérsékelt.](http://www.microsoft.com/downloads/details.aspx?familyid=c1915633-d181-4ca1-a4f0-7ca0f865aa72)
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
Internet Explorer 7 Windows Server 2003 SP1 javítócsomaggal ellátott Itanium-alapú rendszerekhez és Windows Server 2003 SP2 csomaggal ellátott Itanium-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Mérsékelt.](http://www.microsoft.com/downloads/details.aspx?familyid=093a2250-3be3-494f-80e0-89ca7217030f)
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
Internet Explorer 7 alkalmazás a Windows Vista rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=86392e8d-098c-427f-a233-699cdb9375ae)
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
Internet Explorer 7 alkalmazás Windows Vista x64 rendszeren
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=62490e6d-0a21-4a15-90bd-63ca8f8886b6)
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
Windows SharePoint Services 3.0 alkalmazás Windows Server 2003 Service Pack 1 (KB934525) rendszerre telepítve
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
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=76fc2225-2802-46e5-a294-a842e3841877)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows SharePoint Services 3.0 alkalmazás Windows Server 2003 Service Pack 2 (KB934525) rendszerre telepítve
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
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=76fc2225-2802-46e5-a294-a842e3841877)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows SharePoint Services 3.0 alkalmazás Windows Server 2003 x64 Edition (KB934525) rendszerre telepítve
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
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=667335dd-df2e-4f14-a130-5758701be055)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows SharePoint Services 3.0 alkalmazás Windows Server 2003 x64 Edition Service Pack 2 (KB934525) rendszerre telepítve
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
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=667335dd-df2e-4f14-a130-5758701be055)
</td>
</tr>
<tr>
<th colspan="7">
Microsoft Office
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Word 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritikus](http://www.microsoft.com/downloads/details.aspx?familyid=8b3072fb-5933-47f7-a498-13a93e268e57)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word 2002 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=d6b787bb-03ff-4f67-8b69-6011fb18ba75)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Fontos](http://www.microsoft.com/mac/downloads.aspx)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 (KB937832)
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
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=aaea9695-f541-4c4c-9107-81ead5cfc8c9)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 x64 Edition (KB937832)
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
[Fontos](http://www.microsoft.com/downloads/details.aspx?familyid=1d319164-d133-4493-be27-1aeda62362c4)
</td>
</tr>
</table>
 
**Megjegyzések:**

**<sup>[1]</sup>** Ehhez az operációs rendszerhez rendelkezésre áll egy biztonsági frissítés. További információt a táblázat érintett szoftverre vagy összetevőre vonatkozó részében illetve az ide vonatkozó biztonsági közleményben talál.** **

Észlelési és telepítési eszközök, útmutatás
-------------------------------------------

<span></span>
**Biztonsági központ**

A szoftveres és biztonsági frissítések kezeléséhez azokat a szervezet asztali és hordozható számítógépeire, valamint kiszolgálóira is telepíteni kell. További tájékoztatásért látogasson el a [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) weboldalára. A [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) bővebb tájékoztatással szolgál a Microsoft-termékek biztonsági funkcióival kapcsolatban. A [Biztonság otthon](http://go.microsoft.com/fwlink/?linkid=85102) weboldalon a megfelelő hivatkozásra kattintva elérhetőek a legújabb biztonsági frissítések.

A biztonsági frissítések a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) és az [Office Update](http://go.microsoft.com/fwlink/?linkid=21135) weboldalakról tölthetőek le. A biztonsági frissítések a [Microsoft letöltőközpontjában](http://go.microsoft.com/fwlink/?linkid=21129) is elérhetőek. legegyszerűbben a „biztonsági javítás” kifejezésre irányuló kulcsszavas kereséssel találhatja meg őket.

A biztonsági frissítések a [Microsoft Update katalógusából](http://go.microsoft.com/fwlink/?linkid=96155) is letölthetőek. A Microsoft Update katalógus a Windows Update és Microsoft Update szolgáltatáson keresztül elérhető tartalom kereshető adatbázisa; ide tartoznak a biztonsági frissítések, illesztőprogramok és javítócsomagok. A biztonsági közlemény számára (pl. „MS07-036”) történő kereséssel hozzáadhatja az összes vonatkozó frissítést a kosárhoz (beleértve a frissítés különböző nyelvi változatait), és letöltheti azokat a megadott mappába. A Microsoft Update katalógus részletes leírását lásd a vonatkozó [GYIK](http://go.microsoft.com/fwlink/?linkid=97900)részben.

**Útmutató az észleléshez és a telepítéshez**

A Microsoft az e havi biztonsági frissítésekhez észlelési és telepítési útmutatót adott ki. Az útmutató a számítógépes szakembereknek is ötleteket adhat ahhoz, hogyan használják a különböző eszközöket, pl. Windows Update, Microsoft Update, Office Update, Microsoft Baseline Security Analyzer (MBSA), Office Detection Tool, Microsoft Systems Management Server (SMS), Extended Security Update Inventory Tool vagy Enterprise Update Scan Tool (EST) a biztonsági frissítések telepítéséhez. További információt a [Microsoft Tudásbázis 910723. számú cikkében](http://support.microsoft.com/kb/910723) talál.

**Microsoft Baseline Security Analyzer és Enterprise Update Scan Tool**

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

-   A Microsoft a Microsoft Update (MU) és a Windows Server Update Services (WSUS) szolgáltatáson keresztül három **nem biztonsági jellegű**, kiemelt fontosságú frissítést adott ki.
-   A Microsoft a Windows Update (WU) szolgáltatáson keresztül egy **nem biztonsági jellegű**, kiemelt fontosságú Windows-frissítést adott ki.

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

-   Cu Fang, az MS07-055 közleményben leírt probléma jelentéséért.
-   Rita Schappler, [Global 360](http://www.global360.com/products/g360_imaging/default.asp), az MS07-055 közleményben ismertetett problémában való közös munkavégzéséért.
-   Greg MacManus, [VeriSign iDefense Labs](http://www.idefense.com/), az MS07-056 közleményben bemutatott probléma jelentéséért.
-   Pierre Geyer, next.motion OHG az MS07-057 közleményben bemutatott probléma jelentéséért.
-   Carsten H. Eiram, [Secunia Research](http://secunia.com/), az MS07-057 közleményben bemutatott probléma jelentéséért.
-   Jakob Balle, [Secunia Research](http://secunia.com/), az MS07-057 közleményben bemutatott probléma jelentéséért.
-   [Zero Day Initiative](http://www.zerodayinitiative.com/) az MS07-058 közleményben bemutatott probléma jelentéséért.
-   Liu Kun-Hao, Information & Communication Security Technology Center, az MS07-060 közleményben bemutatott probléma jelentéséért.

#### Terméktámogatás

-   Teszteléssel állapították meg a felsorolt szoftverek egyes verzióinak érintettségét. A többi verzió támogatási életciklusa végére ért. Az egyes szoftververziók támogatási életciklusáról a [Microsoft termékek terméktámogatási életciklusát ismertető webhelyen](http://go.microsoft.com/fwlink/?linkid=21742) talál felvilágosítást.
-   Az Amerikai Egyesült Államokban és Kanadában technikai segítség igényelhető a [Microsoft terméktámogatási szolgáltatásától](http://go.microsoft.com/fwlink/?linkid=21131), amelynek telefonszáma 1-866-PCSAFETY. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek.
-   Más országokban a helyi Microsoft-képviseletek nyújtanak támogatást. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. A [nemzetközi támogatási webhely](http://go.microsoft.com/fwlink/?linkid=21155) felvilágosítást nyújt arról, támogatási kérdéseivel hogyan fordulhat a Microsofthoz.

#### Felelősséget kizáró nyilatkozat

A Microsoft Tudásbázisban leírtak előzetes bejelentés nélkül változhatnak, és a cikkek tartalmáért a Microsoft nem vállal garanciát. A Microsoft egyben elhárít minden kifejezett és értelemszerű garanciát, beleértve az eladhatóságra és az adott célra való alkalmasságra vonatkozó garanciát is. A Microsoft Corporation vagy annak szállítói semmilyen körülmények között nem tehetők felelőssé közvetlen, közvetett, eseti, ok-okozati vagy különleges kárért (beleértve az elmaradt hasznot is), még akkor sem, ha a Microsoft Corporation vagy szállítói tudatában voltak a kár lehetséges voltának. Egyes államok törvényi szabályozása nem teszi lehetővé a véletlen vagy ok-okozati károkért vállalt felelősség korlátozását vagy kizárását, így ezekben az államokban az ez a felelősségkizárás nincs érvényben.

#### Verziók

-   1.0 verzió (2007. október 9.): Összefoglaló közlemény közzététele.

*Built at 2014-04-18T01:50:00Z-07:00*
