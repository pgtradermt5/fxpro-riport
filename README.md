# fxpro-riport

\# 📊 FXPro Master Compact - Automatizált Kereskedési Riportrendszer



Ez a projekt egy \*\*egyedi készítésű, automatizált pénzügyi elemző- és riportáló rendszer\*\*, amely a MetaTrader 5 (MT5) tőzsdei terminálból származó adatokat dolgozza fel, rendszerezi, majd egy teljesen automatizált folyamat végén közzéteszi egy online, bárhonnan elérhető weboldalon.



\## 🌐 Élő Weboldalak Elérése

A rendszer által generált, sötét módú (Dark Mode), interaktív grafikonos riportok az alábbi linkeken érhetőek el:

\*   👉 \[Fő Piaci Riport (index.html)](https://github.io)

\*   👉 \[Teljes Piaci Jelentés (fxpro\_teljes\_piaci\_riport.html)](https://github.iofxpro\_teljes\_piaci\_riport.html)

\## 🚀 Főbb Funkciók és Tudás

\*   \*\*254 Pénzügyi Termék Követése:\*\* A rendszer hatalmas mennyiségű devizapárt, kriptovalutát és egyéb instrumentumot képes egyidejűleg kezelni.

\*   \*\*Swap-alapú Rangsorolás:\*\* A Carry Trade (kamatvadász) stratégiáknak megfelelően a pozitív kamatú (Swap) termékeket automatikusan előre sorolja, azon belül pedig a legalacsonyabb költségű (Spread) szerint rendezi őket.

\*   \*\*Fejlett Grafikonok (Plotly):\*\* Minden termékhez automatikus D1 idősíkú gyertyadiagramot rajzol, kiegészítve egy precíz MACD indikátorral (fővonal és szignálvonal).

\*   \*\*Tranzakció és Jegyzet Követés:\*\* A grafikonok alatt vizuálisan megjeleníti az éppen futó (BUY/SELL) pozíciókat, a lezárt múltbeli trade-eket, valamint a webes felületen hozzáadott egyedi jegyzeteket.

\*   \*\*Dupla Jogi Védelem:\*\* A riportok tetején és alján is hivatalos, sötétvörös szegélyű Kockázati Figyelmeztetés és Felelősségkizárás található.



\## 📁 A Projekt Architektúrája

A rendszer moduláris felépítésű, az alábbi komponensekből áll:

1\.  `data\_manager.py` – Az adatfeldolgozó motor. Beolvassa és szűri az MT5 CSV táblázatait.

2\.  `riport\_generalo1.py` – A HTML és grafikon gyártó. Elvégzi az elemzést és a Git alapú GitHub feltöltést.

3\.  `riport\_generalo\_idozito.py` – Az automata robotpilóta. Biztosítja a napi rendszerességű háttérben futást.

4\.  `githubkod.txt` – A biztonságos hitelesítésért felelős, 40 karakteres egyedi GitHub Token tárolója.

\## 📊 Felhasznált Adatfájlok (MT5 Files)

A programok a háttérben az alábbi helyi fájlokból építkeznek:

\*   `fxpro\_history\_macd\_fast.csv` – Nyers tőzsdei árak és indikátor adatok.

\*   `fxpro\_trade\_history.csv` – Aktív és lezárt kereskedési pozíciók listája.

\*   `fxpro\_notes.csv` – Instrumentumokhoz fűzött egyedi felhasználói feljegyzések.

\*   `fxpro\_height\_config.json` – Grafikonok magassági beállításai.



\## ⚠️ Jogi és Kockázati Figyelmeztetés

A projektben generált adatok és grafikonok kizárólag edukációs, oktatási és személyes tájékozódási célokat szolgálnak. Nem minősülnek hivatalos befektetési tanácsadásnak, sem ajánlattételnek! A tőkeáttételes tőzsdei kereskedés magas kockázattal jár, a múltbeli hozamok és swap adatok pedig nem jelentenek garanciát a jövőbeli teljesítményre.



