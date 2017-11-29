# Prva domaća zadaća
## Pravila i upute

Napisati Jupyter bilježnicu u Pythonu o jednoj ili više matematičkih (u širem smislu) tema, koja treba sadržavati:

1. barem tri Python funkcije ili klase koje ste sami napisali,
1. barem 99 linija Python koda (prazni retci i retci s komentarima se ne računaju),
1. barem šest slika, animacija ili interaktivnih widgeta kreiranih u bilježnici (ubacivanje gotovih slika/klipova se ne računa),
1. barem četiri objekta, metode ili funkcije iz paketa Numpy, Scipy, Matplotlib ili Sympy koji nisu korišteni na predavanjima,
1. barem tri objekta, metode ili funkcije iz paketa Pandas, Basemap, Cython, Numba (koji nisu korišteni na predavanjima), ili paketa koji nisu obrađeni na predavanjima.

Za specifične teme (samo u dogovoru sa mnom) ne morate se držati pravila 4.
Alternativno, možete napisati bilježnicu koristeći Juliu. Tada je jedini uvjet da bilježnica sadržava barem 99 linija Julia koda (prazni retci i retci s komentarima se ne računaju).

Bilježnica treba biti napisana tako da je se može čitati kao smisleno štivo. Za matematičke formule koristiti $\LaTeX$.

### Instalacija dodatnih paketa
Popis python paketa možete naći [ovdje](https://pypi.python.org/pypi), trenutno ima [894 matematičkih paketa](https://pypi.python.org/pypi?:action=browse&c=396) no paket i ne mora biti na tom popisu da bi ga koristili. Ako paket koji bi željeli koristiti već nije instaliran na Sagemath oblaku, vrlo vjerojatno (uglavnom svi osim nekih paketa koji imaju jako puno zavisnosti) se može instalirati na Sagemath oblaku ako u terminalu izvršite sljedeće naredbe
````
anaconda3
easy_install --user ime_paketa
```
Prije nego počnete koristiti novi paket u Jupyter bilježnici, trebate ponovo pokrenuti jezgru `Python 3 (Anaconda)`.