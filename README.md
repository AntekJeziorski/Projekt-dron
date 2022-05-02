## Opis
Program służy do obsługi dwóch dronów w środowisku trójwymiarowym. Użytkownik ma możliwość wyboru, którym dronem chce sterować. Sterowanie odbywa się poprzez podanie kąta obrotu oraz długości lotu. 
Możliwe jest umieszczanie oraz usuwanie przeszkód na scenie. Podczas lądowania drona sprawdzane jest, czy podłoże pod nim nie posiada żadnych przeszkód.

## Uruchamianie programu
1. Należy stworzyć folder "build" jeśli nie istnieje i następnie zbudować w nim plik MakeFile przy użyciu polecenia "cmake ..".
2. Po zbudowaniu pliku MakeFile w folderze build należy użyć polecenia make.
3. Po kompilacji można uruchomić program poleceniem ./main bedąc w folderze build.

## Dokumentacja
Wygenerowana dokumentacja znajduje się w pliku "index.html" w folderze dox.

## Testy
Po kompilacji w folderze build można użyć polecenia ./unit_tests -s, aby wykonac testy i sprawdzić poprawność działania programu.
