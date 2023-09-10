# MDP REPRESENTATION

## AIM:
To represent Markov's Decision Process using a real time problem statement.

## PROBLEM STATEMENT:

### Problem Description
To develop a environment to make sure a dog reaches the food using Markov's Decision Process.

### State Space
{0,1,2,3,4,5,6,7,8}

### Sample State
5

### Action Space
1. {0} --> MOVING UP
2. {1} --> MOVING RIGHT
3. {2} --> MOVING DOWN
4. {3} --> MOVING LEFT

### Sample Action
{3}

### Reward Function
1. 1 --> Reaching the goal
2. 0 --> Otherwise

### Graphical Representation
![o9arfnxr](https://github.com/Shavedha/MDP-REPRESENTATION/assets/93427376/8f50968a-14c7-4a0f-9fcd-e48c46f801fe)


## PYTHON REPRESENTATION:
```
P = {
    0 : {
        0 : [(0.23, 0, 0.0, False)],
        1 : [(0.52, 1, 0.0, False)],
        2 : [(0.78, 3, 0.0, False)],
        3 : [(0.12, 0, 0.0, False)]
    },
    1 : {
        0 : [(0.16, 1, 0.0, False)],
        1 : [(0.35, 2, 0.0, False)],
        2 : [(0.58, 4, 0.0, False)],
        3 : [(0.29, 0, 0.0, False)]
    },
    2 : {
        0 : [(0.23, 2, 0.0, False)],
        1 : [(0.34, 2, 0.0, False)],
        2 : [(0.78, 5, 0.0, False)],
        3 : [(0.50, 0, 0.0, False)]
    },
    3 : {
        0 : [(0.23, 0, 0.0, False)],
        1 : [(0.45, Hole, 0.0, False)],
        2 : [(0.76, 8, 0.0, False)],
        3 : [(0.12, 3, 0.0, False)]
    },
    4(HOLE): {
        0 : [(0.23, Hole, 0.0, False)],
        1 : [(0.45, Hole, 0.0, False)],
        2 : [(0.76, Hole, 0.0, False)],
        3 : [(0.12, Hole, 0.0, False)]
    },
   5 : {
        0 : [(0.23, 2, 0.0, False)],
        1 : [(0.63, 5, 0.0, False)],
        2 : [(0.76, 6, 0.0, False)],
        3 : [(0.76, Hole, 0.0, False)]
    },
    6 : {
        0 : [(0.31, 2, 0.0, False)],
        1 : [(0.16, 6, 0.0, False)],
        2 : [(0.19, 6, 0.0, False)],
        3 : [(0.76, 7, 0.0, False)]
    },
    7 : {
        0 : [(0.50, 4, 0.0, False)],
        1 : [(0.45, 6, 0.0, False)],
        2 : [(0.65, 7, 0.0, False)],
        3 : [(0.89, 8, 0.0, True)]
    },
    8 : {
        0 : [(0.29, 3, 0.0, False)],
        1 : [(0.45, 7, 0.0, False)],
        2 : [(0.65, 8, 0.0, True)],
        3 : [(0.89, 8, 0.0, True)]
    }
}
    
```

## OUTPUT:
<img width="294" alt="image" src="https://github.com/Shavedha/MDP-REPRESENTATION/assets/93427376/128b2efb-14cc-46cb-8b4a-14699d26ec5a">


## RESULT:
Thus a real world problem is represented using Markov's Decision Process.

