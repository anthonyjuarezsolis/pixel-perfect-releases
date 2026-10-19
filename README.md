# Pixel Perfect · instaladores

Pixel Perfect compara un frame de Figma con la pantalla que de verdad se renderiza en el navegador y te dice qué diferencias se ven, de dónde vienen y cómo pasarlas a Jira. App de escritorio para Mac, Windows y Linux, en español e inglés.

Página: **https://pixel-perfect-site.web.app** (pronto con dominio propio).

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

Cada release trae `SHA256SUMS.txt` para revisar que el archivo llegó entero (`shasum -a 256 <archivo>` en Mac y Linux, `certutil -hashfile <archivo> SHA256` en Windows).

## Instalar

**Mac.** Abre el `.dmg` y arrastra Pixel Perfect a Aplicaciones. Mientras la app no esté firmada por Apple, la primera vez macOS dice que no puede comprobar el desarrollador: haz **clic derecho → Abrir** y confirma. Si no aparece la opción, ve a Ajustes del Sistema → Privacidad y seguridad → «Abrir igualmente». Después abre normal.

**Windows.** Ejecuta el `.exe`. Como el instalador no está firmado, Windows SmartScreen muestra «Windows protegió tu PC»: toca **Más información → Ejecutar de todas formas**. Se instala solo para tu usuario y puedes elegir la carpeta.

**Linux.** El `.AppImage` no se instala: dale permiso de ejecución (`chmod +x Pixel-Perfect-*.AppImage`) y ábrelo (si no abre, instala `libfuse2`). En Debian o Ubuntu también sirve `sudo apt install ./Pixel-Perfect-<versión>-linux-amd64.deb`.

La app se actualiza sola en lo visual; cuando haga falta un instalador nuevo, aparece aquí.

---

## English

Pixel Perfect compares a Figma frame with the screen your browser actually renders, tells you which differences show, where they come from and how to send them to Jira. Desktop app for Mac, Windows and Linux, in English and Spanish. Website: https://pixel-perfect-site.web.app. This repo only hosts the installers.

- **Mac:** open the `.dmg` and drag the app to Applications. Until the app is signed by Apple, the first time **right-click → Open** and confirm (or System Settings → Privacy & Security → «Open Anyway»).
- **Windows:** run the `.exe` (`win-x64` for most PCs, `win-arm64` for ARM). SmartScreen will warn because the installer isn't signed: **More info → Run anyway**.
- **Linux:** `chmod +x` the `.AppImage` and run it, or `sudo apt install ./<file>.deb`.
- Check downloads against `SHA256SUMS.txt` in each release.
