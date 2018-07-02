# Areena
Buutin työntekijöille ja miksei muillekin avoin peliprojekti

## Peli-idea
Yhdistetään tower defence ja Diablo.

Pelialue on suuri areena jonka reunoilta hyökkää vihollisjoukkoja keskelle ja yrittävät hyökätä joko pelaajaan mikäli hän on edessä tai “channelata” voimansa keskellä olevaan timanttiin. Mikäli pelaaja kuolee tai timantin voimat maksimoituvat ennen aallon loppumista niin pelaaja häviää.

Pelaaja ohjaa hahmoaan joita on muutama erilainen (esim. 5) WASD näppäimillä ja käyttää kykyjä numeronäppäimistä. Kykyinä on esimerkiksi vahinkoa tekeviä iskuja, stuneja, knockbackeja tai muuta crowd controllia sekä puolustavia tai liikuttavia kykyjä.

Eri hahmoilla on eri vahvuudet. Osa tekee enemmän vahinkoa mutta ovat vaikeampia pelata ja kuolevat helpommin virheisiin. Hahmoja voi olla esimerkiksi jonkinlainen soturi, jousiampuja, maagi ja rogue tms.

Vihollisia tulee aalloissa. Esimerkkivihollisia voi olla esim soturi, maagi jonka iskuja voi väistää sekä parantaja jonka parantaminen pitää pysäyttää jollain kyvyllä. 

Välillä timantista ilmenee jokin suurempi bossi jonka iskuja pitää väistellä ja sen tuhoamiseen käyttää erilaisia taktiikoita. Bossi saa lisää voimaa mikäli viholliset ovat saaneet channelattua timanttia, jonka takia kannattaa pitää viholliset aisoissa.

Lisäehdotuksia tulevaisuuteen:
- lisää hahmoja
- erilaisia areenoita
- local coop (tai online coop local hostilla) jossa omat bossit ja pelaajien pitää ottaa eri rooleja. esim parantaja, tankki
- heroic mode (vaikea moodi esim. 5 pelaajalle)

## Miten commitoida projektiin (ulkopuolisille)
1. Forkaa projekti
2. Tee oma branchi, vastaten jotenkin nykyistä featurea mitä teet
3. Muutokset tehtyäsi squishaa kaikki committisi interactive rebasella yhdeksi, ja muotoile commit message järkevästi!
   - https://chris.beams.io/posts/git-commit/ tuossa hyvän commit messagen malli. Muista commit messagen bodyssa mainita issue, mitä teet (tyylillä "Fixes #issue")
4. Pull requestaa branchisi masteriin.
