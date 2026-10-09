# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Menin osassa tehtävistä hieman sekaisin järjestyksestä, esim. tyylit haaran tehdessä en tajunnut siirtyä siihen haaraan ennen muutoksien tallentamista. Jouduin sitten menemään edestakaisin masterin ja tyylit haaran välillä. Tarkastelemalla ohjeistusta siitä kyllä selvisi.

## Osiossa käyttämäni Git-komennot

mkdir demo      # luodaan hakemisto
cd demo         # vaihdetaan uusi hakemisto oletushakemistoksi
git init        # repositorion perustaminen
git clone       # repositorion kopiointi
git status      # git-tilan tarkastelu
git add         # tiedoston lisääminen
git commit      # varsinainen talletus
git commit -m   # talletus + kommentti
git log         # talletuksien listaus
git diff        # muutoksien vertailu viimeisimpään versioon
git rm          # tiedoston poisto hakemistosta ja git-hallinnasta 
git mv          # tiedoston nimeäminen uudelleen tai siirtäminen
git tag         # tunnisteen lisäys talletukseen 
git switch      # haaran vaihto
git branch      # olemassa olevien haarojen katselu
git reset       # add-komennon peruuttaminen
git restore     # tallettamattomien muutosten peruuttaminen
git revert      # kokonaisen talletuksen peruuttaminen
git merge       # haarojen yhdistäminen
--no-ff         # yhdistämistalletuksen pakotus