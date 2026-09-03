# copilota-dati-es

Dataset delle mappe di Co-Driver, Spagna. **Non è un indirizzo da distribuire.**

L'app non li scarica da qui: passa dal proxy `https://codriver.pages.dev/mappe/<file>.json`,
che va a prenderli e li ripassa. È voluto: l'indirizzo di questo repo contiene un
cognome, e nel telefono di un tester non ci deve finire.

Diciannove unità: le diciassette comunità autonome più Ceuta e Melilla. Formato
identico a `copilota-dati`, prodotto da `process_es.py`, che conosce i due decreti
recenti che un processore generico sbaglia: le strade convenzionali tutte a 90 dal
2019, e l'urbano 20/30/50 per corsie dall'11 maggio 2021.

**Con gli autovelox**, 2.636 in tutto, a differenza di Francia (dove segnalarli è
vietato) e Gran Bretagna (dove sarebbero leciti ma manca la fonte). In Spagna la
segnalazione di un radar fisso è lecita e l'elenco lo pubblica la DGT; vietati sono
i rilevatori e i disturbatori, che sono un'altra cosa.

`es_melilla` non ha il `dos-`: nel suo territorio l'unico elemento di traffic
calming presente in OSM è un salvagente, giustamente escluso. Assenza dichiarata,
non un file perso.

Perché sta in un repo suo: GitHub Pages pubblica al massimo 1 GB per sito.

Dati © OpenStreetMap contributors, ODbL.
