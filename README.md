![License](https://img.shields.io/badge/status-work%20in%20progress-red) ![License](https://img.shields.io/badge/version-0.0.0-yellow) ![License](https://img.shields.io/github/languages/top/scouting4bot/carta_intestata_latex)
*Il progetto è ancora in fase di sviluppo (versione alpha). Per ora non consiglio l'uso.
Per maggiori dettagli si veda il paragrafo sugli Sviluppi.*

# Carta Intestata LaTeX
Progetto basato sulla carta intestata dell'associazione scout [CNGEI](https://cngei.it/).
> Tutta l'immagine coordinata in un unico file, con la comodità di LaTeX

## Immagini e GIF
n.d.

# Indice
- [Multilanguage](#multilanguage)
- [Come iniziare](#come-iniziare)
- [Segnalazione bug e richieste](#segnalazione-bug-e-richieste-di-aiuto)
- [Come contribuire](#come-contribuire)
- [Licenza](#licenza)
- [Sviluppi futuri](#sviluppi-futuri)

## Multilanguage
Not available.

# Come iniziare
## Prerequisiti
- un editor LaTeX sul computer locale od online (es. https://www.overleaf.com/).
- conoscenza minima del LaTeX.

## Configurare l'editor
**Questo paragrafo non è ancora completo!**
- Scarica l'intero progetto [TODO: mettere spiegazione passo-passo]

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
├── MontserratFontFiles                   # cartella con i file per l'uso del font Montserrat
├── images                    # cartella con le immagini
├── main.tex                   # File tex in cui configurare la lettera con l'intestazione
├── LICENSE
└── README.md
```	

## Community
Scourting4bot ha uno spazio su [Slack](https://slack.com).

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)]()

Il Code of Conduct regolamenta le interazioni tra i vari attori di un
repository. Tendenzialmente è bene che questo incoraggi qualsiasi tipo di
contribuzione. Esistono diversi template già preimpostati che, dopo attenta
analisi, si possono incorporare nel proprio progetto. Il Team per la
Trasformazione Digitale adotta [questo Codice](https://www.contributor-covenant.org/version/2/0/code_of_conduct/code_of_conduct.md). 

### Segnalazione bug e richieste di aiuto
Se noti malfunzionamenti, puoi segnalarli usando lo strumento `Issue` di GitHub. Non temere di segnalare: ogni issue è un passo avanti verso un prodotto migliore.

### Semantic Versioning
Per il versionamento si cerda di seguire la modalità [Semantic Versioning](https://semver.org/). Ovviamente, se noti che qualcosa non torna, segnalalo.

## Manutenzione 
Attualmente il progetto è in sviluppo. Per segnalazioni o suggerimenti usa lo strumento `Issue` di GitHub.

---
# Licenza 
## Licenza generale 
Di norma, la licenza è indicata in modo abbreviato nel file README in quanto la
sua versione estesa è presente in un file dedicato chiamato `LICENSE.md`
presente, di norma, nella root del repository.  Per avere un aiuto nel percorso
di scelta di una licenza è possibile visitare
[Choose a License](https://choosealicense.com/).
Per i progetti del Team Digitale le licenze preferibili sono
[queste](https://github.com/teamdigitale/licenses).

## Autori e Copyright
* Ogni logo ed il formato della carta intestata è di proprietà del [CNGEI](https://cngei.it/).
* Il font Montserrat è utilizzato secondo [SIL Open Font License](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)
* Il copyright del resto del codice (main.text) è di `Scouting4Bot e tutti i contributori` ma può essere liberamente usato da chiunque, per ruolo od incarico, abbia il diritto d'uso della carta intestata dell'associazione (dirigenti, educatori, branche, settori, gruppi di lavoro, etc).

## Licenze software dei componenti di terze parti
L'analisi è stata eseguita con [FOSSA](https://fossa.com/pricing/). 

# Sviluppi futuri
 - **versione 0.1.0**
   - [ ] redme
     - [x] ~~struttura~~
     - [ ] [badges](https://shields.io/)
     - [ ] gif con [Recordit](http://recordit.co/)
     - [ ] paragrafi incompleti
   - [x] ~~grafica~~
     - [x] ~~barra laterale prima pagina~~
     - [x] ~~barra laterale pagine successive~~
     - [x] ~~intestazione~~
     - [x] ~~piè di pagina~~
     - [x] ~~font~~
   - [ ] configurazione
     - [ ] dimensione caratteri
		  - [ ] intestazione
		  - [ ] piè di pagina
		  - [ ] testo principale
     - [ ] margini
       - [ ] margini di pagina da rivedere
       - [ ] **ATTENZIONE**: nella seconda pagina il primo paragrafo si porta i margini precedenti
    - [ ] revisione finale dell'allineamento delle immagini
 - **versione 0.2.0**
   - [ ] portare i commenti in italiano
   - [ ] finire la guida d'uso
   - [ ] aggiornare le immagini
 - **versione 0.3.0**
   - [ ] sostituire le immagini laterali con un sistema configurabile
   - [ ] configurabilità settore/sezione automatica
