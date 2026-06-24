# OS2SOFD Audits

Repository til lagring, historik og rapportering af OS2SOFD selvevalueringer.

---

## 📊 Seneste rapport

### GitHub Pages

Hvis GitHub Pages er aktiveret:

https://os2sofd.github.io/OS2sofd-audits/docs/self-assessment/latest.html

### Repository-filer

- HTML-rapport: `docs/self-assessment/latest.html`
- Markdown-rapport: `docs/self-assessment/latest.md`

---

## Formål

Repositoryet anvendes af OS2SOFD-styregruppen til at:

- Gemme selvevalueringer fra audit.os2.eu
- Bevare historik over tidligere vurderinger
- Generere læsevenlige rapporter automatisk
- Dokumentere modenhed og compliance i forhold til OS2-governancekrav

---

## GitHub-indstillinger i formularen

![GitHub-indstillinger](docs/images/github-settings-form.png)

Anvend følgende værdier:

| Felt | Værdi |
|-------|--------|
| GitHub owner | `OS2sofd` |
| GitHub repo | `OS2sofd-audits` |
| Branch | `main` |
| GitHub token | Fine-grained PAT |

### Token-rettigheder

Tokenet skal have følgende repository permissions:

- `Contents: Read and write`
- `Actions: Read and write`

---

## GitHub-token

Tokenet opbevares i styregruppens fælles passwordhvælv.

Tokenet må **ikke** gemmes i:

- Repositoryet
- README-filer
- JSON-filer
- GitHub Issues
- E-mails
- Andet offentligt tilgængeligt materiale

Ved udløb oprettes et nyt Fine-grained Personal Access Token med samme rettigheder.

---

## Opret eller opdater en selvevaluering

1. Åbn formularen:

   https://audit.os2.eu/docs/evaluering/selvevaluering-formular.html

2. Udfyld eller opdater vurderingen.

3. Angiv GitHub-oplysningerne.

4. Klik **Gem JSON data i GitHub**.

5. Workflowet opretter automatisk:

   - En ny JSON-fil med tidsstempel
   - En opdateret Markdown-rapport (`latest.md`)
   - En opdateret HTML-rapport (`latest.html`)

---

## Genåbn og redigér en eksisterende vurdering

1. Download den nyeste JSON-fil fra:

   ```text
   docs/self-assessment/
   ```

2. Åbn formularen:

   https://audit.os2.eu/docs/evaluering/selvevaluering-formular.html

3. Klik **Importér JSON data**.

4. Vælg den downloadede JSON-fil.

5. Foretag ændringer.

6. Klik **Gem JSON data i GitHub**.

---

## Rapporter

### HTML-rapport

Fil:

```text
docs/self-assessment/latest.html
```

Hvis GitHub Pages er aktiveret:

```text
https://os2sofd.github.io/OS2sofd-audits/docs/self-assessment/latest.html
```

### Markdown-rapport

Fil:

```text
docs/self-assessment/latest.md
```

Kan læses direkte i GitHub.

### Statusfarver

| Status | Farve |
|---------|---------|
| Ja | 🟢 Grøn |
| Nej | 🔴 Rød |
| Ved ikke | 🟡 Gul |
| Planlagt | 🟡 Gul |
| Ikke relevant | ⚪ Grå |

---

## Historik

Selvevalueringer overskrives ikke.

Hver gemning opretter en ny JSON-fil med tidsstempel.

Eksempel:

```text
os2sofd-20260623T090758Z.json
os2sofd-20260623T102408Z.json
os2sofd-20260623T102840Z.json
```

Dette giver et komplet revisionsspor og mulighed for at genskabe tidligere versioner af vurderingen.

---

## Repositorystruktur

```text
OS2sofd-audits
├── .github/
│   └── workflows/
│       └── save-self-assessment.yml
├── docs/
│   ├── images/
│   │   └── github-settings-form.png
│   └── self-assessment/
│       ├── latest.html
│       ├── latest.md
│       ├── os2sofd-YYYYMMDDTHHMMSSZ.json
│       └── ...
└── README.md
```

---

## Vedligeholdelse

Workflowet:

```text
.github/workflows/save-self-assessment.yml
```

er ansvarligt for:

- Gemning af JSON-filer
- Generering af Markdown-rapport
- Generering af HTML-rapport
- Commit og push af ændringer

Ved ændringer i JSON-strukturen fra audit.os2.eu skal workflowet eventuelt tilpasses.

---

## GitHub Pages

Aktivér under:

```text
Settings → Pages
```

Vælg:

```text
Source: Deploy from a branch
Branch: main
Folder: / (root)
```

Når publiceringen er gennemført, kan rapporten læses direkte via:

```text
https://os2sofd.github.io/OS2sofd-audits/docs/self-assessment/latest.html
```

Dette giver styregruppen, kommunerne og sekretariatet en direkte URL til den seneste selvevalueringsrapport.
