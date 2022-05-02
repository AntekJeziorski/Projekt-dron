## Opis
Program służy do obsługi dwóch dronów w środowisku trójwymiarowym. Użytkownik ma możliwość wyboru, którym dronem chce sterować. Sterowanie odbywa się poprzez podanie kąta obrotu oraz długości lotu. 
Możliwe jest umieszczanie oraz usuwanie przeszkód na scenie. Podczas lądowania drona sprawdzane jest, czy podłoże pod nim nie posiada żadnych przeszkód.

## Uruchamianie programu
1. Nalezy stworzyc folder "build" jesli nie istnieje i nastepnie zbudowac w nim plik MakeFile przy uzyciu polecenia "cmake ..".
2. Po zbudowaniu pliku MakeFile w folderze build nalezy uzyc polecenia make.
3. Po kompilacji mozna uruchomic program poleceniem ./main bedac w folderze build.

## Dokumentacja
Wygenerowana dokumentacja znajduje sie w pliku "index.html" w folderze dox.

## Testy
Po kompilacji w folderze build mozna uzyc polecenia ./unit_tests -s, aby wykonac testy i sprawdzic poprawnosc dzialania programu.
