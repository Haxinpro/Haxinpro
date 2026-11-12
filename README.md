# Teemu Karne

## Suomeksi

Olen ohjelmistokehittäjä. Teen pääasiassa React/Vite-käyttöliittymiä. Minulle on tärkeää, että projektit on selkeästi rakennettu, helppo julkaista ja ylläpitää. Käytän enimmäkseen Linux-käyttöjärjestelmiä, kuten Debian 13:a ja CachyOS:ää.

Käytän Codexia ja Claude Codea apuna koodin kirjoittamisessa ja tarkistamisessa. Työkalut eivät ylläpidä tai julkaise projektejani omin päin.

### Tämänhetkinen painopiste

- React/Vite-sovellusten kehitys
- Verkkosivujen julkaisu ja CDN-palvelut
- Paikallinen testaus ja julkaisu Dockerilla
- SQLite-tietokannat ja API-integraatiot
- Käyttöliittymien viimeistely, saavutettavuus ja responsiivisuus
- Linux-työpöytäsovellukset Rustilla

### Pääprojektit

#### GameDexia

[![GameDexia homepage](https://raw.githubusercontent.com/Haxinpro/Public/main/gamedexia-homepage.png)](https://www.gamedexia.com/)

GameDexia on julkinen pelikatalogi, jossa voi hakea ja selata pelejä, tarkistaa julkaisutietoja ja suodattaa sisältöä.

Olen keskittynyt projektissa erityisesti julkiseen sivustoon, hakuun, mediasisältöön, suorituskykyyn ja julkaisuympäristöön. Mediatiedostot jaetaan Bunny Storagen ja CDN:n kautta.

- Sivusto: [gamedexia.com](https://www.gamedexia.com/)

#### Sonux

[![Sonux-mikseri](https://raw.githubusercontent.com/Haxinpro/Sonux/main/docs/screenshots/sonux-mixer.png)](https://github.com/Haxinpro/Sonux)

Sonux on laitevalmistajasta riippumaton PipeWire-pohjainen äänireititin ja mikseri Linuxille. Tavoitteena on tehdä sovelluskohtaisesta äänireitityksestä ja äänenkäsittelystä selkeää ja helppokäyttöistä.

Sonuxissa on Game-, Chat-, Media- ja Aux-kanavat sekä omia kanavia, parametrinen taajuuskorjain, mikrofonin äänenkäsittely, OBS:n kanssa toimivat tallennusmiksaukset ja halutessa binauraalinen 7.1-tilaääni.

Sonux on oma oppimisprojektini, ja idea siihen syntyi SteelSeries Sonarin käytöstä. Se on rakennettu [Sink](https://github.com/NC1107/sink)-projektin päälle. Sonux ei ohjaa kuulokkeiden laiteohjelmistoa eikä valmistajakohtaisia ominaisuuksia.

- Lähdekoodi: [github.com/Haxinpro/Sonux](https://github.com/Haxinpro/Sonux)
- Teknologiat: Rust, Tauri, React, TypeScript, PipeWire ja WirePlumber
- Lisenssi: GPL-3.0
- Testattu tällä hetkellä CachyOS-järjestelmässä

#### VTT Dice

[![VTT Dice -selaindemo](https://raw.githubusercontent.com/Haxinpro/VTT-Dice/main/docs/screenshot.webp)](https://haxinpro.github.io/VTT-Dice/)

VTT Dice on 3D-noppasarja virtuaalipöytäpeleihin: d4–d20, prosenttinoppapari ja 100-tahkoinen pallo mustaa marmoria kultaisin numeroin. Mallit on tehty Blenderissä Python-skriptillä, ja selaindemossa noppia heitetään three.js:n ja cannon-es-fysiikkakirjaston avulla.

Heiton tuloksen voi myös päättää etukäteen, esimerkiksi palvelimen tai pelinjohtajan arpomana, ja noppa pysähtyy juuri siihen numeroon. Tein nopat omaan VTT-projektiini ja päätin myös jakaa ne muiden käyttöön.

- Kokeile selaimessa: [haxinpro.github.io/VTT-Dice](https://haxinpro.github.io/VTT-Dice/)
- Lähdekoodi: [github.com/Haxinpro/VTT-Dice](https://github.com/Haxinpro/VTT-Dice)
- Teknologiat: Blender (Python), three.js, cannon-es ja glTF
- Lisenssit: koodi MIT, nopat CC BY 4.0, Blender-skripti GPL-3.0

### Osaaminen

**Frontend:** React, JavaScript, HTML, CSS, responsiiviset käyttöliittymät  
**Backend ja data:** Node.js, SQLite, API-integraatiot  
**Julkaisu:** Docker, Cloudflare Pages, Bunny.net, CDN-asetukset  
**Työkalut:** Git, Codex, Claude  
**Ympäristö:** Linux (Debian 13, CachyOS)  
**Kokeilut:** Blender, riggaus/animaatio, pienet peliprojektit  
**Työpöytä- ja järjestelmäkehitys:** Rust, Tauri, PipeWire, WirePlumber, Linux-äänireititys

### Pienempiä projekteja

- [C# miniprojektit](https://github.com/Haxinpro/Projektini)

### Linkit

- Portfolio: [www.teemukarne.fi](https://www.teemukarne.fi/)
- [LinkedIn](https://www.linkedin.com/in/teemu-karne)

---

## English

I am a software developer focused on React/Vite interfaces, practical deployment workflows, and maintainable project structure. I mainly work in a Debian/Linux environment and use Docker, Cloudflare, Bunny.net, and AI-assisted tooling as part of my development process.

I use Codex and Claude Code to help write and review code. These tools do not maintain or publish my projects on their own.

### Current focus

- React/Vite frontend development
- Public web deployments and CDN workflows
- Docker-based local testing and release flows
- SQLite-backed projects and API integration
- UI polish, accessibility, and responsive layouts
- Rust development (Linux desktop apps)

### Featured projects

#### GameDexia

[![GameDexia homepage](https://raw.githubusercontent.com/Haxinpro/Public/main/gamedexia-homepage.png)](https://www.gamedexia.com/)

GameDexia is a public game catalog for searching and browsing games, checking release information, and filtering content.

My work has focused on the public website, search experience, media handling, performance, and deployment flow. Media is served through Bunny Storage/CDN.

- Live site: [gamedexia.com](https://www.gamedexia.com/)

#### Sonux

[![Sonux mixer](https://raw.githubusercontent.com/Haxinpro/Sonux/main/docs/screenshots/sonux-mixer.png)](https://github.com/Haxinpro/Sonux)

Sonux is a vendor-independent PipeWire audio router and mixer for Linux. Its goal is to make per-application audio routing and processing more visually approachable and simpler to use.

It provides Game, Chat, Media, Aux and custom channels, parametric equalization, microphone processing, OBS-compatible recording mixes, and optional binaural 7.1 spatial audio.

I built Sonux as a personal learning project inspired by the user experience of SteelSeries Sonar. It builds on [Sink](https://github.com/NC1107/sink), whose original work provides the project’s foundation. Sonux does not manage headset firmware or vendor-specific hardware features.

- Source: [github.com/Haxinpro/Sonux](https://github.com/Haxinpro/Sonux)
- Technologies: Rust, Tauri, React, TypeScript, PipeWire, and WirePlumber
- License: GPL-3.0
- Currently tested on CachyOS

#### VTT Dice

[![VTT Dice browser demo](https://raw.githubusercontent.com/Haxinpro/VTT-Dice/main/docs/screenshot.webp)](https://haxinpro.github.io/VTT-Dice/)

VTT Dice is a 3D dice set for virtual tabletops: d4–d20, the percentile pair and a 100-face ball in black marble with gold numbers. The models are generated in Blender with a Python script, and the browser demo throws them with three.js and cannon-es physics.

A throw can also be steered to end on a chosen number, the way a server or game master would decide it. I made the dice for my own VTT project, and they are free for others to use.

- Try it in your browser: [haxinpro.github.io/VTT-Dice](https://haxinpro.github.io/VTT-Dice/)
- Source: [github.com/Haxinpro/VTT-Dice](https://github.com/Haxinpro/VTT-Dice)
- Technologies: Blender (Python), three.js, cannon-es, and glTF
- Licenses: code MIT, dice CC BY 4.0, Blender script GPL-3.0

### Skills

**Frontend:** React, JavaScript, HTML, CSS, responsive UI work  
**Backend and data:** Node.js, SQLite, API integration  
**Deployment:** Docker, Cloudflare Pages, Bunny.net, CDN configuration  
**Tools:** Git, Codex, Claude  
**Environment:** Linux (Debian 13, CachyOS)  
**Experiments:** Blender, rigging/animation, small game projects  
**Desktop and systems:** Rust, Tauri, PipeWire, WirePlumber, Linux audio routing

### Smaller projects

- [C# miniprojects](https://github.com/Haxinpro/Projektini)

### Links

- Portfolio: [www.teemukarne.fi](https://www.teemukarne.fi/)
- [LinkedIn](https://www.linkedin.com/in/teemu-karne)
