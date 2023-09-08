# Uniswap

PoolStatus Struct: Defines the data structure for pool status, including the amounts of X and Y tokens in the pool.

addLiquidity Function: Adds liquidity to a pool by increasing the amounts of X and Y tokens.

removeLiquidity Function: Removes liquidity from a pool by decreasing the amounts of X and Y tokens based on a given percentage.

swapTokens Function: Swaps tokens between two pools. It takes an amount of tokens to be swapped from one pool to another and returns the output amount received.

calculateArbitrageProfit Function: Calculates the potential profit from an arbitrage transaction between two pools.

Main Function: Demonstrates the usage of the above functions by creating two pools, adding liquidity, performing a token swap, and calculating the arbitrage profit.

# How to run

-Save the code provided in a file with a .cpp extension, such as uniswap.cpp.

-Ensure that you have a C++ compiler installed on your system.

-Open a terminal or command prompt and navigate to the directory where the uniswap.cpp file is located.

-Compile the code using the C++ compiler by running the following command:

`g++ -o uniswap uniswap.cpp`

    This will generate an executable file named uniswap in the current directory.

-Run the compiled program by executing the following command:

`./uniswap`

    The program will then be executed, and you will see the output on the terminal.

# Uniswap Code

    This repository contains the code for performing liquidity addition, removal, token swapping, and calculating arbitrage profit using Uniswap algorithm.

## Prerequisites

- C++ compiler (GCC recommended)

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/silverspoon19931120/uniswap.git
