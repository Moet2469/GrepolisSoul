# GrepolisSoul
Grepolis Bot 

Bot do grepolis.com

Sprzedaję caly w pelni dzialajacy source bota, gotowy do skonfigutowania i odpalenia, praca jest w 100% autorska i dosyc rozbudowan.

Zawartość Bota :) 

1) Uzupeleninie tokenow logowania podczas 1 uruchomienia. 
2)Automatyczne wczytanie wszystkich miast
-Jeśli podbijesz nowe miasto bot to wykryje i zapyta czy dodać nowe miasto do configu.
-Podczas dodawania miasta do configu, możesz wybrać typ miasta (ogniowe, biremowe, ląd off/deff)
3)Autobudowa ( wszystkie miasta zostaną zakolejkowane według ustalonego typu miasta np. miasto ogniowe port 30 lvl, bot będzie kolejkował te miasto tak aby zbudować je pod wybrany typ miasta)
4)Farmbot (Kapitan) Co 10 minut, działa tylko z wykupionym kapitanem premium.
5)Giełda (Bot automatycznie sprzedaje surowce na giełdzie, z wykupionym captcha resolverem rozwiązuje captche, za każdym razem wysyła na discord powiadomienie o braku xx surowca na xx morzu, również wtedy kiedy wymagana jest captcha)
6)Monitor Ataków, monitoruje wszystkie miasta, również świątnie (na olimpie - wykrywa rodzaj ataku, jeśli płynie kolon wysyła powiadomienie @everyone na kanale discord z informacją)
7)Podczas ataku na miasto automatycznie powołuje oddział
8)Podczas ataku automatycznie rotuje jednostkami w mieście na 4 minuty przed dojściem ataku ( wysyła wojska na wsparcia do najbliższego miasta)
9)Pomocnik Discord (Świetne rozwiązanie do obsługi bota z poziomu telefonu)
-Wywołanie pomocnika na kanale discord !help po tym dostaniemy wiadomość typu 
========================================
        **GrepoSoul DiscordBot - HELP**
========================================
1) !rek <unit> <townId>    – konfiguruje auto‑rekrutację
2) !tak / !nie             – odpowiedź na pytanie o surowce
3) !stoprek <townId>       – zatrzymuje rekrutację
4) !synchro <townId>       – planuje wysyłkę synchro (dalej !atak/!wsparcie …)
5) !kultura                – automatyczne festyny & pochody co 2 h
6) !status                 – podgląd aktywnych procesów
7) !miasta                 – pełna lista miast z budynkami i jednostkami
========================================

-Funkcja 1 automatyczne kolejkowanie miasta, np. miasto o id 3295 to ogniówka, !rek attack_ship 3295
zlecam rekrutację statków ogniowych w danym mieście, bot pyta o to czy wysłać xx ilość surowców z wszystkich dostępnych miast tak aby zrekrutować maksymalną ilość 
statków ogniowych.
-Bot sam odczytuję cene danej jednostki w danej chwili i wysyła wymaganą ilość do tego miasta. 
-Funkcja 4 pozwala nam ustawić synchro atak/wsparcie na dane miasto z możliwością ustawienia marginesu błędu.
-Funkcja 5 tak jak nazwa wskazuje
-Funkcja 6 pokazuje co jest w danym momencie odpalone
-Funkcja 7 pokazuje nam na kanale discord całą listę miast, z poziomami budynków jak i wszystkimi dostępnymi jednostkami w mieście
szczególnie pomocne przy ustawianiu synchro. 

10) Możliwość robienia synchro z poziomu rowniez komputera. 






Sprzedaję cały source do bota, można go rozbudować o wiele innych funkcji, stworzyłem go samodzielnie i tylko ja z niego korzystałem, ale przestałem grać i już raczej nie wrócę także niech projekt żyje swoim życiem. 
Również na zamówienie i dodatkową opłatę mogę go rozbudować o wymagane funkcje.

Film z działania bota mogę podesłać na discord, ew. w przyszłości wrzucę go na YT.
