# Yahtzee Cheater's Companion 🎲

## Description

Every Sunday, you find yourself engaged in a heated game of Yams (Yahtzee) with your grandmother. In pursuit of victory, you've decided to gain a little extra edge by developing a software tool that calculates the chances of obtaining a specific combination on the next dice roll.

## Combinations

The software supports the following combinations:

- **Pair:** At least 2 dice of the same value.
- **Three-of-a-kind:** At least 3 dice of the same value.
- **Four-of-a-kind:** At least 4 dice of the same value.
- **Full House:** One pair and one three-of-a-kind.
- **Straight:** 5 dice of sequential value.
- **Yahtzee/Yams:** 5 dice of the same value.


## How to Use

1. Clone the repository to your local machine.
2. Run the software and input the desired combination.
3. Receive the calculated chances for obtaining that combination on the next roll.

## Usage

```bash
    USAGE
        ./201yams d1 d2 d3 d4 d5 c
    
    DESCRIPTION
        
        d1 value of the first die (0 if not thrown)
        d2 value of the second die (0 if not thrown)
        d3 value of the third die (0 if not thrown)
        d4 value of the fourth die (0 if not thrown)
        d5 value of the fifth die (0 if not thrown)
        c expected combination
```

## Example

```bash
./201yams 1 2 4 4 3 yams_4
>> Chances to get a 4 yams: 0.46%
```

## {E} Result:

![Barre de progression](https://progress-bar.dev/75/?title=Complet&color=4CAF50)
