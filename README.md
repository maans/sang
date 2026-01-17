# Sangtime Generator (SangApp)

Single-file webapp til at bygge en sangtime og bladre i noder (scan-sider) i en modal-viewer.

## Kør appen lokalt

1. Læg `index.html` i en mappe.
2. Opret en mappe `pages/` i **samme** mappe.
3. Læg scan-billederne i `pages/`.
4. Åbn `index.html` i en browser.

Appen forsøger automatisk at bruge `./pages/` hvis den findes. Alternativt kan du vælge en billedmappe under **Temaer** (folder picker).

## Billedformat og filnavne

Appen forventer PNG-filer med navne på formen:

- `page_001.png` ... `page_214.png`

**Vigtigt:** Filnavnene skal have 3 cifre og starte ved 001.

### Ophavsret

Læg **ikke** bogens scan-sider på GitHub (eller andre offentlige steder). Repoet bør kun indeholde app-koden. Scan-siderne lægges lokalt i `pages/` på din computer.

## Hjælp i appen

Klik på `?` i topbaren for en kort brugervejledning.

## Udskift sangtitler og temaer (CSV fra Excel)

Du kan importere en CSV, der **erstatter/overstyrer** sangtitler og temaer.

- Gå til **Temaer** → **Data (sange og temaer)**
- Vælg CSV → klik **Importér**

Kolonner (header):

- `nr` (sangnummer)
- `titel`
- `temaer` (flere temaer adskilles med `|` eller `;`)

Eksempel:

```csv
nr,titel,temaer
1,Her er mit sted,FÆLLESSKAB|LIVSMOD
19,Puslespil,LIVSMOD
```

For at gå tilbage til standarddata: klik **Nulstil data**.

## Noter om GitHub Pages

GitHub Pages kan hoste selve appen, men ikke (lovligt) scan-billederne. Hvis du åbner appen fra GitHub Pages, skal du derfor typisk bruge folder picker til at vælge din lokale `pages/`-mappe.
