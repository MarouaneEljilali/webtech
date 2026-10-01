# Labo 2 - reflecties

Naam: (Marouane El jilali)

## 2. Selectors lezen

Welke elementen raakt elke selector? Eén zin per selector.

- a. `header nav ul li a`: Deze selector selecteert de drie navigatielinks "Adopteren", "Onze bewoners" en "Openingsuren" in de header.
- b. `article > p`: Deze selector selecteert de drie paragrafen met de teksten over het adopteren en de bewoners binnen het article-element.
- c. `.uren li:nth-child(3)`: Deze selector selecteert het derde lijstitem in de lijst met de class uren.
- d. `h2 ~ p`: Deze selector selecteert alle vier de paragrafen die in het article na een <h2>-kop staan.
- e. `.rassen li:first-child`: Deze selector selecteert het eerste lijstitem van de hoofdlijst én het eerste lijstitemvan de sublijst.

## 3. Voorspel, dan kijk

Vul de eerste twee kolommen in vóór je de pagina opent. Trede: herkomst, specificiteit, volgorde of overerving (of iets anders, benoem het).

| vraag | mijn voorspelling (kleur) | beslissende trede | uitkomst in de browser | juist? |
|---|---|---|---|---|
| 1 |crimson | specificiteit| crimson| ja|
| 2 | darkslateblue| volgorde| darkslateblue| ja|
| 3 | geel| overerving| geel| ja|
| 4 | zwart| herkomst| zwart| ja|
| 5 | | | | |
| 6 | | | | |
| 7 | | | | |
| 8 | | | | |
| 9 | | | | |
| 10 | | | | |

Bij welke vraag zat je fout, en wat was de reden? (Alles juist? Welke vraag duurde het langst, en waarom?)

## 4. De nabouw

- Welke selector koos je voor de links in de navigatie, en waarom geen class?
- Ik gebruikte nav a. We mochten niks aanpassen in de HTML (dus we konden geen class toevoegen), en met nav a pak je sowieso al alle links die in het navigatiemenu staan.
- Welke regel kostte je het meeste tijd, en wat was uiteindelijk de oorzaak?
- Vraag 3 (.rassen > li), omdat ik eerst .rassen li had geschreven. Daardoor kregen ook alle sub-items (zoals Herders, Staffords, etc.) een rode rand, terwijl alleen de hoofditems (Honden, Katten, Konijnen) een rand moesten krijgen. De oorzaak was dat ik vergeten was om het pijl-teken (>) te gebruiken om alleen de directe kinderen te selecteren.

## 6. Je site

- Welke drie waarden staan in je tokenblok, en waarom die?
- Drie CSS-variabelen (zoals --primaire-kleur, --secundaire-kleur en --lettertype). Je zet deze bovenaan in je CSS zodat je belangrijke keuzes voor je design op één vaste plek bewaart
- Wat verandert er in je site als je één token wijzigt?
- De waarde verandert meteen overal op de hele website waar je dat token hebt gebruikt (bijvoorbeeld: pas je de kleurcode in het token aan, dan veranderen alle knoppen en titels tegelijk mee).

## Thuis: R2.3 (met AI)

Prompt en onbewerkte output staan in `review/`. Minstens vijf bevindingen, elk met een verwijzing naar de sectie of het foutnummer:

1. 
2. 
3. 
4. 
5. 

