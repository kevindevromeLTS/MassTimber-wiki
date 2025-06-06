---
tags:
    - brandsituatie
---

# Rekenkundige factoren

Rekenkudnige factoren volgens EC0-EC5

## Combinatiefactoren
- Accidenteel - brand: 1.0* perm + 0.2 winddruk, gamma_m = 1.0, kmod ?= 0.9
- Accidenteel - waterophoping: 1.0*perm + 1.0*water + 0.2*winddruk, gamma_m = 1.0, kmod ?= 1
- NL: Bij de combinatie met mobiele belasting: max(6.10a, 6.10b)
    - 1.35perm + 1.5*gereduceerde mobiele of 1.2*perm + 1.5*mobiele
    - phi_0’s zijn 0 bij onderhoud, wind & sneeuw ( Tabel A1.1 in bijlage NEN1990→
        - 1.35 perm
        - 1.2perm + 1.5 onderhoud
        - 1.2perm + 1.5 wind
        - 1.2perm + 1.5 sneeuw
- Comb 6.10a 1.35p + 1.5*q_red; 6.10b 1.2p * 1.5q
- Tijdelijke last bij montage: simpel rekenen als wind met kmod 1,1. Probeer de 1,5 UGT factor te behouden. Meer in detail → geen onderhoud, geen sneeuw, wind reduceren met seizoensfactor, gebruiksklasse veel korter

### NL: variaties
- wind is kort ipv onmiddelijk → kmod = 0.9
- afschuifkracht op oppervlakken door windwrijving
- Sneeuwophoping tot 4x, terwijl in BE slechts tot 2x
- Bij de combinatie met mobiele belasting: max(6.10a, 6.10b)
    - 1.35perm + 1.5*gereduceerde mobiele of 1.2*perm + 1.5*mobiele
- Onderhoudslast: 2kN puntlast in midden van ligger + 1kN/m² op oppervlak van 10m² (10/afstand op asafstand in midden vd ligger)
- Constructeur = studiebureau, staalbouwer = aannemer, constructiemodel?=architecturaal model
- Schuifpui is schuifraam, dus schrijnwerk wordt puien genoemd
- Vervormingen
- ! k_mod bij trek loodrecht op de vezel

## k_mod
- k_mod is een veiligheidsfactor volgens belastingsduur & klimaatklasse (CC)
- k_mod reduceert de draagkracht van het materiaal in de houtcontroles
- niet te verwarren met k_def die het kruipgedrag van het materiaal toevoegt in de doorbuigingscontrole
- k_mod wordt bepaald door keuze belastingen in combinatie met kortste duur in die belastingscombinatie

Modificatie coëfficiënt k_mod volgens EC5:

| Belastingsduur     | Klimaatklasse 1 | Klimaatklasse 2 |  Klimaatklasse 3 |
| --------           | -------         | -------         | -------          |
| Permanent          | 0,60            | 0,60            | 0,50             |
| Lange duur         | 0,70            | 0,70            | 0,55             |
| Gemiddelde duur    | 0,80            | 0,80            | 0,65             |
| Korte duur         | 0,90            | 0,90            | 0,70             |
| Ogenblikkelijk     | 1,10            | 1,10            | 0,90             |
| Accidenteel        | 1,10            | 1,10            | 1,10             |
| Brand              | 1,00            | 1,00            | 1,00             |

///////// Accidenteel en brand bij CC3 nog te verifiëren, alsook tabelnummer nog aan te vullen

- gamma_m is bij de accidentele of brandsituatie gelijk aan 1,0
- Zwembad = klimaatklasse 2

///////// Definieer klimaatklasses, ook voor hfst vochtbeheersing

### NL-NB: k_mod bij trek ⊥ op de vezel
    
- Van belang bij verjongingen, sparingen en ophangen aan de onderrand

> Voor trekspanningen loodrecht op de vezelrichting die horen bij:
> 
> - 6.1.3 Trek loodrecht op de vezelrichting
> - 6.4.3(6) en (7) Liggers met een tweezijdig taps verlopende hoogte, gebogen liggers, zadeldakliggers
> - 6.4.4 en 6.4.5 Volledoorsnedevingerlassen als gegeven in deze nationale bijlage (NEN)
> 
> Moeten de waarden voor k_mod volgens tabel NB.1 zijn gebruikT.

Modificatie coëfficiënt k_mod volgens NEN-EC5-NB Tabel NB.1:

| Belastingsduur     | Klimaatklasse 1 | Klimaatklasse 2 |  Klimaatklasse 3 |
| --------           | -------         | -------         | -------          |
| Permanent          | 0,50            | 0,50            | 0,40             |
| Lange duur         | 0,50            | 0,50            | 0,40             |
| Gemiddelde duur    | 0,65            | 0,65            | 0,55             |
| Korte duur         | 0,80            | 0,80            | 0,65             |
| Ogenblikkelijk     | 1,10            | 1,10            | 0,75             |
    


## k_def
- k_def is een veiligheidsfactor volgens klimaatklasse (CC)
- k_def verhoogt de resulterenede doorbuiging in de gebruikssituatie om het effect van kruip in rekening te brengen

/////// doorbuigingsformules met k_def

Vervormingscoëfficient k_def volgens EC5:

| Belastingsduur     | Klimaatklasse 1 | Klimaatklasse 2 |  Klimaatklasse 3 |
| --------           | -------         | -------         | -------          |
|                    | 0,60            | 0,80            | 2,00             |
