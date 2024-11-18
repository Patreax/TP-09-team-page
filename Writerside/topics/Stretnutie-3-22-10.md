# Stretnutie 3 - 22.10

## 🗒️ Detaily stretnutia

| **🖋️Typ stretnutia** | Sprint Start |
| ---| --- |
| 🖋️**Miesto** | FIIT STU |
| 🖋️**Dátum** | 22.10. |
|  |  |
| 🖋️**Čas** | 13:00 |

## 🙋 **Participants**

**Scrum Master**

Patrik Tomčo

**Zápisnica**

Silvia / Lujza

**Účastníci stretnutia**

- [x]     - [x]     René Bukovina
    - [ ]     Patrik Fejda
    - [x]     Matej Kandráč
    - [x]     Silvia Kuchtová
    - [x]     Lujza Šufliarska
    - [x]     Patrik Tomčo
    - [x]     Filip Zatroch
    - [x]     FISERV



## ✍️ Poznámky zo stretnutia

*   historia zmien - rollback nemusi byt a uklada sa posledna verzia, da sa urobit kopia tej verezie
*   offer - ponuka (jeden subor ktory sa uklada), offer per klient per environment
    *   moze mat viacero environmentov
*   1 klient môže mať viacero offerov
*   1 offer može mať viac environmentov
*   konfigurácia by bola v súboroch, ktoré my načítame (keď sa aj zmení konfigurácia tak sa musí vedieť updateovať)
*   yaml je jak keby json
*   yaml - response z api ale prekonvertovaný do json (ten nás až tak nezaujíma)
*   výsledok je yaml, ktorý ide tiež ďalej
*   offline aplikácia (➝ docker)
*   koniec procesu u nás - upravujeme súbory a ukladáme do databázy a integráciu si sám robí fiserv
*   lockovanie - môžeme keď tak urobiť že sa opýta či chce overridenúť locknutý súbor
    *   prípadne ak je to locknuté, tak sa opýta či mu vytvorí kópiu
*   verzie - rollback po dňoch
*   registrácia - ldap gropu/ len prihlasovanie stačí
*   feature - visible - ked má kllient niečo čo nemajú vidieť, je to optional, teoreticky to visible môže byť pri hocijakom fielde
*   dashboard - jeho klienti (prihlaseneho usera)
*   niekde ze su nove fieldy by mohlo upozorniť klienta
*   draft označí na spracovanie (na publishnutie)
*   po otvorení draftu (ktorý nie je ready na publish) upozorní že je tam nový config



| **Úloha** | **Vlastník úlohy** | **Poznámka** |
| ---| ---| --- |
| seed default user | [@Filip Zatroch](javascript: void;) |  |
|  |  |
| prototyp + flowchart | [@Lujza Šufliarska](javascript: void;) |  |
| autentifikacia frontend | [@René Bukovina](javascript: void;) |  |
| biznis modely | [@Silvia Kuchtová](javascript: void;) |  |
| locking | [@Matej Kandráč](javascript: void;) |  |

## Detaily ďalšieho stretnutia

| 📧**Dátum ďalšieho stretnutia** | 29.10.2024 |
| ---| --- |
| **📧Čas ďalšieho stretnutia** | 13:00 |
| **📧Miesto ďalšieho stretnutia** | FIIT STU |
| **📧Typ ďalšieho stretnutia** | Iteration Planning, stretnutie s fiserv architektom |