# Olympics Project
DA project

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Asma-Zahouani/PB/main?labpath=index.ipynb)

## Ceci est un mini projet 
The modern Olympic Games or Olympics (French: Jeux olympiques[1][2]) are leading international sporting events featuring summer and winter sports competitions in which thousands of athletes from around the world participate in a variety of competitions. The Olympic Games are considered the world's foremost sports competition with more than 200 nations participating.[3] The Olympic Games are held every four years, with the Summer and Winter Games alternating by occurring every four years but two years apart.

Their creation was inspired by the ancient Olympic Games, which were held in Olympia, Greece, from the 8th century BC to the 4th century AD. Baron Pierre de Coubertin founded the International Olympic Committee (IOC) in 1894, leading to the first modern Games in Athens in 1896. The IOC is the governing body of the Olympic Movement, with the Olympic Charter defining its structure and authority.

The evolution of the Olympic Movement during the 20th and 21st centuries has resulted in several changes to the Olympic Games. Some of these adjustments include the creation of the Winter Olympic Games for snow and ice sports, the Paralympic Games for athletes with a disability, the Youth Olympic Games for athletes aged 14 to 18, the five Continental games (Pan American, African, Asian, European, and Pacific), and the World Games for sports that are not contested in the Olympic Games. The Deaflympics and Special Olympics are also endorsed by the IOC. The IOC has had to adapt to a variety of economic, political, and technological advancements. As a result, the Olympics has shifted away from pure amateurism, as envisioned by Coubertin, to allowing participation of professional athletes. The growing importance of mass media created the issue of corporate sponsorship and commercialisation of the Games. World wars led to the cancellation of the 1916, 1940, and 1944 Games. Large boycotts during the Cold War limited participation in the 1980 and 1984 Games. The latter, however, attracted 140 National Olympic Committees, which was a record at the time.[4]

The Olympic Movement consists of international sports federations (IFs), National Olympic Committees (NOCs), and organising committees for each specific Olympic Games. As the decision-making body, the IOC is responsible for choosing the host city for each Games, and organises and funds the Games according to the Olympic Charter. The IOC also determines the Olympic programme, consisting of the sports to be contested at the Games. There are several Olympic rituals and symbols, such as the Olympic flag and torch, as well as the opening and closing ceremonies. Over 13,000 athletes compete at the Summer and Winter Olympic Games in 33 different sports and nearly 400 events. The first, second, and third-place finishers in each event receive Olympic medals: gold, silver, and bronze, respectively.

The Games have grown so much that nearly every nation is now represented. This growth has created numerous challenges and controversies, including boycotts, doping, bribery, and a terrorist attack in 1972. Every two years the Olympics and its media exposure provide unknown athletes with the chance to attain national and sometimes international fame. The Games also constitute an opportunity for the host city and country to showcase themselves to the world.

## :file_folder: dataset
This is a historical data set on the modern Olympic Games,:date: from Athens  1896 to Rio 2016.Each row consists of an individual athlete competing in an Olympic event and which medal was won :

|    |   id | name                     | sex   |   age |   height |   weight | team           | noc   | games       |   year | season   | city      | sport         | event                            | medal   |
|---:|-----:|:-------------------------|:------|------:|---------:|---------:|:---------------|:------|:------------|-------:|:---------|:----------|:--------------|:---------------------------------|:--------|
|  0 |    1 | A Dijiang                | M     |    24 |      180 |       80 | China          | CHN   | 1992 Summer |   1992 | Summer   | Barcelona | Basketball    | Basketball Men's Basketball      | nan     |
|  1 |    2 | A Lamusi                 | M     |    23 |      170 |       60 | China          | CHN   | 2012 Summer |   2012 | Summer   | London    | Judo          | Judo Men's Extra-Lightweight     | nan     |
|  2 |    3 | Gunnar Nielsen Aaby      | M     |    24 |      nan |      nan | Denmark        | DEN   | 1920 Summer |   1920 | Summer   | Antwerpen | Football      | Football Men's Football          | nan     |
|  3 |    4 | Edgar Lindenau Aabye     | M     |    34 |      nan |      nan | Denmark/Sweden | DEN   | 1900 Summer |   1900 | Summer   | Paris     | Tug-Of-War    | Tug-Of-War Men's Tug-Of-War      | Gold    |
|  4 |    5 | Christine Jacoba Aaftink | F     |    21 |      185 |       82 | Netherlands    | NED   | 1988 Winter |   1988 | Winter   | Calgary   | Speed Skating | Speed Skating Women's 500 metres | nan     |

## :dictionnary: Data Dictionary

|Column   |Explanation                   |
| ------- | ---------------------------- |
|id       |Unique number for each athlete |
|name     |Athlete's name                 |
|sex      |M or F                         |
|age      |Age of the athlete                        |
|height   |In centimeters                 |
|weight   |In kilograms                   |
|team     |Team name                      |
|noc      |National Olympic Committee 3   |
|games    |Year and season                |
|year     |Integer                        |
|season   |Summer or Winter               |
|city     |Host city                      |
|sport    |Sport                          |
|event    |Event                          |
|medal    |Gold, Silver, Bronze, or NA    |
