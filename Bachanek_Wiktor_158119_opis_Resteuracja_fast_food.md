# Restauracja fast_food

Do restauracji w losowych momentach czasu wchodzą klienci. Część z nich (ok. 2%) nie robi
zamówienia (klienci, którzy nie zrobili zamówienia mogą - ale nie muszą - skorzystać z łazienki).
Pozostali kupują dania dostępne w menu. Każdy z klientów wybiera losową liczbę dań/napojów.
W menu restauracji znajduje się 6 dań (D1, D2, D3, D4, D5, D6) oraz 3 różne napoje (N1, N2, N3).
Każde z dań ma inną, określoną w menu cenę. Za przygotowanie poszczególnych dań/napojów
odpowiada kucharz. Każde z 6 dań i 3 napojów ma pojemnik mogący pomieścić odpowiednio
maksymalnie od P1 do P6 dań i od P7 do P9 napojów. Kucharz w sposób losowy umieszcza
poszczególne potrawy/napoje w pojemnikach (jeżeli jest wolne miejsce).
Obsługa pobiera przygotowane przez kuchnię dania z pojemników, jeżeli w danym momencie nie ma
konkretnego dania zamówionego przez klienta, obsługa informuje klienta i prosi o wybranie innego
dania/napoju lub rezygnację z zamówienia.
Zasady działania restauracji ustalone przez kierownika są następujące:
− Restauracja jest czynna w godzinach od Tp do Tk;
− W restauracji w danym momencie może przebywać co najwyżej K klientów;
− W restauracji oprócz sali do konsumpcji znajduje się łazienka damska (maksymalnie 3
osoby), męska (maksymalnie 4 osoby) oraz dla osób z ograniczeniami sprawności
(maksymalnie 1 osoba) – z tej ostatniej mogą korzystać również panie lub osoby z dziećmi
do lat 6;
− Z łazienki mogą korzystać bezpłatnie tylko osoby, które zakupiły jakikolwiek posiłek/napój.
Pozostałe osoby za wstęp do łazienki muszą zapłacić w kasie 5,0zł;
− Dzieci w wieku do 6 lat wchodzą do restauracji pod opieką osoby dorosłej. Osoba dorosła
może opiekować się jednocześnie co najwyżej trzema dziećmi w wieku do 6 lat;
− Klienci ustawiają się do zamówienia/kasy;
− Osoby z ograniczeniami sprawności (max. 1% klientów) wchodzą do restauracji bez kolejki;
W restauracji są łącznie 4 kasy. Zasady ich działania przyjęte przez kierownika są następujące:
− Zawsze działają min. 2 stanowiska kasowe;
− Klienci ustawiają się w danej kolejce wg zasady „najkrótszej kolejki”;
− Jeżeli liczba klientów w danej kolejce przekracza 7 osób uruchamiana jest kolejna kasa;
− Jeśli spełniony jest warunek: K / (N-1) < 7, gdzie K oznacza liczbę klientów we wszystkich
kolejkach, N oznacza liczbę czynnych kas, to jedna z kas zostaje zamknięta;
10
− Osoby z ograniczeniami sprawności zamawiają i płacą omijając kolejkę (mniej niż 1%
klientów);
− Kasa przyjmuje zamówienie, ewentualnie przy braku jakiegoś dania komunikuje się z
klientem w celu zmian w zamówieniu oraz na końcu pobiera zapłatę.
Na polecenie kierownika (sygnał 1) obsługa otwiera kolejną kasę.
Na polecenie kierownika (sygnał 2) obsługa zamyka kasę, przy której stoi najmniej klientów, wszyscy
klienci którzy już stali w kolejce muszą być obsłużeni.
Na polecenie kierownika (sygnał 3) wszyscy klienci oraz obsługa natychmiast opuszczają restaurację.
Napisz procedury Kierownik, Obsługa, Kucharz i Klient symulujące działanie restauracji. Raport z
przebiegu symulacji (logi) zapisać w pliku (plikach) tekstowym.
