# db first

## richiesta

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

1. auto_usate
    - marca
    - targa
    - prezzo
    - tipo_motore (benzina, diesel, elettrico, ibrida)
    - cilindrata 
    - anno_immatricolazione
    - km_percorsi
    - incidentata (si/no)
    - lunghezza 
    - larghezza 
    - optional 
    - numero_di_porte

<hr>
<hr>

![img](<imgWork/Screenshot 2024-01-18 173948.png>)

per la Primary Key ho deciso di non usare la targa perche essendo auto usate è possibile che arrivino auto sprovviste di targa o magari la loro targa verrà cambiata e quindi per sicurezza ho usato un PK di numeri incrementali