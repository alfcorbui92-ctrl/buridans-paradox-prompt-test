# Donkey Rationality Prompt Project

This project is a prompt engineering case study about reasoning errors in language models.

## Goal
The goal is to test whether a model can correctly analyze a scenario similar to the Buridans Paradox, detect the difference or fall into a pattern-matching bias.

## Scenario
Donkey is equally thirsty and hungry and finds two locked chests:
- a golden chest labeled "Only drinks"
- a silver chest labeled "Only food"
Same as the Buridan Paradox but the silver chest has a key inserted, which makes it the only chest that can potentially be opened.

## What this project tests
This project tests whether the model can identify that:
- both chests are locked
- only the silver chest has a key inserted
- the golden chest is inaccessible
- this is not a true Buridan's paradox case

## Main finding
Some models ignore the accessibility constraint and focus only on the food-versus-drink dilemma.
