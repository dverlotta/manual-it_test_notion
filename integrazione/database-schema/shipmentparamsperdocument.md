# ShipmentParamsPerDocument
Parametri per la spedizione di un documento di vendita

<br>
**Chiavi**
- *Id*
- TrademarkId, SeasonId, DocumentTypeId, ShipmentNumber
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| --- | --- | --- | --- | --- |
| Description | Descrizione | text | 100 |
| DocumentTypeId | Id del tipo documento | text | 50 |
| Id | Id | text | 50 |
| Prebuy | Attiva gestione 'prebuy' | bool |  |
| SeasonId | Id della stagione | text | 50 |
| ShipmentEndDate | Data fine validità | date |  |
| ShipmentNumber | Numero consegna | text | 10 |
| ShipmentStartDate | Data inizio validità | date |  |
| ShipmentStartDateEditable | Consenti modifica data inizio spedizione | bool |  |
| TrademarkId | Id del Marchio | text | 50 |

