# ItemCost

Costo articoli \(netto, lordo, ...\)

  
 **Chiavi**

* _Id_
* ItemId, StartDate, EndDate, CurrencyId, SalesUomId, UnitsPerPack

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| CurrencyId | Id della valuta | text | 50 |
| EndDate | Data fine validità | date |  |
| GrossCost | Costo lordo | dec |  |
| Id | Id | text | 50 |
| ItemId | Id dell'articolo | text | 50 |
| NetCost | Costo netto | dec |  |
| OtherCost | Altro costo | dec |  |
| SalesUomId | Id unità di misura di vendita | text | 50 |
| StartDate | Data inizio validità | date |  |
| [Type](itemcost.md#type) |  | enum |  |
| UnitsPerPack | Unità per confezione | dec |  |

## Type

0: Regualar  
1: NetCost

