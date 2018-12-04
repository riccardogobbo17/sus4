## sus4
Stat Under the Stars 4

#### Introduzione
L’azienda Findomestic Banca/S.R.l. (denominata Findomestic), al fine di risolvere un
problema di decisione sull’erogazione dei finanziamenti, ha chiesto alla nostra società di
organizzare una gara nella quale si sfideranno diversi team. Fate parte del team che,
accettando la sfida, è chiamato a proporre un modello statistico che consenta di predire
il comportamento dei clienti. Il vostro team risponde che è in grado di costruire un
modello statistico molto affidabile, ma all’interno della Findomestic ci sono delle giurie
scettiche verso l’approccio statistico per cui verrete sottoposti a una ‘Proof of Concept’.
Al termine della competizione l’azienda deciderà se affidarvi o meno l’incarico.

#### Descrizione del dataset e del problema di interesse
Il dataset fornito dall’azienda Findomestic è composto da circa 67.000 richieste di finan-
ziamento approvate. Ogni record del dataset contiene alcune caratteristiche rilevate al
momento della richiesta. La Figura riportata in Appendice 1 descrive 30 variabili rag-
gruppate in socio-demografiche, equipaggiamento del cliente, storico del cliente e com-
portamento del cliente. in Appendice 2 è riportata la codifica utilizzata per le variabili
qualitative. La variabile target “comportamento dei clienti denotata con “ClientStatus”, è osservata dopo 24 mesi dalla concessione del finanziamento, e assume le modalità seguenti elencate per ordine decrescente di gravità:

• cliente con contenzioso,

• cliente in recupero,

• cliente regolare.

Il vostro obiettivo è quello di utilizzare metodi statistici che consentano
di predire il comportamento dei clienti in funzione dell’opportuno sottoinsieme,
proprio o improprio, delle variabili rilevate.
