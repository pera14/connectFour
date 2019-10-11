# ConnectFour :v:
[Lamdawork challenge](https://lambdaworks.io/challenge)

## Pokretanje igre :white_check_mark:
Igrica se jednostavno pokrece otvaranjem `index.html` fajla ili na :point_right:[pera14.github.io](https://pera14.github.io/):point_left:
Prvi igrač se bira nasumicno :game_die:

## Algoritam :mag_right:
CPU engine se zasniva na pretrazi `prvi u širinu` sa limitiranon dubinom u mom slucaju na ukupno :five: poteza u napred (:three: cpu i :two: player):bangbang:. Dodati su ekplicitni slucajevi ukoliko se moze pobediti u prvom potezu ili isključujuci slučajevi kada za odigrani potez player ima otvorenu pobedu tada se taj potez eliminise:x:. Na sličan način su odradjene ostale sitne finese koje ubrzavaju i skraćuju pretragu za željeno polje :bowtie:
