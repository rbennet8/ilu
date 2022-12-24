# ilu

```
const facts = [
  "The average person spends 6 months of their lifetime waiting on a red light to turn green.",
  "The world's oldest piece of chewing gum is over 9,000 years old.",
  "A small child could swim through the veins of a blue whale.",
  "The world's largest snowflake on record was 15 inches wide and 8 inches thick.",
  "Pteronophobia is the fear of being tickled by feathers."
];
```

```
function displayFact() {
  // Select a random fact from the array
  const fact = facts[Math.floor(Math.random() * facts.length)];

  // Display the fact to the user
  document.getElementById("fact").innerHTML = fact;
}
```

```
<button onclick="displayFact()">Show me a fact!</button>
<div id="fact"></div>
```

```
body {
  font-family: Arial, sans-serif;
  text-align: center;
}

button {
  font-size: 1em;
  padding: 0.5em 1em;
  border: none;
  border-radius: 0.5em;
  background-color: #0077c9;
  color: white;
  cursor: pointer;
}

#fact {
  margin-top: 1em;
  font-size: 1.2em;
  font-weight: bold;
}
```
