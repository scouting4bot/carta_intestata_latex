
![License](https://img.shields.io/badge/status-work%20in%20progress-red) ![License](https://img.shields.io/badge/version-0.1.0-yellow) ![License](https://img.shields.io/github/languages/top/scouting4bot/carta_intestata_latex)

*Il progetto è ancora in fase di sviluppo (versione alpha). Per ora non consiglio l'uso.
Per maggiori dettagli si veda il paragrafo sugli Sviluppi.*

# Carta Intestata LaTeX
Progetto basato sulla carta intestata dell'associazione scout [CNGEI](https://cngei.it/).
> Tutta l'immagine coordinata in un unico file, con la comodità di LaTeX

## Immagini e GIF
**Questo paragrafo non è ancora completo!**

# Indice
- [Multilanguage](#multilanguage)
- [Come iniziare](#come-iniziare)
- [Segnalazione bug e richieste](#segnalazione-bug-e-richieste-di-aiuto)
- [Come contribuire](#come-contribuire)
- [Licenza](#licenza)
- [Sviluppi futuri](#sviluppi-futuri)

## Multilanguage
Not available. The usage of this project is reserved to members of an italian scout association.

# Come iniziare
## Prerequisiti
- un editor LaTeX sul computer locale od online (es. https://www.overleaf.com/).
- conoscenza minima del LaTeX.

## Configurare Overleaf
Overleaf è un sito che fornisce un editor intuitivo per latex.
 1. **scarica il progetto da git**:
    -  puoi fare un clone del progetto se hai dimestichezza con git (non è difficile, online trovi facilmente le istruzioni).
    -  in alternativa scarica lo zip con tutto:
       1. clicca il pulsante `Code` e seleziona `Download ZIP`.
       2. decomprimi il file zip dove ti è più comodo
       3. entra nella cartella "carta_intestata_latex-main" creata: qui troverai una serie di file e cartelle come descritte nel paragrafo sulla [struttura del progetto](#struttura-del-progetto) (immagini, fon, main.tex, readme).
   2. **importa su Overleaf**: vai su overleaf https://www.overleaf.com/project
       -  se hai premium, puoi scaricare il progetto direttamente da GitHub cliccando sul pulsante `New Project` e selezionando dal menù a tendina `Import from GitHub` [per dettagli rimando alle istruzioni di Overleaf](https://it.overleaf.com/learn/how-to/How_do_I_connect_an_Overleaf_project_with_a_repo_on_GitHub,_GitLab_or_BitBucket%3F).
       -  in alternativa puoi importare a mano.
          1. clicca sul pulsante `New Project`.
          2. dal menù a tendina seleziona `blanck project` (progetto vuoto).
          3. nel campo vuoto inserisci un nome per identificare il progetto (es. *carta intestata*).
          4. clicca il pulsante `Create`.
          5. ora sei nella schermata di lavoro. A sinistra c'è un'area che ti descrive il tavolo di lavoro con tutti i file disponibili. Tra i pulsanti in cima clicca quello con la freccia rivolta verso l'alto (Upload).
          6. trascina i file che hai spacchettato precedentemente dallo ZIP scaricato da GitHub.
          7. se ti segnala conflitti, seleziona la sovrascrittura.
          8. attendi che sia eseguito il comando.
          9. verifica l'organizzazione dei file: devono essere strutturati in cartelle come descritto in [struttura del progetto](#struttura-del-progetto). In caso di incongruenze puoi riorganizzarli creando le cartelle a mano con i pulsanti in cima al tavolo di lavoro.
   3. **configura Overleaf**: in alto a sinistra clicca il pulsante `Menu` e cambia il compilatore a `XeLaTeX`.
   4. **compila il progetto**
          1. nel tavolo di lavoro a sinistra seleziona il file `main.tex`.
          2. nell'area centrale vedrai il testo modificabile.
          3. in cima all'area a destra puoi cliccare il pulsante `Recompile` per compilare il file `main.tex`.
          4. una volta finito, overleaf ti visualizzerà un pdf di anteprima nell'area di destra.
   5. **personalizza il file d'esempio**: se vuoi creare una circolare personalizzata, puoi fare le seguenti modifiche
          1. ***barra laterale informativa***: a *riga 75* cambia `brancae` con il nome del file immagine che contiene le tue informazioni. Se non è disponibile, puoi crearlo e metterlo nella cartella `images`.
          2. ***testo della circolare***: a *riga 105* sostituisci `\lipsum[1-19]` con il tuo testo. Mi raccomando *non rimuovere* `\end{document}` perché serve a LaTeX per chiudere il corpo del testo.
          3. se vorrai vedere delle anteprime del tuo testo, ricordati di cliccare `Recompile`.
    

## Come installare
**Questo paragrafo non è ancora completo!**

## Documentazione
Per dettagli sulla immagine coordinata e la carta intestata del CNGEI, si rimanda alla documentazione disponibile nel [cloud associativo](https://cloud.cngei.it/index.php/apps/files/?dir=/Settori/Settore%20Comunicazione/KIT%20-%20Immagine%20COORDINATA&fileid=1901575).

---
# Come contribuire

## Installare le dipendenze di sviluppo
Nessuna dipendenza è richiesta oltre all'editor LaTeX scelto dallo sviluppatore.

## Struttura del progetto
Una descrizione schematica del progetto:
```
.
├── MontserratFontFiles   # cartella con i file per l'uso del font Montserrat
├── images                # cartella con le immagini
├── main.tex              # File tex in cui configurare la lettera con l'intestazione
├── LICENSE
└── README.md
```	

## Community
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](https://www.contributor-covenant.org/version/2/0/code_of_conduct/code_of_conduct.md)

Scourting4bot ha uno spazio su [Slack](https://slack.com), ad oggi poco attivo.

### Segnalazione bug e richieste di aiuto
Se noti malfunzionamenti, puoi segnalarli usando lo strumento `Issue` di GitHub. Non temere di segnalare errori o suggerire nuovi sviluppi: ogni issue è un passo avanti verso un prodotto migliore.

### Semantic Versioning
Per il versionamento si cerca di seguire la modalità [Semantic Versioning](https://semver.org/).

## Manutenzione 
Attualmente il progetto è in sviluppo.

---
# Licenza 
* Ogni logo ed il formato della carta intestata è di proprietà del [CNGEI](https://cngei.it/).
* Il font Montserrat è utilizzato secondo [SIL Open Font License](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)
* Il resto del codice (main.text) è di `Scouting4Bot e tutti i contributori` ma può essere liberamente usato da chiunque, per ruolo od incarico, abbia il diritto d'uso della carta intestata dell'associazione (dirigenti, educatori, branche, settori, gruppi di lavoro, etc).

## Licenze software dei componenti di terze parti
L'analisi è stata eseguita con [FOSSA](https://fossa.com/pricing/). 

# Sviluppi futuri
 - **versione 0.1.0**
   - [x] ~~readme~~
     - [x] ~~struttura~~
     - [x] [~~badges](https://shields.io/)~~
     - [x] ~~guida su come iniziare~~
   - [x] ~~grafica~~
     - [x] ~~barra laterale prima pagina~~
     - [x] ~~barra laterale pagine successive~~
     - [x] ~~intestazione~~
     - [x] ~~piè di pagina~~
     - [x] ~~font~~
   - [x] ~~configurazione~~
     - [x] ~~dimensione caratteri~~
		  - [x] ~~intestazione~~
		  - [x] ~~piè di pagina~~
		  - [x] ~~testo principale~~
     - [x] ~~margini~~
       - [x] ~~margini di pagina da rivedere~~
   - [x] ~~commenti in italiano~~
 - **versione 0.2.0**
   - [ ] licenza
   - [ ] readme
     - [ ] gif con [Recordit](http://recordit.co/)
     - [ ] finire la guida d'uso
     - [ ] altri [badges](https://shields.io/)
   - [ ] configurazione
     - [ ] margini - **ATTENZIONE**: se il paragrafo scavalla alla seconda pagina, si porta i margini precedenti
     - [ ] revisione allineamento delle immagini
   - [ ] aggiornare le immagini nella cartella images
 - **versione 0.3.0**
   - [ ] sostituire le immagini laterali con un sistema configurabile
   - [ ] configurabilità settore/sezione automatica
