# Qigong — Corpus delle Scienze Bioenergetiche

**Sito pubblico:** https://andrea76b.github.io/QIGONG/ (GitHub Pages, ramo `gh-pages`). Il ramo `gh-pages` va aggiornato a ogni modifica con `git push origin HEAD:gh-pages`.

Pagina HTML unica (`index.html`) con un manichino 3D in Three.js e un player del Liu Zi Jue sincronizzato con la musica (`audio/liu_zi_jue.mp3`, sequenza Health Qigong, 15:02).

- **Avvio locale:** il player ha bisogno di un server che supporti le richieste HTTP Range, altrimenti non si può spostare il punto di ascolto. Va bene `npx http-server` o GitHub Pages; `python -m http.server` no.
- **Tempi e sottotitoli:** vengono dai comandi vocali ufficiali (口令) della traccia IHQA con voce guida, trascritti con un riconoscimento vocale offline (SenseVoice) e corretti con il lessico HQA. Sono in `LZJ_CUES` (tempo, cinese, pinyin, italiano, tipo di respiro) e valgono per entrambe le tracce, che hanno la stessa linea temporale.
- **Etichette di evidenza:** Fonte classica / Tradizione / Evidenza / Speculativo.
- **File audio:** `audio/liu_zi_jue_musica_sync_96k.mp3` (predefinita, solo musica, 15:22) e `audio/liu_zi_jue_voce_96k.mp3` (con voce guida in cinese, 15:24), entrambe a 96 kbps mono. La traccia solo musica è ricavata da quella con voce: nei primi 4:50 la voce è tolta con il modello di separazione UVR-MDX-NET Inst HQ3; dal minuto 4:50 c'è la musica originale senza voce (`audio/liu_zi_jue.mp3`, 192 kbps), che lì coincide con la versione con voce a meno di 19,6 s di sfasamento. Collaudo: sul tratto in cui la musica pulita è nota, la separazione porta il rapporto segnale/disturbo da −0,6 a +6,1 dB e il riconoscimento vocale non trova più parole.
- **Audio:** traccia ufficiale HQA. Verificare i diritti prima di pubblicare.
