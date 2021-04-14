# Descrizione processo database calcoli

## Descrizione file

- file in W:\Frame Simulator
    - Tab Rapporti di prova con rapporti di calcolo fatturati ai clienti
    - Tab calcoli interni Quasar_Freud con con calcoli cascading Freud (ci sono clienti diversi perchè richieste partite dal cliente poi sponsorizzate da Freud e inserite in cascading)
- alcuni calcoli sono fatti solo per comparazione quindi non contengono link al rapporto di calcolo

### Colonne
- Cliente
- Richiesta
- Codice rapporto di calcolo
- Inserito in anagrafiche TTS (sì/no) -> no = calcoli comparativi/studio/interni
- Sistems (se Freud)
- Sp (i.e. spessore anta/telaio)
- Calcoli di riferimento
- Note/Logiche di estensione (come sono stati estesi i calcoli) -> Conisderazioni generali su cosa è stato deciso per i calcoli (estensioni, calcoli comparativi,...)


## Cose da ricordare

- attribuire numero rapporto prima su excel.
- Link assoluti non relativi


## Cartelle da verificare

- La prate rapporti di prova dovrebbe essere aggiornata (Laura confronta con fatture)
- Da controllare X:\Freud CE\ contiente tutti gli altri rapporti di calcolo
    
# Regole creazione cartelle

Tutti i calcoli di trasmittanza andranno inseriti nella cartella ```X:\Calcoli trasmittanza termica```.
Come regola generale, inserire un file nella cartella più specifica che contenga, nelle propie sottocartelle, tutti i calcoli a cui il file si riferisce (ad esempio il file ```.dwg``` contenente tutti i disegni di una singola anagrafica verrà inserito nella cartella dell'anagrafica mentre quello contenente tutti i disegni di un sistema Freud verrà inserito un livello più in alto nella cartella contenente tutte le anagrafiche del sistema).
 la struttura delle sotto-cartelle è come segue 

- :file_folder:```Clienti```
  - :file_folder:*Nome cliente*
    - :file_folder:*Nome Sistema* (Nome anagrafica oppure ```altro``` per calcoli che non generano una nuova anagrafica nodi, e.g. cassonetti, pannelli isolanti, ponti termici, etc.)
        - :page_facing_up: :green_circle: Excel file con riepilogo calcoli anagrafica 
        - :triangular_ruler: :pencil2: disegni ```.dwg``` e ```.dxf``` dell'anagrafica, se presenti
        - **Se nodo**:<br/>
         :file_folder:*Spessore* (e.g. 68mm, 78mm, 80mm, etc.)
          - :file_folder: *Tipo nodo* (e.g. Inferiore porta PRT029, Laterale superiore, Telaio fisso, Traverso intermedio, etc.)
              - :page_facing_up: :red_circle: File calcoli ```.frs```
              - :page_facing_up: :red_circle: Report generale ```.pdf```
              - :page_facing_up: :large_blue_circle: Rapporto di calcolo Word ```.docx```
              - :triangular_ruler: :pencil2: disegni ```.dwg``` e ```.dxf``` 
              - :camera: screenshot per report word
              - :camera: immagini con quote
        - **Se altro**<br/>
         :file_folder:*identificativo* (nome unico per identificare il calcolo)
            - :page_facing_up: :red_circle: File calcoli ```.frs```
            - :page_facing_up: :red_circle: Report generale ```.pdf```
            - :page_facing_up: :large_blue_circle: Rapporto di calcolo Word ```.docx```
            - :triangular_ruler: :pencil2: disegni ```.dwg``` e ```.dxf``` 
            - :camera: screenshot per report word
            - :camera: immagini con quote
               
- :file_folder:```Clienti Freud```
    - *Nome cliente*
      - *Nome sistema* (Nome anagrafica oppure ```altro``` per calcoli che non generano una nuova anagrafica nodi, e.g. cassonetti, pannelli isolanti, ponti termici, etc.)
        - :page_facing_up: :green_circle: Excel file con riepilogo calcoli anagrafica 
        - :triangular_ruler: :pencil2: disegni ```.dwg``` e ```.dxf``` dell'anagrafica, se presenti
        - **Se nodo**:<br/>
         :file_folder:*Spessore* (e.g. 68mm, 78mm, 80mm, etc.)
          - :file_folder: *Tipo nodo* (e.g. Inferiore porta PRT029, Laterale superiore, Telaio fisso, Traverso intermedio, etc.)
              - :page_facing_up: :red_circle: File calcoli ```.frs```
              - :page_facing_up: :red_circle: Report generale ```.pdf```
              - :page_facing_up: :large_blue_circle: Rapporto di calcolo Word ```.docx```
              - :triangular_ruler: :pencil2: disegni ```.dwg``` e ```.dxf``` 
              - :camera: screenshot per report word
              - :camera: immagini con quote
        - **Se altro**<br/>
         :file_folder:*identificativo* (nome unico per identificare il calcolo)
            - :page_facing_up: :red_circle: File calcoli ```.frs```
            - :page_facing_up: :red_circle: Report generale ```.pdf```
            - :page_facing_up: :large_blue_circle: Rapporto di calcolo Word ```.docx```
            - :triangular_ruler: :pencil2: disegni ```.dwg``` e ```.dxf``` 
            - :camera: screenshot per report word
            - :camera: immagini con quote
- :file_folder:```Sistemi Freud```
    - :file_folder:*Nome famiglia* (e.g. Alumfast, Freumex HP, etc.)
      - :file_folder:*Nome sistema* (e.g. Easy, Sistema 16, ECO100, etc.)
        - :page_facing_up: :green_circle: Excel file con riepilogo calcoli anagrafica 
        - :triangular_ruler: :pencil2: disegni ```.dwg``` e ```.dxf``` dell'anagrafica, se presenti
        - :file_folder:*Spessore* (e.g. 68mm, 78mm, 80mm, etc.)
          - :file_folder:*Tipo nodo* (e.g. Inferiore porta PRT029, Laterale superiore, Telaio fisso, Traverso intermedio, etc.)
              - :page_facing_up: :red_circle: File calcoli ```.frs```
              - :page_facing_up: :red_circle: Report generale ```.pdf```
              - :page_facing_up: :large_blue_circle: Rapporto di calcolo Word ```.docx```
              - :triangular_ruler: :pencil2: disegni ```.dwg``` e ```.dxf``` 
              - :camera: screenshot per report word
              - :camera: immagini con quote
