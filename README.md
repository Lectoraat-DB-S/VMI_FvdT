# VMI - Slijtage onderzoek
De code is ontworpen om een motor aan te sturen die een platform over twee rails heen en weer beweegt. De code gaat in samenwerking met de CORTEXX, dit is een computer van VMI waarin alle data van de motor wordt opgeslagen. Op de CORTEXX staan ook instellingen voor de HMI die ook een input geeft aan de code.

Deze code werkt alleen voor de testopstelling die samenkomt met de E-kast. Verder is deze code ook alleen te gebruiken in Rockwell PLC's. Dit komt doordat het is geschreven in Studio5000, een software programma voor industriële automatisering speciaal voor Rockwell.

Hardware:

-CORTEXX / HMI == IP adres 192.168.1.101 

-Rockwell PLC 1756-L82ES == IP adres 192.168.1.112
-1734-AENTR/C Ethernet Adapter == IP adres 192.168.1.113
