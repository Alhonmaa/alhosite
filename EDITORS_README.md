---
layout: page
title: SIVUSTON MUOKKAUS
permalink: /EDITORS_README/
hero_image: /alhosite/assets/images/newalhonmaa.png
hero_height: is-fullwidth
hero_darken: true
---

# Jaa että miten tätä ajetaan?

Jos haluat muokata nettisivua, tee github käyttäjä ja pyydä Alhonmaa-käyttäjältä, että sinut lisätään muokkaajaksi. Sen jälkeen mene prose.io sivulle, valtuuta sivusto käyttämään Github-käyttäjäsi rajapintaa ja lisää alhonmaa uudeksi projektiksi Alhonmaa/alhosite.

Sivuja voi järjestellä kansioihin. Niitä on esimerkiksi "legislation", "geography" tai "culture". Sivuja voi myös olla suoraan yläkansiossa, esim. "index.md" eli etusivu ja "legislation.md".

Kaikki yläpalkin pääsivut on tarkoitus olla markdown-tiedostoina (.md) suoraan yläkansiossa. Muut sivut olisi hyvä pitää alakansioissa. Yläpalkkia voi muokata täällä tidostossa "/_data/navigation.yml".

Jokainen markdown-tiedosto pitää aloittaa seuraavalla pätkällä, niinkutsutulla "front-matter" osiolla:

    ---
    layout: page
    title: laita-tähän-otsikko
    permalink: /alakansio/tiedoston_nimi/
    hero_image: /alhosite/assets/images/newalhonmaa.png
    hero_height: is-fullwidth
    hero_darken: true
    ---

Permalink-kohtaan laitetaan markdown-tiedoston nimi ilman .md päätettä.

Esimerkki legislation.md tiedoston alusta:

    ---
    layout: page
    title: Lainsäädäntö ja politiikka
    permalink: /legislation/
    hero_image: /alhosite/assets/images/newalhonmaa.png
    hero_height: is-fullwidth
    hero_darken: true
    ---

Jos tiedosto olisi kansion example alla, niin permalink kohtaan tulisi /example/legislation/.

"legislation" kansioon menee kaikki lakijutut.
"geography" kansioon voi laiteilla rajoista ja maantieteestä jne.
"culture" kansioon mitä vaan alhonmaalaisen kulttuurin ylpeydenaiheita.