---
TOCTitle: 'MS11-SEP'
Title: 'Microsoft biztonsági közlemény - összefoglalás, 2011. szeptember'
ms:assetid: 'ms11-sep'
ms:contentKeyID: 61227762
ms:mtpsurl: 'https://technet.microsoft.com/hu-HU/library/ms11-sep(v=Security.10)'
author: SharonSears
ms.author: SharonSears
---

Security Bulletin Summary

Microsoft biztonsági közlemény - összefoglalás, 2011. szeptember
================================================================

Közzétéve: 2011. szeptember 13. | Frissítve: 2011. szeptember 13.

**Verzió:** 1.1

Az összefoglaló a 2011 szeptemberében kiadott biztonsági közleményeket összegzi.

A 2011. szeptember biztonsági közlemények kiadása folytán az összefoglaló a 2011. szeptember 8-án kiadott előzetes értesítés helyébe lép. További információk a biztonsági közlemények kiadásáról szóló előzetes értesítés szolgáltatásról lásd: [Előzetes értesítés a Microsoft biztonsági közleményeinek kiadásáról](http://go.microsoft.com/fwlink/?linkid=217213).

Ha automatikus értesítést szeretne kapni a Microsoft biztonsági közleményeinek megjelenéséről, fizessen elő a [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) szolgáltatásra.

A közleményekkel kapcsolatos kérdések megválaszolására a Microsoft 2011. szeptember 14-én, csendes-óceáni idő szerint 11 órakor webes szemináriumot tart. [Jelentkezzen most a szeptemberi közleményeket bemutató webes szemináriumra](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=en-us&eventid=1032487951). Ezt követően a webes szeminárium igény szerint kerül megrendezésre. További információkért látogasson el a [Microsoft biztonsági közleményeit és a webes szemináriumokat](http://go.microsoft.com/fwlink/?linkid=217214)bemutató oldalra.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225825">MS11-070</a></td>
<td style="border:1px solid black;"><strong>A WINS biztonsági rése a jogok kiterjesztését teheti lehetővé (2571621)</strong><br />
<br />
Ez a biztonsági frissítés egy, a Microsoftnak közvetlenül jelentett biztonsági rést javít ki a Windows Internet Name Service (WINS) szolgáltatásban. A biztonsági rés a jogok kiterjesztését teheti lehetővé, ha a felhasználó speciálisan kialakított WINS replikációs csomagot fogad egy érintett rendszeren, amelyen a WINS fut. A támadónak a biztonsági rés kihasználásához érvényes bejelentkezési adatokkal kell rendelkeznie, és képesnek kell lennie helyileg bejelentkezni a rendszerbe.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Jogok kiterjesztése</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223632">MS11-071</a></td>
<td style="border:1px solid black;"><strong>A Windows-összetevők biztonsági rése távoli kódfuttatást tehet lehetővé (2570947)</strong><br />
<br />
Ez a biztonsági frissítés egy nyilvánosan jelentett biztonsági rést szüntet meg a Microsoft Windows termékben. A támadó a biztonsági résen keresztül távoli kódfuttatást tud elérni, ha a felhasználó megnyit egy olyan normál Rich Text formátumú (.rtf) fájlt vagy Word dokumentumot, amely azonos hálózati könyvtárban található, mint a speciálisan létrehozott dinamikus csatolású függvénytárfájl (DLL). A biztonsági rést kihasználó támadó a helyi felhasználóval egyező hozzáférést nyer a rendszerhez. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Excel biztonsági rései távoli kódfuttatást tehetnek lehetővé (2587505)</strong><br />
<br />
Ez a biztonsági frissítés öt közvetlenül a Microsoftnak jelentett biztonsági részt javít ki a Microsoft Office termékben. A biztonsági rések távoli kódvégrehajtást tehetnek lehetővé, amennyiben a felhasználó egy speciálisan kialakított Excel fájlt nyit meg. A biztonsági rések valamelyikét sikeresen kihasználó támadó a bejelentkezett felhasználóval egyező hozzáférést nyer a rendszerhez. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén Ha a gyanús fájlok megnyitásának megakadályozása érdekében telepíti és konfigurálja az Office fájlellenőrzés (OFV) szolgáltatást, az védelmet nyújt a CVE-2011-1986 és CVE-2011-1987 közleményben ismertetett biztonsági rések kihasználásával végrehajtható támadások ellen.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server Software</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Office biztonsági rése távoli kódfuttatást tehet lehetővé (2587634)</strong><br />
<br />
Ez a biztonsági frissítés két közvetlenül a Microsoftnak jelentett biztonsági részt javít ki a Microsoft Office termékben. A támadó a biztonsági réseken keresztül távoli kódfuttatást tud elérni, ha rá tudja venni a felhasználót, hogy nyisson meg egy különlegesen kialakított Office-fájlt vagy egy különlegesen kialakított objektumtárfájllal azonos hálózati meghajtón található normál Office-fájlt. A biztonsági rések valamelyikét sikeresen kihasználó támadó a bejelentkezett felhasználóéval megegyező felhasználó jogokat nyer a rendszerhez. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;"><strong>A Microsoft SharePoint biztonsági rései a jogok kiterjesztését tehetik lehetővé (2451858)</strong><br />
<br />
Ez a biztonsági frissítés öt közvetlenül a Microsoftnak és egy nyilvánosan jelentett biztonsági rést szüntet meg a Microsoft SharePoint termékben és a Windows SharePoint Services szolgáltatásban. A legsúlyosabb besorolású biztonsági rések jogok kiterjesztését tehetik lehetővé, ha a felhasználó egy speciálisan kialakított URL-címre kattint, vagy meglátogat egy speciálisan kialakított webhelyet. A legsúlyosabb besorolású biztonsági rések esetén az Internet Explorer 8 és az Internet Explorer 9 felhasználói, ha az Internet zónában böngészik a SharePoint webhelyet, kevésbé veszélyeztettek, mert alapértelmezés szerint az Internet Explorer 8 és az Internet Explorer 9 verzióban lévő XSS-szűrő az Internet zónában segíti a támadások blokkolását. Az Internet Explorer 8 és az Internet Explorer 9 alkalmazás XSS-szűrője azonban az Intranet zónában alapértelmezés szerint nem engedélyezett.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Jogok kiterjesztése</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server Software</td>
</tr>
</tbody>
</table>
 

Kihasználhatósági információk
-----------------------------

<span></span>
A következő táblázat az adott hónapban megoldott biztonsági rések kihasználhatósági jellemzőit ismerteti. A biztonsági rések a közlemény azonosítója és súlyossági besorolás azonosítója szerint vannak felsorolva. Csak a kritikus és fontos besorolású biztonsági rések szerepelnek.

**A táblázat használata**

Az alábbi táblázatból minden telepítendő biztonsági frissítésről megtudhatja, hogy mekkora a valószínűsége annak, hogy a biztonsági közlemény kiadása után 30 napon belül kódvégrehajtási és szolgáltatásmegtagadási támadások jelenhetnek meg. A havi frissítések telepítési sorrendjének meghatározásához, az adott konfigurációnak megfelelően tekintse át az alábbi értékeléseket. A minősítések jelentéséről és meghatározásuk módjáról a [Microsoft biztonsági rések jegyzéke](http://technet.microsoft.com/security/cc998259.aspx) tartalmaz bővebb információt.

Az alábbi oszlopokban a „legújabb szoftver” kifejezés az adott szoftver legutóbb kiadott változatára vonatkozik, a „korábbi szoftver” kifejezés az adott szoftver valamennyi, korábban kiadott támogatott verziójára vonatkozik, amint az az érintett vagy a nem érintett szoftverek felsorolásában szerepel.

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Közlemény azonosítója</th>
<th style="border:1px solid black;" >A biztonsági rés címe</th>
<th style="border:1px solid black;" >CVE-azonosító</th>
<th style="border:1px solid black;" >Kódfuttatás kihasználhatóságának felmérése a legújabb szoftvereknél</th>
<th style="border:1px solid black;" >Kódfuttatás kihasználhatóságának felmérése a korábbi szoftvereknél</th>
<th style="border:1px solid black;" >Szolgáltatásmegtagadás kihasználhatóságának felmérése</th>
<th style="border:1px solid black;" >Fontos megjegyzések</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225825">MS11-070</a></td>
<td style="border:1px solid black;">A WINS jogok helyi kiterjesztését eredményező biztonsági rése</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1984">CVE-2011-1984</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223632">MS11-071</a></td>
<td style="border:1px solid black;">Windows Components nem biztonságos betöltése miatti biztonsági rés</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1991">CVE-2011-1991</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">A biztonsági rés nyilvánosságra került</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Az Excel felszabadítás utáni használatból eredő WriteAV biztonsági rése</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1986">CVE-2011-1986</a></td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Az Excel határokon kívüli tömb elérése miatti biztonsági rése</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1987">CVE-2011-1987</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Az Excel halommemória-sérülést okozó biztonsági rése</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1988">CVE-2011-1988</a></td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> - Valószínűleg inkonzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Az Excel feltételes kifejezések elemzésével kapcsolatos biztonsági rése</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1989">CVE-2011-1989</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Az Excel határokon kívüli tömb elérése miatti biztonsági rése</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1990">CVE-2011-1990</a></td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;">Office-összetevő nem biztonságos függvénytár betöltése miatti biztonsági rése</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1980">CVE-2011-1980</a></td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;">Office nem inicializált objektummutatóval kapcsolatos biztonsági rése</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1982">CVE-2011-1982</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Ideiglenes</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">SharePoint naptárban az XSS miatti biztonsági rés</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0653">CVE-2011-0653</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">HTML-törlés miatti biztonsági rés</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1252">CVE-2011-1252</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Nem valószínű működő rosszindulatú programkód</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Nem valószínű működő rosszindulatú programkód</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">A biztonsági rés illetéktelen adatelérést okoz<br />
<br />
A biztonsági rés nyilvánosságra került</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Az Editform parancsfájlindító biztonsági rése</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1890">CVE-2011-1890</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Kapcsolattartási adatokban a tükröződő XSS miatti biztonsági rés</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1891">CVE-2011-1891</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">SharePoint kiszolgálói fájl illetéktelen távoli elérése miatti biztonsági rés</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1892">CVE-2011-1892</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Nem valószínű működő rosszindulatú programkód</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Nem valószínű működő rosszindulatú programkód</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">A biztonsági rés illetéktelen adatelérést okoz</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">SharePoint kiszolgálói XSS miatti biztonsági rés</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1893">CVE-2011-1893</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Nem érintett</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
</tbody>
</table>
  
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
<th colspan="3">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS11-070**](http://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[**MS11-071**](http://go.microsoft.com/fwlink/?linkid=223632)
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
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=70f944b0-9bf0-4168-b150-67d2ff68df2d)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4b9debed-edbb-43e1-b755-0faf01980289)  
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
[**MS11-070**](http://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[**MS11-071**](http://go.microsoft.com/fwlink/?linkid=223632)
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1e6ac3b2-752e-49a0-84e5-5a8dfe955299)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d44274d2-0401-4fd8-bc4f-c59f6d81c34f)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f9378339-c58e-4e84-9427-85aeb35b0d99)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=935720ee-cee0-42c2-965e-ce1b07e95e1a)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 SP2 Itanium-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=c35c71a8-13b4-47a6-9763-06f6f65327b1)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=78c2ac72-da89-42a4-bff9-79551b5d3c4e)  
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
[**MS11-070**](http://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[**MS11-071**](http://go.microsoft.com/fwlink/?linkid=223632)
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
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=15840336-4886-4a1b-8c1e-2c535c3938f7)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e80739b4-89bb-4317-8381-991244a71cb8)  
(Fontos)
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
[**MS11-070**](http://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[**MS11-071**](http://go.microsoft.com/fwlink/?linkid=223632)
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
Windows Server 2008 32 bites rendszerekhez, Service Pack 2\*
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a9039660-3cc2-470d-a0a5-a70f78074495)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=05c39ab3-7b57-4147-8913-df5df6005799)\*  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 x64-alapú rendszerekhez, Service Pack 2\*
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64-alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5ea78a9b-b1f7-4e94-b69e-c984e1622ae9)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64-alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1499d988-fd55-4317-b859-ec170907d547)\*  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 Itanium-alapú rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 Itanium-alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6e2d2ea9-0af6-4d23-875d-3211722cd62f)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="3">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS11-070**](http://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[**MS11-071**](http://go.microsoft.com/fwlink/?linkid=223632)
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
Windows 7 32 bites rendszerekhez és Windows 7 32 bites rendszerekhez Service Pack 1
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows 7 32 bites rendszerekhez és Windows 7 32 bites rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=76b99ab2-7e99-4aad-a419-7996bae05c48)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 x64 alapú rendszerekhez és Windows 7 x64 alapú rendszerekhez Service Pack 1
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows 7 x64-alapú rendszerekhez és Windows 7 x64-alapú rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=0f6d32de-d3ff-4af9-9b26-a4f12581f5fe)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="3">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS11-070**](http://go.microsoft.com/fwlink/?linkid=225825)
</td>
<td style="border:1px solid black;">
[**MS11-071**](http://go.microsoft.com/fwlink/?linkid=223632)
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
Windows Server 2008 R2 x64 alapú rendszerekhez és Windows Server 2008 R2 x64 alapú rendszerekhez Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64-alapú rendszerekhez és Windows Server 2008 R2 x64-alapú rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f58cf343-946c-4e74-bd9c-40ac934a4986)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64-alapú rendszerekhez és Windows Server 2008 R2 x64-alapú rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a8a451bd-3e5c-4845-9941-daabd9418776)\*  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium alapú rendszerekhez és Windows Server 2008 R2 Itanium alapú rendszerekhez Service Pack 1
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 Itanium-alapú rendszerekhez és Windows Server 2008 R2 Itanium-alapú rendszerekhez, Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=0fdfb1f9-20b3-4d61-8019-33d1003290c8)  
(Fontos)
</td>
</tr>
</table>
 
**Megjegyzések a Windows Server 2008 és Windows Server 2008 R2 rendszerhez**

**\*Érinti a kiszolgálómag telepítését.** Ez a frissítés ugyanolyan biztonsági besorolás mellett, a megadottak szerint érvényes az Windows Server 2008 és a Windows Server 2008 R2 összes támogatott kiadására, függetlenül attól, hogy a kiszolgálómag-telepítési opcióval telepítették-e. Erről a telepítési opcióról bővebben a [Kiszolgálómag-telepítés kezelése](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)és [Kiszolgálómag-telepítés szervizelése](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) TechNet cikkekben olvashat. A kiszolgálómag-telepítési opció nem vonatkozik a Windows Server 2008 és a Windows Server 2008 R2 bizonyos kiadásaira; lásd: [A kiszolgálómag-telepítési opciók összehasonlítása](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Microsoft Office programcsomagok és szoftverek

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="4">
Microsoft Office programcsomagok és összetevők
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS11-072**](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-073**](http://go.microsoft.com/fwlink/?linkid=225103)
</td>
<td style="border:1px solid black;">
[**MS11-074**](http://go.microsoft.com/fwlink/?linkid=204797)
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
<td style="border:1px solid black;">
Nincsenek
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=dee4f3d7-bc4b-47fd-8e3f-9d2b0e82d0f6)  
(KB2553072)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=7faa2f90-2e64-4dbf-ac93-bb8cffc9b5fe)  
(KB2584052)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=498ac241-d728-4944-abac-ec8444ca6418)  
(KB2553073)<sup>[1]</sup>
(Fontos)  
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=df04b9ce-2daa-4b4d-a944-a873075656f9)  
(KB2553089)<sup>[1]</sup>
(Fontos)  
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=90eef02b-db1f-4fdd-bb1d-408063671e4d)  
(KB2553090)<sup>[1]</sup>
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=34bbee95-0e83-4705-8bfe-02e4fb22f8e7)  
(KB2584063)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 és Microsoft Office 2010 Service Pack 1 (32 bites kiadások)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 és Microsoft Excel 2010 Service Pack 1 (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=4612c6e4-ac29-4cc4-9da5-88779ea3643e)  
(KB2553070)  
(Fontos)  
[Microsoft Office 2010 és Microsoft Office 2010 Service Pack 1 (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=1fd15144-5547-4927-8583-8d9b06819226)  
(KB2553091)  
(Fontos)  
[Microsoft Office 2010 és Microsoft Office 2010 Service Pack 1 (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=18840d78-944f-400a-addc-dce7e570a569)  
(KB2553096)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 és Microsoft Office 2010 Service Pack 1 (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=3c8fd04a-9df6-4726-a9bc-811f49665981)  
(KB2584066)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 és Microsoft Office 2010 Service Pack 1 (64 bites kiadások)
</td>
<td style="border:1px solid black;">
[Microsoft Excel 2010 és Microsoft Excel 2010 Service Pack 1 (64 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=d40db27b-1318-4ca7-b44f-c90bb6342109)  
(KB2553070)  
(Fontos)  
[Microsoft Office 2010 és Microsoft Office 2010 Service Pack 1 (64 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=f83800aa-6403-4341-afea-d363e54d5831)  
(KB2553091)  
(Fontos)  
[Microsoft Office 2010 és Microsoft Office 2010 Service Pack 1 (64 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=92787e00-6f30-4020-9c1a-70270be5a623)  
(KB2553096)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 és Microsoft Office 2010 Service Pack 1 (64 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=85360dc1-99e7-4e3e-be6f-3795e8a8122f)  
(KB2584066)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="4">
Microsoft Office for Mac
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS11-072**](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-073**](http://go.microsoft.com/fwlink/?linkid=225103)
</td>
<td style="border:1px solid black;">
[**MS11-074**](http://go.microsoft.com/fwlink/?linkid=204797)
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
Nincsenek
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=868f4d9f-3498-4d59-a017-59204553889c)  
(KB2598782)  
(Fontos)
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
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=afa79cfc-6e8a-4d0b-88aa-0d7e05031e44)  
(KB2598781)  
(Fontos)
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
Microsoft Office for Mac 2011
</td>
<td style="border:1px solid black;">
[Microsoft Office for Mac 2011](http://www.microsoft.com/downloads/details.aspx?familyid=535fcf4a-eeb2-44eb-b2a6-9c512509c49d)  
(KB2598783)  
(Fontos)
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
Open XML File Format Converter for Mac
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=9796588d-238f-4694-9598-1aa8d2becb55)  
(KB2598785)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="4">
Microsoft Office Groove és Microsoft SharePoint Workspace
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS11-072**](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-073**](http://go.microsoft.com/fwlink/?linkid=225103)
</td>
<td style="border:1px solid black;">
[**MS11-074**](http://go.microsoft.com/fwlink/?linkid=204797)
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
Nincsenek
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Groove 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Groove 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5ea6192b-55e5-4ca4-8d91-cc768ede8277)  
(KB2552997)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft SharePoint Workspace 2010 és Microsoft SharePoint Workspace 2010 Service Pack 1 (32 bites kiadások)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Workspace 2010 és Microsoft SharePoint Workspace 2010 Service Pack 1 (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=f6ee7e43-9da9-4b96-abd0-390cfcacb885)  
(KB2566445)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Workspace 2010 és Microsoft SharePoint Workspace 2010 Service Pack 1 (64 bites kiadás)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Workspace 2010 és Microsoft SharePoint Workspace 2010 Service Pack 1 (64 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=234efac1-4f09-41f5-90a9-4a3c2e81c05e)  
(KB2566445)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="4">
Egyéb Microsoft Office szoftver
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS11-072**](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-073**](http://go.microsoft.com/fwlink/?linkid=225103)
</td>
<td style="border:1px solid black;">
[**MS11-074**](http://go.microsoft.com/fwlink/?linkid=204797)
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
<td style="border:1px solid black;">
Nincsenek
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel megjelenítő Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Excel Viewer Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f82ca5da-a55a-487c-8170-46a40000c8e3)  
(KB2553075)  
(Fontos)
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
Microsoft Office kompatibilitási csomag a Word, Excel és a PowerPoint 2007 fájlformátumokhoz Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office kompatibilitási csomag a Word, Excel és PowerPoint 2007 fájlformátumok Service Pack 2 csomagjához](http://www.microsoft.com/downloads/details.aspx?familyid=01093f22-06b7-4c9b-bff9-f54ac5d73bf8)  
(KB2553074)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
</table>
 
**Megjegyzések az MS11-072 közleményhez**

<sup>[1]</sup>A Microsoft Excel 2007 Service Pack 2 felhasználóknak a KB2553073, KB2553089 és KB2553090 frissítésen kívül a Microsoft Office kompatibilitási csomag a Word, Excel és PowerPoint 2007 fájlformátum Service Pack 2 csomagjához (KB2553074) biztonsági frissítését is telepíteniük kell, hogy megvédjék rendszerüket a jelen közleményben ismertetett biztonsági rések hibáitól.

Az ugyanezen a közleményazonosító alatt található, további frissített fájlokat illetően lásd még az egyéb szoftverkategóriák részt ebben a fejezetben, **Érintett szoftverek és letöltési helyek**. Ez a közlemény több szoftverkategóriát ölel fel.

**Megjegyzés az MS11-074 közleményhez**

Az ugyanezen a közleményazonosító alatt található, további frissített fájlokat illetően lásd még az egyéb szoftverkategóriák részt ebben a fejezetben, **Érintett szoftverek és letöltési helyek**. Ez a közlemény több szoftverkategóriát ölel fel.

#### Microsoft Server Software

 
<p> </p>
<table style="border:1px solid black;">
<tr>
<th colspan="3">
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS11-072**](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-074**](http://go.microsoft.com/fwlink/?linkid=204797)
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
Microsoft Office SharePoint Server 2007 Service Pack 2 (32 bites kiadások)
</td>
<td style="border:1px solid black;">
[Microsoft Excel Services](http://www.microsoft.com/downloads/details.aspx?familyid=dd532201-485c-4270-88d3-63bd3f24327e)  
(KB2553093)<sup>[2]</sup>
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=ad52c341-13ce-4b53-87b4-269cb3f41275)  
(KB2508964)<sup>[1]</sup>
(Fontos)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (oserver) (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=fd6189c9-ab3b-441f-a901-6ac7f3b202aa)  
(KB2553001)<sup>[1]</sup>
(Fontos)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (sserverx) (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=d9601fae-4a80-45cd-a49b-ef441856d7e4)  
(KB2553002)<sup>[1]</sup>
(Fontos)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (dlc) (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=55b60e2f-ec68-4ccb-803a-5d03add8a1f1)  
(KB2553003)<sup>[1]</sup>
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2 (64 bites kiadások)
</td>
<td style="border:1px solid black;">
[Microsoft Excel Services](http://www.microsoft.com/downloads/details.aspx?familyid=1086a5b0-e441-4e26-a8d1-924a20121dde)  
(KB2553093)<sup>[2]</sup>
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (64 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=e5e60751-242a-4fdb-9852-6d94050d3d0e)  
(KB2508964)<sup>[1]</sup>
(Fontos)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (oserver) (64 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=b1466366-e2ae-498e-b964-135e034e7348)  
(KB2553001)<sup>[1]</sup>
(Fontos)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (sserverx) (64 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=bb788c8d-8383-4e53-ac05-2a7dd9b83e70)  
(KB2553002)<sup>[1]</sup>
(Fontos)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (dlc) (64 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=e8e1a5bb-a552-45fe-8e81-e05fbfbb57ee)<sup>[1]</sup>
(Fontos)  
(KB2553003)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2010 és Microsoft Office SharePoint Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Excel Services](http://www.microsoft.com/downloads/details.aspx?familyid=0c150328-6a15-4852-a09c-4063142bd946)  
(KB2553094)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2010 és Microsoft Office SharePoint Server 2010 Service Pack 1 (osrchwfe)](http://www.microsoft.com/downloads/details.aspx?familyid=c17eb04d-cbbc-457e-a424-4ee26b7a9654)  
(KB2494022)  
(Fontos)  
[Microsoft Office SharePoint Server 2010 és Microsoft Office SharePoint Server 2010 Service Pack 1 (osrv)](http://www.microsoft.com/downloads/details.aspx?familyid=2a80a849-b712-47d4-9def-9395ee54a265)  
(KB2560885)  
(Fontos)  
[Microsoft Office SharePoint Server 2010 és Microsoft Office SharePoint Server 2010 Service Pack 1 (pplwfe)](http://www.microsoft.com/downloads/details.aspx?familyid=b84c2bcb-0327-4916-871e-7a5c19b8c41b)  
(KB2560890)  
(Fontos)  
[Microsoft Office SharePoint Server 2010 és Microsoft Office SharePoint Server 2010 Service Pack 1 (ppsmawfe)](http://www.microsoft.com/downloads/details.aspx?familyid=1597f295-02a9-4479-9d52-f18f0e83eaba)  
(KB2566456)  
(Fontos)  
[Microsoft Office SharePoint Server 2010 és Microsoft Office SharePoint Server 2010 Service Pack 1 (dlc)](http://www.microsoft.com/downloads/details.aspx?familyid=e6b666a4-a795-441c-9bda-23e2de2e7b05)  
(KB2566954)  
(Fontos)  
[Microsoft Office SharePoint Server 2010 és Microsoft Office SharePoint Server 2010 Service Pack 1 (ppsmamui)](http://www.microsoft.com/downloads/details.aspx?familyid=57592ce4-5d99-45c2-830f-380d67af8899)  
(KB2566958)  
(Fontos)  
[Microsoft Office SharePoint Server 2010 és Microsoft Office SharePoint Server 2010 Service Pack 1 (wosrv)](http://www.microsoft.com/downloads/details.aspx?familyid=dd64a635-1e55-4b4d-9718-9b94c31c5625)  
(KB2566960)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office Forms Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS11-072**](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-074**](http://go.microsoft.com/fwlink/?linkid=204797)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Összesített súlyossági** **besorolás**
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
Microsoft Office Forms Server 2007 Service Pack 2 (32 bites kiadások)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Forms Server 2007 Service Pack 2 (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=c4c8ad7e-50bd-460e-9678-d8c72c6ee7ab)  
(KB2553005)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Forms Server 2007 Service Pack 2 (64 bites kiadások)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Forms Server 2007 Service Pack 2 (64 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=7390b526-f411-45a4-8587-8077b473ac17)  
(KB2553005)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Groove Server
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS11-072**](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-074**](http://go.microsoft.com/fwlink/?linkid=204797)
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
Microsoft Office Groove Data Bridge Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Groove Data Bridge Server 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5958247e-204e-409c-bdc1-7aff06e854b8)  
(KB2552999)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Groove Management Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Groove Management Server 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6b5b4caf-6a95-487d-ac17-c4435225af3a)  
(KB2552998)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Groove Server 2010 és Microsoft Groove Server 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Groove Server 2010 és Microsoft Groove Server 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=71c0f217-5112-4dca-b9aa-46c69f6099e4)  
(KB2508965)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Office Web Apps
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS11-072**](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-074**](http://go.microsoft.com/fwlink/?linkid=204797)
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
Microsoft Office Web Apps 2010 és Microsoft Office Web Apps 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft Excel Web App 2010 és Microsoft Excel Web App 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=73d49094-a9cf-407e-8921-1b22fbc30427)  
(KB2553095)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office Web Apps 2010 és Microsoft Office Web Apps 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=288a7394-b8d5-4445-bd4c-65bbf4b10eaf)  
(KB2566449)  
(Fontos)  
[Microsoft Word Web App 2010 és Microsoft Word Web App 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=152ff9f4-d720-41af-8f89-793133ece037)  
(KB2566450)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="3">
Windows SharePoint Services és Microsoft SharePoint Foundation
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS11-072**](http://go.microsoft.com/fwlink/?linkid=225047)
</td>
<td style="border:1px solid black;">
[**MS11-074**](http://go.microsoft.com/fwlink/?linkid=204797)
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
Microsoft Windows SharePoint Services 2.0
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 2.0](http://www.microsoft.com/downloads/details.aspx?familyid=71e32745-cb05-4b87-a447-741ccdac7450)  
(KB2494007)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32 bites verziók)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32 bites verziók)](http://www.microsoft.com/downloads/details.aspx?familyid=0f306cbd-a652-4e77-b394-1a6dc38ba83c)  
(KB2493987)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64 bites verziók)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64 bites verziók)](http://www.microsoft.com/downloads/details.aspx?familyid=3137e4c6-783d-4461-88bd-90da064e3105)  
(KB2493987)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Foundation 2010 és Microsoft SharePoint Foundation 2010 Service Pack 1
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft SharePoint Foundation 2010 és Microsoft SharePoint Foundation 2010 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=0db799e2-896f-464b-8cd5-ecf2014f0588)  
(KB2494001)  
(Fontos)
</td>
</tr>
</table>
 
**Megjegyzések az MS11-072 közleményhez**

<sup>[2]</sup>A frissítés azokra a kiszolgálókra vonatkozik, amelyekre telepítették az Excel Services szolgáltatást, vagyis a Microsoft Office SharePoint Server 2007 Enterprise és a Microsoft Office SharePoint Server 2007 for Internet Sites alapértelmezett konfigurációira. A Microsoft Office SharePoint Server 2007 Standard nem foglalja magában az Excel Services funkciót.

Az ugyanezen a közleményazonosító alatt található, további frissített fájlokat illetően lásd még az egyéb szoftverkategóriák részt ebben a fejezetben, **Érintett szoftverek és letöltési helyek**. Ez a közlemény több szoftverkategóriát ölel fel.

**Megjegyzések az MS11-074 közleményhez**

<sup>[1]</sup>A Microsoft Office SharePoint Server 2007 támogatott kiadásai esetén a Microsoft Office SharePoint 2007 biztonsági frissítőcsomagjai mellett (KB2508964, KB2553001, KB2553002 és KB2553003) a Microsoft Windows SharePoint Services 3.0 szolgáltatás biztonsági frissítését (KB2493987) is telepíteniük kell a felhasználóknak annak érdekében, hogy védjék rendszerüket a jelen közleményben bemutatott biztonsági rések kockázataitól.

Az ugyanezen a közleményazonosító alatt található, további frissített fájlokat illetően lásd még az egyéb szoftverkategóriák részt ebben a fejezetben, **Érintett szoftverek és letöltési helyek**. Ez a közlemény több szoftverkategóriát ölel fel.

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

A biztonsági frissítésnek Windows Server Update Services szolgáltatással történő központi telepítéséről a [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx) webhelyen tudhat meg többet.

**System Center Configuration Manager 2007**

A Configuration Manager 2007 szoftverfrissítés-kezelés leegyszerűsíti a frissítéseknek a vállalat minden IT-rendszerére történő eljuttatása és kezelése összetett feladatát. A Configuration Manager 2007 segítségével az IT-rendszergazdák a Microsoft-termékek frissítéseit számos készülékre juttathatják el, köztük asztali számítógépekre, hordozható számítógépekre, kiszolgálókra és mobilkészülékekre.

A Configuration Manager 2007 automatizált biztonságirés-elemzése jelzi a frissítések szükségességét és jelentést küld a javasolt lépésekről. A Configuration Manager 2007 szoftverfrissítés-kezelése a Microsoft Windows Software Update Services (WSUS) szolgáltatására épül, amely az IT-rendszergazdák számára világszerte ismerős, jól bevált frissítési infrastruktúra. További információkat a Configuration Manager 2007 rendszergazdai használatáról a frissítések telepítéséhez lásd: [Szoftverfrissítés-kezelés](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). További információkért a Configuration Manager alkalmazásról látogasson el a [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx) oldalra.

**Systems Management Server 2003**

A Microsoft Systems Management Server (SMS) rendszer egy sokoldalúan beállítható vállalati megoldás, amely a frissítések kezelésére szolgál. Az SMS segítségével a rendszergazda megállapíthatja, hogy melyik Windows alapú számítógép szorul biztonsági frissítésre, és ezeket a frissítéseket szabályozott módon, a felhasználók minimális zavarásával központilag telepítheti a vállalat teljes informatikai környezetében.

**Megjegyzés** A System Management Server 2003 rendszer általános támogatása 2010. január 12-én lejár. Ha többet szeretne tudni a Windows termékek életciklusáról, keresse fel a [Microsoft támogatási életciklusokkal foglalkozó webhelyét](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Az SMS, vagyis a System Center Configuration Manager 2007 újabb kiadása már elérhető, lásd a korábbi, **System Center Configuration Manager 2007** c. részben.

Ha többet szeretne tudni arról, hogy a rendszergazdák miként telepíthetik a biztonsági frissítéseket az SMS 2003 alkalmazással, látogasson el a [Forgatókönyvek és eljárások a Microsoft Systems Management Server 2003 alkalmazáshoz Szoftverterjesztés és javításkezelés](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) oldalra. Az SMS-szolgáltatásról bővebben a [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx) oldalán olvashat.

**Megjegyzés** Az SMS a Microsoft Baseline Security Analyzer eszközön keresztül széles körű támogatást nyújt a biztonsági közlemények frissítéseinek észleléséhez, valamint a frissítések telepítéséhez. Előfordulhat, hogy egyes szoftverfrissítéseket ezek az eszközök nem észlelnek. Az SMS-alkalmazás leltározási szolgáltatásai segítségével a rendszergazdák adott rendszereken hajthatják végre a frissítést. Az eljárással kapcsolatban olvassa el a [szoftverfrissítések telepítése az SMS szoftverelosztó ügynök segítségével](http://go.microsoft.com/fwlink/?linkid=33341) című tájékoztatót. Egyes biztonsági frissítésekhez rendszergazdai jogosultságokra van szükség a számítógép újraindítása után. A rendszergazdák az Elevated Rights Deployment Tool eszközt (az [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en) része) alkalmazhatják a frissítések telepítéséhez.

**Az Update Compatibility Evaluator (a frissítéskompatibilitás kiértékelője) és az Application Compatibility Toolkit (alkalmazáskompatibilitási eszközkészlet)**

Az alkalmazások működése érdekében a frissítések gyakran írnak ugyanazokba a fájlokba, illetve regisztrációs bejegyzésekbe. Ez inkompatibilitást okozhat, és növelheti a biztonsági frissítések központi telepítésére használt időt. A Windows frissítések és az alkalmazásoknak való megfelelőség tesztelése és ellenőrzése egyszerűsíthető az [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) eszközeivel, ami része az [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) alkalmazáskompatibilitási eszközkészletnek.

Az Application Compatibility Toolkit (ACT) tartalmazza a Microsoft Windows Vista, a Windows Update, a Microsoft Security Update vagy a Windows Internet Explorer új verziójának központi telepítése előtt az alkalmazáskompatibilitási problémák kiértékeléséhez és enyhítéséhez szükséges eszközöket és dokumentációt.

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

-   A biztonsági frissítések a [Microsoft letöltőközpontban](http://go.microsoft.com/fwlink/?linkid=21129) érhetők el. Legegyszerűbben a „security update” kifejezésre irányuló kulcsszavas kereséssel találhatja meg ezeket.
-   Az ügyfélrendszerek frissítései a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) oldalról elérhetőek.
-   A Windows Update szolgáltatáson keresztül terjesztett havi aktuális biztonsági frissítések a letöltőközpontból a biztonsági és kritikus frissítéseket tartalmazó ISO CD-képfájlként is letölthetőek. További információt a [Microsoft Tudásbázis 913086](http://support.microsoft.com/kb/913086) számú cikkében talál.

**IT Pro Security közösség**

Az [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) közösségben hasznos információt találhat a biztonság javításáról és az informatikai infrastruktúrák optimalizálásáról, továbbá eszmecserét folytathat a biztonsági kérdésekről más informatikai szakemberekkel.

#### Köszönetnyilvánítás

A Microsoft [köszönetét](http://go.microsoft.com/fwlink/?linkid=21127) fejezi ki a vásárlók védelmének biztosításában nyújtott segítségért az alábbi szervezet(ek)nek és szakember(ek)nek:

-   Nicolas Economou, [Core Security Technologies](http://www.coresecurity.com/), az MS11-070 közleményben ismertetett probléma jelentéséért
-   A [VeriSign iDefense Labs](http://labs.idefense.com/) anonim együttműködő partnerének az MS11-072 közleményben ismertetett probléma jelentéséért
-   Sean Larsson, [VeriSign iDefense Labs](http://labs.idefense.com/), az MS11-072 közleményben bemutatott probléma jelentéséért
-   A [VeriSign iDefense Labs](http://labs.idefense.com/) anonim együttműködő partnerének az MS11-072 közleményben ismertetett probléma jelentéséért
-   A [Tipping Point](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) programjában részt vevő anonim kutató, az MS11-072 közleményben ismertetett probléma jelentéséért
-   Omair, a [TippingPoint](http://www.tippingpoint.com/)[](http://www.zerodayinitiative.com/)Zero Day Initiative programjával együttműködésben, az MS11-072 közleményben ismertetett probléma jelentéséért
-   Parvez Anwar, [Secunia Research](http://secunia.com/) az MS11-073 közleményben leírt probléma jelentéséért
-   David Warren, [CERT/CC](http://www.cert.org/), az MS11-073 közleményben ismertetett probléma jelentéséért
-   Andrew Connell, [Critical Path Training, LLC](http://www.criticalpathtraining.com/), az MS11-074 közleményben ismertetett probléma jelentéséért
-   David Feldman, [Raytheon](http://www.raytheon.com/), az MS11-074 közleményben ismertetett probléma jelentéséért
-   Adi Cohen, [IBM Rational Application Security](http://blog.watchfire.com/), az MS11-074 közleményben ismertetett probléma jelentéséért
-   [Trend Micro](http://www.trendmicro.com/), az MS11-074 közleményben ismertetett probléma közös megoldásában való részvételéért
-   Pedro Jimenez, [ITT](http://www.itt.com/), az MS11-074 közleményben ismertetett probléma jelentéséért
-   [A Seeker automatikus alkalmazásbiztonság-tesztelő megoldása](http://www.seekersec.com/), az MS11-074 közleményben ismertetett probléma jelentéséért
-   Nicolas Grégoire, [Agarri](http://www.agarri.fr/), az MS11-074 közleményben ismertetett probléma jelentéséért
-   Jim LaValley, [LaValley Consulting, LLC](http://www.lavalley.net), az MS11-074 közleményben ismertetett probléma jelentéséért
-   Irene Abezgauz, [Seeker](http://www.seekersec.com), az MS11-074 közleményben ismertetett probléma miatti mélyreható védelmi módosítások kialakításában való közreműködésért

#### Terméktámogatás

-   Teszteléssel állapították meg a felsorolt szoftverek egyes verzióinak érintettségét. A többi verzió támogatási életciklusa végére ért. Az egyes szoftververziók támogatási életciklusáról a [Microsoft termékek terméktámogatási életciklusát ismertető webhelyen](http://go.microsoft.com/fwlink/?linkid=21742) talál felvilágosítást.
-   Az Amerikai Egyesült Államokban és Kanada területén élő ügyfelek technikai támogatást kérhetnek a [biztonsági támogatás szolgáltatójától](http://go.microsoft.com/fwlink/?linkid=21131) vagy az 1-866-PCSAFETY telefonszámon. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. Az elérhető támogatási lehetőségekről további információt talál a [Microsoft segítségnyújtással és támogatással foglalkozó webhelyén](http://support.microsoft.com/).
-   Más országokban a helyi Microsoft-képviseletek nyújtanak támogatást. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. A [nemzetközi támogatási webhely](http://go.microsoft.com/fwlink/?linkid=21155) felvilágosítást nyújt arról, támogatási kérdéseivel hogyan fordulhat a Microsofthoz.

#### Felelősséget kizáró nyilatkozat

A Microsoft Tudásbázisban leírtak előzetes bejelentés nélkül változhatnak, és a cikkek tartalmáért a Microsoft nem vállal garanciát. A Microsoft egyben elhárít minden kifejezett és értelemszerű garanciát, beleértve az eladhatóságra és az adott célra való alkalmasságra vonatkozó garanciát is. A Microsoft Corporation vagy annak szállítói semmilyen körülmények között nem tehetők felelőssé közvetlen, közvetett, eseti, ok-okozati vagy különleges kárért (beleértve az elmaradt hasznot is), még akkor sem, ha a Microsoft Corporation vagy szállítói tudatában voltak a kár lehetséges voltának. Egyes államok törvényi szabályozása nem teszi lehetővé a véletlen vagy ok-okozati károkért vállalt felelősség korlátozását vagy kizárását, így ezekben az államokban az ez a felelősségkizárás nincs érvényben.

#### Verziók

-   1.0 verzió (2011. szeptember 13.): Összefoglaló közlemény közzététele.
-   1.1 verzió (2011. szeptember 13.): Az MS11-074 közlemény a Microsoft Office SharePoint Server 2010 és Microsoft Office SharePoint Server 2010 Service Pack 1 (pplwfe) (KB2560890) frissítéshez tartozó hivatkozással és csomaginformációkkal bővült.

*Built at 2014-04-18T01:50:00Z-07:00*
