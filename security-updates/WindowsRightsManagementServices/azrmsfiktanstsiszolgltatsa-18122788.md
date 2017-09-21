---
TOCTitle: Az RMS fióktanúsítási szolgáltatása
Title: Az RMS fióktanúsítási szolgáltatása
ms:assetid: 'fb294969-850e-44b4-8f6a-ca5d5cec1bf1'
ms:contentKeyID: 18122788
ms:mtpsurl: 'https://technet.microsoft.com/hu-hu/library/Cc747802(v=WS.10)'
---

Az RMS fióktanúsítási szolgáltatása
===================================

A fióktanúsítási szolgáltatás csak az RMS legfelső szintű fürtjén fut. A fióktanúsítási szolgáltatás hozza létre a tartalomvédelmi fióktanúsítványokat, amelyek adott számítógépekhez társítják a felhasználói fiókokat. A tartalomvédelmi fióktanúsítvány lehetővé teszi a felhasználónak, hogy adott számítógépen tartalomvédelemmel ellátott tartalmat tegyen közzé vagy használjon.

A fióktanúsítási szolgáltatás alkalmazásfájlja, a Certification.asmx, az IIS szolgáltatás Certification virtuális könyvtárában található.

A szolgáltatás alapértelmezett hozzáférési szabálygyűjteményét a következő táblázat szemlélteti:

###  

<p> </p>
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Felhasználó vagy Csoport</th>
<th>Alapértelmezett engedély</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><p>Rendszergazdák</p></td>
<td style="border:1px solid black;"><p>Teljes hozzáférés</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p>RMS szolgáltatáscsoport</p></td>
<td style="border:1px solid black;"><p>Olvasás és végrehajtás</p></td>
</tr>  
<tr class="odd">
<td style="border:1px solid black;"><p>RENDSZER</p></td>
<td style="border:1px solid black;"><p>Teljes hozzáférés</p></td>
</tr>  
<tr class="even">
<td style="border:1px solid black;"><p>Felhasználók</p></td>
<td style="border:1px solid black;"><p>Olvasás és végrehajtás</p></td>
</tr>  
</tbody>  
</table>