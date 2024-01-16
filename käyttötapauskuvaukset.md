# Käyttötapauskuvaukset
**Sisäänkirjautuminen**
- Käyttötapauksen nimi: Sisäänkirjautuminen
- Käyttäjät: Käyttäjä
- Laukaisija: Käyttäjä aloittaa sovelluksen käytön
- Esiehto: Käyttäjä tietää kirjautumistunnuksen
- Jälkiehto: Käyttäjä pääsee käyttämään sovellusta
- Käyttötapauksen kulku:
1. Käyttäjä menee sovellukseen
2. Sovellus pyytää kirjautumaan sisään
3. Käyttäjä syöttää kirjautumistiedot
4. Kirjautuminen onnistuu ja käyttäjä pääsee sovellukseen / kirjautuminen epäonnistuu
- Poikkeuksellinen toiminta:
3a. Tapahtuu kirjautumisvirhe

**Äänestyksen ylläpito**
- Käyttötapauksen nimi: Äänestyksen ylläpito
- Käyttäjät: Ylläpitäjä
- Laukaisija: Ylläpitäjä aloittaa sovelluksen käytön
- Esiehto: Ylläpitäjällä on sovelluksen käyttöoikeudet
- Jälkiehto: Ylläpitäjä on voinut lisätä/poistaa äänestyksiä
- Käyttötapauksen kulku:
1. Ylläpitäjä menee sovellukseen
2. Ylläpitäjä valitsee joko äänestyksen lisäämisen tai poistamisen
- Poikkeuksellinen toiminta:
2a. Äänestyksen poistaminen tai lisääminen ei onnistu

**Äänestystulosten katsominen**
- Käyttötapauksen nimi: Äänestystulosten katsominen
- Käyttäjät: Käyttäjä
- Laukaisija: Käyttäjä aloittaa sovelluksen käytön
- Esiehto: Käyttäjä tietää kirjautumistunnuksen
- Jälkiehto: Käyttäjä pääsee käyttämään sovellusta
- Käyttötapauksen kulku:
1. Käyttäjä on sovelluksessa
2. Käyttäjä katselee sovelluksen etusivulla näkyviä äänestystuloksiaepäonnistuu
- Poikkeuksellinen toiminta:
2a. Ylläpitäjä poistaa juuri tarkkailtavaa äänestystä

**Äänestäminen**
- Käyttötapauksen nimi: Äänestäminen
- Käyttäjät: Käyttäjä
- Laukaisija: Käyttäjä aloittaa sovelluksen käytön
- Esiehto: Käyttäjä tietää kirjautumistunnuksen
- Jälkiehto: Käyttäjä pääsee käyttämään sovellusta
- Käyttötapauksen kulku:
1. Käyttäjä on sovelluksessa
2. Käyttäjä osallistuu äänestykseen äänestämällä
2a. Ylläpitäjä poistaa juuri äänestettävää äänestystä
