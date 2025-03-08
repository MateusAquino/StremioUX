<h1 align="center">
  <img width="250" src="./logo.png" align="center"></img>
</h1>

<p align="center">🛠️ <strong>StremioUX</strong> is a BetterStremio plugin for patching Stremio's UX quirks.</p>

## 🎉 StremioUX

<p align="left">
  <a target="_blank" href="https://github.com/MateusAquino/WatchParty/assets/16140783/bbe21561-c07a-48ae-9cf0-9613cbde665a">
    <img width="300px" alt="Archer Logo" title="Archer Logo" align="right" src="https://github.com/MateusAquino/WatchParty/assets/16140783/5e986203-361b-4ef8-bd21-69bee97cdfcd"></img>
  </a>
</p>

You must download [BetterStremio](https://github.com/MateusAquino/BetterStremio) to use this plugin. **StremioUX** was developed to fix weird Stremio player behaviours.  

This Plugin works by changing the `#playerTpl` with custom angular instructions plus monkey patching the `playerCtrl`.  

This repository is currently accepting contributions and suggestions, feel free to do so :)

## 🛠️ Quirks

1. Clicking the main video player on Stremio wouldn't play/pause the stream, currently it requires to press the Play button.
2. Player Popups (such as subtitles, volume...) wouldn't stay in the screen for less than a second unless you keep moving your mouse.
