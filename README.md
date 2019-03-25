# poke-train
Recognize pokemon cries

The goal is to train an ML algorithm using pokemon characteristics, and features from their cries, in order to automatically figure out which pokemon a new cry belongs to.

We would use the same format as https://pokemoncries.com/:

- A choice of 4 pokemons
- A cry
- Rate over 10 tests

### Features

The first features to consider are the ones unrelated to the cry itself:

- Pokemon types (normal, poison, fly, ...)
- Evolution level (base? first/second evolution?)
- How many evolutions does it have
- Rarity

More features can probably be extracted from the cry itself (high/low note, variation between notes, ...)
