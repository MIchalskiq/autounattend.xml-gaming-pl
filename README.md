# autounattend.xml-gaming-pl
Repozytorium zawiera konfigurację i skrypty służące do stworzenia zoptymalizowanej, "odchudzonej" wersji systemu Windows, przygotowanej specjalnie pod kątem maksymalnej wydajności w grach.

---

## 1. Automatyzacja Instalacji (Unattended)
Głównym zadaniem zawartych tu plików jest przeprowadzenie instalacji systemu w sposób niemal bezobsługowy.

* **Wybór języka:** Automatyczne ustawienie języka polskiego (**pl-PL**) dla interfejsu systemu, układu klawiatury oraz formatów regionalnych.
* **Partycjonowanie:** Skrypt konfiguruje strukturę dysku (formatowanie i tworzenie partycji). 
    > ⚠️ **Uwaga:** Proces ten usuwa wszystkie dane z docelowego dysku!
* **Klucz produktu:** Automatyczne pominięcie monitu o klucz lub użycie klucza uniwersalnego do zakończenia instalacji.
* **Konto użytkownika:** Tworzenie **lokalnego konta administratora**, co pozwala na ominięcie wymogu logowania do konta Microsoft (MSA).

---

## 2. Optymalizacja pod Gaming (Wydajność)
Po zakończeniu instalacji, system przechodzi proces "debloat" i tuningu, aby zminimalizować opóźnienia (input lag) i zwiększyć liczbę klatek na sekundę (FPS).

### Kluczowe zmiany:
* **Wyłączenie Telemetrii:** Całkowite zablokowanie usług zbierających dane diagnostyczne, co odciąża procesor i łącze internetowe.
* **Plan Zasilania:** Automatyczna aktywacja schematu **"Wysoka wydajność"** (High Performance), zapobiegająca dławieniu (throttlingu) procesora.
* **Wyłączenie zbędnych usług:**
    * *SysMain* (Superfetch) – redukcja zbędnego zapisu na dysku SSD.
    * *Print Spooler* – wyłączenie obsługi druku (opcjonalnie).
    * *Raportowanie błędów* – oszczędność zasobów systemowych.
* **Game Mode:** Aktywacja systemowego trybu gry, który nadaje priorytet procesom gier nad zadaniami w tle.

---

## 3. Usuwanie Bloatware (Odchudzanie systemu)
System zostaje oczyszczony ze zbędnych aplikacji i funkcji, które spowalniają komputer i zajmują miejsce na dysku.

* **Czyszczenie Start Menu:** Usunięcie preinstalowanych aplikacji (np. Candy Crush, Disney+, aplikacje pogodowe i informacyjne).
* **Zarządzanie przeglądarkami:** Możliwość usunięcia Microsoft Edge lub automatycznej instalacji alternatyw (Chrome/Brave).
* **Odchudzenie interfejsu:** Wyłączenie Cortany oraz integracji wyszukiwarki Bing w Menu Start.

---

## Jak użyć?
1. Pobierz plik `autounattend.xml`.
2. Umieść go w głównym katalogu swojej instalacyjnej pamięci USB z Windows.
3. Uruchom komputer z pendrive'a – instalacja przebiegnie automatycznie
