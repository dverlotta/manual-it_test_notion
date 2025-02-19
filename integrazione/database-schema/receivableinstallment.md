---
description: Scadenzario
---

# ReceivableInstallment

**Chiavi**

* _Id_

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| ActualPaymentAmount | Importo del pagamento | dec |  |
| ActualPaymentDate | Data | date |  |
| ActualPaymentReference | Riferimento al pagamento | text | text |
| ActualPaymentTypeId | Tipo pagamento attualmente utilizzato | text | 50 |
| BankAbi | Codice ABI | text | 5 |
| BankCab | Codice CAB | text | 5 |
| BankCc | Codice CC | text | 20 |
| BankCin | Codice CIN | text | 1 |
| BankCountryCode | Codice del paese | text | 5 |
| BankIban | Codice IBAN | text | 40 |
| BankIbanCheckDigits | Check digits dell'IBAN | text | 5 |
| CashingId |  | text | 50 |
| CreationDate | Data di creazione | dt |  |
| CreatorId | Id dell'agente che ha creato il record | text | 50 |
| CurrencyId | Id della valuta | text | 50 |
| CustomerCode | Codice | text | 50 |
| CustomerId | Id | text | 50 |
| CustomerName | Nome | text | 100 |
| CustomerName2 | Nome 2 | text | 100 |
| DebitInterestAmount | Importo interessi | dec |  |
| DebitNoteNumber | Numero | text | 50 |
| [EntityStatus](receivableinstallment.md#entitystatus) | Campo che definisce lo stato del record | enum |  |
| ExpiryDate | Data di scadenza | date |  |
| FreeBoolean1 | Campo booleano libero | bool |  |
| FreeBoolean2 | Campo booleano libero | bool |  |
| FreeBoolean3 | Campo booleano libero | bool |  |
| FreeDateTime1 | Campo datetime libero | date |  |
| FreeDateTime2 | Campo datetime libero | date |  |
| FreeDateTime3 | Campo datetime libero | date |  |
| FreeDecimal1 | Campo decimale libero | dec |  |
| FreeDecimal2 | Campo decimale libero | dec |  |
| FreeDecimal3 | Campo decimale libero | dec |  |
| FreeText1 | Campo testo libero | text | text |
| FreeText2 | Campo testo libero | text | text |
| FreeText3 | Campo testo libero | text | text |
| Id | Id | text | 50 |
| InstallmentFromUnpaid | Indica se è una rata da insoluto | bool |  |
| IsCashableBySalesAgent | Indica se la partita è incassabile dall'agente | bool |  |
| IsDeleted | Indica se il record è stato cancellato | bool |  |
| LastModifiedTimeStamp | Data dell'ultima modifica | dt |  |
| LastModifiedUserId | Id dell'agente che ha effettuato l'ultima modifica | text | 50 |
| LastReminderDate | Data | date |  |
| LastReminderType | Tipo | text | 50 |
| LineNumber | Numero riga | int |  |
| Notes | Note | text | text |
| NumberOfMultipleCashedInstallments |  | int |  |
| OriginalDueAmount | Importo originario | dec |  |
| PaidAmount | Importo pagato | dec |  |
| PaidDate | Data pagamento | date |  |
| PaymentForcedlyClosed | Indica una chiusura forzata della rata | bool |  |
| [PaymentStatus](receivableinstallment.md#paymentstatus) | Stato del pagamento | enum |  |
| PaymentTypeId | Tipo pagamento atteso | text | 50 |
| ReceivableDate | Data | date |  |
| ReceivableId | Id | text | 50 |
| ReceivableNumber | Numero | text | 50 |
| ResidualDueAmount | Importo residuo | dec |  |
| SourceDocumentDate | Data | date |  |
| SourceDocumentFamilyId | ID della famiglia | enum |  |
| SourceDocumentId | Id | text | 50 |
| SourceDocumentNumber | Numero | text | 50 |
| SourceDocumentTypeId | Id del tipo documento | text | 50 |
| SyncReference | Riferimento | text | 50 |
| UnpaidPaymentTypeId | Id tipo effetto | text | 50 |
| UnpaidReference | Riferimento | text | 50 |
| UploadToServerTimeStamp |  | dt |  |

## EntityStatus

* 0: ImportedFromErp
* 1: ExportedToErp
* 2: ImportedByErp
* 3: ExportingToErp
* 4: Deleted
* 5: CommittingExportToErp
* 6: ToExportToErp
* 7: Editing
* 8: UploadedToServer
* 9: StartedUploadToServer
* 10: EditingPending
* -1: Undefined

## PaymentStatus

* 0: ToPay
* 1: Paid
* 2: Unpaid
* 3: PaidOnKimo
