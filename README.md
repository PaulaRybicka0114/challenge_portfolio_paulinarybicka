# challenge_portfolio_paulinarybicka

# TASK 1
### Subtask 1 - wyciągamy karteczki
8/10 punktów :tada:
### Subtask 3 - formatowanie README file w GitHub - dlaczego zdecydowałaś się na udział w challenge_portfolio?
Cześć! Nazywam się Paulina i w 2023 roku zdecydowałam się zmienić w swoim życiu wiele - jednym z tych elementów jest praca. Choć z wykształcenia jestem ~~histeryczką~~ historyczką (:laughing:), to testowanie zainteresowało mnie na tyle, by podjąć to wyzwanie. Na obecnym etapie jestem zupełnym żółtodziobem (do tego stopnia, że ciężko poruszać mi się nawet po GitHubie czy Jirze), ale wiele jest we mnie chęci do nauki i rozwoju! Chciałabym w najbliższym roku stać się odpowiedzialnym i przygotowanym juniorem testowania, by potem coraz lepiej wytykać innym błędy (żart!). Wierzę, że wyzwanie DareIT mi to umożliwi. :blush:
### Subtask 4 - testy eksploatacyjne - poznaj aplikację
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

# TASK 2
### Subtask 1 - pisanie przypadków testowych na podstawie User Story
[Link do mojego zadania numer 1 :seedling:](https://docs.google.com/document/d/1xZzAiv-qPUc-sOcceb53-VZilA6fl0uwffPWm7YxOIE/edit?usp=sharing)
### Subtask 2 - pisanie przypadków testowych na podstawie własnych doświadczeń
[Link do mojego zadania numer 2 :herb:](https://docs.google.com/document/d/1FPu1Hi3YssMdmY61RP9hfx1K_zwJDi-lV-BI50-fq6I/edit?usp=sharing)
### Subtask 3 - po co piszemy test case'y?
![alt text](https://testerzy.pl/assets/img/articles/old/jest-jedna-odpowiedz.jpg)

A tak na poważnie... :mag_right: Tworzenie test case'ów jest moim jednym z najistotniejszych zadań testera oprogramowania. Wymyślanie różnych przypadków testowych nie tylko wzmacnia naszą testerską docierkliwość i kreatywność w wymyślaniu problemów, ale przede wszystkim daje pewność, że w trakcie naszej pracy nie umknęła nam żadna funkcjonalność. Zbiór takich przypadków testowych stanie się później także bazą sporządzanych przez nas raportów testów. Test case'y mówią bardzo wiele o testowanej stronie/aplikacji, wobec czego stanowią również nieocenioną pomoc dla nowych członków zespołu pracującego na danym projekcie, którzy chcą się z nią zapoznać. 

### Subtask 4 - pisanie przypadków testowych na podstawie własnych doświadczeń (aplikacja mobilna PickEatUp)
