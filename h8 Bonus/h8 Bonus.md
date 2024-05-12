# h8 Bonus

Osiossa oli tarkoitus käydä läpi ne osiot, joihin olen tehnyt olennaisia parannuksia palautuksen jälkeen sekä luetella kaikki vapaaehtoiset bonustehtävät (Karvinen 2024)

- a)[ Parannus](#a-parannus)
- b)[ Bonus](#b-bonus)
- [Lähdeluettelo](#lähdeluettelo)

---

## a) Parannus
Jälkikäteen olen lisännyt ainoastaan tehtävässä H6 benchmark osiossa [a) Paketti windowsia](https://github.com/NicklasHH/Palvelinten-hallinta/blob/master/h6%20Benchmark/h6%20Benchmark.md#a-paketti-windowsia) korjauksen virheellisestä huomiosta. Alunperin ymmärsin lähteestä, että `pkg installes` funktio toimii ainoastaan minioniin ja `pkg.install` paikalliseen asennukseen. Tämä käsitys korjaantui tunnilla jonka johdosta lisäsin tekstin, että oikea komento olisi ollut `salt-call --local state.single pkg.installed winrar`. Lisätty osa löytyy a -osion lopusta ja osioon on kirjattu myös muokkauspäivämäärä.

Linkki osioon: https://github.com/NicklasHH/Palvelinten-hallinta/blob/master/h6%20Benchmark/h6%20Benchmark.md#a-paketti-windowsia 

---

## b) Bonus
Tein kurssin aikana kaikki vapaaehtoiset tehtävät ja tässä ne ovat listattuna suoralla linkillä:
##### H3
- [H3 tehtävä F. Se toinen järjestelmä](https://github.com/NicklasHH/Palvelinten-hallinta/blob/master/h3%20Toimiva%20versio/h3%20Toimiva%20versio.md#f-vapaaehtoinen-se-toinen-j%C3%A4rjestelm%C3%A4)
- [H3 tehtävä G. Yhteistyö](https://github.com/NicklasHH/Palvelinten-hallinta/blob/master/h3%20Toimiva%20versio/h3%20Toimiva%20versio.md#g-vapaaehtoinen-yhteisty%C3%B6t%C3%A4)

##### H4
- [H4 tehtävä E. Apache](https://github.com/NicklasHH/Palvelinten-hallinta/blob/master/h4%20Demoni/h4%20Demoni.md#e-vapaaehtoinen-apache)
- [H4 tehtävä F. Caddy](https://github.com/NicklasHH/Palvelinten-hallinta/blob/master/h4%20Demoni/h4%20Demoni.md#f-vapaaehtoinen-caddy)
- [H4 tehtävä G. Nginx](https://github.com/NicklasHH/Palvelinten-hallinta/blob/master/h4%20Demoni/h4%20Demoni.md#g-vapaaehtoinen-nginx)

##### H5
- [H5 tehtävä F. Gui2fs](https://github.com/NicklasHH/Palvelinten-hallinta/blob/master/h5%20Tekniikoita/h5%20Tekniikoita.md#f-vapaaehtoinen-gui2fs)
- [H5 tehtävä G. Ämpärillinen](https://github.com/NicklasHH/Palvelinten-hallinta/blob/master/h5%20Tekniikoita/h5%20Tekniikoita.md#g-vapaaehtoinen-%C3%A4mp%C3%A4rillinen)

---

## Lähdeluettelo

Karvinen, T. 2024. Infra as Code - Palvelinten hallinta 2024. Luettavissa: https://terokarvinen.com/2024/configuration-management-2024-spring/. Luettu: 10.5.2024.