# Doświadczenie: anatomia i proporcje modeli 3D

## Obserwacja użytkownika
W testach tworzenia dorosłej elfki modele AI oddawały pierwsze wersje z nieproporcjonalnymi dłońmi, dziwnym nosem i ustami. Poprawne wykonanie renderu nie gwarantuje poprawności anatomicznej.

## Metoda do weryfikacji
- Pracuj w OBJSmith (folder `Edytor`) — odczytuj i zmieniaj parametry brył bezpośrednio w tekście OBJ (wierzchołki, `# @offset`, `# @pivot`, hierarchia `# @parent`).
- Na tym etapie zbieraj doświadczenie TYLKO z anatomii: które punkty zmieniać i jak oceniać wynik.
- Zapisuj wymiary, współrzędne, jednostki, osie, skalę i proporcje względem całego ciała.
- Zmieniaj pojedynczy parametr lub spójną grupę parametrów; porównuj stan przed i po w tych samych ujęciach.
- Kontroluj wiek, styl i proporcje całej postaci, szczególnie dłonie, twarz i połączenia kończyn.
- Zachowuj udane korekty jako pary danych liczbowych i referencji wizualnych; odnotowuj również nieudane zmiany.
- Buduj bazę sprawdzonych parametrów i wzorców. Nie traktuj nieprzetestowanych liczb jako norm anatomicznych.

## Gdzie najczęściej celować (do potwierdzenia testami)
- Dłonie: długość palców względem dłoni, grubość, pivoty stawów.
- Twarz: nos, usta, oczy — położenie względem osi i proporcje do głowy.
- Połączenia kończyn: barki, łokcie, biodra, kolana (`# @pivot`, `# @offset`).
- Proporcje całości: wysokość w głowach, wiek, styl.

## Format pojedynczego doświadczenia
- Plik OBJ / obiekt (`o Nazwa`) i punkt zmiany:
- Obiekt i zamierzony wygląd:
- Parametry początkowe:
- Zmiana (wartość początkowa, końcowa, jednostka):
- Referencje przed/po:
- Ocena wizualna i pomiary:
- Wniosek oraz zakres zastosowania:
- Status: hipoteza / sprawdzone / zatwierdzone.

Status metody: propozycja oparta na obserwacjach użytkownika; wartości liczbowe i skuteczność wymagają praktycznych testów.
