## Calculator
Implement a calculator cli

### Requirements:
* Use `argparse` https://docs.python.org/3/library/argparse.html
* Support add, subtract, multiply, divide 
* Support an optional flag -i for integer division/multiplication

#### Example syntax:
`python calc.py add 1 2` -> `3`  
`python calc.py multiply 2 4` -> `8`  
`python calc.py -i divide 5 2` -> `2`  

#### Extra credit:
How could you handle multiple operations?  
Is your code re-usable? What if the next lesson is a calculator as an API?  
How do you handle errors/invalid input? Actual extra credit for adding tests: https://docs.pytest.org/en/8.2.x/