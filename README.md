# Pixel Perfect · installers

Pixel Perfect compares a Figma frame with the screen your browser actually renders, tells you which differences show, where they come from and how to send them to Jira. Desktop app for Mac, Windows and Linux, in English and Spanish.

Website: **https://usepixelperfect.com**

This repo only hosts the installers. The source code is not here.

*Versión en español más abajo.*

## Download

From [Releases](https://github.com/anthonyjuarezsolis/pixel-perfect-releases/releases/latest), pick the file for your computer:

| computer | file |
| --- | --- |
| Mac with Apple Silicon (M1 and later) | `Pixel-Perfect-<version>-mac-arm64.dmg` |
| Mac with Intel | `Pixel-Perfect-<version>-mac-x64.dmg` |
| Windows (most PCs) | `Pixel-Perfect-<version>-win-x64.exe` |
| Windows on ARM (Surface Pro X, Snapdragon) | `Pixel-Perfect-<version>-win-arm64.exe` |
| Linux | `Pixel-Perfect-<version>-linux-x86_64.AppImage` or `-linux-amd64.deb` |

Every release includes `SHA256SUMS.txt` so you can check the file arrived intact (`shasum -a 256 <file>` on Mac and Linux, `certutil -hashfile <file> SHA256` on Windows).

## Install

**Mac.** Open the `.dmg` and drag Pixel Perfect to Applications. The app is signed and notarized by Apple, so it opens normally.

**Windows.** Run the `.exe`. The installer isn't signed yet, so Windows SmartScreen shows "Windows protected your PC": click **More info → Run anyway**. It installs for your user only and you can choose the folder.

**Linux.** The `.AppImage` doesn't need installing: make it executable (`chmod +x Pixel-Perfect-*.AppImage`) and open it (if it doesn't start, install `libfuse2`). On Debian or Ubuntu you can also run `sudo apt install ./Pixel-Perfect-<version>-linux-amd64.deb`.

The app updates its interface on its own; when a new installer is needed, it shows up here.

---

# Pixel Perfect · instaladores

Pixel Perfect compara un frame de Figma con la pantalla que de verdad se renderiza en el navegador y te dice qué diferencias se ven, de dónde vienen y cómo pasarlas a Jira. App de escritorio para Mac, Windows y Linux, en español e inglés.

Página: **https://usepixelperfect.com**

Este repo solo publica los instaladores. El código no está aquí.

## Descargar

En [Releases](https://github.com/anthonyjuarezsolis/pixel-perfect-releases/releases/latest), el archivo de tu equipo:

| equipo | archivo |
| --- | --- |
| Mac con Apple Silicon (M1 en adelante) | `Pixel-Perfect-<versión>-mac-arm64.dmg` |
| Mac con Intel | `Pixel-Perfect-<versión>-mac-x64.dmg` |
| Windows (la mayoría) | `Pixel-Perfect-<versión>-win-x64.exe` |
| Windows en ARM (Surface Pro X, Snapdragon) | `Pixel-Perfect-<versión>-win-arm64.exe` |
| Linux | `Pixel-Perfect-<versión>-linux-x86_64.AppImage` o `-linux-amd64.deb` |

Cada versión trae `SHA256SUMS.txt` para revisar que el archivo llegó entero (`shasum -a 256 <archivo>` en Mac y Linux, `certutil -hashfile <archivo> SHA256` en Windows).

## Instalar

**Mac.** Abre el `.dmg` y arrastra Pixel Perfect a Aplicaciones. La app está firmada y notarizada por Apple: abre normal.

**Windows.** Ejecuta el `.exe`. Como el instalador todavía no está firmado, Windows SmartScreen muestra «Windows protegió tu PC»: toca **Más información → Ejecutar de todas formas**. Se instala solo para tu usuario y puedes elegir la carpeta.

**Linux.** El `.AppImage` no se instala: dale permiso de ejecución (`chmod +x Pixel-Perfect-*.AppImage`) y ábrelo (si no abre, instala `libfuse2`). En Debian o Ubuntu también sirve `sudo apt install ./Pixel-Perfect-<versión>-linux-amd64.deb`.

La app se actualiza sola en lo visual; cuando haga falta un instalador nuevo, aparece aquí.
