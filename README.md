## Source Code

### Python
```markdown
import random

seqType = random.randint(0,8)

a = ['Blackened', 'Broken', 'Concealed', 'Dreaded', 'Fancy', 'Grand', 'Hidden', 'Mystic', 'Plentiful', 'Ravaged', 'Royal', 'Salted', 'Scorched', 'Secluded', 'Secret', 'Splenid', 'Stolen', 'Sunken', 'Sweet', 'Wrecked']
b = ["Barracuda's", "Captain's", "Dragon's", "Guild's", "Hunter's", "Kraken's", "Maiden's", "Mermaid's", "Order's", "Parrot's", "Raider's", "Sailor's", "Shark's", "Shipwreck's", "Siren's", "Storm's", "Thieve's", "Triton's", "Turtle's", "Wanderer's"]
c = ['Asylum', 'Bounty', 'Den', 'Fort', 'Gem', 'Harbor', 'Haven', 'Hideout', 'Hold', 'Jewel', 'Keep', 'Port', 'Refuge', 'Rest', 'Retreat', 'Sanctuary', 'Shelter', 'Stronghold', 'Treasure', 'Trove']
d = ['Archipelago', 'Atol', 'Bay', 'Bluffs', 'Cliffs', 'Cove', 'Crag', 'Enclave', 'Groves', 'Hollow', 'Island', 'Isle', 'Lagoon', 'Peninsula', 'Reef', 'Ridge', 'Rock', 'Sands', 'Shallows', 'Shores']
e = ['amidst the Maelstroms', 'between the Waves', 'in the Mists', 'in the Shadows', 'of a Thousand Coins', 'of Plentiful Riches', 'of Skulls ', 'of the Countless Wrecks', 'of the Cursed', 'of the Damned', 'of the Depths', 'of the Homesick', 'of the Lawless', 'of the Lost Souls', 'of the Moon', 'of the Raven', 'of the Sunset', 'of the Sweet Embrace', 'of the Tides', 'of Whispers']

r1 = random.randint(0,18)
r2 = random.randint(0,18)
r3 = random.randint(0,18)

sequences = [a[r1] + ' ' + c[r2], a[r1] + ' ' + b[r2] + ' ' + c[r3], a[r1] + ' ' + d[r2], a[r1] + ' ' + b[r2] + ' ' + d[r3], a[r1] + ' ' + c[r2] + ' ' + e[r3], b[r1] + ' ' + d[r2] + ' ' + e[r3], a[r1] + ' ' + d[r2] + ' ' + e[r3], b[r1] + ' ' + e[r2], d[r1] + ' ' + e[r2]]

sequence = (sequences[seqType])
print(sequence)
```

### Javascript
```markdown
let seqType = Math.floor(Math.random() * 9);
let a = ['Blackened', 'Broken', 'Concealed', 'Dreaded', 'Fancy', 'Grand', 'Hidden', 'Mystic', 'Plentiful', 'Ravaged', 'Royal', 'Salted', 'Scorched', 'Secluded', 'Secret', 'Splenid', 'Stolen', 'Sunken', 'Sweet', 'Wrecked'];
let b = ["Barracuda's", "Captain's", "Dragon's", "Guild's", "Hunter's", "Kraken's", "Maiden's", "Mermaid's", "Order's", "Parrot's", "Raider's", "Sailor's", "Shark's", "Shipwreck's", "Siren's", "Storm's", "Thieve's", "Triton's", "Turtle's", "Wanderer's"];
let c = ['Asylum', 'Bounty', 'Den', 'Fort', 'Gem', 'Harbor', 'Haven', 'Hideout', 'Hold', 'Jewel', 'Keep', 'Port', 'Refuge', 'Rest', 'Retreat', 'Sanctuary', 'Shelter', 'Stronghold', 'Treasure', 'Trove'];
let d = ['Archipelago', 'Atol', 'Bay', 'Bluffs', 'Cliffs', 'Cove', 'Crag', 'Enclave', 'Groves', 'Hollow', 'Island', 'Isle', 'Lagoon', 'Peninsula', 'Reef', 'Ridge', 'Rock', 'Sands', 'Shallows', 'Shores'];
let e = ['amidst the Maelstroms', 'between the Waves', 'in the Mists', 'in the Shadows', 'of a Thousand Coins', 'of Plentiful Riches', 'of Skulls ', 'of the Countless Wrecks', 'of the Cursed', 'of the Damned', 'of the Depths', 'of the Homesick', 'of the Lawless', 'of the Lost Souls', 'of the Moon', 'of the Raven', 'of the Sunset', 'of the Sweet Embrace', 'of the Tides', 'of Whispers'];
          
let r1 = Math.floor(Math.random() * 20);
let r2 = Math.floor(Math.random() * 20);
let r3 = Math.floor(Math.random() * 20);

let sequences = [a[r1] + ' ' + c[r2], a[r1] + ' ' + b[r2] + ' ' + c[r3], a[r1] + ' ' + d[r2], a[r1] + ' ' + b[r2] + ' ' + d[r3], a[r1] + ' ' + c[r2] + ' ' + e[r3], b[r1] + ' ' + d[r2] + ' ' + e[r3], a[r1] + ' ' + d[r2] + ' ' + e[r3], a[r1] + ' ' + d[r2], d[r1] + ' ' + e[r2]];


let sequence = sequences[seqType]
```
