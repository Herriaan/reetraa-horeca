# Reetraa Horeca Beheer - Website

Overkoepelende one-page website voor **Reetraa Horeca Beheer**, een holding met vijf horecazaken in Breda en Eindhoven.

**Live**: https://herriaan.github.io/reetraa-horeca/

## Venues

| Concept | Type | Locatie |
|---|---|---|
| Shots Breda | Shooterbar | Vismarktstraat 24, Breda |
| Shots Eindhoven | Shooterbar | Stratumseind 43, Eindhoven |
| Feestcafe De Dokter | Feestcafe | Havermarkt 27, Breda |
| IJssalon Maystro | IJssalon | Molenplein, Breda + Made |
| CrossRover | Mobiele DJ-booth | Heel Nederland |

## Tech stack

- Single-file HTML/CSS/JS (`index.html`)
- Fonts: Syne (headings), DM Sans (body), Caveat (accenten) via Google Fonts
- Hosting: GitHub Pages (deploy vanuit `main` branch)
- Geen build tools, frameworks of dependencies

## Secties

1. **Hero** - Logo, tagline, floating venue foto's, animated reveal
2. **Over ons** - Beschrijving + animated counter stats (5 concepten, 2 steden, 180+ shots, sinds '16)
3. **Photo strip** - Hover-to-expand fotobalk
4. **Venues** - Vijf venue blocks met logo, beschrijving, locatie en link naar eigen website
5. **Vacatures** - Sollicitatie CTA (blauwe gradient sectie)
6. **Contact** - Contactgegevens + Google Maps embed
7. **Footer** - KVK-nummer, copyright

## Lokaal draaien

Geen build nodig. Open `index.html` in een browser, of serveer met een lokale server:

```bash
python3 -m http.server 8000
# Open http://localhost:8000
```

## Deploy

Push naar `main` branch. GitHub Pages publiceert automatisch.

## Structuur

```
reetraa-horeca/
  index.html              # Volledige website (HTML + CSS + JS)
  assets/
    img/
      logo.png            # Reetraa logo (header + hero)
      logo-original.png   # Origineel logo
      logo-shots.png      # Shots venue logo
      logo-dokter.png     # De Dokter venue logo
      logo-maystro.png    # Maystro venue logo
      logo-crossrover.png # CrossRover venue logo
      hero-bar.jpg        # Hero achtergrond
      shots-*.jpg         # Shots foto's
      dokter-*.jpg        # De Dokter foto's
      maystro-*.webp      # Maystro foto's
      crossrover-*.jpg    # CrossRover foto's
      ...                 # Sfeer- en stockfoto's
```
