
# Project 3

Třetí projekt v rámci ENGETO Academy.

# Popis projektu

Projekt slouží k extrahování výsledků z parlamentních voleb z roku 2014. Odkaz [zde](https://volby.cz/pls/ps2017nss/ps3?xjazyk=CZ)




## Instalace knihoven

Veškeré použité knihovny jsou v 
```requirements.txt```. Pro instalaci použijte následující příkazy:

```bash
  $ pip3 install -r requirements.txt
```
    
## Spuštění programu

Spuštění souboru ```main.py``` vyžaduje dva povinné argumenty.
```bash
  python main.py <URL územního celku> <název souboru>
```




## Ukázka projektu

Výsledky hlasování pro okres Prostějov:
```bash
1. argument: https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=12&xnumnuts=7103
2. argument: data.csv
```
```bash
  python main.py "https://volby.cz/pls/ps2017nss/ps32?xjazyk=CZ&xkraj=12&xnumnuts=7103" "data.csv"
```
Částačný výstup:

```bash
Číslo obce,Název obce,Voliči v seznamu,Vydané obálky,...
506761,Alojzov,205,145,29,0,0,9,0,5,17,4,1,1,0,0,18,0,5,32,0,0,6,0,0,1,1,15,0
589268,Bedihošť,834,527,51,0,0,28,1,13,123,2,2,14,1,0,34,0,6,140,0,0,26,0,0,0,0,82,1
589276,Bílovice-Lutotín,431,279,13,0,0,32,0,8,40,1,0,4,0,0,30,0,3,83,0,0,22,0,0,0,1,38,0
...
```
