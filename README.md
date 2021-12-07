# kira - english
KIRA is a PC monitoring script made in Python. It helps schools monitor student activities and help them tackle any inappropriate or illegal activities. It can be used 
by parents as well to monitor their child's activities. KIRA means "Killer" in Japanese. (edgy name!111!!!111)

It uses several modules which might have to be installed. One of them is Colorama, which is just for spicy colors. It can be disabled, however, process might be lenghty.
Requirements for the modules will be in "requirements.txt". You can run ```pip install -r requirements.txt``` in terminal to install the requirements. If it doesn't work, try ```python -m pip install -r requirements.txt```.

How does this work?
This uses the client vs server system. The client is, in KIRA's case, defined as the computer being monitored, while the server is the computer overlooking the client.
The "server.py" script must be installed in the server, while "client.py" in the client. The server runs the server.py script and gets ready for incoming connections. The client has to edit the script to set up the server's local IP address. The client runs the client.py file and connects to the server successfully.

**Do not use this for illegal activities. This only works in local networks.***

# kira - bosanski
KIRA je skripta za pregled aktivnosti računara. Pomaže školama da gledaju aktivnosti učenika i pomaže im da zaustave ikakve protiv-zakonite ili bezobrazne aktivnosti. Roditelji isto mogu koristiti skriptu da gledaju aktivnosti svog djeteta. KIRA znači "ubica" na japanskom. (edži naziv!!!!!!!!!!!!!!!!!!!!!!!!!!!!)

Koristi nekoliko module-a koji se možda trebaju instalirati. Jedan od njih je Colorama, koja se koristi za boje. Može se isključiti, ali isključiti Coloramu će potrajati. Zahtjevi za module će biti u "requirements.txt". U komandnoj prompti možete ukucati ```pip install -r requirements.txt``` da instalirate zahtjeve. Ako to ne radi, probajte ```python -m pip install -r requirements.txt```.

Kako ovo funkcioniše?
Ovo koristi klijenat vs server sistem. Klijenat, u slučaju KIRA skripte, je definiran kao računar kojem se gledaju aktivnosti, dok je server računar koji gleda aktivnosti klijenta. "server.py" mora biti instaliran u serveru, dok "client.py" mora biti instaliran u klijentu. Server će uključiti server.py skriptu i sprema se za konekcije. Klijenat mora editovati skriptu da postavi serverovu lokalnu IP adresu. Klijenat pokrene client.py fajl i konekta se na server.

**Ne koristiti ovo za ilegalne aktivnosti. Ovo samo radi u lokalnim mrežama.**
