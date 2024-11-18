# Stretnutie 4 - 29.10

## 🗒️ Detaily stretnutia

| **🖋️Typ stretnutia** | Stretnutie s Fiserv architektom |
| ---| --- |
| 🖋️**Miesto** | FIIT STU |
| 🖋️**Dátum** | 29.10.2024 |
|  |  |
| 🖋️**Čas** | 13:00 |

## 🙋 **Participants**

**Scrum Master**

Patrik Tomčo

**Zápisnica**

Silvia / Lujza

**Účastníci stretnutia**

- [x]     - [x]     René Bukovina
    - [x]     Patrik Fejda
    - [x]     Matej Kandráč
    - [x]     Silvia Kuchtová
    - [x]     Lujza Šufliarska
    - [x]     Patrik Tomčo
    - [x]     Filip Zatroch
    - [x]     Fiserv



## ✍️ Poznámky zo stretnutia

*   UI musí byť rozšíriteľné
*   klient ➝ env ➝ config: AQ & EQ



**!!! filters sa mozu ignorovat !!!**

### Terminologia

Offer je konkretny element (v YAML s klucom `- name`) v acquiring/equipment offers



*   v YAML file sa nachadza iba bare minimum
*   acquiring offers a equipment offers sa nebudu menit
*   acquiring offer - napr. cenove tarify
*   equipment offers - napr. terminaly (+ services k nim)
*   poradie fieldov je dolezite
*   rozsiritelnost UI o dalsie fieldy (napr visible, saasPlan)
*   client → env → jeden config (offer)
*   treba funkcionalitu na propagovanie konfigov do roznych env
*   no delete strategy → rollback vytvori novu verziu
*   validacia by fungovalo tak, ze nemozem ulozit konfiguraciu o ktorej vieme ze je nevalidna (tu validitu treba skontrolovat voci OMS)
*   spravit valildaciu nad starsimi verziami konfigov
*   rozsirenie fieldov - staci na jedno vnorenie
*   autorizaciu netreba teraz riesit - strech feature
*   staticka konfiguracia environmentov a clientov - na to sa vytvori konfiguracny subor, ktory bude ako vstup do BE
*   admina alebo adminske prostredie netreba



## Detaily ďalšieho stretnutia

| 📧**Dátum ďalšieho stretnutia** | 5.11.2024 |
| ---| --- |
| **📧Čas ďalšieho stretnutia** | 13:00 |
| **📧Miesto ďalšieho stretnutia** | FIIT STU |
| **📧Typ ďalšieho stretnutia** | New Sprint Start |