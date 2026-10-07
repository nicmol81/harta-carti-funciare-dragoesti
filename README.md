# Harta imobile - Cărți funciare Drăgoești

Hartă interactivă cu poligoanele a 3136 de imobile din comuna Drăgoești,
jud. Vâlcea (nr. cadastral, tarlă, intravilan/extravilan, suprafață).

Click pe un poligon pentru detalii. Căutare după nr. cadastral în colțul
din stânga-sus. Comutator hartă/satelit în colțul din dreapta-sus. Buton
GPS pentru locația curentă (util pe teren, de pe telefon).

Se încarcă treptat: la zoom mic se văd doar conturul larg al tarlalelor
(`data/sole.geojson`), poligoanele individuale (`data/imobile.geojson`)
apar abia de la zoom 15 în sus — detalii în README-ul repo-ului privat
(`nicmol81/carti-funciare-dragoesti`, secțiunea 11).

**Fără date personale** — nu conține nume de proprietari sau linkuri către
documentele de carte funciară (acelea rămân într-un repo privat separat).

## Rulare locală

```bash
python3 -m http.server 8000
```
apoi deschide `http://localhost:8000/`.

## Publicare (GitHub Pages)

Settings → Pages → Source: Deploy from a branch → `main` / `(root)`.
