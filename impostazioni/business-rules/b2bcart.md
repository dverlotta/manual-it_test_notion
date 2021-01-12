# B2b\Cart

| Valore | Descrizione |
| :--- | :--- |
| [**CartNameTemplate**](b2bcart.md#cartnametemplate) | Template per il nome del carrello |
| [**CheckoutActionPriority**](b2bcart.md#checkoutactionpriority) | Ordine azioni di checkout |
| [**ConstraintFields**](b2bcart.md#constraintfields) | Campi che costituiscono un vincolo obbligatorio |
| [**CreditLimitCheck**](b2bcart.md#creditlimitcheck) | Tipo di controllo sul fido al checkout |
| [**ShipmentSiteIsMandatory**](b2bcart.md#shipmentsiteismandatory) | Destinazione merci obbligatoria |
| [**ValidatePricesObsolescence**](b2bcart.md#validatepricesobsolescence) | Abilita la validazione dei prezzi al checkout |

## CartNameTemplate

**Tipo:** Template  
**Valore di default:** ${CreationDate}  
**Valori:**

* CreationDate
* ItemCollection.Description
* ItemCollection.Id
* ReassortmentType.Description
* Season.Description
* Season.Id
* Trademark.Description
* Trademark.Id

## CheckoutActionPriority

**Tipo:** Valori separati da pipe

## ConstraintFields

**Tipo:** Valori separati da pipe  
**Valori:**

* ItemCollection
* ReassortmentType
* Season
* Trademark

## CreditLimitCheck

**Tipo:** Enum  
**Valori:**

* 0 =&gt; Nessun controllo
* 1 =&gt; Importo totale \(con IVA e spese accessorie incluse\)
* 2 =&gt; Totale merce \(IVA esclusa\)

## ShipmentSiteIsMandatory

**Tipo:** Boolean

## ValidatePricesObsolescence

**Tipo:** Boolean  
**Valore di default:** True

