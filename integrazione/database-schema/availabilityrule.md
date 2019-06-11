# AvailabilityRule
Regole di disponibilità

<br>
**Chiavi**
- *Id*
<br><br>

| Campo | Descrizione | Tipo | Dimensione | 
| --- | --- | --- | --- | --- |
| Description | Descrizione | text | 100 |
| Id | Id | text | 50 |
| [ItemAvailabilityValidationRule](#itemavailabilityvalidationrule) | Indica se la quantità inserita deve essere confrontata con la disponibilità dell'articolo | enum |  |
| ShouldShowItemAvailability | Indica se la disponibilità dell'articolo è visibile in fase di inserimento quantità | bool |  |

ItemAvailabilityValidationRule
---
0: DoNotValidate<br>1: BlockIfExceed

