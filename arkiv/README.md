# Arkiv af gemte sangtimer

Denne mappe er tiltænkt **manuelt arkiv** af gemte sangtimer som JSON-filer.

## Sådan gør du
1. I appen: klik **Gem** (i Sangtime-fanen).
2. Der downloades en fil som fx `Sangtime_2026-01-17.json`.
3. Læg filen her i mappen `arkiv/`.
4. Commit/push til GitHub hvis du vil dele arkivet.

## Hvorfor ligger filerne ikke her automatisk?
Browseren kan af sikkerhedshensyn ikke skrive direkte til projektmappen på disk eller til dit GitHub-repo.
Derfor gemmer appen:
- automatisk seneste sangtime i `localStorage`
- og tilbyder download af en JSON-backupfil, som du selv kan lægge i `arkiv/`.
