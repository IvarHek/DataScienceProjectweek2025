# Challenge Week – Bird Classification

## Inleiding
Tijdens de **Challenge Week (27 t/m 31 oktober 2025)** hebben wij, **Ivar Hekkink** en **Jens Hooijmans**, gewerkt aan een machine learning-project gericht op het **herkennen van vogelgeluiden**.  
Ons doel was om een **neuronaal netwerk (neural network)** te bouwen dat verschillende vogelsoorten kan classificeren op basis van hun geluiden.  

We hebben hiervoor gebruikgemaakt van een dataset met vogelgeluiden die we hebben **omgezet naar spectrogrammen** — visuele representaties van audiofrequenties over tijd.  
Deze spectrogrammen dienden als input voor ons model, vergelijkbaar met hoe een neuraal netwerk afbeeldingen verwerkt.  

Onze workflow bestond uit de volgende stappen:
1. **Data preprocessing:** audiobestanden opschonen, normaliseren en omzetten naar spectrogrammen.  
2. **Segmentatie:** het opdelen van langere geluidsbestanden in kleinere fragmenten met één of meerdere vogelgeluiden.  
3. **Modelontwikkeling:** het ontwerpen en trainen van een **Convolutional Neural Network (CNN)** voor classificatie.  
4. **Evaluatie:** testen en verbeteren van het model aan de hand van validatiegegevens.  
5. **Presentatie:** het presenteren van onze aanpak, bevindingen en resultaten aan het eind van de week.

Uiteindelijk hebben we een **accuratesse van 82% op Kaggle** behaald.  
Voor ons beiden was dit de **eerste keer dat we een neuraal netwerk hebben opgezet en getraind**, waardoor dit resultaat boven verwachting was.  

---

## Wat ging goed
We zijn trots op hoe we als duo hebben samengewerkt.  
De taken waren goed verdeeld:  
- **Ivar** richtte zich voornamelijk op het voorbereiden van de data en het genereren van spectrogrammen.  
- **Jens** focuste zich op de segmentatie van vogelgeluiden en het structureren van de dataset.  

De communicatie verliep soepel, waardoor we snel beslissingen konden nemen en efficiënt konden werken.  
Ook het verbeteren van het model en het voorbereiden van de presentatie gingen goed.  
De combinatie van onze inspanningen zorgde voor een goed presterend model met een duidelijke eindpresentatie.

---

## Wat kon beter
Er zijn ook punten die we bij een volgende challenge anders zouden aanpakken:
- We hadden **het veranderen van de gewichten in de lagen kunnen automatiseren** en deze **visueel kunnen weergeven met een heatmap van de neuronen**.  
  Dit zou ons beter inzicht hebben gegeven in hoe het model leert en waarschijnlijk tijd hebben bespaard.  
  Deze aanpak willen we de volgende keer zeker meenemen.
- We hadden **meer aandacht kunnen besteden aan documentatie** van onze experimenten en resultaten.  
- De **voorbereiding van de presentatie** begon wat laat, waardoor we op het einde nog veel moesten afronden.  
- Een vorm van **versiebeheer (zoals GitHub)** had geholpen om onze code en bestanden beter te organiseren en te delen.

---

## Wat we hebben geleerd
Tijdens deze Challenge Week hebben we allebei veel geleerd, zowel technisch als op het gebied van samenwerking.  
De belangrijkste leerpunten zijn:

- Hoe je **audio kunt omzetten naar spectrogrammen** en hoe deze gebruikt kunnen worden als input voor neurale netwerken.  
- Inzicht in de werking van **Convolutional Neural Networks (CNN’s)** en hoe je de prestaties kunt verbeteren door te experimenteren met lagen en parameters.  
- Het belang van **data preprocessing en segmentatie** voor het verbeteren van modelkwaliteit.  
- Hoe kleine aanpassingen in de **architectuur of leersnelheid** een groot verschil kunnen maken in de accuraatheid.  
- Het belang van **duidelijke taakverdeling, planning en communicatie** bij het werken onder tijdsdruk.  
- Hoe waardevol het is om **experimenten visueel te analyseren**, bijvoorbeeld via heatmaps of foutenanalyse, om beter te begrijpen wat het model leert.  
- Dat zelfs met beperkte ervaring en tijd, **een gestructureerde aanpak tot sterke resultaten kan leiden**.

---

## Conclusie
De Challenge Week was een intensieve maar zeer leerzame ervaring.  
We hebben in korte tijd veel geleerd over **Neural Networks, audiobewerking en modelontwikkeling**, maar ook over **effectieve samenwerking en reflectie**.  
Met een score van **82% accuraatheid op Kaggle** zijn we trots op wat we hebben bereikt.  

We nemen onze nieuwe kennis en inzichten mee naar toekomstige projecten,  
waar we nog dieper willen duiken in **neuraal netwerken, visualisatie van leerprocessen** en het **automatiseren van modelanalyse**.


---
-DP
Opslag plek voor Pickle bestanden.

-essential_data
Orginele data om mee te trainen van de Kaggle Challange.

-supplemental_data
Extra data van de Kaggle Challange om mee te trainen.

-models
De modellen van de beste resultaten

-log
Visualisatie van de model training history en visualisatie van de data prep.

-BirdClassificationFinal
Jupyternotebooks bestand waar alle python code uitgevoerd wordt.
