![OWNER Facebook](https://i.imgur.com/jbYlZ5L.jpeg)

# Installation

You can install `Rahad-pinterest-dl` using npm:

```bash
npm install Rahad-pinterest-dl
```

## Features

* [Pinterest](#pinterest)
* [Genshin Character Info](#genshinCH)

## Pinterest <a name="pinterest"></a>

```js
const { pinterestdl } = require('Rahad-pinterest-dl');

(async () => {
  console.log(await pinterestdl('https://in.pinterest.com/pin/617204323960160868/'));
})();
```
_You can use [pin.it](https://pin.it) and [in.pinterest.com](https://in.pinterest.com) URLs._

#### Output
```json
{
   "ironman":{
      "url":"https://i.pinimg.com/736x/11/3a/4a/113a4af38e8eae9b500457071986782e.jpg",
      "title":"(Title)",
      "type":"image",
      "Creator":"Mohammad Rahad",
      "description":" about information"
   }
}
```

------

## Genshin Character Info <a name="genshinCH"></a>

```js
const { genshinCH } = require('Rahad-pinterest-dl');

(async () => {
  const characterDetails = await genshinCH('furina');// Genshin Impact Character names
  console.log(characterDetails);
})();
```
#### Output
```js
{
   "name":"Furina",
   "title":"Endless Solo of Solitude",
   "vision":"Hydro",
   "weapon":"Sword",
   "gender":"Female",
   "nation":"Fontaine",
   "affiliation":"Court of Fontaine",
   "rarity":5,
   "release":"2023-11-08",
   "constellation":"Animula Choragi",
   "birthday":"0000-10-13",
   "description":"The absolute focus of the stage of judgment, until the final applause sounds."}
//and more...
```
-----

### Coming Soon

This package is under development, and many exciting features are planned for future releases. Stay tuned for updates and enhancements!

## Contributing

We welcome contributions! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request. If you want to contact me, check my [GitHub profile](https://github.com/MR-RAHAD-511).

Copyright © 2024 Mohammad Rahad