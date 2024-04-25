Instrukcja instalacji i uruchomienia aplikacji
Instalacja zależności
Upewnij się, że masz zainstalowanego Pythona w wersji 3.9 lub nowszej. Możesz pobrać najnowszą wersję Pythona ze strony Python.org.
Sklonuj repozytorium z GitHuba na swój lokalny komputer:
git clone https://github.com/twoje-konto/cw_praca_z_kodem.git

Przejdź do katalogu z projektem:
cd cw_praca_z_kodem

Aktywuj wirtualne środowisko Pythona:
Na systemach Windows:
venv\Scripts\activate


Na systemach Unix/Linux:
source venv/bin/activate


Zainstaluj zależności projektu z pliku requirements.txt za pomocą pip:
pip install -r requirements.txt

Uruchomienie aplikacji
Po zainstalowaniu zależności, możesz uruchomić aplikację za pomocą komendy:
bash
Copy code
python app.py

Aplikacja będzie dostępna pod adresem http://localhost:5000/ w Twojej przeglądarce internetowej.
