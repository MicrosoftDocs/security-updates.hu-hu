---
TOCTitle: Az RMS működése
Title: Az RMS működése
ms:assetid: 'd7ddcc38-b7e3-4a2a-9506-7db44f7cb56e'
ms:contentKeyID: 18122758
ms:mtpsurl: 'https://technet.microsoft.com/hu-hu/library/Cc747763(v=WS.10)'
---

Az RMS működése
===============

A „tartalomvédelmi szolgáltatások (RMS)” fogalom minden olyan kiszolgálói és ügyféloldali technológiát magában foglal, amely a szervezeteknél az adatok védelméhez szükséges lehet. Az RMS tanúsítási és licenckiszolgálói, közösen a Microsoft által működtetett RMS szolgáltatásokkal (igénylés, aktiválás és RMS fióktanúsítás) tanúsítással látják el az RMS rendszerben részt vevő megbízható entitásokat. Emellett az RMS szervezetben lévő licenckiszolgálói közzétételi és használati licenceket állítanak ki, amelyek az RMS-védelemmel ellátott tartalom felhasználási módját szabályozzák. Az RMS ügyféloldali technológiái, azaz az RMS ügyfélszoftvere, a kulcstároló és az RMS-kompatibilis alkalmazások az ügyfélszámítógépeken futnak, és lehetővé teszik a felhasználóknak RMS-védelemmel ellátott tartalom létrehozását, közzétételét és használatát.

Az RMS különböző ügyféloldali és kiszolgálói technológiái együttműködve biztosítják a következő funkciókat:

-   **RMS-védelemmel ellátott tartalom létrehozása**. Az RMS rendszerben megbízhatónak minősített felhasználók egyszerűen létrehozhatnak és kezelhetnek védett fájlokat a közismert RMS-kompatibilis alkalmazások és eszközök használatával. Emellett az RMS-kompatibilis alkalmazások központilag meghatározott és jóváhagyott jogmegadási sablonokat is használhatnak, ami segítséget nyújt a felhasználóknak az előre megadott vállalati használati szabályok hatékony alkalmazásához. A Microsoft és más szoftverfejlesztők egyaránt készítenek az RMS rendszerrel használható alkalmazásokat.
-   **Az RMS-védelemmel ellátott tartalom licencelése és terjesztése**. Az RMS rendszerben működő kiszolgálók által kiállított tanúsítványok azonosítják azokat a megbízható entitásokat, amelyek jogosultak RMS-védelemmel ellátott tartalom közzétételére és használatára. Az RMS rendszerben megbízhatónak minősített felhasználók használati jogokat és feltételeket rendelhetnek az általuk létrehozott és védeni kívánt tartalomhoz. Ezek a használati szabályok meghatározzák, hogy ki és milyen célra használhatja fel a tartalmat. A szerzők közzétételi licencet is kérelmezhetnek, amely a megadott tartalomhoz köti a használati szabályokat. Ezt követően terjeszthetik a tartalmat, például úgy, hogy elküldik a szervezet más felhasználóinak, hogy vállalati használat céljából közzéteszik egy belső kiszolgálón, vagy megbízható külső partnereknek elküldik.
    Az RMS rendszer a felhasználók számára észrevétlen eljárással ellenőrzi a közzétételi licenc iránti kérelemben szereplő megbízható entitások érvényességét, majd kiállítja a tartalomhoz a meghatározott használati jogokat és feltételeket tartalmazó licencet. Az RMS-kompatibilis alkalmazás ezután előállítja a szimmetrikus kulcsokat, és ezek használatával titkosítja a tartalmat. Miután ezzel az eljárással megtörtént a tartalom védelme, csak a közzétételi licencekben megadott felhasználók tudják visszafejteni és használni a tartalmat. Ezeknek a felhasználóknak megbízható entitásnak kell lenniük az RMS rendszerben.
-   **Az RMS-védelemmel ellátott tartalom visszafejtéséhez szükséges licencek beszerzése, a használati szabályok betartatása**. A megbízható entitásnak minősített felhasználók megbízható ügyfél segítségével használhatják az RMS-védelemmel ellátott tartalmat. Ilyen ügyfélnek az RMS-kompatibilis számítógépeket és alkalmazásokat számítanak, amelyek lehetővé teszik a felhasználóknak az RMS-védelemmel ellátott tartalom megtekintését és használatát, a tartalom épségének megóvását, valamint a használati szabályok betartatását. Amikor egy felhasználó RMS-védelemmel ellátott tartalomhoz kísérel meg hozzáférni, az RMS kiszolgáló kérelmet kap, hogy állítson ki a felhasználónak a tartalom használatához szükséges használati licencet.
    Az RMS kiszolgáló a felhasználók számára észrevétlen eljárással kiállítja az egyedi használati licencet, amelyet az RMS ügyfél beolvashat és értelmezhet. Az RMS ügyfél megvizsgálja a tartalom tanúsítványláncát, és szükség szerint áttekinti a tartalom visszavonási listáját annak ellenőrzésére, hogy teljesül-e a tartalom érvényességére vonatkozó összes feltétel. Ezt követően az RMS ügyfél betartatja a közzétételi licencben a felhasználóra megadott használati jogokat és feltételeket. Ha az összes jog megfelelő és az összes feltétel teljesül, az RMS-kompatibilis alkalmazás az RMS kiszolgálótól kapott tartalomkulcs segítségével visszafejti a tartalmat. A használati jogok és feltételek maradandóan rögzítve vannak, így bárhova kerüljön is a tartalom, betartathatók.
-   RMS-védelemmel ellátott tartalom létrehozásáról a további tudnivalókat lásd a dokumentumgyűjtemény „RMS műszaki források” részében az „RMS-kompatibilis alkalmazások” témakörben.
-   A megbízható entitások RMS rendszeren belüli hierarchiájáról a további tudnivalókat lásd a dokumentumgyűjtemény „RMS műszaki források” részében a „Bizalmi hierarchia” témakörben.
-   RMS-védelemmel ellátott tartalom közzétételéről és használatáról a további tudnivalókat lásd a dokumentumgyűjtemény „RMS műszaki források” részében a „Közzététel” témakörben.
-   Az RMS-védelemmel ellátott tartalom közzétételének és használatának folyamatáról a további tudnivalókat lásd a dokumentumgyűjtemény „RMS műszaki források” részében a „Közzététel” témakörben.