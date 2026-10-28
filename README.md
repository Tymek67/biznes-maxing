# Kontakt — mapa klientów

Prosta aplikacja do planowania kontaktów z firmami, z mapą i historią rozmów.

Strona: https://tymek67.github.io/biznes-maxing/

## Funkcje

- Firmy na mapie z kolorami statusów i liczbą dni od kontaktu.
- Wskazanie lokalizacji firmy kliknięciem lub przeciągnięciem pinezki.
- Historia rozmów, przypisanie opiekuna i terminy kolejnych kontaktów.
- Lista kontaktów na dziś oraz zaległych.
- Wyszukiwanie i filtrowanie firm.
- Eksport i import kopii bazy w pliku JSON.

## Dane

Firmy i rozmowy w zestawie startowym są fikcyjne. Nowe wpisy są zapisywane
w `localStorage` przeglądarki. Nie ma wspólnej bazy na serwerze ani synchronizacji
między urządzeniami. Każda osoba korzysta z własnej bazy. Wyczyszczenie danych
witryny usuwa lokalny zapis, dlatego warto korzystać z eksportu JSON.

Aplikacja nie wykonuje telefonów i nie wysyła ofert. Wskazanie pinezki zapisuje
współrzędne; wpisanie adresu lub opisu lokalizacji jest opcjonalne.

## Uruchomienie i publikacja

To strona statyczna w HTML, CSS i JavaScript, bez instalacji zależności.
Do lokalnego podglądu udostępnij katalog dowolnym serwerem plików statycznych.

GitHub Pages publikuje pliki z katalogu głównego gałęzi `main`.
Po przesłaniu zmian przez Git strona aktualizuje się automatycznie.

## Wykorzystane zasoby

- Leaflet 1.9.4 — licencja BSD-2-Clause, tekst w `vendor/LICENSE-Leaflet.txt`.
- Mapa i dane: © OpenStreetMap contributors; atrybucja jest widoczna na mapie.
- Fonty z Google Fonts. Załadowanie podkładu mapy i fontów wymaga internetu.
