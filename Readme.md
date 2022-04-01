SDLC ACTIVITY BASED LEARNING

PROJECT : ONLINE BANK MANAGEMENT SYSTEM

 |   Build   |  Code Quality  | Unity  | Git Inspector |
 |-----------|----------------|--------|---------------|
 |[![C/C++ CI - Build Status](https://github.com/saipoor/miniproject/actions/workflows/c-cpp.yml/badge.svg)](https://github.com/saipoor/miniproject/actions/workflows/c-cpp.yml)|[![Code Quality - Static Code - Cppcheck](https://github.com/saipoor/miniproject/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/saipoor/miniproject/actions/workflows/cppcheck.yml)[![CodeQuality Dynamic Code Analysis Valgrind](https://github.com/saipoor/miniproject/actions/workflows/CodeQuality_Dynamic.yml/badge.svg)](https://github.com/saipoor/miniproject/actions/workflows/CodeQuality_Dynamic.yml)[![CI-Coverage](https://github.com/saipoor/miniproject/actions/workflows/gcov.yml/badge.svg)](https://github.com/saipoor/miniproject/actions/workflows/gcov.yml)[![Codacy Badge](https://app.codacy.com/project/badge/Grade/adfe65efd9e640f9ab16df06250890e8)](https://www.codacy.com/gh/saipoor/miniproject/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=saipoor/miniproject&amp;utm_campaign=Badge_Grade) |[![Unit Testing - Unity](https://github.com/saipoor/miniproject/actions/workflows/unity.yml/badge.svg)](https://github.com/saipoor/miniproject/actions/workflows/unity.yml)|[![Contribution Check - Git Inspector](https://github.com/saipoor/miniproject/actions/workflows/gitinspector.yml/badge.svg)](https://github.com/saipoor/miniproject/actions/workflows/gitinspector.yml)

FOLDER STRUCTURE:
  |       Folder        |            Description                         |
  |:--------------------|:-----------------------------------------------|
  |1.Requirements       |Documents detailing requirements and research   |
  |2.Design             |Documents specifying design details             |
  |3.implementation     |All code and documentation                      |
  |4.Testplan           |Documents with test plans and procedures        |
  
Contributors List and Summary:
|SF Id.|Name|Features|Issuess Raised|Issues Resolved|No. of TestCases|Test Case|
|:-----|:---|:-------|:-------------|:--------------|:-----------|:--------|
|261623|poornima| F_1,F_2,F_3|	0|0|1|pass|

 |Feature Id	|Feature|
 |--------------|-------|
|F_1	|Option to load older saved data|
|F_2	|Save data to file if only new data is added|
|F_3	|New records gets saved in file at program shut down|

Challenges Faced:
|No.|	Challenge	|Solution|
|---|---------------|--------|
|1.|gcov generating *.gcda and *.gcno files in different directory than object file|added  steps in make file under coverage  and ran coverage then deleted all the unnecessary files.|
|2.|After program shutdown, not able to recover recorded data.|To solve problem file system is implemented|

Learning Resources:
 1. markdownBasics
 2. git inspector
 3. github workflow
 4. markdown cheatsheet
