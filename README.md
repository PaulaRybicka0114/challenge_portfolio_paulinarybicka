# challenge_portfolio_paulinarybicka

# TASK 1 - testy eksploracyjne
### Subtask 1 - wyciągamy karteczki
8/10 punktów :tada:
### Subtask 3 - formatowanie README file w GitHub - dlaczego zdecydowałaś się na udział w challenge_portfolio?
Cześć! Nazywam się Paulina i w 2023 roku zdecydowałam się zmienić w swoim życiu wiele - jednym z tych elementów jest praca. Choć z wykształcenia jestem ~~histeryczką~~ historyczką (:laughing:), to testowanie zainteresowało mnie na tyle, by podjąć to wyzwanie. Na obecnym etapie jestem zupełnym żółtodziobem (do tego stopnia, że ciężko poruszać mi się nawet po GitHubie czy Jirze), ale wiele jest we mnie chęci do nauki i rozwoju! Chciałabym w najbliższym roku stać się odpowiedzialnym i przygotowanym juniorem testowania, by potem coraz lepiej wytykać innym błędy (żart!). Wierzę, że wyzwanie DareIT mi to umożliwi. :blush:
### Subtask 4 - testy eksploracyjne - poznaj aplikację
**1. Na czym polega ta aplikacja i do czego służy?**
* aplikacja to swojego rodzaju baza danych na temat poszczególnych piłkarzy - ich imiona i nazwiska, wiek, pozycja, klub, a także raporty z rozegranych meczy
* ma za zadanie pomóc tzw. łowcom talentów w wyszukiwaniu pożądanych zawodników z całego zbioru
* umożliwia także tworzenie nowych profili piłkarzy oraz panelów meczy i raportów

**2. Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a?**
* możliwość zalogowania i wylogowania
* resetowanie hasła
* tworzenie panelu piłkarza i jego edycja
* korzystanie z przeglądarki zawodników
* dodawanie meczów i raportów
* konwertowanie danych do pliku csv i drukowanie zestawień
* zamiana języka z polskiego na angielski i odwrotnie

Ze względu na prostą, wręcz surową budowę strony, funkcjonalności względnie intuicyjne, jednak przez istniejące błędy trzeba się w niektórych przypadkach natrudzić (jak np. tworzenie raportu). Zmieniłabym sam system tworzenia profilu gracza - formularz ogranicza nas w wyborze do ustawienia pochodzenia z konkretnego województwa, a jednocześnie daje możliwość wpisania języka, którym piłkarz się posługuje i przetłumaczenia strony na język angielski. Niejako sugeruje to międzynarodowe potencjalne środowisko. Warto byłoby wobec tego rozbudować stronę o więcej opcji dotyczących pochodzenia, jak np. kraj. Dodatkowo uprościłabym niektóre funkcjonalności, jak np. możliwość wyboru danych odpowiedzi z rozwijalnej listy (jak wspomniane już wcześniej języki).

**3. Oceń interfejs aplikacji (wygląd).**

Jak już wspomniałam, interfejs aplikacji jest bardzo podstawowy. Na panelu głównym, poza jednym obrazkiem symbolizującym platformę (który moim zdaniem znajduje się w złym, nieintuicyjnym miejscu strony) oraz kilkoma ikonami symbolizującymi np. zmianę języka lub przycisk wylogowania, na próżno szukać innych "upiększeń". Strona jest względnie czytelna, jednak nie sposób nazwać jej minimalistyczną - raczej bardzo ubogą. Brakuje tutaj pracy designera, który oprócz praktycznych oczekiwań użytkownika, weźmie pod uwagę także aspekt wizualny.

**4. Czy aplikacja jest intuicyjna?**

Na pierwszy rzut oka wydaje się, że aplikacja jest intucyjna i prosta w obsłudze (ma to także związek z aspektem wizualnym). Jednak im bardziej ponadpodstawowe czynności chcemy wykonać, tym aplikacja traci na przejrzystości.
* Wyszukiwarka - lupka nie jest aktywnym elementem, co może wprowadzić użytkownika w błąd, jedynie enter zatwierdza wprowadzoną frazę wyszukiwania. Wygodnym udogodnieniem byłyby także podpowiedzi wyskakujące już w trakcie wpisywania poszukiwanej frazy
* Sortowanie danych - brak wyraźnej opcji sortowania rosnąco/malejąco, dopiero po kliknięciu w nagłówki pokazuje się ta funkcjonalność
* Brak możliwości eksportowania danych do innego formatu niż csv
* Funkcjonalność "dodaj" dla "mecze i raporty" znajduje się w innym miejscu niż dla "gracze"

**5. Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem?**
* można stworzyć zawodnika z ujemnym wzrostem i wagą (co ciekawe, system podpowiada nam w jakim systemie miar podać wzrost, jednak nie okresla tego przy wadze)
* można stworzyć zawodnika, którego data urodzenia jest dzisiejsza/ z przyszłości
* numer telefonu nie wymaga wpisania cyfr
* podczas uzupełniania danych gracza użycie przycisku "clear" nie wyczyszcza danych, a jedynie cofa wykonaną ostatnią czynność
* formularz nie podpowiada nam jakie dane są błędnie uzupełnione (oprócz podkreślenia konieczności uzupełnienia obowiązkowych danych z gwiazdką). Wobec tego, kiedy wpisałam niewłaściwy format maila (bez @) strona nie podpowiedziała mi tego, tylko uzyskałam komunikat, że nie mogę stworzyć zawodnika
* można wpisać datę meczu z przyszłości
* nie można dodać raportu przez główny przycisk - po kliknięciu w przycisk "dodaj raport", jesteśmy przekierowani na panel z meczami
* można ustawić niestandardowy czas gry, nietypową ilość części meczu
* literówki

### Subtask 5 - Jira
Dołączyłam do zespołu

# TASK 2 - przypadki testowe (test cases)
### Subtask 1 - pisanie przypadków testowych na podstawie User Story
[Link do mojego zadania numer 1 :seedling:](https://docs.google.com/document/d/1xZzAiv-qPUc-sOcceb53-VZilA6fl0uwffPWm7YxOIE/edit?usp=sharing)
### Subtask 2 - pisanie przypadków testowych na podstawie własnych doświadczeń
[Link do mojego zadania numer 2 :herb:](https://docs.google.com/document/d/1FPu1Hi3YssMdmY61RP9hfx1K_zwJDi-lV-BI50-fq6I/edit?usp=sharing)
### Subtask 3 - po co piszemy test case'y?
![alt text](https://testerzy.pl/assets/img/articles/old/jest-jedna-odpowiedz.jpg)

A tak na poważnie... :mag_right: Tworzenie test case'ów jest moim zaniem jednym z najistotniejszych zadań testera oprogramowania. Wymyślanie różnych przypadków testowych nie tylko wzmacnia naszą testerską docierkliwość i kreatywność w wymyślaniu problemów, ale przede wszystkim daje pewność, że w trakcie naszej pracy nie umknęła nam żadna funkcjonalność. Zbiór takich przypadków testowych stanie się później także bazą sporządzanych przez nas raportów testów. Test case'y mówią bardzo wiele o testowanej stronie/aplikacji, wobec czego stanowią również nieocenioną pomoc dla nowych członków zespołu pracującego na danym projekcie, którzy chcą się z nią zapoznać. 

### Subtask 4 - pisanie przypadków testowych na podstawie własnych doświadczeń (aplikacja mobilna PickEatUp)
[Link do mojego zadania numer 4 :four_leaf_clover:](https://docs.google.com/document/d/1ggp4R4D1-amPfFjD827dhJ1Jy-3eLA9R2AbQxq7ZL14/edit?usp=sharing)

# TASK 3 - raportowanie błędów
### Subtask 1 - utworzenie formatki do zgłaszania błędów systemu
[Oto moja formatka! :sunflower:](https://docs.google.com/spreadsheets/d/1NW57GwwUnjMHU6PSPcICeUSy3ALyG7JaiKGPpA1wJE4/edit?usp=sharing)
### Subtask 2 - testowanie według planów testów i raportowanie błędów
Wszystko jest tam :point_up:
### Subtask 3 - raport z wykonanych testów
[Jest i on :muscle:](https://docs.google.com/document/d/1pV_uc5rgfgzhnrVOhAIunLe-NPP7Kt1eJiM27s-mhgY/edit?usp=sharing)
### Subtask 4 - sesja testów eksploracyjnych
[Moim zadaniem jest obsessive-compulsive tour :fire:](https://docs.google.com/spreadsheets/d/18SOzG8UrxqBPdEnDUFCoeiyL4_LCXVI-8x2n0KvR5UQ/edit?usp=sharing)

# TASK 4 - testowanie aplikacji mobilnych
### Subtask 1 - utworzenie formatki do zgłaszania błędów systemu
[Jest i ona! :bowtie:](https://docs.google.com/spreadsheets/d/15tyBRXSrZejbMZvBfMCzaDc_WyZ-M_TNP3H5oGZYQ9A/edit?usp=sharing)
### Subtask 2 - testowanie eksploracyjne i raportowanie błędów
Jak wyżej :arrow_up:
### Subtask 3 - do czego służy ta aplikacja?
**1. Do czego służy ta aplikacja? Jaki jest cel tej aplikacji?**

Aplikacja ta służy przede wszystkim wystawianiu różnych produktów lub usług do sprzedaży/oddania/wymiany. Użytkownicy platformy mogą z niej korzystać będąc “nadawcą” lub “odbiorcą” przedmiotu danej aukcji. Celem aplikacji jest również zarobek, zarówno dla użytkowników, którzy skutecznie zakończyli swoją aukcję sprzedażą; dla użytkowników, którzy zyskali tym jakiś przedmiot/usługę, ale także dla twórców aplikacji, dzięki zyskowi z prowizji sprzedaży.

**2. Kto ma być użytkownikiem końcowym aplikacji?**

Użytkownikiem końcowym aplikacji ma być osoba, która ostatecznie będzie z niej korzystać. Tworząc daną aplikację deweloperzy powinni mieć na uwadze właśnie potrzeby użytkownika końcowego. W przypadku aplikacji OLX będą to osoby, które poszukują dobrej platformy oferującej pośrednictwo w różnego typu transakcjach.

**3. Czy według Ciebie ta aplikacja jest user friendly?**

Aplikacja OLX zasadniczo zaprojektowana jest zgodnie z wytycznymi user friendly. Za przyjazność interfejsu względem użytkownika odpowiada między innymi przejrzysty panel zawierający najważniejsze funkcjonalności, znajdujący się w dolnej części ekranu (w zasięgu kciuka). Łatwo dostępna jest także wyszukiwarka, która znajduje się w oczekiwanym miejscu (górna część ekranu). Aplikacja potrafi generować powiadomienia push, dzięki czemu użytkownik nawet bez wchodzenia w nią, jest w stanie dowiedzieć się o jakiejś zaistniałej akcji. OLX dba także o bezpieczeństwo użytkownika i jego płatności, ofertując użytkownikowi możliwość skorzystania z popularnych metod płatności, jak np. Blik. Aplikacja zawiera w sobie jednak również takie niedociągnięcia, jak brak możliwości użytkowania w trybie offline (choćby wybranych funkcjonalności), czy też brak wyraźnego wsparcia osób niepełnosprawnych (np. wzrokowo, czy słuchowo) w korzystaniu z niej.

**4. Jak byś usprawniła aplikację? Co byś w niej poprawiła? Czy masz jakiś pomysł na dodatkową funkcjonalność?**

Aplikacja, choć dopracowana, nie jest pozbawiona wad. W moim odczuciu niedoskonały jest system szybkiego dodawania danej oferty (bez wchodzenia w nią) do ulubionych. Przycisk serca, który do tego służy jest na tyle mały, że wielokrotnie omyłkowo klikałam minimalnie obok przycisku, co skutkowało wejściem w ofertę. Do aplikacji dodałabym również licznik ofert obserwowanych, gdyż po osiągnięciu puli 150 ofert aplikacja blokuje możliwość dodawania kolejnych. Dodanie licznika pomogłoby użytkownikowi kontrolować tę liczbę. Jak wspomniałam w poprzednim punkcie, rozwinęłabym też w aplikacji szersze wsparcie dla osób niepełnosprawnych, by również swobodnie mogły z niej korzystać

**5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej a natywnej?**

Odniosłam wrażenie, że aplikacja natywna częściej może wywołać bezpośrednią interakcję z urządzeniem, z którego korzystamy. Może się zdarzyć, że odeśle nas bezpośrednio do ustawień urządzenia, czy też poprosi nas o zgodę na wykorzystanie jego zasobów (np. zdjęć). Testując aplikację natywną mamy większą możliwość zbadać jej wpływ i działanie oraz kompatybilność z danym urządzeniem. W statystykach możemy zauważyć jej zasobożerność, zarówno pamięciową, jak i baterii. Testując aplikację internetową zmuszeni jesteśmy korzystać z "pośrednika", którego rolę pełni przeglądarka. Okraja to proces testowania z wspomnianych już procesów i zdecydowanie go spłyca. 

### Subtask 4 - testy aplikacji mobilnej i webowej

[Jira :mortar_board:](https://challengetesting.atlassian.net/jira/software/projects/CTP/boards/1)

![image](https://github.com/PaulaRybicka0114/challenge_portfolio_paulinarybicka/blob/main/T4S4_1.png?raw=true)

![image](https://github.com/PaulaRybicka0114/challenge_portfolio_paulinarybicka/blob/main/T4S4_2.png?raw=true)

![image](https://github.com/PaulaRybicka0114/challenge_portfolio_paulinarybicka/blob/main/T4S4_3.png?raw=true)
