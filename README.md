# Kaomojis


A curated JSON list of kaomojis for reuse. Use the `kaomojis.json` file directly in your projects.


Website: https://kaomojisymbols.com


## Contents
- `kaomojis.json` — list of kaomojis with id, kaomoji, description, and tags.


## How to use
- Download or fetch the `kaomojis.json` file and parse it in your app.


Example (JavaScript):


```js
fetch('https://raw.githubusercontent.com/<your-username>/<repo-name>/main/kaomojis.json')
.then(r => r.json())
.then(data => console.log(data));
