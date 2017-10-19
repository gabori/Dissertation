# Dissertation
Éttermi rendelésnyilvántartó rendszer
=====================================

Bevezetés
---------

* Le kell majd bennei írni, hogy milyen problémát old meg a dolgozat, és az elkészült alkalmazás.
* Itt kell majd meggyőzni az olvasót, hogy olvassa is végig a dolgozatot. :)
* Elég lesz majd csak a végén megírni.
* Maximum 2 oldal ide elegendő lesz.

Éttermi nyilvántartás
---------------------

Itt ki kell majd fejteni, hogy melyek azok a dolgok, amiket egy étteremnek nyilván kell tartania. Ebben a részben még nem kell belemenni a technikai részletekbe, hanem azt kell körüljárni, hogy mi a konkrét problémakör, annak mely részeire fog koncentrálni a dolgozat további része.

Elterjedt megoldások:

* Ebben a részben össze kell szedni, hogy milyen elérhető megoldások vannak az éttermek számára.
* Itt érdemes minél több elérhető megoldást összeszedni, és ha lehet diagramokat, összehasonlító táblázatokat is készíteni hozzá.
* A bemutatott megoldásokat majd mindenképpen be is kell hivatkozni.

Az alkalmazás felépítése
------------------------

Először az alkalmazás felépítését csak nagyvonalakban, funkcionális egységenként kell részletezni. Kvázi a tipikus kliens-szerver-es architektúrát kell személyre szabni kicsit.

Ebbe a részbe következik majd aztán a felhasznált technológiák bemutatása. Itt annak kell érződnie, hogy minden eszköz a problémának megfelelően lett megválasztva.

Már itt célszerű azt is láthatóvá tenni, hogy hol érnek véget a library-k és keretrendszerek, és mi az ami saját készítésű. Nem tudni, hogy milyen szinten lesz otthon ezekben az, aki olvassa, ezért jól láthatóvá kell tenni, hogy melyik komponens/kódrész mit csinál, és hogy saját készítésű, vagy készen felhasznált.

A rendelések adatainak nyilvántartása
-------------------------------------

Itt magáról az adatmodellről van szó gyakorlatilag. Itt érdemes kifejteni, hogy milyen adat, és hol kerül majd tárolásra. Az ER jellegű diagram, illetve az SQLAlchemy-s modellek egyszerűsített változata kellene majd ide.

A felhasználói felület
----------------------

Itt kellene majd bemutatni, hogy a felhasználói felület egyáltalán milyen részekből áll, azokat hogy lehet elérni és használni.

Attól függően, hogy a funkciók inkább kliens vagy szerver oldalon lesznek majd, itt lehet részletezni az összes, felhasználói felülettel kapcsolatos tudnivalót, de az is jó megoldás, ha minden funkciónál külön kerül bemutatásra.

Alapfunkciók bemutatása
-----------------------

Ez nem feltétlen jó így fejezet címnek, pontosabban ezen a témán belül több fejezet is lehet, attól függően, hogy majd mivel és hogy sikerül elkészülni.

Itt kb. olyasmire kell gondolni, mint
- rendelések nyilvántartása,
- promóciók, törzsvásárlói kedvezmények megvalósítása a rendszerben,
- nyersanyagok nyilvántartása,
- rendelési statisztikák, elemzés, megjelenítés,
- ...

Annyi biztos, hogy a címnek megfelelően a rendeléseket majd nyilván kell tartani. A többi ahhoz kapcsolható funkció, de csak akkor célszerű vele foglalkozni, ha az alapfunkciók már megvannak.

A tervezéséről szóló dolgokat az alkalmazás felépítésénél is el lehet kezdeni, de ott még inkább csak az interfészekre, az API jellegére, konvenciókra, illesztési módokra vonatkozóan.

Magában az implementációba annyira kell csak majd belemenni az alapfunkciók bemutatásánál, hogy a kiemelt kódpéldák alapján át lehessen tekinteni a rendszer egészét, és a leírás alapján aki akarja hellyel-közzel tuda is reprodukálni a rendszert.

Tesztelés
---------

Itt is jobb lehet majd egy beszédesebb fejezetcím, de mindenképpen kell egy külön rész a tesztelésnek. Ebben olyan jellegű tesztekről van már szó, hogy mennyi- és milyen adattal sikerült kipróbálni. Lehetnek profilozással/válaszidőkkel kapcsolatos dolgok, becslések az adatbázis méretére vonatkozóan a későbbiekben.

A tesztelésre majd még egyébként az implementációs (Alapfunkciók bemutatása) során is érdemes kitérni, értve ez alatt az egységteszteket.

Ide igazán az lenne szép, ha már valamilyen valósághoz közeli adatokkal és felhasználási móddal ki lehetne majd próbálni, de ha van egy részletes belső teszt, akkor már az is nagyon jó.

Összegzés
---------

* A Bevezetéshez hasonlóan ezt is a végére lehet majd hagyni.
* Itt szépen, lekerekítve össze kell foglalni, hogy mit tartalmaz a dolgozat.
* Szót lehet benne majd ejteni a későbbi fejlesztési lehetőségekről. (Amennyiben több ötlet maradna a végére,az is kerülhet még közvetlenül ez elé egy külön fejezetbe is.)

Irodalomjegyzék
---------------

* webfejlesztéssel kapcsolatos irodalmak
* a javaslattételekhez, elemzésekhez használt algoritmusokhoz kötődő irodalmak
* kvázi konkurrens rendszerekre való hivatkozások

