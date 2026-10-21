# 📊 FxPro Riport & Premium Analytics Dashboard

[![MQL5](https://shields.io)](https://mql5.com)
[![Python](https://shields.io)](https://python.org)
[![GitHub Pages](https://shields.io)](https://github.com)
[![License: MIT](https://shields.io)](https://opensource.org)

Egy professzionális, automatizált kereskedési és elemző rendszer, amely összeköti a **MetaTrader 5 (MQL5)** környezetet a modern **Python-alapú adatanalitikával**, valamint automatikus **GitHub Pages** riportálással rendelkezik.

---

## 🚀 Főbb Funkciók

*   **Automatizált Adatfeldolgozás:** MQL5 környezetből származó strukturált adatok automatikus szinkronizációja.
*   **Premium UI Dashboard:** Modern, reszponzív HTML/JS alapú riport felület (index.html).
*   **Git & GitHub Pages Automatizáció:** Egykattintásos vagy teljesen automatizált távoli szinkronizáció biztonságos token-kezeléssel.
*   **Moduláris Architektúra:** Könnyen bővíthető, szeparált logikai rétegek az indikátorok, adatok és a megjelenítés számára.

---

## 📂 Projekt Struktúra

```text
modularis_struktura/
│
├── github_sync.py          # GitHub szinkronizációért és push-ért felelős Python szkript
└── githubkod.txt           # GitHub Personal Access Token (biztonságosan kezelve)

fxpro-riport/ (Git Repository & GitHub Pages)
│
├── index.html              # A prémium UI riport és dashboard főoldala
└── README.md               # [Ez a fájl] A generált, professzionális projektleírás
```

---

## 🛠️ Telepítés és Beállítás

### 1. Előfeltételek
Győződj meg róla, hogy a Python 3.8+ és a Git telepítve van a rendszereden.

### 2. Környezet beállítása
A `github_sync.py` mellett található `githubkod.txt` fájlba helyezd el a GitHub Personal Access Tokenedet.

### 3. Szinkronizáció indítása
Futtasd a szinkronizációs szkriptet manuálisan a parancssorból, vagy hívd meg automatizálva:
```bash
python github_sync.py
```

---

## 💻 Technológiai Stakk

*   **Kereskedési Környezet:** MQL5 (MetaTrader 5 Terminal)
*   **Szkriptnyelv & Logika:** Python 3
*   **Verziókövetés & Hoszting:** Git, GitHub, GitHub Pages
*   **Frontend / UI:** Prémium HTML5, CSS3 (Tailwind/Bootstrap), modern JavaScript diagramok

---

## 🔒 Biztonság (Security)

A `githubkod.txt` fájl tartalmazza a GitHub eléréshez szükséges privát azonosítót. **Soha ne töltsd fel ezt a fájlt nyilvános repozitóriumba!** A token védelméről a helyi könyvtárszerkezet gondoskodik.

---

## 📜 Licenc

Ez a projekt az **MIT Licenc** alatt érhető el. Részletekért lásd a [LICENSE](LICENSE) fájlt.

---
*Utolsó automatikus frissítés: 2026-10-21*