# Súbory

| **Názov súboru** | **Miesto uloženie** |
| ---| --- |
| cluk\_template-prod.yaml | mail |
| cluk\_template-prod-v2.yaml | mail, github |
| default-offers-target\_bkp\_2024-08-14.json | github |
| default\_offers.json | mail |
| payment-methods.json | mail |



| **Názov súboru** | **Použitie** |
| ---| --- |
| cluk\_template-prod.yaml |  |
| cluk\_template-prod-v2.yaml | základná schéma čo sa používa |
| default-offers-target\_bkp\_2024-08-14.json |  |
| default\_offers.json |  |
| payment-methods.json |  |

## Analýza súborov

### cluk\_template-prod-v2.yaml

*   acquiring offers
    *   name
*   equipment offers
    *   name

Obsah fieldu ,,_name"_

| **acquiring offers** | **equipment offers** |
| ---| --- |
| currency | currency |
| filters | filters |
| payment methods | main bundles |
| features | mandatory bundles |
|  | terminals |
|  | accessories |
|  | features |

![](https://t9012359320.p.clickup-attachments.com/t9012359320/b434534e-e5bb-40a4-9486-09f9b4302c24/image.png)

### default-offers-target\_bkp\_2024-08-14.json

offers \[\] (viacero offers vo fielde)

*   accessories
*   customFields
*   description
*   enabled
*   features \[list\] (len 2?)
    *   description
    *   enabled
    *   featureUuid
    *   fees
        *   enabled
        *   level
        *   name
        *   prices
            *   .
                *   ...
            *   .
        *   references
            *   key
            *   system
            *   value
    *   mandatory
    *   name
    *   references
        *   key
        *   system
        *   value
    *   tags
*   filters \[list\] (4? language, offertype, leadtype, cardnotpresentflag)
    *   key
    *   typevalue
*   images
*   name
*   offerUuid
*   paymentMethods \[\] (6)
    *   blended
    *   cardtypes
        *
    *   description
    *   enabled
    *   fees
        *
    *   group
    *   images
    *   interchange
    *   mandatory
    *   name
    *   paymentmethoduuid
    *   references
        *
    *   tags
*   references \[\] (3? - acquiring\_offering\_external\_id, settlement\_method\_id, posting\_tariff\_id)
    *   key
    *   system
    *   value
*   tags
*   terminals