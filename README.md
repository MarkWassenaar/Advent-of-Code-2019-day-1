# Advent of Code 2019 - Day 1

## Part 1

### Plan:

1. Calculate the fuel per module.
2. Run the calculation over the entire array of modules.
3. Show the result.

### Blocks:

1. I had to look up the best way to round down. I found that `Math.floor` did the trick just perfectly and used it.
2. I wanted to use a `for` loop first to go through the array, but I remembered the better method of `reduce`. I had to look up the syntax for this before using it.

## Part 2

### Plan:

1. Add a function with a loop that keeps adding the fuel requirements for the fuel.
2. I'm using the `calculateFuel` function to calculate the formula over the extra fuel needed.
3. If the extra fuel needed is bigger than 0, it runs again and keeps adding the additional fuel to the total fuel.
4. I use the new `calculateTotalFuel` function in the `totalFuelRequirement` function to calculate the total fuel.

### Blocks:

1. I used an `if` statement instead of a `while` statement first. But then remembered after testing that the `if` statement doesn’t loop without the `for` loop. I found online that the `while` statement works perfectly for this.
