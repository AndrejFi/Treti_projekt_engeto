# Treti_projekt_engeto
tento soubor slouží k extrahování volebních dat

**Instalace knihoven**
Knihovny využity v tomto scriptu jsou uloženy v requirements.txt. Pro instalaci se doporučuje použít virtuální prostředí a následující příkaz.
- pip install -r requirements.txt

**Spuštění projektu**
Pro spuštění main.py použijte následující terminálový příkaz
- python main.py "odkaz územního celku" <jméno-souboru.csv>

**Ukázka projektu**
1. argument - https://www.volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=12&xnumnuts=7103
2. argument - vysledky_prostejov.csv

Příklad spuštění

python main.py "https://www.volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=12&xnumnuts=7103" vysledky_prostejov.csv
Výsledkem spuštění je stáhnutí souboru vysledky_prostejov.csv


Průběh stahování
Kontrola vstupních parametrů - OK
Načtení obcí - OK
Přehled kandidujících stran - OK
Data za jednotlivé obce - OK


Částečný výstup csv výstup
<img width="1070" height="304" alt="Snímek obrazovky (17)" src="https://github.com/user-attachments/assets/faf9d59a-03d1-478e-89e5-b615a705dff2" />

částečný výstup csv v excel podobě
<img width="1920" height="467" alt="Snímek obrazovky (19)" src="https://github.com/user-attachments/assets/8cd30434-3c85-4569-8f0c-649c183a0bcd" />

