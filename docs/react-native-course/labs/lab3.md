# Labo 3

Voor dit labo moet je de volgende theorie bekeken hebben:
- Lijsten
- Controlled components

## Opdracht: Posts met FlatList

Maak een nieuwe react native app. Bij het opstarten van de app wordt een lijst van posts getoond. De posts worden opgehaald van de volgende url: https://jsonplaceholder.typicode.com/posts. Je moet de data ophalen met een fetch request in een useEffect hook. De posts worden getoond in een FlatList met een refresh control om de data te refreshen. 

De applicatie moet als er als volgt uitzien:

![Alt text](../images/posts.gif)

## Opdracht: Dark/Light Toggle

Maak een nieuwe react native app. Plaats twee invoervelden in de app en een switch. ALs je op de switch duwt, veranderd de achtergrond kleur van de app initieel van wit naar zwart en omgekeerd. De invoervelden dienen om de kleur waartussen je kan switchen in te geven. De applicatie moet er als volgt uitzien:

![Alt text](../images/darklight.gif)

## Opdracht: Rainbows met state

### Stap 1: Loops
Zorg dat je colors array 10 waarden bevat. Pas dan jouw Rainbow component aan zodat die over de eerste 6 waarden van de kleuren array loopt. (tip: je vervangt 6 lijnen code door 1 lijn)

Doe dit ook voor de Footer component: maak een variabele text aan die het woord Rainbow bevat en loop over de letters van het woord (tip: je vervangt 7 lijnen code door 1 lijn). 

Zorg dat het woord dat in Footer getoond wordt **nooit langer kan zijn dan 10 letters** (bv: als je de variabele text de waarde "Hallo ik ben een student van AP" geeft, zie je in de footer alleen "Hallo ik b")

### Stap 2: State

- Voeg een knop toe waarmee je de kleuren van de regenboog kan veranderen van pastel kleuren naar niet pastelkleuren (en omgekeerd)
- Voeg een input veld toe waar je een tekst kan ingeven. Als je op submit drukt, wordt de tekst in de footer veranderd naar de tekst die je ingegeven hebt. (tip: gebruik de `onSubmitEditing` event handler van een `TextInput` component)
- Je hebt hier twee state variabelen nodig.

Je kan je baseren op de volgende screen recording:

![picture 8](../images/interaction-statemobile.gif)

### Stap 3: Randomize rainbow

- Voeg nog een extra knop toe waarmee je de kleuren van de regenboog kan randomizen. (tip: gebruik de `Math.random()` functie)
- De tekst in de footer mag niet mee gerandomized worden.
- De pastel knop moet ook nog steeds werken.

![picture 8](../images/interaction-statemobile2.gif)
