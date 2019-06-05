# MarketingForm
Schede Marketing

<br>
**Chiavi**
- *Id*
- AccountId, FormTypeId
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| --- | --- | --- | --- | --- |
| AccountId | Id del cliente | text | 50 |
| CreationDate | Data di creazione | dt |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| [EntityStatus](#entitystatus) | Campo che definisce lo stato del record | enum |  |
| FormFamilyId | Id della famiglia della scheda marketing | text | 50 |
| FormTypeId | Id del tipo di scheda marketing | text | 50 |
| Id | Id | text | 50 |
| IsDeleted | Indica se il record è stato cancellato | bool |  |
| LastModifiedTimeStamp | Data dell'ultima modifica | dt |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |
| RegistryTypeId | Id del tipo di registrazione | text | 50 |
| SyncReference | Riferimento | text | 50 |
| UploadToServerTimeStamp |  | dt |  |

EntityStatus
---
0: ImportedFromErp<br>1: ExportedToErp<br>2: ImportedByErp<br>3: ExportingToErp<br>4: Deleted<br>5: CommittingExportToErp<br>6: ToExportToErp<br>7: Editing<br>8: UploadedToServer<br>10: EditingPending

