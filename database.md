#  cars  

##
- id : TinyInt;  {NOTNULL - AUTO_INCREMENT - UNIQUE}
- targa :  char(5); {NOTNULL - UNIQUE}
- alimentazione : varchar(20); {NOTNULL}
- anno immatricolazione : smallInt ; {NOTNULL}
- km percorsi : int; {NOTNULL}
- numero proprietari : tinyInt;
- casa di produzione : varchar(20); {NOTNULL}
- modello : varchar(20); {NOTNULL}
- prezzo : float(8,2); {NOTNULL}
- posizione : varchar(50);
