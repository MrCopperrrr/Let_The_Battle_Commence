# Advanced Programming Assignment 1: Let the Battle Commence

Advanced Programming Assignment
 
This repository represents a solution to the "Let the Battle Commence" assignment for the Advanced Programming course. The goal is to implement a battle simulation between different character types, adhering to specific rules for combat score calculation and class structure.

## Overview

The assignment involves implementing several classes representing different characters (Knight, Warrior, Paladin, DeathEater) with varying combat abilities. The combat score of each character depends on their attributes (WP, baseHP, mana), the battleground conditions (prime or square number), and special abilities.

## Structure

The project is structured into three parts:

*   **Part A (Given Classes):** This part provides initial classes in bytecode form (`.class` files). These are mostly abstract classes and interfaces, including:
    *   `Combatable`: Interface for combat-capable entities.
    *   `Human`, `Fighter`, `Monster`: Abstract base classes.
    *   `Main`: Contains the `main` method to start the simulation.
    *   `Battle`: Simulates the battle logic and calculates fighting results.
*   **Part B (Implemented Classes):** This part requires you to implement specific classes according to the provided class diagram:
    *   `Knight`, `Warrior`, `Paladin`: Character classes with specific combat score calculations.
    *   `DeathEater`: Monster class with combat score calculation based on a complex number (mana).
*   **Part C (Free-to-Change Classes):** This part allows you to modify existing classes, specifically:
    *   `Complex`: Represents a complex number used by `DeathEater`.
    *   `TeamMaker`: Generates teams for the battle. **Note:** The implementation of this class will be replaced with test cases for grading purposes.
    *   `Utility`: Provides utility functions to check square and prime numbers.

## Key Requirements

1.  **Implement Classes in Part B:** Carefully implement the `Knight`, `Warrior`, `Paladin`, and `DeathEater` classes according to the specified logic for combat score calculation.
2.  **Handle Special Cases:** Correctly implement the special cases for combat score calculation, such as:
    *   Prime/square ground numbers affecting `Warrior` and `Knight` combat scores.
    *   `Paladin` exceeding 999 combat score based on Fibonacci numbers.
    *   `DeathEater` combat score calculated from the magnitude of a complex number.
3.  **Modify Classes in Part C (if needed):** Adapt the provided `Complex` class to work with the `DeathEater` class. You can also modify `TeamMaker`.
4.  **Follow the Class Diagram:** Adhere strictly to the provided class diagram in Figure 1.
5.  **Place Classes in Default Package:** Ensure that all your classes are placed in the default (root) package.



## Notes

*   The `TeamMaker` class is provided with dummy code and can be changed to adapt the requirement. However, its implementation will be replaced during testing.  Focus on the logic of the combat simulation.
*   All classes should be placed in the default (root) package.
