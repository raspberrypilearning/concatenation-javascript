Je kunt tekst (strings) en variabelen combineren in JavaScript.

Een "string" (tekenreeks) is een gegevenstype in JavaScript en andere programmeertalen. Data types are groups of data that tell the program how we want to use data.

Je kunt strings opmaken door middel van samenvoeging of sjabloonliteralen.

### Samenvoeging

Je kunt strings samenvoegen met behulp van de operator `+`.

## --- code ---

language: js
filename:
line_numbers: true
-------------------------------------------------------

const superhero = "Iron Man";
const power = "harnas";
// Voorbeeld dat samenvoeging gebruikt
const description = "De superheld " + superhero + " heeft als superkracht een " + power + ".";
console.log(description);

\--- /code ---

### Sjabloonliteralen

Je kunt de inhoud van variabelen in een string opnemen door backticks `` ` `` te gebruiken om variabelen in deze symbolen in te sluiten: `${}`.

Hier is een voorbeeld.

## --- code ---

language: js
filename:
line_numbers: true
-------------------------------------------------------

const name = "Spider-Man";
const age = 25;
// Voorbeeld dat sjabloonliteralen gebruikt
const message = `Hallo, ${name}! Je bent ${age} jaar oud.`;
console.log(bericht);

\--- /code ---
