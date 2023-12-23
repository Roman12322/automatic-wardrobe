# Automatic-wardrobe

## Task description

Goal: create environment to fit our model using primitive math model.

## Environment

### Introduction

As for beginning, we should denote that will be a simplified math-model of wardrobe robot without complex parameters such as gravity and so on.

### Mechanics 
First step: denote our agent - it's gonna be a hanger that moves forward/backwards, right/left. Thus, we have 4 possible actions to make for out agent.
Second step: denote mechanincs of out environment. Firstly, our environment is a track that have multiple ways (not a circle). Secondly, our constraints are:
*    max hanger's speed = 1-2 m/s;
*    min hanger's speed = 0 m/s;
*    max hanger's weight = 25 kilo;
*    min hanger's weight = 150 gramms;
