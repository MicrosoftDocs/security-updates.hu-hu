---
TOCTitle: 'MS08-NOV'
Title: 'Microsoft biztonsági közlemény - összefoglalás, november 2008'
ms:assetid: 'ms08-nov'
ms:contentKeyID: 61227723
ms:mtpsurl: 'https://technet.microsoft.com/hu-HU/library/ms08-nov(v=Security.10)'
author: SharonSears
ms.author: SharonSears
---

Security Bulletin Summary

Microsoft biztonsági közlemény - összefoglalás, november 2008
=============================================================

Közzétéve: 2008. november 11. | Frissítve: 2011. július 12.

**Verzió:** 4.0

Az összefoglaló a 2008 novemberében kiadott biztonsági közleményeket összegzi.

A 2008. novemberi közlemények kiadása folytán az összefoglaló a 2008. november 6-án kiadott előzetes értesítés helyébe lép. További információk a biztonsági közlemények kiadásáról szóló előzetes értesítés szolgáltatásról lásd: [Előzetes értesítés a Microsoft biztonsági közleményeinek kiadásáról](http://technet.microsoft.com/security/bulletin/advance).

Ha automatikus értesítést szeretne kapni a Microsoft biztonsági közleményeinek megjelenéséről, fizessen elő a [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) szolgáltatásra.

A közleményekkel kapcsolatos kérdések megválaszolására a Microsoft 2008. november 12-én, csendes-óceáni idő szerint (USA és Kanada) 11 órakor webes szemináriumot tart. [Jelentkezzen most a novemberi közleményeket bemutató webes szemináriumra](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374642). Ezt követően a webes szeminárium igény szerint kerül megrendezésre. További információkért látogasson el a [Microsoft biztonsági közleményeit és a webes szemináriumokat](http://technet.microsoft.com/security/bulletin/summary)bemutató oldalra.

A Microsoft abban is segítséget nyújt felhasználóinak, hogy a havi biztonsági közleményekkel azonos napon kiadott, nem biztonsági jellegű, de fontos frissítéseket megfelelően rangsorolhassák. Lásd az **Egyéb információ című részt**.

### A közleménnyel kapcsolatos információk

#### Összefoglalások

Az e havi biztonsági közlemények súlyossági sorrendben:

Kritikus (1)
------------

<span></span>

| Közlemény azonosítója                          | Microsoft MS08-069 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                                                                           |
|------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**A Microsoft XML Core Services biztonsági rései távolról történő programkódfuttatást tehetnek lehetővé (955218)**](http://go.microsoft.com/fwlink/?linkid=128803)                                                                                                                                                                                                                                                                                      |
| **Összefoglalás**                              | A biztonsági frissítés a Microsoft XML Core Services számos biztonsági rését szünteti meg. A legsúlyosabb besorolású biztonsági rés távoli kódvégrehajtást tehet lehetővé, amennyiben a felhasználó egy különlegesen kialakított weboldalt tekint meg az Internet Explorer alkalmazásban. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén |
| **Súlyosság maximális foka**                   | [Kritikus](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                 |
| **A biztonsági rés hatása**                    | Távoli kódfuttatás                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. Előfordulhat, hogy a frissítés a rendszer újraindítását igényli.                                                                                                                                                                                                                                                                                  |
| **Érintett szoftverek**                        | **Microsoft Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                                                               |

Fontos (1)
----------

<span></span>

| Közlemény azonosítója                          | A Microsoft MS08-068 számú biztonsági közleménye                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Közlemény címe**                             | [**Az SMB biztonsági rése távolról történő kódfuttatást tehet lehetővé (957097)**](http://go.microsoft.com/fwlink/?linkid=133434)                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Összefoglalás**                              | Ez a biztonsági frissítés a Microsoft Server Message Block (SMB) protokoll közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rés lehetővé teszi programkódok távolról történő futtatását az érintett rendszereken. A biztonsági rést sikeresen kihasználó támadó programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén |
| **Súlyosság maximális foka**                   | [Fontos](http://go.microsoft.com/fwlink/?linkid=21140)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **A biztonsági rés hatása**                    | Távoli kódfuttatás                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **A szoftver észlelésével kapcsolatos adatok** | A Microsoft Baseline Security Analyzer képes észlelni, szükséges-e a számítógépen az adott frissítést. Ez a frissítés újraindítást igényel.                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Érintett szoftverek**                        | **Microsoft Windows.** További információt az Érintett szoftverek és letöltési helyek című rész tartalmaz.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |

Kihasználhatósági információk
-----------------------------

<span></span>
**A táblázat használata**

A táblázat segítségével meghatározható annak valószínűsége, hogy a biztonsági közlemény kiadását követő 30 napon belül a telepíteni szükséges biztonsági frissítésekre működő rosszindulatú programkódot jelentetnek meg. A telepítés fontossági sorrendjének megállapításához az adott konfigurációnak megfelelően tekintse át az alábbi értékeléseket. A minősítések jelentéséről és meghatározásuk módjáról a [Microsoft biztonsági rések jegyzéke](http://technet.microsoft.com/en-us/security/cc998259.aspx) tartalmaz bővebb információt.

| Közlemény azonosítója                                     | Közlemény címe                                                                                                                                                  | CVE-azonosító                                                                    | Kihasználhatósági információk értékelése                                                                             | Fontos megjegyzések                                                                                                                      |
|-----------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| [MS08-068](http://go.microsoft.com/fwlink/?linkid=133434) | [Az SMB biztonsági rése távolról történő kódfuttatást tehet lehetővé (957097)](http://go.microsoft.com/fwlink/?linkid=133434)                                   | [CVE-2008-4037](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4037) | [1 - Valószínűleg konzisztens rosszindulatú programkód](http://technet.microsoft.com/en-us/security/cc998259.aspx)   | A kihasználásra alkalmas kód Windows XP rendszer esetében nyilvánosságra került.                                                         |
| [MS08-069](http://go.microsoft.com/fwlink/?linkid=128803) | [A Microsoft XML Core Services biztonsági rései távolról történő programkódfuttatást tehetnek lehetővé (955218)](http://go.microsoft.com/fwlink/?linkid=128803) | [CVE-2008-4029](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4029) | [1 - Valószínűleg konzisztens rosszindulatú programkód](http://technet.microsoft.com/en-us/security/cc998259.aspx)   | Az adatokhoz való illetéktelen hozzáférés rosszindulatú kódja valószínű, mivel idegen tartományokból induló támadásokra használható fel. |
| [MS08-069](http://go.microsoft.com/fwlink/?linkid=128803) | [A Microsoft XML Core Services biztonsági rései távolról történő programkódfuttatást tehetnek lehetővé (955218)](http://go.microsoft.com/fwlink/?linkid=128803) | [CVE-2007-0099](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2007-0099) | [2 - Valószínűleg inkonzisztens rosszindulatú programkód](http://technet.microsoft.com/en-us/security/cc998259.aspx) | A biztonsági rés az XML-fájlok betöltésekor versenyhelyzettel társul. Emiatt konzisztens kihasználása nehézségekbe ütközik.              |
| [MS08-069](http://go.microsoft.com/fwlink/?linkid=128803) | [A Microsoft XML Core Services biztonsági rései távolról történő programkódfuttatást tehetnek lehetővé (955218)](http://go.microsoft.com/fwlink/?linkid=128803) | [CVE-2008-4033](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4033) | [2 - Valószínűleg inkonzisztens rosszindulatú programkód](http://technet.microsoft.com/en-us/security/cc998259.aspx) |                                                                                                                                          |

Érintett szoftverek és letöltési helyek
---------------------------------------

<span></span>
**A táblázat használata**

A táblázat segítségével megtudhatja a szükséges információt a telepítendő biztonsági frissítésekről. Nézzen meg minden felsorolt szoftvert vagy összetevőt annak megállapításához, hogy van-e telepítendő biztonsági frissítés. Ha a szoftver vagy összetevő szerepel a listán, hiperhivatkozással kapcsolódik hozzá az elérhető szoftverfrissítés, és a frissítés besorolása is fel van tüntetve.

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
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
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
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=559cd4b6-24b7-4e60-8749-37d9b833d3eb)  
(KB955069)  
(Kritikus)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Fontos)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=44c971e6-96fc-4bba-8f4a-f9d46bda2b6c)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="3">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
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
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=6ed1a087-97e2-4283-9b53-b7b046654d08)  
(KB955069)  
(Kritikus)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Fontos)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6f8ae0aa-fd68-4156-9016-bba00149793c)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.http//www.microsoft.com/downloads/details.aspx?familyid=6ed1a087-97e2-4283-9b53-b7b046654d08)  
(KB955069)  
(Kritikus)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Fontos)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=7493fa37-2cbf-4d66-8690-d50d63da4096)  
(KB954459)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6f8ae0aa-fd68-4156-9016-bba00149793c)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition és Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=1b79f220-ebfc-49c1-963b-58bbda21b6e7)  
(KB955069)  
(Kritikus)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Fontos)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition és Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9501b33b-d639-43e7-ad5a-9e76ed66effd)  
(Fontos)
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
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
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
Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2 rendszerhez
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=0a0f8385-e908-4b5f-b9bf-80b7dabfcafd)  
(KB955069)  
(Kritikus)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Alacsony)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Alacsony)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=57a0606d-ea7a-4e5b-8b8b-7b77a444ef75)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2 rendszerhez
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=347c8c83-4269-4a0e-af6f-4be2e824d22b)  
(KB955069)  
(Kritikus)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Alacsony)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Alacsony)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=915e001f-9aa0-4fb0-9c2a-0f0c72b4f056)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP1 Itanium alapú rendszerekhez és Windows Server 2003 SP2 Itanium alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=3a65e1cd-eb4e-44b6-8868-a5a84be2cb32)  
(KB955069)  
(Kritikus)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Alacsony)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Alacsony)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1 Itanium alapú rendszerekhez és Windows Server 2003 SP2 Itanium alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=6abf7ba9-825f-4ee2-a2fe-6b1cd9fab622)  
(Fontos)
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
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
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
[**Mérsékelt**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista és Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=affbc957-1867-4bbe-924d-6f0696ae0895)  
(KB955069)  
(Kritikus)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Fontos)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=cb6c4315-8c6d-43af-978b-b190b1a1577a)  
(KB954459)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Vista és Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5612815f-8685-45d2-af4a-164c298a0869)  
(Mérsékelt)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition és Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=b01a5f31-8c57-4c5c-909e-b37caf0439b0)  
(KB955069)  
(Kritikus)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Fontos)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=39443046-2093-4c87-ac7b-679deab96414)  
(KB954459)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition és Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=727ce9b6-827f-4350-b4ff-c08e8ac541a6)  
(Mérsékelt)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Fontos)
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
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
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
[**Mérsékelt**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 32 bites rendszerekhez
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=90a04164-4d02-4ce9-b3d8-bddb1ec27618)\*\*  
(KB955069)  
(Kritikus)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(Alacsony)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=dea9f227-967f-47c7-bb2a-ed68f13645d9)\*\*  
(KB954459)  
(Alacsony)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=b305e894-61ec-46b4-91ee-4c9ac59bc47e)\*  
(Mérsékelt)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 32 bites rendszerekhez, Service Pack 2\*
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(Alacsony)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 x64-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=b7bfe3f4-835f-402c-95b5-6d49b6935308)\*\*  
(KB955069)  
(Kritikus)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(Alacsony)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f16e2a5f-37fd-4ee1-aef0-597214323dc4)\*\*  
(KB954459)  
(Alacsony)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=e8d26dfd-b347-4f10-b5b6-27dfff5e4f47)\*  
(Mérsékelt)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 x64-alapú rendszerekhez, Service Pack 2\*
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(Alacsony)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 Itanium-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=4e0d1efe-70ac-459b-b330-c0149b74f520)  
(KB955069)  
(Kritikus)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Alacsony)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=d4ae74e2-1b09-4a99-8cf5-8a8ca8ac6f7f)  
(KB954459)  
(Alacsony)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 Itanium alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=d565467d-e10f-4ddc-a278-3f81a3798686)  
(Mérsékelt)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Itanium-alapú rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Alacsony)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
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
Nincsenek
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 32 bites rendszerekhez és Windows 7 32 bites rendszerekhez Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 alapú rendszerekhez és Windows 7 x64 alapú rendszerekhez Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
[**Alacsony**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 x64 alapú rendszerekhez és Windows Server 2008 R2 x64 alapú rendszerekhez Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(Alacsony)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium alapú rendszerekhez és Windows Server 2008 R2 Itanium alapú rendszerekhez Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Alacsony)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
</table>
 
**\*Érinti a kiszolgálómag telepítését.** Ez a frissítés ugyanolyan biztonsági besorolás mellett, a megadottak szerint érvényes az Windows Server 2008 és a Windows Server 2008 R2 összes támogatott kiadására, függetlenül attól, hogy a kiszolgálómag-telepítési opcióval telepítették-e. Erről a telepítési opcióról bővebben a [Kiszolgálómag](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) és a [Kiszolgálómag a Windows Server 2008 R2 rendszerhez](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) MSDN-cikkekben olvashat. A kiszolgálómag-telepítési opció nem vonatkozik a Windows Server 2008 és a Windows Server 2008 R2 bizonyos kiadásaira; lásd: [A kiszolgálómag-telepítési opciók összehasonlítása](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*A kiszolgálómag-telepítés nem érintett.** A frissítésben tárgyalt biztonsági rések nem érintik a jelzett módon a Windows Server 2008 és a Windows Server 2008 R2 támogatott kiadásait, amennyiben a telepítés a kiszolgálómag-telepítési opció használatával történt. Erről a telepítési opcióról bővebben a [Kiszolgálómag](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) és a [Kiszolgálómag a Windows Server 2008 R2 rendszerhez](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) MSDN-cikkekben olvashat. A kiszolgálómag-telepítési opció nem vonatkozik a Windows Server 2008 és a Windows Server 2008 R2 bizonyos kiadásaira; lásd: [A kiszolgálómag-telepítési opciók összehasonlítása](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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
Microsoft Office programcsomagok, rendszerek és összetevők
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
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
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ad891a8-c3bb-4479-8282-13d629c410e3)  
(KB951535)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office System és 2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245)  
(KB951550)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="2">
További Office-szoftverek
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
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
Microsoft Word Viewer 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=7ad891a8-c3bb-4479-8282-13d629c410e3)  
(KB951535)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office kompatibilitási csomag a Word, Excel, PowerPoint 2007 fájlformátumokhoz, továbbá Microsoft Office kompatibilitási csomag a Word, Excel, valamint PowerPoint 2007 fájlformátumokhoz (Service Pack 1)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245)  
(KB951550)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Web és Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245)  
(KB951550)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 és Microsoft Office SharePoint Server 2007 Service Pack 1 (32 bites kiadás)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=a208f2b5-2b0d-43bb-8f8a-58d4a3fc64f5)  
(KB951597)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 és Microsoft Office SharePoint Server 2007 Service Pack 1, 64 bites kiadás
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=0735f4af-e32b-4970-bed7-b2b9323cf54c)  
(KB951597)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Groove Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=0735f4af-e32b-4970-bed7-b2b9323cf54c)  
(KB951597)  
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

**Megjegyzés:** Az SMS a Microsoft Baseline Security Analyzer és a Microsoft Office Detection Tool program segítségével széles körű támogatást nyújt a biztonsági értesítők frissítéseinek észleléséhez és telepítéséhez. Előfordulhat, hogy egyes szoftverfrissítéseket ezek az eszközök nem észlelnek. Az SMS alkalmazás leltározási szolgáltatásai segítségével a rendszergazdák adott rendszereken hajthatják végre a frissítést. Az eljárással kapcsolatban olvassa el a [szoftverfrissítések telepítése az SMS szoftverelosztó ügynök segítségével](http://go.microsoft.com/fwlink/?linkid=33341) című tájékoztatót. Egyes biztonsági frissítésekhez rendszergazdai jogosultságokra van szükség a számítógép újraindítása után. A rendszergazdák az [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) és az [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) csomag részét képező Elevated Rights Deployment Tool nevű eszközzel telepíthetik ezeket a frissítéseket.

**Az Update Compatibility Evaluator (a frissítéskompatibilitás kiértékelője) és az Application Compatibility Toolkit (alkalmazáskompatibilitási eszközkészlet)**

Az alkalmazások működése érdekében a frissítések gyakran írnak ugyanazokba a fájlokba, illetve regisztrációs bejegyzésekbe. Ez inkompatibilitást okozhat, és növelheti a biztonsági frissítések központi telepítésére használt időt. A Windows frissítések és az alkalmazásoknak való megfelelőségének tesztelése és ellenőrzése egyszerűsíthető az [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) eszközeivel, ami része az [Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=hu) csomagnak.

Az Application Compatibility Toolkit (ACT) tartalmazza a Microsoft Windows Vista, a Windows Update, a Microsoft Security Update vagy a Windows Internet Explorer új verziójának központi telepítése előtt az alkalmazáskompatibilitási problémák kiértékeléséhez és enyhítéséhez szükséges eszközöket és dokumentációt.

### Egyéb információ

#### A Microsoft Windows rosszindulatú szoftvereket eltávolító eszköze

A Microsoft a Windows Update, Microsoft Update, Windows Server Update Services és Letöltőközpont szolgáltatásán keresztül elérhetővé tette a Microsoft Windows rosszindulatú szoftvereket eltávolító eszközének frissített változatát.

#### Nem biztonsági jellegű, kiemelt fontosságú frissítések a MU, WU és WSUS-szolgáltatásokban

A Windows Update és a Microsoft Update helyen elérhető, nem biztonsági jellegű frissítésekről tájékozódjon itt:

-   [Microsoft Tudásbázis 894199. cikke:](http://support.microsoft.com/kb/894199) A Software Update Services és a Windows Server Update Services 2008-as tartalmi módosításainak ismertetése. Minden, Windows rendszerre vonatkozó tartalom.
-   [Microsoft-termékek új, módosított és közreadott frissítései, a Microsoft Windows rendszert kivéve](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

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

-   Gregory Fleischer, az MS08-069 közleményben leírt probléma jelentéséért
-   Stefano Di Paola, [Minded Security](http://www.mindedsecurity.com/), az MS08-069 közleményben leírt probléma jelentéséért

#### Terméktámogatás

-   Teszteléssel állapították meg a felsorolt szoftverek egyes verzióinak érintettségét. A többi verzió támogatási életciklusa végére ért. Az egyes szoftververziók támogatási életciklusáról a [Microsoft termékek terméktámogatási életciklusát ismertető webhelyen](http://go.microsoft.com/fwlink/?linkid=21742) talál felvilágosítást.
-   Az Amerikai Egyesült Államokban és Kanadában technikai segítség igényelhető a [Microsoft terméktámogatási szolgáltatásától](http://go.microsoft.com/fwlink/?linkid=21131), amelynek telefonszáma 1-866-PCSAFETY. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek.
-   Más országokban a helyi Microsoft-képviseletek nyújtanak támogatást. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. A [nemzetközi támogatási webhely](http://go.microsoft.com/fwlink/?linkid=21155) felvilágosítást nyújt arról, támogatási kérdéseivel hogyan fordulhat a Microsofthoz.

#### Felelősséget kizáró nyilatkozat

A Microsoft Tudásbázisban leírtak előzetes bejelentés nélkül változhatnak, és a cikkek tartalmáért a Microsoft nem vállal garanciát. A Microsoft egyben elhárít minden kifejezett és értelemszerű garanciát, beleértve az eladhatóságra és az adott célra való alkalmasságra vonatkozó garanciát is. A Microsoft Corporation vagy annak szállítói semmilyen körülmények között nem tehetők felelőssé közvetlen, közvetett, eseti, ok-okozati vagy különleges kárért (beleértve az elmaradt hasznot is), még akkor sem, ha a Microsoft Corporation vagy szállítói tudatában voltak a kár lehetséges voltának. Egyes államok törvényi szabályozása nem teszi lehetővé a véletlen vagy ok-okozati károkért vállalt felelősség korlátozását vagy kizárását, így ezekben az államokban az ez a felelősségkizárás nincs érvényben.

#### Verziók

-   1.0 verzió (2008. november 11.): Összefoglaló közlemény közzététele.
-   2.0 verzió (2009. április 29.): Az MS08-069 közlemény érintett szoftverek listája a Windows Vista Service Pack 2 32 bites és x64 alapú kiadásain, valamint a Windows Server 2008 Service Pack 2 32 bites, x64 alapú és Itanium alapú kiadásain futó Microsoft XML Core Services 4.0 alkalmazással bővült (KB954430). Ez csak az észlelésre vonatkozó módosítás; a bináris fájlok nem változtak. Azoknak a felhasználóknak, akik sikeresen telepítették a KB954430 frissítést, nem kell újratelepítést végezniük.
-   3.0 verzió (2009. október 13.): Az MS08-069 közlemény érintett szoftverek listája a Windows 7 32 bites és x64 alapú kiadásain, valamint a Windows Server 2008 R2 x64 alapú és Itanium alapú kiadásain futó Microsoft XML Core Services 4.0 alkalmazással bővült (KB954430). Ez csak az észlelésre vonatkozó módosítás; a bináris fájlok nem változtak. Azoknak a felhasználóknak, akik sikeresen telepítették a KB954430 frissítést, nem kell újratelepítést végezniük.
-   4.0 verzió (2011. július 12.): Az MS08-069 közlemény érintett szoftverek listája a Windows 7 Service Pack 1 32 bites és x64 alapú kiadásain, valamint a Windows Server Service Pack 1 2008 R2 x64 alapú és Itanium alapú kiadásain futó Microsoft XML Core Services 4.0 alkalmazással bővült (KB954430). Ez csak az észlelésre vonatkozó módosítás; a bináris fájlok nem változtak. Azoknak a felhasználóknak, akik sikeresen telepítették a KB954430 frissítést, nem kell újratelepítést végezniük.

*Built at 2014-04-18T01:50:00Z-07:00*
