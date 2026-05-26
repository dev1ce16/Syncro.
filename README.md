# Syncro. 🎵

Syncro. è un'applicazione mobile di streaming audio sviluppata con **Flutter** e **Dart**, progettata per offrire un'esperienza di riproduzione fluida, reattiva e altamente personalizzabile.

## 🚀 Caratteristiche Principali
- **State Management Avanzato:** Architettura **MVVM** (Model-View-ViewModel) con `Provider` per un rendering UI reattivo e performante.
- **Ottimizzazione Playback:** Logica di disaccoppiamento tra stato visivo e logico per eliminare il *micro-stuttering* durante l'interazione con lo slider.
- **Gestione Coda Dinamica:** Operazioni di inserimento prioritario $O(N)$ e riordinamento tramite drag-and-drop.
- **UI Adattiva:** Supporto per titoli lunghi tramite animazioni *marquee* automatiche.

## 🛠 Tech Stack
- **Framework:** [Flutter](https://flutter.dev/)
- **Linguaggio:** [Dart](https://dart.dev/)
- **Architettura:** MVVM (Model-View-ViewModel)
- **State Management:** [Provider](https://pub.dev/packages/provider)

## 📦 Installazione e Setup
1. Clona la repository: `git clone https://github.com/tuo-username/syncro.git`
2. Entra nella cartella: `cd syncro`
3. Installa le dipendenze: `flutter pub get`
4. Esegui: `flutter run`

## 🏗 Architettura
L'applicazione segue una separazione netta tra i layer per garantire manutenibilità e scalabilità.


## 📝 Roadmap
- [ ] Implementazione persistenza dati con SQFlite.
- [ ] Integrazione API RESTful per streaming cloud.
- [ ] Gestione riproduzione in background tramite `audio_service`.

---

## ⚖️ Copyright e Proprietà Intellettuale

**Copyright © 2026 Tommaso Manfroni. Tutti i diritti riservati.**

Questo software è un'opera protetta da diritto d'autore. Nessuna parte di questo codice, dei componenti grafici o della documentazione può essere riprodotta, distribuita, modificata o venduta in qualsiasi forma o con qualsiasi mezzo, senza previa autorizzazione scritta dell'autore. 

L'utilizzo del codice sorgente presente in questo repository è consentito esclusivamente per fini di consultazione e studio personale.
