# TEST CASES AND OUTPUT
# High Level Test Cases
| Test ID | Description | Expected Output | Actual Output |
| --------|:------------|:--------|:-----------|
| 1 | Push Button pressed | ACC mode ON | Red LED ON |
| 2 | Push Button pressed | WIPER starts | LED's ON and switching| 
| 3 | Push Button pressed | WIPER changes speed | LED's ON and switching | 
| 4 | Push Button pressed | WIPER works at high speed | LED's ON and switching |  
| 5 | Push Button pressed |ACC mode OFF | LED OFF| 


# LOW LEVEL TEST CASE
 | Test ID | Description | Exp.o/p | Actual o/p | STATUS | 
 | --------|:------------|:--------|:-----------|:-------------| 
 | 1 | Push Button --> pressed | Car starts | Red LED ON | PASS |
 | 2 | Push Button --> pressed | WIPER starts and operates at different speed | Different LED's gets ON in sequence | PASS |
 | 3 | Push Button --> pressed | Car Stops | LED OFF | PASS |

