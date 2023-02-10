# Analiza_glownych_skladowych_i_analiza_skupien_dla_danych_z_2018_r._dotyczacych_panstw_UE


## Wprowadzenie

#### Celem projektu jest analiza danych dotyczących zgonów na poszczególne nowotwory oraz wybranych wskaźników w celu dostrzeżenia pewnych zależności, związków i ich podobieństw między państwami Unii Europejskiej i Szwajcarii. Jedynym państwem będącym w UE i jednocześnie niebędącym w zbiorze danych jest Malta, ponieważ miała zbyt duże braki w danych, które uniemożliwiły eksplorację. Utworzony zbiór zawiera 27 obserwacji i 16 kolumn. Źródłami danych wykorzystanych w projekcie są bazy Our World in data, The World Bank, Eurostat, WHO oraz raport “Human Development Report 2019”, United Nations Development Programme. Wybrano dane dotyczące 2018 roku.

## Wiecej o zmiennych

### Zmienne wykorzystane w analizach:

country - nazwy państw w UE;

lung - liczba zgonów z powodu nowotworów tchawicy, oskrzeli i płuc na 10 000 osób;

colon - liczba zgonów z powodu nowotworów jelita grubego i odbytu na 10 000 osób;

breast - liczba zgonów z powodu nowotworu piersi na 10 000 osób;

leukemia - liczba zgonów z powodu białaczki na 10 000 osób;

air_pollution_exposure - wskaźnik narażenia na pył zawieszony w aglomeracjach;

hdi - wskaźnik rozwoju społecznego;

tobacco - procent osób powyżej 15. roku życia używających wyrobów tytoniowych;

deaths_drugs - liczba zgonów spowodowanych uzależnieniem od narkotyków na 10 000 osób;

### Zmienne nie będące wskaźnikami zostały przeliczone tak, aby oddawały stosunek do populacji, tj. na potrzeby poprawnego porównania danych oraz lepszego przyswojenia wartości w kolumnach najpierw wyrażono je w ujęciu per capita, a następnie przemnożono je przez 10 000 mieszkańców.

### Odrzucono zmienne najmniej skorelowane z innymi, tak, aby zmienne poddane dalszym analizom spełniały odpowiednie kryteria.

### Zmienne odrzucone:

doctors - liczba lekarzy na 10 000 osób;

alcohol_liters - ilość spożywanego alkoholu w litrach przypadająca na osobę (powyżej 15. roku życia);

suicide_rate - liczba samobójstw na 10 000 osób;

deaths_alcohol - liczba zgonów spowodowanych uzależnieniem od alkoholu na 10 000 osób;

liver - liczba zgonów z powodu nowotworu wątroby na 10 000 osób;

stomach - liczba zgonów z powodu nowotworu żołądka na 10 000 osób;

population - liczba ludności; zmiennej użyto jedynie do przeliczenia pozostałych zmiennych.

## Linki do danych

<https://data.worldbank.org/indicator/SP.POP.TOTL>

<https://ourworldindata.org/how-many-people-in-the-world-die-from-cancer>

<https://ec.europa.eu/eurostat/databrowser/view/sdg_11_50/default/table?lang=en>

<https://hdr.undp.org/sites/default/files/hdr_2019_overview_-_english.pdf>

<https://data.worldbank.org/indicator/SH.PRV.SMOK?end=2018&start=2018>

<https://ourworldindata.org/drug-use>

<https://www.who.int/data/gho/data/indicators/indicator-details/GHO/medical-doctors-(per-10-000-population>

<https://data.worldbank.org/indicator/SH.ALC.PCAP.LI>

<https://data.worldbank.org/indicator/SH.STA.SUIC.P5>
