# bar-board
Papieren stamkaarten zijn verleden tijd, hier is Bar Bord!

Gebruik Bar Bord om leiding te laten betalen voor drank, snacks, etc.

### Beschikbaarheid
Voorlopig is Bar Bord enkel beschikbaar voor MacOS, maar we zouden deze ook graag uitbrengen voor Windows.

Wil je Bar Bord eigenhandig omzetten als Windows programma? Volg de stappen hieronder:

#### 1. Installatie
- Controleer of Node.js geïnstalleerd is
  - Open Commandoprompt en plak de volgende code ```node -v```
  - Als Node.js niet geïnstalleer is download deze dan via https://nodejs.org/en/
  - Volg de stappen die op het scherm 
- Installeer NPM ```npm install npm@latest -g```
- Installeer Electron Forge ```npm i -g @electron-forge/cli```

#### 2. Omzetting
- Sleep de folder die je gedownload hebt naar het icoontje van command prompt
- Plak het volgende in de commandprompt ```electron-forge make```

Er zal in de map die je gedownload hebt een nieuwe folder gemaakt worden genaamd 'Out', hier vind je de nieuwe applicatie in.