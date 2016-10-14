<h1>Dokumentáció</h1>

<h2>Látványosságok</h2>
<p>Készítette: Madák Ildikó </p>

<b>1. Követelményanalízis</b>
<p> Az alkalmazás célja megjeleníteni a felhasználók által beküldött látványosságok adatait.  
Az adatok védelme érdekében lehetőség van regisztrációra, majd bejelentkezésre. 
Bejelentkezett felhasználó új helyszíneket adhat hozzá a már meglévőkhöz, lehetősége van értékelni a mások által beküldött helyszíneket, 
valamint az önmaga által beküldötteket módosítani, törölni.
Az adminisztrátornak lehetősége van bármely beküldött helyszínt módosítani, vagy akár törölni.</p>
<p><i> Funkcionális követelmények </i></p>
<ul>
<li>Vendégek által elérhető funkciók
<ul>
<li>Regisztráció </li>
<li>Bejelentkezés</li>
<li>A főoldalon megtekinteni a legjobb értékelésű nevezetességeket</li>
<li>Látványosságok között szűrni név, elhelyezkedés alapján</li>
</ul>
</li>
<li>Bejelentkezett felhasználók által elérhető funkciók
<ul>
<li>Új látványosság hozzáadása</li>
<li>Látványosságok értékelése</li>
<li>Saját látványosság adatainak módosítása</li>
<li>Saját látványosság törlése</li>
</ul>
</li>
<li>Admin felhasználó által elérhető funkciók
<ul>
<li>Bármely látványosságok törlése</li>
<li>Bármely látványosság adatainak módosítása</li>
<li>Új látványosság hozzáadása</li>
</ul>
</li>
</ul>
<p><i>Nem funkcionális követelmények </i></p>
<ul>
<li>Könnyű áttekinthetőség: színek használata a keresés megkönnyítéséhez, ésszerű elrendezés, hibásan bevitt adatok esetén a hiba egyértelmű jelzése</li>
<li>Megbízhatóság: jelszóval védett funkciók</li>
</ul>

<p><i>Szakterületi fogalomjegyzék </i><p>
<ul>
<li><b>Nehézség:</b> túrák osztályozása fizikai szükséglet szerint. <br>
Például egy hegyvidéki kilátó több ponttal rendelkezik mint egy kis túraútvonal a völgyben</li>
<li><b>Jelleg:</b> a nevezetesség csoportosítása célcsoport, tematika szerint  <br>
Például megkülönböztet tanösvényeket, múzeumokat, szabadidős programokat</li>
</ul>


<p><i>Használatieset-modell, funkcionális követelmények</i></p>
<p><b>Vendég</b>: Csak a publikus oldalakt éri el: főoldal, bejelentkezés, regisztráció <br>
<b>Bejelentkezett felhasználó</b>: A publikos oldalak elérésén kívül egyéb funkciókhoz is hozzájuz: új nevezetesség felvétele, meglévő nevezetesség törlése/módosítása/értékelése<br>
<b>Bejelentkezett adminisztrátor</b>: Bármelyik nevezetességet módosíthatja, törölheti vagy új látványosságokat vehet fel. </p>

<img src="./images/usecase.png">
