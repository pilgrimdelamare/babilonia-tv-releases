<div align="center">

**🇮🇹 Italiano** | [🇬🇧 English](README.en.md)

<a href="https://babilonia-tv.pages.dev"><img src="docs/img/hero_it.jpg" alt="Babilonia TV: ogni canale del mondo, doppiato nella tua lingua" width="100%"></a>

# Babilonia TV

### Ogni canale del mondo, doppiato nella tua lingua. In diretta.

[![Versione](https://img.shields.io/github/v/release/pilgrimdelamare/babilonia-tv-releases?style=for-the-badge&label=versione&color=e50914&labelColor=111)](https://github.com/pilgrimdelamare/babilonia-tv-releases/releases/latest)
[![Download](https://img.shields.io/github/downloads/pilgrimdelamare/babilonia-tv-releases/total?style=for-the-badge&label=download&color=e50914&labelColor=111)](https://github.com/pilgrimdelamare/babilonia-tv-releases/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-white?style=for-the-badge&labelColor=111&color=333)](#-come-si-usa)
[![IA sul tuo PC](https://img.shields.io/badge/IA-sul%20tuo%20PC-white?style=for-the-badge&labelColor=111&color=333)](#-perch%C3%A9-%C3%A8-diverso)
[![Gratis](https://img.shields.io/badge/prezzo-gratis-white?style=for-the-badge&labelColor=111&color=333)](#-domande-frequenti)

<br>

<a href="https://github.com/pilgrimdelamare/babilonia-tv-releases/releases/latest/download/Babilonia_Engine_Windows.zip"><img src="https://img.shields.io/badge/Scarica%20per%20Windows-e50914?style=for-the-badge&logoColor=white" height="56" alt="Scarica per Windows"></a>
&nbsp;
<a href="https://babilonia-tv.pages.dev"><img src="https://img.shields.io/badge/Apri%20il%20player-222?style=for-the-badge" height="56" alt="Apri il player"></a>

<sub>Gratis. Nessuna installazione: si estrae lo ZIP e si avvia.</sub>

</div>

<br>

Incolli il link di uno stream e Babilonia lo **ascolta, lo traduce e lo ridoppia** nella lingua del tuo browser, mentre va in onda. Ogni persona che parla ha **la sua voce**, i sottotitoli sono già pronti e la pubblicità del canale resta com'era. Il lavoro pesante lo fa il tuo PC: nessun video passa dai nostri server.

<br>

## ✨ Perché è diverso

| | |
|---|---|
| 🎙️ **Una voce per ogni persona** | Riconosce chi parla dal timbro e gli dà una voce sua, fissa per tutta la trasmissione. Dieci voci, cinque maschili e cinque femminili. |
| 🧠 **Orecchie specializzate** | Capisce da sola la lingua del canale e passa al modello più preciso: russo, cinese, giapponese, coreano, arabo, ebraico hanno un modello dedicato. |
| 🗣️ **Voci naturali, senza internet** | Le voci vengono generate sul tuo PC in 31 lingue, italiano compreso. |
| 📺 **Gli spot restano spot** | Riconosce le pause pubblicitarie e le lascia in lingua originale, con il volume livellato. |
| 🔒 **Privato per davvero** | Audio e video restano sul tuo computer. Niente account, niente abbonamenti. |
| 🧳 **Portatile** | Tutto in una cartella: Python, FFmpeg e modelli inclusi. Per disinstallare la cancelli. |

<br>

<p align="center"><img src="docs/img/pipeline_it.jpg" alt="Come funziona: cattura, ascolto, traduzione, voci, montaggio" width="100%"></p>

<p align="center"><img src="docs/img/voices_it.jpg" alt="Dieci voci, una per ogni persona" width="100%"></p>

<p align="center"><img src="docs/img/languages_it.jpg" alt="Lingue: ascolta oltre 90 lingue, doppia in 31" width="100%"></p>

<p align="center"><img src="docs/img/ads_it.jpg" alt="Gli spot del canale restano com'erano" width="100%"></p>

<br>

## 🚀 Come si usa

1. **Scarica** [lo ZIP](https://github.com/pilgrimdelamare/babilonia-tv-releases/releases/latest/download/Babilonia_Engine_Windows.zip) ed estrailo in una cartella.
2. **Avvia** `Avvia_Babilonia_Engine.bat`. Compare l'icona di Babilonia vicino all'orologio e si apre il player.
3. **Incolla** il link di uno stream (`.m3u8`) o carica una playlist `.m3u`. Dopo circa un minuto lo guardi doppiato.

> [!TIP]
> Se il browser chiede di **accedere ai dispositivi della rete locale**, scegli *Consenti*: serve solo a far parlare la pagina con il motore sul tuo PC.
>
> Se Windows mostra **"PC protetto da Windows"**, clicca *Ulteriori informazioni* → *Esegui comunque*.

<br>

## 💻 Requisiti

| | Minimo | Consigliato |
|---|---|---|
| Sistema | Windows 10 o 11, 64 bit | Windows 11 |
| Processore | 4 thread | 8 thread o più |
| Memoria | 8 GB | 16 GB |
| Spazio | 1,5 GB | 3 GB (per i modelli extra) |
| Browser | Chrome, Edge, Brave, Firefox | Chrome o Edge |

Non serve una scheda video. Sui PC più veloci il motore scarica da solo i modelli più grandi per arabo ed ebraico.

<br>

## ❓ Domande frequenti

<details>
<summary><b>Quanto costa?</b></summary>

Niente. Babilonia TV è gratis e senza abbonamenti. Se ti piace puoi [offrirci un caffè](https://paypal.me/alemarasso).
</details>

<details>
<summary><b>Da quali lingue traduce?</b></summary>

Riconosce da solo la lingua di partenza tra oltre 90. Russo, cinese, giapponese, coreano, cantonese, arabo ed ebraico hanno un modello dedicato, più preciso. Doppia con voci naturali in 31 lingue; per le altre usa voci online.
</details>

<details>
<summary><b>Quanto ritardo c'è rispetto alla diretta?</b></summary>

Circa un minuto all'avvio, il tempo di preparare i primi blocchi da 30 secondi. Durante l'attesa il player mostra cosa sta facendo il motore, blocco per blocco.
</details>

<details>
<summary><b>Babilonia TV fornisce i canali?</b></summary>

No. È un player, come VLC: non fornisce, non ospita e non indicizza canali. Apri solo stream che hai il diritto di guardare.
</details>

<details>
<summary><b>Perché il browser chiede di accedere alla rete locale?</b></summary>

È il modo in cui il sito parla con il motore che gira sul tuo PC (indirizzo `127.0.0.1`). Non accede ad altri dispositivi e niente esce dal tuo computer.
</details>

<details>
<summary><b>Come lo disinstallo?</b></summary>

Chiudi il motore (clic destro sull'icona vicino all'orologio → *Esci*) e cancella la cartella. Non lascia niente altrove.
</details>

<br>

## 🧩 Costruito con

Babilonia mette insieme progetti open source straordinari:
[FFmpeg](https://ffmpeg.org) ·
[faster-whisper](https://github.com/SYSTRAN/faster-whisper) ·
[sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) ·
[GigaAM](https://github.com/salute-developers/GigaAM) ·
[SenseVoice](https://github.com/QwenAudio/SenseVoice) ·
[Moonshine](https://github.com/moonshine-ai/moonshine) ·
[Omnilingual ASR](https://github.com/facebookresearch/omnilingual-asr) ·
[3D-Speaker CAM++](https://github.com/modelscope/3D-Speaker) ·
[Supertonic](https://github.com/supertone-oss-archive/supertonic)

<br>

<div align="center">

### ☕ Ti piace Babilonia TV?

È gratis e lo resterà. Un caffè aiuta a tenerlo vivo.

<a href="https://paypal.me/alemarasso"><img src="https://img.shields.io/badge/Offrici%20un%20caff%C3%A8-PayPal-e50914?style=for-the-badge&logo=paypal&logoColor=white&labelColor=111" height="40" alt="Offrici un caffè con PayPal"></a>

<br><br>

<sub>Babilonia TV è un player e traduttore neutro, come VLC o Kodi: non fornisce, non ospita e non indicizza canali, stream o contenuti televisivi. Gli utenti sono gli unici responsabili delle fonti che aprono e devono avere il diritto di guardarle. Traduzioni e voci sono generate automaticamente e possono contenere errori.</sub>

</div>
