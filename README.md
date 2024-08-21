# Degrees
Program determining how many “degrees of separation” apart two actors are.

## Instructions
1. Download this repository to your device.
2. Open a terminal or command prompt.
3. Navigate to the directory where you downloaded the repository.
4. Run the degrees.py file with Python 3 to start the game

```bash
python degrees.py
```

6. Follow the prompts by typing in names of actors 

## Background
According to the Six Degrees of Kevin Bacon game, anyone in the Hollywood film industry can be connected to Kevin Bacon within six steps, where each step consists of finding a film that two actors both starred in.
This program finds the shortest path between any two actors by choosing a sequence of movies that connects them. The programme searches through an enormous database, containing approximately 1,050,000 Actors and 350,000 Movies.
This can be framed as a search problem: our states are people; actions are movies (taking us from one actor to another); initial state and goal state are defined by the two people we’re trying to connect. By using breadth-first search, we can find the shortest path from one actor to another.
