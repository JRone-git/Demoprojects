# Muistiinpanosovellus

Muistiinpanosovellus on Pythonilla toteutettu graafinen sovellus, jolla voit hallita muistiinpanojasi helposti. Ohjelma tukee muistiinpanojen lisäämistä, poistamista, ja hälytysten asettamista muistiinpanoille. Lisäksi voit lisätä muistiinpanoja puheentunnistuksen avulla.

---

## Ominaisuudet
- **Muistiinpanojen hallinta**: Lisää ja poista muistiinpanoja SQLite-tietokantaan tallennettuna.
- **Hälytystoiminto**: Aseta hälytys muistiinpanoille valitsemalla päivämäärä ja kellonaika.
- **Puheentunnistus**: Lisää muistiinpanoja puhumalla (tukee suomen kieltä).
- **Moderni käyttöliittymä**: Käyttää `ttkbootstrap`-kirjastoa moderniin ja responsiiviseen ulkoasuun.
- **Tietokannan hallinta**: Automaattinen tietokannan luonti ja hallinta.

---

## Asennus

### 1. Riippuvuudet
Varmista, että sinulla on Python 3.9 tai uudempi asennettuna. Asenna tarvittavat kirjastot seuraavalla komennolla:


pip install sqlite3 ttkbootstrap SpeechRecognition tkcalendar


### 2. Käyttöönotto
1. Lataa ohjelman lähdekoodi tai kloonaa tämä repositorio:
   
   git clone <REPOSITORIO_URL>
   cd Muistiinpanosovellus
   

2. Suorita ohjelma:
   
   python app.py
 

---

## Käyttöohjeet

### Käyttöliittymän osat
1. **Muistiinpanojen syöttökenttä**: Kirjoita muistiinpanosi ja lisää se painamalla "Lisää"-painiketta.
2. **Muistiinpanolista**: Näyttää kaikki muistiinpanot ja mahdolliset hälytysajat.
3. **Hälytysten asettaminen**: Kun lisäät muistiinpanon, saat mahdollisuuden asettaa hälytyksen päivämäärän ja kellonajan.
4. **Puheentunnistus**: Pidä "Kuuntele"-painike painettuna ja puhu. Puheesi lisätään muistiinpanoksi.

---

## Kehittäminen
Ohjelma on suunniteltu helposti laajennettavaksi. Voit esimerkiksi lisätä uusia ominaisuuksia, kuten:
- Hälytysten muistutukset (ponnahdusikkunat tai äänihälytykset).
- Muistiinpanojen hakutoiminto.
- Synkronointi pilvipalveluiden kanssa.

---

## Teknologiat ja kirjastot
- **Python 3**: Pääohjelmointikieli.
- **Tkinter**: Graafinen käyttöliittymä.
- **SQLite**: Tietokannan hallintaan.
- **SpeechRecognition**: Puheentunnistukseen.
- **ttkbootstrap**: Moderni ulkoasuteema.
- **tkcalendar**: Päivämäärävalitsin.

---

## Tunnetut rajoitukset
- Hälytysten muistutus toimii vain, kun ohjelma on käynnissä.
- Puheentunnistuksen tarkkuus riippuu mikrofonin laadusta ja ympäristön melutasosta.

---

## Lisenssi
Tämä projekti on lisensoitu MIT-lisenssillä. Katso lisätietoja [LICENSE](LICENSE)-tiedostosta.

---

## Kehittäjät
- Jonne Riepponen - Pääkehittäjä

Ota yhteyttä ongelmissa tai ehdotuksissa!

``` 
