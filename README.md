# Condizionatore Automatico
Gestione automatica del condizionatore

# Aggiornamento 25 ottobre 2020
Novità:
  - Aggiuta sezione "Auto Start&Stop Temperatura"
    E' possibile impostare una temperatura sopra la quale il condizionatore partirà da solo e una sotto la quale in condizionatore si fermerà.
    Nell'esempio dell'anteprima (uso estivo notturno) il condizionatore parte impostando una temperatura target di 26°, se la temperatura ambientale supera i 27° e l'umidità è superiore al 50%. Quando la temperatura ambientale scende sotto i 26°, il condizionatore si spegne

<img src="https://github.com/calas80/condizionatore_automatico/blob/master/Anteprima.jpg" alt="Anteprima">

# Prerequisiti
Custom Component necessari:
  - Vertical Stack In Card
  - fold-entity-row
  - card-mod
  - Mini Graph Card
  - multiple-entity-row

# Spiegazioni
Consente di definire 3 fasce con relativo settaggio della temperatura e velocità della ventilazione. La modalità di funzionamento (freddo, caldo, deumidificatore ecc) è invece unica per tutte le fasce orarie.

L'integrazinoe si basa su SmartIr e Broadlink. Potete trovare la lista dei condici dei condizionatori a questo link https://github.com/smartHomeHub/SmartIR/blob/master/docs/CLIMATE.md 


# Importante
Sia nel package che nella card, tutto quello che dovete "personalizzare" è indicato con delle "XXXX"
