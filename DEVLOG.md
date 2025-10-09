# 🧱 Padel BreakPoint — DevLog

Benvenuti nel diario di sviluppo ufficiale di **Padel BreakPoint** 🎾  
Un progetto indipendente che vuole portare il **padel** nel mondo dei videogiochi, unendo ritmo, tecnica e spettacolo.

---

## 🗓️ Giorno 1 — “La palla prende vita” (07/10/2025)
Oggi inizia ufficialmente lo sviluppo del gioco.  
L’obiettivo era creare **una base fisica stabile** e **una scena di test** per iniziare a sperimentare la dinamica della palla.

✅ Risultati:
- Creato progetto **Unity URP 3D**  
- Configurato **Input System** per future espansioni su joypad  
- Costruita la **struttura delle cartelle e delle scene** base  
- Implementata la **palla con fisica personalizzata** (gravità, rimbalzo, attrito)  
- Aggiunta una **scia luminosa (trail)** per migliorare leggibilità e feedback  
- Primo test di gameplay nella scena *Sandbox_Physics*  

🧠 Sensazioni:
> Vedere la palla rimbalzare in modo coerente è il primo passo concreto.  
> Da qui comincia tutto — la base su cui costruiremo il resto del gioco.

---

## 🔜 Prossimo step — “Player e movimento”
Il prossimo obiettivo sarà introdurre il **giocatore controllabile** e una **camera TopSpin** per avere una visuale di gioco completa.  
Verranno testati i primi movimenti e direzioni di colpo.

---

## 💬 Note sul progetto
Padel BreakPoint è sviluppato da **Roberto D’Anna**, con l’obiettivo di creare un titolo sportivo accessibile ma tecnico, dove ogni colpo ha peso e personalità.

Seguici per nuovi aggiornamenti, GIF e prototipi nelle prossime settimane!

---

## 🗓️ Giorno 2 — “Il giocatore entra in campo” (09/10/2025)

Dopo aver dato vita alla palla, oggi il focus è stato sul **giocatore** e sul **controllo della scena**.  
L’obiettivo era ottenere un movimento fluido, una camera da fondo campo stabile e un sistema di mira semplice ma funzionale.

---

### 🎮 Risultati
- Implementato il **PlayerMovement** con supporto per tastiera e joypad.  
- Aggiunta la **rotazione dinamica** verso la direzione di movimento.  
- Creata una **camera fissa da fondo campo**, che segue il giocatore solo in profondità (asse Z).  
- Sistemate le **proporzioni reali** del campo (10×20 m) e del giocatore (~1.8 m).  
- Introdotto l’**Aim Indicator**, un piccolo mirino che si muove davanti al player e indica la direzione del colpo.

---

### 💬 Riflessioni
> “Ora che il giocatore si muove, la telecamera si comporta come una vera ripresa da match,  
> e il mirino risponde ai comandi, il campo inizia finalmente a sembrare vivo.”

La base del controllo è pronta: movimento, camera e mira sono già perfettamente sincronizzati.  
Da qui in avanti inizieremo a costruire **i colpi veri e propri**.

---

### 🔜 Prossimo step
- Creare il sistema di **ShotHandler** (carica, rilascio e forza del colpo).  
- Collegare il mirino alla **traiettoria della palla**.  
- Aggiungere i primi **feedback visivi** (colori del colpo, forza, effetto).

📅 *Ultimo aggiornamento:* 09 Ottobre 2025  
👤 *Sviluppatore:* Roberto D’Anna  
🛠️ *Motore:* Unity 2023 LTS (URP)
