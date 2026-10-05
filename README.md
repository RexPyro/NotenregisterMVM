JSON format:


{
  "pdf": "angezeigtpdf.pdf",
  "kategorien": [
  
    {"buchstabe": "A", "name": "Märsche"},
  ],
  
  Bei Stücke kann man nummer mit Buchstabe+Zahl, dann einfach Titel, Komponist.
  Dann Ort mit:
  Schrank: WR - Wandschrank rechts, WL - Wandschrank links, ON- Oberer Notenschrank, UN - Unterer Notenschrank
  Fach: oben, unten, mitte, 1 , 2 , usw. mit zahlen
  pos (für WR/WL): vorne, hinten

  Vollständigkeit:
  status: fehlt, ok, keine_info (standardmäßig)
  falls status = fehlt: detail: beliebiger Text

  Ausgabebereit:
  status: fehlt, ok, keine_info (standardmäßig)
  falls status = fehlt: detail: beliebiger Text

  
  "stuecke": [
  
    {"nr": "A1", "titel": "Alte Kameraden", "komponist": "C. Teike, Arr. Siegfried Rundel", "ort": {"schrank": "WR", "fach": "oben", "pos": "hinten"}, "vollstaendigkeit": {"status": "fehlt", "detail": "2. Klarinette"}, "ausgabebereit": {"status": "fehlt", "detail": "1. Horn, Barisax, Timpani"}},
    {"nr": "A2", "titel": "Neue Kameraden", "komponist": "Mozart, Arr. Siegfried Rundel", "ort": {"schrank": "WL", "fach": "unten", "pos": "vorne"}, "vollstaendigkeit": {"status": "ok"}, "ausgabebereit": {"status": "keine_info"}},
    {"nr": "A3", "titel": "Radetzky-Marsch", "ort": {"schrank": "WL", "fach": "mitte", "pos": "hinten"}},
    {"nr": "A4", "titel": "The Stars and Stripes Forever", "ort": {"schrank": "ON", "fach": 1}},
    {"nr": "A12", "titel": "Preußens Gloria", "ort": {"schrank": "UN", "fach": 5}},
    {"nr": "A44", "titel": "Das Fähnlein der Sieben Aufrechten"},
    {"nr": "B1", "titel": "Die Dichter und Bauern"},
    {"nr": "C2", "titel": "Die Post im Walde"},
    {"nr": "C44", "titel": "Ein Traum von Wien"},
    {"nr": "D1", "titel": "Pomp and Circumstance"},
    {"nr": "E1", "titel": "The Lion King"},
    {"nr": "F1", "titel": "The Rose"},
    {"nr": "G1", "titel": "Großer Gott, wir loben dich"},
    {"nr": "H1", "titel": "Zum Geburtstag viel Glück"}
  ],
  "programm": [
  
    {"nr": 1, "code": "A3"},
    {"nr": 2, "code": "B1"},
    {"nr": 3, "code": "C44"},
    {"nr": 4, "code": "E2"},
    {"nr": 5, "code": "A1"},
    {"nr": 6, "code": "D1"}
  ]
}
