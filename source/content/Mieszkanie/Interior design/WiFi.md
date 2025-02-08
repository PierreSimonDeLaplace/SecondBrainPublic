
>[!warning]
>Dowiedzieć się jaki jest rozmiar skrzynki telekomunikacyjnej i czy router tam wejdzie. Jeśli nie to koniecznie już na etapie uzgadniają szczegółów umowy należy się domagać zamontowania [ONT](https://en.wikipedia.org/wiki/Network_interface_device?wprov=sfti1). Pozwoli to przenieść router w dowolne inne miejsce. Później może być problem aby się doprosić. 

## Double NAT Networks
Podwójny NAT ma miejsce kiedy łączymy jeden router za drugim, który posiada dostęp do ISP. **Tworzymy w ten sposób drugą sieć zamiast rozszerzać to co mamy.** 

## Mesh WiFi
Sieć typu mesh polega na wdrożeniu wielu access pointów w jednej sieci. Pakiety są przekazywane z jednego miejsca w drugie. Minusami takiego rozwiązania jest spadek prędkości nawet do 50% przy każdym przeskoku. Może to być problem przy grach online, czy oglądaniu filmów.

## Wireless Extenders/Repeaters
Łączą to co najgorsze podwójnych NATów i repeaterów. Tworzą one nową sieć plus przesyłają pakiety jedynie do centralnego punktu.

# Co zrobić?
Przewidzieć na razu okablowanie. Jeśli się o tym zapomni na etapie projektowania to koszty drastycznie wzrosną. 

Ewentualnie wykorzystać Mesh korzystając z takich punktów dostępowych:
- [TP-Link Deco X50](https://www.x-kom.pl/p/1049468-system-mesh-wi-fi-tp-link-deco-x50-mesh-wifi-3000mb-s-a-b-g-n-ax-2xap.html#Opinie)
- [Linksys Velop Atlas Pro 6](https://www.x-kom.pl/p/696759-system-mesh-wi-fi-linksys-velop-atlas-pro-6-5400mb-s-a-b-g-n-ax-2xap.html)
- Być może poczekać na WiFi 7

# WiFi 7 (802.11be)
- **Teoretyczna** szybkość 46 Gb/s
- Większa częstotliwość 6GHz
- Większa liczba kanałów (7 zamiast 6 jak w WiFi 6)
- QAM (z 1024 do 4098) - w ramach wiązki radiowej o takiej samej objętości większej liczby sygnałów za pomocą kodowania
- Preamble Puncturing - pozwala na wycięcie fragmentu pasma, wycieszenie na 20 MHz które jest zakłócone. Nie trzeba już szukać innego kanału w razie pojawienia się zakłócenia, co znacznie obniża przepustowość
- Urządzenia będą mogły komunikować się bezpośrednio np. Laptop i TV (router jedynie będzie orkiestrował takie połączenie)
- Hybrid Automatic Repeat Request - jeśli w wyniku zakłócenia dana paczka przyjdzie uszkodzona i po prośbie o ponowne wysłanie paczek to jak znowu przyjdzie jakaś paczka uszkodzona to router sobie powinien poskładać sobie wszystko co potrzebne
- Multilink - będzie pozwalał automatycznie przełączać się pomiędzy 2.4 a 5 GHz

#flat #wifi
