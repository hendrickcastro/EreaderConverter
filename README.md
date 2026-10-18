# Ereader Converter

Aplicación de escritorio para **Windows y macOS** que organiza tu biblioteca de libros electrónicos, los convierte
entre formatos (EPUB, AZW3, KFX, MOBI, PDF…) y los envía al Kindle.

Este repositorio solo publica los **ejecutables**: descárgalos en [Releases](../../releases/latest).

| Sistema | Archivo |
|---|---|
| Windows 10/11 (64 bits) | `EreaderConverter-<versión>-windows-x64.zip` |
| macOS con Apple Silicon (M1, M2…) | `EreaderConverter-<versión>-macos-arm64.dmg` |
| macOS con Intel | `EreaderConverter-<versión>-macos-x64.dmg` |

## Instalación

**Windows**: descomprime el `.zip` donde quieras y abre `EreaderConverter\EreaderConverter.exe`. La carpeta va
completa: no muevas el `.exe` fuera de ella. Como la app no está firmada, Windows puede avisar la primera vez: pulsa
*Más información › Ejecutar de todas formas*.

**macOS**: abre el `.dmg` y arrastra *EreaderConverter* a *Aplicaciones*. Como no está firmada, la primera vez ábrela
con **clic derecho › Abrir**. Si macOS dice que está dañada, ejecuta en Terminal:

```
xattr -dr com.apple.quarantine /Applications/EreaderConverter.app
```

## Requisitos

- **[Calibre](https://calibre-ebook.com/download)** instalado: es el motor de conversión. La app lo encuentra sola.
- Para **KFX**: los plugins *KFX Output* y *KFX Input* (la app los instala desde *Ajustes › Asistente KFX*) y
  **Kindle Previewer**.
- La versión ejecutable convierte los PDF con Calibre. El motor Docling (IA para PDF) no va incluido.

---

*Ereader Converter* — desktop app for Windows and macOS to manage, convert and send e-books to the Kindle. Download
the installers from [Releases](../../releases/latest). Requires [Calibre](https://calibre-ebook.com/download).
