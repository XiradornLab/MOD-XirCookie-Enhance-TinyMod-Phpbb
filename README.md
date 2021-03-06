﻿# XirCookie Enhance Mod - Phpbb Mod for 3.0.x
### Modifica per l'accettazione dei cookie per phpbb 3.0.x. [Xiradorn Lab] [xlab] - Sir Xiradorn  
[xlab]: http://xiradorn.it "Xiradorn Lab"
----
**Nome MOD:** XirCookie Enhance Mod  
**Autore**: Sir Xiradorn  
**Versione Mod**: 1.0.0  
**Data**: 16/07/2015  
**Versioni phpBB compatibili**: 3.0.x  

**Descrizione MOD:** Rendiamo il nostro forum a norma di legge creando un pre-portale di accoglienza per gli utenti con tutte le informazioni di cui hai bisogno. Il cookie sono a prova di dispositivo e non richiede JavaScript quindi anche sui browser più datati può essere visualizzato il tutto. Fornisce anche alcune funzioni aggiuntive e auto traduzione nelle lingue più disparate.

**Link Download Mod:** [XirCookie Enhance Mod - Last Release] [repo_last_url]  
[repo_last_url]: https://github.com/Xiradorn/XirCookie-Enhance-TinyMod-Phpbb/releases/tag/v1.0.0 "XirCookie-Enhance-TinyMod-Phpbb - Last Release"  
**Demo:** [XirCookie Enhance Mod] [stargate_url] -> Stargate - XiLab  
[stargate_url]: http://stargate.xiradorn.it/30x/ "Stargate - XiLab"
**Repository:** [XirCookie Enhance Mod - Git] [repo_url]  
[repo_url]: https://github.com/Xiradorn/XirCookie-Enhance-TinyMod-Phpbb/releases "XirCookie-Enhance-TinyMod-Phpbb - Git"  

**ALPHA - Changelog v 0.0.0 / 0.4.0:**

 * 01/06/2015 - Dev - Inizio 
 * 03/06/2015 - Dev - Terminazione sviluppo codice funzionale e stile di base
 * 07/06/2015 -

 * Dev - Inizio 'improve' per lo stile e le funzioni aggiuntive.
 * Dev - Rifinitura della parte responsive - fissata da dispositivi minimi a 640px.
 * Dev - Passaggio da Alpha a Dev

**DEV - Changelog v 0.4.0 / 0.30.10:**

 * 13/06/2015 - Fix - Ripulitura codice da errori di varia natura
 
 * 16/06/2015 -
  * Dev - Creazione e definizione funzione di auto traduzione tramite user-agent
  * Dev - Creazione file di traduzione it e en
  * Dev - Creazione funzione alternativa per localizzazione linguaggio
 
 * 17/06/2015 - 
  * Pwr - Perfezionamento funzioni create e riposizionamento file
  * Dev - Creazione e perfezionamento localizzazione in forzamento
  * Fix/Add - Controlli, fix e aggiunta immagini mancanti
 
 * 18/06/2015 - Add - supporto per le seguenti lingue: Italiano, Inglese, Francese, Tedesco, Spagnolo, Greco, Russo, 
 Cinese, Giapponese
 
 * 19/06/2015 - 
  * Pwr - Aggiunto un doppio riconoscimento per la lingua del browser e quella scelta dalla form tramite classe css. Se queste coincidono, predominerà la classe della lingua del browser
  * Up - Traduzione Tasti
 
 * 20/06/2015 - 
  * Fix - Errore nel mancato redirect totale - segnalato da brunino
  * Up - Traduzione stringe restanti
  * Dev - Creazione della Custom Page che ripete la stessa pagina di benvenuto che trovate grazie a tale mod. Le modifiche che fate in quella, le avrete contemporaneamente in questa e allo stesso modo. Questo vale anche per le traduzioni nei file di lingua della mod in questione.
 
 * 21/06/2015 - Fix - Alcuni fix per le modalità di Debug / Debug Extra che ora non danno più segno di squilibrio ![altimg][img]
[altimg]: ":mrgreen:"
[img]: data:image/gif;base64,R0lGODlhDwARAOZEAAAAAP///zpANwDkfgCKTAC8aACyYgB8RQB+RQDIbgCoXQDSdEZOROnq6QCcVe7u7gCOTtXW1UxXSQDaeADqgVViUgDug/b29kZQQgDOcVtkWFNbUZaZlQDifACCSIWMhHyCegDceUJKQADyhW92bQC+aVJdT01WSwDGbWtyabW4tSlyRlODaQCGSgCgWQDKb5OwogCmWwDsggDEbQDWdgDYd4CFfgGBR2l+Zf3+/gDgewC0YwCWUwCaVQB4QkuPZ11oWomPiFF7YwCqXv///wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEAAEQALAAAAAAPABEAQAe9gESCF0FAJhUmGh8XgkQMHgABAZGSlAAJAo2CKkIaKTA5mh8QDgoAADMZNacWIwM2RCQICKeSkwAxCiSCHDgKBgUJCxMDFBYSHEQSBDwuQzsFKBk0IToDISIgB5a2liUggg0CBwceBAQQEAINmhEVwMLEFBsRgg8MpfDDxa0CDyekAAAD8AJAhw4AZAwQUaHFqYcQTy3AwGBbpW6VSjCIIIHWJIwCMdR7IMAHLYg9HPjT1GDDihvnfrBgJygQADs=
 
 * 24/06/2015 - 
  * Fix - Importante fix sul sid e su un errore di cron.
  * Fix - Ripulitura codice da variabili ridondanti e/o inutilizzate
  * Fix - Correzione entità html errate in fase di battitura. Ora funzionanti perfettamente
  * Fix - Correzione errori sul template per duplicazione tag di chiusura inutili
 
 * 25/06/2015 -
  * Dev - Sviluppo Modulo per profilo utente
  * Dev - Sviluppo funzione di riconoscimento più leggera per supporto ai file di linguaggio dei moduli
  * Dev - Traduzione modulare nelle lingue della mod e con file di linguaggio separati da quelli presenti per una rimozione più facile e senza toccare o stravolgere il codice
 
 * 27/06/2015 - Dev - Aggiunto Modulo per lista Amministratori e Founder
 
 * 28/06/2015 - 
  * Add - Aggiunta specifica css per differenziazione dal normale css di phpbb. Serve a non creare confusione tra i codici
  * Up - Aggiornamento Css con nuova specifica per pannello e altre funzioni per il forcing del layout
  * Up - Modifica alla specifica per il pannello nel Css
 
 * 30/06/2015 - Add - Aggiunto testo della normativa e traduzione per le lingue
 
 * 01/07/2015 - 
  * Dev - Creata una zona con una spiegazione dettagliata dell'uso dei cookie
  * Add - Traduzione completa di ogni singolo blocco
  * Dev - Creata sezione a scomparsa in CSS Pure solo su Desktop. Per le vecchie versioni dovrebbero non aversi problemi e poter essere letta comunque
  * Fix - Risolto problema traduzione nella parte delle liste Admin / Founder
 
 * 02/07/2015 - 
  * Dev - Sviluppata funzione per mostrare la normativa europea da http://eur-lex.europa.eu
  * Add - Aggiunta variabile per traduzione e file. I file però sono solo nelle seguenti lingue: IT, EN, DE, FR, EL, ES. Per mantenerle la reale integrità e veridicità NON SONO STATI MODIFICATI
  * Add - Aggiunto pseudo selettore a protezione delle immagini tramite immagine trasparente
  * Pwr - Minificazione del codice PHP e CSS
  * Fix - Alcuni fix prima e dopo la minificazione del codice


**Beta - Changelog v 0.30.10 / 1.0.0:**
 * 04/07/2015 - Passaggio in versione beta

**Versione 1.0.0:**
 * 16/07/2015 - Rilascio versione Ufficiale 1.0.0


\* La lingua dei file in questione non ha nulla a che vedere con quella del forum. Sul forum potete avere anche solo l'italiano e usare invece per la mod tutte le lingue elencate prima e/o crearne voi delle altre  
\* La mia legenda personale prevede i seguenti tag. Inoltre questo influirà sul numero di versione:  
\- Dev - ovvero quando vine sviluppata una funzione Ex novo  
\- Pwr - potenziamento di funzioni attuali  
\- Add - aggiunta di parti e componenti  
\- Up - aggiornamento dei file preesistenti  
\- Fix - risoluzione problemi  
Sono previste anche combinazione dei suddetti tag. Il numero di versione è strutturato come x.y.z.  
\- x - versione generale. Verrà incrementato se cambiano 5 o più funzioni insieme o se si totalizzeranno 99 modifiche  
\- y - ogni modifica, aggiunta, e powering segnano un incremento  
\- z - rappresenta il numero di fix sulla versione corrente x   

**Funzionalità Principale: **  
Generazione di cookie per uniformazione alla normativa europea e alla discussione sulla stessa che potrete trovare qua con una modifica di base in js: [Normativa Europea sui cookie](http://www.phpbbitalia.net/forum/forum-di-supporto-f205/normativa-europea-sui-cookie-legge-sui-cookie-2015-t12304.html), Legge sui cookie 2015. La modifica blocca inoltre la sessione quindi non rende fruibile la board fino all'accettazione del cookie in questione.

La mod inoltre prevede la possibilità di localizzazione nella lingua desiderata in base ai parametri [ISO 639-1 Language Codes](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) in due maniere: 
- Auto localizzazione controllata per mezzo dell'user-agent del proprio browser
- possibilità di switching tra i linguagi tramite GET requesting

Oltre alla funzionalità di cookie e di preportale, vi vengono messe alcune classi per personalizzare i vostri pannelli. Vi sono presenti inoltre funzioni per il controllo sul mobile di alcuni elementi che potrete usare per personalizzare il vostro stile o creare bbcode o similari.

Per ora la mod funzione solo su prosilver e verrà forse adattata (molto probabile al 90%) su subsilver

**Funzionalità Aggiuntive: **  
\- Classi di personalizzazione per .panel  
\- Classe per il controllo di elementi su mobile tramite media-query  
\- Set di flag per le lingue dia piccole che grandi  
\- Pagina personalizzata similare al preportale che riporta la cookie policy con la funzione di auto-traduzione come per la mod  
\- Normativa europea presa dal sito ufficiale dell'europa e tradotta (non da me ma da eur-lex.europa.eu) in varie lingue in PDF o HTML.   

**Funzionalità Future: **  
\- Style per subsilver2