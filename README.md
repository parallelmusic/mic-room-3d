# Mic Room 3D

An interactive browser-based tool for visualizing microphone and sound source placement in a 3D room — designed for classical and acoustic recording planning.

Built as a single HTML file, no dependencies, no build step.

## Features

- Four synchronized views: **Top (X/Z)**, **Front (X/Y)**, **Side (Z/Y)**, **Isometric 3D**
- Add any number of **microphones** and **sound sources**
- Drag objects freely in any 2D view to position them on two axes simultaneously
- Set precise **X / Y / Z coordinates** in cm from the properties panel
- Choose **polar pattern** per microphone (cardioid, supercardioid, omni, fig-8, hypercardioid)
- Set **horizontal and vertical orientation** for each microphone
- Real-time **3D distance** display between each mic and each source
- Adjustable **room dimensions** (width, depth, height in cm)

## Usage

Open `index.html` in any modern browser. No server required.

Or visit the live version: **[parallelmusic.github.io/mic-room-3d](https://parallelmusic.github.io/mic-room-3d)**

## Keyboard & Mouse

| Action | Result |
|---|---|
| Drag object in Top view | Move on X/Z |
| Drag object in Front view | Move on X/Y |
| Drag object in Side view | Move on Z/Y |
| Click object in list | Select |
| Edit coordinate fields | Precise positioning |

## License

MIT — see [LICENSE](LICENSE)

## Author

Francesco De Grazia · [byparallel.art](https://byparallel.art)
