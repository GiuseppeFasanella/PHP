# PHP
I concetti fondamentali da capire sono:

* Se scrivi un file .html e ci clicchi sopra, il browser lo aprira' e lo legge
* Se scrivi un codice .php in linea di principio il browser non sapra' cosa fare. 

Questo perche' **la logica del php e' questa**:
* Gli script php sono processati dal server che li traduce in file html standard leggibili dal browser (Il PHP e' un linguaggio di scripting **server side**)
* Percio', se vuoi imitare cio' che fa il server:
* Installa php: sudo apt-get install php5-cli
* Imita cio' che fa il server: `php myfile.php > myfile.html; firefox myfile.hmtl`

Capito come funziona, passiamo alla **soluzione pratica** (guarditi i video tutorial)
* Installa (in locale) il server Apache
* Installa php sul server Apache

Al che, l'utente root avra' una cartella **/var/www** all'interno della quale puoi mettere i tuoi file .html e .php

Se ora, nel browser scrivi l'indirizzo `localhost/file` accedi da browser ai tuoi file

Il modo migliore per imparare il PHP e' **partire da un esempio**.

L'obiettivo e': `Voglio passare informazioni tramite browser e farne qualcosa`

* Si parte con un **file .html** (per la sintassi [html] (https://github.com/GiuseppeFasanella/html_snippets_codes) vedi qui) `enteringinfo.html` e' un wrapper. un supporto grafico che avvolge lo script in php

* enteringinfo.html chiama **learn.php** che processa le informazioni passate tramite l'html di prima
* learn.php e' commentato bene qui dove commento un po' la sintassi
