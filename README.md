# Tampereen Tapahtumat ja Säätiedot

Yksinkertainen verkkosivusto, joka tarjoaa ajankohtaisia tietoja Tampereen tapahtumista ja säätiedoista. Tehtävä sisältää kolme HTML-sivua, jotka käyttävät julkisia rajapintoja tietojen hakemiseen ja näyttämiseen.

## Tehtävän Sisältö

### Sivut

- **index.html**: Aloitussivu, jossa on yleiskuvaus. Sisältää linkit muille sivuille, jotka esittelevät säätiedot ja tapahtumat.
- **saa.html**: Sivusto, joka näyttää ajantasaiset säätiedot Tampereelta ja Helsingistä. Säätiedot haetaan [OpenWeatherMap](https://openweathermap.org/) API:n kautta.
- **tapahtumat.html**: Sivusto, joka listaa Tampereen ajankohtaiset tapahtumat. Tapahtumatiedot haetaan Tampereen avoimen datan [VisitTampere API](https://api.visittampere.com/api/v1/) kautta.

### Navigointi

Jokaisella sivulla on navigointinapit, jotka mahdollistavat helpon siirtymisen sivujen välillä:

- **Takaisin pääsivulle**: Nappi, joka ohjaa käyttäjän `index.html`-sivulle.
- **Katso säätiedot**: Nappi, joka ohjaa käyttäjän `saa.html`-sivulle.
- **Katso tapahtumat**: Nappi, joka ohjaa käyttäjän `tapahtumat.html`-sivulle.

### Käytetyt Teknologiat

- **HTML**: Rakenteen ja sisällön esittämiseen.
- **CSS**: Sivujen tyylittelyyn ja ulkoasun hallintaan.
- **JavaScript**: Rajapintakutsujen tekemiseen ja datan käsittelyyn.
- **OpenWeatherMap API**: Säätietojen hakemiseen.
- **VisitTampere API**: Tampereen tapahtumatietojen hakemiseen.

## Käyttö

1. Avaa `index.html` selaimessa aloittaaksesi.
2. Navigoi sivuston eri osioihin käyttämällä aloitussivun nappeja.

### Huomioitavaa

- **Säätiedot**: Tarvitset API-avaimen OpenWeatherMap-palvelusta säätietojen hakemiseen. Voit käyttää opettajan API-avainta tai rekisteröityä [OpenWeatherMap](https://openweathermap.org/) palveluun saadaksesi oman avaimen.
- **API-rajapinnat**: Käytä rajapintojen tarjoamia URL-osoitteita ja varmista, että JSON-dataa haetaan oikeasta osoitteesta.
