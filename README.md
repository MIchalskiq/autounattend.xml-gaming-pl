# 🚀 Gaming-Autounattend.xml

Zautomatyzowany plik odpowiedzi (`autounattend.xml`) dla **Windows 11**, stworzony z myślą o maksymalnej wydajności w grach, prywatności i błyskawicznej konfiguracji systemu po instalacji.

---

## ✨ Główne Funkcje

### 🛠 Automatyzacja instalacji
* **Bypass wymagań systemowych**: Pomija sprawdzanie TPM 2.0, Secure Boot oraz minimalnej ilości RAM.
* **Bypass NRO**: Umożliwia instalację systemu bez wymaganego połączenia z internetem i bez konta Microsoft.
* **Automatyczna nazwa komputera**: System ustawia nazwę hosta na `gamingowiec`.
* **Konfiguracja Wi-Fi**: Automatyczne łączenie z siecią `Orange_Swiatlowod_FF50`.

### 🧹 Optymalizacja (Debloat)
* **Usuwanie zbędnych aplikacji**: Automatycznie odinstalowuje bloatware, w tym: Copilot, OneDrive, Cortana, Teams, Bing Search, Mapy, Pogodę i wiele innych.
* **Wyłączanie telemetrycznych usług**: Blokuje SmartScreen, UAC (User Account Control) oraz usługi zbierania danych.
* **Gaming Tweaks**: Wyłącza zbędne animacje systemowe, aby zminimalizować opóźnienia i odciążyć procesor.

### 📦 Automatyczna instalacja softu (Winget)
Podczas pierwszego logowania system automatycznie pobiera i instaluje:
* **Przeglądarka**: Mozilla Firefox
* **Gry**: Steam, Discord
* **Narzędzia**: 7-Zip, VLC, OBS Studio, LocalSend, Flow-Launcher
* **Produktywność**: Thunderbird, Spotify

### 🎨 Personalizacja
* **Dark Mode**: Wymuszony ciemny motyw systemowy i dla aplikacji.
* **Tapeta**: Automatycznie ustawia ciemną, minimalistyczną tapetę 4K.
* **Skróty na pulpicie**:
    * `Chris_Titus_Tool.bat` - Szybki dostęp do popularnego narzędzia do optymalizacji Windowsa.
    * `Tapety.bat` - Skrypt do pobierania dodatkowych paczek tapet.

---

## 🚀 Jak użyć?

1. Pobierz plik `autounattend.xml` z tego repozytorium.
2. Skopiuj go na pendrive'a z instalatorem Windows 11 (powinien znajdować się w głównym folderze, obok folderów `boot`, `sources` itp.).
3. Uruchom komputer z pendrive'a.
4. Proces instalacji przebiegnie automatycznie, wymagając jedynie interwencji przy wyborze partycji.

---

## ⚠️ Uwaga
* **Bezpieczeństwo**: Plik wyłącza UAC (User Account Control), co ułatwia pracę, ale wymaga większej uwagi od użytkownika.
* **Prywatność**: Wyłączono większość usług śledzących Microsoftu.

---
*Projekt wygenerowany przy użyciu generatora Schneegans i zmodyfikowany pod potrzeby graczy.*
