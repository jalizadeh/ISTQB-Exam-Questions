# Exam Questions : Chapter 04 Plus (with details)


### Question 1
Count Statement coverage and Decision coverage for the following scneario.

```
1. Pick up and read the newspaper
2. Look at what is on television
3. If there is a program that you are interested in watching then switch the television on and watch the program
4. Otherwise
5. Continue reading the newspaper
6. If there is a crossword in the newspaper then try and complete the crossword
```

To calculate statement coverage, we need to determine the percentage of statements that are executed during testing. In this case, all six statements are executed, so the statement coverage is 100%.

To calculate decision coverage, we need to determine the percentage of decision points that are executed during testing. A decision point is a point in the code where the program can take different paths depending on a condition. In this case, there are two decision points:

1. The decision to switch the television on and watch the program
2. The decision to try and complete the crossword

To achieve 100% decision coverage, we need to ensure that both decision points are executed for all possible outcomes. In this case, there are four possible outcomes:

1. There is a program that you are interested in watching, and there is a crossword in the newspaper
2. There is a program that you are interested in watching, but there is no crossword in the newspaper
3. There is no program that you are interested in watching, but there is a crossword in the newspaper
4. There is no program that you are interested in watching, and there is no crossword in the newspaper

If we test all four possible outcomes, we can achieve 100% decision coverage. Alternatively, we can use a decision table to ensure that all possible combinations of conditions are tested. For example:

| Program of interest | Crossword | Expected outcome |
| -- | -- | -- |
| Yes | Yes | Switch on TV |
| Yes | No | Switch on TV |
| No | Yes | Complete crossword |
| No | No | Continue reading newspaper |

By testing all four combinations, we can achieve 100% decision coverage.

**How many test cases i need for 100% statement coverage and decision coverage?**

To achieve 100% statement coverage, we need to ensure that every statement in the code is executed at least once during testing. From the scenario given, there are six statements. Therefore, we need a minimum of six test cases to achieve 100% statement coverage. Each test case should cover a different path through the code to ensure that all statements are executed at least once.

To achieve 100% decision coverage, we need to ensure that every possible outcome of every decision point in the code is executed during testing. From the scenario given, there are two decision points. Therefore, we need to test all possible outcomes of both decision points to achieve 100% decision coverage.

The first decision point is "If there is a program that you are interested in watching then switch the television on and watch the program; otherwise, continue reading the newspaper". This decision point has two possible outcomes: either the program is watched on TV or the newspaper is read. Therefore, we need to test both outcomes.

The second decision point is "If there is a crossword in the newspaper then try and complete the crossword". This decision point has two possible outcomes: either the crossword is completed or it is not. Therefore, we need to test both outcomes.

Combining the outcomes of both decision points gives us a total of four possible outcomes, which we need to test to achieve 100% decision coverage. We can design test cases to cover each of these outcomes, as shown below:

1. There is a program that you are interested in watching, and there is a crossword in the newspaper.
2. There is a program that you are interested in watching, but there is no crossword in the newspaper.
3. There is no program that you are interested in watching, but there is a crossword in the newspaper.
4. There is no program that you are interested in watching, and there is no crossword in the newspaper.

Therefore, we need a minimum of four test cases to achieve 100% decision coverage in this scenario. However, it's important to note that this assumes that each test case is designed to cover a unique path through the code. If multiple test cases cover the same path, we may need additional test cases to achieve complete coverage.