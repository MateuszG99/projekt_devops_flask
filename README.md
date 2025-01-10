
# Projekt Flask + Docker

## Opis projektu
Prosta aplikacja webowa w Flask, z konteneryzacją za pomocą Dockera i konfiguracją CI/CD w GitHub Actions.

## Instrukcja uruchomienia

### Lokalne uruchomienie:
1. Zainstaluj Dockera.
2. W katalogu projektu uruchom:
    ```bash
    docker build -t flask-app .
    docker run -p 5000:5000 flask-app
    ```
3. Otwórz przeglądarkę i przejdź na `http://localhost:5000`.

### CI/CD:
1. Pipeline w `.github/workflows/ci.yml` automatyzuje testowanie i budowę obrazu Dockera.

### Autor:
- Twoje Imię i Nazwisko
