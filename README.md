# OS2SOFD Audits

Repository til lagring af OS2SOFD selvevalueringer.

## GitHub-indstillinger i formularen

![GitHub-indstillinger](docs/images/github-settings-form.png)

Anvend følgende værdier:

- GitHub owner: `OS2sofd`
- GitHub repo: `OS2sofd-audits`
- Branch: `main`
- GitHub token: Fine-grained PAT med Actions: Write og Contents: Write

## Redigering af eksisterende vurdering

1. Download den nyeste JSON-fil fra `docs/self-assessment/`
2. Åbn formularen på https://audit.os2.eu/docs/evaluering/selvevaluering-formular.html
3. Klik **Importér JSON data**
4. Vælg JSON-filen
5. Foretag ændringer
6. Klik **Gem JSON data i GitHub**

## Struktur

```text
OS2sofd-audits
├── .github/
│   └── workflows/
│       └── save-self-assessment.yml
├── docs/
│   ├── images/
│   └── self-assessment/
└── README.md
```
