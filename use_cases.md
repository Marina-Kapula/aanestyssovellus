# Käyttötapauskuvaukset – Äänestyssovellus

---

## 1. Selaa äänestyksiä

**Käyttäjät:** Käyttäjä  
**Laukaisija:** Käyttäjä avaa sovelluksen  
**Esiehto:** Käyttäjä on sovelluksen etusivulla  
**Jälkiehto:** Käyttäjä näkee listan äänestyksistä  
**Kulku:**
1. Käyttäjä avaa sovelluksen
2. Sovellus näyttää listan olemassa olevista äänestyksistä

**Poikkeus:** Jos äänestyksiä ei ole, näytetään viesti "Ei äänestyksiä saatavilla"

---

## 2. Näytä äänestystilanne

**Käyttäjät:** Käyttäjä  
**Laukaisija:** Käyttäjä valitsee äänestyksen katsottavaksi  
**Esiehto:** Äänestys on valittuna  
**Jälkiehto:** Äänestystilanne näytetään  
**Kulku:**
1. Käyttäjä valitsee äänestyksen
2. Sovellus näyttää vaihtoehdot ja prosentit tai äänimäärät

---

## 3. Äänestä

**Käyttäjät:** Käyttäjä  
**Laukaisija:** Käyttäjä valitsee vaihtoehdon ja painaa "Äänestä"  
**Esiehto:** Käyttäjä ei ole jo äänestänyt  
**Jälkiehto:** Ääni tallennetaan, tilanne päivittyy  
**Kulku:**
1. Käyttäjä valitsee vaihtoehdon
2. Käyttäjä painaa "Äänestä"
3. Sovellus tallentaa äänen ja päivittää tilanteen

**Poikkeus:** Jos käyttäjä on jo äänestänyt → näytetään viesti "Olet jo äänestänyt"

---

## 4. Luo uusi äänestys

**Käyttäjät:** Ylläpitäjä  
**Laukaisija:** Ylläpitäjä painaa "Uusi äänestys"  
**Esiehto:** Ylläpitäjä on kirjautunut  
**Jälkiehto:** Uusi äänestys näkyy listassa  
**Kulku:**
1. Ylläpitäjä kirjoittaa otsikon ja vaihtoehdot
2. Paina "Tallenna"
3. Äänestys lisätään tietokantaan

**Poikkeus:** Jos kentät puuttuvat → näytetään virheviesti

---

## 5. Poista äänestys

**Käyttäjät:** Ylläpitäjä  
**Laukaisija:** Ylläpitäjä painaa "Poista"  
**Esiehto:** Äänestys on valittuna  
**Jälkiehto:** Äänestys poistuu listasta  
**Kulku:**
1. Ylläpitäjä valitsee poistettavan äänestyksen
2. Sovellus kysyy varmistuksen
3. Jos "Kyllä", äänestys poistetaan

