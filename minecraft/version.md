---
icon: versions
---

# ZMIANA WERSJI SERWERA
!!!warning
Pamiętaj, podczas zmiany wersji serwera upewnij się, że wybrałeś/Aś odpowiednią wersję Javy, w celu dokonania zmiany oprogramowania Javy przejdź, do zakładki "Startup" z rozwijanej listy Docker Image wybierz docelową wersję, która cię interesuje.
!!!

### SPOSÓB 1 - ZMIANA WERSJI SERWERA POPRZEZ PANEL
By zainstalować wersję serwera użyjemy dostępnego w naszym panelu instalatora wersji, z którego możesz również skorzystać udając się pod adres [https://cpanel.endhost.eu](https://cpanel.endhost.eu/)/ następnie po zalogowaniu należy wybrać serwer, na którym zostanie przeprowadzona instalacja.
![](/static/minecraft/s1.png)
Po wskazaniu właściwego dla nas serwera, udajemy się do zakładki VERSIONS wybierając interesującą nas wersję z dostępnej listy postanowiliśmy dokonać instalację wersji PURPUR 1.20.1 należy jednak pamiętać, że decyzja zależy od was, zachęcamy do zapoznania się z listą oferowanych wersji gry.

![](/static/minecraft/s2.png)
Po wyborze odpowiedniej wersji do instalacji, należy nacisnąć przycisk INSTALL, po którego wciśnięciu system spyta się nas, czy jesteśmy pewni, że chcemy dokonać tej właśnie instalacji gry, przypomni nam również, że działanie to spowoduje usunięcie wszystkich dotychczasowych plików serwera jeśli więc nie mamy nic przeciwko, naciskamy przycisk INSTALL.

![](/static/minecraft/s3.png)
Gotowe, prawidłowo przeprowadziliśmy proces instalacji nowej wersji serwera.
### SPOSÓB 2 - INSTALACJA PRZY UŻYCIU KLIENTA SFTP
Ten poradnik dotyczy instalacji wersji serwerowej z wykorzystaniem aplikacji WINSCP, jednakże jeśli nie posiadasz zainstalowanej aplikacji WINSCP na komputerze to do instalacji możesz się posłużyć dowolnie wybranym klientem SFTP, jak chociażby FILEZILLA etc.

Po wyborze odpowiedniego programu, za pomocą którego będziemy mogli rozpocząć instalację wersji serwerowej, przystępujemy do wybrania odpowiedniego silnika oraz jego pobrania na komputer, naszym wyborem będzie silnik VELOCITY.

Silnik został wybrany, zatem należy go pobrać poprzez przejście pod adres https://papermc.io/downloads/velocity. Skoro został pobrany to, wypadałoby go również dodać na serwer, przechodzimy więc do klienta SFTP po czym logujemy się przy pomocy danych znajdujących się w panelu klienta zakładka SETTINGS.

![](/static/minecraft/s4.png)
![](/static/minecraft/s5.png)
Gdy zalogujemy się do klienta SFTP, zostanie nam wyświetlony pusty folder, to właśnie do niego przerzucamy pobraną wcześniej wersję serwera.
!!!warning
Należy pamiętać, że do poprawnego działania serwera niezbędna będzie zmiana domyślnej nazwy silnika na server.jar lub zmiany nazwy w zakładce startup w polu "SERVER JAR FILE", w przeciwnym wypadku nie zostanie on uruchomiony, a co więcej, ekran konsoli wyświetli błąd z tym związany.
!!!
!!!success
Gotowe! Instalacja nowej wersji dobiegła końca, a po ponownym uruchomieniu będzie można cieszyć się nowym oprogramowaniem serwerowym.
!!!
