---
TOCTitle: 'MS10-DEC'
Title: Microsoft Security Bulletin Summary for december 2010
ms:assetid: 'ms10-dec'
ms:contentKeyID: 61227740
ms:mtpsurl: 'https://technet.microsoft.com/hu-HU/library/ms10-dec(v=Security.10)'
author: SharonSears
ms.author: SharonSears
---

Security Bulletin Summary

Microsoft Security Bulletin Summary for december 2010
=====================================================

Közzétéve: 2010. december 14. | Frissítve: 2010. december 15.

**Verzió:** 1.1

Az összefoglaló a 2010 decemberében kiadott biztonsági közleményeket összegzi.

A 2010. decemberi biztonsági közlemények kiadása folytán az összefoglaló a 2010. december 9-én kiadott előzetes értesítés helyébe lép. További információk a biztonsági közlemények kiadásáról szóló előzetes értesítés szolgáltatásról lásd: [Előzetes értesítés a Microsoft biztonsági közleményeinek kiadásáról](http://technet.microsoft.com/security/bulletin/advance).

Ha automatikus értesítést szeretne kapni a Microsoft biztonsági közleményeinek megjelenéséről, fizessen elő a [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163) szolgáltatásra.

A közleményekkel kapcsolatos kérdések megválaszolására a Microsoft 2010. december 15-én, csendes-óceáni idő szerint 11 órakor webes szemináriumot tart. [Jelentkezzen most a decemberi közleményeket bemutató webes szemináriumra](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454444&eventcategory=4&culture=en-us&countrycode=us). Ezt követően a webes szeminárium igény szerint kerül megrendezésre. További információkért látogasson el a [Microsoft biztonsági közleményeit és a webes szemináriumokat](http://technet.microsoft.com/security/bulletin/summary)bemutató oldalra.

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td style="border:1px solid black;"><strong>Összesítő biztonsági frissítés az Internet Explorer programhoz (2416400)</strong><br />
<br />
A biztonsági frissítés négy közvetlenül és három nyilvánosan jelentett biztonsági rést szüntet meg az Internet Explorer programban. A súlyosabb biztonsági rések távoli kódfuttatást tesznek lehetővé, amennyiben a felhasználó speciálisan kialakított weboldalt tekint meg az Internet Explorer alkalmazással. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=203895">MS10-091</a></td>
<td style="border:1px solid black;"><strong>Az OpenType betűtípus (OTF) illesztőprogram biztonsági rései távolról történő kódfuttatást tesznek lehetővé (2296199)</strong><br />
<br />
A biztonsági frissítés a Windows Open Type betűtípus (OTF) illesztőprogram néhány, közvetlenül jelentett, és távoli kódfuttatást lehetővé tevő biztonsági rését szünteti meg. A támadó speciálisan kialakított OpenType betűtípust üzemeltethet egy hálózati megosztáson. Az érintett vezérlési útvonal ezt követően akkor aktiválódik, amikor a felhasználó erre a megosztásra navigál a Windows Intézőben, lehetővé téve a speciálisan kialakított betűtípus számára, hogy átvegye az irányítást az érintett rendszer felett. Ezt követően a támadó programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritikus</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=203463">MS10-092</a></td>
<td style="border:1px solid black;"><strong>A Feladatütemező biztonsági rése jogosultság illetéktelen megszerzéséhez vezethet (2305420)</strong><br />
<br />
A biztonsági frissítés a Windows Feladatütemező nyilvánosan jelentett biztonsági rését szünteti meg. A biztonsági rés a jogok kiterjesztését teheti lehetővé, ha a támadó bejelentkezett az érintett rendszerre, és ott különlegesen kialakított alkalmazást futtatott. A támadónak a biztonsági rés kihasználásához érvényes bejelentkezési adatokkal kell rendelkeznie, és képesnek kell lennie helyileg bejelentkezni a rendszerbe. Névtelen felhasználók nem tudják távolról kiaknázni ezt a biztonsági rést.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Jogok kiterjesztése</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206698">MS10-093</a></td>
<td style="border:1px solid black;"><strong>A Windows Movie Maker biztonsági rése, amely távoli programkódfuttatást tehet lehetővé (2424434)</strong><br />
<br />
A biztonsági frissítés a Windows Movie Maker nyilvánosan jelentett biztonsági rését szünteti meg. A támadó a biztonsági résen keresztül távoli kódfuttatást tud elérni, ha rá tudja venni a felhasználót, hogy nyisson meg egy normál Windows Movie Maker fájlt, amely azonban azonos hálózati meghajtón található, mint a speciálisan létrehozott függvénytárfájl. A sikeres támadáshoz a felhasználónak egy nem megbízhatónak ítélt távoli fájlrendszerre vagy WebDAV megosztásra kell ellátogatnia, majd onnan dokumentumot megnyitnia, amelyet ezt követően a biztonsági rés által érintett alkalmazás betölt.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206699">MS10-094</a></td>
<td style="border:1px solid black;"><strong>A Windows Media kódoló biztonsági rése, amely távoli programkódfuttatást tesz lehetővé (2447961)</strong><br />
<br />
A biztonsági frissítés a Windows Media kódoló nyilvánosan jelentett biztonsági rését szünteti meg. A támadó a biztonsági résen keresztül távoli kódfuttatást tud elérni, ha rá tudja venni a felhasználót, hogy nyisson meg egy normál Windows Media profil (.prx) fájlt, amely azonban azonos hálózati meghajtón található, mint a speciálisan létrehozott függvénytárfájl. A sikeres támadáshoz a felhasználónak egy nem megbízhatónak ítélt távoli fájlrendszerre vagy WebDAV megosztásra kell ellátogatnia, majd onnan dokumentumot megnyitnia, amelyet ezt követően a biztonsági rés által érintett alkalmazás betölt.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206683">MS10-095</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Windows biztonsági rése távolról történő programkódfuttatást tehet lehetővé (2385678)</strong><br />
<br />
A biztonsági frissítés a Microsoft Windows közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rés távolról történő programkódfuttatást tehet lehetővé, ha a felhasználó olyan .eml és .rss (Windows Live Mail) vagy .wpost (Microsoft Live Writer) fájlt nyit meg, amely egy speciálisan kialakított függvénytárfájllal egy hálózati mappában található. A sikeres támadáshoz a felhasználónak egy nem megbízhatónak ítélt távoli fájlrendszerre vagy WebDAV megosztásra kell ellátogatnia, majd onnan dokumentumot megnyitnia, amelyet ezt követően a biztonsági rés által érintett alkalmazás betölt.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206738">MS10-096</a></td>
<td style="border:1px solid black;"><strong>A Windows címjegyzék biztonsági rése, amely távoli programkódfuttatást tehet lehetővé (2423089)</strong><br />
<br />
A biztonsági frissítés a Windows címjegyzék nyilvánosan jelentett biztonsági rését szünteti meg. A biztonsági rés távolról történő programkódfuttatást tehet lehetővé, ha a felhasználó olyan Windows címjegyzékfájlt nyit meg, amely egy speciálisan kialakított függvénytárfájllal egy hálózati mappában található. A sikeres támadáshoz a felhasználónak egy nem megbízhatónak ítélt távoli fájlrendszerre vagy WebDAV megosztásra kell ellátogatnia, majd onnan dokumentumot megnyitnia, amelyet ezt követően a biztonsági rés által érintett alkalmazás betölt.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206689">MS10-097</a></td>
<td style="border:1px solid black;"><strong>A függvénytárak nem biztonságos betöltése az Internetkapcsolat-előfizetési varázslóba távolról történő kódfuttatást tesz lehetővé (2443105)</strong><br />
<br />
A biztonsági frissítés a Microsoft Windows Internetkapcsolat-előfizetési varázslója nyilvánosan jelentett biztonsági rését szünteti meg. A biztonsági frissítés a Windows XP és Windows Server 2003 összes támogatott kiadására nézve Fontos besorolású. A Windows Vista, Windows Server 2008, Windows 7 és Windows Server 2008 R2 támogatott kiadásait nem érinti a biztonsági rés okozta probléma.<br />
<br />
A biztonsági rés távoli kódfuttatást tehet lehetővé, ha egy felhasználó megnyit egy speciálisan kialakított függvénytárfájllal azonos hálózati mappában található .ins vagy .isp fájlt. A sikeres támadáshoz a felhasználónak egy nem megbízhatónak ítélt távoli fájlrendszerre vagy WebDAV megosztásra kell ellátogatnia, majd onnan dokumentumot megnyitnia, amelyet ezt követően a biztonsági rés által érintett alkalmazás betölt.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td style="border:1px solid black;"><strong>A Windows kernel módú illesztőprogramok biztonsági rése jogok kiterjesztéséhez vezethet (2436673)</strong><br />
<br />
Ez a biztonsági frissítés egy nyilvánosságra került biztonsági rést és több közvetlenül jelentett biztonsági rést szüntet meg a Microsoft Windows rendszerben. A biztonsági rések jogok kiterjesztését tehetik lehetővé, ha a támadó helyben bejelentkezett, és ott különlegesen kialakított alkalmazást futtatott. A támadónak a biztonsági rések kihasználásához érvényes bejelentkezési adatokkal kell rendelkeznie, és képesnek kell lennie helyileg bejelentkezni a rendszerbe. Névtelen felhasználók nem tudják távolról kiaknázni ezeket a biztonsági réseket.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Jogok kiterjesztése</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206365">MS10-099</a></td>
<td style="border:1px solid black;"><strong>Az útválasztás és a távoli hozzáférés-vezérlés biztonsági rése jogok kiterjesztését teheti lehetővé (2440591)</strong><br />
<br />
Ez a biztonsági frissítés egy közvetlenül jelzett biztonsági rés megszüntetésére szolgál, amely a Microsoft Windows rendszer Útválasztás és távelérés NDProxy összetevőjében található. A biztonsági frissítés a Windows XP és Windows Server 2003 összes támogatott kiadására nézve Fontos besorolású. A Windows Vista, Windows Server 2008, Windows 7 és Windows Server 2008 R2 támogatott kiadásait nem érinti a biztonsági rés okozta probléma.<br />
<br />
A biztonsági rés a jogok kiterjesztését teheti lehetővé, ha a támadó bejelentkezik az érintett rendszerre, és ott különlegesen kialakított alkalmazást futtat. A támadónak a biztonsági rés kihasználásához érvényes bejelentkezési adatokkal kell rendelkeznie, és képesnek kell lennie helyileg bejelentkezni a rendszerbe. Névtelen felhasználók nem tudják távolról kiaknázni ezt a biztonsági rést.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Jogok kiterjesztése</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204906">MS10-100</a></td>
<td style="border:1px solid black;"><strong>A Consent felhasználói felület biztonsági rése jogok kiterjesztését teheti lehetővé (2442962)</strong><br />
<br />
A biztonsági frissítés a Consent felhasználói felület (UI) közvetlenül jelzett biztonsági rését szünteti meg. A biztonsági rés lehetővé teheti a jogosultság illetéktelen megszerzését, ha a támadó speciálisan kialakított alkalmazást futtat az érintett rendszeren. A támadónak a biztonsági rés kihasználásához érvényes bejelentkezési adatokkal és SeImpersonatePrivilege jogosultsággal kell rendelkeznie, és képesnek kell lennie helyileg bejelentkezni a rendszerbe. Névtelen felhasználók nem tudják távolról kiaknázni ezt a biztonsági rést.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Jogok kiterjesztése</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=201319">MS10-101</a></td>
<td style="border:1px solid black;"><strong>A Windows Netlogon szolgáltatás biztonsági rése szolgáltatásmegtagadást okozhat (2207559)</strong><br />
<br />
Ez a biztonsági frissítés egy közvetlenül jelzett biztonsági rést szüntet meg a Netlogon távoli eljáráshívási szolgáltatásban a Windows Server rendszer érintett verzióiban, amennyiben azok tartományvezérlői szerepkörre vannak konfigurálva. A biztonsági rés szolgáltatásmegtagadást okozhat, ha a támadó egy speciálisan kialakított RPC-csomagot küld az érintett rendszer Netlogon RPC szolgáltatási felületére. A biztonsági rés kihasználásához a támadónak az érintett tartományvezérlővel azonos tartományhoz csatlakoztatott számítógépen rendszergazdai jogosultsággal kell rendelkeznie.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Szolgáltatásmegtagadás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=205309">MS10-102</a></td>
<td style="border:1px solid black;"><strong>Szolgáltatásmegtagadást lehetővé tévő Hyper-V biztonsági rés (2345316)</strong><br />
<br />
A biztonsági frissítés a közvetlenül jelentett biztonsági rés hibáit oldja meg a Windows Server 2008 Hyper-V és a Windows Server 2008 R2 Hyper-V használatával működő kiszolgálókon. A biztonsági rés szolgáltatásmegtagadást tehet lehetővé, ha a Hyper-V kiszolgálón vendégként futó virtuális gépek valamelyikén hitelesített felhasználó speciálisan kialakított csomagot küld a VMBus-ra. A biztonsági rés kihasználásához a támadónak rendelkeznie kell érvényes bejelentkezési adatokkal és képesnek kell lennie speciálisan kialakított tartalom küldésére valamely vendég virtuális gépről. Névtelen felhasználók nem tudják távolról kiaknázni ezt a biztonsági rést.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Szolgáltatásmegtagadás</td>
<td style="border:1px solid black;">Újraindítást igényel</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Publisher biztonsági rései távoli kódfuttatást tehetnek lehetővé (2292970)</strong><br />
<br />
A biztonsági frissítés a Microsoft Publisher öt, közvetlenül a Microsoftnak jelzett biztonsági rését szünteti meg, amelyek távoli kódfuttatást tesznek lehetővé, amennyiben a felhasználó speciálisan kialakított Publisher fájlt nyit meg. A biztonsági rések bármelyikét kiaknázó támadó teljes mértékben átveheti az érintett rendszer vezérlését. Ezt követően a támadó programokat telepíthet, illetve adatokat tekinthet meg, módosíthat és törölhet, de korlátozás nélküli jogosultságokkal rendelkező új fiókokat is létrehozhat. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=206469">MS10-104</a></td>
<td style="border:1px solid black;"><strong>A Microsoft SharePoint biztonsági rése távoli kódfuttatást tehet lehetővé (2455005)</strong><br />
<br />
A biztonsági frissítés a Microsoft SharePoint közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rés távoli kódfuttatást okozhat a vendégfelhasználó biztonsági környezetében, ha a támadó speciálisan kialakított SOAP-kérelmet küld a dokumentumkonvertálás terheléselosztó szolgáltatását használó SharePoint kiszolgáló dokumentumkonvertálás indítószolgáltatásának. A dokumentumkonvertálás terheléselosztó szolgáltatása és a dokumentumkonvertálás indítószolgáltatása alapértelmezésben nincs engedélyezve a Microsoft Office SharePoint Server 2007 rendszeren.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft SharePoint</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Office grafikus szűrők biztonsági rése távolról történő programkódfuttatást tehet lehetővé (968095)</strong><br />
<br />
Ez a biztonsági frissítés a Microsoft Office hét, közvetlenül jelzett biztonsági rését szünteti meg. A biztonsági rések távoli kódvégrehajtást tehetnek lehetővé, amennyiben a felhasználó egy különlegesen kialakított képfájlt tekintett meg a Microsoft Office alkalmazás segítségével. A biztonsági rések valamelyikét sikeresen kihasználó támadó a helyi felhasználóval egyező hozzáférést nyer a rendszerhez. A kevesebb jogosultsággal bíró fiókkal rendelkező felhasználók esetében kisebb a veszélyeztetettség, mint a rendszergazdai jogosultságokkal rendelkezők esetén</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Fontos</a><br />
Távoli kódfuttatás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204624">MS10-106</a></td>
<td style="border:1px solid black;"><strong>A Microsoft Exchange Server biztonsági rése szolgáltatásmegtagadást okozhat (2407132)</strong><br />
<br />
A biztonsági frissítés a Microsoft Exchange Server közvetlenül jelentett biztonsági rését szünteti meg. A biztonsági rése szolgáltatásmegtagadást tesz lehetővé, ha a támadó speciálisan kialakított hálózati üzenetet küld az Exchange szolgáltatást futtató számítógépre. A tűzfalakra vonatkozó gyakorlati tanácsok, valamint a szabványos alapértelmezett tűzfal-konfigurációk segítséget nyújtanak a hálózatot érő, a szervezet határain kívülről eredő támadások kivédésében. Gyakorlati tanácsként azt javasoljuk, hogy az internetkapcsolattal rendelkező számítógépeken a lehető legkevesebb port legyen megnyitva.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Mérsékelt</a><br />
Szolgáltatásmegtagadás</td>
<td style="border:1px solid black;">Esetleg újra kell indítani a rendszert</td>
<td style="border:1px solid black;">Microsoft Exchange</td>
</tr>
</tbody>
</table>
  
Kihasználhatósági információk  
-----------------------------
  
<span></span>
A következő táblázat az adott hónapban megoldott biztonsági rések kihasználhatósági jellemzőit ismerteti. A biztonsági rések a kihasználhatósági kockázat, majd a CVE azonosító szerint vannak felsorolva. Csak a kritikus és fontos besorolású biztonsági rések szerepelnek.
  
**A táblázat használata**
  
A táblázat segítségével meghatározható annak valószínűsége, hogy a biztonsági közlemény kiadását követő 30 napon belül a telepíteni szükséges biztonsági frissítésekre működő rosszindulatú programkódot jelentetnek meg. A telepítés fontossági sorrendjének megállapításához az adott konfigurációnak megfelelően tekintse át az alábbi értékeléseket. A minősítések jelentéséről és meghatározásuk módjáról a [Microsoft biztonsági rések jegyzéke](http://technet.microsoft.com/en-us/security/cc998259.aspx) tartalmaz bővebb információt.
  
| Közlemény azonosítója                                     | A biztonsági rés címe                                                                                     | CVE-azonosító                                                                    | Kihasználhatósági információk értékelése                                                                                 | Fontos megjegyzések                                        |  
|-----------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------|  
| [MS10-103](http://go.microsoft.com/fwlink/?linkid=198156) | Csomagméret halommemória-sérülési biztonsági rése a pubconv.dll elemben                                   | [CVE-2010-2569](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2569) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-103](http://go.microsoft.com/fwlink/?linkid=198156) | Halom túlcsordulását okozó biztonsági rés a pubconv.dll elemben                                           | [CVE-2010-2570](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2570) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-097](http://go.microsoft.com/fwlink/?linkid=206689) | Az Internetcsatlakozás varázsló nem biztonságos függvénytárbetöltésének biztonsági rése                   | [CVE-2010-3144](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3144) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | **A biztonsági rés nyilvánosságra került**                 |  
| [MS10-096](http://go.microsoft.com/fwlink/?linkid=206738) | A függvénytárak nem biztonságos betöltése miatti biztonsági rés                                           | [CVE-2010-3147](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3147) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | **A biztonsági rés nyilvánosságra került**                 |  
| [MS10-092](http://go.microsoft.com/fwlink/?linkid=203463) | Feladatütemező biztonsági rése                                                                            | [CVE-2010-3338](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3338) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | **A biztonsági rést internetszerte kihasználják**          |  
| [MS10-090](http://go.microsoft.com/fwlink/?linkid=206495) | HTML-objektumok okozta memóriameghibásodás biztonsági rése                                                | [CVE-2010-3340](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3340) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-090](http://go.microsoft.com/fwlink/?linkid=206495) | HTML-objektumok okozta memóriameghibásodás biztonsági rése                                                | [CVE-2010-3343](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3343) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-090](http://go.microsoft.com/fwlink/?linkid=206495) | HTML-elemek miatti memóriameghibásodás okozta biztonsági rés                                              | [CVE-2010-3345](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3345) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-090](http://go.microsoft.com/fwlink/?linkid=206495) | HTML-elemek miatti memóriameghibásodás okozta biztonsági rés                                              | [CVE-2010-3346](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3346) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-098](http://go.microsoft.com/fwlink/?linkid=204869) | Win32k puffertúlcsordulás okozta biztonsági rés                                                           | [CVE-2010-3939](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3939) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | **A biztonsági rés nyilvánosságra került**                 |  
| [MS10-098](http://go.microsoft.com/fwlink/?linkid=204869) | Win32k PFE-mutató kétszeres felszabadítási biztonsági rése                                                | [CVE-2010-3940](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3940) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-098](http://go.microsoft.com/fwlink/?linkid=204869) | Win32k kurzorcsatolási biztonsági rés                                                                     | [CVE-2010-3943](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3943) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-098](http://go.microsoft.com/fwlink/?linkid=204869) | A Win32k memóriameghibásodást okozó biztonsági rése                                                       | [CVE-2010-3944](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3944) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-105](http://go.microsoft.com/fwlink/?linkid=147425) | FlashPix-képkonvertáló puffertúlcsordulási biztonsági rése                                                | [CVE-2010-3951](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3951) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-091](http://go.microsoft.com/fwlink/?linkid=203895) | OpenType betűtípus kétszeres felszabadítási biztonsági rése                                               | [CVE-2010-3957](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3957) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-091](http://go.microsoft.com/fwlink/?linkid=203895) | OpenType CMAP-leírótábla biztonsági rése                                                                  | [CVE-2010-3959](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3959) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-100](http://go.microsoft.com/fwlink/?linkid=204906) | Consent UI megszemélyesítés biztonsági rése                                                               | [CVE-2010-3961](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3961) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-090](http://go.microsoft.com/fwlink/?linkid=206495) | Inicializálás hiánya miatti memóriameghibásodás okozta biztonsági rés                                     | [CVE-2010-3962](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3962) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | **A biztonsági rést jelenleg internetszerte kihasználják** |  
| [MS10-099](http://go.microsoft.com/fwlink/?linkid=206365) | Kernel NDProxy puffertúlcsordulás okozta biztonsági rés                                                   | [CVE-2010-3963](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3963) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-104](http://go.microsoft.com/fwlink/?linkid=206469) | Hibás kérelem kódfuttatási biztonsági rése                                                                | [CVE-2010-3964](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3964) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-094](http://go.microsoft.com/fwlink/?linkid=206699) | A függvénytárak nem biztonságos betöltése miatti biztonsági rés                                           | [CVE-2010-3965](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3965) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | **A biztonsági rés nyilvánosságra került**                 |  
| [MS10-095](http://go.microsoft.com/fwlink/?linkid=206683) | BranchCache, a függvénytárak nem biztonságos betöltése miatti biztonsági rés                              | [CVE-2010-3966](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3966) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | (Nincs)                                                    |  
| [MS10-093](http://go.microsoft.com/fwlink/?linkid=206698) | A függvénytárak nem biztonságos betöltése miatti biztonsági rés                                           | [CVE-2010-3967](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3967) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg konzisztens rosszindulatú programkód   | **A biztonsági rés nyilvánosságra került**                 |  
| [MS10-103](http://go.microsoft.com/fwlink/?linkid=198156) | Érvénytelen tömbindex memóriameghibásodási biztonsági rése a Pubconv.dll elemben                          | [CVE-2010-2571](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2571) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                    |  
| [MS10-098](http://go.microsoft.com/fwlink/?linkid=204869) | Win32k kétszeres felszabadítási biztonsági rése                                                           | [CVE-2010-3941](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3941) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                    |  
| [MS10-098](http://go.microsoft.com/fwlink/?linkid=204869) | Win32k WriteAV biztonsági rése                                                                            | [CVE-2010-3942](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3942) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                    |  
| [MS10-105](http://go.microsoft.com/fwlink/?linkid=147425) | CGM-képkonvertáló puffertúlcsordulási biztonsági rése                                                     | [CVE-2010-3945](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3945) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                    |  
| [MS10-105](http://go.microsoft.com/fwlink/?linkid=147425) | PICT-képkonvertáló egészszám-túlcsordulási biztonsági rése                                                | [CVE-2010-3946](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3946) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                    |  
| [MS10-105](http://go.microsoft.com/fwlink/?linkid=147425) | TIFF-képkonvertáló halomtúlcsordulási biztonsági rése                                                     | [CVE-2010-3947](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3947) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                    |  
| [MS10-105](http://go.microsoft.com/fwlink/?linkid=147425) | TIFF-képkonvertáló puffertúlcsordulási biztonsági rése                                                    | [CVE-2010-3949](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3949) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                    |  
| [MS10-105](http://go.microsoft.com/fwlink/?linkid=147425) | TIFF-képkonvertáló memóriameghibásodást okozó biztonsági rése                                             | [CVE-2010-3950](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3950) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                    |  
| [MS10-105](http://go.microsoft.com/fwlink/?linkid=147425) | FlashPix-képkonvertáló halommemória-sérülési biztonsági rése                                              | [CVE-2010-3952](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3952) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                    |  
| [MS10-103](http://go.microsoft.com/fwlink/?linkid=198156) | Tömbindexelési memóriameghibásodási biztonsági rés                                                        | [CVE-2010-3955](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3955) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                    |  
| [MS10-091](http://go.microsoft.com/fwlink/?linkid=203895) | Az OpenType betűtípus indexértékekre vonatkozó biztonsági rése                                            | [CVE-2010-3956](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3956) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Valószínűleg inkonzisztens rosszindulatú programkód | (Nincs)                                                    |  
| [MS10-101](http://go.microsoft.com/fwlink/?linkid=201319) | A Netlogon távoli eljáráshívás NULL-visszakeresésének szolgáltatásmegtagadást eredményező biztonsági rése | [CVE-2010-2742](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2742) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Nem valószínű működő rosszindulatú programkód       | A hiba csak szolgáltatásmegtagadást okoz                   |  
| [MS10-106](http://go.microsoft.com/fwlink/?linkid=204624) | Az Exchange Server végtelen ciklus biztonsági rése                                                        | [CVE-2010-3937](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3937) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Nem valószínű működő rosszindulatú programkód       | A hiba csak szolgáltatásmegtagadást okoz                   |  
| [MS10-103](http://go.microsoft.com/fwlink/?linkid=198156) | A Microsoft Publisher memóriameghibásodási biztonsági rése                                                | [CVE-2010-3954](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3954) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Nem valószínű működő rosszindulatú programkód       | (Nincs)                                                    |  
| [MS10-102](http://go.microsoft.com/fwlink/?linkid=205309) | Hyper-V VMBus biztonsági rés                                                                              | [CVE-2010-3960](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3960) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Nem valószínű működő rosszindulatú programkód       | A hiba csak szolgáltatásmegtagadást okoz                   |
  
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
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="14">
Windows XP  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://go.microsoft.com/fwlink/?linkid=206495)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://go.microsoft.com/fwlink/?linkid=203895)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://go.microsoft.com/fwlink/?linkid=206698)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://go.microsoft.com/fwlink/?linkid=206699)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://go.microsoft.com/fwlink/?linkid=206683)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://go.microsoft.com/fwlink/?linkid=206738)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://go.microsoft.com/fwlink/?linkid=206689)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://go.microsoft.com/fwlink/?linkid=204869)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://go.microsoft.com/fwlink/?linkid=206365)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://go.microsoft.com/fwlink/?linkid=204906)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://go.microsoft.com/fwlink/?linkid=201319)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://go.microsoft.com/fwlink/?linkid=205309)
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
<td style="border:1px solid black;">
Nincsenek
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
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Nincsenek
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
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=6031d98a-cd0f-4dd8-80b6-70a7167e9e55)  
(Kritikus)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=922a0835-7f69-4e37-a9f7-c64e976e3513)  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=a55b8029-9499-4219-99b7-65c30b0b864a)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=cdef3358-ad3e-40a6-9ba5-3be220a56a65)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Media kódoló 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=46baa431-126c-4fa5-9a7b-525008e2817d)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=fa9a1aac-b9c5-4d4e-9083-a080ad4ccc6f)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=bb9d1657-5beb-4372-b74c-a612a6fff5a8)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=4d0ae558-a4f2-4048-b5fd-ba072ca35e48)  
(Fontos)
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=5d3a5678-77f8-4ebc-8775-aedd25ef0eb8)  
(Kritikus)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a7c826b0-4aac-41ce-b297-6b6e11105c14)  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d5207bf5-7e58-4001-aa8f-f9a4b2c037d8)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=070fef8e-ba09-40f4-abaa-9cebf08983c3)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Media kódoló 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d)  
(Fontos)  
[Windows Media kódoló 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b9ce9d62-2eaa-48d8-bb6d-ea137e63d077)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6dabc306-c858-46b1-815c-cd8d011ff62e)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1f277ae4-4f85-4c8a-bfc5-dcdc8afed133)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=238bb885-eae6-464a-bb3d-679025f1cb50)  
(Fontos)
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
<th colspan="14">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://go.microsoft.com/fwlink/?linkid=206495)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://go.microsoft.com/fwlink/?linkid=203895)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://go.microsoft.com/fwlink/?linkid=206698)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://go.microsoft.com/fwlink/?linkid=206699)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://go.microsoft.com/fwlink/?linkid=206683)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://go.microsoft.com/fwlink/?linkid=206738)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://go.microsoft.com/fwlink/?linkid=206689)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://go.microsoft.com/fwlink/?linkid=204869)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://go.microsoft.com/fwlink/?linkid=206365)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://go.microsoft.com/fwlink/?linkid=204906)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://go.microsoft.com/fwlink/?linkid=201319)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://go.microsoft.com/fwlink/?linkid=205309)
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
<td style="border:1px solid black;">
Nincsenek
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
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=4f1f41fb-368a-42e6-8d17-fca83b64f57b)  
(Kritikus)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a3b57d26-5551-4785-86cf-41b532d78979)  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=4f5a3677-0990-4702-bf08-af64cf12cb6c)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9b70334c-490d-446c-988a-a88a75595fd4)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Media kódoló 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e0b2837c-019b-419b-954d-5bdc71a3a332)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8fa2cfa4-a01d-4910-b69f-736aeb585bab)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4aa39f59-2177-459f-9b8a-9543330d48ec)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c87af292-a068-4089-aab8-115c18b4b024)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ad843b97-2f6e-4406-a17a-627b7db8a926)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=6a9f56a0-230a-4dde-94da-f051ebf51f47)  
(Kritikus)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8b0d2a3a-7fed-4d48-9ec5-8558000e51bb)  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=1e134e5d-84fb-432b-99b1-593b1be5d5a4)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=08328e82-b012-4ea5-bf89-becb4881084f)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Media kódoló 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d)  
(Fontos)  
[Windows Media kódoló 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4c5cb600-9a39-40a0-be42-1593b1e0b97d)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=17b0b340-73b2-42a7-9d86-1297c63dcc2b)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bca61d61-d5cf-49a4-ab99-b61e50e8f619)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e17b8878-d065-49cc-bdba-0f24cdf35ea3)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0b0a06e7-0ae5-41f4-9ff5-d524fc0afbfa)  
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
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=7c1cf126-604c-4f70-bbe8-aa4d145eb68f)  
(Kritikus)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=96884bfa-00c8-4263-9936-d7c054919dd3)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 javítócsomaggal Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=15588d6a-f576-4e3d-95e8-d422af8a94de)  
(Fontos)
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
[Windows Server 2003 SP2 javítócsomaggal Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=9abc8270-f3ac-474d-9ebc-410aaa6262cc)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 javítócsomaggal Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=04a178cc-1afd-4e47-8cab-05e402e5a568)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 javítócsomaggal Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=4fce129d-2b4e-4a66-af27-bbbde1e65ba1)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 javítócsomaggal Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=ad896d80-167f-4e8f-a448-cac93516f4d0)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2003 SP2 javítócsomaggal Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=7c0c2850-e81d-4347-aeb3-47036caa7c1b)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="14">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://go.microsoft.com/fwlink/?linkid=206495)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://go.microsoft.com/fwlink/?linkid=203895)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://go.microsoft.com/fwlink/?linkid=206698)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://go.microsoft.com/fwlink/?linkid=206699)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://go.microsoft.com/fwlink/?linkid=206683)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://go.microsoft.com/fwlink/?linkid=206738)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://go.microsoft.com/fwlink/?linkid=206689)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://go.microsoft.com/fwlink/?linkid=204869)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://go.microsoft.com/fwlink/?linkid=206365)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://go.microsoft.com/fwlink/?linkid=204906)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://go.microsoft.com/fwlink/?linkid=201319)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://go.microsoft.com/fwlink/?linkid=205309)
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
Nincsenek
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Vista Service Pack 1 és Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=897351de-9697-4954-aa7e-169e980b932c)  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=bebf0df0-5ebe-44b4-9ace-b3085a993e58)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 és Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2ddb8a06-c9cc-4d33-b6d1-22dbda2d871f)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 és Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=48f10251-34d8-4149-b4b2-bf3ec28f5846)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=55141a02-3ad3-4691-98b9-80dd8ecb14c5)<sup>[1]</sup>
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Media kódoló 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=e8a57950-43cd-486f-bd97-70b0ad360a0b)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 és Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a1c7f1b5-e054-4cd6-857d-2ab0a2fe9f62)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 és Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b824d3b9-2ce1-4abc-ae06-68aef1250be9)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 és Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=85265a23-5094-4007-8d33-f402cabd1664)  
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
Windows Vista x64 Edition Service Pack 1 és Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=171c02f9-f7d2-42f2-ba31-4c819a43784a)  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=837b6056-af04-4aed-8afe-cc392770a590)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 és Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9a245f3c-ffb6-4ccd-956c-e7d1231fca30)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 és Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=099ccc5f-b92f-4d06-bcb5-92e35c49f613)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Movie Maker 2.6](http://www.microsoft.com/downloads/details.aspx?familyid=5b078136-a492-4a2e-939d-82799f774d82)<sup>[1]</sup>
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Media kódoló 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=f98c3b96-acb5-49f1-be42-3dd44d316408)  
(Fontos)  
[Windows Media kódoló 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=e1054088-f484-4f44-ba0e-5cbd21773c0c)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 és Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=73624b68-a69d-4517-b971-f0b7d2ccc9d6)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 és Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f4c42cfe-b7f2-4436-919e-4bd305a3439a)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 és Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=63c7257a-16bf-4108-80b9-9dfe53528348)  
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
<th colspan="14">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://go.microsoft.com/fwlink/?linkid=206495)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://go.microsoft.com/fwlink/?linkid=203895)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://go.microsoft.com/fwlink/?linkid=206698)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://go.microsoft.com/fwlink/?linkid=206699)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://go.microsoft.com/fwlink/?linkid=206683)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://go.microsoft.com/fwlink/?linkid=206738)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://go.microsoft.com/fwlink/?linkid=206689)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://go.microsoft.com/fwlink/?linkid=204869)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://go.microsoft.com/fwlink/?linkid=206365)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://go.microsoft.com/fwlink/?linkid=204906)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://go.microsoft.com/fwlink/?linkid=201319)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://go.microsoft.com/fwlink/?linkid=205309)
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
[**Kritikus**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 32 bites rendszerekhez és Windows Server 2008 32 bites rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f3785f3b-64c6-46a4-8e3a-9b9448124a8f)\*\*  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=98183a76-5642-4e19-b488-029eb7ed3942)\*\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez és Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=87149ec2-74a8-4dea-b7e3-873558e0103e)\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez és Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bdc9564a-4091-4cde-963a-239513db6c17)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Media kódoló 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=a4ea028f-edfc-4237-8325-7ece11fcf437)\*\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez és Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=118f528f-bd05-49c2-a4a4-78314cd00992)\*\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez és Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6e2f572a-4169-47f2-a872-5466997122ed)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez és Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=14e079a8-01a4-47c9-bd47-f5c9a6ca070a)\*\*  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 32 bites rendszerekhez és Windows Server 2008 32 bites rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6793f75b-cdf4-42ef-a53e-a1acb5b662d1)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 x64-alapú rendszerekhez és Windows Server 2008 x64-alapú rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=4b81aae5-6034-4c83-b5d2-e7e472435284)\*\*  
(Kritikus)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=d47b457d-e995-4a7e-9bfa-eebab9b3a729)\*\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64 alapú rendszerekhez és Windows Server 2008 x64 alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=523a47d3-771d-471a-889b-16311c276a00)\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64 alapú rendszerekhez és Windows Server 2008 x64 alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dff39bfe-0799-4912-ae22-392562178ae6)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Media kódoló 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=f468d2b5-f02c-4691-9fb5-a7f69752f126)\*\*  
(Fontos)  
[Windows Media kódoló 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=533d91d8-0291-421e-9701-3bd86d18bc45)\*\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64 alapú rendszerekhez és Windows Server 2008 x64 alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=77e288fb-b51f-4f57-baac-1443d8fbd37b)\*\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64 alapú rendszerekhez és Windows Server 2008 x64 alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=09a4b646-989d-43ef-a3e8-64af8b380a14)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64 alapú rendszerekhez és Windows Server 2008 x64 alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6baf92b7-a336-45f2-a1ba-c00c34dfb76f)\*\*  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64 alapú rendszerekhez és Windows Server 2008 x64 alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=85add876-ca5a-4a92-984e-188a72e349fc)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 x64 alapú rendszerekhez és Windows Server 2008 x64 alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b8c06bbc-6e84-4cf1-89f0-c0d34cfffaed)\*  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 Itanium-alapú rendszerekhez és Windows Server 2008 Itanium-alapú rendszerekhez, Service Pack 2
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=8ddafaaf-84a0-4325-b06f-4aac7cd61274)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 Itanium-alapú rendszerekhez és Windows Server 2008 Itanium-alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=959146ee-0e70-4e56-9012-72ed59aeb24b)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 Itanium-alapú rendszerekhez és Windows Server 2008 Itanium-alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=cf341a35-32ea-4ff7-aca9-1a4683c100ee)  
(Fontos)
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
[Windows Server 2008 Itanium-alapú rendszerekhez és Windows Server 2008 Itanium-alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=82f71194-6f1f-4f43-8752-4bf5e5f94a93)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 Itanium-alapú rendszerekhez és Windows Server 2008 Itanium-alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=46522323-837e-4a74-9cf0-45f69343e776)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 Itanium-alapú rendszerekhez és Windows Server 2008 Itanium-alapú rendszerekhez, Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7a4b23d4-f68e-4d5b-8814-d9247145f164)  
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
<th colspan="14">
Windows 7
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://go.microsoft.com/fwlink/?linkid=206495)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://go.microsoft.com/fwlink/?linkid=203895)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://go.microsoft.com/fwlink/?linkid=206698)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://go.microsoft.com/fwlink/?linkid=206699)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://go.microsoft.com/fwlink/?linkid=206683)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://go.microsoft.com/fwlink/?linkid=206738)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://go.microsoft.com/fwlink/?linkid=206689)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://go.microsoft.com/fwlink/?linkid=204869)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://go.microsoft.com/fwlink/?linkid=206365)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://go.microsoft.com/fwlink/?linkid=204906)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://go.microsoft.com/fwlink/?linkid=201319)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://go.microsoft.com/fwlink/?linkid=205309)
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
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 7 32 bites rendszerekhez
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c288fe87-b113-4615-9b02-5e388bcb5241)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows 7 32 bites rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=ff590db8-4264-42ba-9e07-88d100e1c4f5)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows 7 32 bites rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=cf85cdb6-58c7-4144-82f6-f01a6a4f9c3a)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows 7 32 bites rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=75591d37-2cb8-4cdf-acbb-89cd0d1a9290)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows 7 32 bites rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=4e8ad5cd-af27-4f00-9378-ad778b8ee7b3)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows 7 32 bites rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=aa7de2e4-ba48-4d58-b034-05349f0eb920)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows 7 32 bites rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=f7c7d57a-d031-46a3-9613-eae2b9cb6401)  
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
Windows 7 x64-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=2cf4ac70-88b4-4840-9895-2bcf119312a7)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows 7 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=4ea4e339-9db2-4b99-b567-80ee55ecdf92)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows 7 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=0597018d-39f5-4ca9-b437-63d9e68f264d)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows 7 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=3a0c4dd0-98b4-4e7a-99ed-22b9d9f76cd1)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows 7 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=35a3e821-b463-411c-858b-d01eb5aed42b)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows 7 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=b21db627-91c2-4ebf-b7c0-38ac58ae5b6c)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows 7 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=e52c36f5-637b-4928-83d0-27514c6cc384)  
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
<th colspan="14">
Windows Server 2008 R2
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS10-090**](http://go.microsoft.com/fwlink/?linkid=206495)
</td>
<td style="border:1px solid black;">
[**MS10-091**](http://go.microsoft.com/fwlink/?linkid=203895)
</td>
<td style="border:1px solid black;">
[**MS10-092**](http://go.microsoft.com/fwlink/?linkid=203463)
</td>
<td style="border:1px solid black;">
[**MS10-093**](http://go.microsoft.com/fwlink/?linkid=206698)
</td>
<td style="border:1px solid black;">
[**MS10-094**](http://go.microsoft.com/fwlink/?linkid=206699)
</td>
<td style="border:1px solid black;">
[**MS10-095**](http://go.microsoft.com/fwlink/?linkid=206683)
</td>
<td style="border:1px solid black;">
[**MS10-096**](http://go.microsoft.com/fwlink/?linkid=206738)
</td>
<td style="border:1px solid black;">
[**MS10-097**](http://go.microsoft.com/fwlink/?linkid=206689)
</td>
<td style="border:1px solid black;">
[**MS10-098**](http://go.microsoft.com/fwlink/?linkid=204869)
</td>
<td style="border:1px solid black;">
[**MS10-099**](http://go.microsoft.com/fwlink/?linkid=206365)
</td>
<td style="border:1px solid black;">
[**MS10-100**](http://go.microsoft.com/fwlink/?linkid=204906)
</td>
<td style="border:1px solid black;">
[**MS10-101**](http://go.microsoft.com/fwlink/?linkid=201319)
</td>
<td style="border:1px solid black;">
[**MS10-102**](http://go.microsoft.com/fwlink/?linkid=205309)
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
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
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
<td style="border:1px solid black;">
[**Fontos**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 R2 x64-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=99a91ba7-035b-4717-ada5-c1ad6645db64)\*\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=e52f7869-474a-44c8-a102-e766c576fc01)\*  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=28c832fb-4937-4652-8799-eab6c76d05fb)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=f58a765f-cea9-456d-b0ab-bfc70b109cbf)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=9e2c95f6-9381-4484-b11b-814ab9138118)\*\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=d417ebce-7841-4bbb-8abc-b15ef5f4b733)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=b823a7aa-0eb9-42dd-bf56-8907d94b314a)\*\*  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=d7307afd-84a0-434e-9658-bf9f8ae4b938)\*  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=39b7abc7-65a4-4dfd-92ba-c638e3de1118)\*  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 Itanium-alapú rendszerekhez
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=c26de145-94b8-404a-b946-744988fab83b)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=a21d061a-794a-4012-b3cd-c67445c074f5)  
(Kritikus)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=3ad64d5c-2d81-4ac8-934e-8917b2fcf961)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=13a9f838-ac07-43dc-9aee-a77207998e1e)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=cb4211f3-1082-4245-8f03-7cbac90e9a31)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=7eeac1bb-9f86-4ea5-b30f-980d52be5044)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 Itanium-alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=66b2506d-80e0-4e32-86e6-0908ef56ae90)  
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
 
**Megjegyzések a Windows Server 2008 és Windows Server 2008 R2 rendszerhez**

**\*Érinti a kiszolgálómag telepítését.** Ez a frissítés ugyanolyan biztonsági besorolás mellett, a megadottak szerint érvényes az Windows Server 2008 és a Windows Server 2008 R2 összes támogatott kiadására, függetlenül attól, hogy a kiszolgálómag-telepítési opcióval telepítették-e. Erről a telepítési opcióról bővebben a [Kiszolgálómag-telepítés kezelése](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)és [Kiszolgálómag-telepítés szervizelése](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) TechNet cikkekben olvashat. A kiszolgálómag-telepítési opció nem vonatkozik a Windows Server 2008 és a Windows Server 2008 R2 bizonyos kiadásaira; lásd: [A kiszolgálómag-telepítési opciók összehasonlítása](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*A kiszolgálómag-telepítés nem érintett.** A frissítésben tárgyalt biztonsági rések nem érintik a jelzett módon a Windows Server 2008 és a Windows Server 2008 R2 támogatott kiadásait, amennyiben a telepítés a kiszolgálómag-telepítési opció használatával történt. Erről a telepítési opcióról bővebben a [Kiszolgálómag-telepítés kezelése](http://technet.microsoft.com/en-us/library/ee441255(ws.10).aspx)és [Kiszolgálómag-telepítés szervizelése](http://technet.microsoft.com/en-us/library/ff698994(ws.10).aspx) TechNet cikkekben olvashat. A kiszolgálómag-telepítési opció nem vonatkozik a Windows Server 2008 és a Windows Server 2008 R2 bizonyos kiadásaira; lásd: [A kiszolgálómag-telepítési opciók összehasonlítása](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Megjegyzés az MS10-093 közleményhez**

<sup>[1]</sup>A Windows Movie Maker 2.6 opcionálisan letölthető összetevő, amely telepíthető az érintett operációs rendszerekre.

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
Microsoft Office programcsomagok és összetevők
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS10-103**](http://go.microsoft.com/fwlink/?linkid=198156)
</td>
<td style="border:1px solid black;">
[**MS10-105**](http://go.microsoft.com/fwlink/?linkid=147425)
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
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=f540692c-e404-4383-8937-4d6a36475da5)  
(KB2284692)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=724d0ad6-ba5f-4dbf-b280-3fb36335d33b)<sup>[1]</sup>
(KB2289162)  
(Fontos)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=e600de65-3e9d-4e37-8906-8b7091ff523e)  
(KB2284695)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=976857e9-77fc-4667-88ca-7637e57536cd)<sup>[1]</sup>
(KB2289163)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office Publisher 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=79275011-bdc1-446a-8ea6-56fc31bd9c35)  
(KB2284697)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=676eeed6-f2b7-4265-afc7-a82ffdbeb290)  
(KB2288931)  
(Nincs súlyossági besorolás<sup>[2]</sup>)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2010 (32 bites kiadások)
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2010 (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=99e18990-75e9-497e-9b4f-5d7ef8656ab2)  
(KB2409055)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=6d644494-b530-4b37-bc37-8a8a7edefe53)  
(KB2289078)  
(Nincs súlyossági besorolás<sup>[2]</sup>)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 (64 bites kiadások)
</td>
<td style="border:1px solid black;">
[Microsoft Publisher 2010 (64 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=9b27ee11-e563-4152-9691-25eec1ee9966)  
(KB2409055)  
(Fontos)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2010 (64 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=58e54779-aa8f-41b3-9993-8cec12c49082)  
(KB2289078)  
(Nincs súlyossági besorolás<sup>[2]</sup>)
</td>
</tr>
<tr>
<th colspan="3">
További Office-szoftverek
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS10-103**](http://go.microsoft.com/fwlink/?linkid=198156)
</td>
<td style="border:1px solid black;">
[**MS10-105**](http://go.microsoft.com/fwlink/?linkid=147425)
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
Microsoft Office Converter Pack
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Office Converter Pack](http://www.microsoft.com/downloads/details.aspx?familyid=dcded2ee-0673-4afe-abe6-04941a2ad306)  
(KB2456849)  
(Fontos)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Works 9
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Works 9](http://www.microsoft.com/downloads/details.aspx?familyid=10f6f330-05d8-4b60-9ebb-822a7321ac0f)  
(KB2431831)  
(Fontos)
</td>
</tr>
</table>
 
**Megjegyzések az MS10-105 közleményhez**

<sup>[1]</sup>A jelzett szoftverek felhasználóinak telepíteniük kell a Microsoft Office MS10-087 közleményben ismertetett frissítését: csak ez biztosít védelmet az MS10-105 közleményben foglalt biztonsági rések ellen.

<sup>[2]</sup>A súlyossági besorolások nem vonatkoznak erre a frissítésre, mivel a tárgyalt biztonsági rések nem érintik ezt a szoftvert. Ennek ellenére a jövőben felfedezett esetleges új támadási pontok elleni mélyreható védekezési lépésként a Microsoft azt javasolja, hogy a szoftver felhasználói alkalmazzák ezt a biztonsági frissítést.

#### Microsoft Server Software

 
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
Microsoft SharePoint Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS10-104**](http://go.microsoft.com/fwlink/?linkid=206469)
</td>
<td style="border:1px solid black;">
[**MS10-106**](http://go.microsoft.com/fwlink/?linkid=204624)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2 (32 bites kiadások)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (32 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=3c8fb9f9-7920-43ea-b618-e26dc3360c60)  
(KB2433089)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 2 (64 bites kiadások)
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 2 (64 bites kiadások)](http://www.microsoft.com/downloads/details.aspx?familyid=3db09280-24bd-42e0-9ae3-02c9bf3e8ee3)  
(KB2433089)  
(Fontos)
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
</tr>
<tr>
<th colspan="3">
Microsoft Exchange Server
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Közlemény azonosítója**
</td>
<td style="border:1px solid black;">
[**MS10-104**](http://go.microsoft.com/fwlink/?linkid=206469)
</td>
<td style="border:1px solid black;">
[**MS10-106**](http://go.microsoft.com/fwlink/?linkid=204624)
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
[**Mérsékelt**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Exchange Server 2007 Service Pack 2 x64 alapú rendszerekhez
</td>
<td style="border:1px solid black;">
Nem érintett
</td>
<td style="border:1px solid black;">
[Microsoft Exchange Server 2007 Service Pack 2 x64 alapú rendszerekhez](http://www.microsoft.com/downloads/details.aspx?familyid=7b983156-9e9f-4d29-9e9b-2369747e3b62)  
(KB2407132)  
(Mérsékelt)
</td>
</tr>
</table>
 

Észlelési és telepítési eszközök, útmutatás
-------------------------------------------

<span></span>
**Biztonsági központ**

A szoftveres és biztonsági frissítések kezeléséhez azokat a szervezet asztali és hordozható számítógépeire, valamint kiszolgálóira is telepíteni kell. További tájékoztatásért látogasson el a [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903) weboldalára. A [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) bővebb tájékoztatással szolgál a Microsoft-termékek biztonsági funkcióival kapcsolatban. A [Biztonság otthon](http://go.microsoft.com/fwlink/?linkid=85102) weboldalon a megfelelő hivatkozásra kattintva elérhetőek a legújabb biztonsági frissítések.

A biztonsági frissítések a [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) és a [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) weboldalról tölthetők le. A biztonsági frissítések a [Microsoft letöltőközpontjában](http://go.microsoft.com/fwlink/?linkid=21129) is elérhetőek. Legegyszerűbben a „security update” kifejezésre irányuló kulcsszavas kereséssel találhatja meg ezeket.

A Microsoft Office for Mac felhasználók számára a Microsoft AutoUpdate for Mac szolgáltatás biztosítja a Microsoft szoftverek naprakész állapotát.. A Microsoft AutoUpdate for Mac működésének részleteiről lásd: [Szoftverfrissítések automatikus keresése](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

A biztonsági frissítések a [Microsoft Update katalógusából](http://go.microsoft.com/fwlink/?linkid=96155) is letölthetőek. A Microsoft Update katalógus a Windows Update és Microsoft Update szolgáltatáson keresztül elérhető tartalom kereshető adatbázisa; ide tartoznak a biztonsági frissítések, illesztőprogramok és szervizcsomagok. A biztonsági közlemény azonosítójára (pl. „MS07-036”) történő kereséssel hozzáadhatja az összes vonatkozó frissítést a kosárhoz (beleértve a frissítés különböző nyelvi változatait), és letöltheti azokat a megadott mappába. A Microsoft Update katalógus részletes leírását lásd a vonatkozó [GYIK](http://go.microsoft.com/fwlink/?linkid=97900)részben.

**Útmutató az észleléshez és a telepítéshez**

A biztonsági frissítésekkel kapcsolatban a Microsoft észlelési és telepítési segítséget nyújt. Ez az útmutató olyan javaslatokat és tudnivalókat tartalmaz, amelyeket segítséget nyújthatnak az informatikusoknak a biztonsági frissítések észlelési és telepítési eszközeinek használatához. További tudnivalókat a [Microsoft Tudásbázis 961747. számú cikkében](http://support.microsoft.com/kb/961747) talál.

**Microsoft Baseline Security Analyzer**

A Microsoft Baseline Security Analyzer (MBSA) segítségével a rendszergazda mind a helyi, mind a távoli számítógépeken ellenőrizheti, hogy mely biztonsági frissítések hiányoznak, illetve hogy mely biztonsági beállítások vannak helytelenül megadva. Ha többet szeretne tudni az MBSA -eszközről, látogasson el a [Microsoft Baseline Security Analyzer webhelyre](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

A Microsoft Server Update Services (WSUS) szolgáltatással a rendszergazdák gyorsan és megbízhatóan telepíthetik a legújabb fontos és biztonsági frissítéseket Microsoft Windows 2000 és újabb operációs rendszerekhez, Office XP és újabb operációs rendszerekhez, Exchange Server 2003 és SQL Server 2000 Microsoft Windows 2000 és újabb operációs rendszerekre.

A biztonsági frissítésnek Windows Server Update Services szolgáltatással történő központi telepítéséről a [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120) webhelyen tudhat meg többet.

**SystemCenter Configuration Manager 2007**

A Configuration Manager 2007 szoftverfrissítés-kezelés leegyszerűsíti a frissítéseknek a vállalat minden IT-rendszerére történő eljuttatása és kezelése összetett feladatát. A Configuration Manager 2007 segítségével az IT-rendszergazdák a Microsoft-termékek frissítéseit számos készülékre juttathatják el, köztük asztali számítógépekre, hordozható számítógépekre, kiszolgálókra és mobilkészülékekre.

A Configuration Manager 2007 automatizált biztonságirés-elemzése jelzi a frissítések szükségességét és jelentést küld a javasolt lépésekről. A Configuration Manager 2007 szoftverfrissítés-kezelése a Microsoft Windows Software Update Services (WSUS) szolgáltatására épül, amely az IT-rendszergazdák számára világszerte ismerős, jól bevált frissítési infrastruktúra. További információkat a Configuration Manager 2007 rendszergazdai használatáról a frissítések telepítéséhez lásd: [Szoftverfrissítés-kezelés](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). További információkért a Configuration Manager alkalmazásról látogasson el a [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx) oldalra.

**Systems Management Server 2003**

A Microsoft Systems Management Server (SMS) rendszer egy sokoldalúan beállítható vállalati megoldás, amely a frissítések kezelésére szolgál. Az SMS segítségével a rendszergazda megállapíthatja, hogy melyik Windows alapú számítógép szorul biztonsági frissítésre, és ezeket a frissítéseket szabályozott módon, a felhasználók minimális zavarásával központilag telepítheti a vállalat teljes informatikai környezetében.

**Megjegyzés** A System Management Server 2003 alkalmazáshoz 2010. január 1-jétől nem tartozik általános támogatás. Az életciklusokra vonatkozó bővebb tájékoztatásért látogasson el ide: . Az SMS, System Center Configuration Manager 2007 legújabb kiadása már elérhető; lásd feljebb, **SystemCenter Configuration Manager 2007**.

Ha többet szeretne tudni arról, hogy a rendszergazdák miként telepíthetik a biztonsági frissítéseket az SMS 2003 alkalmazással, látogasson el a [Forgatókönyvek és eljárások a Microsoft Systems Management Server 2003 alkalmazáshoz Szoftverterjesztés és javításkezelés](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en) oldalra. Az SMS-szolgáltatásról bővebben a [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx) oldalán olvashat.

**Megjegyzés** Az SMS a Microsoft Baseline Security Analyzer eszközön keresztül széles körű támogatást nyújt a biztonsági közlemények frissítéseinek észleléséhez, valamint a frissítések telepítéséhez. Előfordulhat, hogy egyes szoftverfrissítéseket ezek az eszközök nem észlelnek. Az SMS-alkalmazás leltározási szolgáltatásai segítségével a rendszergazdák adott rendszereken hajthatják végre a frissítést. Az eljárással kapcsolatban olvassa el a [szoftverfrissítések telepítése az SMS szoftverelosztó ügynök segítségével](http://go.microsoft.com/fwlink/?linkid=33341) című tájékoztatót. Egyes biztonsági frissítésekhez rendszergazdai jogosultságokra van szükség a számítógép újraindítása után. A rendszergazdák az Elevated Rights Deployment Tool eszközt (az [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en) része) alkalmazhatják a frissítések telepítéséhez.

**Az Update Compatibility Evaluator (a frissítéskompatibilitás kiértékelője) és az Application Compatibility Toolkit (alkalmazáskompatibilitási eszközkészlet)**

Az alkalmazások működése érdekében a frissítések gyakran írnak ugyanazokba a fájlokba, illetve regisztrációs bejegyzésekbe. Ez inkompatibilitást okozhat, és növelheti a biztonsági frissítések központi telepítésére használt időt. A Windows frissítések és az alkalmazásoknak való megfelelőség tesztelése és ellenőrzése egyszerűsíthető az [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true) eszközeivel, ami része az [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=hu) alkalmazáskompatibilitási eszközkészletnek.

Az Application Compatibility Toolkit (ACT) tartalmazza a Microsoft Windows Vista, a Windows Update, a Microsoft Security Update vagy a Windows Internet Explorer új verziójának központi telepítése előtt az alkalmazáskompatibilitási problémák kiértékeléséhez és enyhítéséhez szükséges eszközöket és dokumentációt.

### Egyéb információ

#### A Microsoft Windows rosszindulatú szoftvereket eltávolító eszköze

A Microsoft a Windows Update, Microsoft Update, Windows Server Update Services és Letöltőközpont szolgáltatásán keresztül elérhetővé tette a Microsoft Windows rosszindulatú szoftvereket eltávolító eszközének frissített változatát.

#### Nem biztonsági jellegű, kiemelt fontosságú frissítések a MU, WU és WSUS-szolgáltatásokban

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

-   Aniway, [VeriSign iDefense Labs](http://labs.idefense.com/), az MS10-090 közleményben bemutatott két probléma jelentéséért
-   Nicolas Joly, [VUPEN Vulnerability Research Team](http://www.vupen.com/), az MS10-090 közleményben leírt probléma jelentéséért
-   Stephen Fewer, a [TippingPoint](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) programjával együttműködésben, az MS10-090 közleményben ismertetett probléma jelentéséért
-   [Peter Vreugdenhil](http://vreugdenhilresearch.nl), a [TippingPoint](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/) programjával együttműködésben, az MS10-090 közleményben ismertetett probléma jelentéséért
-   [Yosuke Hasegawa](http://utf-8.jp/), az MS10-090 közleményben ismertetett probléma közös megoldásában való részvételéért
-   Jose Antonio Vazquez Gonzalez, [VeriSign iDefense Labs](http://labs.idefense.com/) az MS10-090 közleményben ismertetett probléma jelentéséért
-   Marc Schoenefeld, [Red Hat Security Response Team](https://www.redhat.com/security/team/), [Opera Security Team](http://www.opera.com/security/), az MS10-091 közleményben leírt egyik biztonsági rés jelentéséért
-   Marc Schoenefeld, [Red Hat Security Response Team](https://www.redhat.com/security/team/), az MS10-091 számú közleményben bemutatott probléma jelentéséért
-   Paul-Kenji Cahier Furuya, az MS10-091 számú közleményben bemutatott probléma jelentéséért
-   Sergey Golovanov, Alexander Gostev, Maxim Golovkin és Alexey Monastyrsky, a [Kaspersky Lab](http://usa.kaspersky.com/), valamint Vitaly Kiktenko és Alexander Saprykin, a [Design and Test Lab](http://www.dnt-lab.com/) munkatársai az MS10-092 közleményben leírt probléma jelentéséért
-   Liam O Murchu, [Symantec](http://www.symantec.com/index.jsp), az MS10-092 közleményben leírt probléma jelentéséért
-   Alexandr Matrosov, Eugene Rodionov, Juraj Malcho és David Harley, [ESET](http://www.eset.com/), az MS10-092 számú közleményben bemutatott probléma jelentéséért
-   Haifei Li, [Fortinet, FortiGuard Labs](http://www.fortiguard.com/), az MS10-095 közleményben ismertetett problémák egyikének jelentéséért
-   Simon Raner, [ACROS Security](http://www.acrossecurity.com), az MS10-096 közleményben bemutatott probléma jelentéséért
-   HD Moore, [Rapid7,](http://www.rapid7.com/) az MS10-096 számú közleményben bemutatott probléma jelentéséért
-   Muhaimin Dzulfakar, [NGSSoftware](http://www.ngssoftware.com/), az MS10-096 közleményben ismertetett probléma jelentéséért
-   Muhaimin Dzulfakar, [NGSSoftware](http://www.ngssoftware.com/), az MS10-097 közleményben ismertetett probléma jelentéséért
-   Tarjei Mandt, [Norman](http://www.norman.com/), az MS10-098 számú közleményben bemutatott probléma jelentéséért
-   Stéfan Le Berre, [Sysdream](http://www.sysdream.com/), az MS10-098 számú közleményben bemutatott probléma jelentéséért
-   Honggang Ren, [Fortinet FortiGuard Labs](http://www.fortiguard.com/), az MS10-099 számú közleményben bemutatott probléma jelentéséért
-   Cesar Cerrudo, [Argeniss](http://www.argeniss.com/), az MS10-100 közleményben bemutatott probléma jelentéséért
-   Matthias Dieter Wallnöfer és Andrew Bartlett, The Samba Team, a MS10-101 közleményben bemutatott probléma jelentéséért
-   [HP](http://www.hp.com/) és [techit](http://www.techit.de/), a MS10-102 közleményben bemutatott probléma jelentéséért
-   Chaouki Bekrar, [VUPEN Vulnerability Research Team](http://www.vupen.com/), az MS10-103 közleményben leírt öt probléma jelentéséért
-   Oleksandr Mirosh, [TippingPoint](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/), az MS10-104 közleményben ismertetett probléma jelentéséért
-   Yamata Li, [Palo Alto Networks](http://www.paloaltonetworks.com/), az MS10-105 közleményben ismertetett két probléma jelentéséért
-   Alin Rad Pop, [Secunia Research](http://secunia.com/), az MS10-105 közleményben leírt problémák egyikének jelentéséért
-   Carsten Eiram, [Secunia Research](http://secunia.com/), az MS10-105 közleményben leírt három probléma jelentéséért
-   Dyon Balding, [Secunia Research](http://secunia.com/), az MS10-105 közleményben leírt két probléma jelentéséért
-   Oleksandr Mirosh, [TippingPoint](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/), az MS10-106 közleményben ismertetett probléma jelentéséért

#### Terméktámogatás

-   Teszteléssel állapították meg a felsorolt szoftverek egyes verzióinak érintettségét. A többi verzió támogatási életciklusa végére ért. Az egyes szoftververziók támogatási életciklusáról a [Microsoft termékek terméktámogatási életciklusát ismertető webhelyen](http://go.microsoft.com/fwlink/?linkid=21742) talál felvilágosítást.
-   Az Amerikai Egyesült Államokban és Kanada területén élő ügyfelek technikai támogatást kérhetnek a [biztonsági támogatás szolgáltatójától](http://go.microsoft.com/fwlink/?linkid=21131) vagy az 1-866-PCSAFETY telefonszámon. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. Az elérhető támogatási lehetőségekről további információt talál a [Microsoft segítségnyújtással és támogatással foglalkozó webhelyén](http://support.microsoft.com/).
-   Más országokban a helyi Microsoft-képviseletek nyújtanak támogatást. A biztonsági frissítésekkel kapcsolatos hívások ingyenesek. A [nemzetközi támogatási webhely](http://go.microsoft.com/fwlink/?linkid=21155) felvilágosítást nyújt arról, támogatási kérdéseivel hogyan fordulhat a Microsofthoz.

#### Felelősséget kizáró nyilatkozat

A Microsoft Tudásbázisban leírtak előzetes bejelentés nélkül változhatnak, és a cikkek tartalmáért a Microsoft nem vállal garanciát. A Microsoft egyben elhárít minden kifejezett és értelemszerű garanciát, beleértve az eladhatóságra és az adott célra való alkalmasságra vonatkozó garanciát is. A Microsoft Corporation vagy annak szállítói semmilyen körülmények között nem tehetők felelőssé közvetlen, közvetett, eseti, ok-okozati vagy különleges kárért (beleértve az elmaradt hasznot is), még akkor sem, ha a Microsoft Corporation vagy szállítói tudatában voltak a kár lehetséges voltának. Egyes államok törvényi szabályozása nem teszi lehetővé a véletlen vagy ok-okozati károkért vállalt felelősség korlátozását vagy kizárását, így ezekben az államokban az ez a felelősségkizárás nincs érvényben.

#### Verziók

-   1.0 verzió (2010. december 14.): Összefoglaló közlemény közzététele.
-   1.1 verzió (2010. december 15.): Hangsúlyozza, hogy a Microsoft Office XP és Microsoft Office 2003 felhasználóknak telepíteniük kell az MS10-087 közleményben tárgyalt frissítést: csak ez biztosít védelmet az MS10-105 közleményben foglalt biztonsági rések ellen.

*Built at 2014-04-18T01:50:00Z-07:00*
