Krótki opis funkcji programu:

Aplikacja stanowi backendowy system zarządzania danymi gier wideo, stworzony z wykorzystaniem ASP.NET Core WebAPI. Główne funkcjonalności obejmują:

-Import danych z plików CSV – administratorzy mogą ładować dane o grach (np. tytuły, sprzedaż, oceny) bezpośrednio z plików CSV.

-Zarządzanie grami – użytkownicy mają dostęp do informacji o grach wideo (wyszukiwanie po ID, tytule itp.), natomiast administratorzy mogą edytować, usuwać lub dodawać nowe rekordy.

-Autoryzacja i logowanie – aplikacja wspiera logowanie przy użyciu tokenów JWT oraz rozróżnia uprawnienia użytkowników i administratorów.

-Architektura warstwowa – system korzysta z wyodrębnionych warstw: ApplicationCore (logika biznesowa, interfejsy), Infrastructure (implementacje), WebAPI (kontrolery, endpointy).

-Wsparcie dla wzorca Repository i Specification – elastyczne filtrowanie danych oraz testowalność komponentów.
