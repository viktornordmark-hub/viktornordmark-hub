# Viktor Nordmark
DevOps Engineer (LIA-sökande: nov 2026 - apr 2027)

viktornordmark@gmail.com · 0736 66 86 63
github.com/viktornordmark-hub · git.chas-lab.dev/vino

---

## Profil

DevOps-student vid Chas Academy med fokus på Linux, automation och säker infrastruktur.
Jag söker LIA november 2026 - april 2027.

Bakgrund från logistik och service - van vid högt tempo, precision och att leverera
när det faktiskt gäller.

---

## Projekt

### Linux Server Automation (Bash) - Grupprojekt, GitLab
[Repo](https://git.chas-lab.dev/LisaLassi/group-4)
Automatiserad konfiguration av Ubuntu 24.04-server via Bash-skript.

Min del: SSH-härdning och firewall.
- Drop-in config via sshd_config.d/ (redigerar inte huvudfilen)
- sshd -t validerar syntax innan restart - servern går inte ner vid stavfel
- Inaktiverar ssh.socket explicit (systemd-socket-activation)
- Non-default port, pubkey-only, PermitRootLogin no, AllowUsers
- Installerar firewalld, inaktiverar ufw, tar bort default-tjänster

### System Monitor (Python) - GitHub
[Repo](https://github.com/viktornordmark-hub/slutprojekt-doe)
Slutprojekt Pythonkurs. Övervakar CPU, RAM och disk i realtid.
Användaren kan sätta, ta bort och trigga larm per resurs.

### systemd-restic-timer (Bash) - GitLab
[Repo](https://git.chas-lab.dev/vino/systemd-restic-timer)
Automatiserad backup via systemd-timer och restic.
Kör schemalagt och loggar utfall.

### Pet Shop Database (Python + MariaDB + Docker) - Grupprojekt
*(privat repo, skolserver)*
Min del: databasschema för shop/orders samt testdatagenerering.
- Python-skript med Faker (sv_SE) för realistisk svensk testdata
- many-to-many-relationer (produkter/färger/material) utan dubletter
- Gruppen körde MariaDB via Docker Compose med named volume och .env-credentials

---

## Tekniska färdigheter

- OS:          Linux (Fedora, Ubuntu, Ubuntu Server), macOS
- Scripting:   Bash, Python
- VCS:         Git - GitHub, GitLab
- Containers:  Docker
- Databaser:   SQL - SQLite, MariaDB

Pågående kurser (VT/HT 2026): CI/CD, Kubernetes, GitOps

---

## Utbildning

DevOps Engineer - Chas Academy, Stockholm
HT 2025 – sommar 2027

Kurser hittills: Python, Linux/Bash-scripting, Databaser

---

## Arbetslivserfarenhet

Lagerarbetare - ICA Centrallager Västerås (2018–pågående, samt 2015–2017)
  Precision, leveranssäkerhet, stort team, högt tempo.

Butiksmedarbetare - TGR, Oslo (2014–2015)
  Utlandserfarenhet, nytt språk, ny miljö - anpassade mig snabbt.

Service - McDonald's & Ben & Jerry's (2010–2014)
  Tidigt fokus på att leverera under tryck.

---

## Övrigt

Språk:  Svenska (modersmål), Engelska (flytande)
Resor:  5 månader Central- & Sydamerika (VT 2018)
