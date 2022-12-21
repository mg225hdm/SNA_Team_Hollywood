# Codebuch Hollywood
Sessen Araia, Manuela Gieger, Stefanie Lauterbach, Tamina Mack, Laura Merz

# Inhalt

1.Edgeslist.csv

2.Nodelist.csv

# 1. Edge-Attribute

id: Eindeutige Benennung nach Buchstabenkürzel aus Vor- und Nachnamen plus ein Kürzel nach der jeweiligen Akteur:innenfunktion. Bei Filmen erfolgt die Kennzeichnung durch ein
eindeutiges Schlagwort. 

from: Film, von dem die Verbindung ausgeht

to: Akteur:innen, die an dem Film mitgewirkt haben

weight: Rankingplatzierung aufgrund des Kritiker-Rankings
beziehungsweise der Box Office Einnahmen 20 = beste Platzierung (erste
Nennung in den Rankings), 1 = schlechteste Platzierung (letzte Nennung
in den Rankings)

country: Geburtsland/Land des Firmensitzes/Produktionsland

year: Geburtsjahr/Veröffentlichungsjahr/Gründungsjahr

type: d = director, p = producer, s = screenwriter, a = actor/actress, c = composer, pc = production company, dc = distribution company

oscar: Anzahl der gewonnen Academy Awards (Oscars)

golden globe: Anzahl der gewonnen Globen Globes


# 2. Node-Attribute

id:Eindeutige Benennung nach Buchstabenkürzel aus Vor- und Nachnamen plus
Kürzel nach der jeweiligen Akteur:innenfunktion. Bei Filmen erfolgt die Kennzeichnung durch ein
eindeutiges Schlagwort. 

name: Vor- und Nachname der Akteur:innen, Filmtitel, Name der Produktions-/ der
Distributionsfirma. 

type: d = Regisseur:in, p = Produzent:in, s = Drehbuchautor:in, a = Schauspieler:in, c = Komponist:in, pc = Produktionsfirma, dc = Vertriebsgesellschaft

sex: m = männliche Akteure, f = weibliche Akteurinnen, k = Filme d = Produktions- und Distributionsfirmen. 

ranking: Platzierung Film im Kritikerranking

ranking_money: Platzierung Film nach Einnahmen im Box Office Ranking

year: Geburtsjahr/Veröffentlichungsjahr/Gründungsjahr

director: Regisseur:in

producer: Produzent:in

screenplay: Drehbuchautor:in

actor1 - actor3: Schauspieler:in

composer: Komponist:in

production_company1 - production_company4: Produktionsfirma

distribution_company: Vertriebsgesellschaft

box_office: Box-Office-Einnahmen in Milliarden US-Dollar, auf drei
Dezimalstellen nach dem Komma gerundet 

oscar: Anzahl gewonnener Academy Awards (Oscars)

golden_globe: Anzahl gewonnener Golden Globes  
Genre: Genre des Films

year: Geburtsjahr/Veröffentlichungsjahr/Gründungsjahr
