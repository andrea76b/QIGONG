# Qigong — Corpus delle Scienze Bioenergetiche

Pagina HTML unica (`index.html`) con un manichino 3D in Three.js e un player del Liu Zi Jue sincronizzato con la musica (`audio/liu_zi_jue.mp3`, sequenza Health Qigong, 15:02).

- **Avvio locale:** il player ha bisogno di un server che supporti le richieste HTTP Range, altrimenti non si può spostare il punto di ascolto. Va bene `npx http-server` o GitHub Pages; `python -m http.server` no.
- **Minutaggi delle fasi:** stimati con l'analisi spettrale della traccia. Si possono correggere dal pannello "Calibrazione" e restano salvati in localStorage. I valori predefiniti sono in `LZJ_DEFAULT_START`.
- **Etichette di evidenza:** Fonte classica / Tradizione / Evidenza / Speculativo.
- **File audio:** la pagina usa `audio/liu_zi_jue_96k.mp3` (96 kbps mono, 10,8 MB), più leggero da caricare su rete mobile. L'originale a 192 kbps stereo resta in `audio/liu_zi_jue.mp3`.
- **Audio:** traccia ufficiale HQA. Verificare i diritti prima di pubblicare.
