# Linked events API, 6Aika

Linked events on avoimen lähdekoodin tapahtumatietokanta ja avoin tapahtumarajapinta. Se tarjoaa erilaisille sovelluksille tapahtumatiedot ja niiden paikkatiedot yhdenmukaisessa ja koneluettavassa muodossa.

Rajapinnan tietomallin suunnittelussa on käytetty schema.orgin sanastoa. Rajapinta palauttaa tiedot JSON-LD-muodossa. Paikkatiedot on Helsingissä linkitetty toimipisterekisteriin, jossa on tietoja muun muassa tapahtumapaikkojen esteellisyydestä.

Rajapinnasta voi tehdä hakuja päivämäärän, avainsanojen ja sijainnin perusteella. Aluehaun voi tehdä ns. bounding box -hakuna.

Tämä määritelmä kattaa 6Aika-kaupunkien yhteisen näkemyksen perusasioista, joita tapahtumarajapintaan tarvitaan. Yhteisellä määritelmällä pyritään varmistamaan, että eri rajapintatoteutukset ovat yhteensopivat. Kukin rajapinnan toteuttaja voi kehittää omaan rajapintaansa lisätoiminnallisuuksia tarpeidensa mukaan, kunhan rajapinta pysyy yhteensopivana 6Aika-määritelmän kanssa.

Esimerkiksi Helsingin kaupungin [Linked Events -rajapinta](http://api.hel.fi/linkedevents/v1/) ([Github](https://github.com/City-of-Helsinki/linkedevents)) on yhteensopiva tämän määritelmän kanssa.

Määritelmän mukaisesti on tehty myös avoimen lähdekoodin referenssitoteutuksia. Tämän määritelmän mukainen 6Aika-referenssitoteutus on osoitteessa https://github.com/6aika/linkedevents.

6Aika-kaupungit kehittävät määritelmää jatkossakin yhdessä. Määritelmää koskevat kommentit otetaan mielellään vastaan GitHubin issueina.

Linked Events is an open source events database and an open API. The API provides categorized data on events and places in a harmonized and machine-readable format.

The data model uses schema.org vocabulary. The API provides the data in JSON-LD format. In Helsinki, the location information is linked to the City of Helsinki registry of service units which contains e.g. information about accessibility.

In the API, you can search data by date, keywords and location. You can also search for an area by bounding box.



## Lisätietoa / further information:

* [Linked events: tapahtumarajapinnan toiminnot ja käyttötarkoitus](https://docs.google.com/document/d/1prnzkICV1x8GZqE9W90ILfRUN-Tc9pKQnpjI7weuoLU/edit)
* [Linked events: rajapinnan tekniset vaatimukset](https://docs.google.com/document/d/1aAgsrVrrDrp272etJStolCTEg2jxDsWAvqe1pApoyDk/edit)
