# OS2SOFD Audits

Repository til lagring og dokumentation af OS2SOFD selvevalueringer.

## GitHub-indstillinger i formularen

![GitHub-indstillinger](docs/images/github-settings-form.png)

Anvend følgende værdier:

- GitHub owner: `OS2sofd`
- GitHub repo: `OS2sofd-audits`
- Branch: `main`
- GitHub token: Fine-grained PAT med:
  - `Contents: Read and write`
  - `Actions: Read and write`

## GitHub-token

Tokenet opbevares i styregruppens fælles passwordmanager.

Tokenet må ikke gemmes i repositoryet, README-filer, JSON-filer eller andre offentligt tilgængelige steder.

Ved udløb oprettes et nyt Fine-grained Personal Access Token med samme rettigheder.

## Visning af seneste selvevaluering

Workflowet genererer automatisk:

```text
docs/self-assessment/latest.md
```

Denne fil indeholder den seneste selvevaluering i et læsevenligt format og kan åbnes direkte i GitHub.

## Redigering af eksisterende vurdering

1. Download den nyeste JSON-fil fra `docs/self-assessment/`
2. Åbn formularen:
   https://audit.os2.eu/docs/evaluering/selvevaluering-formular.html
3. Klik **Importér JSON data**
4. Vælg JSON-filen
5. Foretag ændringer
6. Klik **Gem JSON data i GitHub**

Ved hver gemning oprettes:

- En ny JSON-fil med tidsstempel
- En opdateret `latest.md` rapport

## Filstruktur

```text
OS2sofd-audits
├── .github/
│   └── workflows/
│       └── save-self-assessment.yml
├── docs/
│   ├── images/
│   │   └── github-settings-form.png
│   └── self-assessment/
│       ├── latest.md
│       ├── os2sofd-YYYYMMDDTHHMMSSZ.json
│       └── ...
└── README.md
```

## Historik

Selvevalueringer overskrives ikke.

Hver gemning opretter en ny JSON-fil med tidsstempel, hvilket giver et komplet revisionsspor og mulighed for at genskabe tidligere versioner af vurderingen.
