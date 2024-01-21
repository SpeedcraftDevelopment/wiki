---
icon: plug
---
# INSTALACJA PLUGINÓW
### SPOSÓB 1 - INSTALCJA JEDYM KLIKNIĘCIEM
Do instalacji możemy posłużyć się wbudowanym instalatorem wtyczek, aby, tego dokonać wystarczy, udać się do panelu zarządzania serwerem znajdującego się pod adresem [https://cpanel.endhost.eu/](https://cpanel.endhost.eu/) następnie po zalogowaniu wybieramy serwer, na którym chcemy zainstalować dodatek.

![](/static/minecraft/infoserwer.png)

Gdy już wybierzemy odpowiedni serwer, przechodzimy do zakładki Plugin Manager i wybieramy wtyczkę, która zostanie zainstalowana na serwerze, naszym wyborem będzie plugin o nazwie LuckPerms, dodający na serwer rangi, uprawnienia itd.

![](/static/minecraft/pluginmanager.png)

Wtyczka została wybrana, możemy więc przystąpić do jej instalacji, aby ją zainstalować, naciskamy zielony przycisk Install, jeżeli wtyczka zainstalowała się poprawnie to wówczas zielony przycisk zamieni się w kolor czerwony z napisem Uninstall.

![](/static/minecraft/pluginmanager2.png)

!!!success
Udało się! Dodatek jest już aktywny, pozostaje jedynie ponownie uruchomić serwer.
!!!

## SPOSÓB 2 - INSTALACJA MANUALNA

!!!info
Podczas ręcznej instalacji należy pobrać wtyczkę za pośrednictwem zewnętrznej witryny.
!!!

Przechodzimy przykładowo na stronę [spigotmc.org](https://www.spigotmc.org/resources/), by wyszukać interesującą nas wtyczkę. Nasz wybór padł na plugin SuperVanish.

![](/static/minecraft/pluginspigot.png)

Po dokonaniu wyboru wtyczki pora na jej instalację wykonujemy to w następujący sposób obok nazwy wtyczki wciskamy przycisk Download Now następnie należy poczekać aż wtyczka zostanie pobrana na nasz komputer, jeżeli plugin się zainstaluje, przechodzimy bezpośrednio do panelu i wybieramy, na jakim serwerze chcemy umieścić nasz dodatek.

![](/static/minecraft/infoserwer.png)

 #### Instalowanie z wykorzystaniem Menadżera plików.
Po zalogowaniu na konto użytkownika przechodzimy do katalogu Files i klikamy na folder plugins.

![](/static/minecraft/pluginmanager.png)

Po naciśnięciu przycisku Upload pojawi się menu służące do wyboru dodatku, który zamierzamy wgrać na serwer.

![](/static/minecraft/okienko.png)

!!!success
Udało się! Dodatek jest już aktywny, pozostaje jedynie ponownie uruchomić serwer.
!!!

![](/static/minecraft/listaploginow.png)

  #### Instalacja przy pomocy klienta SFTP zainstalowanego na komputerze.
  
  Dla celów tego poradnika posłużymy się narzędziem WINSCP, można użyć również innego oprogramowania, niekoniecznie wspomnianego powyżej.

Po uruchomieniu programu ukaże się ekran z prośbą o podanie danych logowania do klienta SFTP.

![](/static/minecraft/ftp.png)

Protokół SFTP pozostawiamy bez zmian. Nazwa hosta, Nazwa użytkownika oraz Hasło znajdują się w panelu zakładka "Settings".

![](/static/minecraft/detailssftp.png)

Po zalogowaniu się przechodzimy do katalogu plugins.

![](/static/minecraft/katalog.png)

Teraz pozostało nam wgranie pluginu przy pomocy programu WINSCP wykonujemy to następująco przechodzimy do ścieżki pobrane na komputerze bądź innej, w której znajduje się plugin i przenosimy plik .jar do programu w katalogu o nazwie plugins.

![](/static/minecraft/katalog2.png)

!!!success
Udało się! Dodatek jest już aktywny, pozostaje jedynie ponownie uruchomić serwer.
!!!
