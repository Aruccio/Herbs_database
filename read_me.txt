ZEBY BAZE WGRAC.
W mudlety tylko.

-> poza arkadiowym folderem zrobic skrypt o tresci:


local url = "https://raw.githubusercontent.com/Aruccio/herbs_database/main/herbs_data.json"
if herbs then
  herbs.data_url = url
end
registerAnonymousEventHandler("scriptsLoaded", function() herbs.data_url = url end, true)



-> restart mudleta


[N] oznacza, ze nie sprawdzilam ziola i jest to, co bylo w starej bazie.
Pytajnik to najpewniej, że wiem, że można to zrobić, ale nie wiem czy to daje taki efekt.



JESLI WYWALI PROFIL
Wywalalo mi profil, jesli byl blad w bazie pod katem skladni. Napisac mi oczywiscie, poprawie najszybciej, jak bede umiala.
Profil wywalony, mam na mysli brak wszystkich okienek, a glowne okno bedzie puste lub bedzie mialo tylko biezaca lokacje.

NAPRAWIC BLAD PROFILU:
W profilu arkadii jest plik herbs_database. Usunac go.
Poza tym jesli nie zdaze naprawic bazy do nowego restartu mudleta przez Ciebie, wylaczyc powyzszy skrypt, zeby pobralo oryginalna baze ze skryptow (coz, ona przynajmniej dziala)
