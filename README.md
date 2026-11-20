# Rezka — Client Releases

Официальный репозиторий публичных релизов нативных клиентов **Rezka** для Android, Android TV, iOS / iPadOS, macOS и Windows.

## 🚀 Актуальный релиз: [v1.0.22](https://github.com/Proletarochka/HdRezka-Releases/releases/tag/v1.0.22) (2026-11-20)

## 📥 Скачать свежие версии

Прямые ссылки на актуальный стабильный релиз:

| Платформа | Устройство | Файл установки | Формат | Размер |
|---|---|---|---|---|
| **Android TV** | Телевизоры и приставки (Google TV / Android TV) | [rezka-tv-release.apk](https://github.com/Proletarochka/HdRezka-Releases/releases/latest/download/rezka-tv-release.apk) | APK | 69.6 МБ |
| **Android Mobile** | Смартфоны на Android | [rezka-mobile-release.apk](https://github.com/Proletarochka/HdRezka-Releases/releases/latest/download/rezka-mobile-release.apk) | APK | 69.5 МБ |
| **Android Tablet** | Планшеты на Android | [rezka-tablet-release.apk](https://github.com/Proletarochka/HdRezka-Releases/releases/latest/download/rezka-tablet-release.apk) | APK | 69.5 МБ |
| **Apple iOS / iPadOS** | iPhone и iPad (SideStore / AltStore / TrollStore) | [Rezka.ipa](https://github.com/Proletarochka/HdRezka-Releases/releases/latest/download/Rezka.ipa) | IPA | 31.3 МБ |
| **macOS (Apple Silicon)** | Mac на чипах M1 и новее | [rezka-desktop-arm64.dmg](https://github.com/Proletarochka/HdRezka-Releases/releases/latest/download/rezka-desktop-arm64.dmg) | DMG | 154.4 МБ |
| **macOS (Intel)** | Mac на процессорах Intel x86_64 (без торрентов) | [rezka-desktop-x64.dmg](https://github.com/Proletarochka/HdRezka-Releases/releases/latest/download/rezka-desktop-x64.dmg) | DMG | 151.0 МБ |
| **Windows** | ПК на Windows (x64) | [rezka-desktop-x64.msi](https://github.com/Proletarochka/HdRezka-Releases/releases/latest/download/rezka-desktop-x64.msi) | MSI | 138.3 МБ |

## 📝 Примечания по установке

- **macOS:** приложение не подписано: после переноса `Rezka.app` в `/Applications` разрешите запуск через «Системные настройки → Конфиденциальность и безопасность → Открыть в любом случае» (либо выполните в Терминале `xattr -cr /Applications/Rezka.app`). В сборке для Intel (`x64`) отсутствует торрент-движок (`libtorrent4j-macos` доступен только для Apple Silicon).
- **iOS / iPadOS (SideStore / AltStore):** источник репозитория для автообновлений:
  `https://raw.githubusercontent.com/Proletarochka/HdRezka-Releases/main/altstore-source.json`

---

## 🔄 Автообновление (In-App & Obtainium)

- **API последнего релиза:**  
  `https://api.github.com/repos/Proletarochka/HdRezka-Releases/releases/latest`
- **Для Obtainium на Android TV и смартфонах:**  
  Добавьте URL `https://github.com/Proletarochka/HdRezka-Releases` в качестве источника приложений для автоматической фоновой проверки и установки обновлений.
- **Встроенное автообновление:**  
  Поддерживается в клиентах Android, Android TV, macOS и Windows через GitHub Releases API.
