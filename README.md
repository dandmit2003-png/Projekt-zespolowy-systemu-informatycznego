## Strona wypożyczenia computerów i laptopów "CompRent"

##Opis projektu
- Сo robi: Strona internetowa zaprojektowana w celu umożliwienia firmom oraz osobom prywatnym wynajmu komputerów dostosowanych do ich potrzeb, wyposażona w funkcje filtrowania ofert, zarządzania zamówieniami oraz obsługi zwrotów.
- Dla kogo jest: Srtona jest skierowana dla wszysktich chętnych
- Jaki problem rozwiązuje: Aplikacja rozwiązuje problem klienta, który potrzebuje szybko i bez zbędnych formalności wypożyczyć laptop na krótki okres, umożliwiając mu samodzielne przeglądanie, filtrowanie, wypożyczenie oraz zwrot sprzętu online z poziomu własnego profilu.

##Sprint plan
Sprint 1 | 10.03 | konfiguracja, baza danych, UI
Sprint 2 | 24.03 | lista laptopów, filtr, logowanie
Sprint 3 | 14.04 | wypożyczenie, profil, zamówienia
Sprint 4 | 28.05 | panel admina, dodawanie produktów

## Skład zespołu
Danylo Melikhov | frontend, logika aplikacji, Github
Kseniia Meshcheninets | koncepcja, testy, dokumentacja

## Technologie
Frontend:
- HTML5
- CSS3
- Netlify drop
Backend:
- Netlify drop
- Visual Studio Code
Baza danych:
- MySQL

## Funkcjonalności
- Rejestracja / logowanie (klient + admin)
- Lista laptopów
- Wyszukiwanie i filtry
- Wypożyczenie i zwrot
- Profil klienta
- Panel admina (dodawanie produktów, zamówienia, logi)
- Zapis danych w localStorage
  
## Architektura
- Aplikacja działa w architekturze klient–serwer:
- Frontend – statyczne pliki (HTML, CSS, JS) hostowane na Netlify Drop (gotowy site)
- Backend – osobna warstwa komunikująca się z MySQL
- Baza danych – MySQL (przechowuje użytkowników, produkty, wypożyczenia, logi)

## Instalacja
1. Sklonuj repozytorium
git clone https://github.com/nazwa/projekt.git
2. Przejdź do katalogu projektu
cd projekt

## Instrukcja użytkownika
1. Otwórz przeglądarkę
2. Przejdź na adres:
http://localhost:3000
3. Utwórz konto
4. Zaloguj się
5. Wybierz pokój i dokonaj rezerwacji

## Struktura projektu
frontend/ – interfejs użytkownika
backend/ – logika aplikacji
docs/ – dokumentacja
tests/ – testy 

## Zrzuty ekranu
![login](docs/login.png)
![dashboard](docs/dashboard.png)

## Status projektu
Projekt ukończony w ramach kursu Projekt Zespołowy Systemu Informatycznych 2026.

## Licencja
Projekt edukacyjny – do użytku wewnętrznego.
