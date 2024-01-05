### Giga sources:
1. https://data.world/the-pudding?q=&tab=resources
2. https://pudding.cool/process/how-to-make-dope-shit-part-1/
3. https://pudding.cool/process/pivot-continue-down/ - o procesie decydowania co analizowac / wizualizowac
4. https://www.census.gov/dataviz/visualizations/020/

### Data tools etc
1. https://github.com/michalczaplinski/pitchfork - pitchfork review scraper lib
2. zly link xd, pewnie z john w miller - troche jak stworzony zostal ten wrapper do geniusa
3. https://datasetsearch.research.google.com/
4. https://huggingface.co/docs/datasets/index
5. https://www.kaggle.com/datasets
6. https://ourworldindata.org/
7. https://archive.ics.uci.edu/datasets
8.  https://data.world/datasets
9. https://github.com/awesomedata/awesome-public-datasets
10. https://data.fivethirtyeight.com/
11. https://www.dataquest.io/blog/free-datasets-for-projects/
12. https://www.interviewquery.com/p/free-datasets
### 1. Cos zwiazanego z wizualizacja jakiejs popularnosci / sukcesu na swiecie z muzyka albo innym tematem

np.: 
1. https://pudding.cool/2017/03/labels/ - wizualizacja i dane o ilosci hitow roznych hip hop labeli, w tym mapka USA gdzie sa itd, definiowanie wlasnych metrics, np. definicja sukcesu poprzez mnozenie jakichs wlasnosci, dzielenie etc i pokazanie na przestrzeni lat albo wzgledem czegos innego
2. https://pudding.cool/2017/05/nba-moments/ - np wyszukane na tubie filmiki zwiazane z NBA moments i porownana popularnosc w czasie itd, moze dodatkowe informacje jak z czym konkretnie zwiazane (po tytulach) itd
3. https://pudding.cool/2018/09/wiki-billboard/ - wikipedia traffic, generalnie traffic
4. 
### 2. Analizy popkultury, tekstow pisanych etc

np.
1. https://pudding.cool/2017/03/film-dialogue/ - niekoniecznie jak to, ale sam fakt analizy film dialogue czy czegos, pod katem ocenialnych, ilosciowych rzeczy jak ile procentow dialogow kobiety, wystapienie pewnych slow itd
2. https://pudding.cool/2017/03/miles/ - wykorzystanie nie wiem jak jakos api wiki zeby znalezc wspomnienia na wszystkich stronach o milesie, pokazane jak rozklada sie w czasie itd
3. https://pudding.cool/projects/vocabulary/
4. https://pudding.cool/2018/07/women-in-parliament/ - temat w/e, ale sam fakt, ze tak duza ilosc dasnych dostepna z jakichs przemowien itd ciekawe
5. https://pudding.cool/2018/06/skate-music/ - wziecie np soundtrackow z gierek (albo filmow) albo innych rzeczy, z tego tytuly utworow, potem dane o nich ze spotify i inne i porownanie
6. https://www.johnwmillr.com/trucks-and-beer/ - swietne + wykorzystanie ranker.com / billboard do oceny popularnosci etc + eleganckie wizualizacje + ciekawe pytania + kwestia dochodzenia, czy jedno powoduje drugie, czy drugie pierwsze, tzn patrzysz najpierw kto mowi czesciej o X, a potem czy wsrod nich jest wiecej mezczyzn, czy sa jakies correlations itd z roznymi rzeczami, nie bedacymi bezposrednio w danych + wykorzsytanie konceptow jak lyrical diveristy (https://www.nltk.org/book/ch01.html) + czyszczenie danych z unicode problemow / rozbieznosci / wielu form (https://bigishdata.com/2016/10/25/talkin-bout-trucks-beer-and-love-in-country-songs-analyzing-genius-lyrics/)
### 3. Jakies real life stats
np.
1. https://pudding.cool/2017/03/incarceration/ - statystyki o US inmates, jaki procent za co, w jakich latach, publiczne i prywatne prisons, takie bary skladane zeby fajne pokazach procenty zamiast barow obok siebie itd, porownwywanie czsu spedzonego za przestepstwach itd, rozklad na stany
2. https://pudding.cool/2019/04/eu-regions/ - nawet jakies GDP numbers wojewodztw itd w polsce i eu
3. https://pudding.cool/2022/03/weather-map/ - zmiany temperatur itd
4. https://pudding.cool/2018/07/airports/ - airport traffic
5. https://pudding.cool/2018/08/retraining/ - automatyzacja, truck drivers
6. https://public.tableau.com/app/profile/westlake.cjw/viz/HE_Viz/AccesstoHE

### 4. Cos o nastrojach ludzi do rzeczy albo ogolnie sentiment analysis
np.
1. https://pudding.cool/2017/12/hater/ - tutaj fajne, ale apka juz nie istnieje
2. https://pudding.cool/2018/08/emo-rap/ - sentiment analysis na lyrics, inne: https://bigishdata.com/2017/01/14/popular-music-lyrics-have-become-more-negative-over-the-decades/
### Ogolne uwagi, fajne techniki
1. Jesli pokazujesz jakas relacje w czasie itd, GIGA fajne jest jesli dodasz dodatkowo jakies znaczniki z kluczowymi wydarzeniami, markery, zeby dodac kontekstu itd
2. Jesli pokazujesz jakis scatter, to nie tylko masz X i Y, ale tez jesli masz jakies category-based albo o wystarczajacym malym rozstrzale dane, mozesz dodac jako label / kolor - wlasciwie jest to rownowazne wizualizowaniu dwoch (albo wielu) roznych scatterow, dla wielu rownych rzeczy
3. Kolorowanie, colorscale dodawanie do tablic, jesli cos dodatnie, to zielone, ujemne czerwone, albo blizej zakresu jesli jakis jest - proste a giga skuteczne
4. Generalnie grupowania rzeczy, tzn zamiast pojedynczych punkcikow zbierane w bąbelki

#### Insp inne
1. https://pudding.cool/2017/05/song-repetition/ - tutaj wziete song lyrics, ale zaaplikowany do nich jakis algorytm kompresji i porowywane pod wzgledem jego rezultatatow - tak samo jak z **vocabulary hip hip artists**
2. https://pudding.cool/2022/02/women-in-headlines/ - analiza headlines
3. https://www.goodreads.com/api , https://openlibrary.org/ - cos z ksiazkami
4. https://bigishdata.com/2016/11/01/classifying-country-music-songs-is-an-art-getting-training-data/ - stworzenie nowych wlasnych kategorii np. Love dla utworow glownei na tym skupionych itd
5. https://iro.uiowa.edu/esploro/outputs/graduate/Differentiation-between-causes-of-optic-disc/9983776883902771 - cos medycznego, bio etc
##### Inne pojedyncze wizualizacje:
* https://www.reddit.com/r/dataisbeautiful/comments/18dfpnn/oc_wikipedias_most_popular_articles_of_2023/
* https://www.reddit.com/r/dataisbeautiful/comments/18hrpem/2023_in_search_trends_oc/
* https://www.reddit.com/r/dataisbeautiful/comments/18ujwyr/oc_game_of_thrones_imdb_ratings/
* https://www.reddit.com/r/dataisbeautiful/comments/11p3555/oc_size_of_bank_failures_since_2000/
* https://www.reddit.com/r/dataisbeautiful/comments/11e90od/oc_young_adults_are_leading_the_mass_exodus_from/
* https://www.reddit.com/r/dataisbeautiful/comments/11kz20a/japans_population_problem_visualized_oc/
* https://www.reddit.com/r/dataisbeautiful/comments/101hvnv/oc_i_tracked_every_hour_of_my_life_for_5_years/
* https://www.reddit.com/r/dataisbeautiful/comments/12ejldf/oc_the_highs_and_lows_of_popular_comedy_shows/
* 
### Wyklarowane projekty:
1. insp. https://pudding.cool/2018/06/skate-music/ - wziecie np soundtrackow z gierek (albo filmow) albo innych rzeczy, z tego tytuly utworow, potem dane o nich ze spotify i inne i porownanie rozkladu gatunkow, dlugosci, czy sa jacys popularni arysci, kompozytorzy, w czasie, zaleznie od gatunku gierki/filmu etc, moze jakies dane z tytulow, z tych danych spotify czy cechy utworu pasuja do gatunku filmu itd
2. insp. https://www.johnwmillr.com/trucks-and-beer/ - swietne + wykorzystanie ranker.com / billboard do oceny popularnosci etc + eleganckie wizualizacje + ciekawe pytania + kwestia dochodzenia, czy jedno powoduje drugie, czy drugie pierwsze, tzn patrzysz najpierw kto mowi czesciej o X, a potem czy wsrod nich jest wiecej mezczyzn, czy sa jakies correlations itd z roznymi rzeczami, nie bedacymi bezposrednio w danych + wykorzsytanie konceptow jak lyrical diveristy (https://www.nltk.org/book/ch01.html) + czyszczenie danych z unicode problemow / rozbieznosci / wielu form (https://bigishdata.com/2016/10/25/talkin-bout-trucks-beer-and-love-in-country-songs-analyzing-genius-lyrics/) - generalnie cos takiego ale z rap etc albo porownanie gatunkow albo inne
3. jakis sentiment analysis z lyrics
4. insp https://pudding.cool/2017/03/incarceration/ - statystyki o US inmates, jaki procent za co, w jakich latach, publiczne i prywatne prisons, takie bary skladane zeby fajne pokazach procenty zamiast barow obok siebie itd, porownwywanie czsu spedzonego za przestepstwach itd, rozklad na stany - cos o wiezieniach w polsce, na swiecie, stanach, albo cos o GDP albo cos innego o ludziach, krajach
5. https://www.kaggle.com/datasets/joebeachcapital/life-longevity-factors - life longevity factors, moze da sie znalezc wiecej,  moze da sie porownac z happiness factors itd - bo ciekawi mnie temat:
	1. https://www.reddit.com/r/datasets/comments/1829z7g/im_looking_for_a_way_to_find_how_happy_the_100/
	2. https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2021
	3. https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey
	4. https://www.kaggle.com/datasets/unsdsn/world-happiness

### Chcialbym, ale nie wiem jak
1. https://www.kaggle.com/datasets/michalwierzbicki/online-chess-games-11-million-lichess-games - cos z szachami, zagraniami, popularnoscia itd, moze istnieja jakies inne datasety
2. https://www.kaggle.com/datasets/sainitishmitta04/23k-reddit-gaming-comments-with-sentiments-dataset - jakis sentiment analysis ogolnie z komentarzy albo czego innego ludzi
3. https://www.kaggle.com/datasets/joebeachcapital/top-10-million-passwords
4. https://www.kaggle.com/datasets/joebeachcapital/top-10-million-websites-2023 - pop
5. https://www.kaggle.com/datasets/skihikingkevin/csgo-matchmaking-damage?select=esea_master_dmg_demos.part1.csv
6. https://github.com/BetaNYC/Bike-Share-Data-Best-Practices/wiki/Bike-Share-Data-Systems
7. https://www.backblaze.com/cloud-storage/resources/hard-drive-test-data
8. https://github.com/src-d/datasets/tree/master/CommitMessages - super ciekawe, jakas anlzia sentiment, czestoliwosci, dlugosci itd
9. https://github.com/jamesqo/gun-violence-data
10. https://www.kaggle.com/datasets/aayushmishra1512/twitchdata - moze jakby znalezc jakies bardziej comprehensive dane
11. https://datahub.io/collections/stock-market-data, https://www.kaggle.com/datasets/nelgiriyewithana/world-stock-prices-daily-updating
12. https://insights.stackoverflow.com/survey
13. https://datasetsearch.research.google.com/search?src=0&query=jpython%20job%20postings&docid=L2cvMTFxNDY0cWs4Zg%3D%3D
14. https://catalog.data.gov/dataset/crime-data-from-2020-to-present
15. https://catalog.data.gov/dataset/walkability-index1
16. https://catalog.data.gov/dataset/fruit-and-vegetable-prices
17. https://catalog.data.gov/dataset/death-rates-for-suicide-by-sex-race-hispanic-origin-and-age-united-states-020c1
18. https://catalog.data.gov/dataset/diabetes
19. https://catalog.data.gov/dataset/electric-vehicle-population-data
20. https://www.kaggle.com/datasets/salvatorerastelli/spotify-and-youtube
21. https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies
22. https://www.kaggle.com/datasets/googleai/musiccaps
23. https://www.kaggle.com/datasets/adityadesai13/used-car-dataset-ford-and-mercedes
24. https://www.kaggle.com/datasets/tunguz/big-five-personality-test
25. https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023
26. https://www.kaggle.com/datasets/kemical/kickstarter-projects
27. https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset 