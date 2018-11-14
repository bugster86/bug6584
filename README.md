Descrizione Role
=========
Modifica il file /opt/reitek/easycim/bin/rm_log_ecas.sh dove esiste.
Cerca all'interno del file .sh se, se esiste già la stringa case insensitive "Form Configurator" non esegue modifiche.
Se non esiste aggiunge una nuova entry path4.

Se esiste già la entry path4 non prosegue ma avvisa l'operatore di rilanciare il playbook con una variabile

.


Requisiti
------------

Variabili
--------------
* path (Nel caso path4 sia già presente può essere specificato)

Dipendenze
------------

Esempio di chiamata
----------------

ansible-playbook /home/playbook/bugs/6584/main.yml

Informazioni Autore
------------------

Martino.Viganò
Martino.Vigano@enghouse.com

![alt text](https://www.panorama.it/wp-content/uploads/2015/01/italiano-medio11-1030x615.jpg)
