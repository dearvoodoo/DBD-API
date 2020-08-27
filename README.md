## Welcome to DBD - API Documentation

You can easily use Queries in url to retrieve specific information.  
ex: `https://dbd-api.herokuapp.com/perks?role=Survivor&lang=en`

API available in English and French.  
Choose language with query `lang=en` or `lang=fr`

### Get perks
```php
GET https://dbd-api.herokuapp.com/perks
```
```json
[
  {
    "_id": "5f46d9afa3777022ec626077",
    "role": "Survivor",
    "name": "Meg Thomas",
    "name_tag": "MT",
    "perk_name": "Quick & Quiet",
    "perk_tag": "QuickQuiet",
    "description": "You do not make as much noise as others when quickly vaulting over obstacles or hiding in Lockers. The vault and hide actions' noise detection and audio range is reduced by 100 %. Quick & Quiet can only be triggered once every 30/25/20 seconds.",
    "teach_level": 30,
    "is_ptb": false,
    "lang": "en",
    "icon": "https://raw.githubusercontent.com/dearvoodoo/dbd/master/Perks/QuickQuiet.png"
  },
  {
    "_id": "5f46d9afa3777022ec626078",
    "role": "Survivor",
    "name": "Meg Thomas",
    "name_tag": "MT",
    "perk_name": "Sprint Burst",
    "perk_tag": "SprintBurst",
    "description": "When starting to run, break into a sprint at 150 % of your normal running speed for a maximum of 3 seconds. Causes the Exhausted Status Effect for 60/50/40 seconds. Sprint Burst cannot be used while Exhausted. You do not recover from Exhaustion while running.",
    "teach_level": 35,
    "is_ptb": false,
    "lang": "en",
    "icon": "https://raw.githubusercontent.com/dearvoodoo/dbd/master/Perks/SprintBurst.png"
  },
  ...
 ]
```

### Killers
```php
GET https://dbd-api.herokuapp.com/killers
```
```json

  {
    "_id": "5f4706f2a3777022ec6261b3",
    "name": "Trapper",
    "name_tag": "TR",
    "full_name": "Evan MacMillan",
    "alias": "Chuckles",
    "gender": "Male",
    "nationality": "American",
    "realm": "The MacMillan Estate",
    "power": "Bear Trap",
    "weapon": "The Cleaver",
    "speed": "115 % | 4.6 m/s",
    "terror_radius": "32",
    "height": "Tall",
    "voice_actor": "Filip Ivanovic",
    "difficulty": "Easy",
    "overview": "The Trapper is an area-control Killer, able to apply pressure across the Map by placing deadly Bear Traps for Survivors to step into.His personal Perks, Unnerving Presence, Brutal Strength, and Agitation, allow him to chase and carry Survivors more effectively.He is focused on physical attributes and making use of his strength and the Survivors' fear.",
    "lore": "Evan MacMillan idolised his father. It wasn't just that he was heir to a great fortune, it was the way he ran the estate. Raised under his firm hand, Evan had taken to running the workforce with an iron hand. Production was always high and the MacMillan Estate prospered under father and son.\n\nAs Archie MacMillan's mental health slowly disintegrated, Evan protected him from the herd who wanted a piece of the fortune. No matter what his father asked of him, Evan would do.\n\nWhen Archie MacMillan finally snapped, Evan became his enforcer in what would become known as the worst mass murder in modern history. They never proved that Evan lead over a hundred men into those dark tunnels before detonating the explosives and sealing them to their fate.The tale of the MacMillan Estate is a tale of wealth and power gone very wrong.\n\nHow many victims fell to the hands of father and son is unknown. No record is ever made of what became of Evan MacMillan. His father is another unsolved puzzle, found trapped in the locked basement of his own warehouse - starved and abandoned.",
    "dlc": "Base Game",
    "dlc_id": 381210,
    "is_free": true,
    "is_ptb": false,
    "lang": "en",
    "icon": {
      "portrait": "https://raw.githubusercontent.com/dearvoodoo/dbd/master/Killers/Portrait/TR.png",
      "preview_portrait": "https://raw.githubusercontent.com/dearvoodoo/dbd/master/Killers/PreviewPortrait/TR.png",
      "shop_background": "https://raw.githubusercontent.com/dearvoodoo/dbd/master/Killers/ShopBG/TR.png"
    }
  },
  ...
]
```

### Survivors
```php
GET https://dbd-api.herokuapp.com/survivors
```
```json
[
  {
    "_id": "5f46a992a3777022ec625f24",
    "name": "Dwight Fairfield",
    "full_name": null,
    "name_tag": "DF",
    "gender": "Male",
    "role": "Nervous Leader",
    "nationality": "American",
    "voice_actor": "Ian Chuprun",
    "overview": "Dwight Fairfield is a nervous Leader, able to locate his allies and increase their effectiveness.\r\n\r\nHis personal Perks, Bond, Prove Thyself, and Leader, allow him to get in proximity of other Survivors and provide bonuses to their actions as well as his own.\r\n\r\nHe is skilled at finding others and working as a group. His Perks help him and others by keeping them together and alive.",
    "lore": "Dwight was geeky and scrawny through high school. He always wanted to be one of the cool kids, but somehow never had the charisma. He tried out for the football team but was cut, the basketball team didn't even take a look, and his grades were distinctly below average. One weekend, on a team-building exercise from his dead-end job, Dwight's boss led them deep into the woods before breaking out his family recipe moonshine. Dwight remembered taking the first sip before waking up late the next morning all alone. During the night, the others had abandoned him. Once again, the laughing stock of the community Dwight tried to hike his way out of the woods. That was the last anyone ever heard of Dwight Fairfield.\r\n\r\nDwight isn't the typical guy you think of when someone says \"Survivor\". He lacks that certain pizzazz and without his glasses, he's more or less blind. But as the sun sets and the woods come alive, Dwight clasps to his rat race life, making sure that he'll live to see another day even though something unimaginable is after him. Dwight won't stop. He'll survive no matter what. As others spent hours being seen in high school. He spent hours becoming invisible and avoiding danger. And it doesn't matter if it's dangers in the hallway or dangers in the woods. Survival is key. As other employees panic when terror infects them, Dwight makes use of his disturbing teen experience. The tables have now turned and now others need to follow to Dwight's firm directions if they are to survive as he knows how to disappear.",
    "difficulty": "Easy",
    "dlc": "Base Game",
    "dlc_id": 381210,
    "is_free": true,
    "is_ptb": false,
    "lang": "en",
    "icon": {
      "portrait": "https://raw.githubusercontent.com/dearvoodoo/dbd/master/Killers/Portrait/DF.png",
      "preview_portrait": "https://raw.githubusercontent.com/dearvoodoo/dbd/master/Killers/PreviewPortrait/DF.png",
      "shop_background": "https://raw.githubusercontent.com/dearvoodoo/dbd/master/Killers/ShopBG/DF.png"
    }
  },
  ...
]
```
