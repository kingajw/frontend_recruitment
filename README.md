Zadanie rekrutacyjne frontend
=============================

Utwórz stronę z formularzem, który posłuży do wyszukiwania podręczników szkolnych w księgarni Gdańskiego Wydawnictwa Oświatowego.
Formularz powinien zawierać jedno pole tekstowe do wpisania hasła i przycisk submit.
Skrypt pobierze listę pozycji z API, które jest dostępne pod adresem:

    https://gwo.pl/booksApi/v1/search?query=historia

Każdą książkę pokaż w osobnej ramce i zaprezentuj dane:
* tytuł,
* autorzy,
* ISBN,
* numer dopuszczenia MEN,
* liczba stron,
* poziomy nauczania,
* przedmiot,
* rodzaj publikacji (podręcznik, zeszyt ćwiczeń, materiały dodatkowe),
* okładka.

Dodatkowo wyświetl przycisk "Przejdź do księgarni", linkujący do konkretnej pozycji na stronie gwo.pl.

Pamiętaj, że przekazując parametry do API musisz je zakodować, czyli np. dla frazy "język polski" adres URL wygląda tak:

    https://gwo.pl/booksApi/v1/search?query=j%C4%99zyk%20polski

Będziemy przyznawać punkty za:
1. Poprawną strukturę HTML 5, CSS i JavaScript, formatowanie kodu.
2. Użycie SASS, Bootstrap, Block Element Modifier.
3. Estetykę i ergonomię strony, responsywność: na szerokich ekranach można zmieścić kilka książek obok siebie.
4. Wykorzystanie dodatkowych narzędzi: Gulp, Webpack itp.
