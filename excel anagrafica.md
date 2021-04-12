# Excel informazioni calcolo anagrafiche

## Descrizione file

### Fogli

- Foglio Cliente -> foglio da far compilare al cliente con informazioni di base sul calcolo da effettuare
- Foglio Nodi -> Foglio con informazioni dettagliate sui nodi su cui effettuare il calcolo
- Foglio Infissi -> Foglio con informazioni dettagliate sugli infissi da creare
- CSV nodi -> riservato per interoperabilità con gestionale
- CSV infissi -> riservato per interoperabilità con gestionale

### Foglio Cliente

Da definire

### Foglio nodi

**Regole base**
- Il nome del nodo determina il tipo di nodo ( se sono presenti due nodi, e.g. due inferiori finestra uno spessore 68mm uno 80mm, verrà creato un unico tipo di nodo chiamato inferiore finestra con spessore telaio minimo 68mm e massimo 80mm contenente i risultati dei test di trasmittanza di entrambi i nodi.)
- Nodi dello stesso tipo, quindi con lo stesso nome devono avere la stessa lista allumini e guarnizioni ( il programma gestionale controllerà solamente le liste del primo nodo presente nel file, se le altre sono differenti verranno sovrascritte )

**Campi da compilare**
- Nome nodo ( da assegnare manualmente ad ogni nodo )
- Tipo di nodo ( da selezionare da menu a tendina )
- Misure ( lasciare vuote quelle che non vanno usate *TODO? aggiungere formattazione condizionale dei campi in base al tipo di nodo?*)
    - Misura Anta
    - Spessore Anta
    - Misura Telaio
    - Spessore Telaio
    - Misura Totale
- Risultati calcoli trasmittanza
    - Legno molto tenero
    - Legno tenero
    - Legno semiduro
    - Legno duro
- Provenienza valore
- Calcolo effettuato da
- Lista guarnizioni (comma separated list *TODO? aggiungere )
- Lista allumini (comma separated list *TODO? aggiungere )
