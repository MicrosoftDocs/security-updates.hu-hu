---
TOCTitle: 'MS08-DEC'
Title: 'Microsoft biztonsági közlemény - összefoglalás, december 2008'
ms:assetid: 'ms08-dec'
ms:contentKeyID: 61227718
ms:mtpsurl: 'https://technet.microsoft.com/hu-HU/library/ms08-dec(v=Security.10)'
author: SharonSears
ms.author: SharonSears
---

Security Bulletin Summary

Microsoft biztonsági közlemény - összefoglalás, december 2008
=============================================================

Közzétéve: 2008. december 9. | Frissítve: 2009. április 29.

**Verzió:** 6.0

Az összefoglaló a 2008 decemberében kiadott biztonsági közleményeket összegzi.

A 2008. decemberi közlemények kiadása folytán az összefoglaló a 2008. december 4-én kiadott előzetes értesítés helyébe lép. További információk a biztonsági közlemények kiadásáról szóló előzetes értesítés szolgáltatásról lásd: [Előzetes értesítés a Microsoft biztonsági közleményeinek kiadásáról](http://technet.microsoft.com/security/bulletin/advance).

Ha automatikus értesítést szeretne kapni a Microsoft biztonsági közleményeinek megjelenéséről, fizessen elő a [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) szolgáltatásra.

A közleményekkel kapcsolatos kérdések megválaszolására a Microsoft 2008. december 10-én, csendes-óceáni idő szerint 11 órakor webszemináriumot tart. [Jelentkezzen most a decemberi közleményeket bemutató webes szemináriumra](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374647). Ezt követően a webes szeminárium igény szerint kerül megrendezésre. További információkért látogasson el a [Microsoft biztonsági közleményeit és a webes szemináriumokat](http://technet.microsoft.com/security/bulletin/summary)bemutató oldalra.

A Microsoft két webes szemináriumot szervez az összefoglaló közlemény 3.0 verzióját kiegészítő, soron kívüli biztonsági közlemény (MS08-078) kapcsán, melynek során a felhasználók választ kaphatnak a közleményekkel kapcsolatos kérdéseikre: 2008. december 17-én csendes-óceáni idő (Egyesült Államok és Kanada) szerint 13 órakor és 2008. december 18-án 11 órakor. Regisztráljon a [december 17-ei](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032399448&culture=en-us) vagy a [december 18-ai webes szemináriumra](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032399449&culture=en-us). Később igény szerint szervezünk további webes szemináriumokat. További információkért látogasson el a [Microsoft biztonsági közleményeit és a webes szemináriumokat](http://technet.microsoft.com/security/bulletin/summary)bemutató oldalra.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125440">MS08-071</a></td>
<td style="border:1px solid black;"><strong>A GDI képmegjelenítő biztonsági rései távolról történő kódfuttatást tesznek lehetővé (956802)</strong><br />
<br />
Ez a biztonsági frissítés a GDI képmegjelenítő két közvetlenül jelzett biztonsági rését szünteti meg. A biztonsági réseket kihasználó támadó távoli kódvégrehajtást végezhet, amennyiben a felhasználó egy különlegesen kialakított WMF képfájlt nyit meg. A biztonsági réseket kihasználó támadó teljes mértékben átveheti az érintett rendszer irányítását. Ezt követően a támadó programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132148">MS08-075</a></td>
<td style="border:1px solid black;"><strong>A Windows Search biztonsági rései távoli programkódfuttatásra adhatnak lehetőséget (959349)</strong><br />
<br />
Ez a biztonsági frissítés a Windows Search két közvetlenül jelzett biztonsági rését szünteti meg. A biztonsági rések távoli kódfuttatást tehetnek lehetővé, ha a felhasználó a Windows Explorer programban megnyit és ment egy különleges kialakítású mentett keresési fájlt, vagy rákattint egy különleges kialakítású keresési URL-címre. A biztonsági réseket kihasználó támadó teljes mértékben átveheti az érintett rendszer irányítását. Ezt követően a támadó programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td style="border:1px solid black;"><strong>Összesítő biztonsági frissítés az Internet Explorer programhoz (958215)</strong><br />
<br />
Ez a kritikus besorolású frissítés négy közvetlenül jelzett biztonsági rést szüntet meg. A biztonsági rések mindegyike távoli kódvégrehajtást tehet lehetővé, amennyiben a felhasználó egy különlegesen kialakított weboldalt tekint meg az Internet Explorer alkalmazás segítségével. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=137335">MS08-078</a></td>
<td style="border:1px solid black;"><strong>Biztonsági frissítés az Internet Explorer programhoz (960714)</strong><br />
<br />
Ez a biztonsági frissítés egy nyilvánosan jelentett biztonsági rést szüntet meg. A biztonsági rés távoli kódvégrehajtást tehet lehetővé, amennyiben a felhasználó egy különlegesen kialakított weboldalt tekint meg az Internet Explorer alkalmazás segítségével. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td style="border:1px solid black;"><strong>A Visual Basic 6.0 Runtime kiterjesztett fájljai (ActiveX-vezérlők) biztonsági rései távoli kódfuttatást tehetnek lehetővé (932349)</strong><br />
<br />
A biztonsági frissítés öt közvetlenül és egy nyilvánosan jelentett biztonsági rést hárít el a Microsoft Visual Basic 6.0 Runtime kiterjesztett fájljainak ActiveX-vezérlőivel kapcsolatban. A biztonsági rések távoli kódfuttatást tehetnek lehetővé, ha a felhasználó egy különlegesen kialakított weboldalra látogat. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft fejlesztői eszközök és szoftver, Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Office Word biztonsági rései távolról történő programkódfuttatást tehetnek lehetővé (957173)</strong><br />
<br />
A biztonsági frissítés a Microsoft Office Word és Microsoft Office Outlook nyolc közvetlenül jelentett biztonsági rését szünteti meg, amelyek távoli kódfuttatást tehetnek lehetővé, ha a felhasználó egy speciálisan létrehozott Word vagy Rich Text formátumú (RTF) fájlt nyit meg. A biztonsági réseket kihasználó támadó teljes mértékben átveheti az érintett rendszer irányítását. Ezt követően a támadó programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Office Excel biztonsági rése távolról történő programkódfuttatást tehet lehetővé (959070)</strong><br />
<br />
A kritikus biztonsági frissítés a Microsoft Office Excel közvetlenül a Microsoftnak jelzett három biztonsági rését szünteti meg, melyek távoli kódfuttatást tesznek lehetővé, ha a felhasználó megnyit egy speciálisan létrehozott Excel fájlt. A biztonsági réseket kihasználó támadó teljes mértékben átveheti az érintett rendszer irányítását. Ezt követően a támadó programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126307">MS08-077</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Office SharePoint Server biztonsági rései jogok kiterjesztését okozhatják (957175)</strong><br />
<br />
Ez a biztonsági frissítés egy közvetlenül jelzett biztonsági rést szüntet meg. A biztonsági rés lehetővé teheti a jogok kiterjesztését, ha a támadó kikerüli a hitelesítést egy felügyeleti URL-címre vagy SharePoint-webhelyre navigálva a böngészővel. A jogok kiterjesztéséhez vezető sikeres támadás következménye szolgáltatásmegtagadás vagy adatokhoz való illetéktelen hozzáférés lehet.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Jogok kiterjesztése</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Office, Microsoft Server Software</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125419">MS08-076</a></td>
<td style="border:1px solid black;"><strong>A Windows Media Components biztonsági rései távoli programkódfuttatást tesznek lehetővé (959807)</strong><br />
<br />
Ez a biztonsági frissítés a a következő Windows Media összetevők két közvetlenül jelzett biztonsági rését szünteti meg: Windows Media Player, Windows Media Format Runtime és Windows Media Services. A legsúlyosabb besorolású biztonsági rés távolról történő kódfuttatást tehet lehetővé. Ha valamely felhasználó felügyeleti jogosultságokkal bejelentkezett a rendszerbe, akkor a biztonsági rést kihasználó támadó teljes mértékben átveheti az irányítást a számítógép felett, Ezt követően a támadó programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Kihasználhatósági információk  
-----------------------------
  
<span></span>
**A táblázat használata**
  
A táblázat segítségével meghatározható annak valószínűsége, hogy a biztonsági közlemény kiadását követő 30 napon belül a telepíteni szükséges biztonsági frissítésekre működő rosszindulatú programkódot jelentetnek meg. A telepítés fontossági sorrendjének megállapításához az adott konfigurációnak megfelelően tekintse át az alábbi értékeléseket. A minősítések jelentéséről és meghatározásuk módjáról a [Microsoft biztonsági rések jegyzéke](http://technet.microsoft.com/en-us/security/cc998259.aspx) tartalmaz bővebb információt.

 
<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Közlemény azonosítója</th>
<th style="border:1px solid black;" >Közlemény címe</th>
<th style="border:1px solid black;" >CVE-azonosító</th>
<th style="border:1px solid black;" >Kihasználhatósági információk értékelése</th>
<th style="border:1px solid black;" >Fontos megjegyzések</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td style="border:1px solid black;">A Visual Basic 6.0 futtatórendszer kiterjesztett fájljai (ActiveX-vezérlők) biztonsági rései távoli kódfuttatást tehetnek lehetővé (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3704">CVE-2008-3704</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">A kihasználható rosszindulatú kód nyilvánosan beszerezhető</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td style="border:1px solid black;">A Visual Basic 6.0 futtatórendszer kiterjesztett fájljai (ActiveX-vezérlők) biztonsági rései távoli kódfuttatást tehetnek lehetővé (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4252">CVE-2008-4252</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td style="border:1px solid black;">A Visual Basic 6.0 futtatórendszer kiterjesztett fájljai (ActiveX-vezérlők) biztonsági rései távoli kódfuttatást tehetnek lehetővé (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4256">CVE-2008-4256</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td style="border:1px solid black;">A Visual Basic 6.0 futtatórendszer kiterjesztett fájljai (ActiveX-vezérlők) biztonsági rései távoli kódfuttatást tehetnek lehetővé (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4253">CVE-2008-4253</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Valószínűleg inkonzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td style="border:1px solid black;">A Visual Basic 6.0 futtatórendszer kiterjesztett fájljai (ActiveX-vezérlők) biztonsági rései távoli kódfuttatást tehetnek lehetővé (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4254">CVE-2008-4254</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Valószínűleg inkonzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130478">MS08-070</a></td>
<td style="border:1px solid black;">A Visual Basic 6.0 futtatórendszer kiterjesztett fájljai (ActiveX-vezérlők) biztonsági rései távoli kódfuttatást tehetnek lehetővé (932349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4255">CVE-2008-4255</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Valószínűleg inkonzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">A legjobban fenyegetett rendszer a Windows 2000. A Windows XP SP2, Windows Server 2003 SP1 és az ezeknél újabb rendszerek a hatékonyabb védelem miatt nem valószínu, hogy fenyegetettek.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125440">MS08-071</a></td>
<td style="border:1px solid black;">A GDI képmegjelenítő biztonsági rései távolról történő kódfuttatást tesznek lehetővé (956802)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3465">CVE-2008-3465</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Valószínűleg inkonzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125440">MS08-071</a></td>
<td style="border:1px solid black;">A GDI képmegjelenítő biztonsági rései távolról történő kódfuttatást tesznek lehetővé (956802)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2249">CVE-2008-2249</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Nem valószínű működő rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">A Microsoft Office Word biztonsági rései távolról történő programkódfuttatást tehetnek lehetővé (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4024">CVE-2008-4024</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">A Microsoft Office Word biztonsági rései távolról történő programkódfuttatást tehetnek lehetővé (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4025">CVE-2008-4025</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Valószínűleg inkonzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">A Microsoft Office Word biztonsági rései távolról történő programkódfuttatást tehetnek lehetővé (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4026">CVE-2008-4026</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Valószínűleg inkonzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">A Microsoft Office Word biztonsági rései távolról történő programkódfuttatást tehetnek lehetővé (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4027">CVE-2008-4027</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Valószínűleg inkonzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">A Microsoft Office Word biztonsági rései távolról történő programkódfuttatást tehetnek lehetővé (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4028">CVE-2008-4028</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Valószínűleg inkonzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">A Microsoft Office Word biztonsági rései távolról történő programkódfuttatást tehetnek lehetővé (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4030">CVE-2008-4030</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Valószínűleg inkonzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">A Microsoft Office Word biztonsági rései távolról történő programkódfuttatást tehetnek lehetővé (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4837">CVE-2008-4837</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Valószínűleg inkonzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126306">MS08-072</a></td>
<td style="border:1px solid black;">A Microsoft Office Word biztonsági rései távolról történő programkódfuttatást tehetnek lehetővé (957173)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4031">CVE-2008-4031</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> - Nem valószínű működő rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td style="border:1px solid black;">Összesítő biztonsági frissítés az Internet Explorer programhoz (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4258">CVE-2008-4258</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td style="border:1px solid black;">Összesítő biztonsági frissítés az Internet Explorer programhoz (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4259">CVE-2008-4259</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td style="border:1px solid black;">Összesítő biztonsági frissítés az Internet Explorer programhoz (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4261">CVE-2008-4261</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=133437">MS08-073</a></td>
<td style="border:1px solid black;">Összesítő biztonsági frissítés az Internet Explorer programhoz (958215)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4260">CVE-2008-4260</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Valószínűleg inkonzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td style="border:1px solid black;">A Microsoft Office Excel biztonsági rése távolról történő programkódfuttatást tehet lehetővé (959070)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4265">CVE-2008-4265</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td style="border:1px solid black;">A Microsoft Office Excel biztonsági rése távolról történő programkódfuttatást tehet lehetővé (959070)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4266">CVE-2008-4266</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=131481">MS08-074</a></td>
<td style="border:1px solid black;">A Microsoft Office Excel biztonsági rése távolról történő programkódfuttatást tehet lehetővé (959070)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4264">CVE-2008-4264</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Valószínűleg inkonzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132148">MS08-075</a></td>
<td style="border:1px solid black;">A Windows Search biztonsági rései távoli programkódfuttatásra adhatnak lehetőséget (959349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4269">CVE-2008-4269</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=132148">MS08-075</a></td>
<td style="border:1px solid black;">A Windows Search biztonsági rései távoli programkódfuttatásra adhatnak lehetőséget (959349)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4268">CVE-2008-4268</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Valószínűleg inkonzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">(Nincs)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125419">MS08-076</a></td>
<td style="border:1px solid black;">A Windows Media Components biztonsági rései távoli programkódfuttatást tesznek lehetővé (959807)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3009">CVE-2008-3009</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Konzisztens rosszindulatú kód létrehozható. Azonban a támadások korlátozott jellege miatt a valód fenyegetettség nagyon alacsony.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125419">MS08-076</a></td>
<td style="border:1px solid black;">A Windows Media Components biztonsági rései távoli programkódfuttatást tesznek lehetővé (959807)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-3010">CVE-2008-3010</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Konzisztens rosszindulatú kód létrehozható. Azonban a támadások korlátozott jellege miatt a valód fenyegetettség nagyon alacsony.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=126307">MS08-077</a></td>
<td style="border:1px solid black;">A Microsoft Office SharePoint Server biztonsági rései jogok kiterjesztését okozhatják (957175)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4032">CVE-2008-4032</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Valószínűleg konzisztens rosszindulatú programkód</td>
<td style="border:1px solid black;">Konzisztens rosszindulatú kód létrehozható. Azonban a kódot kihasználó támadások legvalószínűbben csak adatokhoz való illetéktelen hozzáférést okozhatnak, nem pedig programkód távoli futtatását.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=137335">MS08-078</a></td>
<td style="border:1px solid black;">Biztonsági frissítés az Internet Explorer programhoz (960714)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4844">CVE-2008-4844</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> - Valószínűleg konzisztens rosszindulatú programkód<br />
(A közlemény kiadásakor nyilvános)</td>
<td style="border:1px solid black;">Aktív támadások esetében felfedeztünk már konzisztens rosszindulatú programkódot. Azonban mivel az Internet Explorer alkalmazás a Windows Vista és Windows Server 2008 rendszerben alapértelmezésben Védett módban fut, ez megnehezíti a biztonsági rés kihasználását.</td>
</tr>
</tbody>
</table>
  
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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="6">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://go.microsoft.com/fwlink/?linkid=125440)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://go.microsoft.com/fwlink/?linkid=132148)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://go.microsoft.com/fwlink/?linkid=133437)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://go.microsoft.com/fwlink/?linkid=137335)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://go.microsoft.com/fwlink/?linkid=125419)
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
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=3b775fb1-1077-455d-af4a-4ccb5237974f)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=c242ba42-556b-4c87-bf33-9d99166ff096)  
(Kritikus)  
[Microsoft Internet Explorer 6 Service Pack 1 szervizcsomaggal](http://www.microsoft.com/downloads/details.aspx?familyid=c0583745-7e57-4265-9429-c3415cb8465f)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=d3e18732-47f1-40ce-999c-d1fd283bf138)  
(Kritikus)  
[Microsoft Internet Explorer 6 Service Pack 1 szervizcsomaggal](http://www.microsoft.com/downloads/details.aspx?familyid=124c14b6-9323-4f6f-902b-727aa56444bc)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=c33d558e-45f9-4e85-b48c-03bd0e8cb4bc)  
(KB954600)  
(Fontos)  
[Windows Media Format Runtime 7.1 és Windows Media Format Runtime 9.0](http://www.microsoft.com/downloads/details.aspx?familyid=6a459497-0ab8-41cb-87d0-b551631d8d8a)  
(KB952069)  
(Fontos)  
[Windows Media Services 4.1](http://www.microsoft.com/downloads/details.aspx?familyid=58b7d241-cef6-48fa-aa52-017695f71db1)  
(KB952068)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="6">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://go.microsoft.com/fwlink/?linkid=125440)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://go.microsoft.com/fwlink/?linkid=132148)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://go.microsoft.com/fwlink/?linkid=133437)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://go.microsoft.com/fwlink/?linkid=137335)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://go.microsoft.com/fwlink/?linkid=125419)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 és Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 és Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2151fbba-c464-4d1e-82d4-5b096e82bed0)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=af9a6cb0-725d-490c-9858-16ec40e98560)  
(Kritikus)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=1b582695-b3cc-4c65-bc4b-d673c9a6d82a)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=1d83e0af-46fa-4bfc-ba57-635435a7ef2d)  
(Kritikus)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=0190a289-164e-41a7-8c01-fa1aaed3f531)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=99241309-e644-4088-a8f3-38837fab4037)  
(KB954600)  
(Fontos)  
[Windows Media Format Runtime 9.0, Windows Media Format Runtime 9.5 és Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=504f816c-f554-4b93-ac28-b085574d9bac)  
(csak Windows XP Service Pack 2 rendszerben)  
(KB952069)  
(Fontos)  
[Windows Media Format Runtime 9.0, Windows Media Format Runtime 9.5 és Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=ad76fcf3-a2f9-4e36-bd1b-c1536749173c)  
(csak Windows XP Service Pack 3 rendszerben)  
(KB952069)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition és Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition és Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2247f6a5-aa33-4c68-9ea8-a63488d126d3)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=60bf9851-24fe-4658-8333-d353e82063c7)  
(Kritikus)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=107cf54b-29d4-4c54-b091-2b5b3ffbf49d)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=a585cb73-2c1a-4fa8-862a-ad6aeaeaf2f8)  
(Kritikus)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=9ba71e23-8cef-4399-b215-983b0dcf5cb5)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=946d47c9-b208-4fab-8ef6-774413d61bc8)  
(KB954600)  
(Fontos)  
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=644ef023-ee40-45b0-9c9d-c76d9fab0005)  
(KB952069)  
(Fontos)  
[Windows Media Format Runtime 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=ae9e8b07-5354-42f3-a226-ba2193244524)  
(KB952069)  
(Fontos)  
[Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=2dadc017-2be5-4240-ab8f-0291756dca6b)  
(KB952069)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://go.microsoft.com/fwlink/?linkid=125440)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://go.microsoft.com/fwlink/?linkid=132148)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://go.microsoft.com/fwlink/?linkid=133437)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://go.microsoft.com/fwlink/?linkid=137335)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://go.microsoft.com/fwlink/?linkid=125419)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2 rendszerhez
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 és Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0c396796-0929-4cd2-99e8-3c0f7075a89e)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=d53adf6f-9501-4862-a1ca-57eb4d40cd75)  
(Mérsékelt)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=9cdd4f9e-c578-405c-af9e-628f2d77fdf4)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=d81e9cf9-ce0c-463a-a359-49a348cb89ae)  
(Kritikus)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=388847ec-817e-45cf-8fa7-32c7e1f57f80)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=2315ce20-2f46-42c2-bb40-045f003409d7)  
(KB954600)  
(Fontos)  
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=d8958248-c889-499e-a6a9-3b394cdb27ea)  
(KB952069)  
(Fontos)  
[Windows Media Services 9 Series](http://www.microsoft.com/downloads/details.aspx?familyid=e71abc2d-d60e-444a-9b7b-062c5805fe9e)  
(KB952068)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2 rendszerhez
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6d5c7d2f-1a82-4cdf-b3f2-b2c2390c6a64)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=5e37cb34-32be-4bbe-87f3-c4e1974e4d00)  
(Mérsékelt)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7c36f92c-d8a0-4b70-b85f-83588a0299a0)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=015df302-d79f-43a1-b5c5-32ac04de0510)  
(Kritikus)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=2ae17caf-6204-470e-8480-380d3d505657)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Media Player 6.4](http://www.microsoft.com/downloads/details.aspx?familyid=4c29bed9-1b88-4d2f-80a5-305c2bedd89f)  
(KB954600)  
(Fontos)  
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=2278022e-a716-46c0-bedf-d626933bd815)  
(KB952069)  
(Fontos)  
[Windows Media Format Runtime 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=ae9e8b07-5354-42f3-a226-ba2193244524)  
(KB952069)  
(Fontos)  
[Windows Media Services 9 Series](http://www.microsoft.com/downloads/details.aspx?familyid=e0030155-1a9a-46cc-bbc8-6d0d1ed65c1f)  
(KB952068)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 SP1 Itanium alapú rendszerekhez és Windows Server 2003 SP2 Itanium alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP1 Itanium alapú rendszerekhez és Windows Server 2003 SP2 Itanium alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=1edb62b4-3d0f-4891-b4b3-8f8bc4e7bdfe)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=0da4e424-4682-4401-a226-7d8f1be19d44)  
(Mérsékelt)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3811030d-5958-4b91-b5b8-20587dc7c4d6)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=18016305-7f72-47f6-ab4c-94282289bf5f)  
(Kritikus)  
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=97d6c093-f68d-4ddf-8e3c-f29662a1940f)  
(Kritikus)
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
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://go.microsoft.com/fwlink/?linkid=125440)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://go.microsoft.com/fwlink/?linkid=132148)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://go.microsoft.com/fwlink/?linkid=133437)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://go.microsoft.com/fwlink/?linkid=137335)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://go.microsoft.com/fwlink/?linkid=125419)
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
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista és Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista és Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=cddf9cf6-bdeb-4429-823a-879387a428d7)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Vista és Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=0dcc5373-0435-42d5-864d-298e5bb122d9)  
(KB958623)  
(Fontos)  
[Windows Vista és Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5b1b65f0-6848-47c6-bdd5-be3c0621b323)  
(KB958624)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=3f62030a-9ce2-4c92-b948-143a6881921e)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=7887111d-4fac-4823-bdd2-a18d9468fdf0)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=1fcdc8dd-26d9-4d1a-8b3f-7b6a21a95999)  
(KB952069)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition és Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition és Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=73dc3775-b6f0-40f1-bd36-6b5fb80eb2fa)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition és Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2112c5c8-7c9f-4491-b127-b1093085e105)  
(KB958623)  
(Fontos)  
[Windows Vista x64 Edition és Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=eb1d0ffe-1644-457b-9e82-768bd4c7f7ab)  
(KB958624)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d8800493-fba4-41f8-bde5-a53eeaf89d54)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=69979d92-8d45-47fe-ac4c-c2f1f23cf1fb)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=8839f6cd-dfbf-448c-bf1e-1da9bb5f3f25)  
(KB952069)  
(Fontos)
</td>
</tr>
<tr>
<th colspan="6">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-071**](http://go.microsoft.com/fwlink/?linkid=125440)
</td>
<td style="border:1px solid black;">
[**MS08-075**](http://go.microsoft.com/fwlink/?linkid=132148)
</td>
<td style="border:1px solid black;">
[**MS08-073**](http://go.microsoft.com/fwlink/?linkid=133437)
</td>
<td style="border:1px solid black;">
[**MS08-078**](http://go.microsoft.com/fwlink/?linkid=137335)
</td>
<td style="border:1px solid black;">
[**MS08-076**](http://go.microsoft.com/fwlink/?linkid=125419)
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
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 32 bites rendszerekhez
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=bbed9e8b-e75e-44ef-ba1d-fd6f852c1f67)\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=90ab7e6f-5ae7-4f55-8838-868fc98d8a16)\*\*\*  
(KB958623)  
(Fontos)  
[Windows Server 2008 32 bites rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=470d506f-77ae-4a44-8598-df645f484295)\*\*\*  
(KB958624)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=45a0de3c-c7d1-4314-a456-1f7428b7c90a)\*\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=5552e564-dd1c-4e2a-9a42-6317522c884d)\*\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=91ec4195-bc1c-444e-a7b0-ebde46c088fa)  
(KB952069)  
(Fontos)  
[Windows Media Services 2008](http://www.microsoft.com/downloads/details.aspx?familyid=ffb5d945-7f98-4849-b020-ed4873fa42df)\*  
(KB952068)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 32 bites rendszerekhez, Service Pack 2\*
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Media Services 2008](http://www.microsoft.com/downloads/details.aspx?familyid=ffb5d945-7f98-4849-b020-ed4873fa42df)\*  
(KB952068)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 x64 alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=48aecf4c-1296-490d-ba37-a28e3ec19bd6)\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=e1deab57-ada2-4b12-9157-5615e7b0071d)\*\*\*  
(KB958623)  
(Fontos)  
[Windows Server 2008 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=e41f23e4-6a2f-4ebb-b425-d241a08da316)\*\*\*  
(KB958624)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=405b28db-47d7-4d6b-90e6-834c0a409323)\*\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=889c6eb1-7d1f-4e60-b637-535cb6e4e443)\*\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=8cab6fe8-161d-4d8c-9772-eb3174a2c3c3)  
(KB952069)  
(Fontos)  
[Windows Media Services 2008](http://www.microsoft.com/downloads/details.aspx?familyid=0204a366-5641-4036-9cb0-a46d04af9d72)\*  
(KB952068)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 x64 alapú rendszerekhez, Service Pack 2\*
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Media Services 2008](http://www.microsoft.com/downloads/details.aspx?familyid=0204a366-5641-4036-9cb0-a46d04af9d72)\*  
(KB952068)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 Itanium alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Windows Server 2008 Itanium alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=9bfe15cd-02ff-45cf-85c8-5ff1e6c1a871)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 Itanium alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=48bed90d-c243-4969-8e54-326d9a7af343)  
(KB958623)  
(Fontos)  
[Windows Server 2008 Itanium alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=83de2263-de2a-4c13-96ba-ecfebdaf0bb9)  
(KB958624)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f0d4f321-941e-4da7-958f-582c75542ee8)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=06cb502a-6818-4599-aa24-6eddb83e4b84)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
</table>
 
**Megjegyzés az MS08-078 közleményhez**

Az MS08-078 közleményben tárgyalt biztonsági rést a Windows Internet Explorer 8 Beta 2 kiadását követően jelentették. A Windows Internet Explorer 8 Beta 2 felhasználóknak ajánljuk a frissítés letöltését és alkalmazását.

A biztonsági frissítések a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) és a [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) weboldalról tölthetők le. A biztonsági frissítések a [Microsoft letöltőközpontjából](http://go.microsoft.com/fwlink/?linkid=21129) is elérhetőek. Legegyszerűbben a „security update” kifejezésre irányuló kulcsszavas kereséssel találhatja meg ezeket.

**Megjegyzések a Windows Server 2008 rendszerhez**

**\*Érinti a Windows Server 2008 kiszolgálómag-telepítését.** A frissítés besorolása ugyanaz a Windows Server 2008 támogatott kiadásain függetlenül attól, hogy a Windows Server 2008 alkalmazást a kiszolgálómag-telepítési opcióval telepítették-e. További tudnivalókat ezzel a telepítési beállítással kapcsolatban a következő weboldalon talál:[Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). A Server Core telepítési beállítás a Windows Server 2008 egyes kiadásainál nem alkalmazható. További tudnivalók: [Server Core telepítési beállítások összehasonlítása](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Nem érinti a Windows Server 2008 kiszolgálómag-telepítését.** A frissítésben tárgyalt biztonsági rések nem érintik a Windows Server 2008 támogatott kiadásait, amennyiben a Windows Server 2008 telepítése a kiszolgálómag-telepítési opció használatával történt. További tudnivalókat ezzel a telepítési beállítással kapcsolatban a következő weboldalon talál:[Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). A Server Core telepítési beállítás a Windows Server 2008 egyes kiadásainál nem alkalmazható. További tudnivalók: [Server Core telepítési beállítások összehasonlítása](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Nem érinti a Windows Server 2008 kiszolgálómag-telepítését.** Amennyiben a Windows Server 2008 telepítése a Server Core telepítési opció használatával történt, a frissítésekben tárgyalt biztonsági rések nem érintik a Windows Server 2008 támogatott kiadásait, bár a biztonsági rések által érintett fájlok jelen lehetnek a rendszeren. Az érintett fájlokkal rendelkező felhasználóknak mégis felajánlják a frissítést, mivel a frissített fájlok újabbak (magasabb verziószámúak), mint a jelenleg a rendszeren található fájlok. További tudnivalókat ezzel a telepítési beállítással kapcsolatban a következő weboldalon talál:[Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx). A Server Core telepítési beállítás a Windows Server 2008 egyes kiadásainál nem alkalmazható. További tudnivalók: [Server Core telepítési beállítások összehasonlítása](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="5">
Microsoft Office programcsomagok, rendszerek és összetevők
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://go.microsoft.com/fwlink/?linkid=130478)
</td>
<td style="border:1px solid black;">
[**MS08-072**](http://go.microsoft.com/fwlink/?linkid=126306)
</td>
<td style="border:1px solid black;">
[**MS08-074**](http://go.microsoft.com/fwlink/?linkid=131481)
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://go.microsoft.com/fwlink/?linkid=126307)
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
Nincsenek
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=43e8c4d8-307b-48f6-ac99-a9617421d40a)  
(KB956328)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2000 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f39d2a49-f861-4f2d-bf91-94a8a85af40c)  
(KB958435)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=3ef41412-50b3-4077-b0e3-9a3704d2f876)  
(KB956329)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=72076e21-2aa3-48e8-883a-c3cb756fc72a)  
(KB958372)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=45c81c60-4b1b-4246-839b-198ebc4eeae2)  
(KB956357)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6c0771e5-fcd4-4365-b903-1a3bd95d9e66)  
(KB958436)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
2007 Microsoft Office rendszer
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007](http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37)  
(KB956358)  
(Fontos)  
[Microsoft Office Outlook 2007](http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37)  
(KB956358)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007](http://www.microsoft.com/downloads/details.aspx?familyid=68bb8d99-f28b-4efd-9314-3eee0bb00ccf)  
(KB958437)\*\*\*\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Microsoft Office System Service Pack 1
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37)  
(KB956358)  
(Fontos)  
[Microsoft Office Outlook 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5b51cb5e-3899-4257-82cf-7e92fa619c37)  
(KB956358)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=68bb8d99-f28b-4efd-9314-3eee0bb00ccf)  
(KB958437)\*\*\*\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office FrontPage
</td>
<td style="border:1px solid black;">
[Microsoft Office FrontPage 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0a6130ae-c5b4-43cb-afe3-ab6a55b9d9ea)\*  
(KB957797)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
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
Microsoft Office Project
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=89a44042-a629-40f3-800a-0bb45fc36591)  
(KB949045)  
(Kritikus)  
[Microsoft Office Project 2007](http://www.microsoft.com/downloads/details.aspx?familyid=2fbf6a5b-ff35-4a2d-9fa0-4e62b6486fe6)  
(KB949046)  
(Kritikus)  
[Microsoft Office Project 2007 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=2fbf6a5b-ff35-4a2d-9fa0-4e62b6486fe6)  
(KB949046)  
(Kritikus)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="5">
Microsoft Office for Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://go.microsoft.com/fwlink/?linkid=130478)
</td>
<td style="border:1px solid black;">
[**MS08-072**](http://go.microsoft.com/fwlink/?linkid=126306)
</td>
<td style="border:1px solid black;">
[**MS08-074**](http://go.microsoft.com/fwlink/?linkid=131481)
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://go.microsoft.com/fwlink/?linkid=126307)
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
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nincsenek
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 for Mac
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=eca13ad8-62ae-41a8-b308-41e2d1773820)\*\*  
(KB960402)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=eca13ad8-62ae-41a8-b308-41e2d1773820)\*\*  
(KB960402)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 for Mac
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=ab31a564-43d2-45bd-98bf-19e9ca477b62)\*\*  
(KB960401)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=ab31a564-43d2-45bd-98bf-19e9ca477b62)\*\*  
(KB960401)  
(Fontos)
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
Nem érintett
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=edb6cd8f-832c-4123-8982-ac0c601ea0a7)\*\*  
(KB960403)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Open XML File Format Converter for Mac](http://www.microsoft.com/downloads/details.aspx?familyid=edb6cd8f-832c-4123-8982-ac0c601ea0a7)\*\*  
(KB960403)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="5">
További Office-szoftverek
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://go.microsoft.com/fwlink/?linkid=130478)
</td>
<td style="border:1px solid black;">
[**MS08-072**](http://go.microsoft.com/fwlink/?linkid=126306)
</td>
<td style="border:1px solid black;">
[**MS08-074**](http://go.microsoft.com/fwlink/?linkid=131481)
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://go.microsoft.com/fwlink/?linkid=126307)
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
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Works 8](http://www.microsoft.com/downloads/details.aspx?familyid=1537d181-90d9-4bb5-b5ae-8d9990a349af)\*\*\*  
(KB959487)  
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
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003](http://www.microsoft.com/downloads/details.aspx?familyid=4b3989ef-02b8-4bd2-b2ab-c3716079936e)  
(KB958434)  
(Fontos)  
[Microsoft Office Excel Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=4b3989ef-02b8-4bd2-b2ab-c3716079936e)  
(KB958434)  
(Fontos)  
[Microsoft Office Excel Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=9dbb35c1-aa7a-481b-a330-8ba916ddd443)  
(KB958442)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer 2003 Service Pack 3 és Microsoft Office Word Viewer](http://www.microsoft.com/downloads/details.aspx?familyid=70de7c3c-519f-4f4a-a03f-027f80b5415c)  
(KB956366)  
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
Microsoft Office kompatibilitási csomag a Word, Excel és PowerPoint 2007 fájlformátumokhoz
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office kompatibilitási csomag a Word, Excel és PowerPoint 2007 fájlformátumokhoz](http://www.microsoft.com/downloads/details.aspx?familyid=55430121-4476-48b8-9f6f-4a60fa0b2970)  
(KB956828)  
(Fontos)  
[Microsoft Office kompatibilitási csomag a Word, Excel és PowerPoint 2007 fájlformátumok Service Pack 1 csomagjához](http://www.microsoft.com/downloads/details.aspx?familyid=55430121-4476-48b8-9f6f-4a60fa0b2970)  
(KB956828)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office kompatibilitási csomag a Word, Excel és PowerPoint 2007 fájlformátumokhoz](http://www.microsoft.com/downloads/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f)  
(KB958439)  
(Fontos)  
[Microsoft Office kompatibilitási csomag a Word, Excel és PowerPoint 2007 fájlformátumok Service Pack 1 csomagjához](http://www.microsoft.com/downloads/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f)  
(KB958439)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e)  
(KB956716)  
(Fontos)  
[Microsoft Office SharePoint Server 2007 Service Pack 1, 32 bites kiadás](http://www.microsoft.com/downloads/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e)  
(KB956716)  
(Fontos)  
[Microsoft Office SharePoint Server 2007 (64 bites kiadás)](http://www.microsoft.com/downloads/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86)  
(KB956716)  
(Fontos)  
[Microsoft Office SharePoint Server 2007 Service Pack 1 (64 bites kiadás)](http://www.microsoft.com/downloads/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86)  
(KB956716)  
(Fontos)
</td>
</tr>
</table>
 
**Megjegyzés az MS08-070 közleményhez**
További frissített fájlokat a következő, a **Microsoft fejlesztői eszközök és szoftver** című részben talál. Ez a közlemény a Microsoft Office programra és a Microsoft fejlesztői eszközökre és szoftverre is vonatkozik.

**Megjegyzés az MS08-077 közleményhez**
További frissített fájlokat a **Microsoft Server Software** című részben talál. Ez a közlemény a Microsoft Office programcsomagokra és szoftverekre valamint a Microsoft Server Software programra is vonatkozik.

**Megjegyzés a Microsoft Office FrontPage programhoz az MS08-070 közleményben**
\*A frissítés kizárólag a FrontPage 2002 Service Pack 3 alkalmazás egyszerűsített kínai (Kína), pánkínai (Hong Kong), hagyományos kínai (Tajvan) és koreai változatát érinti.

**Megjegyzés a Microsoft Office for Mac programhoz az MS08-072 és MS08-074 közleményekben**
\*\*A vonatkozó frissítések azonosak az MS08-072 és MS08-074 közleményekben. Mivel a biztonsági rések ugyanabban a fájlokban találhatók, a frissítések megegyeznek mindkét közlemény esetében.

**Megjegyzés a Works 8 rendszerre vonatkozóan az MS08-072-ben**
\*\*\*A biztonsági frissítés beszerzéséhez a Microsoft Works 8.0 felhasználóknak először frissíteniük kell a Works 8.5 verzióra, ahogyan az a [Microsoft Works Update](http://www.microsoft.com/products/works/international/update_1001.mspx) című cikkben olvasható. Ebbe a körbe tartoznak a Microsoft Works 8.0, Works Suite 2004 és a Works Suite 2005 felhasználói is. A Works Suite 2006 felhasználóinak már Works 8.5 rendszere van.

**A Microsoft Office Excel 2007 és Microsoft Office Excel 2007 Service Pack 1 rendszerre vonatkozó megjegyzés az MS08-074 közleményben**
\*\*\*\*A Microsoft Office Excel 2007 és Microsoft Office Excel 2007 Service Pack 1 felhasználóknak a KB958437 frissítésen kívül a [Microsoft Office kompatibilitási csomag a Word, Excel és PowerPoint 2007 fájlformátumhoz](http://www.microsoft.com/downloads/details.aspx?familyid=99cca4ed-f1f9-4cfd-a986-edbec82ced4f) (KB958439) biztonsági frissítést is telepíteniük kell, hogy megvédjék rendszerüket az MS08-074 közleményben ismertetett biztonsági rések hibáitól. Azoknak a felhasználóknak, akik sikeresen telepítették a KB958437 és KB958439 frissítőcsomagot, nem kell újratelepíteniük azokat.

#### Microsoft fejlesztői eszközök és szoftver

 
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
Visual Studio
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-070**](http://go.microsoft.com/fwlink/?linkid=130478)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Összesített súlyossági besorolás**
</td>
<td style="border:1px solid black;">
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual Basic
</td>
<td style="border:1px solid black;">
[Microsoft Visual Basic 6.0 futtatórendszer kiterjesztett fájljai](http://www.microsoft.com/downloads/details.aspx?familyid=e27eebcb-095d-43ec-a19e-4a46e591715c)  
(KB926857)  
(Kritikus)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Studio .NET
</td>
<td style="border:1px solid black;">
[Microsoft Visual Studio .NET 2002 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=afad980d-7f27-49d9-aa23-b762c7b94cd6)  
(KB958392)  
(Kritikus)  
[Microsoft Visual Studio .NET 2003 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=6ac7cf8f-d046-43a8-b4ef-253153d65aed)  
(KB958393)  
(Kritikus)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Visual FoxPro
</td>
<td style="border:1px solid black;">
[Microsoft Visual FoxPro 8.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=a6977f81-f7f6-486b-96ad-8d296d79f205)  
(KB958369)  
(Kritikus)  
[Microsoft Visual FoxPro 9.0 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=386d27a6-b2c7-4acc-bf3e-edcbc7358172)  
(KB958370)  
(Kritikus)  
[Microsoft Visual FoxPro 9.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=5b1f28a9-da8d-463a-8ae4-dfc8fcc6c41a)  
(KB958371)  
(Kritikus)
</td>
</tr>
</table>
 
**Megjegyzés az MS08-070 közleményhez**
További frissített fájlokat az előző, a **Microsoft Office programcsomagok és szoftverek** című részben talál. Ez a közlemény a Microsoft Office programcsomagokra és szoftverekre valamint a Microsoft fejlesztői eszközökre és szoftverre is vonatkozik.

#### Microsoft Server Software

 
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
Search Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS08-077**](http://go.microsoft.com/fwlink/?linkid=126307)
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
Microsoft Search Server
</td>
<td style="border:1px solid black;">
[Microsoft Search Server 2008 (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=f8f73997-6f4c-4b43-aa50-5c8276e83d3e)\*  
(KB956716)  
(Fontos)  
[Microsoft Search Server 2008 (64 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=a7fda284-273c-42ab-8188-433beaacca86)\*\*  
(KB956716)  
(Fontos)
</td>
</tr>
</table>
 
**Megjegyzések az MS08-077 közleményhez**

\*Beleértve a Microsoft Search Server 2008 Express (32 bites) rendszert

\*\*Beleértve a Microsoft Search Server 2008 Express (64 bites) rendszert

További frissített fájlokat a **Microsoft Office programcsomagok és szoftverek** című részben talál. Ez a közlemény a Microsoft Office programcsomagokra és szoftverekre valamint a Microsoft Server Software programra is vonatkozik.

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

**Megjegyzés:** Az SMS a Microsoft Baseline Security Analyzer és a Microsoft Office Detection Tool program segítségével széles körű támogatást nyújt a frissítések biztonsági értesítők segítségével történő észleléséhez és telepítéséhez. Előfordulhat, hogy egyes szoftverfrissítéseket ezek az eszközök nem észlelnek. Az SMS alkalmazás leltározási szolgáltatásai segítségével a rendszergazdák adott rendszereken hajthatják végre a frissítést. Az eljárással kapcsolatban olvassa el a [szoftverfrissítések telepítése az SMS szoftverelosztó ügynök segítségével](http://go.microsoft.com/fwlink/?linkid=33341) című tájékoztatót. Egyes biztonsági frissítésekhez rendszergazdai jogosultságokra van szükség a számítógép újraindítása után. A rendszergazdák az [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) és az [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) csomag részét képező Elevated Rights Deployment Tool nevű eszközzel telepíthetik ezeket a frissítéseket.

**Az Update Compatibility Evaluator (a frissítéskompatibilitás kiértékelője) és az Application Compatibility Toolkit (alkalmazáskompatibilitási eszközkészlet)**

Az alkalmazások működése érdekében a frissítések gyakran írnak ugyanazokba a fájlokba, illetve regisztrációs bejegyzésekbe. Ez inkompatibilitást okozhat, és növelheti a biztonsági frissítések központi telepítésére használt időt. A Windows frissítések és az alkalmazásoknak való megfelelőségének tesztelése és ellenőrzése egyszerűsíthető az [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) eszközeivel, ami része az [Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=hu) csomagnak.

Az Application Compatibility Toolkit (ACT) tartalmazza a Microsoft Windows Vista, a Windows Update, a Microsoft Security Update vagy a Windows Internet Explorer új verziójának központi telepítése előtt az alkalmazáskompatibilitási problémák kiértékeléséhez és enyhítéséhez szükséges eszközöket és dokumentációt.

### Egyéb információ

#### A Microsoft Windows rosszindulatú szoftvereket eltávolító eszköze

A Microsoft a Windows Update, Microsoft Update, Windows Server Update Services és Letöltőközpont szolgáltatásán keresztül elérhetővé tette a Microsoft Windows rosszindulatú szoftvereket eltávolító eszközének frissített változatát.

#### Nem biztonsági jellegű, kiemelt fontosságú frissítések a MU, WU és WSUS-szolgáltatásokban

A Windows Update és a Microsoft Update helyen elérhető, nem biztonsági jellegű frissítésekről tájékozódjon itt:

-   [Microsoft Tudásbázis 894199. cikke](http://support.microsoft.com/kb/894199): A Software Update Services és a Windows Server Update Services 2008-as tartalmi módosításainak ismertetése. Minden, Windows rendszerre vonatkozó tartalom.
-   [Microsoft-termékek új, módosított és közreadott frissítései, a Microsoft Windows rendszert kivéve](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

#### Microsoft Active Protections Program (MAPP)

Az ügyfelek védelmének növelése érdekében a biztonsági szoftverekkel foglalkozó nagyobb gyártók a Microsoft a havi biztonsági közlemények megjelenése előtt ellátja biztonsági résekkel kapcsolatos információkkal. Így a biztonságiszoftver-gyártók a kapott biztonsági résekkel kapcsolatos információt felhasználhatják ügyfeleik hatásosabb védelmére az olyan biztonsági szoftverek vagy eszközök (például víruskeresők, hálózati behatolásérzékelő rendszerek vagy kiszolgálóalapú behatolásvédelmi rendszerek) frissítése által. A biztonságiszoftver-gyártók által kiadott aktív védelem elérhetőségéről a [Microsoft Active Protections Program (MAPP) Partners](http://www.microsoft.com/security/msrc/mapp/partners.mspx) webhelyén található listán szereplő és a programban részt vevő gyártók aktív védelmi webhelyein tájékozódhat.

#### Biztonsági stratégiák és közösségek

**Frissítésekkel kapcsolatos stratégiák**

[A frissítések kezelésére vonatkozó útmutatás](http://go.microsoft.com/fwlink/?linkid=21168) a Microsoft által a biztonsági frissítések telepítéséhez ajánlott legjobban bevált eljárást ismerteti.

**Egyéb biztonsági frissítések beszerzése**

Az alábbi helyekről más típusú biztonsági problémákhoz szerezhetők be frissítések.

-   A biztonsági frissítések a [Microsoft letöltőközpontban](http://go.microsoft.com/fwlink/?linkid=21129) érhetők el. Legegyszerűbben a „security update” kifejezésre irányuló kulcsszavas kereséssel találhatja meg ezeket.
-   Az ügyfélrendszerek frissítései a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) oldalról elérhetőek.
-   A Windows Update szolgáltatáson keresztül terjesztett havi aktuális biztonsági frissítések a letöltőközpontból a biztonsági és kritikus frissítéseket tartalmazó ISO CD-képfájlként is letölthetőek. További információt a [Microsoft Tudásbázis 913086](http://support.microsoft.com/kb/913086) számú cikkében talál.

**IT Pro Security közösség**

Az [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) közösségben hasznos információt találhat a biztonság javításáról és az informatikai infrastruktúrák optimalizálásáról, továbbá eszmecserét folytathat a biztonsági kérdésekről más informatikai szakemberekkel.

#### Köszönetnyilvánítás

A Microsoft [köszönetét](http://go.microsoft.com/fwlink/?linkid=21127) fejezi ki a vásárlók védelmének biztosításában nyújtott segítségért az alábbi szervezet(ek)nek és szakember(ek)nek:

-   ADLab, [VenusTech](http://www.venustech.com.cn/), az MS08-070 közleményben leírt probléma jelentéséért
-   Jason Medeiros, [Affiliated Computer Services](http://www.acs-inc.com/), az MS08-070 közleményben leírt probléma jelentéséért
-   Carsten Eiram, [Secunia Research](http://secunia.com/), az MS08-070 közleményben leírt probléma jelentéséért
-   Mark Dowd, a [McAfee Avert Labs](http://www.avertlabs.com/) együttműködő partnere, az MS08-070 közleményben leírt probléma jelentéséért
-   Brett Moore, [Insomnia Security](http://www.insomniasec.com/), az MS08-070 közleményben leírt probléma jelentéséért.
-   CHkr\_D591, a [TippingPoint](http://www.tippingpoint.com/) és a [Zero Day Initiative](http://www.zerodayinitiative.com/) együttműködő partnere, az MS08-070 közleményben leírt probléma jelentéséért
-   Michal Bucko, a [CERT/CC](http://www.cert.org/) együttműködő partnere, az MS08-070 közleményben leírt probléma jelentéséért
-   Symantec, [Security Intelligence Analysis Team](http://www.symantec.com/), az MS08-070 közleményben leírt probléma megoldásában történő együttműködésért
-   Jun Mao, [Verisign iDefense Labs](http://labs.idefense.com/), az MS08-071 közleményben leírt probléma jelentéséért
-   Juan Caballero, a [Carnegie Mellon University és az UC Berkeley Bitblaze csoportjának](http://bitblaze.cs.berkeley.edu/) együttműködő partnere, az MS08-071 közleményben leírt probléma jelentéséért
-   Ricardo Narvaja, [Core Security Technologies](http://www.coresecurity.com/), az MS08-072 közleményben leírt probléma jelentéséért
-   Carsten Eiram, [Secunia Research](http://secunia.com/), az MS08-072 közleményben leírt probléma jelentéséért
-   Yamata Li, [Palo Alto Networks](http://www.paloaltonetworks.com/), az MS08-072 közleményben bemutatott probléma jelentéséért
-   Wushi, valamint az együttműködő [TippingPoint](http://www.tippingpoint.com/) és [Zero Day Initiative](http://www.zerodayinitiative.com/), az MS08-072 közleményben ismertetett probléma jelentéséért
-   Aaron Portnoy, [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/), az MS08-072 közleményben leírt probléma jelentéséért
-   Wushi, [team509](http://www.team509.com/), a [Zero Day Initiative](http://www.zerodayinitiative.com/) céggel együttműködve az MS08-072 közleményben bemutatott probléma jelentéséért.
-   Wushi és Ling, a [TippingPoint](http://www.tippingpoint.com/) és a [Zero Day Initiative](http://www.zerodayinitiative.com/) együttműködő partnerei, az MS08-072 közleményben ismertetett probléma jelentéséért
-   Carlo Di Dato (shinnai) az MS08-073 közleményben ismertetett probléma jelentéséért
-   Brett Moore, a [TippingPoint](http://www.tippingpoint.com/) és a [Zero Day Initiativ](http://www.zerodayinitiative.com/), együttműködő partnere, az MS08-073 közleményben ismertetett probléma jelentéséért
-   Chris Weber, [Casaba Security](http://www.casabasecurity.com/), az MS08-073 közleményben ismertetett probléma jelentéséért
-   Jun Mao, [Verisign iDefense Labs](http://labs.idefense.com/), az MS08-073 közleményben leírt probléma jelentéséért
-   Joshua J. Drake, [Verisign iDefense Labs](http://labs.idefense.com/), az MS08-074 közleményben ismertetett probléma jelentéséért
-   Claes M Nyberg, [signedness.org](http://www.signedness.org/), az MS08-074 közleményben ismertetett probléma jelentéséért
-   Dyon Balding, [Secunia](http://secunia.com/), az MS08-074 közleményben leírt probléma jelentéséért.
-   Andre Protas, [eEye Digital Security](http://www.eeye.com/), az MS08-075 közleményben ismertetett probléma jelentéséért
-   Nate McFeters, az MS08-075 közleményben bemutatott probléma jelentéséért
-   Névtelen megtaláló, az MS08-077 közleményben leírt probléma jelentéséért

#### Terméktámogatás

-   Teszteléssel állapították meg a felsorolt szoftverek egyes verzióinak érintettségét. A többi verzió támogatási életciklusa végére ért. Az egyes szoftververziók támogatási életciklusáról a [Microsoft termékek terméktámogatási életciklusát ismertető webhelyen](http://go.microsoft.com/fwlink/?linkid=21742) talál felvilágosítást.
-   Az Amerikai Egyesült Államokban és Kanadában technikai segítség igényelhető a [Microsoft terméktámogatási szolgáltatásától](http://go.microsoft.com/fwlink/?linkid=21131), amelynek telefonszáma 1-866-PCSAFETY. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek.
-   Más országokban a helyi Microsoft-képviseletek nyújtanak támogatást. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. A [nemzetközi támogatási webhely](http://go.microsoft.com/fwlink/?linkid=21155) felvilágosítást nyújt arról, támogatási kérdéseivel hogyan fordulhat a Microsofthoz.

#### Felelősséget kizáró nyilatkozat

A Microsoft Tudásbázisban leírtak előzetes bejelentés nélkül változhatnak, és a cikkek tartalmáért a Microsoft nem vállal garanciát. A Microsoft egyben elhárít minden kifejezett és értelemszerű garanciát, beleértve az eladhatóságra és az adott célra való alkalmasságra vonatkozó garanciát is. A Microsoft Corporation vagy annak szállítói semmilyen körülmények között nem tehetők felelőssé közvetlen, közvetett, eseti, ok-okozati vagy különleges kárért (beleértve az elmaradt hasznot is), még akkor sem, ha a Microsoft Corporation vagy szállítói tudatában voltak a kár lehetséges voltának. Egyes államok törvényi szabályozása nem teszi lehetővé a véletlen vagy ok-okozati károkért vállalt felelősség korlátozását vagy kizárását, így ezekben az államokban az ez a felelősségkizárás nincs érvényben.

#### Verziók

-   1.0 verzió (2008. december 9.) Összefoglaló közlemény közzététele.
-   2.0 verzió (2008. december 10.): Az MS08-076 közlemény érintett szoftverek táblázata most már helyesen, külön frissítésként tünteti fel a Windows Media Format Runtime 9.5 és Windows Media Format Runtime 11 verziót Windows XP Professional x64 Edition és Windows XP Professional x64 Edition Service Pack 2 rendszeren. Ugyanakkor az MS08-076 közleményben megszűnt a téves utalás a Windows XP Professional x64 Edition, Windows XP Professional x64 Edition Service Pack 2, Windows Server 2003 x64 Edition és Windows Server 2003 x64 Edition Service Pack 2 rendszeren futó Windows Media Format Runtime 11 x64 Edition alkalmazásra.
-   3.0 verzió (2008. december 17.): Kiadásra került a Microsoft MS08-078 számú, Internet Explorer alkalmazást érintő biztonsági frissítést tartalmazó biztonsági közleménye (960714). A soron kívüli biztonsági frissítés webes szemináriumokra vonatkozó hivatkozásokkal is kiegészült.
-   3.1 (2008. december 18.): A MS08-078 közleményben megjelent a nem érintett kiszolgálómagra utaló megjegyzés a Windows Internet Explorer 7 alkalmazásra nézve Windows Server 2008 32 bites rendszerekhez és Windows Server 2008 x64-alapú rendszerekhez esetén.
-   3.2 verzió (2009. január 7.): A Microsoft Office Word Viewer 2003 alkalmazás kikerült az MS08-072 közleményben foglalt probléma által érintett szoftverek táblázatából.
-   4.0 verzió (2009. január 13.): A Microsoft azért adta ki újra az MS08-076 közleményt, mert az új frissítéseket tartalmaz a Windows Media Format Runtime 9.5 programhoz a Windows XP Service Pack 2 (KB952069) és a Windows XP Service Pack 3 (KB952069) rendszeren. A Windows Media-összetevők összes többi támogatott és érintett verziójának azon felhasználóinak, akik már telepítették az eredeti MS08-076 biztonsági frissítéseket, nincs további teendőjük. A frissített MS08-076 közleményben a Windows Media Player 6.4 és Windows Media Services 4.1 is érintettként szerepel a Microsoft Windows 2000 Service Pack 4 minden verzióján; így azok a felhasználók, akik nem telepítették a felajánlott, Windows Media Player 6.4 esetén KB954600 számú, Windows Media Services 4.1 esetén pedig KB952068 számú frissítést, most tegyék meg. Végül pedig a Microsoft Office Word Viewer programot is felsorolja az MS08-072 által érintett programok között. Azoknak a felhasználóknak, akik sikeresen telepítették a KB956366 biztonsági frissítést, nem kell végrehajtaniuk az újratelepítést.
-   5.0 verzió (2009. január 28.): Az MS08-074 közlemény **Érintett szoftverek** táblázata lábjegyzettel egészült ki a Microsoft Office Excel 2007 alkalmazás támogatott verzióira vonatkozó KB958437 és KB958439 biztonsági frissítőcsomagról. A biztonsági frissítéshez kapcsolódó bináris fájlok és az észlelés nem változott. Azoknak a Microsoft Office Excel 2007 illetve Microsoft Office Excel 2007 Service Pack 1 felhasználóknak, akik sikeresen telepítették a KB958437 és KB958439 frissítést, nem kell újratelepíteniük azokat.
-   6.0 verzió (2009. április 29.): A frissített közleményben a Windows Media Services 2008 (KB952068) 32 bites és x64 alapú Windows Server 2008 Service Pack 2 rendszereken az MS08-076 frissítls vonatkozásában az érintett szoftverek között szerepel. Ez csak észlelési módosítás; a bináris értékek nem változtak. Azoknak a felhasználóknak, akik sikeresen telepítették a KB952068 frissítést, nem kell újratelepítést végezniük.

*Built at 2014-04-18T01:50:00Z-07:00*
