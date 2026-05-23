# round-robin-scheduler
This module creates scheduled match pairs from a list of competition participants in a round-robin format, where everyone plays everyone else exactly once.

Supports both even and odd numbers of participants.

algorithm description: https://nrich.maths.org/1443

## Development status

Working prototype ready.

## Sample input

```python
players = ['roger', 'rafa', 'novak', 'andy']
```

## Sample output

```python
[
    ['rafa - andy', 'roger - novak'],
    ['roger - andy', 'novak - rafa'],
    ['novak - andy', 'rafa - roger']
]
```
