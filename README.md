# Linked events API, 6Aika

Linked events on avoimen lähdekoodin tapahtumatietokanta ja avoin tapahtumarajapinta. Se tarjoaa erilaisille sovelluksille tapahtumatiedot ja niiden paikkatiedot yhdenmukaisessa ja koneluettavassa muodossa.

Rajapinnan tietomallin suunnittelussa on käytetty schema.orgin sanastoa. Rajapinta palauttaa tiedot JSON-LD-muodossa. Paikkatiedot on Helsingissä linkitetty toimipisterekisteriin, jossa on tietoja muun muassa tapahtumapaikkojen esteellisyydestä.

Rajapinnasta voi tehdä hakuja päivämäärän, avainsanojen ja sijainnin perusteella. Aluehaun voi tehdä ns. bounding box -hakuna.

Tämä määritelmä kattaa 6Aika-kaupunkien yhteisen näkemyksen perustoiminnallisuuksista, joita tapahtumarajapintaan tarvitaan. Yhteisellä määritelmällä pyritään varmistamaan, että eri rajapintatoteutukset ovat yhteensopivat. Kukin rajapinnan toteuttaja voi kehittää omaan rajapintaansa lisätoiminnallisuuksia tarpeidensa mukaan, kunhan rajapinta pysyy yhteensopivana 6Aika-määritelmän kanssa.

Esimerkiksi Helsingin kaupungin [Linked Events -rajapinta](http://api.hel.fi/linkedevents/v1/) ([Github](https://github.com/City-of-Helsinki/linkedevents)) on yhteensopiva tämän määritelmän kanssa.

Määritelmän mukaisesti on tehty myös avoimen lähdekoodin referenssitoteutus. Tämän määritelmän mukainen 6Aika-referenssitoteutus on osoitteessa https://github.com/6aika/linkedevents.

6Aika-kaupungit kehittävät määritelmää jatkossakin yhdessä. Määritelmää koskevat kommentit ja kehitysehdotukset otetaan mielellään vastaan GitHubin issueina.

# Linked events API, 6Aika

Linked Events is an open source events database and an open API. The API provides categorized data on events and places in a harmonized and machine-readable format.

The data model uses schema.org vocabulary. The API provides the data in JSON-LD format. In Helsinki, the location information is linked to the City of Helsinki registry of service units which contains e.g. information about accessibility.

The API allows to search data by date, keywords and location. You can also search for an area by bounding box.

This is a specification of basic features needed in an event information API. 
The six largest cities in Finland created this specification with an aim to improve interoperability of event APIs across the globe. It is nevertheless possible for anyone interested in providing an event API to create features suitable for his/her own needs, as long as the API is interoperable with this specification.

Additionally, an open source reference API exists according to the 6Aika-definition. The API can be found via following link: https://github.com/6aika/linkedevents.

The Six Cities are committed to further develop this definition in cooperation of the cities. Comments and development ideas regarding the definition are welcome as GitHub issues.

## Lisätietoa / further information:

* [Linked events: tapahtumarajapinnan toiminnot ja käyttötarkoitus](https://www.databusiness.fi/fi/linked-events/)
* [Linked events: rajapinnan tekniset vaatimukset](https://www.databusiness.fi/fi/avoindata/avoimet-rajapinnat/linkedevents-teknisetvaatimukset/)
