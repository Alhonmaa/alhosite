# Jaa että miten tätä ajetaan?

Sivuja voi järjestellä kansioihin. Niitä on esimerkiksi "legislation", "geography" tai "culture". Sivuja voi myös olla suoraan yläkansiossa, esim. "index.md" eli etusivu ja "legislation.md".

Kaikki yläpalkin pääsivut on tarkoitus olla markdown-tiedostoina (.md) suoraan yläkansiossa. Muut sivut olisi hyvä pitää alakansioissa. Yläpalkkia voi muokata täällä tidostossa "/_data/navigation.yml".

Jokainen markdown-tiedosto pitää aloittaa seuraavalla pätkällä, niinkutsutulla "front-matter" osiolla:

    ---
    layout: page
    title: laita-tähän-otsikko
    permalink: /alakansio/tiedoston_nimi/
    hero_image: /assets/images/newalhonmaa.png
    hero_height: is-fullwidth
    hero_darken: true
    ---

Permalink-kohtaan laitetaan markdown-tiedoston nimi ilman .md päätettä.

"legislation" kansioon menee kaikki lakijutut.
"geography" kansioon voi laiteilla rajoista ja maantieteestä jne.
"culture" kansioon mitä vaan alhonmaalaisen kulttuurin ylpeydenaiheita.