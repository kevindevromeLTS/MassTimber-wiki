# Algemene richtlijnen verbindingen

## Excel verbindingsblad

- gamma_m is 1.3 bij verbindingen
- f_uk steeds 800MPa bij bouten, stiften zijn volgens S235 of S355 of 8.8 waarden
- alpha is hoek tussen krachtvector en houtrichting
- !! geef normaal en dwarskracht apart in in Excel, en combineer de unity check met pyth ipv normaal & dwarskracht the combineren met pyth.
- n0 volgens krachtvector, interpoleren kan maar niet echt nodig
    - tussenafstand a_1 geproj op rechte // aan kracht (bij 30° situatie)
- Koordwerking: alsof je touw ipv tige zou gebruiken, dan zou verbinding enkel in stand houden door knopen op uiteinde en trek in je touw → trekkracht in tige
- Houtdraadbouten meestal met catalogus ipv met Excel

## Karakteristiek - rekenwaarde

- karakteristieke lasten -(comb factoren)→ design reactiekrachten -(veiligheidsfactoren)→ karakteristieke gevraagde verbindingsdraagvermogen
- veiligheidsfactoren:
    - gamma_m = 1.3
    - kmod = afh bepalende belasting
    - design reactiekracht * 1.3 / kmod = karakteristieke verbindingsdraagvermogen
        - karakteristieke draagvermogen * kmod/1.3 = design draagvermogen

## Praktisch

- Bout normaal niet langer dan 10*d
- Boutdiameter std 1/10* spantbreedte
- Overmaat gaten:
  - bij bout/draadstang 2mm in hout en 2mm in staal
  - bij stiften 0mm in hout en 2mm in staal
- stiftdiepte min 15mm minder dan volledig door, boorpunt is meer dan 10mm
- Stiftlengte volgens tiental ipv twintigtal, vb 150mm, is mogelijk -> zie cataloog leverancier bij keuze
- Houtdraadbouten (telefon/KOP) is staalkwaliteit 4.6
- houtdoppen: volgens inbrandsnelheid, reductie met t_bout of t_stift volgens Colin te gunstig, Rothoblaas rekent in smartbook timber met een factor 1,5. Verder te onderzoeken.
- Standaardkleur op maat gemaakt metaal = RAL7042;
    - “file:///R:/Korlam/Technische%20Fiches/Zwembaden/bundel/00-Technische%20fiches%20zwembaden.pdf”
- Duroc Duplex 2000 behandeling bij zwembadmilieu
- Boutkwaliteit -> f_y of f_t: vb 4.6:
  - 4*100 = ft;
  - 4*6*10 = fy
- Draadstangen: Bij plooien voor ankers; staalkwaliteit niet hoger dan 4.6
- Moerbalken transportefficiëntie: bij een std industriehal; nooit metaal op moerbalk laten premonteren atelier, zeer nadelig in transport
- Metaal die nadien RF geschilderd zal worden op de werf, voorzien van de specificatie op de metaalstuktekening: ‘Grondlaag voor RF’ 
- Vernagelde spantschoenen
  - Rothoblaas LBS460 altijd vervangen door paslode4x50 zodat ze met onze standaard nagelpistolen geplaatst kunnen worden
- Leveranciers stiften
    - Rothoblaas
    - Fabory
    - Jari
    - Schrauben Smit

## Hilti

- Hilti: expansieanker HST. (HSA enkel bij niet gescheurd, niet meer gebruikt) - M10 - M16
    - randafstand min 80mm, liefst zeker 100mm
- Hilti: chem. anker:
    - std: HIT-HY 200 met HAS-U (tige niet bij hilti bestellen)
    - sterker met epoxy: HIT-RE 500 met HAS-U
- Hilti: indien 6 of meer bouten door een plaat, gaten opvullen zodat ze allemaal op afschuiving belast zijn. Opvulmiddel ook tekenen in CA zodat deze in lijsten staat
- [Operating-Instruction-Seismic-Filling-set-Operating-Instruction-PUB-5245905-000.pdf](https://www.hilti.co.uk/medias/sys_master/documents/h02/hd9/10162838011934/Operating-Instruction-Seismic-Filling-set-Operating-Instruction-PUB-5245905-000.pdf)
- “De opening op spreidankers (HST, HST2, HST3, HDA, HSL-4, HMU, HSA) moet gevuld worden met HIT-HY injecteerbaar chemische mortel (HIT-RE is niet geschikt)” ([Vulring (koolstofstaal) - Bevestigingselementen - Hilti België](https://www.hilti.be/c/CLS_FASTENER_7135/CLS_FASTENING_ELEMENTS_7135/r4930047))
- Sven: HIT RE is chem ankerprod voor vullen gaten ↔ CW: HIT HY200A ??

## Gekleurde verbindingsmiddelen

Zwarte draadstangen & moeren bij 2260029 Amsterdam-  Mediahuis

## Paslode

```markdown
file:///R:/Korlam/Technische%20Fiches/Paslode%20nagels%202.8x70%20hout-hout.pdf
```
