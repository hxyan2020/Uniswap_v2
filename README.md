# Uniswap Implementation (C++)
## PoolStatus Struct and Functions
+ PoolStatus Struct
  + Defines the data structure for pool status, including the amounts of X and Y tokens in the pool.

+ addLiquidity Function
  + Adds liquidity to a pool by increasing the amounts of X and Y tokens.

+ removeLiquidity Function
  + Removes liquidity from a pool by decreasing the amounts of X and Y tokens based on a given percentage.

+ swapTokens Function
  + Swaps tokens between two pools. It takes an amount of tokens to be swapped from one pool to another and returns the output amount received.

+ calculateArbitrageProfit Function
  + Calculates the potential profit from an arbitrage transaction between two pools.

+ Main Function
  + Demonstrates the usage of the above functions by creating two pools, adding liquidity, performing a token swap, and calculating the arbitrage profit.

## How to run

1. Save the code provided in a file with a .cpp extension, such as uniswap.cpp.

2. Ensure that you have a C++ compiler installed on your system.

3. Open a terminal or command prompt and navigate to the directory where the uniswap.cpp file is located.

4. Compile the code using the C++ compiler by running the following command:

   `g++ -o uniswap uniswap.cpp`

    This will generate an executable file named uniswap in the current directory.

5. Run the compiled program by executing the following command:

   `./uniswap`

    The program will then be executed, and you will see the output on the terminal.

## Test Cases 
Test cases to stimulate user's swap transaction (e.g. Swap 100 DAI to ETH) and benchmark non-blocking calculation.

The following is the test result:
```
Pool A: X = 100, Y = 10
Pool B: X = 200, Y = 20

result:
Pool A: X = 140, Y = 15.7976
Pool B: X = 310, Y = 29.2024

Output amount: 0.8

Arbitrage profit: 0.0006
```
## Uniswap Code

    This repository contains the code for performing liquidity addition, removal, token swapping, and calculating arbitrage profit using Uniswap algorithm.

## Prerequisites

- C++ compiler (GCC recommended)

## Author
Haixiang YAN  
+65 91319481  
hxyan.2015@gmail.com

## Version History
+ v0.1
  + Initial Release
+ v0.2
  + Various bug fixes and optimizations
