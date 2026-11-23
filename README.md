<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MichaelxBelmonte/VisualBrain/main/docs/assets/banner-dark.svg">
  <img src="https://raw.githubusercontent.com/MichaelxBelmonte/VisualBrain/main/docs/assets/banner-light.svg" alt="Visual Brain. A map of your files. A team of agents on every node." width="100%">
</picture>

<p align="center">
  <a href="https://github.com/MichaelxBelmonte/VisualBrain-releases/releases/latest"><img alt="Download the latest release" src="https://img.shields.io/github/v/release/MichaelxBelmonte/VisualBrain-releases?style=flat-square&label=download&labelColor=000000&color=ffd400"></a>
  <img alt="macOS 13.5 or later" src="https://img.shields.io/badge/macOS-13.5%2B-000000?style=flat-square">
  <img alt="Apple Silicon and Intel" src="https://img.shields.io/badge/Apple%20Silicon%20%2B%20Intel-000000?style=flat-square">
  <a href="https://github.com/MichaelxBelmonte/VisualBrain/blob/main/LICENSE"><img alt="MIT license" src="https://img.shields.io/badge/license-MIT-000000?style=flat-square"></a>
</p>

<p align="center">
  <a href="https://github.com/MichaelxBelmonte/VisualBrain-releases/releases/latest"><b>Download the latest release</b></a> ·
  <a href="https://michaelxbelmonte.github.io/VisualBrain/">Website</a> ·
  <a href="https://github.com/MichaelxBelmonte/VisualBrain">Source code</a> ·
  <a href="#italiano">Italiano</a>
</p>

This repository holds the packages of **Visual Brain** for Mac and the feed the app updates from. The code, the documentation and the issues are in [MichaelxBelmonte/VisualBrain](https://github.com/MichaelxBelmonte/VisualBrain), under the MIT license.

## Install

1. Download `Visual-Brain-X.Y.Z-mac-universal.zip` from the [latest release](https://github.com/MichaelxBelmonte/VisualBrain-releases/releases/latest).
2. Unzip it and drag **Visual Brain.app** into **Applications** before opening it.
3. On first launch choose Italian or English and the folders to map. Nothing is scanned before you choose.

Requires macOS 13.5 or later, on Apple Silicon or Intel. Nothing else to install.

The package uses a stable self-signed identity and is not notarized, so macOS may ask you to approve the first launch in **System Settings › Privacy & Security**. The steps are also in the ZIP, in `README.txt` and `LEGGIMI.txt`.

## Updates

Installed apps check the signed `latest.json` of the latest release and offer the update. It installs into Applications without closing your open terminals. You do not need to come back here.

## Check a download

Each release carries the checksum of its package. With both files in the same folder:

```bash
shasum -a 256 -c Visual-Brain-X.Y.Z-mac-universal.zip.sha256
```

## What is in a release

| File | What it is |
|---|---|
| `Visual-Brain-X.Y.Z-mac-universal.zip` | the app, for Apple Silicon and Intel |
| `Visual-Brain-X.Y.Z-mac-universal.zip.sha256` | its SHA-256 checksum |
| `latest.json` and `latest.json.sig` | the update feed and its signature, read by installed apps |

---

## Italiano

Questo repository contiene i pacchetti di **Visual Brain** per Mac e il feed da cui l'app si aggiorna. Il codice, la documentazione e le segnalazioni sono in [MichaelxBelmonte/VisualBrain](https://github.com/MichaelxBelmonte/VisualBrain), con licenza MIT.

**Installazione**

1. Scarica `Visual-Brain-X.Y.Z-mac-universal.zip` dall'[ultima release](https://github.com/MichaelxBelmonte/VisualBrain-releases/releases/latest).
2. Estrailo e trascina **Visual Brain.app** in **Applicazioni** prima di aprirla.
3. Al primo avvio scegli italiano o inglese e le cartelle da mappare. Nessuna scansione parte prima della scelta.

Serve macOS 13.5 o successivo, su Apple Silicon o Intel. Non c'è altro da installare.

Il pacchetto usa un'identità autofirmata stabile e non è notarizzato, quindi macOS può chiederti di autorizzare il primo avvio in **Impostazioni di Sistema › Privacy e sicurezza**. I passaggi sono anche nello ZIP, in `LEGGIMI.txt` e `README.txt`.

**Aggiornamenti.** Le app installate controllano il `latest.json` firmato dell'ultima release e propongono l'aggiornamento. Si installa in Applicazioni senza chiudere i terminali aperti. Non serve tornare qui.

**Controllare un download.** Ogni release ha il checksum del suo pacchetto. Con i due file nella stessa cartella: `shasum -a 256 -c Visual-Brain-X.Y.Z-mac-universal.zip.sha256`.
