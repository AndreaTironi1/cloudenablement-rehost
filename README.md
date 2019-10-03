# Premessa
Anche se il ReHost non è la strategia migliore, per iniziare a parlare con un cloud provider e capire i 
costi da sostenere, può essere un buon esercizio.

Vengono indicati in questo documento alcuni aspetti interessanti da indicare al fornitore cloud.

# Parametri

## CPU
Indicare numero cpu o ghz in uso:
es. 90 vcpu da 2.2 ghz
es. 90 Ghz

## Ram
Indicare numero di gigabyte di ram utilizzati da tutte le macchine
es. 800 gb ram

## Disco
Indicare GB o TB di disco utilizzati
es. 27.5 TB
Indicare tipo di storage
es. ibrido
es. ssd

## Numero server
Indicare numero server
es. 30 server

# Licenze server
Indicare server windows, linux, o altro.
es. 27 windows, 3 linux

## Backup
Indicare il tipo di software di backup, con relativa retention e se e' gestito direttamente o da fornitore.
es. backup gestito da fornitore, retention 30 giorni
es. backup con veeam, accesso al pannello, retention variabile a seconda del carico (da backup giornaliero 
retention 30 giorni a backup mensile retention 12 mesi)

## DR
Indicare se esistente il DR, con relativo RPO e RTO
es. dr non esistente (al momento è copia remota del backup, RPO 4 ore, RTO non calcolabile)
es. DR con RPO 10 minuti, RTO 

## Gestione
Come si gestiscono le vm?
es. gestione mediante vclouddirector
es. gestione mediante pannello aws, azure, gpc

## Connettivitàbanda 50 mbit simmetrici garantiti
Indicare banca up/down e quanta è garantita
es. 100 mbit simmetrici garantiti

## Assistenza

### Indicare SLA
Indicare uptime garantito. 
es. sla 99%

### Tipologia assistenza
Indicare assistenza (telefonica, ticket, altro)
es. assistenza mediante ticket, e telefonica

### Indicare in che fasce orarie serve l'assistenza
es. il servizio che eroghiamo è lun-ven 8.30-18 e sabato 8.30-12.30

## Provisioning
In quanto tempo viene effettuato il provisioning?
es. provisioning di solito in max 1 giornata lavorativa
