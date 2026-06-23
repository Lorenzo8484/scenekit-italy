# Backup aNavigator v1.0

Tutti i file necessari per compilare aNavigator v1.0.

## Per compilare

```bash
bash build_ipa.sh 1.0
```

Dipende da:
- clang-19
- ld64.lld-19
- iPhoneOS16.5.sdk in /home/alina/sdk/

## Struttura

- `*.h` / `*.m` / `*.mm` — sorgenti ObjC
- `Info.plist` — metadati app
- `map.html` — mappa MapLibre GL JS
- `assets/` — texture bus 3D, bussola, freccia
- `build_ipa.sh` — script compilazione

## Versioni

- `v1.0` — Prima versione con MapLibre GL JS + OpenFreeMap + UI completa aNavigator
