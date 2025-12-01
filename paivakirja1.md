# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

## Mitä opin?
- Opin käyttämään Git-versionhallintaa perusmuodossaan. Opin esimerkiksi, miten tiedostoja lisätään 'git add' -komennolla ja miten talletuksia tehdään 'git commit' -komennolla.
- Ymmärsin myös mitä eri haarat tarkoittavat, miksi niitä käytetään ja miten niitä voi yhdistää.
### Lisäksi opin:
- Kuinka voin lisätä ja poistaa tiedostoja komentokehotteessa
- Miten voin nähdä gitin tilan ja commit-historian (git status ja git log komennot)
- Miten voin perua virheitä git restore ja git revert komennoilla
## Mikä oli vaikeaa?
- Minulle oli vaikeaa keksiä, mitä tehdä tilanteessa jossa tapahtui jokin konflikti. Välillä en ymmärtänyt missä hakemistossa olin, joka aiheutti välillä sekaannusta ja johti virheilmoituksiin.
## Mikä oli helppoa?
- Koin helposti peruskomentojen käytön, kuten add, commit ja status. Ne olivat aika yksiselitteisiä ja kun ymmärsin mitä ne tekevät, tuntui niiden käyttö loogiselta
- Komentokehotteen käyttö oli myös aika yksinkertaista. Kaipaisin toki visuaalisempaa tapaa, mutta se ajoi asiansa.
## Mikä auttoi minua oppimaan?
- Jos tuli ongelmia jotka ei selvinneet oppimateriaalista, pyysin tekoälyä selittämään ne minulle yksinkertaisesti, sekä etsin googlesta vastauksia ja taas pystyin jatkamaan tehtäviä eteenpäin
- Opin tekemistäni virheistä ja niiden selvittelemisestä paljon
- Pyrin ymmärtä,ään, mistä jokin virheilmoitus kertoo joko googlen, chat gpt:n tai oppimateriaalin avulla
- Komentojen testaaminen

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git log | näyttää commit-historian |
| git status | kertoo nykytilanteen |
| dir | tarkistaa, mitä tiedostoja on kansiossa |
| git add | lisää tiedoston Git-hallintaan|
| git commit | tekee talletuksen |
| git commit –m | tekee tallennuksen ilman editorin avaamista |
| git rm | poistaa tiedoston kansiosta ja versionhallinnasta |
| git restore . | palauttaa kaikki kaikki muokatut tiedostot viimeisimpään committiin |
| git revert head | kumoaa edellisen commitin |