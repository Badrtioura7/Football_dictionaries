# Football_Dictionaries
In this Project I will make three assignments to the squad list:
```python
SQUADS_DATA = [
  [
    "1",                                     # Number
    "GK",                                    # Position
    "Juan Botasso",                          # Name
    "(1908-10-23)23 October 1908 (aged 21)", # Date of Birth
    "",                                      # Caps
    "Quilmes",                               # Club
    "Argentina",                             # Country (Players Country)
    "Argentina",                             # Club Country
    "1930"                                   # Year
],

1st:
turn these players into dictionaries with the following structure:

```python
{
    'number': ...,
    'position': ...,
    'name': ...,
    'date_of_birth': ...,
    'caps': ...,
    'club': ...,
    'country': ...,
    'club_country': ...,
    'year': ...,
}
```
2nd:
This assignment is similar to the previous one, but instead of having just one big list with all the players, we're going to group them by position. Your result will look something like:
```python
{
  "GK": [{..player1..}, {..player2..}],
  "DF": [{..player1..}, {..player2..}],
  "MF": [{..player1..}, {..player2..}],
  "FW": [{..player1..}, {..player2..}],
}
```
3rd:
And finally this is really similar to the previous assignment but we're adding one more level of nesting. This function will return the players grouped by country, and per each country, grouped by position. Example:
{
  "Argentina": {
    "GK": [{..player1..}, {..player2..}],
    "DF": [{..player1..}, {..player2..}],
    "MF": [{..player1..}, {..player2..}],
    "FW": [{..player1..}, {..player2..}],
  },
  "Brazil": {
    "GK": [{..player1..}, {..player2..}],
    "DF": [{..player1..}, {..player2..}],
    "MF": [{..player1..}, {..player2..}],
    "FW": [{..player1..}, {..player2..}],
  }
}
```
