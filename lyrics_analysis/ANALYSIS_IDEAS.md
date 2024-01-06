# What do you actually want to analyze?

Currently have most popular 200 songs (10 artists x 20 songs) from rap artists downloaded

Could maybe download lyrics for artists of other genres such as rock, pop, soul, ...

for rock - think typical - tenacious d probably not a good general representation etc:

- QOTSA
- nirvana
- Foo fighters
- the strokes
- the white stripes
- led zeppelin
- fugazi
- the rolling stones
- black sabbath
- deep purple

for pop:

- taylor swift
- dua lipa
- carly rae jepsen
- michael jackson
- jessie ware
- charlie xcx
- olivia rodrigo .. 7
- beyonce
- aaliyah
- britney spears

for soul:
- stevie wonder
- marvin gaye
- curtis mayfield
- otis redding
- aretha franklin
- al green
- nina simone ..7
- sam cooke
- clarence carter
- minnie riperton

### Once we have this data:

1. we could choose certain words from imagination, such as 'love', 'money', 'shoot', 'bitch', 'drugs'
2. or better yet - topical groups of words:
    1. firstly by some artificial groupings, eg:
        * for 'love':
            * 'love', 'lover', 'honey', 'babygirl', 'shorty'
        * for 'money':
            * 'money', 'cash', 'bill', 'bills', 'stack', 'dolla', 'ca$h', 'checks', 'bags', 'bag'
        * for 'violence':
            * 'shoot', 'kill', 'kills', 'victim', 'whack', 'murder', 'gun', 'rob', 'robbin', 'steal', 'stole', 'whacked', 'killed', 'shot', 'robbed'
        * for 'cops etc':
            * 'cops', 'opps', 'opp', 'dog', 'pig', 'pigs', 'copper', ''
        * for 'drugs':
            * 'drugs', 'weed', 'kush', 'mary jane', 'perc', 'cocaine', 'molly', ''
        * for 'bitch':
            * 'bitch', 'bitches', 'whore', 'skank', 'tramp'
    2. somehow utilize word embeddings / vectors that could help with identifying word relations / closely related words, eg. start with 'love' and count words with vectors within a short distance

3. then make comparisons between artists, genres, years etc. How? Specifically:
    * save counts for every word / group for every songs
    * summary for every artist
    * summary for every genre
    * maybe an additional count in how many of artists / genres songs the word ocurred
    * PER YEAR within genre
    * PER YEAR within everything
    * maybe something with months

4. Use the year data for something
5. Use the pageviews data for something
6. Maybe try to get count of ['writer_artists'] and/or ['producer_artists'], ['featured_artists'], ['']

7. Try to get named entity recognition counts from lyrics
8. Maybe try to get counts of parts of speech, eg whether some artists use more verbs, nouns etc
9. Data like 'male' and 'female' would have to be included manually? or if we could find some altrnative source of data like wiki - then compare the above things grouped by gender
10. try to get some sentiment classification? agression, sadness etc - then you could compare those stats plus compare eg. if a song has many mentions of X is it more/less likely to be sad or w/e
11. compare correlations between word / word group ocurrences. Eg if 'love' is mentioned are other things likely to be mentioned as well
12. find some outliers
13. maybe some word vector / embedding visualizations - how big is the overlap
14. jakos inaczej pokazanie overlapu albo braku - **jak**
15. moze jakos porownanie typowej dlugosci zdan? Ale wtedy musialbym nie usuwac z tekstow newlines i co wtedy zliczac? slowa? odzielone spacja? moze
16. porowannie word diversity:
    * pomiedzy artystami
    * pomiedzy gatunkami
    * latami
    - jaka dokladnie metoda? jest to w jakiejs bibliotece?
17. wordcloudy - wiadomka
18. wspomniane juz - analiza tone, main topic, sentiment - zarowno klasyfikacja, jak i np zliczanie "pozytywnych" i "negatywnych" slow
19. moze znalezienie jakichs popularnych kombinacji slow, phrases
20. 'the frequency of a word or phrase in a text or corpus, its distribution, central tendency, and dispersion, correlation, co-occurrence, or collocation'
21. 'relationship between two or more words or phrases in a text or corpus (e.g. using t-tests, chi-square tests, or ANOVA)'
22. **vocabulary counts** per artist, genre, year (how is it different from diversity?)
23. generally distributions - counts of songs with words etc, histograms

