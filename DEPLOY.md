# DEPLOY

## Anbefalt oppsett

Bruk GitHub Pages fra `main`-grenen og mappen `docs/`.

Selve nettstedet ligger i:

- `docs/`

Det gjør at repoet får en ryddig forside med `README.md`, mens arkivet publiseres fra undermappen.

## GitHub Pages

1. Gå til `Settings` -> `Pages`
2. Velg `Deploy from a branch`
3. Velg `main`
4. Velg mappen `docs/`
5. Lagre

## Domene

Følgende fil er allerede med i `docs/`:

- `CNAME`

Den er satt til:

```txt
arkiv.ringeriketkd.no
```

## DNS

Legg normalt inn:

```txt
Type: CNAME
Name/Host: arkiv
Target/Value: <brukernavn>.github.io
```

Bytt ut `<brukernavn>` med GitHub-brukeren eller organisasjonen som eier Pages-nettstedet.
