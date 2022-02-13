
# Codebuch,

## Datenerhebung
Instagram, Youtube, Facebook und Twitter der AkteurInnen
https://www.abgeordnetenwatch.de/
https://www.bundestag.de/webarchiv
https://www.bundestag.de/abgeordnete
https://www.fdp.de/person/jens-brandenburg
https://www.franziska-brantner.de/ueber-mich/vita/
https://www.bmwi.de/Redaktion/DE/Dossier/Visitenkarten/Brantner/lebenslauf.html
https://www.toncar.de/
https://www.bundesfinanzministerium.de/Content/DE/Standardartikel/Ministerium/Leitung/Staatssekretaere/florian-toncar.html
https://www.fdp.de/person/florian-toncar
https://xn--schwarzelhr-sutter-u6b.de/
https://www.spdfraktion.de/abgeordnete/schwarzeluehr-sutter
https://www.bmuv.de/ministerium/leitung/rita-schwarzeluehr-sutter/lebenslauf-der-parlamentarischen-staatssekretaerin-rita-schwarzeluehr-sutter
https://www.tobias-lindner.de/
https://www.gruene-bundestag.de/abgeordnete/infos-zur-person/tobias-lindner
https://benjamin-strasser.de/home
https://www.bundestag.de/abgeordnete/biografien/S/strasser_benjamin-858068
https://www.oezdemir.de/
https://www.bmel.de/DE/ministerium/minister/bm-oezdemir.html
https://www.fdp.de/person/michael-theurer


## Nodelist Kodierung,

id ,"AkteurInnen mit Typ 0 werden immer mit den Initialien des Vor- und Nachnamens angegeben, AkteurInnen des Typ 1 mit einer geeigneten Abkuerzung (identisch mit edgelist, aber hier nur einmalige Nennung)"
name_short ,"Nachname bei AkteurInnen des Typ 0, kuerzere Beizeichnung bei AkteurInnen des Typ 1"
name,voller Name bzw. Bezeichnung
type ,"Typ: 0 = Person, 1 = Partei/Organisation/Ort/Verband etc. (Typ 1 beeinhaltet Orte, Ausschuesse, Unternehmen, Ehrenaemter, Parteien, Berufe...)"
sex ,"Geschlecht: 1= weiblich, 2 = maennlich 3=divers"
birth ,Geburtsjahr
position ,"Taetigkeit: StaatssekretaerIn = 1, StaatsministerIn = 2, BundesministerIn = 3"
education ,"hoechster Abschlusss: Diplom = 1, Promotion = 2, juristisches Staatsexamen = 3, Magister Atrium = 4"
subject,"Studienfach: Betriebswirtschaft = 1, Politikwissenschaften = 2, Volkswirtschaft = 3, Rechtswissenschaften = 4, Sozialpaedagogik = 5"
party ,"Parteizugehoerigkeit: Gruene = 1, FDP = 2, SPD = 3"
religion,"Konfessionszugehoerigkeit: roemisch katholisch = 1, evangelisch = 2, muslimisch = 3"
kids,Anzahl der Kinder
twitter ,Anzahl follower auf twitter
instagram,Anzahl follower auf instagram
facebook ,Anzahl follower auf Facebook
youtube ,Anzahl AbonnentInnen auf YouTube


## Edgelist Kodierung,

"- from (id),",Beziehung von einem/r AkteurIn...
- to (id),...zur naechsten AkteurIn
- relationship,Art der Beziehung
1=Ministerium (auch angegliedert als StaatsekretaerIn)
2=politische Funktionen --> auch Eintritt in die Partei
3=Ehrenamt
4=Unternehmen und Aufsichtsräte
5=Stipendien
6=Berufstaetigkeiten
7=Studienort in In- und Ausland
- year ," Jahr, in dem die Variable relationship erhoben wurde"

