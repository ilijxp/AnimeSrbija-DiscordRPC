# ASRPC (Anime Srbija Rich Presence) 🎌

**Podeli sa prijateljima na Discordu šta trenutno gledaš na Anime Srbija!**

## 📝 O projektu
ASRPC je lagana desktop aplikacija i prateća browser ekstenzija koja automatski povezuje tvoju aktivnost sa sajta Anime Srbija sa tvojim Discord profilom. Bilo da pretražuješ sajt, čitaš o novom naslovu ili uživaš u najnovijoj epizodi, tvoj Discord Rich Presence će to elegantno prikazati – uključujući i originalnu sliku animea!

## ✨ Glavne funkcionalnosti
* **Status u realnom vremenu:** Prikazuje tačno ime animea i broj epizode koju trenutno gledaš.
* **Dinamične slike:** Aplikacija "hvata" cover sliku animea sa sajta i prikazuje je na tvom Discord profilu.
* **Potpuna kontrola privatnosti:** Jednim klikom na prekidač možeš da pauziraš deljenje statusa kada god želiš.
* **Rad u pozadini (System Tray):** Aplikacija ne smeta na taskbaru; minimizuje se u donji desni ugao ekrana (Tray) i tiho radi svoj posao.
* **Auto-pokretanje:** Opcija da se program sam upali zajedno sa računarom, kako ne bi morao da misliš o tome.
* **Custom Client ID:** Mogućnost unošenja sopstvenog Discord Application ID-ja za naprednije korisnike.
* **Dark Mode Interfejs:** Prelep, moderan kontrolni panel dizajniran da se vizuelno uklopi u Discord estetiku.

## ⚙️ Kako funkcioniše?
Ovaj projekat se oslanja na dva dela koji rade u savršenoj harmoniji:
1. **ASRPC Ekstenzija (za pregledač):** Prati na kojoj si stranici na animesrbija.com (čita naslov i epizodu) i šalje te podatke na tvoj računar.
2. **ASRPC Desktop Aplikacija:** Hvata te podatke lokalno (preko lokalnog servera) i preko Discord RPC tehnologije ih prosleđuje na tvoj Discord nalog.

## 🚀 Instalacija

### 1. Instalacija Desktop Aplikacije
1. Preuzmi najnoviju verziju iz **Releases** taba na ovom repozitorijumu (fajl `ASRPC Setup 1.0.0.exe`).
2. Pokreni instalacioni fajl.
3. Nakon instalacije, aplikacija će se pokrenuti i smestiti u System Tray (dole desno kod sata). 
4. Desni klik na ikonicu -> **Otvori podešavanja** da prilagodiš opcije (Paljenje uz sistem, deljenje statusa, itd.).

### 2. Instalacija Browser Ekstenzije
1. Otvori svoj pregledač (Chrome, Brave, Edge...) i idi na stranicu za ekstenzije (npr. `chrome://extensions/`).
2. Uključi **Developer mode** (uglavnom prekidač u gornjem desnom uglu).
3. Klikni na dugme **Load unpacked** (Učitaj raspakovano).
4. Pronađi i izaberi folder u kom se nalaze fajlovi ekstenzije (gde su ti `manifest.json`, `background.js` i `content.js`).
5. To je to! Otvori [Anime Srbija](https://animesrbija.com) i tvoj status će se automatski ažurirati na Discordu.

## 🛠️ Tehnologije
* **Electron** - Za desktop aplikaciju i korisnički interfejs
* **Node.js & Express** - Za lokalni server
* **Discord RPC** - Za komunikaciju sa Discord klijentom
* **JavaScript / HTML / CSS** - Za logiku ekstenzije i dizajn prozora

---
*Made by [@ilijxp](https://github.com/ilijxp)*
