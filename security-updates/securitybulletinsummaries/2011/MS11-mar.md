---
TOCTitle: 'MS11-MAR'
Title: Microsoft Security Bulletin Summary for március 2011
ms:assetid: 'ms11-mar'
ms:contentKeyID: 61227757
ms:mtpsurl: 'https://technet.microsoft.com/hu-HU/library/ms11-mar(v=Security.10)'
author: SharonSears
ms.author: SharonSears
---

Security Bulletin Summary

Microsoft Security Bulletin Summary for március 2011
====================================================

Közzétéve: 2011. március 8. | Frissítve: 2011. március 16.

**Verzió:** 1.1

Az összefoglaló a 2011 márciusában kiadott biztonsági közleményeket összegzi.

A 2011. márciusi biztonsági közlemények kiadása folytán az összefoglaló a 2011. március 3-án kiadott előzetes értesítés helyébe lép. A biztonsági közlemények kiadásáról szóló előzetes értesítés szolgáltatásról itt olvashat bővebben: [Előzetes értesítés a Microsoft biztonsági közleményeinek kiadásáról](http://technet.microsoft.com/security/bulletin/advance).

Ha automatikus értesítést szeretne kapni a Microsoft biztonsági közleményeinek megjelenéséről, fizessen elő a [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) szolgáltatásra.

A közleményekkel kapcsolatos kérdések megválaszolására a Microsoft 2011. március 9-én, csendes-óceáni idő szerint 11 órakor webes szemináriumot tart. Jelentkezzen most a [márciusi közleményeket bemutató webes szemináriumra](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032455049&eventcategory=4). Ezt követően a webes szeminárium igény szerint kerül megrendezésre. További információkért látogasson el a [Microsoft biztonsági közleményeit és a webes szemináriumokat](http://technet.microsoft.com/security/bulletin/summary)bemutató oldalra.

A Microsoft abban is segítséget nyújt felhasználóinak, hogy a havi biztonsági közleményekkel azonos napon kiadott, nem biztonsági jellegű frissítéseket megfelelően rangsorolhassák. Lásd az **Egyéb információ című részt**.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207841">MS11-015</a></td>
<td style="border:1px solid black;"><strong>A Windows Media biztonsági rései távoli programkódfuttatást tesznek lehetővé (2510030)</strong><br />
<br />
A biztonsági frissítés a DirectShow egy nyilvánosságra került és a Windows Media Player és a Windows Media Center egy közvetlenül jelentett biztonsági résének hibáját hárítja el. Ezek közül a legsúlyosabb biztonsági rés távoli kódfuttatásra ad lehetőséget, ha a felhasználó megnyit egy speciálisan kialakított Microsoft Digital Video Recording (.dvr-ms) fájlt. A felhasználót nem lehet a fájl megnyitására kényszeríteni: minden esetben rá kell venni, hogy magától nyissa meg a fájlt.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=207892">MS11-017</a></td>
<td style="border:1px solid black;"><strong>A Távoli asztali ügyfél biztonsági rése távoli kódfuttatást okozhat (2508062)</strong><br />
<br />
A biztonsági frissítés a Windows Távoli asztali ügyfél nyilvánosal jelentett biztonsági rését szünteti meg. A biztonsági rés távolról történő programkódfuttatást tehet lehetővé, ha a felhasználó olyan érvényes Távoli asztali ügyfél konfigurációs fájlt nyit meg (.rdp), amely egy speciálisan kialakított függvénytárfájllal azonos hálózati mappában található. A sikeres támadáshoz a felhasználónak egy nem megbízhatónak ítélt távoli fájlrendszerre vagy WebDAV megosztásra kell ellátogatnia, majd onnan dokumentumot megnyitnia, amelyet ezt követően a biztonsági rés által érintett alkalmazás betölt.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=209774">MS11-016</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Groove biztonsági rése távoli kódfuttatást tehet lehetővé (2494047)</strong><br />
<br />
A biztonsági támadás egy nyilvánosságra került biztonsági rés problémáját oldja meg, amelyen keresztül távoli kódfuttatást lehetett elérni, ha a támadó ráveszi a felhasználót, hogy nyisson meg egy normál, Groove alapú fájlt, amely azonban azonos hálózati meghajtón található, mint a speciálisan létrehozott függvénytárfájl. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
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
A következő táblázat az adott hónapban megoldott biztonsági rések kihasználhatósági jellemzőit ismerteti. A biztonsági rések a kihasználhatósági kockázat, majd a CVE azonosító szerint vannak felsorolva. Csak a kritikus és fontos besorolású biztonsági rések szerepelnek.
  
**A táblázat használata**
  
A táblázat segítségével meghatározható annak valószínűsége, hogy a biztonsági közlemény kiadását követő 30 napon belül a telepíteni szükséges biztonsági frissítésekre működő rosszindulatú programkódot jelentetnek meg. A telepítés fontossági sorrendjének megállapításához az adott konfigurációnak megfelelően tekintse át az alábbi értékeléseket. A minősítések jelentéséről és meghatározásuk módjáról a [Microsoft biztonsági rések jegyzéke](http://technet.microsoft.com/en-us/security/cc998259.aspx) tartalmaz bővebb információt.
  
| Közlemény azonosítója                                     | A biztonsági rés címe                                                       | CVE-azonosító                                                                    | Kihasználhatósági információk értékelése                                                                         | Fontos megjegyzések                                                              |  
|-----------------------------------------------------------|-----------------------------------------------------------------------------|----------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|  
| [MS11-016](http://go.microsoft.com/fwlink/?linkid=209774) | Microsoft Groove nem biztonságos függvénytárbetöltése miatti biztonsági rés | [CVE-2010-3146](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3146) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | **A biztonsági rést nyilvánosan jelentették, és a PoC kód rendelkezésre állhat** |  
| [MS11-017](http://go.microsoft.com/fwlink/?linkid=207892) | Távoli asztal nem biztonságos függvénytárbetöltése miatti biztonsági rés    | [CVE-2011-0029](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0029) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | **A biztonsági rés nyilvánosságra került**                                       |  
| [MS11-015](http://go.microsoft.com/fwlink/?linkid=207841) | DirectShow nem biztonságos függvénytárbetöltése miatti biztonsági rés       | [CVE-2011-0032](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0032) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | **A biztonsági rést nyilvánosan jelentették, és a PoC kód rendelkezésre állhat** |  
| [MS11-015](http://go.microsoft.com/fwlink/?linkid=207841) | DVR-MS biztonsági rés                                                       | [CVE-2011-0042](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0042) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | (Nincs)                                                                          |
  
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
[**MS11-015**](http://go.microsoft.com/fwlink/?linkid=207841)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://go.microsoft.com/fwlink/?linkid=207892)
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
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=d8284bfa-ed6c-4647-9fb0-588e53173775)  
(KB2479943)  
(Kritikus)  
[Windows XP Media Center Edition 2005 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b1be30de-7e88-467d-aee2-68f88e6a7355)  
(KB2502898)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Távoli asztali kapcsolat 5.2 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=1aed6080-feab-4b5e-9d26-6a3f4b92434d)  
(KB2483618)  
(Fontos)  
[Távoli asztali kapcsolat 6.1 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=d67e4d8c-aeb9-45e6-9555-7456c5540475)  
(KB2481109)  
(Fontos)  
[Távoli asztali kapcsolat 7.0 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=6a01992e-c9a1-4dc9-a3ef-7410b81f17e6)  
(KB2483614)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5270b5d3-3720-42a2-a8cf-67089c0cc658)  
(KB2479943)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Távoli asztali kapcsolat 6.0 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=6d4539ef-4a05-4c7d-9489-436f7b7a3ebe)<sup>[1]</sup>
(KB2481109)  
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
[**MS11-015**](http://go.microsoft.com/fwlink/?linkid=207841)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://go.microsoft.com/fwlink/?linkid=207892)
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Távoli asztali kapcsolat 6.0 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=641d5d12-0790-4551-831a-e78febad17a7)<sup>[1]</sup>
(KB2481109)  
(Fontos)  
[Távoli asztali kapcsolat 6.0 ügyfélszoftver Multilingual User Interface (MUI) felülete](http://www.microsoft.com/downloads/details.aspx?familyid=6fec0d06-042d-4e55-9843-009edd7d26ce)<sup>[2]</sup>
(KB2483619)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Távoli asztali kapcsolat 6.0 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=78dbb9cf-8a18-4f0a-8edf-f1ce0c993c63)<sup>[1]</sup>
(KB2481109)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="3">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS11-015**](http://go.microsoft.com/fwlink/?linkid=207841)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://go.microsoft.com/fwlink/?linkid=207892)
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
Windows Vista Service Pack 1 és Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 és Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f9f1dde2-2219-4bf1-a497-edd011577b96)<sup>[1]</sup>
(KB2479943)  
(Kritikus)  
[Windows Media Center TV Pack for Windows Vista (32 bites kiadások](http://www.microsoft.com/downloads/details.aspx?familyid=1bc240b3-1938-4350-b26f-67b81a79f8a0))<sup>[2]</sup>
(KB2494132)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Távoli asztali kapcsolat 6.1 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=e3ea7690-386b-4cdf-889f-b3914921c56f)  
(KB2481109)  
(Fontos)  
[Távoli asztali kapcsolat 7.0 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=3c30f67e-7c31-4553-ba3e-e056df1bf8eb)  
(KB2483614)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 és Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 és Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e11d00df-d1cf-4a33-a1be-6721cdff5995)<sup>[1]</sup>
(KB2479943)  
(Kritikus)  
[Windows Media Center TV Pack for Windows Vista (64 bites kiadások](http://www.microsoft.com/downloads/details.aspx?familyid=cd4c5a80-db24-4696-a248-1286c3b9f550))<sup>[2]</sup>
(KB2494132)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Távoli asztali kapcsolat 6.1 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=5735bed6-0e3d-46a4-85d0-14ec34a82edd)  
(KB2481109)  
(Fontos)  
[Távoli asztali kapcsolat 7.0 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=8025482b-f58f-4f5a-a133-5563c65b21f6)  
(KB2483614)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS11-015**](http://go.microsoft.com/fwlink/?linkid=207841)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://go.microsoft.com/fwlink/?linkid=207892)
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
Windows Server 2008 32 bites rendszerekhez és Windows Server 2008 32 bites rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Távoli asztali kapcsolat 6.1 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=31d790c9-92f9-4a2b-800b-8e8d2b570bb9)\*\*  
(KB2481109)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 x64-alapú rendszerekhez és Windows Server 2008 x64-alapú rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Távoli asztali kapcsolat 6.1 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=5b0a8eb5-4bc2-4054-b952-58aa645afcf5)\*\*  
(KB2481109)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Itanium-alapú rendszerekhez és Windows Server 2008 Itanium-alapú rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Távoli asztali kapcsolat 6.1 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=25da7e00-745d-4d98-9dd8-52a8a4340404)  
(KB2481109)  
(Fontos)
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
[**MS11-015**](http://go.microsoft.com/fwlink/?linkid=207841)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://go.microsoft.com/fwlink/?linkid=207892)
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
Windows 7 32 bites rendszerekhez és Windows 7 32 bites rendszerekhez Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 32 bites rendszerekhez és Windows 7 32 bites rendszerekhez Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1be77daa-29b1-4dae-a87f-2cb8f7e6a305)  
(KB2479943)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Csak Windows 7 32 bites rendszerekhez:  
[Távoli asztali kapcsolat 7.0 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=0768a5f4-da28-4b2e-8aff-d68f890df3e6)  
(KB2483614)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64 alapú rendszerekhez és Windows 7 x64 alapú rendszerekhez Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 x64 alapú rendszerekhez és Windows 7 x64 alapú rendszerekhez Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=56fb24ce-65c7-4573-b613-e424ccc1a3a6)  
(KB2479943)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Csak Windows 7 x64 alapú rendszerekhez:  
[Távoli asztali kapcsolat 7.0 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=935adb10-1e7e-4501-b543-8247b88f6d18)  
(KB2483614)  
(Fontos)
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
[**MS11-015**](http://go.microsoft.com/fwlink/?linkid=207841)
</td>
<td style="border:1px solid black;">
[**MS11-017**](http://go.microsoft.com/fwlink/?linkid=207892)
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
Windows Server 2008 R2 x64 alapú rendszerekhez és Windows Server 2008 R2 x64 alapú rendszerekhez Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64 alapú rendszerekhez és Windows Server 2008 R2 x64 alapú rendszerekhez Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6f45658a-1db8-4ef5-b840-4d0180d4d90e)\*\*  
(KB2479943)  
(Fontos)
</td>
<td style="border:1px solid black;">
Csak Windows Server 2008 R2 x64 alapú rendszerekhez:  
[Távoli asztali kapcsolat 7.0 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=3fcb2e11-591e-484a-a992-2f1d563e6d17)\*\*  
(KB2483614)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Távoli asztali kapcsolat 7.0 ügyfélszoftver](http://www.microsoft.com/downloads/details.aspx?familyid=c29b6487-78f0-421c-810c-c5e45d6a2352)  
(KB2483614)  
(Fontos)
</td>
</tr>
</table>
 
**Megjegyzések a Windows Server 2008 és Windows Server 2008 R2 rendszerhez**

**\*\*A kiszolgálómag-telepítés nem érintett.** A frissítésben tárgyalt biztonsági rések nem érintik a jelzett módon a Windows Server 2008 és a Windows Server 2008 R2 támogatott kiadásait, amennyiben a telepítés a kiszolgálómag-telepítési opció használatával történt. Erről a telepítési opcióról bővebben a [Kiszolgálómag-telepítés kezelése](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)és [Kiszolgálómag-telepítés szervizelése](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) TechNet cikkekben olvashat. A kiszolgálómag-telepítési opció nem vonatkozik a Windows Server 2008 és a Windows Server 2008 R2 bizonyos kiadásaira; lásd: [A kiszolgálómag-telepítési opciók összehasonlítása](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Megjegyzések az MS11-015 közleményhez**

<sup>[1]</sup>A Windows Media Center TV Pack for Windows Vista verzióra nézve lásd az alábbi, <sup>[2]</sup> megjegyzést.

<sup>[2]</sup>A Windows Media Center TV Pack for Windows Vista kizárólag az eredeti berendezésgyártótól (OEM) beszerzett Windows Vista Home Premium és Ultimate kiadásaihoz elérhető, opcionális összetevőként. Ha telepítette rendszerére ezt az opcionális összetevőt, mindkét elérhető frissítést telepítse. A bevált gyakorlat azt mutatja, hogy érdemes előbb telepíteni az operációs rendszer frissítését (KB2479943), és csak azután a Windows Media Center TV Pack frissítését (KB2494132).

**Megjegyzések az MS11-017 közleményhez**

<sup>[1]</sup>A letöltött frissítés a Távoli asztali kapcsolat 6.0 ügyfélszoftvert a probléma által nem érintett 6.1 verzióra frissíti.

<sup>[2]</sup>A letöltött frissítés a Távoli asztali kapcsolat 6.0 ügyfélszoftver Multilingual User Interface (MUI) felületét a probléma által nem érintett 6.1 verzióra frissíti.

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
Microsoft Office programok
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS11-016**](http://go.microsoft.com/fwlink/?linkid=209774)
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
Microsoft Groove 2007
</td>
<td style="border:1px solid black;">
[Microsoft Groove 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3981ab53-1082-4155-9000-11d8a976ff33)  
(KB2494047)  
(Fontos)
</td>
</tr>
</table>
 

Észlelési és telepítési eszközök, útmutatás
-------------------------------------------

<span></span>
**Biztonsági központ**

A szoftveres és biztonsági frissítések kezeléséhez azokat a szervezet asztali és hordozható számítógépeire, valamint kiszolgálóira is telepíteni kell. További tájékoztatásért látogasson el a [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) weboldalára. A [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) bővebb tájékoztatással szolgál a Microsoft-termékek biztonsági funkcióival kapcsolatban. A [Biztonság otthon](http://go.microsoft.com/fwlink/?linkid=85102) weboldalon a megfelelő hivatkozásra kattintva elérhetőek a legújabb biztonsági frissítések.

A biztonsági frissítések a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) és a [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) weboldalról tölthetők le. A biztonsági frissítések a [Microsoft letöltőközpontjában](http://go.microsoft.com/fwlink/?linkid=21129) is elérhetőek. Legegyszerűbben a „security update” kifejezésre irányuló kulcsszavas kereséssel találhatja meg ezeket.

A Microsoft Office for Mac felhasználói számára a Microsoft AutoUpdate for Mac szolgáltatás biztosítja a Microsoft szoftverek naprakész állapotát. A Microsoft AutoUpdate for Mac működésének részleteiről lásd: [Szoftverfrissítések automatikus keresése](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

A biztonsági frissítések a [Microsoft Update katalógusából](http://go.microsoft.com/fwlink/?linkid=96155) is letölthetőek. A Microsoft Update katalógus a Windows Update és Microsoft Update szolgáltatáson keresztül elérhető tartalom kereshető adatbázisa; ide tartoznak a biztonsági frissítések, illesztőprogramok és szervizcsomagok. A biztonsági közlemény azonosítójára (pl. „MS07-036”) történő kereséssel hozzáadhatja az összes vonatkozó frissítést a kosárhoz (beleértve a frissítés különböző nyelvi változatait), és letöltheti azokat a megadott mappába. A Microsoft Update katalógus részletes leírását lásd a vonatkozó [GYIK](http://go.microsoft.com/fwlink/?linkid=97900)részben.

**Útmutató az észleléshez és a telepítéshez**

A biztonsági frissítésekkel kapcsolatban a Microsoft észlelési és telepítési segítséget nyújt. Ez az útmutató olyan javaslatokat és tudnivalókat tartalmaz, amelyeket segítséget nyújthatnak az informatikusoknak a biztonsági frissítések észlelési és telepítési eszközeinek használatához. További tudnivalókat a [Microsoft Tudásbázis 961747. számú cikkében](http://support.microsoft.com/kb/961747) talál.

**Microsoft Baseline Security Analyzer**

A Microsoft Baseline Security Analyzer (MBSA) segítségével a rendszergazda mind a helyi, mind a távoli számítógépeken ellenőrizheti, hogy mely biztonsági frissítések hiányoznak, illetve hogy mely biztonsági beállítások vannak helytelenül megadva. Ha többet szeretne tudni az MBSA -eszközről, látogasson el a [Microsoft Baseline Security Analyzer webhelyre](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

A Microsoft Server Update Services (WSUS) szolgáltatással a rendszergazdák gyorsan és megbízhatóan telepíthetik a legújabb fontos és biztonsági frissítéseket Microsoft Windows 2000 és újabb operációs rendszerekhez, Office XP és újabb operációs rendszerekhez, Exchange Server 2003 és SQL Server 2000 Microsoft Windows 2000 és újabb operációs rendszerekre.

A biztonsági frissítésnek Windows Server Update Services szolgáltatással történő központi telepítéséről a [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) webhelyen tudhat meg többet.

**System Center Configuration Manager 2007**

A Configuration Manager 2007 szoftverfrissítés-kezelés leegyszerűsíti a frissítéseknek a vállalat minden IT-rendszerére történő eljuttatása és kezelése összetett feladatát. A Configuration Manager 2007 segítségével az IT-rendszergazdák a Microsoft-termékek frissítéseit számos készülékre juttathatják el, köztük asztali számítógépekre, hordozható számítógépekre, kiszolgálókra és mobilkészülékekre.

A Configuration Manager 2007 automatizált biztonságirés-elemzése jelzi a frissítések szükségességét és jelentést küld a javasolt lépésekről. A Configuration Manager 2007 szoftverfrissítés-kezelése a Microsoft Windows Software Update Services (WSUS) szolgáltatására épül, amely az IT-rendszergazdák számára világszerte ismerős, jól bevált frissítési infrastruktúra. További információkat a Configuration Manager 2007 rendszergazdai használatáról a frissítések telepítéséhez lásd: [Szoftverfrissítés-kezelés](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). További információkért a Configuration Manager alkalmazásról látogasson el a [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx) oldalra.

**Systems Management Server 2003**

A Microsoft Systems Management Server (SMS) rendszer egy sokoldalúan beállítható vállalati megoldás, amely a frissítések kezelésére szolgál. Az SMS segítségével a rendszergazda megállapíthatja, hogy melyik Windows alapú számítógép szorul biztonsági frissítésre, és ezeket a frissítéseket szabályozott módon, a felhasználók minimális zavarásával központilag telepítheti a vállalat teljes informatikai környezetében.

**Megjegyzés** A System Management Server 2003 rendszer általános támogatása 2010. január 12-én lejár. Ha többet szeretne tudni a Windows termékek életciklusáról, keresse fel a [Microsoft támogatási életciklusokkal foglalkozó webhelyét](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Az SMS, vagyis a System Center Configuration Manager 2007 újabb kiadása már elérhető, lásd a korábbi, **System Center Configuration Manager 2007** c. részben.

Ha többet szeretne tudni arról, hogy a rendszergazdák miként telepíthetik a biztonsági frissítéseket az SMS 2003 alkalmazással, látogasson el a [Forgatókönyvek és eljárások a Microsoft Systems Management Server 2003 alkalmazáshoz Szoftverterjesztés és javításkezelés](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) oldalra. Az SMS-szolgáltatásról bővebben a [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx) oldalán olvashat.

**Megjegyzés** Az SMS a Microsoft Baseline Security Analyzer eszközön keresztül széles körű támogatást nyújt a biztonsági közlemények frissítéseinek észleléséhez, valamint a frissítések telepítéséhez. Előfordulhat, hogy egyes szoftverfrissítéseket ezek az eszközök nem észlelnek. Az SMS-alkalmazás leltározási szolgáltatásai segítségével a rendszergazdák adott rendszereken hajthatják végre a frissítést. Az eljárással kapcsolatban olvassa el a [szoftverfrissítések telepítése az SMS szoftverelosztó ügynök segítségével](http://go.microsoft.com/fwlink/?linkid=33341) című tájékoztatót. Egyes biztonsági frissítésekhez rendszergazdai jogosultságokra van szükség a számítógép újraindítása után. A rendszergazdák az Elevated Rights Deployment Tool eszközt (az [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en) része) alkalmazhatják a frissítések telepítéséhez.

**Az Update Compatibility Evaluator (a frissítéskompatibilitás kiértékelője) és az Application Compatibility Toolkit (alkalmazáskompatibilitási eszközkészlet)**

Az alkalmazások működése érdekében a frissítések gyakran írnak ugyanazokba a fájlokba, illetve regisztrációs bejegyzésekbe. Ez inkompatibilitást okozhat, és növelheti a biztonsági frissítések központi telepítésére használt időt. A Windows frissítések és az alkalmazásoknak való megfelelőség tesztelése és ellenőrzése egyszerűsíthető az [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) eszközeivel, ami része az [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=hu) alkalmazáskompatibilitási eszközkészletnek.

Az Application Compatibility Toolkit (ACT) tartalmazza a Microsoft Windows Vista, a Windows Update, a Microsoft Security Update vagy a Windows Internet Explorer új verziójának központi telepítése előtt az alkalmazáskompatibilitási problémák kiértékeléséhez és enyhítéséhez szükséges eszközöket és dokumentációt.

### Egyéb információ

#### A Microsoft Windows rosszindulatú szoftvereket eltávolító eszköze

A Microsoft a Windows Update, Microsoft Update, Windows Server Update Services és Letöltőközpont szolgáltatásán keresztül elérhetővé tette a Microsoft Windows rosszindulatú szoftvereket eltávolító eszközének frissített változatát.

#### Nem biztonsági jellegű frissítések a MU, WU és WSUS-szolgáltatásokban

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

-   Matthew Watchinski, [Sourcefire VRT](http://www.sourcefire.com/services/sf_vrt.html), az MS11-015 közleményben leírt probléma jelentéséért
-   HD Moore, [Rapid7,](http://www.rapid7.com/) az MS11-016 számú közleményben bemutatott probléma jelentéséért
-   Eyal Gruner, [Versafe Anti Fraud](http://www.versafe-login.com/), az MS11-017 közleményben ismertetett problémák egyikének jelentéséért

#### Terméktámogatás

-   Teszteléssel állapították meg a felsorolt szoftverek egyes verzióinak érintettségét. A többi verzió támogatási életciklusa végére ért. Az egyes szoftververziók támogatási életciklusáról a [Microsoft termékek terméktámogatási életciklusát ismertető webhelyen](http://go.microsoft.com/fwlink/?linkid=21742) talál felvilágosítást.
-   Az Amerikai Egyesült Államokban és Kanada területén élő ügyfelek technikai támogatást kérhetnek a [biztonsági támogatás szolgáltatójától](http://go.microsoft.com/fwlink/?linkid=21131) vagy az 1-866-PCSAFETY telefonszámon. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. Az elérhető támogatási lehetőségekről további információt talál a [Microsoft segítségnyújtással és támogatással foglalkozó webhelyén](http://support.microsoft.com/).
-   Más országokban a helyi Microsoft-képviseletek nyújtanak támogatást. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. A [nemzetközi támogatási webhely](http://go.microsoft.com/fwlink/?linkid=21155) felvilágosítást nyújt arról, támogatási kérdéseivel hogyan fordulhat a Microsofthoz.

#### Felelősséget kizáró nyilatkozat

A Microsoft Tudásbázisban leírtak előzetes bejelentés nélkül változhatnak, és a cikkek tartalmáért a Microsoft nem vállal garanciát. A Microsoft egyben elhárít minden kifejezett és értelemszerű garanciát, beleértve az eladhatóságra és az adott célra való alkalmasságra vonatkozó garanciát is. A Microsoft Corporation vagy annak szállítói semmilyen körülmények között nem tehetők felelőssé közvetlen, közvetett, eseti, ok-okozati vagy különleges kárért (beleértve az elmaradt hasznot is), még akkor sem, ha a Microsoft Corporation vagy szállítói tudatában voltak a kár lehetséges voltának. Egyes államok törvényi szabályozása nem teszi lehetővé a véletlen vagy ok-okozati károkért vállalt felelősség korlátozását vagy kizárását, így ezekben az államokban az ez a felelősségkizárás nincs érvényben.

#### Verziók

-   1.0 verzió (2011. március 8.): Összefoglaló közlemény közzététele.
-   1.1 verzió (2011. március 16.): Az MS11-015 közleményhez fűződő megjegyzések **Érintett szoftverek és letöltési helyek** részében hibásan, nem érintett rendszerként szerepelt a Windows XP Home Edition Service Pack 3 és Windows XP Tablet PC Edition Service Pack 3. Ezt most kijavítottuk. A módosítás csak tájékoztató jellegű. A biztonsági frissítéshez kapcsolódó fájlok és az észlelési logika nem változott. A Windows XP ezen kiadásainak olyan felhasználói számára, akik még nem alkalmazták a frissítést, a Microsoft a frissítés azonnali alkalmazását javasolja. Ha már alkalmazták a frissítést, nincs további teendő.

*Built at 2014-04-18T01:50:00Z-07:00*
