# Codeboek — synthetische oefendata

Alle personen en cijfers zijn **verzonnen**, uitsluitend voor de didactische oefening. Er zijn geen echte studenten onderzocht. Dit bestand onderbouwt geen effectiviteit van een training.

- `id`: fictief deelnemernummer, uniek.
- `groep`: `training` (oefentraining broncontrole) of `controle` (geen training).
- `score_voor`: score op fictieve toets vooraf, 0–10.
- `score_na`: score op fictieve toets achteraf, 0–10; één waarde ontbreekt bewust.
- `uren_zelfstudie`: synthetische zelfrapportage, 0–4.

## Belangrijke beperkingen

- Groepen zijn klein, niet willekeurig samengesteld en niet representatief.
- Geen causaliteitsconclusies uit deze dataset trekken.
- Een ontbrekende waarde mag niet zonder verantwoording worden ingevuld of als nul worden behandeld.
- Scores zijn integers; er is geen echte toetsvalidatie uitgevoerd.

## Controleberekeningen

- Training, complete paren (n=6): som verschil score_na - score_voor = 15; gemiddeld verschil = **2,5**.
- Controle, complete paren (n=5): som verschil = 3; gemiddeld verschil = **0,6**.
- Verschil in gemiddelde veranderingen = **1,9** punten. Beschrijvend, geen betrouwbaar effectbewijs.
- Controle-ID 12 heeft geen nameting; verwijder deze niet stilzwijgend uit ruwe data.