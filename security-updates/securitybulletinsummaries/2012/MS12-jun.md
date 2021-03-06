---
TOCTitle: 'MS12-JUN'
Title: 'A Microsoft biztonsági közleményei – összefoglalás, 2012. június'
ms:assetid: 'ms12-jun'
ms:contentKeyID: 61227766
ms:mtpsurl: 'https://technet.microsoft.com/hu-HU/library/ms12-jun(v=Security.10)'
author: SharonSears
ms.author: SharonSears
---

Security Bulletin Summary

A Microsoft biztonsági közleményei – összefoglalás, 2012. június
================================================================

Közzétéve: 2012. június 12.

**Verzió:** 1.0

Az összefoglaló a 2012 júniusára kiadott biztonsági közleményeket összegzi.

A 2012. júniusi biztonsági közlemények kiadása folytán az összefoglaló a 2012. június 7-én kiadott előzetes értesítés helyébe lép. További információk a biztonsági közlemények kiadásáról szóló előzetes értesítés szolgáltatásról lásd: [Előzetes értesítés a Microsoft biztonsági közleményeinek kiadásáról](http://go.microsoft.com/fwlink/?linkid=217213).

Ha automatikus értesítést szeretne kapni a Microsoft biztonsági közleményeinek megjelenéséről, fizessen elő a [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) szolgáltatásra.

A közleményekkel kapcsolatos kérdések megválaszolására a Microsoft 2012. június 13-án, csendes-óceáni idő szerint 11 órakor webes szemináriumot tart. [Jelentkezzen most a júniusi közleményeket bemutató webes szemináriumra](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499671). Ezt követően a webes szeminárium igény szerint kerül megrendezésre. További információkért látogasson el a [Microsoft biztonsági közleményeit és a webes szemináriumokat](http://go.microsoft.com/fwlink/?linkid=217214) bemutató oldalra.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=246927"><strong>MS12-036</strong></a></td>
<td style="border:1px solid black;"><strong>A Távoli asztal biztonsági rése távoli kódfuttatást tehet lehetővé (2685939)</strong><br />
<br />
A biztonsági frissítés a Remote Desktop Protocol közvetlenül jelzett biztonsági rését szünteti meg. A biztonsági rés távoli kódfuttatást tehet lehetővé, ha a támadó különlegesen kialakított RDP-csomagsorozatot küld az érintett rendszerre. Alapértelmezés szerint a Remote Desktop Protocol (RDP) protokoll nem engedélyezett egyik Windows operációs rendszeren sem. Azok a rendszerek, amelyeknél az RDP nem engedélyezett, nem veszélyeztettek.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td style="border:1px solid black;"><strong>Összesítő biztonsági frissítés az Internet Explorerhez (2699988)</strong><br />
<br />
A biztonsági frissítés egy nyilvánosan és tizenkét közvetlenül jelentett biztonsági rést szüntet meg az Internet Explorer programban. A súlyosabb biztonsági rések távoli kódfuttatást tesznek lehetővé, amennyiben a felhasználó speciálisan kialakított weboldalt tekint meg az Internet Explorer alkalmazással. A biztonsági rések valamelyikét sikeresen kihasználó támadó az aktuális felhasználóval egyező hozzáférést nyer a rendszerhez. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251095"><strong>MS12-038</strong></a></td>
<td style="border:1px solid black;"><strong>A .NET Framework biztonsági rése távoli programkódfuttatást tehet lehetővé (2706726)</strong><br />
<br />
A biztonsági frissítés a Microsoft .NET Framework egy közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rés távoli kódfuttatást tehet lehetővé az ügyfélrendszereken, ha a felhasználó különlegesen kialakított weboldalt tekint meg az XAML böngészőalkalmazások (XBAP alkalmazások) futtatására alkalmas böngészőben. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén A biztonsági rés a Windows .NET alkalmazásokban is kihasználható a kódműködési biztonsági (CAS) korlátozások megkerülésére. Webböngészős támadási forgatókönyv esetén a támadónak olyan webhelyet kell üzemeltetnie, amely a biztonsági rés kihasználását lehetővé tevő weblapot tartalmaz. Az érintett weboldalak és a felhasználó által biztosított tartalomnak, esetleg hirdetéseknek helyet adó weboldalak és hirdetések is tartalmazhatnak a biztonsági rést kihasználni képes, különlegesen kialakított tartalmat. A támadóknak azonban nem áll módjukban, hogy a felhasználókat ezen weboldalak megtekintésére kényszerítsék. Ehelyett a támadóknak az adott webhelyre kell csábítaniuk a felhasználókat. Ezt rendszerint úgy érik el, hogy ráveszik őket arra, hogy kattintsanak rá egy e-mailben lévő hivatkozásra vagy azonnali üzenetkezelőben megjelenő kérésre.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td style="border:1px solid black;"><strong>A <strong>Lync</strong> alkalmazás <strong>biztonsági rései</strong> távolról történő kódfuttatást tesznek lehetővé (2707956)</strong><br />
<br />
Ez a biztonsági frissítés egy nyilvánosságra került és három közvetlenül jelentett biztonsági rést szüntet meg a Microsoft Lync alkalmazásban. A legsúlyosabb biztonsági rések távoli kódfuttatást tesznek lehetővé, amennyiben a felhasználó speciálisan kialakított TrueType betűkészletet tartalmazó megosztott tartalmat tekint meg.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Lync</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251612"><strong>MS12-040</strong></a></td>
<td style="border:1px solid black;"><strong>A Microsoft Dynamics AX Enterprise Portal biztonsági rése jogok kiterjesztését teheti lehetővé (2709100)</strong><br />
<br />
A biztonsági frissítés a Microsoft Dynamics AX Enterprise Portal egy közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rés jogok kiterjesztését teheti lehetővé, ha a felhasználó egy speciálisan kialakított URL-címre kattint, vagy meglátogat egy speciálisan kialakított webhelyet. E-mailes támadás esetén a támadó kihasználhatja a biztonsági rést, ha e-mail üzenetben elküldi a speciálisan létrehozott URL-címet a támadással megcélzott Microsoft Dynamics AX Enterprise Portal oldal felhasználójának, és ráveszi a felhasználót, hogy kattintson rá arra. Az Internet Explorer 8 és az Internet Explorer 9 felhasználói a Microsoft Dynamics AX Enterprise Portal oldalak Internet zónában történő böngészésekor kevésbé veszélyeztetettek. Az Internet Explorer 8 és az Internet Explorer 9 alkalmazás XSS-szűrője az Internet zónában alapértelmezés szerint megakadályozza ezt a támadást. Az Internet Explorer 8 és az Internet Explorer 9 alkalmazás XSS-szűrője azonban az Intranet zónában alapértelmezés szerint nem engedélyezett.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Jogok kiterjesztése</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Dynamics AX</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td style="border:1px solid black;"><strong>A Windows kernelmódú illesztőprogramjainak biztonsági rései jogok kiterjesztéséhez vezethetnek (2709162)</strong><br />
<br />
A biztonsági frissítés a Microsoft Windows öt közvetlenül jelzett biztonsági rését szünteti meg. A biztonsági rések jogok kiterjesztését tehetik lehetővé, ha a támadó bejelentkezik a rendszerre, és ott speciálisan kialakított alkalmazást futtat. A támadónak bármely biztonsági rés kihasználásához érvényes bejelentkezési adatokkal kell rendelkeznie, és képesnek kell lennie helyileg bejelentkezni a rendszerbe.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Jogok kiterjesztése</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=252515"><strong>MS12-042</strong></a></td>
<td style="border:1px solid black;"><strong>A Windows Kernel biztonsági rései illetéktelen jogosultságmegszerzést eredményezhetnek (2711167)</strong><br />
<br />
Ez a biztonsági frissítés egy közvetlenül jelentett és egy nyilvánosságra került biztonsági rést szüntet meg a Microsoft Windows rendszerben. A biztonsági rések a jogok kiterjesztését tehetik lehetővé, ha a támadó bejelentkezik az érintett rendszerre, és ott a biztonsági rést kihasználó, különlegesen kialakított alkalmazást futtat. A támadónak a biztonsági rés kihasználásához érvényes bejelentkezési adatokkal kell rendelkeznie, és képesnek kell lennie helyileg bejelentkezni a rendszerbe. Névtelen felhasználók nem tudják távolról kiaknázni ezt a biztonsági rést.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Jogok kiterjesztése</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Kihasználhatósági információk  
-----------------------------
  
<span></span>
A következő táblázat az adott hónapban megoldott biztonsági rések kihasználhatósági jellemzőit ismerteti. A biztonsági rések a közlemény azonosítója és súlyossági besorolás azonosítója szerint vannak felsorolva. Csak a kritikus és fontos besorolású biztonsági rések szerepelnek.
  
**A táblázat használata**
  
Az alábbi táblázatból minden telepítendő biztonsági frissítésről megtudhatja, hogy mekkora a valószínűsége annak, hogy a biztonsági közlemény kiadása után 30 napon belül kódvégrehajtási és szolgáltatásmegtagadási támadások jelenhetnek meg. A havi frissítések telepítési sorrendjének meghatározásához, az adott konfigurációnak megfelelően tekintse át az alábbi értékeléseket. A minősítések jelentéséről és meghatározásuk módjáról a [Microsoft kihasználhatósági információk](http://technet.microsoft.com/security/cc998259.aspx) című rész tartalmaz bővebb információt.
  
Az alábbi oszlopokban a „legújabb szoftver” kifejezés az adott szoftver legutóbb kiadott változatára vonatkozik, a „korábbi szoftver” kifejezés az adott szoftver valamennyi, korábban kiadott támogatott verziójára vonatkozik, amint az az érintett vagy a nem érintett szoftverek felsorolásában szerepel.
  
| Közlemény azonosítója                                         | A biztonsági rés címe                                                                  | CVE-azonosító                                                                    | Kihasználhatóság felmérése a legújabb szoftvereknél                                                              | Kihasználhatóság felmérése a korábbi szoftvereknél                                                               | Szolgáltatásmegtagadás kihasználhatóságának felmérése | Fontos megjegyzések                                                                                                                                             |  
|---------------------------------------------------------------|----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [**MS12-036**](http://go.microsoft.com/fwlink/?linkid=246927) | Remote Desktop Protocol biztonsági rése                                                | [CVE-2012-0173](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0173) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Állandó                                               | (Nincs)                                                                                                                                                         |  
| [**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045) | A középpont elem távoli kódfuttatást lehetővé tevő biztonsági rése                     | [CVE-2012-1523](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1523) | Nem érintett                                                                                                     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Ideiglenes                                            | (Nincs)                                                                                                                                                         |  
| [**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045) | HTML-törlés miatti biztonsági rés                                                      | [CVE-2012-1858](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nem valószínű rosszindulatú programkód          | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nem valószínű rosszindulatú programkód          | Nem érintett                                          | A biztonsági rés illetéktelen adatelérést okoz. Az [MS12-039](http://go.microsoft.com/fwlink/?linkid=252488) közlemény szintén foglalkozik a biztonsági réssel. |  
| [**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045) | A NULL bájt adatokhoz való illetéktelen hozzáférést okozó biztonsági rése              | [CVE-2012-1873](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1873) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nem valószínű rosszindulatú programkód          | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nem valószínű rosszindulatú programkód          | Nem érintett                                          | A biztonsági rés illetéktelen adatelérést okoz.                                                                                                                 |  
| [**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045) | A fejlesztői eszköztár távoli kódfuttatást lehetővé tevő biztonsági rése               | [CVE-2012-1874](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1874) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nem valószínű rosszindulatú programkód          | Ideiglenes                                            | (Nincs)                                                                                                                                                         |  
| [**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045) | Egyező azonosító tulajdonság távoli kódfuttatást lehetővé tevő biztonsági rése         | [CVE-2012-1875](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1875) | Nem érintett                                                                                                     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Ideiglenes                                            | A Microsoft értesült a biztonsági rés kihasználására törekvő, korlátozott mértékű támadásokról.                                                                 |  
| [**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045) | Az oszlop elem távoli kódfuttatást lehetővé tevő biztonsági rése                       | [CVE-2012-1876](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1876) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Ideiglenes                                            | (Nincs)                                                                                                                                                         |  
| [**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045) | A cím elem módosítása miatti, távoli kódfuttatást lehetővé tevő biztonsági rés         | [CVE-2012-1877](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1877) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Ideiglenes                                            | (Nincs)                                                                                                                                                         |  
| [**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045) | Az OnBeforeDeactivate esemény távoli kódfuttatást lehetővé tevő biztonsági rése        | [CVE-2012-1878](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1878) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Ideiglenes                                            | (Nincs)                                                                                                                                                         |  
| [**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045) | Az insertAdjacentText függvény távoli kódfuttatást lehetővé tévő biztonsági rése       | [CVE-2012-1879](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1879) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Ideiglenes                                            | (Nincs)                                                                                                                                                         |  
| [**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045) | Az insertRow függvény távoli kódfuttatást lehetővé tevő biztonsági rése                | [CVE-2012-1880](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1880) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Ideiglenes                                            | (Nincs)                                                                                                                                                         |  
| [**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045) | Az OnRowsInserted esemény távoli kódfuttatást lehetővé tevő biztonsági rése            | [CVE-2012-1881](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1881) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Ideiglenes                                            | (Nincs)                                                                                                                                                         |  
| [**MS12-038**](http://go.microsoft.com/fwlink/?linkid=251095) | A .NET keretrendszer memória-hozzáférés miatti biztonsági rése                         | [CVE-2012-1855](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1855) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Nem érintett                                          | (Nincs)                                                                                                                                                         |  
| [**MS12-039**](http://go.microsoft.com/fwlink/?linkid=252488) | TrueType betűtípus-elemzés biztonsági rése                                             | [CVE-2011-3402](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nem valószínű rosszindulatú programkód          | Nem érintett                                                                                                     | Állandó                                               | A biztonsági rés nyilvánosságra került,                                                                                                                         |  
| [**MS12-039**](http://go.microsoft.com/fwlink/?linkid=252488) | TrueType betűtípus-elemzés biztonsági rése                                             | [CVE-2012-0159](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0159) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nem valószínű rosszindulatú programkód          | Nem érintett                                                                                                     | Állandó                                               | (Nincs)                                                                                                                                                         |  
| [**MS12-039**](http://go.microsoft.com/fwlink/?linkid=252488) | A Lync alkalmazás nem biztonságos függvénytárbetöltése miatti biztonsági rés           | [CVE-2012-1849](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1849) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Nem érintett                                                                                                     | Nem érintett                                          | (Nincs)                                                                                                                                                         |  
| [**MS12-039**](http://go.microsoft.com/fwlink/?linkid=252488) | HTML-törlés miatti biztonsági rés                                                      | [CVE-2012-1858](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858) | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nem valószínű rosszindulatú programkód          | [3](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Nem valószínű rosszindulatú programkód          | Nem érintett                                          | A biztonsági rés illetéktelen adatelérést okoz. Az [MS12-037](http://go.microsoft.com/fwlink/?linkid=249045) közlemény szintén foglalkozik a biztonsági réssel. |  
| [**MS12-040**](http://go.microsoft.com/fwlink/?linkid=251612) | A Dynamics AX Enterprise Portal XSS-támadást lehetővé tévő biztonsági rése             | [CVE-2012-1857](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1857) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Nem érintett                                                                                                     | Nem érintett                                          | (Nincs)                                                                                                                                                         |  
| [**MS12-041**](http://go.microsoft.com/fwlink/?linkid=251707) | Karakterlánc atom osztálynév-kezelési biztonsági rése                                  | [CVE-2012-1864](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1864) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Állandó                                               | (Nincs)                                                                                                                                                         |  
| [**MS12-041**](http://go.microsoft.com/fwlink/?linkid=251707) | Karakterlánc atom osztálynév-kezelési biztonsági rése                                  | [CVE-2012-1865](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1865) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Állandó                                               | (Nincs)                                                                                                                                                         |  
| [**MS12-041**](http://go.microsoft.com/fwlink/?linkid=251707) | Vágólapformátum atom névkezelési biztonsági rése                                       | [CVE-2012-1866](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1866) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Állandó                                               | (Nincs)                                                                                                                                                         |  
| [**MS12-041**](http://go.microsoft.com/fwlink/?linkid=251707) | Betűkészlet erőforrás hivatkozásszámának egészszám-túlcsordulást okozó biztonsági rése | [CVE-2012-1867](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1867) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Állandó                                               | (Nincs)                                                                                                                                                         |  
| [**MS12-041**](http://go.microsoft.com/fwlink/?linkid=251707) | A Win32k.sys versenyhelyzet miatti biztonsági rése                                     | [CVE-2012-1868](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1868) | Nem érintett                                                                                                     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Állandó                                               | (Nincs)                                                                                                                                                         |  
| [**MS12-042**](http://go.microsoft.com/fwlink/?linkid=252515) | A User Mode Scheduler memóriameghibásodás miatti biztonsági rése                       | [CVE-2012-0217](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0217) | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Nem érintett                                                                                                     | Állandó                                               | (Nincs)                                                                                                                                                         |  
| [**MS12-042**](http://go.microsoft.com/fwlink/?linkid=252515) | A BIOS ROM meghibásodása miatti biztonsági rés                                         | [CVE-2012-1515](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1515) | Nem érintett                                                                                                     | [1](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Konzisztens rosszindulatú programkódról van szó | Állandó                                               | A biztonsági rés nyilvánosságra került,                                                                                                                         |
  
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
<tr>
<th colspan="6">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS12-036**](http://go.microsoft.com/fwlink/?linkid=246927)
</td>
<td style="border:1px solid black;">
[**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045)
</td>
<td style="border:1px solid black;">
[**MS12-038**](http://go.microsoft.com/fwlink/?linkid=251095)
</td>
<td style="border:1px solid black;">
[**MS12-041**](http://go.microsoft.com/fwlink/?linkid=251707)
</td>
<td style="border:1px solid black;">
[**MS12-042**](http://go.microsoft.com/fwlink/?linkid=252515)
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
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=fd2216eb-283b-4a23-b259-018a7fa5fe47)  
(KB2685939)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=7f222e05-2a8d-4099-851f-2044811f7425)  
(KB2699988)  
(Kritikus)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=07c75ac6-f92a-4204-aa58-bdf8c033df9e)  
(KB2699988)  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5bc1656f-cf1d-4f77-a078-a8602401b8e1)  
(KB2699988)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft .NET-keretrendszer 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f)  
(KB2686828)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=a399bd47-ffe1-4476-932c-9c119496222a)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0efff733-4c8d-4fce-8de3-28465c6b762b)  
(KB2707511)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6e354955-32ae-447c-b16f-960acc01773b)  
(KB2685939)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=57e8bf9d-97c3-4166-a5d4-6b0c99afc6a1)  
(KB2699988)  
(Kritikus)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4b35e90b-145d-44c2-a8bc-4f9108d46fa1)  
(KB2699988)  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0a386b16-74f7-4d36-93d0-75e7da9bf9b5)  
(KB2699988)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft .NET-keretrendszer 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f)  
(KB2686828)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bdb356db-bd36-4159-8e64-ecdb3dfc61bf)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS12-036**](http://go.microsoft.com/fwlink/?linkid=246927)
</td>
<td style="border:1px solid black;">
[**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045)
</td>
<td style="border:1px solid black;">
[**MS12-038**](http://go.microsoft.com/fwlink/?linkid=251095)
</td>
<td style="border:1px solid black;">
[**MS12-041**](http://go.microsoft.com/fwlink/?linkid=251707)
</td>
<td style="border:1px solid black;">
[**MS12-042**](http://go.microsoft.com/fwlink/?linkid=252515)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Összesített** **súlyossági besorolás**
</td>
<td style="border:1px solid black;">
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e856fec-9f05-49b7-91b6-11c2636a2f1d)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b1dcc826-7e96-464b-830e-39946e7802aa)  
(KB2699988)  
(Mérsékelt)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=de828031-1ace-43df-80f2-db7d503fb0a2)  
(KB2699988)  
(Mérsékelt)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4e6e5589-b767-4e8a-b8b3-df7b97e002e5)  
(KB2699988)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Microsoft .NET-keretrendszer 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f)  
(KB2686828)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e0b39b00-d7db-4008-8310-1258e84a72a2)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=855611a1-91ad-4d22-8c1c-fdcd6af4cef0)  
(KB2707511)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9b63fa4d-b42e-43ca-9f2c-cf60c37731a5)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=b060e03b-e63e-446b-9cfd-ea4e1e9383a6)  
(KB2699988)  
(Mérsékelt)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a36f7ffe-d537-4f9e-b676-22a24f50c089)  
(KB2699988)  
(Mérsékelt)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=b1acb2f0-63ba-4524-94cf-42b3534e21e7)  
(KB2699988)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Microsoft .NET-keretrendszer 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f)  
(KB2686828)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ed7359ce-13e8-42b2-956d-e8be534583aa)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2 Itanium-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=7dfdc5dc-54b0-49e3-bf5a-bbc40b0f159f)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=893667c4-ef9f-48d3-ab18-a0df51bd3dcc)  
(KB2699988)  
(Mérsékelt)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=30a9d518-8067-44f4-90fd-09fec8a0c883)  
(KB2699988)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Microsoft .NET-keretrendszer 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f)  
(KB2686828)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=2317c8d9-cae8-497b-952e-78eb4a6d585c)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="6">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS12-036**](http://go.microsoft.com/fwlink/?linkid=246927)
</td>
<td style="border:1px solid black;">
[**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045)
</td>
<td style="border:1px solid black;">
[**MS12-038**](http://go.microsoft.com/fwlink/?linkid=251095)
</td>
<td style="border:1px solid black;">
[**MS12-041**](http://go.microsoft.com/fwlink/?linkid=251707)
</td>
<td style="border:1px solid black;">
[**MS12-042**](http://go.microsoft.com/fwlink/?linkid=252515)
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
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f55b62bf-0571-4888-9061-3f7cc75d7f17)  
(KB2685939)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=16f4404e-e6d6-4bde-af15-3bb692412213)  
(KB2699988)  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=610e753a-21db-43e6-bc42-3e1227fa4bb1)  
(KB2699988)  
(Kritikus)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=828fdb71-747b-481d-9683-895325331478)  
(KB2699988)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft .NET-keretrendszer 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b)  
(KB2686833)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9188f1eb-b568-4a99-9b39-745c760a693d)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ab06290c-4f57-4349-8abd-a382b9044631)  
(KB2685939)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=993c5bc4-8903-4c8c-bbc9-da2e47d959f9)  
(KB2699988)  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=87100a7e-7feb-4a18-b7aa-04fdd2d6ef52)  
(KB2699988)  
(Kritikus)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7b551d67-e0f1-498a-ac4f-06376a0fcf18)  
(KB2699988)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft .NET-keretrendszer 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b)  
(KB2686833)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4b94ae42-2882-444c-ad5e-74e34b805006)  
(KB2709162)  
(Fontos)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS12-036**](http://go.microsoft.com/fwlink/?linkid=246927)
</td>
<td style="border:1px solid black;">
[**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045)
</td>
<td style="border:1px solid black;">
[**MS12-038**](http://go.microsoft.com/fwlink/?linkid=251095)
</td>
<td style="border:1px solid black;">
[**MS12-041**](http://go.microsoft.com/fwlink/?linkid=251707)
</td>
<td style="border:1px solid black;">
[**MS12-042**](http://go.microsoft.com/fwlink/?linkid=252515)
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
<td style="border:1px solid black;">
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 32 bites rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d8dcb487-0df7-46f4-8726-bd58e2722812)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=e7f9ad40-d515-4224-90ff-4bd4bff9180f)  
(KB2699988)  
(Mérsékelt)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c4eaeff8-7b7a-4418-a479-09b2146df2bf)  
(KB2699988)  
(Mérsékelt)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=a20c839c-ce3b-46a5-becb-588de404878d)  
(KB2699988)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Microsoft .NET-keretrendszer 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b)  
(KB2686833)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6398a156-9618-4ca4-95bc-d36ecacf0745)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 x64-alapú rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64-alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=40c16540-7839-412c-b474-892292a96fa5)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7420c9f3-8f7e-4823-aaba-b14b957408d8)  
(KB2699988)  
(Mérsékelt)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=fd5308b7-7430-4713-922c-f06c46886fad)  
(KB2699988)  
(Mérsékelt)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=1a737d87-0689-470b-8fc0-8c874af18794)  
(KB2699988)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Microsoft .NET-keretrendszer 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b)  
(KB2686833)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64-alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bc4412ee-8cb8-42e9-96fe-0be49af149b2)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 Itanium-alapú rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 Itanium-alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c4b8af1c-b483-4aed-9be5-b0f1698b2c28)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=472842c4-5fe7-4d4c-a927-05be030b5b4e)  
(KB2699988)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Microsoft .NET-keretrendszer 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b)  
(KB2686833)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 Itanium-alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=098607b3-9424-4440-8832-fc1de010977e)  
(KB2709162)  
(Fontos)
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
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS12-036**](http://go.microsoft.com/fwlink/?linkid=246927)
</td>
<td style="border:1px solid black;">
[**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045)
</td>
<td style="border:1px solid black;">
[**MS12-038**](http://go.microsoft.com/fwlink/?linkid=251095)
</td>
<td style="border:1px solid black;">
[**MS12-041**](http://go.microsoft.com/fwlink/?linkid=251707)
</td>
<td style="border:1px solid black;">
[**MS12-042**](http://go.microsoft.com/fwlink/?linkid=252515)
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
<td style="border:1px solid black;">
Windows 7 32 bites rendszerekhez
</td>
<td style="border:1px solid black;">
[Windows 7 32 bites rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=e8549243-e6bf-4007-9bc3-d9c2a24936ef)  
(KB2685939)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=595e72c3-f195-4f93-b24e-afe444abd628)  
(KB2699988)  
(Kritikus)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=48ca08c8-78cc-4b09-a0ec-bcd208668620)  
(KB2699988)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236)  
(KB2686830)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows 7 32 bites rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=605f64bd-0615-47d8-bb32-6bc3e80da4a7)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 32 bites rendszerekhez, Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 32 bites rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e8549243-e6bf-4007-9bc3-d9c2a24936ef)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=595e72c3-f195-4f93-b24e-afe444abd628)  
(KB2699988)  
(Kritikus)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=48ca08c8-78cc-4b09-a0ec-bcd208668620)  
(KB2699988)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b)  
(KB2686831)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows 7 32 bites rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=605f64bd-0615-47d8-bb32-6bc3e80da4a7)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 x64-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Windows 7 x64-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=7f0f54e4-b9d9-45d8-bc58-05d7e7b75f07)  
(KB2685939)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=30feb2fe-b19b-4d02-8c5b-4499dd6905d1)  
(KB2699988)  
(Kritikus)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=bf8dbfee-573b-4d45-a752-90e1d485e503)  
(KB2699988)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236)  
(KB2686830)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows 7 x64-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=3c77ca1f-2eec-4f95-a769-973b75af184c)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows 7 x64-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=c2b47091-534f-41c3-a229-b5a9ec4b64bb)  
(KB2709715)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 x64 alapú rendszerekhez, Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows 7 x64 alapú rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=7f0f54e4-b9d9-45d8-bc58-05d7e7b75f07)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=30feb2fe-b19b-4d02-8c5b-4499dd6905d1)  
(KB2699988)  
(Kritikus)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=bf8dbfee-573b-4d45-a752-90e1d485e503)  
(KB2699988)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b)  
(KB2686831)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows 7 x64 alapú rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=3c77ca1f-2eec-4f95-a769-973b75af184c)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows 7 x64 alapú rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c2b47091-534f-41c3-a229-b5a9ec4b64bb)  
(KB2709715)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS12-036**](http://go.microsoft.com/fwlink/?linkid=246927)
</td>
<td style="border:1px solid black;">
[**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045)
</td>
<td style="border:1px solid black;">
[**MS12-038**](http://go.microsoft.com/fwlink/?linkid=251095)
</td>
<td style="border:1px solid black;">
[**MS12-041**](http://go.microsoft.com/fwlink/?linkid=251707)
</td>
<td style="border:1px solid black;">
[**MS12-042**](http://go.microsoft.com/fwlink/?linkid=252515)
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
<td style="border:1px solid black;">
Windows Server 2008 R2 x64-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9464b044-e40b-4300-97b8-dc3a13c85929)  
(KB2699988)  
(Mérsékelt)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7c0c8b04-b749-4c6c-8b9f-244abc5f8ecf)  
(KB2699988)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236)  
(KB2686830)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c)  
(KB2709715)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 x64-alapú rendszerekhez, Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64-alapú rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9464b044-e40b-4300-97b8-dc3a13c85929)  
(KB2699988)  
(Mérsékelt)  
[Internet Explorer 9](http://www.microsoft.com/downloads/details.aspx?familyid=7c0c8b04-b749-4c6c-8b9f-244abc5f8ecf)  
(KB2699988)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b)  
(KB2686831)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64-alapú rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64-alapú rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c)  
(KB2709715)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=8ecc5d12-9921-4d04-a04c-d69e8f4349dc)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=40302688-fcda-489c-87c4-480d3b9d754c)  
(KB2699988)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236)  
(KB2686830)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=039ddfe1-3ce5-48d8-8cb4-65481da3f29c)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium alapú rendszerekhez, Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 Itanium alapú rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=8ecc5d12-9921-4d04-a04c-d69e8f4349dc)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=40302688-fcda-489c-87c4-480d3b9d754c)  
(KB2699988)  
(Mérsékelt)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b)  
(KB2686831)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 Itanium alapú rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=039ddfe1-3ce5-48d8-8cb4-65481da3f29c)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="6">
Kiszolgálómag-telepítési opció
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS12-036**](http://go.microsoft.com/fwlink/?linkid=246927)
</td>
<td style="border:1px solid black;">
[**MS12-037**](http://go.microsoft.com/fwlink/?linkid=249045)
</td>
<td style="border:1px solid black;">
[**MS12-038**](http://go.microsoft.com/fwlink/?linkid=251095)
</td>
<td style="border:1px solid black;">
[**MS12-041**](http://go.microsoft.com/fwlink/?linkid=251707)
</td>
<td style="border:1px solid black;">
[**MS12-042**](http://go.microsoft.com/fwlink/?linkid=252515)
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
<td style="border:1px solid black;">
Windows Server 2008 32 bites rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d8dcb487-0df7-46f4-8726-bd58e2722812)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6398a156-9618-4ca4-95bc-d36ecacf0745)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 x64-alapú rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64-alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=40c16540-7839-412c-b474-892292a96fa5)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64-alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bc4412ee-8cb8-42e9-96fe-0be49af149b2)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 x64-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236)  
(KB2686830)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c)  
(KB2709715)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 x64-alapú rendszerekhez, Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64-alapú rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266)  
(KB2685939)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b)  
(KB2686831)  
(Kritikus)  
[Microsoft .NET Framework 4](http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145)<sup>[1]</sup>
(KB2686827)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64-alapú rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8)  
(KB2709162)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64-alapú rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c)  
(KB2709715)  
(Fontos)
</td>
</tr>
</table>
 
**Megjegyzés aMS12-038** közleményhez

<sup>[1]</sup>**A .NET Framework 4 verziója és a .NET Framework 4 verziójához tartozó ügyfélprofil.** A .NET-keretrendszer 4-es verziójú terjeszthető csomagjai két profilban érhetőek el: a .NET Framework 4 és a .NET Framework 4 verziójához tartozó ügyfélprofil. A .NET Framework 4 verziójához tartozó ügyfélprofil a .NET Framework 4 részhalmaza. Az ebben a frissítésben tárgyalt biztonsági rés egyaránt érinti a .NET Framework 4 verzióját és a .NET Framework 4 verziójához tartozó ügyfélprofilt is. További információk [A .NET keretrendszer telepítése](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx) c. MSDN cikkben.

#### Microsoft kommunikációs platformok és szoftverek

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Communicator
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS12-039**](http://go.microsoft.com/fwlink/?linkid=252488)
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
Microsoft Communicator 2007 R2
</td>
<td style="border:1px solid black;">
[Microsoft Communicator 2007 R2](http://www.microsoft.com/downloads/details.aspx?familyid=75eea324-689a-4892-bdd9-03ef399c4cba)  
(KB2708980)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="2">
Microsoft Lync
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS12-039**](http://go.microsoft.com/fwlink/?linkid=252488)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 bites)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 (32 bites)](http://www.microsoft.com/downloads/details.aspx?familyid=425406ea-28b9-46f7-8c49-0c7ea46f16e3)  
(KB2693282)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 bites)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 (64 bites)](http://www.microsoft.com/downloads/details.aspx?familyid=06e5285f-1947-4409-b608-e0a145fadba4)  
(KB2693282)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 Attendee](http://www.microsoft.com/downloads/details.aspx?familyid=c40f0d38-af90-4966-a0f0-346fa48683d0)  
(rendszergazdai szintű telepítés)  
(KB2696031)  
(Fontos)  
[Microsoft Lync 2010 Attendee](http://www.microsoft.com/downloads/details.aspx?familyid=ad864c0e-5850-44a3-b74f-5980a998a384)<sup>[1]</sup>
(felhasználói szintű telepítés)  
(KB2693283)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendant (32 bites)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 Attendant (32 bites)](http://www.microsoft.com/downloads/details.aspx?familyid=fe7ad0f9-ee84-4cda-b252-a8d31ead5053)  
(KB2702444)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendant (64 bites)
</td>
<td style="border:1px solid black;">
[Microsoft Lync 2010 Attendant (64 bites)](http://www.microsoft.com/downloads/details.aspx?familyid=fe7ad0f9-ee84-4cda-b252-a8d31ead5053)  
(KB2702444)  
(Fontos)
</td>
</tr>
</table>
 
**Megjegyzés az** **MS12-039 közleményhez**

<sup>[1]</sup>Ez a frissítés kizárólag a Microsoft letöltő központból érhető el.

#### Microsoft vállalatirányítási (ERP) megoldások

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="2">
Microsoft Dynamics ERP
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS12-040**](http://go.microsoft.com/fwlink/?linkid=251612)
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
Microsoft Dynamics AX 2012
</td>
<td style="border:1px solid black;">
[Microsoft Dynamics AX 2012 Enterprise Portal](http://www.microsoft.com/downloads/details.aspx?familyid=45df362d-8fed-4d99-91c1-81c61878300a)<sup>[1]</sup>
(KB2706738)  
(Fontos)  
[Microsoft Dynamics AX 2012 Enterprise Portal](http://www.microsoft.com/downloads/details.aspx?familyid=780ddcef-19da-44c4-beca-d10b652cd22a)<sup>[1]</sup>
(KB2710639)  
(Fontos)  
[Microsoft Dynamics AX 2012 Enterprise Portal](http://www.microsoft.com/downloads/details.aspx?familyid=41dc5958-c224-40f9-89c2-179607a8ee2a)<sup>[1]</sup>
(KB2711239)  
(Fontos)
</td>
</tr>
</table>
 
**Megjegyzés a MS12-040 közleményhez**

<sup>[1]</sup>Ez a frissítés kizárólag a Microsoft letöltőközpontból, valamint a Microsoft Dynamics CustomerSource és a Microsoft Dynamics PartnerSource weboldalakon érhető el.

Észlelési és telepítési eszközök, útmutatás
-------------------------------------------

<span></span>
**Biztonsági központ**

A szoftveres és biztonsági frissítések kezeléséhez azokat a szervezet asztali és hordozható számítógépeire, valamint kiszolgálóira is telepíteni kell. További tájékoztatásért látogasson el a [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) weboldalára. A [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) bővebb tájékoztatással szolgál a Microsoft termékek biztonsági funkcióival kapcsolatban. A [Biztonság otthon](http://go.microsoft.com/fwlink/?linkid=85102) weboldalon a megfelelő hivatkozásra kattintva elérhetőek a legújabb biztonsági frissítések.

A biztonsági frissítések a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) és a [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) weboldalról tölthetők le. A biztonsági frissítések a [Microsoft letöltő központjában](http://go.microsoft.com/fwlink/?linkid=21129) is elérhetőek. Legegyszerűbben a „security update” kifejezésre irányuló kulcsszavas kereséssel találhatja meg ezeket.

A Microsoft Office for Mac felhasználói számára a Microsoft AutoUpdate for Mac szolgáltatás biztosítja a Microsoft szoftverek naprakész állapotát. A Microsoft AutoUpdate for Mac működésének részleteiről lásd: [Szoftverfrissítések automatikus keresése](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

A biztonsági frissítések a [Microsoft Update katalógusából](http://go.microsoft.com/fwlink/?linkid=96155) is letölthetőek. A Microsoft Update katalógus a Windows Update és Microsoft Update szolgáltatáson keresztül elérhető tartalom kereshető adatbázisa; ide tartoznak a biztonsági frissítések, illesztőprogramok és szervizcsomagok. A biztonsági közlemény azonosítójára (pl. „MS07-036”) történő kereséssel hozzáadhatja az összes vonatkozó frissítést a kosárhoz (beleértve a frissítés különböző nyelvi változatait), és letöltheti azokat a megadott mappába. A Microsoft Update katalógus részletes leírását lásd a vonatkozó [GYIK](http://go.microsoft.com/fwlink/?linkid=97900)részben.

**Útmutató az észleléshez és a telepítéshez**

A biztonsági frissítésekkel kapcsolatban a Microsoft észlelési és telepítési segítséget nyújt. Ez az útmutató olyan javaslatokat és tudnivalókat tartalmaz, amelyeket segítséget nyújthatnak az informatikusoknak a biztonsági frissítések észlelési és telepítési eszközeinek használatához. További tudnivalókat a [Microsoft Tudásbázis 961747. számú cikkében](http://support.microsoft.com/kb/961747) talál.

**Microsoft Baseline Security Analyzer**

A Microsoft Baseline Security Analyzer (MBSA) segítségével a rendszergazda mind a helyi, mind a távoli számítógépeken ellenőrizheti, hogy mely biztonsági frissítések hiányoznak, illetve hogy mely biztonsági beállítások vannak helytelenül megadva. Ha többet szeretne tudni az MBSA eszközről, látogasson el a [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) webhelyre.

**Windows Server Update Services**

A Microsoft Server Update Services (WSUS) szolgáltatással a rendszergazdák gyorsan és megbízhatóan telepíthetik a legújabb fontos és biztonsági frissítéseket Microsoft Windows 2000 és újabb operációs rendszerekhez, Office XP és újabb operációs rendszerekhez, Exchange Server 2003 és SQL Server 2000 Microsoft Windows 2000 és újabb operációs rendszerekre.

A biztonsági frissítésnek Windows Server Update Services szolgáltatással történő központi telepítéséről a [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx) webhelyen tudhat meg többet.

**SystemCenter Configuration Manager**

A System Center Configuration Manager szoftverfrissítés-kezelése leegyszerűsíti a frissítéseknek a vállalat minden IT-rendszerére történő eljuttatásával és kezelésével járó összetett feladatot. A System Center Configuration Manager segítségével az IT-rendszergazdák a Microsoft-termékek frissítéseit számos készülékre juttathatják el, köztük asztali számítógépekre, hordozható számítógépekre, kiszolgálókra és mobilkészülékekre.

A System Center Configuration Manager automatizált biztonságirés-elemzése jelzi a frissítések szükségességét, és jelentést küld a javasolt lépésekről. A System Center Configuration Manager szoftverfrissítés-kezelése a Microsoft Windows Software Update Services (WSUS) szolgáltatására épül, amely az IT-rendszergazdák számára világszerte ismerős, jól bevált frissítési infrastruktúra. Ha többet szeretne tudni arról, hogy a rendszergazdák miként telepíthetik a frissítéseket a System Center Configuration Manager alkalmazással, lásd a [Szoftverfrissítés-kezelés](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx) című részt. A System Center Configuration Manager alkalmazással kapcsolatos bővebb információt lásd: [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

A Microsoft Systems Management Server (SMS) rendszer egy sokoldalúan beállítható vállalati megoldás, amely a frissítések kezelésére szolgál. Az SMS segítségével a rendszergazda megállapíthatja, hogy melyik Windows alapú számítógép szorul biztonsági frissítésre, és ezeket a frissítéseket szabályozott módon, a felhasználók minimális zavarásával központilag telepítheti a vállalat teljes informatikai környezetében.

**Megjegyzés** A System Management Server 2003 rendszer általános támogatása 2010. január 12-én lejár. Ha többet szeretne tudni a Windows termékek életciklusáról, keresse fel a [Microsoft támogatási életciklusokkal foglalkozó webhelyét](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Az SMS újabb kiadása, a System Center Configuration Manager már elérhető: lásd a korábbi, **System Center Configuration Manager** című részben.

Ha többet szeretne tudni arról, hogy a rendszergazdák miként telepíthetik a biztonsági frissítéseket az SMS 2003 alkalmazással, látogasson el a [Forgatókönyvek és eljárások a Microsoft Systems Management Server 2003 alkalmazáshoz: Szoftverterjesztés és javításkezelés](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) oldalra. Az SMS szolgáltatásról bővebben a [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx) oldalán olvashat.

**Megjegyzés** Az SMS a Microsoft Baseline Security Analyzer eszközön keresztül széles körű támogatást nyújt a biztonsági közlemények frissítéseinek észleléséhez, valamint a frissítések telepítéséhez. Előfordulhat, hogy egyes szoftverfrissítéseket ezek az eszközök nem észlelnek. Az SMS-alkalmazás leltározási szolgáltatásai segítségével a rendszergazdák adott rendszereken hajthatják végre a frissítést. Az eljárással kapcsolatban olvassa el a [Szoftverfrissítések telepítése az SMS szoftverelosztó ügynök segítségével](http://go.microsoft.com/fwlink/?linkid=33341) című tájékoztatót. Egyes biztonsági frissítésekhez rendszergazdai jogosultságokra van szükség a számítógép újraindítása után. A rendszergazdák az Elevated Rights Deployment Tool eszközt (az [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en) része) alkalmazhatják a frissítések telepítéséhez.

**Az Update Compatibility Evaluator (a frissítéskompatibilitás kiértékelője) és az Application Compatibility Toolkit (alkalmazáskompatibilitási eszközkészlet)**

Az alkalmazások működése érdekében a frissítések gyakran írnak ugyanazokba a fájlokba, illetve regisztrációs bejegyzésekbe. Ez inkompatibilitást okozhat, és növelheti a biztonsági frissítések központi telepítésére használt időt. A Windows frissítések és az alkalmazásoknak való megfelelőség tesztelése és ellenőrzése egyszerűsíthető az [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) összetevőivel, amelyek az [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) alkalmazáskompatibilitási eszközkészletben megtalálhatók.

Az Application Compatibility Toolkit (ACT) tartalmazza a Windows Vista, a Windows Update, a Microsoft Security Update vagy a Windows Internet Explorer új verziójának központi telepítése előtt az alkalmazáskompatibilitási problémák kiértékeléséhez és enyhítéséhez szükséges eszközöket és dokumentációt.

### Egyéb információ

#### A Microsoft Windows rosszindulatú szoftvereket eltávolító eszköze

A Microsoft a Windows Update, Microsoft Update, Windows Server Update Services és Letöltőközpont szolgáltatásán keresztül elérhetővé tette a Microsoft Windows rosszindulatú szoftvereket eltávolító eszközének frissített változatát.

#### Nem biztonsági jellegű frissítések a MU, WU és WSUS-szolgáltatásokban

A Windows Update és a Microsoft Update helyen elérhető, nem biztonsági jellegű frissítésekről tájékozódjon itt:

-   [Microsoft Tudásbázis 894199. cikke](http://support.microsoft.com/kb/894199): Tartalommódosítás a Software Update Services és Windows Server Update Services rendszerek leírásában. Az összes Windows-tartalmat érinti.
-   [Az elmúlt hónapok frissítései Windows Server Frissítési szolgáltatások esetén](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Microsoft termékek új, módosított és újra kiadott frissítései, a Microsoft Windows rendszert kivéve.

#### Microsoft Active Protections Program (MAPP)

Az ügyfelek védelmének növelése érdekében a biztonsági szoftverekkel foglalkozó nagyobb gyártók a Microsoft a havi biztonsági közlemények megjelenése előtt ellátja biztonsági résekkel kapcsolatos információkkal. Így a biztonságiszoftver-gyártók a kapott biztonsági résekkel kapcsolatos információt felhasználhatják ügyfeleik hatásosabb védelmére az olyan biztonsági szoftverek vagy eszközök (például víruskeresők, hálózati behatolásérzékelő rendszerek vagy kiszolgálóalapú behatolásvédelmi rendszerek) frissítése által. A biztonságiszoftver-gyártók által kiadott aktív védelem elérhetőségéről a [Microsoft Active Protections Program (MAPP) Partners](http://go.microsoft.com/fwlink/?linkid=215201) webhelyén található listán szereplő és a programban részt vevő gyártók aktív védelmi webhelyein tájékozódhat.

#### Biztonsági stratégiák és közösségek

**Frissítésekkel kapcsolatos stratégiák**

[A frissítések kezelésére vonatkozó útmutatás](http://go.microsoft.com/fwlink/?linkid=21168) a Microsoft által a biztonsági frissítések telepítéséhez ajánlott legjobban bevált eljárást ismerteti.

**Egyéb biztonsági frissítések beszerzése**

Az alábbi helyekről más típusú biztonsági problémákhoz szerezhetők be frissítések:

-   A biztonsági frissítések a [Microsoft letöltő központjában](http://go.microsoft.com/fwlink/?linkid=21129) érhetők el. Legegyszerűbben a „security update” kifejezésre irányuló kulcsszavas kereséssel találhatja meg ezeket.
-   Az ügyfélrendszerek frissítései a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) oldalról elérhetőek.
-   A Windows Update szolgáltatáson keresztül terjesztett havi aktuális biztonsági frissítések a letöltőközpontból a biztonsági és kritikus frissítéseket tartalmazó ISO CD-képfájlként is letölthetőek. További információt a [Microsoft Tudásbázis 913086. számú cikkében](http://support.microsoft.com/kb/913086) talál.

**IT Pro Security közösség**

Az [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) közösségben hasznos információt találhat a biztonság javításáról és az informatikai infrastruktúrák optimalizálásáról, továbbá eszmecserét folytathat a biztonsági kérdésekről más informatikai szakemberekkel.

#### Köszönetnyilvánítás

A Microsoft [köszönetét](http://go.microsoft.com/fwlink/?linkid=21127) fejezi ki a vásárlók védelmének biztosításában nyújtott segítségért az alábbi szervezet(ek)nek és szakember(ek)nek:

-   A [VeriSign iDefense Labs](http://labs.idefense.com/) anonim együttműködő partnerének az MS12-037 közleményben ismertetett probléma jelentéséért
-   Adi Cohen, [IBM Security Systems - Application Security](http://blog.watchfire.com/) a MS12-037 közleményben ismertetett probléma jelentéséért
-   Masato Kinugawa, az MS12-037 közleményben ismertetett egyik probléma jelentéséért
-   Roman Shafigullin, LinkedIn,az MS12-037 közleményben leírt probléma jelentéséért
-   Code Audit Labs, [VulnHunt](http://www.vulnhunt.com) az MS12-037 közleményben leírt probléma jelentéséért
-   Dark Son, [VulnHunt](http://www.vulnhunt.com),az MS12-037 közleményben leírt probléma jelentéséért
-   [Qihoo 360 Security Center](http://www.360.cn/) az MS12-037 közleményben ismertetett probléma megoldásában nyújtott segítségéért
-   Yichong Lin, McAfee Labs, az MS12-037 közleményben ismertetett probléma megoldásában való közreműködésért
-   [Google Inc](http://www.google.com/)., az MS12-037 közleményben ismertetett egyik probléma megoldásában való közreműködésért
-   [VUPEN Security](http://www.vupen.com), [TippingPoint's](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), az MS12-037 közleményben ismertetett probléma jelentéséért
-   A [TippingPoint](http://www.tippingpoint.com/)[Zero Day](http://www.zerodayinitiative.com/) Initiative céggel együttműködő anonim kutató, az MS12-037 közleményben leírt probléma jelentéséért.
-   A [TippingPoint](http://www.tippingpoint.com/)[Zero Day](http://www.zerodayinitiative.com/) Initiative céggel együttműködő anonim kutató, az MS12-037 közleményben leírt probléma jelentéséért.
-   A [TippingPoint](http://www.tippingpoint.com/)[Zero Day](http://www.zerodayinitiative.com/) Initiative céggel együttműködő anonim kutató, az MS12-037 közleményben leírt probléma jelentéséért.
-   A [TippingPoint](http://www.tippingpoint.com/)[Zero Day](http://www.zerodayinitiative.com/) Initiative céggel együttműködő anonim kutató, az MS12-037 közleményben leírt probléma jelentéséért.
-   A [TippingPoint](http://www.tippingpoint.com/)[Zero Day](http://www.zerodayinitiative.com/) Initiative céggel együttműködő anonim kutató, az MS12-037 közleményben leírt probléma jelentéséért.
-   Vitaliy Toropov VUPEN Security, [TippingPoint](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), az MS12-038 közleményben ismertetett probléma jelentéséért
-   hamburgers maccoy, a Secunia SVCRP programon keresztül, az MS12-039 közleményben bemutatott probléma jelentéséért
-   Adi Cohen, [IBM Security Systems – Application Security](http://blog.watchfire.com/), az MS12-039 közleményben ismertetett probléma jelentéséért
-   Alin Rad Pop, a [TippingPoint](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) programjával együttműködésben, az MS12-039 számú közleményben ismertetett probléma jelentéséért
-   Finian Mackin, az MS12-040 közleményben ismertetett egyik probléma jelentéséért
-   Tarjei Mandt, [Azimuth Security](http://www.azimuthsecurity.com/), az MS12-041 közleményben ismertetett három probléma jelentéséért
-   [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org), [Google Inc](http://www.google.com)., az MS12-041 közleményben bemutatott egyik probléma jelentéséért
-   Rafal Wojtczuk, [Bromium](http://www.bromium.com/) és Jan Beulich, [SUSE](http://www.suse.com/), az MS12-042 közleményben leírt probléma jelentéséért

#### Terméktámogatás

-   Teszteléssel állapították meg a felsorolt szoftverek egyes verzióinak érintettségét. A többi verzió támogatási életciklusa végére ért. Az egyes szoftververziók támogatási életciklusáról a [Microsoft termékek terméktámogatási életciklusát ismertető webhelyen](http://go.microsoft.com/fwlink/?linkid=21742) talál felvilágosítást.
-   Biztonsági megoldások informatikai szakemberek számára: [TechNet Security hibakeresés és támogatás](http://technet.microsoft.com/security/bb980617.aspx)
-   Segítség Windows operációs rendszert futtató számítógépének vírusok és rosszindulatú szoftverek elleni védelmében: [Vírusmegoldás és Biztonsági központ](http://support.microsoft.com/contactus/cu_sc_virsec_master)
-   Helyi támogatás országának megfelelően: [Nemzetközi támogatás](http://support.microsoft.com/common/international.aspx)

#### Felelősséget kizáró nyilatkozat

A Microsoft Tudásbázisban leírtak előzetes bejelentés nélkül változhatnak, és a cikkek tartalmáért a Microsoft nem vállal garanciát. A Microsoft egyben elhárít minden kifejezett és értelemszerű garanciát, beleértve az eladhatóságra és az adott célra való alkalmasságra vonatkozó garanciát is. A Microsoft Corporation vagy annak szállítói semmilyen körülmények között nem tehetők felelőssé közvetlen, közvetett, eseti, ok-okozati vagy különleges kárért (beleértve az elmaradt hasznot is), még akkor sem, ha a Microsoft Corporation vagy szállítói tudatában voltak a kár lehetséges voltának. Egyes államok törvényi szabályozása nem teszi lehetővé a véletlen vagy ok-okozati károkért vállalt felelősség korlátozását vagy kizárását, így ezekben az államokban az ez a felelősségkizárás nincs érvényben.

#### Verziók

-   1.0 verzió (2012. június 12.): Összefoglaló közlemény közzététele.

*Built at 2014-04-18T01:50:00Z-07:00*
