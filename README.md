<p align="center">
  <a href="https://github.com/YerraHemanthKumar/My-pokedex-project-hemanth"><img src="C:\Users\q\OneDrive\Desktop\pokedex.png" width="250px"></a>
  
  ![Website](https://img.shields.io/badge/Website-Up-green)
  ![Offline](https://img.shields.io/badge/Offline_Compatible-Yes-yellowgreen)
  ![Installable](https://img.shields.io/badge/Installable-Yes-brightgreen)
  ![Maintenance](https://img.shields.io/badge/Maintained-Yes-green)
  ![GitHub release](https://img.shields.io/badge/Version-1.0-brightgreen)
  ![Made with](https://img.shields.io/badge/Angular-9.1.2-red)
  ![Angular CLI](https://img.shields.io/badge/Angular_CLI-9.1.1-orange)
  ![NPM](https://img.shields.io/badge/NPM-6.14.4-yellow)
  ![Node](https://img.shields.io/badge/Node-13.12.0-blue)
</p>
<p align="center">
   A PWA (Progressive Web App) Built using Angular 9 with Service Workers.
   Works Offline and can be installed.<br>
   Built using the PokéAPI.
  
   <p align="center">Website : <a href="https://hybridshivam.com/pokedex/pokemon</">iamhemantnani@gmail.com</a><br>[For best experience use Chrome or any other Chromium-based browser]</p>
   
# Versions
 **v1.0**
 * 807 Pokemon Species with all alternate forms including Alolan and Megas.
 * Special Mega Evolution Animation for Desktop Clients. (Can be disabled)
 * Abilities.
 * Moves.
 * Evolution Chains.
 * Training, Breeding, Typing and Forms.
 * Flavor Text according to the selected games.
 * *Works Offline.* :heavy_check_mark:
 * *Can be installed.* :heavy_check_mark:

# Getting Started:

**Repo with all the assets : [PokeDex Assets](https://github.com/YerraHemanthKumar/My-pokedex-project-hemanth/)**

**Setting up the environment:**
1. Install Node.js and use `node -v` to check version.
1. IMP Note: You might need to use sudo depending on the npm configuration.
1. Install Angular CLI as `npm install -g @angular/cli`
1. Clone or download this repo.
1. Run `npm install` inside this project folder to install all dependencies.
1. Make sure you use the latest version of the CLI (upgrade guide below)
1. I have set the `serviceWorker` flag to `false` in `angular.json` : So Now there are two ways to start the server: 
  * If `false`
    * Without Service Worker
      1. Run `ng serve` to see the app in action (try `npm start` in case `ng serve` fails).
      1. Connect to app on `localhost:4200`
      (I use `ng serve -o --host 0.0.0.0` so that I can connect to the server via my Mobile device while on the same network and navigating to `<ip-address-of-server>:4200`)
    * With Service Worker
      1. Due to `angular-pwa` this can can only be viewed on production builds so use `ng build --prod --serviceWorker true` , this creates a build in `\dist` directory.
      1. To serve this you'll need http server : `npm install -g http-server`
      1. Run the server using `http-server -c-1 dist\pokedex`

  * If `true`
    * With Service Worker
      1. As service worker is enable here, it can can only be viewed on production builds so use `ng build --prod` , this creates a build in `\dist` directory.
      1. To serve this you'll need http server : `npm install -g http-server`
      1. Run the server using `http-server -c-1 dist\pokedex`

**Upgrading Angular CLI version**
* Run the below commands - use "sudo" only on Mac/ Linux.
1. `sudo npm uninstall -g angular-cli @angular/cli`
1. `npm cache clean --force`
1. `sudo npm install -g @angular/cli`

# Copyright Notice
This is an unofficial, non-commercial, fan-made app and is NOT affiliated, endorsed or supported by Nintendo, Game Freak and The Pokémon Company in any way. Many images used in this app are copyrighted and are supported under fair use. Pokémon and Pokémon character names are trademarks of Nintendo. No copyright infringement intended.

