# Dale POS · Descargas

Repositorio **público sólo de binarios** de Dale POS. El código fuente es privado; acá no hay código, tokens ni datos.

| App | Última versión | Se actualiza desde la app |
| --- | --- | --- |
| Android | [`mobile-latest`](https://github.com/BruninAlv61/dale-pos-releases/releases/tag/mobile-latest) → `Dale-POS-Mobile-Android.apk` | Sí (descarga e instala el APK) |
| iPhone | TestFlight (invitación) o `Dale-POS-Mobile-iOS-sideload.ipa` con Sideloadly/AltStore | TestFlight: sí. Sideload: avisa |
| Windows | [`desktop-latest`](https://github.com/BruninAlv61/dale-pos-releases/releases/tag/desktop-latest) → `Dale-POS-Desktop-Setup-*.exe` | Sí (Setup) · Portable: avisa |
| Linux | `Dale-POS-Desktop-*.AppImage` o `.deb` | AppImage: sí · deb: avisa |
| macOS | `Dale-POS-Desktop-*-mac-arm64.dmg` (Apple Silicon) o `-x64.dmg` (Intel) | Avisa y abre la descarga |

Los canales `mobile-latest` y `desktop-latest` se reemplazan en cada versión; las releases `mobile-vX.Y.Z` y `desktop-vX.Y.Z` quedan como historial con `SHA256SUMS.txt`.

Los workflows de los repositorios privados publican acá con el secreto `RELEASES_TOKEN` (token fine-grained con *Contents: Read and write* sólo sobre este repositorio).
