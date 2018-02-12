
simple-footer-oz

Egy egyszerû "ragadós" footer.
Mindig az adott oldal adott tartalma után jelenik meg.

Az oldal tartalma nem gördül be alá, tehát, ha a viewport higth értéke kisebb,
mint a tartalom magassága, akkor csak lefelé görgetéskor jelenik csak meg.


Techika:
- A footer-t átalakítjuk táblázattá, hogy a benne lévõ tartalmat vertikálisan közpre rendezhessük
- szélessége: 100vw - mindig kitölti a képernyõt
- magassága: rem-ben van megadva, így reszponzív
- a tartalmi részr (wrapper) csak azért kell, hogy a footer-nek, mint táblázatnak a cellájaként
  a benne található tartalom vertikálisan (függõlegesen) középre rendezett legyen
- a kód többi része már csak formázás és szín
- a "strong" (kiemelés) beállítása azért kell, mert a CSS resettel ezt korábban "kilõttük",
  így nem lenne kiemelt a szövegrész