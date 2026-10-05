# Silueta įrankiai

Skaičiuoklės, testai ir žaidimai apie apatinį trikotažą ir kompresines kojines.

Gyvai: https://vaityl2222.github.io/silueta-irankiai/

## Kas čia yra

| Failas | Kas tai |
|---|---|
| `index.html` | Pagrindinis puslapis su įrankių sąrašu |
| `irankiai/liemeneles-dydis.html` | Liemenėlės dydžio skaičiuoklė |
| `stilius.css` | Bendros spalvos ir šriftai |
| `3d/verta-pasitikrinti.html` | 3D antraštė |
| `vizualai/` | Logotipai |

Viskas veikia naršyklėje. Jokių bibliotekų, jokio diegimo, jokių duomenų
nerenkama ir nesaugoma.

## Liemenėlės dydžio skaičiuoklė

Metodika paimta iš straipsnio
[Kaip išsirinkti liemenėlės dydį?](https://www.silueta.lt/kaip-issirinkti-liemeneles-dydi)

Juostos dydis: apimtis po krūtine apvalinama iki artimiausio penketo.
Kaušelis: krūtinės apimtis minus tikra išmatuota apimtis po krūtine.
Riba tarp dviejų kaušelių priskiriama didesniajam (17,5 cm -> D, 19,5 cm -> E).

Rezultatas yra orientacinis dydis, nuo kurio verta pradėti matavimąsi, o ne
galutinis atsakymas.

## Kaip paleisti pas save

    python -m http.server 8777

Tada http://localhost:8777

## Pastaba dėl dydžių sąrašo

Skaičiuoklės gale esantis `FILTRAS` sąrašas sieja dydį su silueta.lt filtro ID.
Jis surinktas 2026-10-05. Atsiradus naujam dydžiui kataloge, sąrašą reikia
atnaujinti, kitaip to dydžio mygtukas nebus rodomas.
