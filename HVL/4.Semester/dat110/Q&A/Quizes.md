

### Quiz week 6
1. Ett distribuert hash table kan gi følgende?
	- Tilgjengelighet
	- Skalerbarhet
	- Feil-tolerang
2. En challenge med home based approach
	- Geografisk skalerbarhet
3. Skalerbarhet feil som adresseres i DNS system er...
	- Replicating hiugher level DNS servere
4. Navn kan løses iterativt og rekursivt når det gjelder DNS. Hvilken av påstandene er korrekt?
	- I rekursiv løsning, vil kommunikasjons distangse ikke være noe problem, men høyere nivå servere kan få for mye load/trafikk
5. Ett name space inneholder...
	- Alle gyldige navn som gjennkjennes og styres av en service
6. Du skal lage ett system der vi skal designe lookupo for ett chord system som kan skalere, hvilken algoritme burde brukes?
	- En løsning der hver node bruker routing table som inneholder referanser til noen få eksponentielle noder
7. DNS brukes til å mappe hostname til IP adresse, hva er riktig? 
	- En authorativ name server er server som lagrer og gir IP adressen til hostname tiul den lokale DNS server
8. Ett distribuert hash table bruker 8bits til å definere adresse space, hvilken størrelse er adressen?
	- 2^8 = 256
9. Ett eksempel på location independent name er...
	- Domene 
10. En DHT chord ring har 3 aktive peers; P1, P2 og P3. P1 har adresse 20, P2 har adresse 10 og P3 har adresse 30. Hvilken av peers er ansvarlig for filene med følgende identifiers: 5, 12, 31 og 1
	- P1 holder 12, P2 holder 1, 5, 31


<hr>


### Quiz week 7
1. At Transport nivå gir en reliable data transfer service betyr at ...
	- Dataen som sendes er lik dataen som mottas, vise versa
2. Å gi data som er pakket inn i ett transport segment til riktig socket kalles ...
	- demultiplexing
3. Er det mulig for to prosesser som kjører på forskjellige hosts å sende UDP segmenter til den samme porten på en host
	- Ja
4. Hva slags pakker sendes mellom protocol entiteter på transport nivå?
	- Segmenter
5. Anta at en host mottaer ett UDP segment og finner ut at checksum er riktig, hva vet mottaker?
	- At segmentet som ble sendt er likt som segmentet motatt med høy sannsynelighet
6. Du blir gitt følgende 8-bit bytes: 01010011, 01100110, 00110100. Hva er komplementet av summen?
	- 00010010
7. Anta at vi har ett nettverk som kan ha duplikate datagrammer, men det er ingen transmisjonsfeil, loss eller overtaking. Hvilken protokoll mekanisme ville du brukt for å sikre reliable data transfer?
	- Sequence numbers
8. Er det mulig å håndtere transmission error på ACK/NAK segmenter i RDT 2.0 protokollen ved å retransmittere data segmentet i tilfellet der en korrupt ACK eller NAK er motatt av sender?
	- Nei
9. Er det mulig å unngå å bruke NAK-segmenter i RDT 2.1 protokollen ved å bruke sequence numbers i acknowledgement - og fortsatt vedlikeholde riktig protokoll
	- Ja
10. Hvis sender transport protokoll entitet i RDT 2.0 mottar en korrup ACK/NAK segment. - hva trenger sender å vite?
	- Noen segmenter ble motatt
11. Hvordan er TCP socket / connection identifisert?
	- Av ett tuppel bestående av source port, source IP adresse, destination port, og destination IP adresse
12. For hvilken av følgende transport protokoller er acknowledgements cumulative?
	- Selective-repeat
13. Hva er meningen med flow control?
	- Sikre reliable transmisjon for transport av segmenter
14. Tap av transport segmenter er allid en indikasjon på nettverk congestion?
	- Ja
15. Hva forholds kravene mellom sekvensnummer range og window size i selected report protokollen?
	- Sequence number range må være dobbelt av window size


<hr>


### Quiz week 8
1. 


