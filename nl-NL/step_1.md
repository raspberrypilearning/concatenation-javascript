Je kunt tekst (strings) en variabelen combineren in JavaScript.

Een "string" (tekenreeks) is een datatype in JavaScript en andere programmeertalen. Datatypes zijn groepen van gegevens die het programma vertellen hoe we gegevens willen gebruiken.

Je kunt strings opmaken door middel van samenvoeging of sjabloonliteralen.

### Samenvoeging

Je kunt strings samenvoegen met behulp van de operator `+`.

## --- code ---

language: js
filename:
line_numbers: true
-------------------------------------------------------

const superheld = "Iron Man";
const kracht = "harnas";
// Voorbeeld dat samenvoeging gebruikt
const beschrijving = "De superheld " + superheld + " heeft als superkracht een " + kracht + ".";
console.log(beschrijving);

\--- /code ---

### Sjabloonliteralen

Je kunt de inhoud van variabelen in een string opnemen door backticks `` ` `` te gebruiken om variabelen in deze symbolen in te sluiten: `${}`.

Hier is een voorbeeld.

## --- code ---

language: js
filename:
line_numbers: true
-------------------------------------------------------

const naam = "Spider-Man";
const leeftijd = 25;
// Voorbeeld dat sjabloonliteralen gebruikt
const bericht = `Hallo, ${naam}! Je bent ${leeftijd} jaar oud.`;
console.log(bericht);

\--- /code ---
