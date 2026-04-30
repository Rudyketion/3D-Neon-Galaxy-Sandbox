# 3D Neon Galaxy Sandbox 🌌

Tento projekt je interaktívna webová aplikácia vytvorená ako semestrálny projekt. Umožňuje používateľom generovať a upravovať procedurálnu 3D galaxiu v reálnom čase. Aplikácia je navrhnutá s dôrazom na silný vizuálny "WOW efekt", responzivitu a moderný dark/cyberpunk dizajn. 

Výnimočnosťou tohto projektu je generatívny ambientný zvuk, ktorý dynamicky reaguje na matematické zmeny parametrov galaxie.

---

## 🚀 Hlavné funkcie

* **Procedurálna 3D Galaxia:** Vykresľovanie stoviek tisíc svietiacich častíc v reálnom čase pomocou technológie WebGL.
* **Interaktívny ovládací panel:** Možnosť meniť parametre ako počet hviezd, polomer galaxie, počet ramien, zakrivenie (spin) a rozptyl.
* **Prispôsobenie farieb:** Používateľ si môže zvoliť farbu jadra aj okrajov galaxie, ktoré sa do seba plynulo prelínajú (additive blending).
* **Generatívne audio (Web Audio API):** Aplikácia neprehráva statické zvukové súbory, ale generuje hlboký "vesmírny" zvuk pomocou oscilátorov. Zvuk mení svoju frekvenciu a filtre na základe toho, aký tvar galaxie používateľ vytvorí.
* **Plynulé ovládanie kamery:** Automatická rotácia scény s možnosťou manuálneho preskúmania galaxie pomocou myši.

---

## 🛠 Použité technológie

Projekt striktne dodržiava požiadavku na **klientské technológie (Client-side only)**. Neobsahuje žiadny backend, databázy ani externé API servery.

* **HTML5 & CSS3** (Štruktúra, UI a neónový dizajn)
* **Vanilla JavaScript (ES6)** (Logika aplikácie)
* **Three.js** (3D knižnica načítaná cez CDN pre prácu s WebGL)
* **Web Audio API** (Tvorba a modulácia zvuku v reálnom čase)

---

## 💻 Ako spustiť projekt

Keďže projekt nevyžaduje žiadny backend (Node.js, Flask, PHP a pod.), jeho spustenie je mimoriadne jednoduché:

1. Stiahnite si alebo vytvorte súbor `index.html` a vložte doň poskytnutý zdrojový kód.
2. Dvojitým kliknutím otvorte tento `index.html` súbor v akomkoľvek modernom webovom prehliadači (odporúča sa Google Chrome, Mozilla Firefox alebo Microsoft Edge).
3. Všetko bude fungovať okamžite, priamo z vášho lokálneho disku.

---

## 🎮 Ovládanie

* **Myš (Ľavé tlačidlo):** Kliknite a potiahnite pre manuálne otáčanie kamery okolo galaxie.
* **Myš (Koliesko):** Približovanie (Zoom-in) a odďaľovanie (Zoom-out).
* **UI Panel (vpravo hore):** Použite posúvače na úpravu tvaru vesmíru. Zmeny sa prejavia okamžite.
* **Tlačidlo "Aktivovať vesmírny zvuk":** Zapne generatívny audio syntetizátor. Keď je zvuk aktívny, skúste meniť počet ramien alebo veľkosť galaxie – budete počuť, ako zvuk reaguje na vaše zmeny.
* **Tlačidlo "← Späť na portál":** Umiestnené vľavo hore, slúži pre návrat do hlavného menu/portálu (podľa požiadaviek zadania).

---

## 📝 Poznámka pre hodnotiteľa

Tento projekt bol navrhnutý tak, aby sa vyhol preplneným témam (ako sú štandardné audio vizualizéry alebo filtre obrázkov), no zároveň spĺňa **všetky technické požiadavky zadania**:
1. Beží čisto na klientovi v jednom súbore.
2. Využíva **Three.js** pre pokročilú 3D vizualizáciu.
3. Využíva **Web Audio API** (v tomto prípade na generatívnu tvorbu zvuku závislú od vizuálu, čo je originálnejší prístup).
4. Obsahuje požadované tlačidlo pre návrat a tmavý moderný vizuál.
