# Task 01 – Test Cases for Calculator Application  

# Application Under Test (AUT)  
A simple calculator that performs addition, subtraction, multiplication, and division operations.  

# Objective  
To verify that the calculator performs all operations correctly with valid and invalid inputs.  

# Test Cases  

# Test Case 1
- **Test Case ID**: TC_CALC_001
- **Description**: Verify addition of two positive integers.
- **Precondition**: Calculator is open.
- **Test Steps**:  
  1. Enter 5.  
  2. Press +.  
  3. Enter 10.  
  4. Press =.  
- **Expected Result**: Output should be 15.

# Test Case 2
- **Test Case ID**: TC_CALC_002
- **Description**: Verify subtraction with negative result.
- **Precondition**: Calculator is open.
- **Test Steps**:  
  1. Enter 5.  
  2. Press -.  
  3. Enter 10.  
  4. Press =.  
- **Expected Result**: Output should be -5.

# Test Case 3
- **Test Case ID**: TC_CALC_003
- **Description**: Verify multiplication with decimals.
- **Steps**: Enter 2.5 × 4.  
- **Expected Result**: 10.

# Test Case 4
- **Test Case ID**: TC_CALC_004
- **Description**: Division by zero.  
- **Steps**: Enter 10 ÷ 0.  
- **Expected Result**: Error message or Infinity (depending on implementation).  

# Test Case 5
- **Test Case ID**: TC_CALC_005
- **Description**: Invalid input (non-numeric).  
- **Steps**: Enter “abc” and press +.  
- **Expected Result**: Error message.
 
  
