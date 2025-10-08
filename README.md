<div align="center">
  <img src="https://raw.githubusercontent.com/Xzar-x/images/main/logo.png" alt="Logo Xzar" width="200" />
  <h1>Hi there, I'm Xzar! 👋</h1>
  <p>Hacker • Pentester • Developer • Bug Bounty Enthusiast</p>
</div>

---

# O mnie
Jestem pasjonatem **cyberbezpieczeństwa** i etycznego hackingu z Polski. Buduję narzędzia recon, piszę write-upy, ćwiczę na HTB i dzielę się wiedzą na YouTube.  
Główne stacki: **Python**, CLI, automatyzacja reconu, bug bounty workflow.

> Where others see a wall, I see a backdoor.

---

# Top badges (szybka kontrola statusu)
<!-- Zmieniaj `main` na swój branch jeśli masz inny -->
<!-- ShadowMap -->
[![ShadowMap CI](https://github.com/Xzar-x/ShadowMap/actions/workflows/ci.yml/badge.svg)](https://github.com/Xzar-x/ShadowMap/actions)
[![ShadowMap Release](https://img.shields.io/github/v/release/Xzar-x/ShadowMap?label=release)](https://github.com/Xzar-x/ShadowMap/releases)
[![ShadowMap License](https://img.shields.io/github/license/Xzar-x/ShadowMap)](https://github.com/Xzar-x/ShadowMap/blob/main/LICENSE)
[![ShadowMap Stars](https://img.shields.io/github/stars/Xzar-x/ShadowMap)](https://github.com/Xzar-x/ShadowMap/stargazers)
[![ShadowMap Last Commit](https://img.shields.io/github/last-commit/Xzar-x/ShadowMap)](https://github.com/Xzar-x/ShadowMap/commits)

<!-- VulnMap -->
[![VulnMap CI](https://github.com/Xzar-x/VulnMap/actions/workflows/ci.yml/badge.svg)](https://github.com/Xzar-x/VulnMap/actions)
[![VulnMap Release](https://img.shields.io/github/v/release/Xzar-x/VulnMap?label=release)](https://github.com/Xzar-x/VulnMap/releases)
[![VulnMap License](https://img.shields.io/github/license/Xzar-x/VulnMap)](https://github.com/Xzar-x/VulnMap/blob/main/LICENSE)
[![VulnMap Stars](https://img.shields.io/github/stars/Xzar-x/VulnMap)](https://github.com/Xzar-x/VulnMap/stargazers)
[![VulnMap Last Commit](https://img.shields.io/github/last-commit/Xzar-x/VulnMap)](https://github.com/Xzar-x/VulnMap/commits)

<!-- github-release-dotfiles-backup -->
[![Dotfiles Backup CI](https://github.com/Xzar-x/github-release-dotfiles-backup/actions/workflows/ci.yml/badge.svg)](https://github.com/Xzar-x/github-release-dotfiles-backup/actions)
[![Dotfiles Release](https://img.shields.io/github/v/release/Xzar-x/github-release-dotfiles-backup?label=release)](https://github.com/Xzar-x/github-release-dotfiles-backup/releases)
[![Dotfiles License](https://img.shields.io/github/license/Xzar-x/github-release-dotfiles-backup)](https://github.com/Xzar-x/github-release-dotfiles-backup/blob/main/LICENSE)
[![Dotfiles Stars](https://img.shields.io/github/stars/Xzar-x/github-release-dotfiles-backup)](https://github.com/Xzar-x/github-release-dotfiles-backup/stargazers)
[![Dotfiles Last Commit](https://img.shields.io/github/last-commit/Xzar-x/github-release-dotfiles-backup)](https://github.com/Xzar-x/github-release-dotfiles-backup/commits)

> Jeśli używasz innej nazwy workflow (np. `build.yml`) lub branchu (np. `master`), zamień `ci.yml` / `main` w linkach na właściwe wartości.

---

# Projekty (wybrane)
Poniżej skróty do głównych repo i krótkie opisy. Dodaj GIF demo w `assets/` każdego repo — link zastąpiony przykładami.

## ShadowMap
**Automatyczny recon**: integruje `amass`, `subfinder`, `gobuster`, `httpx`, `ffuf`. Generuje `report.html` z przejrzystym podsumowaniem i zakładkami dla każdego etapu.
- Repo: https://github.com/Xzar-x/ShadowMap  
- Demo GIF (wrzuć `assets/shadowmap-demo.gif`):  
  `![ShadowMap Demo](./assets/shadowmap-demo.gif)`

## VulnMap
**Mapa podatności i helpery** — skrypty/utility do sanityzacji wyników, parsowania, szybkiego proof-of-concept generation (sanitized).
- Repo: https://github.com/Xzar-x/VulnMap

## github-release-dotfiles-backup
**Automatyczny backup dotfiles** do GitHub Releases — proste narzędzie do archiwizacji konfiguracji i szybkiego odtworzenia środowiska.
- Repo: https://github.com/Xzar-x/github-release-dotfiles-backup

---

# Krótka instrukcja: jak dodać GIF demo (3 kroki)
1. Nagraj demo (Peek / asciinema + agg / OBS → eksport do GIF).  
2. W repo wrzuć plik do `assets/` (np. `assets/shadowmap-demo.gif`).  
3. W README wklej: `![ShadowMap Demo](./assets/shadowmap-demo.gif)` — najlepiej 3–7s, rozmiar <800KB.

---

# Sekcja: Write-ups & Templates
- Sanityzowane write-upy (bez hostnames/identyfikatorów, only PoC + kroki reprodukcji na test env).  
- Checklista recon / Bug Bounty templates: recon plan, payload list, quick wins list.  
(Jeśli chcesz, wkleję gotowy szablon write-upa do osobnego repo.)

---

# Kontakt / Social
| Platforma | Link |
| :--- | :--- |
| GitHub | https://github.com/Xzar-x |
| YouTube | https://youtube.com/@xzar206 |
| HTB (profil) | https://app.hackthebox.com/profile/1148597 |
| HTB (referral) | https://referral.hackthebox.com/mzy3zVi |

<div align="center">
  [![HTB Profile](https://img.shields.io/badge/HackTheBox-Hacker-blue?style=for-the-badge&logo=hackthebox&logoColor=white)](https://app.hackthebox.com/profile/1148597)
</div>

---

# FAQ / Debug badge'ów (jeśli coś nie działa)
- **404 na SVG** → sprawdź czy workflow o tej nazwie jest w `.github/workflows/` i czy branch to `main`.  
- **Puste miejsce zamiast obrazka** → otwórz URL obrazka bezpośrednio w przeglądarce (np. `https://github.com/Xzar-x/ShadowMap/actions/workflows/ci.yml/badge.svg`) — zobaczysz błąd.  
- **Adblock / privacy** → czasami blokuje shields.io lub GitHub Actions badges — spróbuj incognito.  
- **Repo prywatne** → niektóre widżety mogą się nie renderować publicznie.

---

# Szybkie fragmenty (copy/paste) — jak dodać do innych README
**Badge CI**:
```markdown
![CI](https://github.com/Xzar-x/ShadowMap/actions/workflows/ci.yml/badge.svg)