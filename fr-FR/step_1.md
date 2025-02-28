Tu peux combiner du texte (chaînes de caractères) et des variables en JavaScript.

Une « chaîne de caractères » est un type de données en JavaScript et dans d'autres langages de programmation. Data types are groups of data that tell the program how we want to use data.

Tu peux formater des chaînes de caractères à l'aide de concaténations ou de modèles littéraux.

### Concaténation

Tu peux combiner des chaînes de caractères en utilisant l'opérateur `+`.

## --- code ---

language: js
filename:
line_numbers: true
-------------------------------------------------------

const superhero = "Iron Man";
const power = "armure";
// Exemple utilisant la concaténation
const description = "Le super-héros " + superhero + " possède une " + power + ".";
console.log(description);

\--- /code ---

### Modèles littéraux

Tu peux inclure le contenu des variables dans une chaîne de caractères en utilisant des guillemets obliques `` ` `` pour incorporer des variables à l'intérieur de ces symboles : `${}`.

Voici un exemple.

## --- code ---

language: js
filename:
line_numbers: true
-------------------------------------------------------

const name = "Spider-Man";
const age = 25;
// Exemple d'utilisation de modèle littéral
message const = `Bonjour ${name} ! Tu as ${age} ans.`;
console.log(message);

\--- /code ---
