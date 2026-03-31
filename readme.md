Projekt obejmuje pełny cykl wdrażania automatyzacji testów mobilnych, od konfiguracji środowiska po wdrożenie potoku CI/CD.

Blok 01: Środowisko i struktura
Konfiguracja podstawowych narzędzi (Python, Git, Podman/Docker). Przygotowanie struktury katalogów projektu i inicjalizacja repozytorium.

Blok 02: ADB i zarządzanie emulatorem
Praca z Android Debug Bridge (ADB). Zarządzanie urządzeniami wirtualnymi, instalacja pakietów APK oraz inspekcja stanów urządzenia z poziomu terminala.

Blok 03: Docker-Compose i serwer Appium
Konteneryzacja infrastruktury testowej. Uruchomienie serwera Appium przy użyciu Docker-Compose, konfiguracja portów i weryfikacja połączenia.

Blok 04: Inspektor i lokalizatory
Użycie Appium Inspector do analizy hierarchii widoków (UI Tree). Tworzenie stabilnych selektorów (ID, XPath, Accessibility ID) dla elementów aplikacji.

Blok 05: Skrypty automatyczne
Tworzenie pierwszych scenariuszy testowych w Pythonie. Implementacja podstawowych asercji i weryfikacja poprawności przepływów biznesowych.

Blok 06: Page Object Model (POM)
Refaktoryzacja kodu do modelu obiektowego. Rozdzielenie logiki testów od definicji stron (BasePage, MainPage) w celu zwiększenia czytelności i łatwości utrzymania.

Blok 07: Gesty i zarządzanie stanem
Implementacja zaawansowanych interakcji (Swipe, Scroll, Drag & Drop). Zarządzanie synchronizacją za pomocą Explicit Waits oraz obsługa przerwań testu.

Blok 08: Statyczna analiza bezpieczeństwa
Wykorzystanie narzędzia MobSF do audytu plików APK. Identyfikacja luk w zabezpieczeniach, analiza uprawnień i ocena ryzyka (Risk Score).

Blok 09: Testowanie API dla Mobile
Realizacja testów hybrydowych. Integracja biblioteki requests z Appium w celu weryfikacji spójności danych między backendem (API) a frontendem aplikacji.

Blok 10: Raportowanie i automatyzacja (CI/CD)
Wdrożenie pełnego raportowania przy użyciu Allure Report. Stworzenie skryptu pipeline.py automatyzującego cykl: podniesienie kontenerów, egzekucja testów, generowanie raportu i sprzątanie środowiska.
