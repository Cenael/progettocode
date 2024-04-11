 ## Comandi GIT 
 **_Comandi iniziali_**

- git config --global user.name "tuo nome" : Imposta il nome utente
- git config --global user.email "tua email" : Imposta indirizzo email utente
- git init: Inizializzazione nuova Repository
- git clone url_repository: Clona Repository già esistente nella directory locale


- git add nome_file: aggiunge un file all'area di staging.
- git add . : Aggiunge tutti i file modificati all'area di staging.


- git commit -m "Messaggio" : Esegue un commit con un messaggio descrittivo.

- git remote: Mostra elenco dei repository remoti collegati
- git push -u (nome remoto) (nome ramo): Carica un ramo su un repository
- git pull (nome remoto) (nome ramo): Scarica e fonde un ramo da un repository remoto


- git status: Mostra lo stato del repository
- git log: Cronologia dei commit

**_Branch_**

- git branch: Elenco dei branch presenti
- git branch (nome branch) : Crea un nuovo branch
- git branch -d (nome branch): elimina il branch
- git checkout (nome branch): Cambia/sposta branch
- git checkout -b (nome branch): Crea un nuovo ramo (e passa automaticamente

- git merge (nome branch): Esegue il merge (unione) di un branch nel branch corrente.

