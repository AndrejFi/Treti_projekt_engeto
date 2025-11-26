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

code	location	registered	envelopes	valid	Občanská demokratická strana
506761	Alojzov	205	145	144	29
589268	Bedihošť	834	527	524	51
589276	Bílovice-Lutotín	431	279	275	13
589284	Biskupice	238	132	131	14
589292	Bohuslavice	376	236	236	20
589306	Bousín	107	67	67	5
589314	Brodek u Konice	695	460	460	25
589322	Brodek u Prostějova	1224	656	655	54
589331	Březsko	178	111	111	9
