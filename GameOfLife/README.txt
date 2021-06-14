https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life

Game of Life-on alapuló C# "szimuláció", lehetőség random nyulak generálására vagy file-ból való beolvasásra.
Random generálás esetén a mezőnek egy értéket kell megadni(pl. 25 -> 25x25 a mező nagysága), minimum 200 üres mezőnek lennie kell hogy ne haljanak ki egyből a nyulak
(pl. 300 random nyúl esetén 23 vagy 25ös mezővel működik rendesen)


Insert megnyomására megadható hány ciklust szeretne a felhasználó lefuttatni (ahol üres mező van,ha körülötte pontosan 3 mező van akkor születik egy új nyúl, ha egy nyúl körül
2-3 nyúl van akkor túléli, ha annál több akkor túlnépesedés miatt kihal).

Delete megnyomására lementhető az adott mező állapota fileba, kérni fog egy számot amit "allapot"+*szám*.txt szerűen fog lementeni, később ez a file beolvasható.

Home megnyomására visszaugrik a random és file beolvasás menüpontba.

Fileból való beolvasás esetén a file legelső sora tartalmazza a mező méretet,és minden utána lévő sor maga a mező ahol: x = nyúl, " " = üres mező.
Ajánlott egy ilyen filet random generálva elkezdeni, lefuttatni 10-20-30 lépést, lementeni, és utána akármikor beolvashatóvá válik.
