---
TOCTitle: 'MS09-NOV'
Title: 'Microsoft biztonsági közlemény - összefoglalás, november 2009'
ms:assetid: 'ms09-nov'
ms:contentKeyID: 61227735
ms:mtpsurl: 'https://technet.microsoft.com/hu-HU/library/ms09-nov(v=Security.10)'
author: SharonSears
ms.author: SharonSears
---

Security Bulletin Summary

Microsoft biztonsági közlemény - összefoglalás, november 2009
=============================================================

Közzétéve: 2009. november 10. | Frissítve: 2009. november 25.

**Verzió:** 1.1

Az összefoglaló a 2009 novemberében kiadott biztonsági közleményeket összegzi.

A 2009. novemberi közlemények kiadása folytán az összefoglaló a 2009. november 5-én kiadott előzetes értesítés helyébe lép. A biztonsági közlemények kiadásáról szóló előzetes értesítés szolgáltatásról itt olvashat bővebben: [Előzetes értesítés a Microsoft biztonsági közleményeinek kiadásáról](http://technet.microsoft.com/security/bulletin/advance).

Ha automatikus értesítést szeretne kapni a Microsoft biztonsági közleményeinek megjelenéséről, fizessen elő a [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) szolgáltatásra.

A közleményekkel kapcsolatos kérdések megválaszolására a Microsoft 2009. november 11-én, csendes-óceáni idő szerint 11 órakor webes szemináriumot tart. [Jelentkezzen most a novemberi közleményeket bemutató webes szemináriumra](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032407490&culture=en-us). Ezt követően a webes szeminárium igény szerint kerül megrendezésre. További információkért látogasson el a [Microsoft biztonsági közleményeit és a webes szemináriumokat](http://technet.microsoft.com/security/bulletin/summary)bemutató oldalra.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163840">MS09-063</a></td>
<td style="border:1px solid black;"><strong>A Web Services on Devices alkalmazásfejlesztői felületének biztonsági rése távolról történő kódfuttatást tesz lehetővé (973565)</strong><br />
<br />
A biztonsági frissítés a Windows operációs rendszerben a Web Services on Devices alkalmazásfejlesztői felületének (WSDAPI) közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rés programkódok távolról történő futtatását teszi lehetővé, ha az érintett Windows rendszer speciálisan kialakított csomagot kap. Csak a helyi alhálózat támadói használhatják ki ezt a biztonsági rést.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163841">MS09-064</a></td>
<td style="border:1px solid black;"><strong>A licencnaplózási szolgáltatás biztonsági rése távolról történő kódfuttatást tesz lehetővé (974783)</strong><br />
<br />
Ez a biztonsági frissítés a Microsoft Windows 2000 rendszer egy közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rés távoli kódfuttatást tesz lehetővé, ha a támadó speciálisan kialakított hálózati üzenetet küld a licencnaplózási szolgáltatást futtató számítógépre. A biztonsági rést sikeresen kihasználó támadó teljes mértékben átveheti az érintett rendszer irányítását. A tűzfalakra vonatkozó gyakorlati tanácsok, valamint a szabványos alapértelmezett tűzfal-konfigurációk segítséget nyújtanak a hálózatot érő, a szervezet határain kívülről eredő támadások kivédésében.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=162428">MS09-065</a></td>
<td style="border:1px solid black;"><strong>A kernel módú Windows illesztőprogramok biztonsági rései távoli programkódfuttatásra adhatnak lehetőséget (969947)</strong><br />
<br />
A biztonsági frissítés a Windows rendszermag számos, közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rések legsúlyosabbjai távoli kódfuttatást tesznek lehetővé, ha a felhasználó speciálisan kialakított beágyazott OpenType (EOT) betűtípusban megjelenített tartalmat tekint meg. Internetes támadás esetén a támadónak olyan webhelyet kell üzemeltetnie, amely a biztonsági rés kihasználását lehetővé tevő, erre a célra kialakított beágyazott betűtípusokat tartalmaz. Az érintett weboldalak és a felhasználó által biztosított tartalomnak, esetleg hirdetéseknek helyet adó weboldalak is tartalmazhatnak a biztonsági rést kihasználni képes különlegesen kialakított tartalmat. A támadónak nincs lehetősége arra, hogy a felhasználót a különlegesen kialakított webhely megnyitására kényszerítse. Ehelyett a támadóknak saját webhelyükre kell csábítaniuk a felhasználót, ezt pedig rendszerint úgy érik el, hogy ráveszik a felhasználókat arra, hogy kattintson rá egy e-mailben lévő hivatkozásra vagy azonnali üzenetkezelőben megjelenő kérésre.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=157862">MS09-066</a></td>
<td style="border:1px solid black;"><strong>Az Active Directory biztonsági rése szolgáltatásmegtagadást okozhat (973309)</strong><br />
<br />
A biztonsági frissítés az Active Directory címtárszolgáltatás, az Alkalmazásmódú Active Directory (ADAM) és az Active Directory Lightweight Directory-szolgáltatás (AD LDS) közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rés szolgáltatásmegtagadást okozhat, ha bizonyos típusú LDAP- vagy LDAPS-kérelmek végrehajtása során a veremtár kimerül. A biztonsági rés csak a tartományvezérlőket, illetve az ADAM vagy AD LDS futtatásához konfigurált rendszereket érinti.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Szolgáltatásmegtagadás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=165431">MS09-067</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Office Excel biztonsági rései távolról történő programkódfuttatást tehetnek lehetővé (972652)</strong><br />
<br />
A biztonsági frissítés a Microsoft Office Excel számos, közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rések távoli kódvégrehajtást tehetnek lehetővé, amennyiben a felhasználó egy speciálisan kialakított Excel fájlt nyit meg. A biztonsági rések valamelyikét sikeresen kihasználó támadó a helyi felhasználóval egyező hozzáférést nyer a rendszerhez. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=165890">MS09-068</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Office Word biztonsági rése távoli kódfuttatást tehet lehetővé (976307)</strong><br />
<br />
A biztonsági frissítés egy, közvetlenül a Microsoftnak jelzett biztonsági rést szüntet meg, amely távoli kódfuttatást tesz lehetővé, amennyiben a felhasználó megnyit egy speciálisan létrehozott Word fájlt. Ha egy támadó kihasználja a biztonsági rést, teljes mértékben átveheti a rendszer irányítását. Ezt követően a támadó programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
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
  
| Közlemény azonosítója                                     | A biztonsági rés címe                                                                                 | CVE-azonosító                                                                    | Kihasználhatósági információk értékelése                                                                                 | Fontos megjegyzések                                                                                                                   |  
|-----------------------------------------------------------|-------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-063](http://go.microsoft.com/fwlink/?linkid=163840) | A Web Services on Devices alkalmazásfejlesztői felületének memóriameghibásodást okozó biztonsági rése | [CVE-2009-2512](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2512) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | Az eset korlátozott szolgáltatásmegtagadást okozó támadást tesz lehetővé.                                                             |  
| [MS09-064](http://go.microsoft.com/fwlink/?linkid=163841) | A Licencnaplózó szolgáltatás halomtúlcsordulást okozó biztonsági rése                                 | [CVE-2009-2523](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2523) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | A támadás egy nehezen kihasználható feltételen alapul. A szolgáltatásmegtagadáson kívüli támadások nem jelentenek komoly fenyegetést. |  
| [MS09-065](http://go.microsoft.com/fwlink/?linkid=162428) | A Win32k NULL mutatója visszakeresési biztonsági rése                                                 | [CVE-2009-1127](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1127) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                                                                                               |  
| [MS09-065](http://go.microsoft.com/fwlink/?linkid=162428) | A Win32k elégtelen adatérvényesítés miatti biztonsági rése                                            | [CVE-2009-2513](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2513) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                                               |  
| [MS09-065](http://go.microsoft.com/fwlink/?linkid=162428) | A Win32k EOT-elemzés miatti biztonsági rése                                                           | [CVE-2009-2514](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2514) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                                               |  
| [MS09-066](http://go.microsoft.com/fwlink/?linkid=157862) | Az LSASS kötegtúlcsordulást okozó rekurzív biztonsági rése                                            | [CVE-2009-1928](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1928) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nem valószínű működő rosszindulatú programkód       | Fennáll a szolgáltatásmegtagadás lehetősége.                                                                                          |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Az Excel gyorsítótár-memória meghibásodást okozó biztonsági rése                                      | [CVE-2009-3127](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3127) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                                                                                               |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Az Excel SxView memóriameghibásodást okozó biztonsági rése                                            | [CVE-2009-3128](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3128) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                                                                                               |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Az Excel Featheader bejegyzés miatti memóriameghibásodást okozó biztonsági rése                       | [CVE-2009-3129](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3129) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                                               |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Az Excel dokumentumelemzés miatti halomtúlcsordulást okozó biztonsági rése                            | [CVE-2009-3130](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3130) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                                               |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Az Excel képletelemzés miatti memóriameghibásodást okozó biztonsági rése                              | [CVE-2009-3131](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3131) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                                               |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Az Excel indexelemzés miatti biztonsági rése                                                          | [CVE-2009-3132](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3132) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                                                                                               |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Az Excel dokumentumelemzés miatti memóriameghibásodást okozó biztonsági rése                          | [CVE-2009-3133](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3133) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                                                                                               |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Az Excel mezőtörlés miatti biztonsági rése                                                            | [CVE-2009-3134](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3134) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                                                                                               |  
| [MS09-068](http://go.microsoft.com/fwlink/?linkid=165890) | A Microsoft Office Word fájlinformációinak memóriameghibásodást okozó biztonsági rése                 | [CVE-2009-3135](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3135) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                                                                                               |
  
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
</tr>
<tr>
<th colspan="5">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-063**](http://go.microsoft.com/fwlink/?linkid=163840)
</td>
<td style="border:1px solid black;">
[**MS09-064**](http://go.microsoft.com/fwlink/?linkid=163841)
</td>
<td style="border:1px solid black;">
[**MS09-065**](http://go.microsoft.com/fwlink/?linkid=162428)
</td>
<td style="border:1px solid black;">
[**MS09-066**](http://go.microsoft.com/fwlink/?linkid=157862)
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
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=365a8dff-2383-42f6-b567-e545461fd135)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=45db8bb1-c81b-4d3f-a658-74f5fa445f81)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Active Directory Microsoft Windows 2000 Server Service Pack 4 rendszeren](http://www.microsoft.com/downloads/details.aspx?familyid=297158cf-374c-45d9-b213-978e1f54d244)  
(KB973037)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="5">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-063**](http://go.microsoft.com/fwlink/?linkid=163840)
</td>
<td style="border:1px solid black;">
[**MS09-064**](http://go.microsoft.com/fwlink/?linkid=163841)
</td>
<td style="border:1px solid black;">
[**MS09-065**](http://go.microsoft.com/fwlink/?linkid=162428)
</td>
<td style="border:1px solid black;">
[**MS09-066**](http://go.microsoft.com/fwlink/?linkid=157862)
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
Nincsenek
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
Windows XP Service Pack 2 és Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 és Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=916abdad-44b7-4f9d-986a-0c3558fb8e06)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Alkalmazásmódú Active Directory (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=cbe09780-f288-457a-b254-58c9c8744055)  
(KB973039)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1d0464c6-5ed8-4064-887e-618a2db09236)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Alkalmazásmódú Active Directory (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=b65ddf36-a02d-4aa2-9b4f-7416dbf59e2a)  
(KB973039)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-063**](http://go.microsoft.com/fwlink/?linkid=163840)
</td>
<td style="border:1px solid black;">
[**MS09-064**](http://go.microsoft.com/fwlink/?linkid=163841)
</td>
<td style="border:1px solid black;">
[**MS09-065**](http://go.microsoft.com/fwlink/?linkid=162428)
</td>
<td style="border:1px solid black;">
[**MS09-066**](http://go.microsoft.com/fwlink/?linkid=157862)
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
Nincsenek
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5cd62750-e269-44ae-8c7c-c335e8545b9a)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=28f1c494-4e16-43b6-93d2-49e15f142ac9)  
(KB973037)  
(Fontos)  
[Alkalmazásmódú Active Directory (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=44cb9029-4b19-4bad-8fc9-3efe285adb0e)  
(KB973039)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=04a7f817-f330-4003-8b25-d3e744905b12)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=509aeec0-112b-44ab-8686-43f381b61940)  
(KB973037)  
(Fontos)  
[Alkalmazásmódú Active Directory (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=87f2109e-5129-467c-930f-70af31ebf5de)  
(KB973039)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP2 for Itanium-based Systems
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 javítócsomaggal Itanium alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=b95daac0-4c99-47a4-b0ca-9429997ea3d9)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?familyid=040e691b-1ef0-4b73-bef7-a1d77b84b0ca)  
(KB973037)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="5">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-063**](http://go.microsoft.com/fwlink/?linkid=163840)
</td>
<td style="border:1px solid black;">
[**MS09-064**](http://go.microsoft.com/fwlink/?linkid=163841)
</td>
<td style="border:1px solid black;">
[**MS09-065**](http://go.microsoft.com/fwlink/?linkid=162428)
</td>
<td style="border:1px solid black;">
[**MS09-066**](http://go.microsoft.com/fwlink/?linkid=157862)
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
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows Vista, Windows Vista Service Pack 1, és Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ebf0c294-cd99-445a-a741-78253e47189f)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1, és Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=54562103-1d99-42d7-8f7f-c0cbcdce90db)  
(Fontos)
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
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 és Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d9645fc9-f524-43f1-8b8c-94b3b4312158)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 és Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fcb87cc8-6fd7-4f16-93d6-552999462fb1)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="5">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS09-063**](http://go.microsoft.com/fwlink/?linkid=163840)
</td>
<td style="border:1px solid black;">
[**MS09-064**](http://go.microsoft.com/fwlink/?linkid=163841)
</td>
<td style="border:1px solid black;">
[**MS09-065**](http://go.microsoft.com/fwlink/?linkid=162428)
</td>
<td style="border:1px solid black;">
[**MS09-066**](http://go.microsoft.com/fwlink/?linkid=157862)
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
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[Windows Server 2008 32 bites rendszerekhez és Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d6a60883-b103-459a-a91b-cd6ed946cefe)\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez és Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b97d48de-0f6d-4bca-b990-acf543fdb8b7)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
[Active Directory és Active Directory Lightweight Directory-szolgáltatás (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=701abf15-7f93-41de-8d09-13404fd79a7e)\*  
(KB973037)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 x64 alapú rendszerekhez és Windows Server 2008 x64 alapú rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64 alapú rendszerekhez és Windows Server 2008 x64 alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3dde1587-42d3-438f-8344-696a5657b9b1)\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64 alapú rendszerekhez és Windows Server 2008 x64 alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0e2b8607-10fa-406a-96a5-18290f479c48)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
[Active Directory és Active Directory Lightweight Directory-szolgáltatás (AD LDS)](http://www.microsoft.com/downloads/details.aspx?familyid=17f5f9e0-5869-41da-9b3b-6e67540af1f0)\*  
(KB973037)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Itanium alapú rendszerekhez és Windows Server 2008 Itanium alapú rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 Itanium alapú rendszerekhez és Windows Server 2008 Itanium alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=841a027f-22fa-42de-93b3-57a3fe92a1d3)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 Itanium alapú rendszerekhez és Windows Server 2008 Itanium alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=28eba3f3-99a5-424c-bc8d-a718c716699e)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
</table>
 
**Megjegyzések a Windows Server 2008 és Windows Server 2008 R2 rendszerhez**

**\*Érinti a kiszolgálómag telepítését.** Ez a frissítés ugyanolyan biztonsági besorolás mellett, a megadottak szerint érvényes az Windows Server 2008 és a Windows Server 2008 R2 összes támogatott kiadására, függetlenül attól, hogy a kiszolgálómag-telepítési opcióval telepítették-e. Erről a telepítési opcióról bővebben a [Kiszolgálómag](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) és a [Kiszolgálómag a Windows Server 2008 R2 rendszerhez](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx) MSDN-cikkekben olvashat. A kiszolgálómag-telepítési opció nem vonatkozik a Windows Server 2008 és a Windows Server 2008 R2 bizonyos kiadásaira; lásd: [A kiszolgálómag-telepítési opciók összehasonlítása](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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
[**MS09-067**](http://go.microsoft.com/fwlink/?linkid=165431)
</td>
<td style="border:1px solid black;">
[**MS09-068**](http://go.microsoft.com/fwlink/?linkid=165890)
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
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=5672c8fc-8509-4962-ad86-ebc0f2575043)  
(KB973471)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0369fae5-958b-4eba-83a4-9c07e701c273)  
(KB973444)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6a6a0f5d-17dc-4a34-b9a0-0774aa287ba5)  
(KB973475)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6b77bc62-bcbb-4b9a-97d1-a49ca0582e54)  
(KB973443)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office rendszer
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1 és Microsoft Office Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=322b24ca-aff6-4ca0-acf1-440cae0f9693)<sup>[1]</sup>
(KB973593)  
(Fontos)
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
[**MS09-067**](http://go.microsoft.com/fwlink/?linkid=165431)
</td>
<td style="border:1px solid black;">
[**MS09-068**](http://go.microsoft.com/fwlink/?linkid=165890)
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
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=8f115b1c-1e28-4ecf-937c-99c4b60c7c8e)  
(KB976830)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=8f115b1c-1e28-4ecf-937c-99c4b60c7c8e)  
(KB976830)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=b84fe57d-ddda-451e-9ead-69e10aee7928)  
(KB976828)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=b84fe57d-ddda-451e-9ead-69e10aee7928)  
(KB976828)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=4dd4bc05-1217-497e-8f65-4347f2544ed6)  
(KB976831)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=4dd4bc05-1217-497e-8f65-4347f2544ed6)  
(KB976831)  
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
[**MS09-067**](http://go.microsoft.com/fwlink/?linkid=165431)
</td>
<td style="border:1px solid black;">
[**MS09-068**](http://go.microsoft.com/fwlink/?linkid=165890)
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
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel Viewer 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=19151e22-5642-456c-bd39-298574369cdb)  
(KB973484)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer Service Pack 1 és Microsoft Office Excel Viewer Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=fb36df5e-ebef-46bf-9edd-67f2c76dbdb3)  
(KB973707)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer 2003
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=4cc5e6c5-7efb-4180-9a9b-0788115c91e1)  
(KB973866)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=4cc5e6c5-7efb-4180-9a9b-0788115c91e1)  
(KB973866)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office kompatibilitási csomag a Word, Excel és PowerPoint 2007 fájlformátumokhoz
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 1 valamint Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c4c92d2e-e87d-446f-8d3e-8f4be10c70aa)  
(KB973704)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
</table>
 
**Megjegyzés az MS09-067 közleményhez**

<sup>[1]</sup>Microsoft Office Excel 2007 Service Pack 1 és Microsoft Office Excel 2007 Service Pack 2 esetén a felhasználóknak a KB973593 frissítésen kívül telepíteniük kell a [Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 1 és a Microsoft Office Compatibility Pack for Word, Excel, and PowerPoint 2007 File Formats Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c4c92d2e-e87d-446f-8d3e-8f4be10c70aa) (KB973704) frissítést is, hogy megvédjék rendszerüket a jelen közleményben ismertetett biztonsági rések hatásától.

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

-   Neel Mehta, [Google Inc.](http://www.google.com/), az MS09-063 közleményben bemutatott probléma jelentéséért
-   Cody Pierce, [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/), az MS09-064 közleményben ismertetett probléma jelentéséért
-   Agin Sun, az MS09-065 közleményben bemutatott probléma jelentéséért
-   Tavis Ormandy, [Google Inc.](http://www.google.com/), az MS09-065 közleményben bemutatott probléma jelentéséért
-   Bing Liu, [Fortinet FortiGuard Labs](http://www.fortiguard.com/), az MS09-067 számú közleményben ismertetett három probléma jelentéséért
-   [TippingPoint](http://www.tippingpoint.com/) és [Zero Day Initiative](http://www.zerodayinitiative.com/), az MS09-067 közleményben ismertetett egyik probléma jelentéséért
-   Sean Larsson, [VeriSign iDefense Labs](http://labs.idefense.com/), az MS09-067 közleményben bemutatott két probléma jelentéséért
-   A [Tipping Point](http://www.tippingpoint.com/) és [Zero Day Initiative](http://www.zerodayinitiative.com/) cégekkel együttműködő anonim kutató, az MS09-067 közleményben leírt probléma jelentéséért.
-   Nicolas Joly, [VUPEN Security](http://www.vupen.com/), az MS09-067 közleményben bemutatott négy probléma jelentéséért
-   Jun Mao, [VeriSign iDefense Labs](http://labs.idefense.com/), az MS09-068 közleményben ismertetett egyik probléma jelentéséért

#### Terméktámogatás

-   Teszteléssel állapították meg a felsorolt szoftverek egyes verzióinak érintettségét. A többi verzió támogatási életciklusa végére ért. Az egyes szoftververziók támogatási életciklusáról a [Microsoft termékek terméktámogatási életciklusát ismertető webhelyen](http://go.microsoft.com/fwlink/?linkid=21742) talál felvilágosítást.
-   Az Amerikai Egyesült Államokban és Kanada területén élő ügyfelek technikai támogatást kérhetnek a [biztonsági támogatás szolgáltatójától](http://go.microsoft.com/fwlink/?linkid=21131) vagy az 1-866-PCSAFETY telefonszámon. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. Az elérhető támogatási lehetőségekről további információt talál a [Microsoft segítségnyújtással és támogatással foglalkozó webhelyén](http://support.microsoft.com/).
-   Más országokban a helyi Microsoft-képviseletek nyújtanak támogatást. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. A [nemzetközi támogatási webhely](http://go.microsoft.com/fwlink/?linkid=21155) felvilágosítást nyújt arról, támogatási kérdéseivel hogyan fordulhat a Microsofthoz.

#### Felelősséget kizáró nyilatkozat

A Microsoft Tudásbázisban leírtak előzetes bejelentés nélkül változhatnak, és a cikkek tartalmáért a Microsoft nem vállal garanciát. A Microsoft egyben elhárít minden kifejezett és értelemszerű garanciát, beleértve az eladhatóságra és az adott célra való alkalmasságra vonatkozó garanciát is. A Microsoft Corporation vagy annak szállítói semmilyen körülmények között nem tehetők felelőssé közvetlen, közvetett, eseti, ok-okozati vagy különleges kárért (beleértve az elmaradt hasznot is), még akkor sem, ha a Microsoft Corporation vagy szállítói tudatában voltak a kár lehetséges voltának. Egyes államok törvényi szabályozása nem teszi lehetővé a véletlen vagy ok-okozati károkért vállalt felelősség korlátozását vagy kizárását, így ezekben az államokban az ez a felelősségkizárás nincs érvényben.

#### Verziók

-   1.0 verzió (2009. november 10.): Összefoglaló közlemény közzététele.
-   1.1 verzió (2009. november 25.): A CVE-2009-2523 kihasználhatósági tudnivalói új elemmel bővültek.

*Built at 2014-04-18T01:50:00Z-07:00*
