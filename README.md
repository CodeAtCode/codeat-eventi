# codeat-eventi
Un JSON che contiene tutti gli eventi di Codeat

## Come si usa
Per aggiungere un evento al calendario basta inserire in formato JSON un elemento evento costruito nel seguente modo.

### Data (yyyy/mm/dd)
La data è sia l'oggetto dell'evento sia l'id che determina anche l'ordinamento e va inserita nel formato appropriato per permettere al sito il giusto sorting.

#### Titolo (string)
Il titolo dell'evento a cui parteciperete.

#### Ruolo (string)
Il ruolo va pensato sempre per essere inserito prima della parola 'PRESSO', quindi è bene usare un termine a scelta tra: speaker, relatore, formatore, studente, assistente, partecipante, etc.

#### Link (string/url)
Link comprensivo del protocollo http/https dell'evento.

## Regole per i commit
Aggiungete eventi nell'ordine in cui volete ma ricoradatevi di rispettare le virgole (usate un linter).
I nomi dei commit brevi e contententi solo l'evento che aggiungete. Es. 'Add WordCamp Torino'.
Se volete aggiungee detagli metteteli nel commento.

## Un augurio
Usiamolo tanto! :)