# CODECRAFT_ST_O1
Manual test cases for calculator
-Addition
-substraction
-Multiplication
-Division

Includes:
-Positive and Negative numbers
-Decimal Values
-BODMAS rule
-Invalide inputs

Testcase ID:CALC_001
TEST DESCRIPTON:Verify additions of two positive numbers
PRECONDITION :Calculator is open
TEST STEPS:1.enter 10
           2.press’+’
           3.enter 20
           4.press’=’  
TEST DATA:10+20
EXPECTED RESULT:Result displayed as 30 
ACTUAL RESULT:
STATUS:

-------------------------------------------------------------------------------------------------
Testcase ID:CALC_002
TEST DESCRIPTON:Verify substraction of two numbers
PRECONDITION :Calculator is open
TEST STEPS:1.enter 10
           2.press’-’
           3.enter 20
           4.press’=’  
TEST DATA:10-20
EXPECTED RESULT:Result displayed as 10
ACTUAL RESULT:
STATUS:
-------------------------------------------------------------------------------------------------

Testcase ID:CALC_003
TEST DESCRIPTON:Verify Multiplication of two numbers
PRECONDITION :Calculator is open
TEST STEPS:1.enter 10
           2.press’x’
           3.enter 2
           4.press’=’  
TEST DATA:10x2
EXPECTED RESULT:Result displayed as 20
ACTUAL RESULT:
STATUS:

------------------------------------------------------------------------------------------------
Testcase ID:CALC_004
TEST DESCRIPTON:Verify Division of two numbers
PRECONDITION :Calculator is open
TEST STEPS:1.enter 10
           2.press’/’
           3.enter 2
           4.press’=’  
TEST DATA:10/2
EXPECTED RESULT:Result displayed as 5 
ACTUAL RESULT:
STATUS:
------------------------------------------------------------------------------------------------

Testcase ID:CALC_005
TEST DESCRIPTON:Verify Substraction with negative result 
PRECONDITION :Calculator is open
TEST STEPS:1.enter 5
           2.press’-’
           3.enter 10
           4.press’=’  
TEST DATA: 5-10
EXPECTED RESULT:Result displayed as -5
ACTUAL RESULT:
STATUS:
           
------------------------------------------------------------------------------------------------

Testcase ID:CALC_006
TEST DESCRIPTON:Verify Multiplication of negative number
PRECONDITION :Calculator is open
TEST STEPS:1.enter -5
           2.press’x’
           3.enter 4
           4.press’=’  
TEST DATA: -5x4
EXPECTED RESULT:Result displayed as -20
ACTUAL RESULT:
STATUS:
           
------------------------------------------------------------------------------------------------

Testcase ID:CALC_007
TEST DESCRIPTON:Verify division with decimal result
PRECONDITION :Calculator is open
TEST STEPS:1.enter 5
           2.press ’/ ‘
           3.enter 2
           4.press’=’
TEST DATA: 5/2
EXPECTED RESULT:Result displayed as 2.5
ACTUAL RESULT:
STATUS:                      
-----------------------------------------------------------------------------------------------       
Testcase ID:CALC_008
TEST DESCRIPTON:Verify BODMAS rule-multiplication before addition
PRECONDITION :Calculator is open
TEST STEPS:1.enter5+3x2
           2.press’=’
TEST DATA: 5+3x2
EXPECTED RESULT:Result displayed as 11
ACTUAL RESULT:
STATUS:                      

-----------------------------------------------------------------------------------------------       
Testcase ID:CALC_009
TEST DESCRIPTON:Verify brackets are evaluated first
PRECONDITION :Calculator is open
TEST STEPS:1.enter (5+3)x2
           2.press ’=’
TEST DATA:(5+3)x2
EXPECTED RESULT:Result displayed as 16
ACTUAL RESULT:
STATUS:                      

-----------------------------------------------------------------------------------------------       
Testcase ID:CALC_010
TEST DESCRIPTON:Verify calculator rejects non-numeric characters
PRECONDITION :Calculator is open
TEST STEPS:1.enter @#$%$%$
TEST DATA: @#$%$%$
EXPECTED RESULT:Calculator should not accept input
ACTUAL RESULT:
STATUS:                 

-----------------------------------------------------------------------------------------------       
Testcase ID:CALC_011
TEST DESCRIPTON:Verify division by zero
PRECONDITION :Calculator is open
TEST STEPS:1.enter 10
          2.press’/’
          3.enter 0
          4.press’=’

TEST DATA:10/0
EXPECTED RESULT:Result displayed as error
ACTUAL RESULT:
STATUS:           

-----------------------------------------------------------------------------------------------       
Testcase ID:CALC_012
TEST DESCRIPTON:Verify invalid operator sequence
PRECONDITION :Calculator is open
TEST STEPS:1.enter 10
          2.press’+’
          3.enter'-'
          4.press’=’

TEST DATA:10+-=
EXPECTED RESULT:No calculation is performed
ACTUAL RESULT:
STATUS:          
