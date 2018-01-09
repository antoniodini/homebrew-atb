## Introduzione: il nome perfetto per questo libro
Homebrew in inglese vuol dire “birra fatta in casa”, cioè birra-fai-da-te. Ma l’attività di preparare, mescolare e far fermentare la birra nel mondo degli smanettoni digitali è diventato il sinonimo di un lavoro fatto in casa, col saldatore in mano e un sacco di caffè a disposizione. Non a caso il ritrovo degli smanettoni per eccellenza si chiamava **Homebrew Computer Club**: all'inizio era il Community Computer Center di Menlo Park, nella Silicon Valley, dove si ritrovavano i migliori smanettoni del nascente mondo dell'informatica personale dal 1975 a tutto il 1986. Tra gli altri, c’erano Steve Jobs e soprattutto Steven Wozniak, che presentarono proprio in quel contesto **l’Apple I**. Ma questa è un'altra storia.   

Nel tempo Homebrew ha assunto vari significati, soprattutto nella scena dei videogiochi per console realizzati dagli stessi giocatori. Con la nascita di Mac OS X per gli utenti Apple si è aggiunto un altro significato: **Homebrew** è diventato il nome di un gestore di pacchetti software per gli smanettoni della riga di comando. Concettualmente simile al **ben più famoso (nel mondo Linux) Apt**, l'Advanced Packaging Tool della distribuzione Debian e altre derivate, Homebrew è una soluzione per gestire il download e l’installazione del software e di tutte le librerie collegate, e poi ad aggiornarlo. Questo permette di semplificare in maniera sostanziale la vita per chi ha bisogno di usare strumenti che Apple non fornisce con la base Unix di macOS oppure che provengono in modo più ampio dal mondo Unix/Linux. Mai titolo di libro fu più azzeccato, dunque, di questo **Homebrew a tutta birra!**

Homebrew non è il primo gestore di pacchetti software di questso tipo sviluppato per Mac OS X: prima ci sono stati altri, soprattutto **Fink** e **MacPorts**. Entrambi con le loro indiosincrasie e difficoltà (soprattutto il secondo). Proprio da queste difficoltà di uso dei suoi predecessori **Max Howell** ha preso la decisione di realizzare Homebrew, scrivendo il programma di gestione dei pacchetti con il linguaggio **Ruby on Rails** e l’obiettivo di arrivare ad avere la massima estendibilità delle funzioni. Le due caratteristiche principali di Homebrew sono proprio queste: la flessibilità e la facilità di utilizzo.

Ma a chi è rivolto Homebrew? Certamente non all’utente casuale di macOS. Il "cliente" più probabile sono **gli sviluppatori**, ma anche **gli appassionati** che vogliono utilizzare alcuni software disponibili per la riga di comando ma che non sono presenti nella distribuzione di software inclusa con macOS. Un esempio? Il software <code>wget</code>, ideale per scaricare pagine e file dal web, oppure <code>MacVim</code>, probabilmente la migliore distribuzione dell'editor di testo <code>Vim</code> incapsulata in una applicazione Cocoa.

Per poter utilizzare Homebrew richiesto prima di tutto **saper usare la shell** (l'interfaccia a riga di comando contenuta nell'app di sistema di macOS che si chiama Terminale e si trova nella cartella <code>/Applications/Utilities</code>) ed essere fluenti con la riga di comando. Se non sapete di cosa stiamo parlando, vuol dire che Homebrew non fa per voi. Ci sono da imparare prima **alcune cose sull’utilizzo dei sistemi Unix/Linux** per poi poter arrivare ad apprezzare il repository di software open source per la parte Unix del nostro Mac. E non stiamo parlando solo di software open source con interfaccia a riga di comando, perché esistono anche applicativi con interfaccia grafica; ma questi ultimi fanno parte di un ambito diverso, che richiede il sotto-gestore **Cask**: ne parleremo più avanti.

Invece, andiamo avanti un passo alla volta. Se non sapete niente dell’argomento, oltre che buoni "guidatori" del Mac dovete prima diventare un po’ “meccanici” e imparare a usare la parte Unix. Dopodiché potete tornare qui e **cominciare a lavorare e divertirci con Homebrew**. L'obiettivo di questo volume della serie "A tutta birra!" è quello di fornirvi gli strumenti sintetici per orientarvi, capire la struttura e il funzionamento di Homebrew rapidamente e senza bisogno di andare a cercare informazioni su decine di siti diversi (e spesso in inglese). Quando avrete capito come funziona Homebrew e come usarlo, questo piccolo libro dovrebbe esservi ancora utile perché contiene un quadro completo e sintetico **per l'utilizzo, l'aggiornamento, il potenziamento e la migrazione di Homebrew**.  