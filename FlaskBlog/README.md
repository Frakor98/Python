# Prosty Blog w Flasku

To repozytorium zawiera projekt prostego bloga internetowego napisanego w języku Python z wykorzystaniem frameworku Flask.

## Opis projektu

Prosty blog w Flasku pozwala na dodawanie postów, edycję istniejących postów oraz usuwanie ich. Strona główna wyświetla wszystkie dostępne posty, a po kliknięciu na dany post, można przeczytać jego pełną treść.

## Instalacja

Aby zainstalować projekt na swoim komputerze, wykonaj poniższe kroki:

1. Sklonuj repozytorium:
    ```
    git clone https://github.com/user/repo.git
    ```
2. Wejdź do folderu z projektem:
    ```
    cd repo
    ```
3. Zainstaluj wymagane biblioteki:
    ```
    pip install -r requirements.txt
    ```
4. Uruchom serwer:
    ```
    python app.py
    ```
5. Przejdź do strony `http://localhost:5000/` w przeglądarce internetowej.

## Struktura projektu


- `app.py` - plik zawierający logikę aplikacji
- `blog.db` - baza danych SQLite
- `models.py` - plik zawierający definicję modelu posta
- `static` - folder zawierający pliki statyczne (arkusze stylów CSS, grafiki itp.)
- `templates` - folder zawierający szablony HTML

## Autor

Projekt został stworzony przez Jan Kowalski. Możesz skontaktować się ze mną drogą mailową pod adresem jan.kowalski@gmail.com lub odwiedzić moją stronę internetową [www.jankowalski.com](http://www.jankowalski.com).

Dziękuję za zainteresowanie projektem!
