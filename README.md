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


code;location;registered;envelopes;valid;Ob�ansk� demokratick� strana;��d n�roda - Vlasteneck� unie;CESTA ODPOV�DN� SPOLE�NOSTI;�esk� str.soci�ln� demokrat.;Radostn� �esko;STAROSTOV� A NEZ�VISL�;Komunistick� str.�ech a Moravy;Strana zelen�ch;ROZUMN�-stop migraci,dikt�t.EU;Strana svobodn�ch ob�an�;Blok proti islam.-Obran.domova;Ob�ansk� demokratick� aliance;�esk� pir�tsk� strana;Referendum o Evropsk� unii;TOP 09;ANO 2011;Dobr� volba 2016;SPR-Republ.str.�sl. M.Sl�dka;K�es�.demokr.unie-�s.str.lid.;�esk� strana n�rodn� soci�ln�;REALIST�;SPORTOVCI;D�lnic.str.soci�ln� spravedl.;Svob.a p�.dem.-T.Okamura (SPD);Strana Pr�v Ob�an�;
506761;Alojzov;205;145;144;29;0;0;9;0;5;17;4;1;1;0;0;18;0;5;32;0;0;6;0;0;1;1;15;0;-;
589268;Bediho��;834;527;524;51;0;0;28;1;13;123;2;2;14;1;0;34;0;6;140;0;0;26;0;0;0;0;82;1;-;
589276;B�lovice-Lutot�n;431;279;275;13;0;0;32;0;8;40;1;0;4;0;0;30;0;3;83;0;0;22;0;0;0;1;38;0;-;
589284;Biskupice;238;132;131;14;0;0;9;0;5;24;2;1;1;0;0;10;2;0;34;0;0;10;0;0;0;0;19;0;-;
589292;Bohuslavice;376;236;236;20;0;0;23;0;3;22;3;4;6;0;1;17;0;4;53;1;1;39;0;0;3;0;36;0;-;
589306;Bous�n;107;67;67;5;0;0;4;0;3;14;0;2;0;0;0;7;0;2;10;0;0;9;0;0;0;0;11;0;-;
589314;Brodek u Konice;695;460;460;25;0;0;32;0;20;47;3;4;5;0;0;38;1;5;144;0;0;60;1;0;1;0;72;2;-;



















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
