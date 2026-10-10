# Opt Loops
Welcome to Opt Loops! This is a github as a template for developing automatic optimization loops using LLMs. 

### Loop Setup
Generally, the Loops used here follow the setup:
 |
 |
 |--- Coding Seshh
 | |
 | | Tools:
 | |- sanity check
 | |- profile
 | |- submit
 | 
 | 
 |--- benchmark
 |
 |--- validate
 |
 |--- Decision : Keep / Revert
 |
 |--- Finalize(Decision)
 | |
 | | Call finalize functions for:
 | |- benchmark
 | |- validation
 | |- profile
 | 
 |--- GlobalFinalize
 | | 
 | |- Set up Logs, manage git etc. 
 | 
 
 

