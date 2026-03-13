Platziere hier deine App-Icon-Dateien (z. B. `icon.png`, `ic_launcher.png`).

Empfehlungen:
- Android: Verwende `flutter_launcher_icons` oder lade verschiedene Größen in `android/app/src/main/res/mipmap-*/`.
- iOS/macOS: Füge Assets in Xcode Asset Catalog hinzu (`AppIcon.appiconset`).

So bindest du Icons in Flutter ein (Beispiel `pubspec.yaml`-Eintrag):

flutter:
  assets:
    - assets/icons/

Dieses Verzeichnis enthält nur eine `.gitkeep`-Datei, damit Git den Ordner verfolgt.
