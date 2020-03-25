# CSGO-ARDIONO-LED

Najpierw obejrzyjcie filmik:

https://www.facebook.com/100015282570072/videos/pcb.2913395172069426/829526194233459/

https://www.facebook.com/100015282570072/videos/pcb.2913395172069426/829525980900147/

Witam, jakiś tydzień temu pytałem się czy ktoś nie łączył diod rgb do csgo. Nie było jakiś odpowiedzi które by dały trochę optymistycznej szansy. Ale się nie poddałem i to zrobiłem. Nie jest to jeszcze finalna wersja. Ale zostało już bardzo mało. Jeżeli ktoś ma chęci, czas, umiejętności to może dokończyć, zmienić i wysłać mi na priv, albo w komentarzu. Myślę że niektórzy mogą zrobić coś niesamowitego z tej podstawy. Jeżeli ktoś chce to oddtworzyć to musi zrobić następujące żeczy:

    skopiuj jakikolwiek plik w formacie .cfg z "F:\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg" (możecie mieć inny dysk. np. C albo D.) zmień jego nazwę na "gamestate_integration_v1" a treść jego masz tu: https://pastebin.com/wfnmPXag . I wklejasz ten plik do tego katalogu powyżej. Pamiętaj o odpowiedniej ilości diod i odpowiednim Pinie.

    skopuj ten kod : https://pastebin.com/DhTfsiXN . Do Arduino IDE i załaduj do swojej płytki. (zapamiętaj port COM którego użyłeś)

    Zainstaluj Python 2.7 (ważna jest wersja 2.7 a nie najnowsza) i skompiluj plik z mojego GitHub'a o nazwie CSGoArduino 2.py . (link do GitHub'a https://github.com/SowaKiller/CSGO-ARDIONO-LEDMusicie . Znajdziecie tam wszystkie pliki do ściągnięcia.) Zmień port COM na ten do którego jest podpięta płytka arduino. Musicie też zainstalować moduł do Pythona o nazwie pyserial. (instalkę tego modułu też macie w GitHabie). Możecie też natrafić na problem ze porty są zablokowane wtedy musicie wejść w "Zapora Windows Defender z zabezpieczeniami zaawansowanymi"
    wybrać "reguły przychodzące", "nowa reguła" dalej "program"
    i wybierzcie ścieżkę zainstalowanego Pythona i plik Python.exe ,
    potem "zezwalaj na połączenie", potem zaznaczacie wszystkie możliwe opcje (domowa, publiczna itd) i nazywacie jak chcecie. Robicie to analogicznie dla "reguł wychodzących".

    Uruchom CSGoArduino 2.py, podłącz arduino i włącz csgo.
    Wzorowałem się na tym projekcie https://www.reddit.com/r/GlobalOffensive/comments/4xt9rf/csgo_game_state_integration_arduino_project/ .
    Jeżeli będziecie mieć jakiś problem to proszę pisać na w komentarzach albo w wiadomości prywatnej. Nie krępować się.
