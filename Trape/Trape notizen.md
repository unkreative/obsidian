#trape 
#notizen

# Design, Figma
## wireframe,
wireframe ass dofier do fier ze kukken wat wou hinner kennt an wei et am beschten ausgesait

probleme mit dem design:
-  zu großer text
- nicht erkennbare simbole

nach dem ausbau der verschiedenen seiten, habe ich herausgefunden  dass  ich unnötiges eingeplant habe, 
Mein klient möchte nur  das  sehen was sie auch eingeben

kleng problemer mat alignement, an schaffen mat elementer ass neideg
elementer sinn einfach stecker dei en kann rem benotzen an dei en dann just eng keier muss änneren amplaatz bei all instanz vun dem object
zum beispill eng navbar, dei sollt op all sait sinn an wann en dei lo änneren geif misst en alles eenzel änneren, mee mat elementer kann en et just eng keier änneren an dann ass et iwwerall sou wei en et gäeren hätt

icons ze wielen dei alles sou duerstellen wei en et gäeren hätt, unfanksproble ass dass en user net erkennt wat dat icon heescht an dofier sech net zerechtfennt. icons hunn ech vun bootstrap oder aaner gratis icon saiten. 

Den login beraich ass nach eng baustell, well ech net wees wat ech keint dohinner maan fier d platz opzefellen

muss en nach eng keier alles mei genau maan wei et soll ausgesinn an alles mei spezifesch an final opzesetzen
# anfangen mit dem design, farben etc.
pro entreprise ein set von farben, die man in den einstellungen kann einstellen. 

erste versuche, sehr schlecht, die farben waren viel zu schwer  und  passten ncioht  zusammen

habe dann die farben etwas leichter gemacht und dann war es ungefähr  gut.


# programmieren
so langsam, während dem designen mit  den farben, fange  ich an ein framework zu suchen dass die daten von der database schon für mich importiert, 

warscheinlich werde ich in den ferien mit auf das büro  meines vaters gehen und dort den programmierer fragen wie ich meine database soll aufbauen. 

## databasenstructur

structur mat der hellef vum haer aubertin opgebaut an erweidert. 

-> grouss tabellen mat daten, an dann eng tabell dei d'ids verbennt 
-> connectiounen zweschen sache

ex.
Table Names
| name        | datatype |
| ----------- | -------- |
| id          | int      |
| first_name  | varchar  |
| second_name | varchar  |
|             |          |

Table houses
| name | dataytpe |
| ---- | -------- |
| id   | int      |
| name | varchar  |
|      |          |

Table names.house (connection database)
| name     | dataytpe |
| -------- | -------- |
| id       | int      |
| name_id  | int      |
| house_id | int      |

This is how it would look like:

Table Names
| id  | first_name | second_name |
| --- | ---------- | ----------- |
| 1   | Lou        | Sergonne    |
| 2   | José       | Santos      |
| 3   | Sven       | Bordez      | 

Table houses
| id  | names      |
| --- | ---------- |
| 1   | larochette |

Table names.house
| id  | name_id | house_id |
| --- | ------- | -------- |
| 1   | 1       | 1        |
| 2   | 2       | 1        |
| 3   | 3       | 1        |


php framework: symfony

ungefaangen odcker ze benotzen fier op 3 pcen selwescht schaffen ze kennen

unfank vun docker ass interessant



# mini conclusion
en full stack developer ass hart, well en alles selwer muss maan an en sain eegent team ass, wat och natierlech seng fierdeeler mat sech brengt. et dauert laang eng app ze entweckelen zumools wann en en unfänger ass an nach all d prinzipen leiren an techniken dei en sou unwennt
main standart ass 