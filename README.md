# GlassRefine-Updates

# 🛡️ GlassRefine
### Il Debloater Chirurgico per Windows 10 & 11

![License](https://img.shields.io/badge/license-MIT-blue.svg) ![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078D6.svg) ![VirusTotal](https://img.shields.io/badge/VirusTotal-0%2F70%20Clean-success)

> **"Windows è una macchina potente, ma esce dalla fabbrica piena di adesivi inutili, limitatori di velocità e pezzi di plastica che ballano. GlassRefine è l'officina che strappa via tutto il superfluo e restituisce il controllo al pilota."**

---

## 🔧 Che cos'è GlassRefine?

**GlassRefine** non è il solito script "distruggi-tutto" trovato su internet che rompe il sistema. È un tool **WPF avanzato** progettato per:
1.  **Pulire (Debloat):** Rimuovere le app preinstallate inutili (Bloatware) con precisione chirurgica.
2.  **Installare (Winget Engine):** Installare il tuo arsenale software preferito in un click, usando il motore ufficiale Microsoft Winget.
3.  **Ottimizzare (Refine):** Applicare tweak di registro mirati per privacy e prestazioni, senza compromettere la stabilità.

🚫 **Nessun processo in background.** GlassRefine è un chirurgo: entra, opera, ripara e se ne va. Non lascia servizi attivi a consumare RAM.

---

## 🚀 Funzionalità Principali (Il Motore)

### 📦 Installazione Intelligente (Winget Auto-Pilot)
Il cuore del sistema. Non serve cercare `.exe` su siti dubbi.
* **Gestione Automatica:** Se `winget` non è presente (comune su Windows 10), GlassRefine lo scarica e lo installa silenziosamente dal server Microsoft.
* **Arsenale Completo:** Categorie organizzate (Gaming, Dev, Privacy, Multimedia) per configurare un PC nuovo in 3 minuti.
* **Logica "Sempre Aggiornato":** Scarica sempre l'ultima versione disponibile dai repository ufficiali.

### 🛡️ Sicurezza & Trasparenza (No Black Box)
Sappiamo che fidarsi di un `.exe` è difficile. Ecco perché abbiamo puntato tutto sulla trasparenza:
* **0/70 su VirusTotal:** Codice pulito, nessuna offuscazione sospetta, nessun comportamento da malware.
* **Logger in Tempo Reale:** Ogni azione (scrittura registro, download, eliminazione) viene mostrata a schermo. Sai sempre cosa sta succedendo.
* **Rete di Sicurezza:** Il programma tenta di creare un **Punto di Ripristino** prima di ogni operazione critica. Se cambi idea, puoi tornare indietro.

### ⚡ Interfaccia "Aero" Moderna
Non ci piacciono le finestre di comando nere e tristi.
* UI scritta in **WPF (XAML)** con stile pulito.
* Animazioni fluide.
* Organizzazione visiva chiara per evitare errori di distrazione.

---

## 🧪 Provalo in una VM (Sfida Aperta)

Sei scettico? **Fai bene.** La sicurezza prima di tutto.
Incoraggiamo tutti gli utenti avanzati a testare **GlassRefine** in una Virtual Machine (VirtualBox, VMware, Sandbox).

1.  Lancia GlassRefine nella VM.
2.  Apri il Task Manager e monitora le risorse.
3.  Controlla il traffico di rete (vedrai solo connessioni ai server Microsoft/GitHub per i download).
4.  Goditi la pulizia.

*Vedrai che l'unica cosa che "ruberemo" è la spazzatura che rallenta il tuo PC.*

---

## 📥 Installazione e Utilizzo

1.  Scarica l'ultima release dalla sezione **Releases**.
2.  Estrai l'archivio.
3.  **⚠️ IMPORTANTE:** Clicca destro su `GlassRefine.exe` e seleziona **"Esegui come Amministratore"**.
    * *Perché?* Per installare programmi (Winget) e modificare il registro di sistema, servono i permessi di officina (Admin). Senza di essi, Windows bloccherà gli attrezzi.
4.  Scegli le operazioni da eseguire e lascia lavorare Stefano (il motore virtuale).

---

## ⚠️ Disclaimer (Leggere attentamente)

*Questo software è fornito "così com'è", senza garanzia di alcun tipo. Sebbene GlassRefine sia progettato per essere sicuro e crei punti di ripristino, modificare il sistema operativo comporta sempre dei rischi.*

* **Non siamo responsabili** se rimuovi per sbaglio un'app che ti serviva (es. la Calcolatrice o lo Store), ma... ehi, puoi sempre reinstallarle con un click!
* L'uso di questo tool implica che tu sappia, almeno in parte, cosa stai facendo al tuo computer.

---

## 👨‍💻 Crediti

Sviluppato con passione, caffè e tanto C#.
* **Motore:** .NET / WPF
* **Package Manager:** Microsoft Winget
* **Design Philosophy:** "Less is More"

---

> **"Un PC pulito è un PC felice. Benvenuto in famiglia."** 🏁
