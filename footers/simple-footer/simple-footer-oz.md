
simple-footer-oz

Egy egyszer� "ragad�s" footer.
Mindig az adott oldal adott tartalma ut�n jelenik meg.

Az oldal tartalma nem g�rd�l be al�, teh�t, ha a viewport higth �rt�ke kisebb,
mint a tartalom magass�ga, akkor csak lefel� g�rget�skor jelenik csak meg.


Techika:
- A footer-t �talak�tjuk t�bl�zatt�, hogy a benne l�v� tartalmat vertik�lisan k�zpre rendezhess�k
- sz�less�ge: 100vw - mindig kit�lti a k�perny�t
- magass�ga: rem-ben van megadva, �gy reszponz�v
- a tartalmi r�szr (wrapper) csak az�rt kell, hogy a footer-nek, mint t�bl�zatnak a cell�jak�nt
  a benne tal�lhat� tartalom vertik�lisan (f�gg�legesen) k�z�pre rendezett legyen
- a k�d t�bbi r�sze m�r csak form�z�s �s sz�n
- a "strong" (kiemel�s) be�ll�t�sa az�rt kell, mert a CSS resettel ezt kor�bban "kil�tt�k",
  �gy nem lenne kiemelt a sz�vegr�sz