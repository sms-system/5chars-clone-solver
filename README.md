# 5chars-clone-solver
CLI Bot-Solver for https://kaskar2008-experiments.github.io/5chars/dist/

# Instruction:

Run solver via `node index.js`
Bot will show you next guess

Answer on this guess, with next rules:
- Letters on known positions must be capitalized
- Correct letters, but on unknown positions must be lowercased
- Invalid letters can be replaced by space or `.` or `-` or `_`

If the guessed word has been solved, you can continue the new guessing by simply pressing `Enter`

# Example
```
> node index.js
ВАРКА
...к.
КОСОК
ко.оК
ОБЛИК
```

The guessed word was solved on the 3rd attempt
