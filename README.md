> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Titel
Activity Diagram Reflect for Effect

## User Story
Als gebruiker wil ik mijn eigen gedrag kunnen vastleggen aan de hand van persoonlijke quizvragen Zodat ik weet hoe ik ervoor sta.

## Activity Diagram

![20220309_112957](https://user-images.githubusercontent.com/26089533/157424417-a6a6cedd-937a-412f-8800-c45010ea8cdc.jpg)

![20220309_112946](https://user-images.githubusercontent.com/26089533/157424470-80bfa6ad-a1ab-4cc0-b490-ac9b7ff897f3.jpg)


## Uitleg pseudo-code 
<!-- Leg de pseudo-code in de control fow uit -->
We beginnen in de Empty state. In deze state wordt getData aangeroepen. State verandert naar loading. Dit zie je terug in het ontwerp met een skeleton loader. In getData wordt fetchData() en renderData() aangeroepen. FetchData haalt de data uit de API op en renderData vertaalt het naar HTML. Is dit gelukt verandert state naar loaded. Is dit niet gelukt verandert state naar error en wordt er error handling uitgevoerd.. 



## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
