# Wes Bos JavaScript 30 Day Challenge - Type Ahead
The function of this exercise was to generate a type ahead functionality for a search looking for city or state name matches. There's also a Pokemon by name variant generated.

Functionally, it takes fetching data, converting it into a recognised form, then putting that data into an empty array to make use of it for searching. In the city and state version, typing in letters will begin the search, finding all which match either a city or state name. Results displayed will continue changing until the typing has ceased. For the Pokemon version, the search looks only at Pokemon names as provided in data, including ones differentiated by a -1 appendation, indicating it's a regional variant Pokemon. There are 8 different generations accounted for in the Pokemon data.

City and State will return results with the name of all matches, organised as City, State, and include a population off to the far left. This population is formatted according to English standards, with a comma inserted after each third numeral from the left.

The Pokemon search returns results indicating the Pokemon's name, their International Pokedex ID #, and then their type(s) to the far right.

# Languages Used
- HTML
- CSS
- JavaScript

# Resources Used
- fuyutarow's pokemon.json data, located: https://github.com/fuyutarow/pokemon.json