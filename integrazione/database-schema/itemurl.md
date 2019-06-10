# ItemUrl

Risorse 'online' degli articoli \(schede tecniche online, immagini, ...\)

  
 **Chiavi**

* _Id_
* ItemId, UrlTypeId, Url

| Campo | Descrizione | Tipo | Dimensione |
| :--- | :--- | :--- | :--- |
| Caption | Titolo immagine | text | text |
| Id | Id | text | 50 |
| ItemId | Id dell'articolo | text | 50 |
| Priority |  | int |  |
| Url | Url collegato all'articolo | text | 500 |
| [UrlTypeId](itemurl.md#urltypeid) |  | enum |  |

## UrlTypeId

0: Undefined  
1: Image  
2: OnlineForm

